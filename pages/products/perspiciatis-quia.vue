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
      return {"slug":"perspiciatis-quia","name":"Ipsum mollitia nemo corrupti.","description":"Officia aperiam repellendus. Veritatis provident distinctio. Adipisci aut nesciunt.","price":52616.84,"header":"Aliquam optio vel quaerat.","footer":"Est adipisci omnis aut.","moreInfo":"Quaerat numquam cumque vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
