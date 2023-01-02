<template>
	<body>
		<header>
			<a class="header_logo" href="/"> 
				<svg viewBox="0 0 119.79 22.32" aria-label="web.dev" height="22.32" role="img" width="119.79" xmlns="http://www.w3.org/2000/svg">
					<path d="M114.99 19.32h-2.2l-4.8-11.9h2.4l3.5 9.2 3.5-9.2h2.4Zm-16.8-7.3h6.8a3.17 3.17 0 0 0-3.4-2.9 3.42 3.42 0 0 0-3.4 2.9Zm3.6 7.7a6 6 0 0 1-6-6.3c0-3.6 2.5-6.3 5.9-6.3s5.8 2.4 5.8 6.5v.2h-9.3a3.88 3.88 0 0 0 3.8 3.9 3.56 3.56 0 0 0 3.3-2.1l2 1a6.22 6.22 0 0 1-5.5 3.1Zm-14 0c-3.1 0-5.7-2.8-5.7-6.3s2.6-6.3 5.7-6.3a5 5 0 0 1 4.1 2h.1l-.1-1.6v-5.5h2.2v17.3h-2.1v-1.6h-.1a5.12 5.12 0 0 1-4.1 2Zm.3-2c2.2 0 3.8-1.7 3.8-4.3s-1.6-4.3-3.8-4.3a4 4 0 0 0-3.8 4.3 4 4 0 0 0 3.8 4.3Zm-6.8.1a1.61 1.61 0 0 1-1.7 1.6 1.74 1.74 0 0 1-1.7-1.6 1.67 1.67 0 0 1 1.7-1.6 1.61 1.61 0 0 1 1.7 1.6Zm-10.5-.1a4 4 0 0 0 3.8-4.3 4 4 0 0 0-3.8-4.3c-2.2 0-3.8 1.8-3.8 4.3s1.6 4.3 3.8 4.3Zm.4 2a5 5 0 0 1-4.1-2h-.1v1.6h-2.1V2.02h2.2v5.5l-.1 1.6h.1a4.84 4.84 0 0 1 4.1-2c3.1 0 5.7 2.8 5.7 6.3s-2.6 6.3-5.7 6.3Zm-17.4-7.7h6.8a3.17 3.17 0 0 0-3.4-2.9 3.42 3.42 0 0 0-3.4 2.9Zm3.6 7.7a6 6 0 0 1-6-6.3c0-3.6 2.5-6.3 5.9-6.3s5.8 2.4 5.8 6.5v.2h-9.3a3.88 3.88 0 0 0 3.8 3.9 3.67 3.67 0 0 0 3.3-2.1l2 1a6.22 6.22 0 0 1-5.5 3.1Zm-6.3-12.2-3.8 11.9h-2.3l-3-9.1-2.9 9.1h-2.3l-3.9-11.9h2.3l2.6 9 2.9-9h2.3l2.9 9 2.6-9Z" class="brand__text" fill="#5f6368" fill-rule="evenodd"></path>
					<path d="M0 19.28a3 3 0 0 1 3-3h16.27a3.045 3.045 0 0 1 0 6.09H3.04A3 3 0 0 1 0 19.28Z" fill="#6cf"></path>
					<path d="M.89.9a3 3 0 0 1 4.3 0l8.12 8.11a3.05 3.05 0 0 1 0 4.3l-8.12 8.12a3.04 3.04 0 1 1-4.3-4.3l5.6-5.61a.51.51 0 0 0 0-.72L.89 5.22A3 3 0 0 1 .89.9Z" fill="#06f" fill-rule="evenodd"></path>
					<path d="m10.39 16.22-5.2 5.2a3.04 3.04 0 1 1-4.3-4.3l.89-.9Z" fill="#c6f"></path>
					<circle cx="19.27" cy="19.27" fill="#06f" r="3.04"></circle>
				</svg> 
			</a>


			<a-menu v-model:selectedKeys="current" mode="horizontal">

				<a-menu-item key="Learn">
					Learn
				</a-menu-item>
				<a-menu-item key="Explore">
					Explore
				</a-menu-item>
				<a-menu-item key="Measure">
					Measure
				</a-menu-item>
				<a-menu-item key="Blog">
					Blog
				</a-menu-item>
				<a-menu-item key="Case studies">
					Case studies
				</a-menu-item>
				<a-menu-item key="About">
					About
				</a-menu-item>
			</a-menu>

			<a-button class="search_logo" type="text" >
				<template #icon>
					<search-outlined />
				</template>
			</a-button>

		</header>


		<main>
			<div class="main_content">
				<section class="guidance">
					<div class="wrapper">
						<div class="true_content">
							<div class="text_content">
								<span aria-hidden="ture" class="text_logo">About web.dev</span>
								<div class="Guidance_text">
									<h1>
										Guidance from Chrome Developer Relations
									</h1>
									<div class="text-p">
										We want to help you build beautiful, accessible, fast, and secure websites that work cross-browser, and for all of your users. This site is our home for content to help you on that journey, written by members of the Chrome team, and external experts.
									</div>
								</div>
							</div>
							<div class="text_picture">
								<img alt="Guidance from Chrome Developer Relations" sizes="(min-width: 546px) 546px, calc(100vw - 48px)" src="https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format" srcset="https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=200 200w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=228 228w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=260 260w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=296 296w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=338 338w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=385 385w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=439 439w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=500 500w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=571 571w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=650 650w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=741 741w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=845 845w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=964 964w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=1092 1092w" class="hero__decor" decoding="async" height="421" loading="lazy" width="546">
							</div>
						</div>
					</div>
				</section>



				<section class="pure_text">
					<div class="this_site" data-size="extra-narrow">
						<h1 class="headline__title">On this site</h1>
						<p class="color-mid-text">Explore our archive of content, covering subjects across the web development stack. Find the latest news and content on our <a href="/blog/">blog</a>, and discover content by groups on the <a href="/explore">explore</a> page.</p>
						<p class="color-mid-text">For complete courses on key web development topics, check out <a href="/learn/">Learn</a>. Developed by industry experts, these courses take you right through a subject. They are structured to allow you to just dip into one or two modules of interest too.</p>
						<p class="color-mid-text">Want some grab and go code? Our <a href="/patterns/">Patterns</a> break down common web development requirements. Whether you want to understand how to approach a certain UI component, or need to know how to copy an image to the <a href="/patterns/clipboard/">clipboard</a>, you’ll find a solution there.</p>
						<p class="color-mid-text">To help you make a case for work on UI or Performance, we have <a href="/tags/case-study/">case studies</a>. Find out how other companies have used metrics such as Core Web Vitals to see real results. And, if that’s quite enough reading for one day we also have a great archive of <a href="/podcasts/">podcasts</a> and other <a href="/shows/">shows</a>, plus recordings of our <a href="/spaces/">Twitter Space</a> sessions with members of the Chrome team.</p>
						<p class="color-mid-text">We believe that a web with multiple browser engines is important, and that web sites and applications should work well no matter which browser your visitors use. We know that you care about that too, and so content on this site should have cross-browser status clearly explained. You’ll see that many articles have a component showing browser support—the data comes from our friends at MDN, via the Browser Compat Data project that powers the data on MDN pages.</p>
					</div>
				</section>

				<hr class="HR"	/>

				<section class="about_teams flow">
					<div class="teams">
						<h1 class="mid-h1">The team</h1>
						<p class="mid-p">This site is brought to by the Chrome DevRel team led by:</p>

						<a-card hoverable style="width: 240px">
							<template #cover>
								<img alt="Paul Kinlan" src="./assets/0O1ZGr2P0l9oTKabyUK5.avif" />
							</template>
							<a-card-meta title="Paul Kinlan">
								<template #description>DevRel lead</template>
							</a-card-meta>
						</a-card>

						<a-card hoverable style="width: 240px">
							<template #cover>
								<img alt="Rachel Andrew" src="./assets/dUAN2DEXHRT6G6iPrIby.avif" />
							</template>
							<a-card-meta title="Rachel Andrew">
								<template #description>Content lead</template>
							</a-card-meta>
						</a-card>

						<a-card hoverable style="width: 240px">
							<template #cover>
								<img alt="Rowan Merewood" src="./assets/TASwqsVceW68MrM7bjt8.avif" />
							</template>
							<a-card-meta title="Rowan Merewood">
								<template #description>SPPI lead</template>
							</a-card-meta>
						</a-card>

						<a-card hoverable style="width: 240px">
							<template #cover>
								<img alt="André Cipriani Bandarra" src="./assets/XVGMhdOgHJhch3EBcw89.avif" />
							</template>
							<a-card-meta title="André Cipriani Bandarra">
								<template #description>Infrastructure lead</template>
							</a-card-meta>
						</a-card>

						<a-card hoverable style="width: 240px">
							<template #cover>
								<img alt="Philip Walton" src="./assets/ovBM8MF9rYDxVVHUVlcG.avif" />
							</template>
							<a-card-meta title="Philip Walton">
								<template #description>Performance Lead</template>
							</a-card-meta>
						</a-card>

						<a-card hoverable style="width: 240px">
							<template #cover>
								<img alt="Una Kravets" src="./assets/c4bzyDkOZ9MhBaqp0HfW.avif" />
							</template>
							<a-card-meta title="Una Kravets">
								<template #description>CSS and UI lead</template>
							</a-card-meta>
						</a-card>

						<a-card hoverable style="width: 240px">
							<template #cover>
								<img alt="Ali Spivak" src="./assets/epjaUBZaBUz4esC6C7n5.avif" />
							</template>
							<a-card-meta title="Ali Spivak">
								<template #description>Chrome extensions lead</template>
							</a-card-meta>
						</a-card>

						<a-card hoverable style="width: 240px">
							<template #cover>
								<img alt="Pete LePage" src="./assets/3rFbsLsMMk1VveHfBRSu.avif" />
							</template>
							<a-card-meta title="Pete LePage">
								<template #description>Advanced apps lead</template>
							</a-card-meta>
						</a-card>

						<a-card hoverable style="width: 240px">
							<template #cover>
								<img alt="Ewa Gasperowicz" src="./assets/K5zWxdTH5JagItd1w8Vm.avif" />
							</template>
							<a-card-meta title="Ewa Gasperowicz">
								<template #description>Tech lead</template>
							</a-card-meta>
						</a-card>

					</div>
				</section>
			</div>
		</main>
	</body>
