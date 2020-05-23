<template>
  <div class="bg-white px-3 sm:mx-auto mt-12">
    <div class="container mx-auto">

      <div class="flex flex-wrap py-4 px-4 items-center">
        <div class="w-full lg:w-3/12 order-1">
          <img src="/imgs/piper-iphone.png" class="max-w-xs lg:max-w-none mx-auto lg:w-full my-6">
        </div>
        <div class="w-full py-4 lg:w-9/12 lg:py-16 lg:my-8 lg:pr-10 text-lg">
          <h2 class="text-center w-full text-2xl font-bold uppercase">An interesting problem I once solved</h2>
          <p class="pt-2 lg:pt-6">Sometime in 2016, my then mentor Niyi gave me a challenge, to make html tables
            convenient to
            read on mobile. This solution would then be used to solve a similar challenge in a startup I work 2
            years later</p>
          <p class="pt-6">Took me a bit of time to think it over, and I had a solution that works, at least
            theoretically, we discussed about it, made some refinements and he asked me to implement, then came the
            moment of truth</p>
          <p class="pt-6">The solution was to display tables in blocks, displaying table rows as a card with an
            enclosed border and cell data stacked ontop of one another. My javascript skill were still in their prime
            and the biggest challenge I faced was being able
            to display the column header alongside each column data, it was tough, but alas using a mix of CSS block
            displays and javascript data-attributes, the result as implemented in the startup I got to work is on the
            screeshot as shown.</p>

        </div>

      </div>

    </div>

  </div>
</template>

<script>
  export default {
    name: 'Problem'
  }
</script>

<style scoped>

</style>
