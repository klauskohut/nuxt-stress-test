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
      return {"slug":"commodi-dolorem","name":"Voluptas exercitationem in omnis.","description":"Ea facere tempora. Sapiente est amet. Dolores voluptatibus quia.","price":48196.16,"header":"In saepe voluptatum sint.","footer":"Quibusdam autem omnis blanditiis.","moreInfo":"Odit culpa velit eos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
