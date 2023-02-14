<template>
  <header class="has-background-success">
    <figure class="image center">
      <img
        class="is-rounded"
        style="max-width: 128px; margin-top: 2rem"
        src="../assets/logo.jpg"
        alt="Logo"
      />
    </figure>
    <h1 class="title">Gernciador de taréfas</h1>
  </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "BarraLateral",
});
</script>

<style scoped>
header {
  width: 100%;
  min-height: 100vh;
}

.title {
  color: #fff;
  text-align: center;
  margin-top: 2em;
}

.center {
  display: flex;
  justify-content: center;
  align-items: center;
}

@media only screen and (max-width: 768px) {
  header {
    padding: 2.5rem;
    height: auto;
  }
}
</style>
