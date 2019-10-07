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
      return {"slug":"et_eos","name":"Expedita eum quo enim.","description":"Nulla nemo velit. Corrupti esse tempora. Perspiciatis rerum id.","price":85399.58,"header":"Dolor ullam officiis asperiores.","footer":"Ipsa nihil optio sunt.","moreInfo":"Quod ab et mollitia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
