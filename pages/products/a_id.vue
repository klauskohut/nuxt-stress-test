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
      return {"slug":"a_id","name":"Quos aliquam enim assumenda.","description":"Aut doloremque at. Odio voluptas repellat. Molestiae tenetur rem.","price":20391.93,"header":"Iure quia expedita distinctio.","footer":"Nihil voluptas beatae voluptatem.","moreInfo":"Beatae impedit velit cumque."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
