---
layout: archive
permalink: /about
title: "About"
---

<html lang="en">
<link rel="stylesheet" href="/css/about.css"/>
	<body id="top">
		<!-- Header -->
		<header id="header">
			<div class="inner">
				<a href="/images/bio-photo.jpg" class="image avatar"><img src="/images/bio-photo.jpg"></a>
				<h1><strong>My name is Kristen</strong>, and I'm a<br />
					Software Engineer located in Fayetteville, Ar. <br />
					I'm currently working at <a >Varsity Tutors</a>.
				</h1>
			</div>
		</header>
		<!-- Main -->
		<div id="main">
			<section id="one">
				<header class="major">
					<h2>Hello!</h2>
				</header>
				<p>Thanks for checking out my portfolio. I'm a 23-year-old programmer currently thriving in downtown
					Fayetteville, Ar. I'm a proud alum of <a href="">University of Arkansas</a> where I 
					received my Bachelor's Degree in Computer Engineering. When I'm not at <a href="">Workiva</a>, I work as
					a freelance <a id="freelance" href="freelance.html">photographer/videographer</a>. I'm also what some would call
					a "music nerd" and enjoy playing a variety of instruments and rocking the <i>occasional</i> karaoke session.
				</p>
				<p>For a closer look at the professional work I've done, check out my resume below. If you're interested in reaching out to me, feel free to <a href="mailto:Kris@kristensiearrablanks.com">contact me</a>. Cheers!</p>
			</section>
			<section id="two">
				<header class="major">
					<h2>Work Experience</h2>
				</header>
				</ul>
				<ul class="actions">
					<li><a id="download" href="" class="button icon fa-download">Download Resume</a></li>
				</ul>
			</section>
			<section id="three">
				<header class="major">
					<h2>Skills</h2>
				</header>
				<div class="box alt">
					<div class="row 50% uniform">
						<div class="4u"><a href="https://www.dartlang.org/"><span class="image fit"><img src="images/thumbs/dart.jpg" alt="Dart"></span></a></div>
						<div class="4u"><a href="https://www.python.org/"><span class="image fit"><img src="images/thumbs/python.jpg" alt="Python"></span></a></div>
						<div class="4u$"><a href="https://facebook.github.io/react/"><span class="image fit"><img src="images/thumbs/react.jpg" alt="React"></span></a></div>
						<div class="4u"><a href="https://www.w3schools.com/html/"><span class="image fit"><img src="images/thumbs/html.jpg" alt="HTML"></span></a></div>
						<div class="4u"><a href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3"><span class="image fit"><img src="images/thumbs/css.jpg" alt="CSS"></span></a></div>
						<div class="4u$"><a href="https://www.javascript.com/"><span class="image fit"><img src="images/thumbs/js.jpg" alt="Javascript"></span></a></div>
					</div>
				</div>
			</section>
			<section id="four">
				<a id="blog"><h2>Blog</h2></a>
			</section>
			<section id="five">
				<h2>Get In Touch</h2>
				<p>If you have any questions or potential career opportunities, please feel free to contact me using this form.</p>
				<div class="row">
					<div class="8u 12u$(small)">
						<div class="row uniform 50%">
							<div class="6u 12u$(xsmall)"><input type="text" name="name" id="name" placeholder="Name" /></div>
							<div class="6u$ 12u$(xsmall)"><input type="email" name="email" id="email" placeholder="Email" /></div>
							<div class="12u$"><textarea name="message" id="message" placeholder="Message" rows="4"></textarea></div>
						</div>
						<br>
						<ul class="actions">
							<li><input type="submit" value="Send Message" onclick="sendEmail()" /></li>
						</ul>
					</div>
					<div class="4u$ 12u$(small)">
						<ul class="labeled-icons">
							<li>
								<h3 class="icon fa-home"><span class="label">Address</span></h3>
								Fayetteville, Ar
							</li>
							<li>
								<h3 class="icon fa-mobile"><span class="label">Phone</span></h3>
								901-277-55997
							</li>
							<li>
								<h3 class="icon fa-envelope-o"><span class="label">Email</span></h3>
								<a href="mailto:Kris@kristensiearrablanks.com">Kris@kristensiearrablanks.com</a>
							</li>
						</ul>
					</div>
				</div>
			</section>
		</div>
		<!-- Footer -->
		<footer id="footer">
			<div class="inner">
				<ul class="icons">
					<li><a id='twitter' href="https://twitter.com/KryptoPicasso" class="icon fa-twitter"><span class="label">Twitter</span></a></li>
					<li><a id='instagram' href="https://www.instagram.com/" class="icon fa-instagram"><span class="label">Instagram</span></a></li>
					<li><a id='github' href="https://github.com/kris777347" class="icon fa-github"><span class="label">Github</span></a></li>
					<li><a id='linkedin' href="https://www.linkedin.com/in" class="icon fa-linkedin"><span class="label">LinkedIn</span></a></li>
					<li><a href="mailto:Kris@kristensiearrablanks.com" class="icon fa-envelope-o"><span class="label">Email</span></a></li>
				</ul>
			</div>
		</footer>
		</body>
		<!-- Scripts -->
		<script>
			function sendEmail() {
				var link = "mailto:Kris@kristensiearrablanks.com"
						 + "?subject=Your Portfolio"
						 + "&body=" + escape(document.getElementById('message').value);
				window.location.href = link;
			}
  document.getElementById('download').addEventListener('click', function() {
				ga('send', 'event', 'Portfolio', 'Click', 'Download Resume');
			});
			document.getElementById('freelance').addEventListener('click', function() {
				ga('send', 'event', 'Portfolio', 'Click', 'Freelance Photography / Videography');
			});
		</script>
		<script src="/js/vendor/jquery.min.js"></script>
		<script src="/js/plugins/jquery.poptrox.min.js"></script>
		<script src="/js/plugins/skel.min.js"></script>
		<script src="/js/plugins/util.js"></script>
		<script src="assets/js/analytics.js"></script>
		<!--[if lte IE 8]><script src="assets/js/ie/respond.min.js"></script><![endif]-->
		<script src="/js/plugins/about.js"></script>
</html>