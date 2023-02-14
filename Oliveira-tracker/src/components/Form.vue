<template>
  <div class="box">
    <div class="columns">
      <div
        class="column is-8"
        role="form"
        area-label="Formulário para a criação de uma nova tarefa"
      >
        <input type="text" class="input" placeholder="Digite uma tarefa..." />
      </div>
      <div class="column">
        <temporizador />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Temporizador from "../components/Temporizador.vue";

export default defineComponent({
  name: "Form",
  components: {
    Temporizador,
  },
});
</script>
