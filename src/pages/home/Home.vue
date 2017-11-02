<template>
  <div>
    <index-header />
    <index-swipper/>
  </div>
</template>

<script>

import header from './Header.vue'
import swipper from './Swipper.vue'

export default {
  
  components:{

    "index-header":header,
    "index-swipper":swipper
  }
}
</script>

