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
      return {"slug":"delectus_iure","name":"Quisquam iure ut dolorem.","description":"Minus nihil qui. Animi et qui. Iure voluptatem optio.","price":35566.18,"header":"Autem nobis est aperiam.","footer":"Aliquid omnis ea sit.","moreInfo":"Et at pariatur sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
