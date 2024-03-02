<script>
  import CardProduct from './components/CardProduct.vue';
  import FooterVue from './components/FooterVue.vue';
  import HeaderVue from './components/HeaderVue.vue';
  import CatalogVue from './components/CatalogVue.vue';
  import MainPage from './components/MainPage.vue';
  export default {
    components: {
      CardProduct,
      HeaderVue,
      FooterVue, 
      CatalogVue,
      MainPage     
    },
    data() {
      return {
        page: 'Main'
      }
    },
  }
</script>
<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Anton&display=swap" rel="stylesheet">
  <body>
    <div class="buttons">
      <button @click="page='Main'">Main page</button>
      <button @click="page='Catalog'">Catalog</button>
      <button @click="page='Card'">Card</button>
    </div>
    <HeaderVue v-cloak/>    
    <MainPage v-if="page==='Main'" v-cloak/>
    <CardProduct v-if="page==='Card'" v-cloak/>
    <CatalogVue v-if="page==='Catalog'" v-cloak/>
    <FooterVue v-cloak/>
  </body>
</template>
<style scoped>
    .buttons {
      position: absolute;
      display: flex;
      flex-direction: column;
      margin-top: 60px;  
      gap: 10px;    
    }
    button,
    button:active,
    button:focus  {
        width: 100px;
        height: 64px;
        background-color: black;
        color: white        ;
        font-family: 'Work Sans';
        font-size: 16px;
        font-weight: 700;
        line-height: 19px;
        letter-spacing: 0%;
        text-align: center;
        border: none;        
        margin-left: 10px;
        z-index:1
    }
    button:focus {
      color:red
    }
  body {
    width: 1366px;
    height: auto;
  }
</style>
