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
      return {"slug":"et_at","name":"Facere quae tempore qui.","description":"Asperiores quidem adipisci. Sunt aliquid repellat. Laudantium deserunt et.","price":24909.64,"header":"Minima at nihil laboriosam.","footer":"Porro accusamus vero quia.","moreInfo":"Quis nesciunt reprehenderit quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
