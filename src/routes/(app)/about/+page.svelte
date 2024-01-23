<script lang="ts">
	import { base } from '$app/paths';
</script>

<svelte:head>
    <title>
        H1roune | About Me
    </title>
</svelte:head>

<section class="mx-[10%] lg:mx-[15%] flex flex-col-reverse lg:flex-row pb-20">
	<div class="lg:w-[60%] pt-16">
		<h1 class="h1 my-8 font-semibold text-4xl lg:text-7xl">Hello, I'm Haroune.</h1>
		<div class="text-2xl opacity-75">
			<span> <span class="font-semibold opacity-95"> Haroune Mabchour Akachab's </span>, also known as <span class="underline font-bold">H1roune</span>. </span> <br />
            
            <hr class="my-4 opacity-0">
			
            <span>
				photographic journey is a testament to his lifelong connection with the visual arts.
			</span>
			<span>
				Growing up in the vibrant city of Marrakech, he was surrounded by a rich blend of tradition
				and modernity, which served as the wellspring of his inspiration.
			</span> <br>
            
            <hr class="my-4 opacity-0">
            
            <span>
				Now splitting his time between the bustling urban life of Casablanca and the coastal charm
				of Tangier, he has harnessed the diverse energies of these cities to infuse his work with a
				unique perspective.
			</span>
			<!-- <span>
				Haroune's photography transcends mere snapshots; it is a poetic exploration of the world
				around him.
			</span>
			<span>
				His portfolio is a visual narrative, weaving stories of everyday life, culture, and the
				natural beauty of Morocco.
			</span>
			<span>
				Whether it's the intricate patterns of the medina's architecture, the candid expressions of
				people on the streets, or the serene landscapes along the coast, Haroune's work captures
				moments frozen in time, inviting viewers to step into the heart of Morocco's soul.
			</span>
            <span>
                In 2022, Haroune Mabchour achieved recognition and acclaim as one of the top five
				photographers in Morocco at the prestigious Maroc Web Awards.
                </span>
			<span>
				His notable project, "100 Moroccans Peoples," showcases his talent for capturing the diverse
				tapestry of Moroccan life.
			</span>
			<span
				>Through his lens, he masterfully encapsulates the essence of his subjects, revealing the
				intricate stories that lie within the faces and places of Morocco.
			</span>
            <span>
                Haroune's work invites viewers to explore the profound connections between people and their
				surroundings, offering a compelling visual narrative that transcends time and borders.
            </span>
			<span>
				His exceptional skill in storytelling through photography has solidified his status as a
				renowned artist, making his portfolio a captivating journey into the heart and soul of
				Morocco.
			</span> -->
		</div>
	</div>
	<div class="lg:w-[40%] flex justify-center items-center pt-16">
		<img
			class="max-w-80 lg:max-w-full "
			src="{base}/assets/profile.png"
			alt="profile, haroune ma, casablanca, maroc, photography"
			srcset=""
		/>
	</div>
</section>
