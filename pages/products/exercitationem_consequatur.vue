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
      return {"slug":"exercitationem_consequatur","name":"Occaecati autem voluptate eaque.","description":"Eaque est totam. Autem fuga sit. Veniam voluptatibus aut.","price":63039.53,"header":"Sed id nam ut.","footer":"Blanditiis dolore voluptas officiis.","moreInfo":"Atque adipisci tempora ipsum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
