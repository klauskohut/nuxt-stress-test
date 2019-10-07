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
      return {"slug":"molestiae_quod","name":"Ut sunt neque illo.","description":"Nihil qui mollitia. Vero voluptas veritatis. Reiciendis odit voluptatum.","price":34869.89,"header":"Nisi dolorem consequatur expedita.","footer":"Fugiat sint praesentium doloremque.","moreInfo":"Eveniet qui adipisci ad."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
