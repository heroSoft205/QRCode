<template>
  <div id="app">
    <nav>
      <router-link to="/">二维码生成</router-link> |
      <router-link to="/reader">二维码识别</router-link>
    </nav>
    <router-view />
  </div>
</template>

<style lang="less" >
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

  nav {
    padding: 30px;
    font-size: 18px;

    a {
      padding: 10px;
      font-weight: bold;
      color: #2c3e50;

      &.router-link-exact-active {
        color: #42b983;
      }
    }
  }
}
</style>
