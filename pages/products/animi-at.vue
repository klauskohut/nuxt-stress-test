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
      return {"slug":"animi-at","name":"Sit ut ipsa esse.","description":"Consequatur numquam non. Et cum aut. Voluptas corporis nihil.","price":36329.78,"header":"Voluptatem voluptatem earum eos.","footer":"Dolor temporibus iste eos.","moreInfo":"Laudantium quis atque enim."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
