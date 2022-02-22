<template>

  <nav>
    <div class="container">
    <div class="row">
      <div class="col-6 title ">
        <p>NXOBrand</p>
      </div>
      <div class="col-2 ">
        <router-link to="/">Strona główna</router-link>
      </div>
      <div class="col-2 ">
        <router-link to="/oferta">Oferta</router-link>
      </div>
      <div class="col-2">
        <router-link to="/contact">Kontakt</router-link>
      </div>
    </div>
  </div>
  </nav>



  <router-view/>
</template>

<style>
  /* @import 'C:\Users\NXO\vueweb\node_modules\bootstrap\dist\css\bootstrap.css'; */

*{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

html{
  font-size: 62.5%;

}

body{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: #333;
}

/* nav */

nav{
  width: 100%;
  background-color: #333;
  height: 10vh;
}

.container{
  padding: 30px;
}

nav a {
  line-height: 200%;
  font-size: 2rem;
  color: #fff;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #42b983;
}

.title{
  font-size:3rem;
  color: #fff;
  font-weight: bold;
}

</style>
