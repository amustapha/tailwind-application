<template>
  <div class="container px-3 sm:mx-auto">
    <div class="flex items-stretch flex-wrap">

      <div class="w-full lg:w-8/12">
        <div class="card flex-wrap">
          <profile-header/>
          <div class="py-4 px-4 w-full">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
              <keyset label="Application for">Fullstack Developer</keyset>
              <keyset label="Email"><a target="_blank" href="mailto:abdulhakeemmustapha@gmail.com">abdulhakeemmustapha@gmail.com</a>
              </keyset>
              <keyset label="Github"><a target="_blank" href="https://github.com/aamustapha/tailwind-application">
                aamustapha/tailwind-application </a></keyset>
              <keyset label="Working on"><a target="_blank" href="http://seller.tiroko.com/dashboard/">
                http://seller.tiroko.com/dashboard/ </a></keyset>
              <keyset label="About" class="md:col-span-2">
                <p>
                  I wrote my first bit of html code sometime in March, 2014 and it has been an amazing journey ever
                  since,
                  filled with curiosity, accomplishments and a love/hate relationship when things don't work for no good
                  reason.
                  I've learnt that there's much more to be learnt, but I also realised that people are willing to sit
                  with
                  me to share my experience. Devout to learning, growing and helping others grow along my path.
                </p>

                <p class="mt-3">I learnt to write code by myself, but taking every opportunity to learn from the
                  masters.
                  I realize that above every possessor of knowledge, there's one person more learned. There is no
                  perfection, but I strive to minimize imperfection.
                </p>

                <p class="mt-3">I learnt to write code by myself, but taking every opportunity to learn from the
                  masters.I love to learn, but hate being a parasite. I always try to be symbiotic, learning and
                  contributing my quota along the way.
                  I know that above every possessor of knowledge, there's one person more learned. Though there is no
                  perfection, but I strive to minimize imperfection. Everyday, I just want to be better than I was.
                </p>
              </keyset>
            </div>


          </div>
        </div>

      </div>
      <div class="w-full mt-6 mb-2 lg:my-0 lg:w-4/12 lg:pl-4">
        <div class="card card-thanks px-5 py-12 h-full w-full items-center">
          <p class="text-center font-bold text-3xl w-full">
            Thank you Adam!
            <small class="text-base font-light block">I look forward to your hearing back from you.</small>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import Keyset from './keyset'
  import ProfileHeader from './ProfileHeader'

  export default {
    name: 'Profile',
    components: {
      ProfileHeader,
      Keyset
    }
  }
</script>

<style scoped>

</style>
