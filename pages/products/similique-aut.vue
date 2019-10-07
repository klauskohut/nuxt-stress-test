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
      return {"slug":"similique-aut","name":"Non numquam assumenda totam.","description":"Iste sapiente ut. Voluptatem est quibusdam. Sed est architecto.","price":50512.73,"header":"Dolores impedit doloremque in.","footer":"Tempora dicta quis cum.","moreInfo":"Distinctio harum pariatur impedit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
