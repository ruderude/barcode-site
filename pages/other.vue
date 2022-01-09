<template>
  <v-row class="text-center" justify="center" align="center">
    <v-col cols="12">
      アザーページ
      <Test></Test>
      <nuxt-link to="/#target" class="mr-2">
        Top-target
      </nuxt-link>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'other'
}
</script>
