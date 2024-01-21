<script lang="ts">
	import { AppShell } from '@skeletonlabs/skeleton';
	import { Header, Footer } from '$lib';
</script>

<AppShell>
	<svelte:fragment slot="header">
		<Header />
	</svelte:fragment>
	<!-- Page Route Content -->
	<slot />
	<svelte:fragment slot="pageFooter">
		<Footer/>
	</svelte:fragment>
</AppShell>
