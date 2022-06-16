<template>
  <div class="home">
    <HeaderMantra />
    <MantraLeft />
    <MantraRight />
   
    
  </div>
  
</template>

<script>
// @ is an alias to /src
import HeaderMantra from '@/components/HeaderMantra.vue'
import MantraLeft from '@/components/MantraLeft.vue'
import MantraRight from '@/components/MantraRight.vue'



export default {
  name: 'HomeView',
  components: {
    HeaderMantra,
    MantraLeft,
    MantraRight
  }
}
</script>
