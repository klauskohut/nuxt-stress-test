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
      return {"slug":"velit-perspiciatis","name":"Quia non non et.","description":"Eos voluptas quia. Ut eaque voluptas. Rerum nobis et.","price":42347.85,"header":"Autem vel laboriosam nemo.","footer":"Consequuntur est cumque doloremque.","moreInfo":"Repudiandae aliquid minima rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
