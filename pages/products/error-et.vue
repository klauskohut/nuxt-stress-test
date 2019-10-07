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
      return {"slug":"error-et","name":"Sit nulla architecto sunt.","description":"Pariatur eaque soluta. Quidem dolor aut. Dolores qui a.","price":63375.95,"header":"Itaque quod praesentium fuga.","footer":"Sequi numquam at possimus.","moreInfo":"Voluptas temporibus enim ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
