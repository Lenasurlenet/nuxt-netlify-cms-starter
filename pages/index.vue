<template>
  <div>
    <section class="hero min-h-screen text-center py-4 ">

      <main class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
        <div class="sm:text-center lg:text-left">
          <h1 class="text-3xl tracking-wide font-bold text-gray-900 pb-4 sm:text-4xl md:text-5xl">
            <span class="block xl:inline text-gray-800 uppercase">votre boutique <br> en ligne</span>
          </h1>
          <p class="mt-3 text-base text-brandSecondary sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
            Libérez du temps. Nous créons la boutique en ligne de votre produit gagnant, aux couleurs de votre entreprise, en un temps record.
          </p>
          <div class="mt-8 sm:mt-8 sm:flex sm:justify-center lg:justify-start">
            <div class="rounded-md shadow">
              <a href="#" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-brandPrimary hover:bg-indigo-700 md:py-4 md:text-lg md:px-10">
                Je veux un site
              </a>
            </div>
            <div class="mt-3 sm:mt-0 sm:ml-3">
              <a href="#" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-brandSecondary hover:bg-indigo-200 md:py-4 md:text-lg md:px-10">
                En savoir plus
              </a>
            </div>
          </div>
        </div>
      </main>
    </section>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  head() {
    return {
      script: [
        { src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }
      ]
    }
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: bold;
  font-size: 3.2rem;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 2rem;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
a {
  font-weight: bold;
  color: #526488;
}
.deploy-button {
  margin-top: 1rem;
}
</style>
