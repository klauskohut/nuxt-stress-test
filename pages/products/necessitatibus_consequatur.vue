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
      return {"slug":"necessitatibus_consequatur","name":"Reiciendis necessitatibus consequatur et.","description":"Ad blanditiis aliquid. Velit magni omnis. Qui molestiae velit.","price":99880.53,"header":"Enim tenetur voluptatibus provident.","footer":"Ea voluptas rem cumque.","moreInfo":"Voluptatem temporibus similique sint."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
