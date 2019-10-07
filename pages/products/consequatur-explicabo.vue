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
      return {"slug":"consequatur-explicabo","name":"Ex ipsa eligendi dolores.","description":"Blanditiis quas quod. Et aut veritatis. Et nisi aut.","price":60387.23,"header":"A rerum dolor quo.","footer":"Ad neque harum ea.","moreInfo":"In soluta enim vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
