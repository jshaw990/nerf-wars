<template>
  <v-app dark>
    <v-main>
      <StaticHeader />
      <Nuxt />
    </v-main>
  </v-app>
</template>

<script>
import StaticHeader from '@/components/AppLayout/StaticHeader.vue'

export default {
  name: 'DefaultLayout',
  components: {
    StaticHeader
  }
}
</script>
