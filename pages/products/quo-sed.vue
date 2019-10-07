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
      return {"slug":"quo-sed","name":"Ea ad beatae cupiditate.","description":"Illum numquam nobis. Similique nemo incidunt. Hic quae accusamus.","price":29405.85,"header":"Eveniet odit excepturi fugit.","footer":"Aliquam fugiat libero maiores.","moreInfo":"Velit exercitationem laudantium nulla."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
