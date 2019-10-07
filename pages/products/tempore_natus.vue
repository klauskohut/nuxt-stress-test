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
      return {"slug":"tempore_natus","name":"Placeat et ea cumque.","description":"Et vel voluptates. Eos deleniti amet. Pariatur quae exercitationem.","price":27493.06,"header":"Rerum rerum nesciunt corrupti.","footer":"Et consectetur tenetur dolor.","moreInfo":"Minima natus sed atque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
