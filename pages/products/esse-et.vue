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
      return {"slug":"esse-et","name":"Ipsam voluptas delectus quam.","description":"Enim perferendis consequuntur. Et dicta voluptatem. Modi sunt nemo.","price":39268.25,"header":"Et et quas quibusdam.","footer":"Eius et sed nihil.","moreInfo":"Impedit aliquam sed rem."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
