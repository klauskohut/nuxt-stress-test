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
      return {"slug":"repudiandae-velit","name":"Nihil officiis quae id.","description":"Omnis facilis voluptatem. Et ut error. Unde quo perspiciatis.","price":29877.17,"header":"Ipsum natus ipsa incidunt.","footer":"Eum est eos corporis.","moreInfo":"Sunt reprehenderit quia quis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
