<template>
  <div class="flow gap-top-size-2 flow-space-size-1">
    <article class="about__pod">
      <svg view-box="0 0 119.79 22.32" aria-label="web.dev" height="22/32" role="img" width="119.79" xmlns="http://www.w3.org/2000/svg">
        <path d="M114.99 19.32h-2.2l-4.8-11.9h2.4l3.5 9.2 3.5-9.2h2.4Zm-16.8-7.3h6.8a3.17 3.17 0 0 0-3.4-2.9 3.42 3.42 0 0 0-3.4 2.9Zm3.6 7.7a6 6 0 0 1-6-6.3c0-3.6 2.5-6.3 5.9-6.3s5.8 2.4 5.8 6.5v.2h-9.3a3.88 3.88 0 0 0 3.8 3.9 3.56 3.56 0 0 0 3.3-2.1l2 1a6.22 6.22 0 0 1-5.5 3.1Zm-14 0c-3.1 0-5.7-2.8-5.7-6.3s2.6-6.3 5.7-6.3a5 5 0 0 1 4.1 2h.1l-.1-1.6v-5.5h2.2v17.3h-2.1v-1.6h-.1a5.12 5.12 0 0 1-4.1 2Zm.3-2c2.2 0 3.8-1.7 3.8-4.3s-1.6-4.3-3.8-4.3a4 4 0 0 0-3.8 4.3 4 4 0 0 0 3.8 4.3Zm-6.8.1a1.61 1.61 0 0 1-1.7 1.6 1.74 1.74 0 0 1-1.7-1.6 1.67 1.67 0 0 1 1.7-1.6 1.61 1.61 0 0 1 1.7 1.6Zm-10.5-.1a4 4 0 0 0 3.8-4.3 4 4 0 0 0-3.8-4.3c-2.2 0-3.8 1.8-3.8 4.3s1.6 4.3 3.8 4.3Zm.4 2a5 5 0 0 1-4.1-2h-.1v1.6h-2.1V2.02h2.2v5.5l-.1 1.6h.1a4.84 4.84 0 0 1 4.1-2c3.1 0 5.7 2.8 5.7 6.3s-2.6 6.3-5.7 6.3Zm-17.4-7.7h6.8a3.17 3.17 0 0 0-3.4-2.9 3.42 3.42 0 0 0-3.4 2.9Zm3.6 7.7a6 6 0 0 1-6-6.3c0-3.6 2.5-6.3 5.9-6.3s5.8 2.4 5.8 6.5v.2h-9.3a3.88 3.88 0 0 0 3.8 3.9 3.67 3.67 0 0 0 3.3-2.1l2 1a6.22 6.22 0 0 1-5.5 3.1Zm-6.3-12.2-3.8 11.9h-2.3l-3-9.1-2.9 9.1h-2.3l-3.9-11.9h2.3l2.6 9 2.9-9h2.3l2.9 9 2.6-9Z" class="brand__text" fill="#5f6368" fill-rule="evenodd"></path>
        <path d="M0 19.28a3 3 0 0 1 3-3h16.27a3.045 3.045 0 0 1 0 6.09H3.04A3 3 0 0 1 0 19.28Z" fill="#6cf"></path>
        <path d="M.89.9a3 3 0 0 1 4.3 0l8.12 8.11a3.05 3.05 0 0 1 0 4.3l-8.12 8.12a3.04 3.04 0 1 1-4.3-4.3l5.6-5.61a.51.51 0 0 0 0-.72L.89 5.22A3 3 0 0 1 .89.9Z" fill="#06f" fill-rule="evenodd"></path>
        <path d="m10.39 16.22-5.2 5.2a3.04 3.04 0 1 1-4.3-4.3l.89-.9Z" fill="#c6f"></path>
        <circle cx="19.27" cy="19.27" fill="#06f" r="3.04"></circle>
      </svg>
      <div class="about__pod-columns">
        <div>
          <!--srcset路径无法识别-->
          <img srcset="" sizes="(min-width: 188px)  188px, calc(100vw-48px)" src="./assets/yqsykCBpsiVTwcs286tS.avif" alt="loading" decoding="async" height="175" loading="lazy" width="188">
        </div>
        <div class="flow flow-space-base">
          <h2 class="text-size-3">为现代Web 开发提供指导</h2>
          <p class="color-mid-text">web.dev 的使命就是帮助开发人员在任何浏览器上构建一流的网络体验。</p>
          <div class="cluster flow-space-size-1">
            <!--暂无链接-->
            <a href="./App.vue">操作指南</a>
            <a href="./components/HelloWorld.vue">案例研究</a>
          </div>
        </div>
      </div>
    </article>
  </div>
</template>

<style>
.flow {
  display: flex;
  flex-direction: column;
  overflow-x: hidden;
  /*测试用*/
  background: #ffff12;
  font-size: clamp(1rem, 0.96rem + 0.18vw, 1.125rem);
  color: #000000;
  font-family: Segoe UI,system-ui,-apple-system,sans-serif;
  line-height: 1.7;
  width: auto;
  /*min-height: 100vh;*/
  margin: 0;
}

.about__pod {
  --cluster-horizontal-alignment: start;
  text-align: left;
  padding: clamp(1.375rem, 1.2rem + 0.89vw, 2rem);
  border-radius: 10px;
  box-shadow: 2px 14px 24px rgb(0 0 0 / 10%);
  max-width: 68rem;
  margin-inline: auto;
  background: #ffffff;
}

.about__pod>svg {
  display: block;
  height: 22.32px;
  width: 119.79px;
}

.about__pod-columns img {
  margin-inline: auto;
}

div {
  display: block;
}

img {
  display: block;
  height: auto;
  max-width: 100%;
  aspect-ratio: auto 188/175;
  width: 188px;
}

svg:not(:root) {
  overflow: hidden;
}

*, *::before, *::after {
  box-sizing: border-box;
}

div, article {
  display: block;
}

p {
  display: block;
  margin-block-start: 1em;
  margin-block-end: 1em;
}

.flow-space-size-1 {
  --flow-space: clamp(1.375rem 1.2rem + 0.89vw, 2rem);
}

.about__pod-columns {
  grid-template-columns: 20rem 1fr;
  min-width: 50em;
}

.about__pod-columns {
  display: grid;
  margin-block-start: 1rem;
  gap: clamp(1.375rem, 1.2rem + 0.89vw, 2rem);
}

.flow-space-base {
  --flow-space: 1rem;
}

.about__pod h2 ,.about__pod p {
  margin-inline: auto;
}

.about__pod h2 ,.about__pod p {
  margin-inline-start: 0;
  min-width: 50em;
}

.about__pod p {
  max-width: 45ch;
}

.text-size-3 {
  font-size: clamp(1.25rem, 1.11rem + 0.71vw, 1.75rem);
}

h1, h2, h3 {
  max-width: 30ch;
}


</style>