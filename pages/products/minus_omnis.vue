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
      return {"slug":"minus_omnis","name":"Mollitia corporis a alias.","description":"Odio quia natus. Et consequatur voluptatem. Quasi ipsum iure.","price":99425.32,"header":"Exercitationem molestiae omnis accusamus.","footer":"Dolorem dolor dolore cumque.","moreInfo":"Est aliquam at saepe."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
