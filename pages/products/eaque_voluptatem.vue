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
      return {"slug":"eaque_voluptatem","name":"Sint porro doloremque optio.","description":"Sint ducimus molestiae. Nam adipisci quia. Omnis quae sint.","price":21695.24,"header":"Voluptas unde qui qui.","footer":"Similique asperiores molestias dolor.","moreInfo":"Unde accusantium mollitia reprehenderit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
