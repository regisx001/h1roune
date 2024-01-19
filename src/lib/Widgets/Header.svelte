<script lang="ts">
    import  {AppBar} from "@skeletonlabs/skeleton"
</script>



<AppBar>
	<svelte:fragment slot="lead">
		<img class="h-12" src="/icon.png" alt="" srcset="">
	</svelte:fragment>
	<h1 class="h3">H1roune</h1>
	<svelte:fragment slot="trail">(actions)</svelte:fragment>
</AppBar>
