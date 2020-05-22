<template>
  <div class="container mx-auto mx-8">
    <div class="w-full xl:w-8/12">
      <div class="card flex-wrap">
        <profile-header/>
        <div class="py-4 px-6 w-full">
          <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
            <keyset label="Application for">Fullstack Developer</keyset>
            <keyset label="Email"><a target="_blank" href="mailto:abdulhakeemmustapha@gmail.com">abdulhakeemmustapha@gmail.com</a>
            </keyset>
            <keyset label="Github"><a target="_blank" href="https://github.com/aamustapha/tailwind-application"> github.com/aamustapha/tailwind-application </a></keyset>
            <keyset label="Working on"><a target="_blank" href="http://seller.tiroko.com/dashboard/"> http://seller.tiroko.com/dashboard/ </a></keyset>
            <keyset label="About" class="md:col-span-2">
              <p>
                I wrote my first bit of html code sometime in March, 2014 and it has been an amazing journey ever since,
                filled with curiosity, accomplishments and a love/hate relationship when things don't work for no good
                reason.
                I've learnt that there's much more to be learnt, but I also realised that people are willing to sit with
                me to share my experience. Devout to learning, growing and helping others grow along my path.
              </p>

              <p class="mt-3">I learnt to write code by myself, but taking every opportunity to learn from the masters.
                I realize that above every possessor of knowledge, there's one person more learned. There is no
                perfection, but I strive to minimize imperfection.
              </p>

              <p class="mt-3">I learnt to write code by myself, but taking every opportunity to learn from the masters.
                I know that above every possessor of knowledge, there's one person more learned. Though there is no
                perfection, but I strive to minimize imperfection. I just want to be better than I was.
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
