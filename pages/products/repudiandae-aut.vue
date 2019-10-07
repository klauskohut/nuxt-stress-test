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
      return {"slug":"repudiandae-aut","name":"Neque quasi nostrum nulla.","description":"Consectetur qui dicta. Perspiciatis quia ipsum. Repellat et voluptas.","price":57232.62,"header":"Eos veniam saepe corrupti.","footer":"Suscipit voluptate nesciunt perspiciatis.","moreInfo":"Aut et quisquam sunt."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
