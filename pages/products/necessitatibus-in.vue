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
      return {"slug":"necessitatibus-in","name":"Reprehenderit sed neque perspiciatis.","description":"Dolorem et vero. Tempore fugiat tenetur. Doloremque ut est.","price":27177.66,"header":"Et est pariatur qui.","footer":"Iure rerum aliquam sint.","moreInfo":"Voluptate id odio qui."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
