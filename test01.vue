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

			<a-button type="text" >
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
							<div class="text_centent">
								<span aria-hidden="ture" class="text_logo">About web.dev</span>
								<h1>
									Guidance from Chrome Developer Relations
								</h1>
								<div class="text-p">
									We want to help you build beautiful, accessible, fast, and secure websites that work cross-browser, and for all of your users. This site is our home for content to help you on that journey, written by members of the Chrome team, and external experts.
								</div>
							</div>
							<div class="text_picture">
								<img alt="Guidance from Chrome Developer Relations" sizes="(min-width: 546px) 546px, calc(100vw - 48px)" src="https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format" srcset="https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=200 200w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=228 228w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=260 260w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=296 296w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=338 338w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=385 385w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=439 439w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=500 500w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=571 571w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=650 650w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=741 741w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=845 845w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=964 964w,     https://web-dev.imgix.net/image/jxu1OdD7LKOGIDU7jURMpSH2lyK2/R8GB4ZvgVvy4gimaqrXs.png?auto=format&amp;w=1092 1092w" class="hero__decor" decoding="async" height="421" loading="lazy" width="546">
							</div>
						</div>
					</div>
				</section>
				<section class="pure_text">
					<div class="wrapper flow" data-size="extra-narrow">
						<h1 class="headline__title">On this site</h1>
						<p class="color-mid-text">Explore our archive of content, covering subjects across the web development stack. Find the latest news and content on our <a href="/blog/">blog</a>, and discover content by groups on the <a href="/explore">explore</a> page.</p>
						<p class="color-mid-text">For complete courses on key web development topics, check out <a href="/learn/">Learn</a>. Developed by industry experts, these courses take you right through a subject. They are structured to allow you to just dip into one or two modules of interest too.</p>
						<p class="color-mid-text">Want some grab and go code? Our <a href="/patterns/">Patterns</a> break down common web development requirements. Whether you want to understand how to approach a certain UI component, or need to know how to copy an image to the <a href="/patterns/clipboard/">clipboard</a>, you’ll find a solution there.</p>
						<p class="color-mid-text">To help you make a case for work on UI or Performance, we have <a href="/tags/case-study/">case studies</a>. Find out how other companies have used metrics such as Core Web Vitals to see real results. And, if that’s quite enough reading for one day we also have a great archive of <a href="/podcasts/">podcasts</a> and other <a href="/shows/">shows</a>, plus recordings of our <a href="/spaces/">Twitter Space</a> sessions with members of the Chrome team.</p>
						<p class="color-mid-text">We believe that a web with multiple browser engines is important, and that web sites and applications should work well no matter which browser your visitors use. We know that you care about that too, and so content on this site should have cross-browser status clearly explained. You’ll see that many articles have a component showing browser support—the data comes from our friends at MDN, via the Browser Compat Data project that powers the data on MDN pages.</p>
					</div>
				</section>
				<section class="about_teams">
					<div class="teams">
						<h1 class="mid-h1">The team</h1>
						<p class="mid-p">This site is brought to by the Chrome DevRel team led by:</p>
						<article class="card">
							<img alt="Paul Kinlan" sizes="(min-width: 192px) 192px, calc(100vw - 48px)" src="https://web-dev.imgix.net/image/T4FyVKpzu4WKF1kBNvXepbi08t52/0O1ZGr2P0l9oTKabyUK5.jpeg?auto=format" srcset="https://web-dev.imgix.net/image/T4FyVKpzu4WKF1kBNvXepbi08t52/0O1ZGr2P0l9oTKabyUK5.jpeg?auto=format&amp;w=192 192w,     https://web-dev.imgix.net/image/T4FyVKpzu4WKF1kBNvXepbi08t52/0O1ZGr2P0l9oTKabyUK5.jpeg?auto=format&amp;w=219 219w,     https://web-dev.imgix.net/image/T4FyVKpzu4WKF1kBNvXepbi08t52/0O1ZGr2P0l9oTKabyUK5.jpeg?auto=format&amp;w=250 250w,     https://web-dev.imgix.net/image/T4FyVKpzu4WKF1kBNvXepbi08t52/0O1ZGr2P0l9oTKabyUK5.jpeg?auto=format&amp;w=284 284w,     https://web-dev.imgix.net/image/T4FyVKpzu4WKF1kBNvXepbi08t52/0O1ZGr2P0l9oTKabyUK5.jpeg?auto=format&amp;w=324 324w,     https://web-dev.imgix.net/image/T4FyVKpzu4WKF1kBNvXepbi08t52/0O1ZGr2P0l9oTKabyUK5.jpeg?auto=format&amp;w=370 370w,     https://web-dev.imgix.net/image/T4FyVKpzu4WKF1kBNvXepbi08t52/0O1ZGr2P0l9oTKabyUK5.jpeg?auto=format&amp;w=384 384w" decoding="async" height="192" loading="lazy" width="192">
							<div class="card_content">
								<h3 class="card_head">
									<a href="https://paul.kinlan.me/" target="_blank">Paul Kinlan</a>
								</h3>
								<p>DevRel lead</p>
							</div>
						</article>
						<article class="card all-center"><img alt="Rachel Andrew" sizes="(min-width: 192px) 192px, calc(100vw - 48px)" src="https://web-dev.imgix.net/image/admin/dUAN2DEXHRT6G6iPrIby.jpg?auto=format" srcset="https://web-dev.imgix.net/image/admin/dUAN2DEXHRT6G6iPrIby.jpg?auto=format&amp;w=192 192w,     https://web-dev.imgix.net/image/admin/dUAN2DEXHRT6G6iPrIby.jpg?auto=format&amp;w=219 219w,     https://web-dev.imgix.net/image/admin/dUAN2DEXHRT6G6iPrIby.jpg?auto=format&amp;w=250 250w,     https://web-dev.imgix.net/image/admin/dUAN2DEXHRT6G6iPrIby.jpg?auto=format&amp;w=284 284w,     https://web-dev.imgix.net/image/admin/dUAN2DEXHRT6G6iPrIby.jpg?auto=format&amp;w=324 324w,     https://web-dev.imgix.net/image/admin/dUAN2DEXHRT6G6iPrIby.jpg?auto=format&amp;w=370 370w,     https://web-dev.imgix.net/image/admin/dUAN2DEXHRT6G6iPrIby.jpg?auto=format&amp;w=384 384w" decoding="async" height="192" loading="lazy" width="192">
							<div class="card__content">
								<h3 class="card__heading text-size-3">
									<a href="https://rachelandrew.co.uk/" target="_blank">Rachel Andrew</a>
								</h3>
								<p>Content lead</p>
							</div>
						</article>

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
	font-size: medium;
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

.wrapper {
	padding: 0 5% 0 5%;
	background-color: azure;
}

.flow {
	padding: 5% 10% 0 10%;
	background-color: aliceblue;
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
	display: flex;
	align-items: flex-end;
}

.about_teams {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}

.teams {
	display: flex;
	flex-direction: column;
}

.mid-h1, .mid-p {
	display: flex;
	align-self: center;
}


</style>