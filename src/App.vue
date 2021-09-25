<template>
  <Header />
  <div class="container mx-auto p-9">
    <router-view/>
  </div>
  
</template>

<script>
import Header from '@/components/Header'

export default {
  components:{
    Header,
  },
}
</script>
