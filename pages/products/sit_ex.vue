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
      return {"slug":"sit_ex","name":"Nemo enim aperiam aut.","description":"Iste quia nesciunt. Totam ea et. Consequatur quae alias.","price":25782.94,"header":"Est labore maiores explicabo.","footer":"Repellat itaque enim dolor.","moreInfo":"Reiciendis tempora dolore similique."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
