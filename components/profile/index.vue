<template>
  <div class="container px-3 sm:mx-auto">
    <div class="flex items-stretch flex-wrap">

      <div class="w-full lg:w-3/5 xl:w-8/12">
        <div class="card flex-wrap">
          <profile-header/>
          <div class="py-4 px-4 pb-10 w-full">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
              <keyset label="Application for">Fullstack Developer</keyset>
              <keyset label="Email"><a target="_blank" href="mailto:abdulhakeemmustapha@gmail.com">abdulhakeemmustapha@gmail.com</a>
              </keyset>
              <keyset label="Github"><a target="_blank" href="https://github.com/aamustapha/">
                www.github.com/aamustapha </a></keyset>

              <keyset label="Code Repo"><a target="_blank" href="https://github.com/aamustapha/tailwind-application">
                aamustapha/tailwind-application </a></keyset>
              <keyset label="Location">Kano, Nigeria</keyset>
              <keyset label="Timezone">UTC+1</keyset>
              <keyset label="About Me" class="md:col-span-2">
                <p>
                  I wrote my first bit of html code sometime in March, 2014 and it has been an amazing journey ever
                  since, filled with curiosity, accomplishments and a love/hate relationship when things don't work for
                  no good reason. I've learnt that there's much more to be learnt, but I also realised that people are
                  willing to sit with me to share my experience. Devout to learning, growing and helping others grow
                  along my path.
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
      <div class="w-full mt-6 lg:my-0 lg:w-2/5 xl:w-4/12 lg:pl-3">
        <div class="card card-thanks px-4 h-full w-full ">
          <div class="py-4">
            <p class="">
              The opportunity to join the Tailwind UI team greatly interests and it's difficult to explain,
              but it is the next place I should be. I won't really call myself a UI expert yet, but I
              put in effort to ensure my apps are lightweight and look neat.
            </p>
            <p class="mt-3 xl:mt-2">
              I've strong frontend and backend skills with expertise with the Vue, Django and Flask.
              I'm proficient with javascript, python, java and php.
              I'm a lifelong learner, trying out my hand with C programming language and a host of none-technical skills
              including marketing, product design and startups in general.
            </p>
            <p class="mt-3 xl:mt-2">
              I can competently manage github issues, troubleshoot problems and fix bugs,
              respond to customer support questions and engage user communities on stackoverflow or discord.
              This among other things makes me believe that I would make a valuable asset to your team.
            </p>
            <p class="text-lg mt-4 xl:mt-1 font-bold w-full block"> Thank you Adam!</p>
            <p class="text-xs">For taking out the time to thoroughly review my application.</p>
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
