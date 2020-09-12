<template>
  <v-app>
      <p>About</p>
  </v-app>
</template>

<script>
export default {
    head() {
        return {
            title: 'About',
            meta: [
                {
                    hid: 'description',
                    name: 'description',
                    content: 'Nuxt API'
                }
            ]
        }
    }
}
</script>

<style>

</style>