<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <Slider />
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  import Slider from '../../components/Slider'

  export default {
    layout: 'product',
    components: {
      Product,
      Slider
    },
    data() {
      return {"slug":"voluptas-ad","name":"Ducimus reiciendis consectetur saepe.","description":"Consequatur incidunt eaque. Dolorem nobis sequi. Ducimus aut quia.","price":62528.22,"header":"Aspernatur non enim mollitia.","footer":"Adipisci distinctio in aut.","moreInfo":"Facilis nostrum sit neque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
