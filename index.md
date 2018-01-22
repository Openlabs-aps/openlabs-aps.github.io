---
layout: default
---

<!-- FEATURE Section-->
<section>

	<header class="major">
		<h2>Features</h2>
	</header>

	<div class="features">

		<article>
			<span class="icon fa-diamond"></span>
			<div class="content">
				<h3>Commons</h3>
				<p>TODO: quacosa su beni comuni, creative commons, etc... Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>


		<article>
			<span class="icon fa-paper-plane"></span>
			<div class="content">
				<h3>Condivisione</h3>
				<p>TODO: Il sapere è di tutti. Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>


		<article>
			<span class="icon fa-rocket"></span>
			<div class="content">
				<h3>Le 4 liberta</h3>
				<p>TODO: Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>


		<article>
			<span class="icon fa-signal"></span>
			<div class="content">
				<h3>Cittadinanza digitale</h3>
				<p>TODO: qualcosa su consapevolezza uso critico. Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>

	</div>
</section>




<!-- POSTS Section -->
<section>
	<header class="major">
		<h2>Posts</h2>
	</header>
	<div class="posts">

	{% for post in site.posts%}

	<article>
		<a href="{{site.baseurl}}{{post.url}}" class="image"><img src="assets/images/{{post.image}}" alt="" /></a>
		<h3><a href="{{site.baseurl}}{{post.url}}">{{ post.title }}</a></h3>
		{{ post.excerpt}}
		<ul class="actions">
			<li><a href="{{site.baseurl}}{{post.url}}" class="button">More</a></li>
		</ul>
	</article>

	{% endfor %}


	<!--
		<article>
			<a href="#" class="image"><img src="assets/images/pic01.jpg" alt="" /></a>
			<h3>Interdum aenean</h3>
			<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			<ul class="actions">
				<li><a href="#" class="button">More</a></li>
			</ul>
		</article>



		<article>
			<a href="#" class="image"><img src="assets/images/pic02.jpg" alt="" /></a>
			<h3>Nulla amet dolore</h3>
			<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			<ul class="actions">
				<li><a href="#" class="button">More</a></li>
			</ul>
		</article>



		<article>
			<a href="#" class="image"><img src="assets/images/pic03.jpg" alt="" /></a>
			<h3>Tempus ullamcorper</h3>
			<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			<ul class="actions">
				<li><a href="#" class="button">More</a></li>
			</ul>
		</article>



		<article>
			<a href="#" class="image"><img src="assets/images/pic04.jpg" alt="" /></a>
			<h3>Sed etiam facilis</h3>
			<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			<ul class="actions">
				<li><a href="#" class="button">More</a></li>
			</ul>
		</article>



		<article>
			<a href="#" class="image"><img src="assets/images/pic05.jpg" alt="" /></a>
			<h3>Feugiat lorem aenean</h3>
			<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			<ul class="actions">
				<li><a href="#" class="button">More</a></li>
			</ul>
		</article>



		<article>
			<a href="#" class="image"><img src="assets/images/pic06.jpg" alt="" /></a>
			<h3>Amet varius aliquam</h3>
			<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			<ul class="actions">
				<li><a href="#" class="button">More</a></li>
			</ul>
		</article>
-->


	</div>
</section>
