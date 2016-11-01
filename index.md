---
layout: home
title: Home
landing-title: Cresca Group
description: Learn, Grow &amp; Share
image: /assets/images/Logo_Master_White_Big.png
author: The Cresca Group
nav-menu:
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<header class="major">
			<img src="{{ page.image }}" alt="{{ page.landing-title }}">
		</header>
		<div class="content">
			<p class="banner-desc" style="text-transform: uppercase;">{{ page.description }}</p>
			<ul class="actions">
				<li><a href="#contact" class="button next scrolly">Get Started</a></li>
			</ul>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one" class="tiles">
	<article>
			<span class="image">
					<img src="assets/images/pic01.jpg" alt="" />
			</span>
			<header class="major">
					<h3><a href="about.html" class="link">About Us</a></h3>
					<p>OUR MISSION, VISION &amp; VALUES</p>
			</header>
	</article>
	<article>
			<span class="image">
					<img src="assets/images/pic04.jpg" alt="" />
			</span>
			<header class="major">
					<h3><a href="opportunities.html" class="link">Opportunities</a></h3>
					<p>BECOME A CRESCATEER</p>
			</header>
	</article>
	<article>
			<span class="image">
					<img src="assets/images/pic02.jpg" alt="" />
			</span>
			<header class="major">
					<h3><a href="services.html" class="link">Services</a></h3>
					<p>DEVELOPING CLIENT SUCCESS</p>
			</header>
	</article>
	<article>
			<span class="image">
					<img src="assets/images/pic05.jpg" alt="" />
			</span>
			<header class="major">
					<h3><a href="studies.html" class="link">Case Studies</a></h3>
					<p>CHALLENGES, SOLUTIONS &amp; RESULTS</p>
			</header>
	</article>
	<article>
			<span class="image">
					<img src="assets/images/pic06.jpg" alt="" />
			</span>
			<header class="major">
					<h3><a href="https://learngrowandshare.com/" class="link">Blog</a></h3>
					<p>Learn, Grow &amp; Share</p>
			</header>
	</article>
	<article>
			<span class="image">
					<img src="assets/images/pic03.jpg" alt="" />
			</span>
			<header class="major">
					<h3><a href="team.html" class="link">Team</a></h3>
					<p>MEET THE CRESCATEERS</p>
			</header>
	</article>
</section>

</div>

<!-- Contact -->
<section id="contact">
	<div class="inner">
		<section>
			<form action="https://formspree.io/{{ site.email }}" method="POST">
				<div class="field half first">
					<label for="name">Name</label>
					<input type="text" name="name" id="name" />
				</div>
				<div class="field half">
					<label for="email">Email</label>
					<input type="text" name="_replyto" id="email" />
				</div>
				<div class="field">
					<label for="message">Message</label>
					<textarea name="message" id="message" rows="6"></textarea>
				</div>
				<ul class="actions">
					<li><input type="submit" value="Send Message" class="special" /></li>
					<li><input type="reset" value="Clear" /></li>
				</ul>
			</form>
		</section>
		<section class="split">
			<section>
				<div class="contact-method">
					<p>
						Thank you for reaching out to us. Please fill out this form, and we will reply as soon as possible.
					</p>
				</div>
			</section>
			<section>
				<div class="contact-method">
					<span class="icon alt fa-phone"></span>
					<h3>Phone</h3>
					<span>{{ site.phone }}</span>
				</div>
			</section>
			<section>
				<div class="contact-method">
					<span class="icon alt fa-home"></span>
					<h3>Address</h3>
					<span>{{ site.street_address }}<br />
					{{ site.city }}, {{ site.state }} {{ site.zip_code }}<br />
					{{ site.country }}</span>
				</div>
			</section>
		</section>
	</div>
</section>
