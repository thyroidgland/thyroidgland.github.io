---
layout: default
---
<div id="homepage--body">
	<div class="row clearfix">
		{% for label in site.data.labels %}
		<div class="full column set-project">
			<h2 class="set-title">{{label.title}}</h2>
			<div class="row clearfix">
				<div class="full">
					<img class="set-preview" src="{{ label.img1 }}" alt="">
				</div>
			</div>
			<div>
				<a href="{{label.download}}"><p class="download-button">DOWNLOAD</p></a>
			</div>
		</div>
		{% endfor %}
	</div>
</div>
