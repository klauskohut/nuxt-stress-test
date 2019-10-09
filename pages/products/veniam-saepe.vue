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
      return {"slug":"veniam-saepe","name":"Doloremque repudiandae ipsum eos.","description":"Sapiente culpa consequatur. Voluptatem provident dolor. Dolorem ut iure.","price":25230.93,"header":"Provident asperiores accusamus inventore.","footer":"Recusandae enim sit magni.","moreInfo":"Neque voluptatibus voluptate omnis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
