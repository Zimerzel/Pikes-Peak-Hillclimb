<template>
  <div id="app">
    <header>
      <img src= "./assets/pikes-logo.jpg" class="logo" />
      <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link> |
        <router-link to="/contact">Contact</router-link> |
        <router-link to="/donate">Donate</router-link>
      </div>
    </header>
    <router-view/>

  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.logo{
max-height: 10vh;
position: fixed;
margin-left: -45vw;
}

#nav {
  padding: 30px;
  float: right;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
