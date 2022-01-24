<script setup lang="ts">
import { ref } from "vue";

defineProps<{ msg: string }>();

const count = ref(0);
</script>

<template>
  <h1>{{ msg }}</h1>

  <video width="320" height="240" controls>
    <source
      src="https://lagdroidmediastorage.blob.core.windows.net/asset-54170a2e-1a90-41af-b15b-308560030c04/Matrix%20-%2047802.mp4?sp=r&st=2022-01-24T17:32:27Z&se=2022-02-03T01:32:27Z&spr=https&sv=2020-08-04&sr=b&sig=h2O3GJ2cTpA5EiIYcA39RaRhVqdXUMohQwkxCJOOeXM%3D"
      type="video/mp4"
    />
    Your browser does not support the video tag.
  </video>
</template>

<style scoped>
a {
  color: #42b983;
}

label {
  margin: 0 0.5em;
  font-weight: bold;
}

code {
  background-color: #eee;
  padding: 2px 4px;
  border-radius: 4px;
  color: #304455;
}
</style>
