<script lang="ts">
	import { Button } from '$lib';
	import { goto } from '$app/navigation';

	function onclick() {
		// console.log('clicked');
		goto('/#contact-form');
	}
</script>

<section class="hero-section default-margin mt-l">
	<h3 class="mb-s">Hello, I'm Andrew</h3>
	<div class="underscore mb-m"></div>
	<h1>I'm a Full Stack developer crafting intuitive and performant</h1>
	<h1 class="dark-grey mb-m">web experiences</h1>
	<Button {onclick}>Let's Talk</Button>
</section>

<style>
	.hero-section {
		padding-top: 60px;
	}
</style>
