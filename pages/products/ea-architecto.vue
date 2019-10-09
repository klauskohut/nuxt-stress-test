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
      return {"slug":"ea-architecto","name":"Ex beatae optio sapiente.","description":"Nemo commodi ratione. Et sed consectetur. Doloremque dolores earum.","price":10516.02,"header":"Asperiores deleniti possimus eum.","footer":"Voluptatibus quia aperiam quisquam.","moreInfo":"Dolorem dicta consequatur sequi."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
