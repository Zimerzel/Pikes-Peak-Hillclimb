<template>
  <div id="app">
    <header id="header">
      <img src= "./assets/pikes-logo.jpg" class="logo" alt="PPIHC logo"/>
      <div id="header">
        <b-navbar toggleable="lg" type="light" variant="white" id="navbar" class="navbar-horizontal">
          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
          <b-collapse id="nav-collapse" v-model="showCollapse" is-nav>
            <b-navbar-nav class="navbar-nav">
              <router-link to="/" class="hover-underline-animation">About</router-link>
              <router-link to="/contact" class="hover-underline-animation">Contact</router-link>
              <router-link to="/sponsor" class="hover-underline-animation">Sponsors</router-link>
              <a href="https://www.facebook.com/pikespeakhillclimb/" target="blank" rel="noreferrer" class="hover-underline-animation" alt="Facebook Link"><i class="fab fa-facebook-f"></i></a>
              <a href="https://www.instagram.com/pikespeakhillclimb/" target="blank" rel="noreferrer" class="hover-underline-animation" alt="Instagram Link"><i class="fab fa-instagram" ></i></a>
              <a href="https://www.youtube.com/user/pikespeakhillclimb" target="blank" rel="noreferrer" class="hover-underline-animation" alt="Youtube Link"><i class="fab fa-youtube"></i></a>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>
    </header>
    <router-view/>
    <footer>
      <h1>Copyright © 2021 Zach Imerzel</h1>
      <a href="https://github.com/Zimerzel/Pikes-Peak-Hillclimb" target="blank" rel="noreferrer" alt="Source Code Link"><i class="fas fa-code-branch"></i></a>
      
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return{
      showCollapse: false
    }
  },
  watch:{
    '$route' (){
      this.showCollapse = false
    }
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.logo{
margin-top:20px;
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

#navbar{
  position: fixed;
  left:73%;
  width:100vw;
  background-color: white;
  padding-top: 30px;
  padding-bottom:40px;
  float: right;
  position: fixed;
  margin-left: -73vw;
  display: inline;
  width:200%;
  z-index: 1;
}

.navbar-nav{
  float: left;
  margin-left: 4vw;
  margin-right: 3vw
}

.navbar-nav a {
  font-size: 18px;
  font-weight: bold;
  color: #2c3e50;
  margin-left: 1vw;
  text-decoration: none;
  margin-right:1vw;
  left: 60vw;
  margin-top: 20px;

}

.navbar-nav a.router-link-exact-active {
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
  background-color: #bb2727;
  transform-origin: bottom right;
  transition: transform 0.25s ease-out;
}

.hover-underline-animation:hover:after {
  transform: scaleX(1);
  transform-origin: bottom left;
}

footer{
  background-image: url("https://ppihc.org/wp-content/uploads/bk-10.png?id=4214");
  height: 150px;
}

footer h1{
  text-align: center;
  font-size: 14px;
  font-weight: 100;
  padding-top:75px;
  color: #ffffff;
}

@media only screen and (max-width: 995px) {
.navbar-nav a{
  margin-left: -25vw
}
.navbar-toggler{
  margin-right: 100px !important;
  margin-top: 5px !important
}

.logo{
  margin-top:10px;
}

}

@media only screen and (min-width: 1524px){
  .navbar a{
  left: 68vw;
  }
}



</style>
