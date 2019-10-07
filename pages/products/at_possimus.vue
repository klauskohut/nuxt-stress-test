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
      return {"slug":"at_possimus","name":"Aspernatur totam quia natus.","description":"Totam quidem earum. Earum natus ducimus. Eveniet tempora perspiciatis.","price":15404.53,"header":"Quos optio est facere.","footer":"Consectetur cumque corrupti minus.","moreInfo":"Explicabo excepturi error sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
