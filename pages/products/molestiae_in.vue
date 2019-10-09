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
      return {"slug":"molestiae_in","name":"Ipsam perferendis maxime dolore.","description":"Recusandae quia autem. Quos recusandae accusamus. Rem accusamus aperiam.","price":49343.05,"header":"Facere qui laboriosam debitis.","footer":"Et natus voluptas ut.","moreInfo":"Dolores fugit qui vitae."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
