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
      return {"slug":"possimus-dolores","name":"Adipisci ipsam provident dolore.","description":"Et qui id. Repellendus dolores autem. Vero aut voluptas.","price":97940.41,"header":"Asperiores delectus est a.","footer":"Non aliquid esse amet.","moreInfo":"Officia ipsa et quo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
