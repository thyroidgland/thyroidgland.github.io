---
layout: default
---
<div id="homepage--body">
	<div class="row clearfix">
		<div class="full column">
			<p class="callout">All overlays are set up at 1920x1080. All you have to do is import each image. If necessary just resize the down to 1280x720, perfect scalability. If you have a specific game you'd like to see here please contact me at <a href="mailto:thyroidgland.twitch@gmail.com" target="_blank">thyroidgland.twitch@gmail.com</a></p>
		</div>
	</div>
	<div class="row clearfix">
		{% for overlay in site.data.overlays %}
		<div class="full column set-project">
			<h2 class="set-title">{{overlay.title}}</h2>
			<div class="row clearfix">
				<div class="full">
					<img class="set-preview" src="{{ overlay.img1 }}" alt="">
				</div>
			</div>
			<div>
				<a href="{{overlay.download}}"><p class="download-button">DOWNLOAD</p></a>
			</div>
		</div>
		{% endfor %}
	</div>
</div>
