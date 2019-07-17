<template>
  <div id="app">
    <router-view></router-view>

    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>

    <img alt="Vue-logo" src="./assets/pwva-logo.png">
    <h1>Creating First Vue.js PWA Project.</h1>
    <p>
      <a href="http://uznetro.net">http://uznetro.net</a>&ensp;/&ensp;2019 Shota Niimi
    </p>
    <a class="button-dl" href="https://github.com/uznetro/"><svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-mark-github" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path></svg>Get started</a>
  </div>
</template>

<style lang="scss">
* {
  box-sizing: border-box;
}

html, body {
  height: 100%;
  background: #fff;
  color: #333;
  font: 14px/1 'Open Sans', sans-serif;
  margin: 0;
  padding: 0;
  overflow-x: hidden;
}
h1 {
  font: 600 22px/1 'Open Sans', sans-serif;
  color: #545454;
}
h2 {
  font: 600 20px/1 'Open Sans', sans-serif;
  color: #888;
  margin: 20px 0;
}
h3 {
  font: 600 15px/1 'Open Sans', sans-serif;
  color: #999;
  margin: 20px 0;
}
p {
  font: 14px/1.4 'Open Sans', sans-serif;
  color: #777;
}
a {
  color: #5f6a7d;
  text-decoration: none;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#nav a {
  text-decoration: underline;
  font-size: 16px;
}
.router-link-exact-active {
  color: #5bb3b6;
  font-weight: bold;
}
.button-dl {
  border: 1px solid #e0e0e0;
  border-radius: 5px;
  color: #5f6a7d !important;
  display: inline-block;
  font-size: 12px;
  height: 30px;
  letter-spacing: .75px;
  line-height: 28px;
  padding: 0 1rem;
  text-decoration: none;
  text-transform: uppercase;
  vertical-align: top;
  svg {
    position: relative;
    top: 3px; left: -5px;
  }
}
</style>
