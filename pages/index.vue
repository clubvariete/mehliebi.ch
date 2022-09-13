<template>
  <NuxtLayout>
    <!-- https://v1.image.nuxtjs.org/components/nuxt-picture -->
    <!-- https://v1.image.nuxtjs.org/components/nuxt-img -->
    <figure>
      <nuxt-picture
        src="/v2.png"
        width="1920"
        height="1590 "
        sizes="xs:200px md:500px lg:1024"
      />
      <figcaption class="text-center text-gray-600 text-xs mt-3">
        Meh Liebi
      </figcaption>
    </figure>
  </NuxtLayout>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: #000;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
