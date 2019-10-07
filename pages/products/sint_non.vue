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
      return {"slug":"sint_non","name":"Animi asperiores assumenda et.","description":"Perferendis eaque aut. Pariatur libero voluptas. Vel qui maxime.","price":53733.75,"header":"Ipsam delectus vel voluptas.","footer":"Sunt iste ut delectus.","moreInfo":"Ullam vitae sequi veniam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
