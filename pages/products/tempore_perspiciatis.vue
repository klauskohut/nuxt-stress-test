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
      return {"slug":"tempore_perspiciatis","name":"Placeat id repellat molestiae.","description":"Qui veritatis excepturi. Aliquid doloribus qui. Repellendus qui quam.","price":30204.46,"header":"Quo officiis harum itaque.","footer":"Dolorum omnis et ipsam.","moreInfo":"Doloremque nihil adipisci architecto."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
