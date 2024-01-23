<script lang="ts">
    import  {AppBar} from "@skeletonlabs/skeleton"
	import {base} from "$app/paths"
</script>



<AppBar>
	<svelte:fragment slot="lead">
		<a class="flex flex-row items-center" href="{base}/">
			<img class="h-12" src="{base}/icon.png" alt="" srcset="">
			<h1 class="h3 px-2">H1roune</h1>
		</a>
	</svelte:fragment>
	<svelte:fragment slot="trail">
		<a href="{base}/about" class="btn variant-filled">About</a>
	</svelte:fragment>
</AppBar>
