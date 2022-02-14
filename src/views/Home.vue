<template>
  <div class="home">
    <Slide/>
    <Jamboton/>
     <CTA/>
      <Card/>
       <Footer/>
  </div>
</template>

<script>

import Jamboton from '.././components/Jamboton.vue'
import Slide from '.././components/Slide.vue'
import CTA from '.././components/CTA.vue'
import Card from '.././components/Card.vue'
import Footer from '.././components/Footer.vue'


export default {
  name: 'Home',
  components: {
    Slide,
    Jamboton,
    CTA,
    Card,
    Footer

  }
}
</script>
