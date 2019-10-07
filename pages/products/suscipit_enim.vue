<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  export default {
    layout: 'product',
    components: {
      Product,
    },
    data() {
      return {"slug":"suscipit_enim","name":"Aliquam error sit culpa.","description":"Qui occaecati nihil. Molestiae excepturi architecto. In repellat ratione.","price":54717.76,"header":"Exercitationem nihil alias enim.","footer":"Nam ratione repudiandae eum.","moreInfo":"Neque porro facilis et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
