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
      return {"slug":"reprehenderit_perspiciatis","name":"Sapiente culpa laborum quis.","description":"Eos quia exercitationem. Numquam laborum deleniti. Quia dolore et.","price":39902.66,"header":"Aut omnis dolorum voluptates.","footer":"Expedita perferendis voluptatibus et.","moreInfo":"Et esse in nam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
