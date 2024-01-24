<script lang="ts">
	import { base } from '$app/paths';
	import { InstagramIcon } from '$lib';

	export let title: string = 'Title';
	export let desc1: string = 'desc1';
	export let desc2: string = 'desc2';
	export let insta: string;
	export let cover:string;

	export let reversed: boolean = false;
</script>

<section class="my-10">
	<div 
    class:lg:flex-row={!reversed}
    class:lg:flex-row-reverse={reversed}
    class="flex flex-col justify-between ">
		<div
		class:md:mr-6={!reversed}
		class:md:ml-6={reversed}
		class="lg:w-3/5 md:mr-6">
			<a href={base}>
				<img
					class="card-hover2 rounded-2xl shadow-2xl max-h-96 aspect-video"
					src="{cover}"
					alt=""
				/>
			</a>
		</div>
		<div class="flex flex-col justify-between lg:w-2/5 opacity-90">
			<header class="flex flex-col">
				<h1 class="h1 text-center">{title}</h1>
				<h2 class="h3 pt-5 md:pt-8">{desc1}</h2>
				<span class="pt-4 md:pt-6 text-xl">
					{desc2}
			    </span>
				<slot />
			</header>

			<a href={insta} target="_blank" class="btn xl:my-10 bg-pink-700">
				<span><InstagramIcon /></span>
				<span>Check Instagram</span>
			</a>
		</div>
	</div>
</section>

<style>
	.card-hover2 {
		transition-property: all;
		transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
		transition-duration: 300ms;
	}
	.card-hover2:hover {
		--tw-scale-x: 104%;
		--tw-scale-y: 104%;
		transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate))
			skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x))
			scaleY(var(--tw-scale-y));
		--tw-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
		--tw-shadow-colored: 0 20px 25px -5px var(--tw-shadow-color),
			0 8px 10px -6px var(--tw-shadow-color);
		box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000),
			var(--tw-shadow);
	}
</style>
