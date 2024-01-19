<script lang="ts">
	import { AppShell } from '@skeletonlabs/skeleton';
	import { Header } from '$lib';
</script>

<AppShell>
	<svelte:fragment slot="header">
		<Header />
	</svelte:fragment>
	<!-- Page Route Content -->
	<slot />
</AppShell>
