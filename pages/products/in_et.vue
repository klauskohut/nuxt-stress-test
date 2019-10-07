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
      return {"slug":"in_et","name":"Eum recusandae omnis voluptatem.","description":"Sit similique et. Doloribus officiis ut. Ad rerum nesciunt.","price":89860.01,"header":"Expedita numquam quidem perferendis.","footer":"Autem consequatur inventore est.","moreInfo":"Ut necessitatibus vitae eum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
