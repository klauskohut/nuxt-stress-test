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
      return {"slug":"nemo_nihil","name":"Harum repellendus nostrum odio.","description":"Sequi voluptatibus quisquam. Inventore officiis rerum. Et quam porro.","price":36006.19,"header":"Voluptatibus rerum nemo odio.","footer":"Adipisci amet distinctio reiciendis.","moreInfo":"Quam impedit itaque vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
