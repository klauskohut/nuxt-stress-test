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
      return {"slug":"ut_aut","name":"Veniam neque quibusdam recusandae.","description":"Mollitia quia debitis. Et cum consequuntur. Voluptas exercitationem perspiciatis.","price":83497.39,"header":"Dolore cumque rerum natus.","footer":"Tenetur pariatur explicabo ut.","moreInfo":"Deleniti animi atque maiores."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
