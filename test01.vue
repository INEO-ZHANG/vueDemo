<template>
    <body class>
      <main id="main">
        <header class="headline all-center flow">
          <h1 class="headline__title">共建美好的网络</h1>
          "Google 相信开放、可访问、私密且安全的网络。我们希望帮助开发人员利用最新的现代技术为每个人打造出色的用户体验。"
          <div class="headline_action all-center flow-space-size-2">
            <h2 class="text-size-3">
              Google 的贡献
            </h2>
          </div>
        </header>
      </main>
    </body>
  </template>
  
  <script>
  
  export default {
  }
  </script>
  
  <style>
  header {
    display: block;
  }
  
  body {
    font-size: clamp(1rem,0.96rem+0.18vw,1.125rem);
    display: flex;
    flex-direction: column;
    overflow-x: hidden;
    color: #000;
    font-family: 'Segoe UI', System-ui, -apple-system, sans-serif;
    line-height: 1.7;
  }
  /* >*选择器*/
  .all-center>* {
    text-align: center;
    margin-inline: auto;
  }
  
  .headline__title {
    font-size: clamp(1.5rem, 1.29rem + 1.07vw, 2.25rem);
  }
  
  h1, h2 {
    max-width: 30ch;
    font-family: Google Sans,Segoe UI,System-ui,system-ui, -apple-system,sans-serif;
    line-height: 1.2;
    font-weight: 400;
    margin: 0;
  }
  
  
  *, *::before, *::after {
    box-sizing: border-box;
  }
  
  .headline {
    --flow-space: 1rem;
  }
  
  .text-size-3 {
    text-align: center;
    margin-inline: auto;
  }
  
  h2 {
    display: block;
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
  }
  
  .flow-space-size-2 {
    --flow-space: clamp(2.375rem, 1.98rem + 1.96vw, 3.75rem);
  }
  
  
  </style>
  