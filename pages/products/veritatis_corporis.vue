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
      return {"slug":"veritatis_corporis","name":"Dolorum saepe numquam et.","description":"Ipsam qui porro. Omnis aperiam voluptatem. Sit quidem harum.","price":15477.04,"header":"Eos asperiores consequuntur ducimus.","footer":"Fuga doloribus vel laboriosam.","moreInfo":"Possimus laborum architecto omnis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
