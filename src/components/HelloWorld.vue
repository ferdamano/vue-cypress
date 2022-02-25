<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12" class="py-16" aria-live="polite">
        <transition name="v-fade">
          <main class="main-container" aria-labelledby="main-container-hero">
            <h1>Sample Vue-Test App</h1>
            <p class="py-12">
              Information about this app that you should read in detail.
            </p>
          </main>
        </transition>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",
  data: () => ({}),
  methods: {},
};
</script>

<style lang="scss" scoped>
.main-container {
  border: 1px solid rgba(0, 0, 0, 0.4);
  padding: 4rem;
}
</style>