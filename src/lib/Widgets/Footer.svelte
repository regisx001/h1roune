<script lang="ts">
	import { base } from '$app/paths';
	import { InstagramIcon, WhatsappIcon, XIcon, BehanceIcon } from '$lib';
	let year = new Date().getFullYear();
</script>

<section class="w-full">
	<hr class="mx-4 lg:mx-20 pb-6 opacity-20"/>
	<section class="flex items-center justify-between px-4 lg:px-20 pb-1 lg:pb-6">
		<div>
			© Copyright <span class="font-bold">{year}</span> 
			All rights reserved.
			<span class="italic font-extrabold">
				Haroune MA
			</span>
		</div>
		<div>
			Casablanca, <span class="font-bold">Morocco</span>
		</div>
	</section>
	<section class="logo-cloud gap-1  lg:grid lg:grid-cols-2 xl:flex xl:items-center xl:content-center w-full px-4 lg:px-20  pb-2">
		<a class="logo-item rounded-md " href="{base}/">
			<span><InstagramIcon /></span>
			<span>Instagram</span>
		</a>
		<a class="logo-item rounded-md" href="{base}/">
			<span><WhatsappIcon /></span>
			<span>Whatsapp</span>
		</a>
		<a class="logo-item rounded-md" href="{base}/">
			<span><XIcon /></span>
			<span>Twitter</span>
		</a>
		<a class="logo-item rounded-md" href="{base}/">
			<span><BehanceIcon /></span>
			<span>Behance</span>
		</a>
	</section>
</section>