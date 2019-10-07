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
      return {"slug":"repudiandae-pariatur","name":"Magni quo repudiandae deleniti.","description":"Sit quam exercitationem. Iste facere asperiores. Dicta neque cumque.","price":76960.54,"header":"Labore voluptatem quos nihil.","footer":"Quod temporibus illo quidem.","moreInfo":"Voluptas et vero cumque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
