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
      return {"slug":"dolor-ut","name":"Sed quis similique nisi.","description":"Est molestias rerum. Rem sequi quod. Consequatur odio quis.","price":70228.64,"header":"Minus aut cum dolorem.","footer":"Adipisci vero sit qui.","moreInfo":"Voluptate quos rerum repellat."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
