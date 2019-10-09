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
      return {"slug":"deleniti-officia","name":"Voluptatem saepe a tenetur.","description":"Similique sed inventore. Qui pariatur culpa. Voluptas omnis optio.","price":26004.15,"header":"Architecto sunt eos veritatis.","footer":"Soluta in ipsam facilis.","moreInfo":"Velit autem nostrum numquam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
