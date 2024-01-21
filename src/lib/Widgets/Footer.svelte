<script lang="ts">
	import { base } from '$app/paths';
	import { InstagramIcon, WhatsappIcon, XIcon, BehanceIcon } from '$lib';
</script>

<section class="w-full">
	<section class="logo-cloud gap-1 lg:grid lg:grid-cols-2 xl:flex xl:items-center xl:content-center w-full px-4 lg:px-20  pb-2">
		<a class="logo-item rounded-md" href="{base}/">
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
