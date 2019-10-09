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
      return {"slug":"perferendis_corrupti","name":"Earum officia repellat sit.","description":"Voluptate molestias ut. Molestias deleniti ut. Exercitationem est voluptatibus.","price":21743.24,"header":"Rem blanditiis illo qui.","footer":"Qui error iure modi.","moreInfo":"Reprehenderit dolore minima beatae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
