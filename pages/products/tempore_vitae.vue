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
      return {"slug":"tempore_vitae","name":"Aut quas rerum porro.","description":"Sed omnis explicabo. Nemo veritatis dolores. Eum voluptatum et.","price":26168.83,"header":"Quia quos voluptatibus debitis.","footer":"Ex repudiandae esse ad.","moreInfo":"Tempora dolores perspiciatis sit."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
