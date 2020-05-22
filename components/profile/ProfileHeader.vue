<template>
  <div class="border-b-2 w-full py-4 px-4">
    <div class="flex items-center">
      <div class="w-0 md:w-16  flex-shrink">
        <img src="/imgs/my-pic-no-bg.png" class="w-full rounded-full bg-gray-400 mx-auto"/>
      </div>
      <div class="flex-grow pr-4 md:px-4">
        <h2 class="text-md md:text-xl font-bold">Abdulhakeem <span class="hidden md:inline">Adetunji</span> Mustapha</h2>
        <h6 class="text-gray-600 font-semibold"><a href="https://twitter.com/_amustapha">@_amustapha</a></h6>

      </div>
      <div class="flex-shrink font-semibold">
        <a class="btn btn-contact text-blue-400 mr-2 border-blue-400 hover:text-blue-600 hover-border-blue-600"
           href="tel:+2347067577058">
          <span class="icon-phone md:mr-2"/>
          <span class="hidden md:inline"> Phone</span>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'ProfileHeader'
  }
</script>

<style scoped>

</style>
