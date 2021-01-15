<template>
  <div class="home">
    <h1>Título nuevo, hola mami, estoy en la tele</h1>
    <Todos />
    <Integrantes />
  </div>
</template>

<script>
// @ is an alias to /src
import Todos from "@/components/Todos.vue";
import Integrantes from "../components/Integrantes";
export default {
  name: "Home",
  components: {
    Todos,
    Integrantes,
  },
};
</script>
