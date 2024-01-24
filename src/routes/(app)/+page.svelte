<script lang="ts">
	import { base } from '$app/paths';
	import { LProjectCard } from '$lib';

	let props1 = {
		title: 'Jihvvn',
		desc1: 'Jihan Yahya, 21 years Old.',
		desc2: 'Moroccan girl passionate about life experience.',
		cover: base + '/assets/jihvvn/cover.jpg',
		insta: 'https://www.instagram.com/jihvvn_/',
	};

    let props2 = {
		title: 'Zaaaak',
		desc1: 'Zakaria, 19 years Old.',
		desc2: 'A Casablanca based , model/talent passionate about Classic style. ',
		cover: base + '/assets/zaak/cover.jpg',
		insta: 'https://www.instagram.com/trulyzaak_106/',
        reversed:false,
	};
</script>

<svelte:head>
	<title>H1roune | Main Page</title>
</svelte:head>

<section class="mx-[10%] lg:mx-[15%]">
	<!-- <header  class="hidden lg:block lg:pt-14 text-5xl font-semibold opacity-75">
		<div class="">Behind every <span class="font-bold text-secondary-600"> PICTURE </span>,</div>
		<div class="lg:mx-80 pt-6 underline text-orange-600">A LONG STORY.</div>
	</header> -->
	<header class="pt-10">
		<h1 class="h1">Latest Project :</h1>
	</header>
	<LProjectCard {...props1} />
    <hr>
	<LProjectCard {...props2} />
</section>
