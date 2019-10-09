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
      return {"slug":"ipsa_iure","name":"Magnam reiciendis nobis quia.","description":"Rerum cumque perspiciatis. Iusto nesciunt facilis. Enim a voluptas.","price":92725.37,"header":"Incidunt porro est sunt.","footer":"Est quas velit assumenda.","moreInfo":"Perferendis labore maiores sed."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
