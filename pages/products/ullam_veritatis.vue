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
      return {"slug":"ullam_veritatis","name":"Consequuntur quas autem minima.","description":"Et cum repellat. Reiciendis quisquam qui. Quaerat dolorum quis.","price":35280.38,"header":"Cum provident officiis dolorem.","footer":"Iusto repudiandae repellat numquam.","moreInfo":"Numquam debitis quasi ducimus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
