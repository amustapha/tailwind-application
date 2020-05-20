<template>
  <div class="container mx-auto py-1">
    <marketing />
    <about-me />

  </div>
</template>

<script>

import Marketing from '../components/marketing/index'
import AboutMe from '../components/about/index'

export default {
  components: {
    AboutMe,
    Marketing
  }
}
</script>
