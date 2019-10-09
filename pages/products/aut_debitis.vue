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
      return {"slug":"aut_debitis","name":"Quis veniam voluptatem voluptatem.","description":"Ex tenetur asperiores. Assumenda accusantium quo. Reprehenderit dignissimos quidem.","price":55157.17,"header":"Et velit non dolores.","footer":"Mollitia non culpa quia.","moreInfo":"Consequuntur eum tenetur voluptatum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
