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
      return {"slug":"molestiae-optio","name":"Tempora quas consequatur est.","description":"Ad necessitatibus qui. Itaque impedit veritatis. Error molestiae aliquam.","price":47017.05,"header":"Nobis et perferendis sed.","footer":"Sunt voluptas voluptatem qui.","moreInfo":"Voluptatum fuga aut quas."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
