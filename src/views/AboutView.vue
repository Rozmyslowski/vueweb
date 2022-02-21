<template>
  <main>
    <div class="offer-box">
       <div id="app">
          <p>Ilość miesięcy <input v-model="x"></p>
          <p>Stawka u nas lub na allegro <input v-model="y"></p>
          
          <p> <span v-text="result"></span></p>
        </div>
    </div>
  </main>
</template>


<script>


</script>

<style>

main{
  height: 90vh;
  background-color: #222;
  color: #fff;
  font-size: 2rem;
}

.offer-box{
   display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		height: 100%;
		text-align: center;
}

</style>

