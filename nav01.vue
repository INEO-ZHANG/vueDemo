<template>
	<body>
		<div class="cluster gutter-base">
			<a class="site-header__brand brand" href="/"> 
				<svg viewBox="0 0 119.79 22.32" aria-label="web.dev" height="22.32" role="img" width="119.79" xmlns="http://www.w3.org/2000/svg">
					<path d="M114.99 19.32h-2.2l-4.8-11.9h2.4l3.5 9.2 3.5-9.2h2.4Zm-16.8-7.3h6.8a3.17 3.17 0 0 0-3.4-2.9 3.42 3.42 0 0 0-3.4 2.9Zm3.6 7.7a6 6 0 0 1-6-6.3c0-3.6 2.5-6.3 5.9-6.3s5.8 2.4 5.8 6.5v.2h-9.3a3.88 3.88 0 0 0 3.8 3.9 3.56 3.56 0 0 0 3.3-2.1l2 1a6.22 6.22 0 0 1-5.5 3.1Zm-14 0c-3.1 0-5.7-2.8-5.7-6.3s2.6-6.3 5.7-6.3a5 5 0 0 1 4.1 2h.1l-.1-1.6v-5.5h2.2v17.3h-2.1v-1.6h-.1a5.12 5.12 0 0 1-4.1 2Zm.3-2c2.2 0 3.8-1.7 3.8-4.3s-1.6-4.3-3.8-4.3a4 4 0 0 0-3.8 4.3 4 4 0 0 0 3.8 4.3Zm-6.8.1a1.61 1.61 0 0 1-1.7 1.6 1.74 1.74 0 0 1-1.7-1.6 1.67 1.67 0 0 1 1.7-1.6 1.61 1.61 0 0 1 1.7 1.6Zm-10.5-.1a4 4 0 0 0 3.8-4.3 4 4 0 0 0-3.8-4.3c-2.2 0-3.8 1.8-3.8 4.3s1.6 4.3 3.8 4.3Zm.4 2a5 5 0 0 1-4.1-2h-.1v1.6h-2.1V2.02h2.2v5.5l-.1 1.6h.1a4.84 4.84 0 0 1 4.1-2c3.1 0 5.7 2.8 5.7 6.3s-2.6 6.3-5.7 6.3Zm-17.4-7.7h6.8a3.17 3.17 0 0 0-3.4-2.9 3.42 3.42 0 0 0-3.4 2.9Zm3.6 7.7a6 6 0 0 1-6-6.3c0-3.6 2.5-6.3 5.9-6.3s5.8 2.4 5.8 6.5v.2h-9.3a3.88 3.88 0 0 0 3.8 3.9 3.67 3.67 0 0 0 3.3-2.1l2 1a6.22 6.22 0 0 1-5.5 3.1Zm-6.3-12.2-3.8 11.9h-2.3l-3-9.1-2.9 9.1h-2.3l-3.9-11.9h2.3l2.6 9 2.9-9h2.3l2.9 9 2.6-9Z" class="brand__text" fill="#5f6368" fill-rule="evenodd"></path>
					<path d="M0 19.28a3 3 0 0 1 3-3h16.27a3.045 3.045 0 0 1 0 6.09H3.04A3 3 0 0 1 0 19.28Z" fill="#6cf"></path>
					<path d="M.89.9a3 3 0 0 1 4.3 0l8.12 8.11a3.05 3.05 0 0 1 0 4.3l-8.12 8.12a3.04 3.04 0 1 1-4.3-4.3l5.6-5.61a.51.51 0 0 0 0-.72L.89 5.22A3 3 0 0 1 .89.9Z" fill="#06f" fill-rule="evenodd"></path>
					<path d="m10.39 16.22-5.2 5.2a3.04 3.04 0 1 1-4.3-4.3l.89-.9Z" fill="#c6f"></path>
					<circle cx="19.27" cy="19.27" fill="#06f" r="3.04"></circle>
				</svg> 
			</a>
		</div>
		<div class="nav">
			<ul>
				<li><a href="/learn/">学习</a></li>
				<li><a href="/measure/">衡量</a></li>
				<li><a href="/blog/">博客</a></li>
				<li><a href="/tags/case-study/">Case studies</a></li>
				<li><a href="/about/">关于</a></li>
			</ul>
		</div>
		<div class="site-header__actions cluster">
			<div class="site-header__search">
				<web-search i18n="{&quot;search&quot;:{&quot;en&quot;:&quot;Search&quot;},&quot;open_search&quot;:{&quot;en&quot;:&quot;Open search&quot;},&quot;all_articles&quot;:{&quot;en&quot;:&quot;All articles&quot;},&quot;close_search&quot;:{&quot;en&quot;:&quot;Close search&quot;}}" results-id="search-main-results"><!---->
					<button class="web-search__open-btn icon-button color-mid-text" aria-label="Open search">
						<svg class="web-search__search-icon" xmlns="http://www.w3.org/2000/svg" height="24" width="24" aria-hidden="true">
							<path d="M0 0h24v24H0z" fill="none"></path>
							<path d="M15.5 14h-.79l-.28-.27A6.471 6.471 0 0016 9.5 6.5 6.5 0 109.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"></path>
						</svg>
					</button>
					<div class="web-search__input-wrapper" role="combobox" aria-controls="web-search__input" aria-haspopup="listbox" aria-expanded="false" aria-owns="search-main-results-list">
						<input id="web-search__input" class="web-search__input" type="text" role="searchbox" autocomplete="off" aria-autocomplete="list" aria-controls="search-main-results-list" aria-label="All articles" placeholder="Search">
					</div>
				</web-search>
				<web-search-results id="search-main-results"><!---->
					<div role="listbox" aria-hidden="true" id="search-main-results-list"></div>
				</web-search-results>
			</div>
		</div>
	</body>
</template>

<style>
ul {
	list-style-type: none;
	margin: 0;
	padding: 0;
	overflow: hidden;
}

.brand {
	float: left;
}

.web-search__open-btn {
	float: right;
}

li {
	float: left;
}


a:link,a:visited
{
	display: block;
	width: 140px;
	font-weight: bold;
	color:#FFFFFF;
	background-color: #bebebe;
	text-align: center;
	padding: 20px;
	text-decoration: none;
}
a:hover,a:active{
	background-color: #e6e6e6;
}
</style>