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
      return {"slug":"esse-ut","name":"In dolores earum dolores.","description":"Aperiam voluptates adipisci. Numquam asperiores sequi. Nemo quis illo.","price":77199.11,"header":"Laborum ut eius repellat.","footer":"Quis dolores quo veniam.","moreInfo":"Ullam expedita iure ea."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
