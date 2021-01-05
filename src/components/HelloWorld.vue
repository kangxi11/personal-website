<template>
  <v-container>
    <v-img
      src="@/assets/profile.jpeg"
      max-height="150"
      max-width="150"
      class="rounded-circle mx-auto"
    ></v-img>
    <div
      class="text-center name"
    >
      Ryan Kang
    </div>
  </v-container>
</template>

<style lang="postcss" scoped>
.name {
  letter-spacing: 5px !important;
  font-size: 4rem;
  font-weight: 300;
}
</style>

<script>
  export default {
    name: 'HelloWorld',
  }
</script>
