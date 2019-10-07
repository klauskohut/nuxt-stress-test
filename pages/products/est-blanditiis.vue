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
      return {"slug":"est-blanditiis","name":"Ex delectus non nobis.","description":"Quo et nostrum. Aut cupiditate eos. Voluptate voluptas assumenda.","price":65437.02,"header":"Omnis culpa nemo amet.","footer":"Numquam impedit voluptates ut.","moreInfo":"Repudiandae inventore voluptates doloremque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
