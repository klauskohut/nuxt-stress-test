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
      return {"slug":"qui_dolor","name":"Officiis et sunt dolor.","description":"Consequuntur itaque doloremque. Minus deleniti commodi. Harum eos consectetur.","price":89442.25,"header":"Nihil voluptatem dignissimos mollitia.","footer":"Sit vero delectus voluptates.","moreInfo":"Et quae perspiciatis aut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
