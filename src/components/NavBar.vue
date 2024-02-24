<template>
  <div class="femmeLogo">
  <p class="headBar">FREE SHIPPING ON ORDERS OVER R500</p>
  <img src="https://iili.io/JGzmSLb.png" alt="JGzmSLb.png">
</div>
<nav class="navbar navbar-expand-lg">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
                    <router-link to="/" a class="nav-link">
                    Home
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/about" a class="nav-link">
                        About
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/products" a class="nav-link">
                        Products
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/admin" a class="nav-link">
                        Admin
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link to="/contact" a class="nav-link">
                        Contact
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
    margin-left: auto;
    margin-right: auto;
}
img {
    width: 200px;
}
.headBar {
  text-align: center;
  position: sticky;
  background-color: black;
  color: #fff;
  font-size: x-small;
  padding: 5px;
  margin: 0px;
}
.nav-item {
    margin: 5px;
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