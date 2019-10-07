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
      return {"slug":"omnis_repellat","name":"In sit dolor facilis.","description":"Velit ut ad. Sed magnam odio. Voluptas quo at.","price":88930.61,"header":"Molestiae quasi magnam ipsam.","footer":"Aperiam error soluta modi.","moreInfo":"Sequi et non hic."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
