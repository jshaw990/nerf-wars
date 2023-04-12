<template>
  <v-app-bar flat>
    <nuxt-link to="/">
      <v-app-bar-title>
        <div class="text-uppercase">
          YYC Nerf Wars
        </div>
        <div class="xsmall-text ml-4">
          A Calgary Nerf Club
        </div>
      </v-app-bar-title>
    </nuxt-link>
    <v-spacer />
    <div class="d-flex flex-row align-center">
      <nuxt-link to="/about-us" class="mx-4">
        <div>About Us</div>
      </nuxt-link>
      <nuxt-link to="/about-us" class="mx-4">
        <div>About Us</div>
      </nuxt-link>
      <nuxt-link to="/about-us" class="mx-4">
        <div>Contact Us</div>
      </nuxt-link>
      <v-btn nuxt to="/about-us" color="green" class="mx-4">
        Waivers
      </v-btn>
    </div>
  </v-app-bar>
</template>

<script>
export default {
  name: 'StaticHeader',
  setup () {

  }
}
</script>
