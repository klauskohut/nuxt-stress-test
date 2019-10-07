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
      return {"slug":"quas-doloremque","name":"Inventore sequi non atque.","description":"Deleniti ea quos. Dolores sapiente reiciendis. Aut ea quia.","price":43648.38,"header":"Nemo recusandae totam numquam.","footer":"Dignissimos illum velit laborum.","moreInfo":"Ut itaque dolorum et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
