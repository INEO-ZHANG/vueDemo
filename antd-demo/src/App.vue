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
					<h1 class="mid-h1">The team</h1>
					<p class="mid-p">This site is brought to by the Chrome DevRel team led by:</p>
					<div class="teams">
						<div class="card">
							<a-card hoverable style="width: 240px">
								<template #cover>
									<img alt="Paul Kinlan" src="./assets/0O1ZGr2P0l9oTKabyUK5.avif" />
								</template>
								<a-card-meta title="Paul Kinlan">
									<template #description>DevRel lead</template>
								</a-card-meta>
							</a-card>
						</div>
						
						<div class="card">
							<a-card class="card" hoverable style="width: 240px">
								<template #cover>
									<img alt="Rachel Andrew" src="./assets/dUAN2DEXHRT6G6iPrIby.avif" />
								</template>
								<a-card-meta title="Rachel Andrew">
									<template #description>Content lead</template>
								</a-card-meta>
							</a-card>
						</div>

						<div class="card">
							<a-card class="card" hoverable style="width: 240px">
								<template #cover>
									<img alt="Rowan Merewood" src="./assets/TASwqsVceW68MrM7bjt8.avif" />
								</template>
								<a-card-meta title="Rowan Merewood">
									<template #description>SPPI lead</template>
								</a-card-meta>
							</a-card>
						</div>
						
						<div class="card">
							<a-card class="card" hoverable style="width: 240px">
								<template #cover>
									<img alt="André Cipriani Bandarra" src="./assets/XVGMhdOgHJhch3EBcw89.avif" />
								</template>
								<a-card-meta title="André Cipriani Bandarra">
									<template #description>Infrastructure lead</template>
								</a-card-meta>
							</a-card>
						</div>
						
						<div class="card">
							<a-card hoverable style="width: 240px">
								<template #cover>
									<img alt="Philip Walton" src="./assets/ovBM8MF9rYDxVVHUVlcG.avif" />
								</template>
								<a-card-meta title="Philip Walton">
									<template #description>Performance Lead</template>
								</a-card-meta>
							</a-card>
						</div>
						
						<div class="card">
							<a-card class="card" hoverable style="width: 240px">
								<template #cover>
									<img alt="Una Kravets" src="./assets/c4bzyDkOZ9MhBaqp0HfW.avif" />
								</template>
								<a-card-meta title="Una Kravets">
									<template #description>CSS and UI lead</template>
								</a-card-meta>
							</a-card>
						</div>
						
						<div class="card">
							<a-card class="card" hoverable style="width: 240px">
								<template #cover>
									<img alt="Ali Spivak" src="./assets/epjaUBZaBUz4esC6C7n5.avif" />
								</template>
								<a-card-meta title="Ali Spivak">
									<template #description>Chrome extensions lead</template>
								</a-card-meta>
							</a-card>
						</div>
						
						<div class="card">
							<a-card class="card" hoverable style="width: 240px">
								<template #cover>
									<img alt="Pete LePage" src="./assets/3rFbsLsMMk1VveHfBRSu.avif" />
								</template>
								<a-card-meta title="Pete LePage">
									<template #description>Advanced apps lead</template>
								</a-card-meta>
							</a-card>
						</div>
						
						<div class="card">
							<a-card class="card" hoverable style="width: 240px">
								<template #cover>
									<img alt="Ewa Gasperowicz" src="./assets/K5zWxdTH5JagItd1w8Vm.avif" />
								</template>
								<a-card-meta title="Ewa Gasperowicz">
									<template #description>Tech lead</template>
								</a-card-meta>
							</a-card>
						</div>
					</div>
					<div class="jump_button">
						<a-button size="large" type="primary" href="https://www.web.dev/authors/">SEE OUR AUTHORS</a-button>
					</div>
				</section>

				<section class="Chrome_developers">
					<div class="Chrome_logo">
						<svg viewBox="0 0 238 36" fill="none" height="36" width="238" xmlns="http://www.w3.org/2000/svg">
							<path d="M54.5001 26.3499C53.4194 26.3768 52.3446 26.1822 51.3419 25.7781C50.3393 25.3739 49.43 24.7688 48.6701 23.9999C47.8956 23.2332 47.2866 22.3159 46.8806 21.3045C46.4747 20.2932 46.2805 19.2093 46.3101 18.1199C46.3101 15.7799 47.1001 13.8199 48.6701 12.2499C49.43 11.4811 50.3393 10.8759 51.3419 10.4718C52.3446 10.0676 53.4194 9.873 54.5001 9.89992C56.8701 9.89992 58.8001 10.7499 60.2801 12.4699L58.8801 13.8299C58.3592 13.175 57.6909 12.6525 56.9298 12.3049C56.1686 11.9574 55.3361 11.7946 54.5001 11.8299C53.6937 11.812 52.8919 11.9568 52.1428 12.2558C51.3937 12.5548 50.7125 13.0017 50.1401 13.5699C49.5504 14.1671 49.0899 14.8792 48.7871 15.662C48.4843 16.4447 48.3458 17.2814 48.3801 18.1199C48.3801 19.9999 48.9701 21.5199 50.1401 22.6799C50.7125 23.2481 51.3937 23.6951 52.1428 23.994C52.8919 24.293 53.6937 24.4378 54.5001 24.4199C56.3901 24.4199 58.0001 23.6499 59.3401 22.1199L60.7401 23.5399C60.0025 24.4168 59.0806 25.1202 58.0401 25.5999C56.9501 26.0999 55.7701 26.3499 54.5001 26.3499V26.3499ZM64.5701 10.2499V15.2199L64.4801 16.7199H64.5701C64.8701 16.1999 65.3201 15.7699 65.9501 15.4199C66.565 15.0574 67.2662 14.8674 67.9801 14.8699C69.3101 14.8699 70.3301 15.2699 71.0401 16.0999C71.7801 17.0354 72.1534 18.2088 72.09 19.3999V25.9999H70.0701V19.6999C70.0701 17.7099 69.1801 16.7199 67.4101 16.7199C66.5701 16.7199 65.8901 17.0499 65.3601 17.7199C64.8301 18.3899 64.5601 19.1599 64.5601 20.0399V25.9999H62.5401V10.2499H64.5701ZM76.4901 25.9999H74.4701V15.2199H76.4001V16.9799H76.5001C76.7001 16.3899 77.1201 15.9099 77.7501 15.5299C78.2472 15.2107 78.8139 15.0159 79.4022 14.962C79.9905 14.908 80.5831 14.9965 81.1301 15.2199L80.3601 17.1199C80.1001 17.0099 79.7401 16.9599 79.2901 16.9599C78.5501 16.9599 77.9001 17.2599 77.3301 17.8399C77.0462 18.1414 76.8256 18.4967 76.6813 18.8849C76.5371 19.2731 76.472 19.6862 76.4901 20.0999V25.9999V25.9999ZM82.7401 16.5199C83.2486 15.9785 83.8665 15.5514 84.5526 15.2669C85.2388 14.9825 85.9776 14.8471 86.7201 14.8699C88.3401 14.8699 89.6601 15.4199 90.7001 16.5199C91.2199 17.0634 91.6265 17.705 91.896 18.4072C92.1656 19.1093 92.2927 19.8581 92.2701 20.6099C92.2701 22.2499 91.7501 23.6199 90.7001 24.7199C90.1881 25.2556 89.5692 25.6775 88.8835 25.9583C88.1978 26.2392 87.4607 26.3726 86.7201 26.3499C85.9794 26.3727 85.2423 26.2393 84.5566 25.9585C83.8709 25.6777 83.2519 25.2557 82.7401 24.7199C81.6962 23.6106 81.1351 22.1325 81.1801 20.6099C81.1801 18.9699 81.7001 17.6099 82.7401 16.5099V16.5199ZM84.2401 23.4499C84.5579 23.7874 84.9415 24.0563 85.3671 24.2401C85.7927 24.4239 86.2514 24.5187 86.715 24.5187C87.1787 24.5187 87.6374 24.4239 88.063 24.2401C88.4886 24.0563 88.8722 23.7874 89.1901 23.4499C89.5465 23.0711 89.8231 22.6245 90.0035 22.1366C90.1839 21.6487 90.2643 21.1295 90.2401 20.6099C90.2662 20.0931 90.1866 19.5765 90.0061 19.0916C89.8255 18.6066 89.5478 18.1637 89.1901 17.7899C88.8745 17.4485 88.4917 17.176 88.0658 16.9897C87.6399 16.8033 87.18 16.7071 86.715 16.7071C86.2501 16.7071 85.7902 16.8033 85.3643 16.9897C84.9384 17.176 84.5556 17.4485 84.2401 17.7899C83.8865 18.1662 83.6122 18.6098 83.4335 19.0942C83.2548 19.5787 83.1754 20.0941 83.2001 20.6099C83.2001 21.7799 83.5501 22.7299 84.2401 23.4499ZM93.8901 25.9999V15.2199H95.8301V16.7199H95.9101C96.2201 16.1999 96.6901 15.7699 97.3201 15.4199C97.9007 15.0713 98.5629 14.8816 99.2401 14.8699C100.91 14.8699 102.04 15.5599 102.64 16.9399C103.024 16.2875 103.577 15.7508 104.24 15.3865C104.904 15.0221 105.654 14.8437 106.41 14.8699C107.68 14.8699 108.64 15.2699 109.29 16.0999C109.94 16.8999 110.26 17.9999 110.26 19.3999V25.9999H108.23V19.6999C108.23 18.6199 108.03 17.8499 107.64 17.3999C107.24 16.9399 106.64 16.7199 105.84 16.7199C105.04 16.7199 104.38 17.0499 103.86 17.7199C103.349 18.3844 103.078 19.2019 103.09 20.0399V25.9999H101.06V19.6999C101.06 18.6199 100.86 17.8499 100.46 17.3999C100.07 16.9399 99.4701 16.7199 98.6601 16.7199C97.8701 16.7199 97.2101 17.0499 96.6801 17.7199C96.1694 18.3844 95.8981 19.2019 95.9101 20.0399V25.9999H93.8901ZM117.51 26.3499C116.769 26.3759 116.031 26.244 115.345 25.963C114.659 25.6819 114.04 25.2582 113.53 24.7199C112.505 23.6014 111.96 22.126 112.01 20.6099C112.01 19.0399 112.5 17.6899 113.48 16.5599C114.48 15.4299 115.75 14.8599 117.28 14.8599C118.88 14.8599 120.16 15.3899 121.12 16.4299C122.127 17.5825 122.647 19.0813 122.57 20.6099L122.55 20.9799H114.03C114.036 21.9486 114.424 22.8758 115.11 23.5599C115.78 24.1899 116.57 24.4999 117.47 24.4999C118.92 24.4999 119.9 23.8899 120.41 22.6599L122.21 23.3999C121.846 24.2564 121.246 24.9917 120.48 25.5199C119.68 26.0699 118.68 26.3499 117.51 26.3499ZM120.41 19.3099C120.343 18.6414 120.042 18.0181 119.56 17.5499C119.04 16.9899 118.27 16.7199 117.25 16.7199C116.5 16.7199 115.85 16.9499 115.29 17.4199C114.74 17.8899 114.37 18.5199 114.16 19.3199H120.41V19.3099V19.3099ZM129.61 25.9999V10.2499H134.42C136.84 10.2499 138.78 10.9799 140.23 12.4499C140.96 13.1972 141.529 14.0854 141.904 15.0603C142.279 16.0352 142.451 17.0763 142.41 18.1199C142.41 20.4599 141.68 22.3599 140.23 23.8199C138.78 25.2699 136.84 25.9999 134.43 25.9999H129.6H129.61V25.9999ZM131.63 24.0599H134.43C136.24 24.0599 137.68 23.5399 138.73 22.4999C139.81 21.4599 140.34 19.9999 140.34 18.1199C140.34 16.2599 139.81 14.8099 138.74 13.7699C138.166 13.2256 137.486 12.8038 136.744 12.5305C136.001 12.2571 135.21 12.1379 134.42 12.1799H131.62V24.0599H131.63V24.0599ZM149.03 26.3599C148.287 26.3853 147.546 26.2521 146.859 25.9694C146.171 25.6866 145.551 25.2607 145.04 24.7199C144.019 23.5998 143.477 22.1246 143.53 20.6099C143.53 19.0399 144.02 17.6899 145 16.5599C146 15.4299 147.27 14.8599 148.8 14.8599C150.4 14.8599 151.68 15.3899 152.63 16.4299C153.641 17.5809 154.164 19.0799 154.09 20.6099L154.06 20.9799H145.55C145.556 21.9486 145.944 22.8758 146.63 23.5599C147.3 24.1899 148.09 24.4999 148.98 24.4999C150.43 24.4999 151.42 23.8899 151.93 22.6599L153.73 23.3999C153.366 24.2564 152.766 24.9917 152 25.5199C151.19 26.0699 150.2 26.3499 149.03 26.3499V26.3599V26.3599ZM151.93 19.3099C151.86 18.6401 151.556 18.0165 151.07 17.5499C150.56 16.9899 149.79 16.7199 148.77 16.7199C148.01 16.7199 147.37 16.9499 146.8 17.4199C146.26 17.8899 145.89 18.5199 145.68 19.3199H151.93V19.3099V19.3099ZM158.93 25.9999L154.58 15.2199H156.78L159.95 23.5799H159.99L163.2 15.2199H165.36L160.96 25.9999H158.93V25.9999ZM171.24 26.3499C170.499 26.3752 169.761 26.243 169.075 25.9621C168.389 25.6811 167.77 25.2577 167.26 24.7199C166.235 23.6014 165.69 22.126 165.74 20.6099C165.74 19.0399 166.24 17.6899 167.21 16.5599C168.21 15.4299 169.48 14.8599 171.02 14.8599C172.62 14.8599 173.9 15.3899 174.85 16.4299C175.857 17.5825 176.377 19.0813 176.3 20.6099L176.28 20.9799H167.76C167.766 21.9486 168.154 22.8758 168.84 23.5599C169.52 24.1899 170.3 24.4999 171.2 24.4999C172.65 24.4999 173.63 23.8899 174.15 22.6599L175.95 23.3999C175.584 24.2579 174.98 24.9934 174.21 25.5199C173.41 26.0699 172.41 26.3499 171.24 26.3499V26.3499ZM174.14 19.3099C174.073 18.6414 173.772 18.0181 173.29 17.5499C172.77 16.9899 172 16.7199 170.98 16.7199C170.23 16.7199 169.58 16.9499 169.02 17.4199C168.48 17.8899 168.1 18.5199 167.9 19.3199H174.15L174.14 19.3099V19.3099ZM180.18 25.9999H178.15V10.2499H180.18V25.9999V25.9999ZM183.48 16.5199C183.989 15.9785 184.606 15.5513 185.293 15.2668C185.979 14.9824 186.718 14.8471 187.46 14.8699C189.08 14.8699 190.4 15.4199 191.44 16.5199C191.96 17.0637 192.366 17.7052 192.635 18.4074C192.905 19.1095 193.032 19.8582 193.01 20.6099C193.01 22.2499 192.49 23.6199 191.45 24.7199C190.937 25.2567 190.316 25.6794 189.629 25.9602C188.941 26.2411 188.202 26.3739 187.46 26.3499C186.719 26.373 185.982 26.2398 185.296 25.959C184.611 25.6781 183.992 25.2559 183.48 24.7199C182.436 23.6106 181.875 22.1325 181.92 20.6099C181.92 18.9699 182.44 17.6099 183.48 16.5099V16.5199V16.5199ZM184.98 23.4499C185.3 23.7848 185.685 24.0507 186.112 24.2313C186.538 24.4118 186.997 24.5033 187.46 24.4999C188.42 24.4999 189.24 24.1499 189.93 23.4499C190.287 23.0711 190.563 22.6245 190.744 22.1366C190.924 21.6487 191.004 21.1295 190.98 20.6099C191.006 20.0931 190.927 19.5764 190.746 19.0914C190.566 18.6065 190.288 18.1636 189.93 17.7899C189.454 17.2758 188.83 16.9226 188.145 16.7792C187.459 16.6359 186.746 16.7095 186.104 16.9899C185.678 17.1763 185.296 17.4487 184.98 17.7899C184.626 18.1662 184.352 18.6098 184.174 19.0942C183.995 19.5787 183.915 20.0941 183.94 20.6099C183.94 21.7799 184.29 22.7299 184.98 23.4499ZM200.35 26.3499C199.53 26.3499 198.79 26.1799 198.13 25.8199C197.535 25.5172 197.031 25.0617 196.67 24.4999H196.59L196.67 25.9999V30.7499H194.65V15.2199H196.59V16.7199H196.67C197 16.1899 197.48 15.7499 198.13 15.3999C198.79 15.0399 199.53 14.8699 200.35 14.8699C201.75 14.8699 202.95 15.4199 203.95 16.5199C204.968 17.6345 205.513 19.101 205.47 20.6099C205.47 22.2399 204.97 23.6099 203.96 24.7099C203.512 25.2275 202.958 25.6421 202.335 25.9252C201.711 26.2082 201.034 26.3531 200.35 26.3499V26.3499ZM200.02 24.4999C200.96 24.4999 201.76 24.1499 202.44 23.4499C203.136 22.6723 203.499 21.6524 203.45 20.6099C203.476 20.0965 203.4 19.5831 203.226 19.0992C203.053 18.6152 202.786 18.1703 202.44 17.7899C202.136 17.4496 201.763 17.1781 201.346 16.9936C200.928 16.8091 200.476 16.7158 200.02 16.7199C199.06 16.7199 198.25 17.0699 197.58 17.7699C196.92 18.4699 196.58 19.4199 196.58 20.6099C196.58 21.7999 196.92 22.7399 197.58 23.4499C198.25 24.1499 199.06 24.4999 200.02 24.4999ZM212.22 26.3499C211.477 26.3773 210.737 26.2461 210.049 25.965C209.361 25.684 208.741 25.2595 208.23 24.7199C207.205 23.6014 206.66 22.126 206.71 20.6099C206.71 19.0399 207.21 17.6899 208.19 16.5599C209.19 15.4299 210.45 14.8599 211.99 14.8599C213.59 14.8599 214.87 15.3899 215.82 16.4299C216.827 17.5825 217.347 19.0813 217.27 20.6099L217.25 20.9799H208.74C208.744 21.9471 209.128 22.8739 209.81 23.5599C210.49 24.1899 211.27 24.4999 212.17 24.4999C213.62 24.4999 214.6 23.8899 215.12 22.6599L216.92 23.3999C216.554 24.2579 215.95 24.9934 215.18 25.5199C214.38 26.0699 213.38 26.3499 212.21 26.3499H212.22V26.3499ZM215.12 19.3099C215.05 18.6401 214.746 18.0165 214.26 17.5499C213.74 16.9899 212.97 16.7199 211.95 16.7199C211.2 16.7199 210.55 16.9499 209.99 17.4199C209.45 17.8899 209.07 18.5199 208.87 19.3199H215.12V19.3099V19.3099ZM221.15 25.9999H219.12V15.2199H221.06V16.9799H221.15C221.35 16.3899 221.77 15.9099 222.4 15.5299C222.898 15.2083 223.467 15.0121 224.057 14.9581C224.647 14.9041 225.242 14.9939 225.79 15.2199L225.02 17.1199C224.75 17.0099 224.39 16.9599 223.94 16.9599C223.21 16.9599 222.56 17.2599 221.98 17.8399C221.698 18.142 221.479 18.4976 221.336 18.8858C221.193 19.274 221.13 19.6868 221.15 20.0999V25.9999V25.9999ZM230.69 26.3499C229.49 26.3499 228.49 26.0499 227.69 25.4699C226.936 24.9025 226.349 24.1426 225.99 23.2699L227.79 22.5199C228.36 23.8699 229.33 24.5499 230.71 24.5499C231.34 24.5499 231.85 24.4099 232.25 24.1299C232.66 23.8499 232.87 23.4799 232.87 23.0299C232.87 22.3299 232.37 21.8499 231.39 21.5999L229.22 21.0699C228.504 20.8812 227.837 20.5439 227.26 20.0799C226.959 19.8426 226.718 19.538 226.557 19.1906C226.395 18.8433 226.318 18.4628 226.33 18.0799C226.33 17.1299 226.75 16.3599 227.59 15.7699C228.44 15.1699 229.44 14.8699 230.6 14.8699C231.55 14.8699 232.4 15.0899 233.15 15.5299C233.883 15.9409 234.449 16.5954 234.75 17.3799L233 18.0999C232.6 17.1499 231.78 16.6699 230.53 16.6699C229.93 16.6699 229.43 16.7999 229.02 17.0499C228.61 17.2999 228.4 17.6299 228.4 18.0499C228.4 18.6699 228.88 19.0899 229.83 19.3099L231.96 19.8099C232.98 20.0499 233.72 20.4599 234.21 21.0299C234.479 21.3406 234.682 21.7032 234.805 22.0954C234.928 22.4876 234.97 22.9009 234.927 23.3098C234.884 23.7186 234.757 24.1142 234.554 24.4721C234.352 24.8299 234.078 25.1423 233.75 25.3899C232.95 26.0299 231.94 26.3499 230.69 26.3499Z" fill="#5F6368"></path>
							<mask height="32" id="mask0_636_18464" maskUnits="userSpaceOnUse" style="mask-type:alpha" width="33" x="2" y="2"><path d="M18.5 34C27.337 34 34.5 26.837 34.5 18C34.5 9.163 27.337 2 18.5 2C9.663 2 2.5 9.163 2.5 18C2.5 26.837 9.663 34 18.5 34Z" fill="#C4C4C4"></path></mask>
							<g mask="url(#mask0_636_18464)">
								<path d="M2.5 2V21.636H12.202L18.5 10.727H34.5V2H2.5Z" fill="#DB4437"></path>
								<path d="M2.5 34.0001H17.73L24.8 26.9301V21.6361H12.202L2.5 4.99609V34.0001Z" fill="#0F9D58"></path>
								<path d="M2.5 34.0001H17.73L24.8 26.9301V21.6361H12.202L2.5 4.99609V34.0001Z" fill="url(#paint0_linear_636_18464)"></path>
								<path d="M18.5 10.7266L24.8 21.6366L17.73 33.9996H34.5V10.7266H18.5Z" fill="#FFCD40"></path><path d="M18.5 10.7266L24.8 21.6366L17.73 33.9996H34.5V10.7266H18.5Z" fill="url(#paint1_linear_636_18464)"></path>
								<path d="M12.3741 21.5733L5.1331 9.15332L5.0271 9.33532L12.2171 21.6623L12.3741 21.5723V21.5733Z" fill="#3E2723" fill-opacity="0.15"></path>
								<path d="M24.653 21.878L24.502 21.791L17.522 34H17.731L24.658 21.884L24.653 21.878Z" fill="#263238" fill-opacity="0.15"></path>
								<path d="M5.04004 9.35352L15.449 19.7615L12.202 21.6355L5.04004 9.35352Z" fill="url(#paint2_radial_636_18464)"></path>
								<path d="M17.7419 33.9797L21.5519 19.7617L24.7999 21.6357L17.7419 33.9797Z" fill="url(#paint3_radial_636_18464)"></path>
								<path d="M18.5 10.7266V14.5366L32.755 10.7266H18.5Z" fill="url(#paint4_radial_636_18464)"></path>
								<path d="M18.5001 25.2726C20.429 25.2726 22.2789 24.5063 23.6428 23.1424C25.0068 21.7784 25.7731 19.9285 25.7731 17.9996C25.7731 16.0706 25.0068 14.2207 23.6428 12.8568C22.2789 11.4928 20.429 10.7266 18.5001 10.7266C16.5711 10.7266 14.7212 11.4928 13.3573 12.8568C11.9933 14.2207 11.2271 16.0706 11.2271 17.9996C11.2271 19.9285 11.9933 21.7784 13.3573 23.1424C14.7212 24.5063 16.5711 25.2726 18.5001 25.2726V25.2726Z" fill="#F1F1F1"></path>
								<path d="M18.4999 23.8176C20.0429 23.8176 21.5227 23.2047 22.6138 22.1136C23.7049 21.0225 24.3179 19.5427 24.3179 17.9996C24.3179 16.4566 23.7049 14.9768 22.6138 13.8857C21.5227 12.7946 20.0429 12.1816 18.4999 12.1816C16.9569 12.1816 15.477 12.7946 14.3859 13.8857C13.2949 14.9768 12.6819 16.4566 12.6819 17.9996C12.6819 19.5427 13.2949 21.0225 14.3859 22.1136C15.477 23.2047 16.9569 23.8176 18.4999 23.8176V23.8176Z" fill="#4285F4"></path>
								<path d="M18.5001 10.5459C16.5713 10.5459 14.7215 11.312 13.3576 12.6758C11.9937 14.0395 11.2273 15.8892 11.2271 17.8179V17.9999C11.2271 16.071 11.9933 14.2211 13.3573 12.8571C14.7212 11.4932 16.5711 10.7269 18.5001 10.7269H34.5V10.5459H18.5001V10.5459Z" fill="#3E2723" fill-opacity="0.2"></path>
								<path d="M24.79 21.6361C24.153 22.741 23.2364 23.6588 22.1322 24.2973C21.0281 24.9357 19.7754 25.2722 18.5 25.2731C17.2241 25.2728 15.9707 24.9365 14.866 24.298C13.7614 23.6596 12.8443 22.7415 12.207 21.6361H12.2L2.5 4.99609V5.17809L12.202 21.8181H12.209C12.8464 22.9233 13.7635 23.8412 14.8682 24.4795C15.9729 25.1177 17.2262 25.4539 18.502 25.4541C19.7774 25.4537 21.0302 25.1175 22.1344 24.4792C23.2386 23.841 24.1552 22.9231 24.792 21.8181H24.802V21.6361H24.791H24.79Z" fill="white" fill-opacity="0.1"></path>
								<path d="M18.6821 10.7266C18.6511 10.7266 18.6221 10.7306 18.5911 10.7326C20.5034 10.7557 22.3296 11.5315 23.6739 12.8917C25.0182 14.2519 25.7724 16.0871 25.7731 17.9996C25.7724 19.912 25.0182 21.7472 23.6739 23.1074C22.3296 24.4677 20.5034 25.2434 18.5911 25.2666C18.6211 25.2666 18.6511 25.2726 18.6811 25.2726C20.61 25.2726 22.4599 24.5063 23.8239 23.1424C25.1878 21.7784 25.9541 19.9285 25.9541 17.9996C25.9541 16.0706 25.1878 14.2207 23.8239 12.8568C22.4599 11.4928 20.61 10.7266 18.6811 10.7266H18.6821Z" fill="#3E2723" opacity="0.1"></path><path d="M24.864 21.8778C25.3698 21.0043 25.6876 20.0348 25.7971 19.0314C25.9066 18.028 25.8054 17.0128 25.5 16.0508C25.673 16.6728 25.773 17.3258 25.773 18.0008C25.773 19.3258 25.415 20.5608 24.796 21.6308L24.8 21.6378L17.73 34.0018H17.942L24.867 21.8848L24.864 21.8778V21.8778Z" fill="white" fill-opacity="0.2"></path><path d="M18.5 2.182C27.305 2.182 34.45 9.296 34.498 18.091L34.5 18C34.5 9.164 27.336 2 18.5 2C9.664 2 2.5 9.164 2.5 18L2.502 18.09C2.55 9.297 9.694 2.183 18.5 2.183V2.182Z" fill="white" fill-opacity="0.2"></path><path d="M18.5 33.8182C27.305 33.8182 34.45 26.7042 34.498 17.9092L34.5 18.0002C34.5 26.8362 27.336 34.0002 18.5 34.0002C9.664 34.0002 2.5 26.8362 2.5 18.0002L2.502 17.9102C2.55 26.7032 9.694 33.8172 18.5 33.8172V33.8182Z" fill="#3E2723" fill-opacity="0.15"></path>
								<path d="M18.5 34C27.337 34 34.5 26.837 34.5 18C34.5 9.163 27.337 2 18.5 2C9.663 2 2.5 9.163 2.5 18C2.5 26.837 9.663 34 18.5 34Z" fill="url(#paint5_radial_636_18464)"></path>
							</g>
							<defs>
								<linearGradient gradientUnits="userSpaceOnUse" id="paint0_linear_636_18464" x1="21.204" x2="10.598" y1="30.4541" y2="24.2421">
									<stop stop-color="#055524" stop-opacity="0.4"></stop>
									<stop offset="0.33" stop-color="#055524" stop-opacity="0"></stop>
								</linearGradient>
								<linearGradient gradientUnits="userSpaceOnUse" id="paint1_linear_636_18464" x1="23.201" x2="25.872" y1="9.60056" y2="21.2956">
									<stop stop-color="#EA6100" stop-opacity="0.3"></stop>
									<stop offset="0.66" stop-color="#EA6100" stop-opacity="0"></stop>
								</linearGradient>
								<radialGradient gradientTransform="translate(5.02304 9.36652) scale(14.1898)" cx="0" cy="0" gradientUnits="userSpaceOnUse" id="paint2_radial_636_18464" r="1">
									<stop stop-color="#3E2723" stop-opacity="0.2"></stop>
									<stop offset="1" stop-color="#3E2723" stop-opacity="0"></stop>
								</radialGradient>
								<radialGradient gradientTransform="translate(18.4719 18.0247) scale(15.9764 15.9764)" cx="0" cy="0" gradientUnits="userSpaceOnUse" id="paint3_radial_636_18464" r="1">
									<stop stop-color="#263238" stop-opacity="0.2"></stop>
									<stop offset="1" stop-color="#263238" stop-opacity="0"></stop>
								</radialGradient>
								<radialGradient gradientTransform="translate(17.805 10.7176) scale(15.2869 15.2869)" cx="0" cy="0" gradientUnits="userSpaceOnUse" id="paint4_radial_636_18464" r="1">
									<stop stop-color="#3E2723" stop-opacity="0.2"></stop>
									<stop offset="1" stop-color="#3E2723" stop-opacity="0"></stop>
								</radialGradient>
								<radialGradient gradientTransform="translate(7.28 6.366) scale(32.1356)" cx="0" cy="0" gradientUnits="userSpaceOnUse" id="paint5_radial_636_18464" r="1">
									<stop stop-color="white" stop-opacity="0.1"></stop>
									<stop offset="1" stop-color="white" stop-opacity="0"></stop>
								</radialGradient>
							</defs>
						</svg>
					</div>
					

					<h1 class="mid-h1">Making the web better for tomorrow</h1>
					<div class="mid-p">
						<p class="mid-p">We hope web.dev helps you to create high quality web experiences today. The Chrome team is also working to make the web better tomorrow. If you want to learn more about what we are doing, and offer feedback on the features we are developing and contributing to, check out 
							<a href="https://developer.chrome.com/">Chrome Developers</a>
						</p>
					</div>
					
					<div class="jump_button Chrome_d">
						<a-button size="large" type="primary" href="https://developer.chrome.com/">CHROME DEVELOPERS</a-button>
					</div>

				</section>

				<section class="two_questions">
					<div class="wrapper">
						<div class="two_pad">
							<div class="Spot">
								<div class="mid-svg">
									<svg viewBox="0 0 41 40" fill="none" height="40" width="41" xmlns="http://www.w3.org/2000/svg"><path d="M20.75 0C9.71 0 0.75 8.96 0.75 20C0.75 31.04 9.71 40 20.75 40C31.79 40 40.75 31.04 40.75 20C40.75 8.96 31.79 0 20.75 0ZM18.75 30V26H22.75V30H18.75ZM18.75 10V22H22.75V10H18.75Z" clip-rule="evenodd" fill="#585B63" fill-rule="evenodd"></path></svg>
								</div>
								
								<h5>Spotted an error?</h5>
								<p class="mid-p color-mid-text">
									Please <a href="https://github.com/GoogleChrome/web.dev/issues">raise an issue</a> with information about the page and what’s wrong, and we’ll take a look.
								</p>
							</div>

							<span class="span1"></span>

							<div class="contribute">
								<div class="mid-svg">
									<svg viewBox="0 0 37 37" fill="none" height="37" width="37" xmlns="http://www.w3.org/2000/svg"><path d="M0.25 29.5001V37.0001H7.75L29.87 14.8801L22.37 7.38012L0.25 29.5001ZM35.67 9.08012C36.45 8.30012 36.45 7.04012 35.67 6.26012L30.99 1.58012C30.21 0.800117 28.95 0.800117 28.17 1.58012L24.51 5.24012L32.01 12.7401L35.67 9.08012V9.08012Z" fill="#585B63"></path></svg>
								</div>
								
								<h5>Want to contribute?</h5>
								<p class="mid-p color-mid-text">
									We feature articles and larger sections of content from external authors. If you would like to pitch an article, <a href="mailto:rachelandrew@google.com">contact Rachel Andrew</a> with an outline of your idea.
								</p>
							</div>
						</div>
					</div>

				</section>
			</div>
		</main>

		<hr>

		<footer>
			<nav class="footer_nav">
				<div>
					<h3>Contribute</h3>
					<ul>
						<li>
							<a href="https://github.com/GoogleChrome/web.dev/issues/new?assignees=&labels=bug&template=bug_report.md&title=">
								File a bug
							</a>
						</li>

						<li>
							<a href="https://github.com/googlechrome/web.dev">View source</a>
						</li>

					</ul>
				</div>

				<div>
					<h3>Related content</h3>
					<ul>
						<li>
							<a href="https://developer.chrome.com/">developer.chrome.com</a>
						</li>
						<li>
							<a href="https://blog.chromium.org/">Chrome updates</a>
						</li>
						<li>
							<a href="https://web.dev/tags/case-study/">Case studies</a>
						</li>
						<li>
							<a href="https://web.dev/podcasts/">Podcasts</a>
						</li>
						<li>
							<a href="https://web.dev/shows/">Shows</a>
						</li>
					</ul>
				</div>

				<div>
					<h3>Connect</h3>
					<ul>
						<li>
							<a href="https://www.twitter.com/ChromiumDev">Twitter</a>
						</li>
						<li>
							<a href="https://www.youtube.com/user/ChromeDevelopers">Youtube</a>
						</li>
					</ul>
				</div>
			</nav>

			<hr>

			<nav class="footer_google">
				<div class="footer_logo_nav">
					<ul class="horizontal_nav" role="list">
						<li>
							<a href="https://developers.google.com/"> 
								<img alt="Google Developers" class="w-footer__utility-logo" height="33" src="./assets/lockup-color.png" width="185"> 
							</a>
						</li>
						<li>
							<a href="https://developer.chrome.com/"> Chrome </a>
						</li>
						<li><a href="https://firebase.google.com/"> Firebase </a></li>
						<li><a href="https://cloud.google.com/"> Google Cloud Platform </a></li>
						<li><a href="https://developers.google.com/products"> All products </a></li></ul>
				</div>

				<div class="theme_switch">
					<div class="dark_switch">
						<a class="switch_name">Dark theme</a>
						<a-switch v-model:checked="checked" />
					</div>

					<div>
						<a-select ref="select" v-model:value="value1" style="width: 120px" @focus="focus" @change="handleChange">
							<a-select-option value="English">English(en)</a-select-option>
						</a-select>
					</div>
				</div>
			</nav>

			<hr />

			<nav>
				<ul class="privacy">
					<li>
						<a href="https://policies.google.com/">Terms & Privacy</a>
					</li>
					<li>
						<a href="https://web.dev/community-guidelines/">Community Guidelines</a>
					</li>
				</ul>
			</nav>

			<p class="bottom_left">Except as otherwise noted, the content of this page is licensed under the <a href="https://creativecommons.org/licenses/by/4.0/"> Creative Commons Attribution 4.0 License</a>, and code samples are licensed under the <a href="https://www.apache.org/licenses/LICENSE-2.0"> Apache 2.0 License</a>. For details, see the <a href="https://developers.google.com/terms/site-policies"> Google Developers Site Policies</a>.</p>

		</footer>
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
		const checked = ref(false);
		const options1 = ref([{
			value: 'English',
			label: 'English',
		}]);

		const focus = () => {
			console.log('focus');
		};

		const handleChange = value => {
			console.log(`selected ${value}`);
		};

		return {
			current,
			checked,
			focus,
			handleChange,
			value1: ref('English'),
			options1,
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

h1, h5 {
	font-family:Verdana, Geneva, Tahoma, sans-serif;
	text-align: center;
}

p {
	font-family: 'Courier New', Courier, monospace;
	max-width: 70ch;
}

img {
	display: block;
	height: auto;
	max-width: 100%;
}

ul {
	list-style-type: none;
	margin: 0px;
	padding: 0px;
}

li a {
	color: #585b63;
}

footer {
	padding-left: 3%;
	padding-right: 3%;
	font-size: medium;
}

.header_logo {
	margin-inline-start: 3%;
}

.search_logo {
	margin-inline-end: 3%;
}

.wrapper {
	padding: 0 5% 0 5%;
}

.flow {
	padding: 5% 10% 0 10%;
}

.guidance {
	
	background-color: azure;
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
	display: flex;
	flex-wrap: wrap;
	justify-content: center;
	gap: 17%;
	margin-top: 3%;
	margin-bottom: 10%;
}

.card {
	margin-bottom: 6%;
}

.mid-h1, .mid-p, .Chrome_logo {
	display: block;
	text-align: center;
	margin-inline: auto;
}

.mid-p {
	
	line-height: 1.7;
}

.Chrome_developers {
	padding-top: 3%;
	padding-bottom: 3%;
	background-color: #f8f9fa;
}

.Chrome_logo {
	margin-bottom: 3%;
}



.jump_button {
	display: block;
	text-align: center;
	margin-top: -10%;
	margin-bottom: 5%;
}

.Chrome_d {
	margin-top: 5%;
}

.mid-svg {
	text-align: center;
}

.two_pad {
	display: flex;
	gap: 4%;
	margin-top: 4%;
	margin-bottom: 4%;
}

.span1 {
	padding: 12px 6px 100px 6px;
	margin-left: 6px;
	border-left: 1px solid;
	font-size: 0;
}



.footer_nav {
	display: flex;
	justify-content: space-between;
	margin-right: 20%;
	margin-block-start: 3%;
	line-height: 2.5;
}

.footer_google {
	display: flex;
	justify-content: space-between;
	align-items: center;
}

.horizontal_nav, .theme_switch, .dark_switch {
	display: flex;
	gap: 3%;
	align-items: center;
	padding: 1rem 0;
}

.horizontal_nav {
	margin-block-end: 0;
}

.switch_name {
	color: #585b63;
	margin-inline-end: 3%;
	white-space: nowrap;
}

.footer_logo_nav {
	width: 50vw;
}

.privacy {
	display: flex;
	gap: 3%;
	margin-top: 3%;
	font-size: small;
}

.bottom_left {
	font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
	font-size: small;
	margin-top: 3%;
	padding-bottom: 3%;
}

</style>