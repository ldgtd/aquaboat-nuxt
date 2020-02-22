<template>
  <Header />
</template>

<script>
import Header from '~/components/Header.vue'

export default {
  components: {
    Header
  },

  head () {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }]
    }
  }
}
</script>
