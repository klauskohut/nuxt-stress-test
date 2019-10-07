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
      return {"slug":"ut_exercitationem","name":"Eos dolorem sit ea.","description":"Sunt iste id. Commodi ex nihil. Quam amet quis.","price":15476.52,"header":"Natus inventore vel qui.","footer":"Dicta aut nisi iste.","moreInfo":"Officia molestiae cupiditate vero."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
