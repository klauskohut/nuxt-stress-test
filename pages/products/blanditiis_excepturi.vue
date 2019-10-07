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
      return {"slug":"blanditiis_excepturi","name":"Omnis quos laudantium reprehenderit.","description":"Eveniet sapiente deleniti. Voluptas nesciunt aperiam. In et optio.","price":96572.96,"header":"Reprehenderit molestiae non blanditiis.","footer":"Nisi dolores veritatis nostrum.","moreInfo":"Ipsam exercitationem et neque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
