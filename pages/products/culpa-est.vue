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
      return {"slug":"culpa-est","name":"Hic magnam ipsam doloremque.","description":"Repudiandae facere debitis. Nostrum officiis eum. Aliquid tempore cum.","price":85409.58,"header":"Et tempora consectetur id.","footer":"Ipsum nihil cupiditate quod.","moreInfo":"A architecto excepturi quam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
