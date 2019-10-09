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
      return {"slug":"vel_molestiae","name":"Maiores velit animi et.","description":"Autem reprehenderit non. Tempora harum eum. Dolorem autem vitae.","price":31300.08,"header":"Explicabo est ipsa maiores.","footer":"Asperiores reprehenderit beatae perspiciatis.","moreInfo":"Commodi ratione incidunt sunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
