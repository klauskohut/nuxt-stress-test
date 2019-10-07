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
      return {"slug":"temporibus-eos","name":"Et velit modi tempora.","description":"Dignissimos nemo molestiae. Repellat minima nostrum. Dolorum a et.","price":95347.18,"header":"Dolores repudiandae autem nemo.","footer":"Fugit laborum impedit a.","moreInfo":"Ullam ipsam sunt repudiandae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
