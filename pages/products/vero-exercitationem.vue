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
      return {"slug":"vero-exercitationem","name":"Enim aut est perferendis.","description":"Ea ut quam. Iste est veniam. Eos corrupti fugit.","price":36543.59,"header":"Totam commodi pariatur perferendis.","footer":"Quo veniam adipisci laudantium.","moreInfo":"Autem corporis officia est."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
