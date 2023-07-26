<script setup lang="ts">
const links = [
  {
    title: 'Home',
    href: '/',
  },
  {
    title: 'Upgrade',
    href: '/upgrade',
  },
  {
    title: 'Dashboard',
    href: '/dashboard',
  },
  {
    title: 'Pricing',
    href: '/#pricing',
  },
  {
    title: 'Features',
    href: '/#features',
  },
]

const authStore = useAuthStore()
const appConfig = useAppConfig()
const year = new Date().getFullYear()
</script>

<template>
  <footer class="footer-area bg-f7fafd">
		<div class="container">
			<div class="row">
				<div class="col-lg-3 col-md-6">
					<div class="single-footer-widget">
						<div class="logo">
							<a href="#"><img style="height: 70px;" src="https://i.imgur.com/uZXb392.png" alt="logo"></a>
						</div>

					</div>
				</div>
				<div class="col-lg-3 col-md-6">
					<div class="single-footer-widget pl-5">
						
					</div>
				</div>
				<div class="col-lg-3 col-md-6">
					<div class="single-footer-widget">
						<h3>Spotplus</h3>
						<ul class="list">
              <li><a href="/upgrade">Upgrade</a></li>
							<li><a href="/dashboard">Dashboard</a></li>

						</ul>
					</div>
				</div>
				<div class="col-lg-3 col-md-6">
					<div class="single-footer-widget">
						<h3>Socials</h3>
						<ul class="social-links">
							<a style="text-decoration: none; color: white;" href="https://discord.gg/spotifyplug">Discord</a> <br>
							
						</ul>
					</div>
				</div>
				<div class="col-lg-12 col-md-12">
					<div class="copyright-area">
						<p>Copyright © 2023 SpotPlus. All rights reserved.</p>
					</div>
				</div>
			</div>
		</div> 
		
	</footer>
</template>
<style>
  @import 'css/style.css';
  @import 'css/animate.css';
  @import 'css/bootstrap.min.css';
  @import 'css/magnific-popup.min.css';
  @import 'css/meanmenu.css';
  @import 'css/odometer.css';
  @import 'css/owl.carousel.min.css';
  @import 'css/responsive.css';
  @import 'css/slick.css';
 
</style>