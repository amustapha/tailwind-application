<template>
  <div class="pb-4">
    <marketing />
    <profile />
  </div>
</template>

<script>

import Marketing from '../components/marketing/index'
import Profile from '../components/profile/index'

export default {
  components: {
    Profile,
    Marketing
  }
}
</script>
