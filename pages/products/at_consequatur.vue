<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <Slider />
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  import Slider from '../../components/Slider'

  export default {
    layout: 'product',
    components: {
      Product,
      Slider
    },
    data() {
      return {"slug":"at_consequatur","name":"Qui aut quisquam et.","description":"Adipisci et rerum. Sit et molestiae. Reiciendis tenetur eos.","price":56280.26,"header":"Iste aut error quod.","footer":"Dolores et libero iusto.","moreInfo":"Odit quidem ad enim."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
