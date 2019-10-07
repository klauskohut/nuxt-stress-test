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
      return {"slug":"occaecati-consequatur","name":"Consequatur ad eligendi quod.","description":"Numquam qui fugit. Occaecati deserunt sit. Voluptatem repudiandae debitis.","price":75198.66,"header":"Sequi quo pariatur dolor.","footer":"Nobis fugiat libero et.","moreInfo":"Eaque aut dolorem asperiores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
