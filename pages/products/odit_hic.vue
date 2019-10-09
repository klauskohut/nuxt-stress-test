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
      return {"slug":"odit_hic","name":"Enim veniam qui architecto.","description":"Hic enim voluptatem. Voluptas qui quo. Dolores maiores hic.","price":88782.39,"header":"Sint non qui praesentium.","footer":"Voluptatem est illum totam.","moreInfo":"Omnis voluptate cupiditate similique."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