</template>

<script>
import { defineComponent, ref } from 'vue';
import { SearchOutlined } from '@ant-design/icons-vue';
export default defineComponent({
	components: {
		SearchOutlined,
	},
	setup() {
		const current = ref(['mail']);
		return {
			current,
		};
	},
});
</script>

<style>         
main {
	font-family: Verdana, Geneva, Tahoma, sans-serif;
	font-size: large;
}

header {
	display: flex;
	justify-content: space-between;
	align-items: center;
}

header>*:first-child {
	align-self: center;
	justify-self: flex-start;
}

section {
	display: block;
}

p {
	max-width: 70ch;
}

img {
	display: block;
	height: auto;
	max-width: 100%;
}



.header_logo {
	margin-inline-start: 3%;
}

.search_logo {
	margin-inline-end: 3%;
}

.wrapper {
	padding: 0 5% 0 5%;
	background-color: azure;
}

.flow {
	padding: 5% 10% 0 10%;
}

.true_content {
	display: flex;
	flex-wrap: wrap;
	background-color: azure;
	padding-block: 10%;
	gap: 6%;
	line-height: 1.7;
}

.true_content>* {
	flex: 1 1 0;
}

.text_content {
	margin-inline-start: 10%;
}

.text_picture {
	margin-inline-end: 10%;
}

.Guidance_text {
	margin-block-start: 20%;
}

.pure_text {
	display: flex;
	justify-items: center;
}

.this_site {
	padding: 5% 5% 5% 5%;
	margin: 0 auto;
	font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

.headline__title .color-mid-text {
	margin-block-start: 100%;
}

.about_teams {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}

.teams {
	display: block;
}

.mid-h1, .mid-p {
	display: flex;
	justify-content: center;
}


</style>