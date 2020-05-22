<template>
  <div class="container mx-auto mx-8">
    <div class="w-8/12">
      <div class="card flex-wrap">
        <div class="border-b-2 w-full py-4 px-6">
          <div class="flex items-center">
            <div class="w-16  flex-shrink">
              <img src="/imgs/my-pic-no-bg.png" class="w-full rounded-full bg-gray-400 mx-auto"/>
            </div>
            <div class="flex-grow px-4">
              <h2 class="text-xl font-bold">Abdulhakeem Adetunji Mustapha</h2>
              <h6 class="text-gray-600 font-semibold"><a href="https://twitter.com/_amustapha">@_amustapha</a></h6>

            </div>
            <div class="flex-shrink font-semibold">
              <a class="btn btn-contact text-blue-400 mr-2 border-blue-400 hover:text-blue-600 hover-border-blue-600"
                 href="tel:+2347067577058">
                <span class="icon-phone mr-2"/>
                Phone
              </a>
            </div>
          </div>
        </div>
        <div class="py-4 px-6 w-full">
          <div class="grid grid-cols-2 gap-4">
            <keyset label="Application for">Fullstack Developer</keyset>
            <keyset label="Email"><a href="mailto:abdulhakeemmustapha@gmail.com">abdulhakeemmustapha@gmail.com</a>
            </keyset>
            <keyset label="About" class="col-span-2">
              <p>
                I wrote my first line of html code sometime in March, 2014 and it has been an amazing journey ever
                since,
                filled with curiosity, accomplishments and a love/hate relationship when things don't work for no good
                reason.
                I've learnt that there's much more to be learnt, but I also realised that people are willing to sit with
                me
                to share my experience. Devout to learning, growing and helping others grow along my path.
              </p>

              <p class="mt-3">I learnt to write code by myself, but taking every opportunity to learn from the masters.
                I realize that above every possessor of knowledge, there's one person more learned. There is no
                perfection, but I strive to minimize imperfection.
              </p>


            </keyset>
          </div>


        </div>
      </div>

    </div>

  </div>
</template>

<script>
  import Keyset from './keyset'

  export default {
    name: 'Profile',
    components: { Keyset }
  }
</script>

<style scoped>

</style>
