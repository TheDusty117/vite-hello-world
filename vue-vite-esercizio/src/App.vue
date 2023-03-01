
<!-- SEZIONE DI SCRIPT , DA CAMBIARE in OPTION API-->
<script>
  //----- (1) -----  importo il mio componente Apphero step 1
  import HeroTeal from './components/AppHero.vue'
  //----- (1) -------------------------------------------


  export default {
  //----- (2) -----  passare il componente desiderato
    components: {
      //questo e' un oggetto, che viene scritto una volta, e questo oggetto e' il nostro HeroTeal che si trova su apphero...
      HeroTeal

    },
  //----- (2) ------------------------------------

    data() {
      return {
        message: 'ciao a tutti!'
      }
    },

    methods: {
      sayHello(){
        console.log('hello!')
      }
    }
  }
</script>

<!-- SEZIONE HTML-->
<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <div>
    <h1>questo l'ho scritto io in tempo reale!</h1>
    <button @click="sayHello">Saluta</button>
  </div>

<!-- ----- (3) ----- UTILIZZO DEL MIO COMPONENTE -->
<HeroTeal></HeroTeal>
<h1>Thunder</h1>

</template>


<!--SEZIONE DI STILE-->
<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.bg-styled:hover{
  filter: drop-shadow(0 0 2em #dfc63aaa);

}

</style>
