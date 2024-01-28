<script lang="ts">
	import { base } from '$app/paths';

	let data = [
		{
			href: base,
			img: 'https://lh4.googleusercontent.com/XrpU-I9KI7YfwQZEIVvrBNB56pcnUZGCM5lxftOYkJiG1D4qLT1-2GOIiRHClCZpvHeUo_aSNsw3I8LvNTOlSocTnHQpPenGFifkP521EeVhvDvX8wn8lGJeYWJhY1mFKw=w1280',
			title: 'Freelance Photographer'
		},
		{
			href: base,
			img: 'https://lh3.googleusercontent.com/H1hbQgNcX7-x7M8FGuMbNfOGqO1rxLl_v_80jqLg12DOc6pwTeHnjXPzQgb-9BtUNz-61DgR51gW4cW1W3eNm8hPob1cwlaWQlf_4bhsyg-rMFi8l4gZr0Tg_iTPWSF_HQ=w1280',
			title: 'Photography Of the match Foot'
		},
		{
			href: base,
			img: 'https://lh6.googleusercontent.com/L9WrmKnSHffoBJ8kTDDmE9m_00RwfZ7eNZZCtG2uz6KozogVgdRx0lEW1JWIA6oAiqnRpCvT4DCX9Pu4Rtoj6fQWPRy99jv1KaQJB8eUcihdabO8G6Uo714-AVosiBw03w=w1280',
			title: 'Rapi M3ana'
		}
	];
</script>

<section
	class="mx-[10%] lg:mx-[10%] pt-10 pb-16 lg:pt-20 lg:pb-20 gap-2 lg:gap-4
                flex flex-col lg:grid grid-cols-2 place-items-center"
>
	{#each data as src}

		<div class="p-4">
			<a href={src.href}>
				<img class="card-hover2 rounded-lg shadow-2xl max-h-96 aspect-video" src={src.img} alt="" />
			</a>
			<h1 class="h3 xl:h2 text-center opacity-75 my-4">
				{src.title}
			</h1>
		</div>
	{/each}
</section>
