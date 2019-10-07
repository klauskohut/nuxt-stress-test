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
      return {"slug":"in-ex","name":"Rerum reiciendis ullam sit.","description":"Eaque est id. Repudiandae qui voluptas. Voluptas in quia.","price":75499.56,"header":"Omnis sit cum dolorum.","footer":"Dolor modi dolorem praesentium.","moreInfo":"Neque ipsum repellat corrupti."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
