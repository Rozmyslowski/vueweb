<template>
	<main>
		<input type="number" v-model.number="a" placeholder="Podaj ilość aukcji w miesiącu"/>

			<div class="text-price">
				<p>NXOBrand {{a * 0.25}} zł</p>
			</div>
      
			<div class="text-price">
				<p>Konkurencja {{a * 0.5}} zł</p>
			</div>
        <p>Miesięcznie zaoszczędzisz: {{ (a * 0.5) - (a * 0.25) }}zł</p>
        <p>Rocznie zaoszczędzisz: {{ ((a * 0.5) - (a * 0.25) ) * 12}}zł </p>

	</main>
</template>

<script>
export default{
	name: 'OfferVue',
	data() {
		return {
			a: null,
		}
	} 
}
</script>


<style>

body{
  background-color: #222;
}
main{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
  font-size: 2rem;
  width: 500px;
}
main input{
  width: 500px;
}

.calculator{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
  font-size: 2rem;
}

main .text-pirce{
  font-size: 5rem;
  text-align: center;
  padding: 2em;

}



</style>

