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
      return {"slug":"reprehenderit_deleniti","name":"Iste ratione tempora modi.","description":"Sunt architecto tempora. Distinctio qui fugiat. Eligendi incidunt ipsum.","price":55751.83,"header":"Quo deserunt voluptate vel.","footer":"Blanditiis saepe id quia.","moreInfo":"Numquam saepe nesciunt quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
