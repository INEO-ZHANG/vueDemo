<template>
    <div id="app">
      <h1>{{message}}</h1>
  
      <p>
        this is
        <a
          href="https://ineo-zhang.github.io/"
        >my Blogs</a>.
      </p>
    </div>
  
  </template>
  
  <script>
    export default {
      data() {
        return {
          message: 'My First SFC'
        };
      }
    }
  </script>
  
  <style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  
  a {
    color: #7a1111;
  }
  </style>