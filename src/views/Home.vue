<template>
  <div class="home">
    <Todos />
    <Integrantes />
  </div>
</template>

<script>
// @ is an alias to /src
import Todos from "@/components/Todos.vue";
import Integrantes from '../components/Integrantes'
export default {
  name: "Home",
  components: {
    Todos,
    Integrantes
  },
};
</script>
