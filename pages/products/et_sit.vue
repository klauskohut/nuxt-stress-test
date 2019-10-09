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
      return {"slug":"et_sit","name":"Et repellat porro illum.","description":"Inventore voluptatibus doloribus. Incidunt repellendus et. Dolores quia tempore.","price":67910.99,"header":"Est repellendus tempora delectus.","footer":"Accusantium minima provident consectetur.","moreInfo":"Aut iste enim fugiat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
