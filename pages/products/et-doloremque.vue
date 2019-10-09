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
      return {"slug":"et-doloremque","name":"Minima accusamus accusantium optio.","description":"Officiis fugiat consequatur. Error possimus sit. Minima neque aut.","price":17124.39,"header":"Nulla architecto neque tempora.","footer":"Ipsa molestiae est optio.","moreInfo":"Error nihil iste enim."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
