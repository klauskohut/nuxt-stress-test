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
      return {"slug":"repellendus-blanditiis","name":"Enim ut quidem enim.","description":"Aspernatur ipsam velit. Quas maxime odit. Modi numquam et.","price":63382.67,"header":"Tempore eius ipsa at.","footer":"Numquam a ut repellat.","moreInfo":"Qui voluptatum in assumenda."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
