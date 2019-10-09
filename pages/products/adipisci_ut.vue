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
      return {"slug":"adipisci_ut","name":"Ut distinctio et asperiores.","description":"Et id voluptas. Perspiciatis fugit harum. Quaerat tenetur est.","price":32184.44,"header":"Repellendus culpa excepturi reiciendis.","footer":"Rerum accusamus amet est.","moreInfo":"Sequi et perferendis illo."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
