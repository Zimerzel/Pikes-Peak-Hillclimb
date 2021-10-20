<template>
  <div id="app">
    <header id="header">
      <img src= "./assets/pikes-logo.jpg" class="logo" />
      <div id="nav">
        <router-link to="/" class="hover-underline-animation">About</router-link>
        <router-link to="/contact" class="hover-underline-animation">Contact</router-link>
        <router-link to="/donate" class="hover-underline-animation">Donate</router-link>
        <a href="https://www.facebook.com/pikespeakhillclimb/" target="blank" rel="noreferrer" class="hover-underline-animation"><i class="fab fa-facebook-f"></i></a>
        <a href="https://www.instagram.com/pikespeakhillclimb/" target="blank" rel="noreferrer" class="hover-underline-animation"><i class="fab fa-instagram" ></i></a>
        <a href="https://www.youtube.com/user/pikespeakhillclimb" target="blank" rel="noreferrer" class="hover-underline-animation"><i class="fab fa-youtube"></i></a>
      </div>
    </header>
    <router-view/>
    <footer>
      <h4>Copyright © 2021 Zach Imerzel</h4>
    </footer>
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
z-index: 2;
}

header{
background-color: rgb(255, 255, 255);
}

footer h4{
  font-size: 14px;
}

#nav {
  background-color: white;
  padding: 40px;
  float: right;
  position: fixed;
  margin-left: -73vw;
  display: inline;
  width:200%;
  z-index: 1;

}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  margin-left: 15px;
  text-decoration: none;

}

#nav a.router-link-exact-active {
  color: royalblue;
}

.hover-underline-animation {
  display: inline-block;
  position: relative;
  color: #ca0d00;
}

.hover-underline-animation:after {
  content: '';
  position: absolute;
  width: 100%;
  transform: scaleX(0);
  height: 2px;
  bottom: 0;
  left: 0;
  background-color: #ca0d00;
  transform-origin: bottom right;
  transition: transform 0.25s ease-out;
}

.hover-underline-animation:hover:after {
  transform: scaleX(1);
  transform-origin: bottom left;
}
</style>
