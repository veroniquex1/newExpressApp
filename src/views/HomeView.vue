<template>
  <div class="home">
    <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://iili.io/JGaywc7.md.jpg" class="d-block" alt="carousel image">
    </div>
    <div class="carousel-item">
      <img src="https://iili.io/JGc9zU7.md.jpg" class="d-block" alt="carousel image">
    </div>
    <div class="carousel-item">
      <img src="https://iili.io/JGc9VOg.md.jpg" class="d-block" alt="carousel image">
    </div>
  </div>
</div>
  </div>
<!-- end of carousel -->
<!-- content begins -->
<div class="aboutSum">
  <p class="shortDesc">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ab reprehenderit fugiat molestias, nulla unde iure impedit error aut odio ullam necessitatibus reiciendis quis, animi odit sunt repudiandae quam non aliquam.
  Ad quam perferendis dolores maxime voluptatibus, recusandae officiis ratione quas explicabo debitis suscipit perspiciatis, quibusdam harum temporibus possimus beatae sequi? Tempora veritatis voluptatum modi corporis, dolores impedit nam. Ab, tempora!
  Assumenda distinctio iure omnis quos unde explicabo perferendis deserunt vitae! Placeat, eum, rerum doloribus iste, veniam voluptatibus a numquam praesentium quibusdam aliquam necessitatibus. Dicta deserunt facilis modi optio rem accusantium?
  </p>
</div>
  <div class="buttons">
    <button class="btn"><a href="/products">Get shopping</a></button>
    <button class="btn"><a href="/about">Read more about us</a></button>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  components: {

  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Cookie&family=Palanquin:wght@100;200;300;400;500;600;700&display=swap');

template {
  font-family: "Palanquin", sans-serif;
}
.buttons {
  width: 100%;
  display: flex;
  justify-content: center;
}
a {
  text-decoration: none;
}
.btn {  
  border-radius: 30px;
  color: #000;
  padding: 10px;
  margin: 10px;
  font-size: 12px;
  border: none;
  cursor: pointer;
  transition: .4s;
  background-color: #d6c7c7;
}
.d-block {
  width: 100%;
}
.shortDesc {
  color: black;
  padding-top: 50px;
  padding-left: 100px;
  padding-right: 100px;
  font-size: large;
}
</style>