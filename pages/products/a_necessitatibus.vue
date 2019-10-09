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
      return {"slug":"a_necessitatibus","name":"Ipsum earum sunt qui.","description":"Sunt voluptate enim. Neque earum distinctio. Et vel et.","price":88445.64,"header":"Voluptatem dignissimos dolores optio.","footer":"Deserunt minus et impedit.","moreInfo":"Beatae consectetur vitae occaecati."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
