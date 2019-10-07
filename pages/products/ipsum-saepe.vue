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
      return {"slug":"ipsum-saepe","name":"Perspiciatis adipisci soluta eum.","description":"Ea corporis voluptatem. Commodi minus perferendis. Maiores quia repellat.","price":93362.14,"header":"Enim perferendis nesciunt sed.","footer":"Et voluptates omnis et.","moreInfo":"Est suscipit corrupti voluptatibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
