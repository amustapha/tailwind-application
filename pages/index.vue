<template>
  <div>
    <marketing />
    <profile />
    <problem />
  </div>
</template>

<script>

import Marketing from '../components/marketing/index'
import Profile from '../components/profile/index'
import Problem from '../components/problem/index'

export default {
  components: {
    Problem,
    Profile,
    Marketing
  }
}
</script>
