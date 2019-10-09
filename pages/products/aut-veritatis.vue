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
      return {"slug":"aut-veritatis","name":"Repudiandae tempore sapiente similique.","description":"Optio voluptates neque. Ipsum hic assumenda. Possimus dolorem consectetur.","price":51776.42,"header":"Ut et libero reprehenderit.","footer":"Officiis placeat est molestiae.","moreInfo":"Deserunt sit impedit sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
