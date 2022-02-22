<template>
    <header id="home">
        <div class="hero-img">
          <div class="hero-shadow"></div>
          <div class="hero-text">
            <h1> Strona naszego sklepu NXOBrand</h1>
          </div>
        </div>
    </header>

</template>

<script>
export default {
  name: 'HomeView',
  
}
</script>

<style>

header {
  color: rgba(255, 255, 255, 0.822);
}

header .hero-img {
  position: relative;
  background-image: url(../components/img/telework.jpg);
  background-position: center;
  background-size: cover;
  background-attachment: fixed;
  height: 90vh;
  z-index: 0;
}

header .hero-shadow {
  position: absolute;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.527);
  z-index: -5;
}

header .hero-text{
    display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		height: 100%;
		z-index: 5;
		text-align: center;
		padding: 10px;
    color: rgb(255, 255, 255);
  
}



</style>
