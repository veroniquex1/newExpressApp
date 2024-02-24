<template>
  <div>
    <p class="headBar">FREE SHIPPING ON ORDERS OVER R800</p>
  </div>
  <div class="femmeLogo">
    <img src="https://iili.io/JGaP6WF.png" alt="JGzmSLb.png">
  </div>
<nav class="navbar navbar-expand-lg">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
                    <router-link to="/" a class="nav-link">
                      home
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/about" a class="nav-link">
                      about
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/products" a class="nav-link">
                      products
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/admin" a class="nav-link">
                      admin
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/contact" a class="nav-link">
                      contact
                    </router-link>
                </li>  
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
    export default {
       components: 'NavBar'
    }
</script>

<style>
.femmeLogo {
  text-align: center;
}
.navbar{
  background-color: #fff;
}
.navbar-nav {
  width: 100%;
  justify-content: center;
}
img {
  width: 250px;
  padding-top: 10px;
}
.headBar {
  text-align: center;
  background-color: black;
  color: #fff;
  font-size: x-small;
  padding: 5px;
  margin: 0px;
}
.nav-item {
  margin-left: 25px;
  margin-right: 25px;
  display: flex;
  justify-content: center;
}
nav {
  padding-left: 30px;
  padding-right: 30px;
}
.nav-item a:hover{
  font-weight: bold;
  color: #a8dadc;
}
.nav-item a.router-link-exact-active {
  color: #a8dadc;
  border-radius: 25px;
  box-shadow: 0px 0px 10px 0px #a8dadc;
}
</style>