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
      return {"slug":"rem-et","name":"Molestias voluptatem sit quidem.","description":"Quia illo voluptas. Eos qui voluptatem. Et adipisci earum.","price":82033.37,"header":"Libero consequatur porro architecto.","footer":"In accusamus quisquam sed.","moreInfo":"Consequuntur beatae ad dolor."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
