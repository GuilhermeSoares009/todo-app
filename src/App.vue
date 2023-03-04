<template>
  <main id="todo" class=".container">
    <div id="todo_cabecalho" class=".col-md-8">
    </div>
    <Cabecalho />
  </main>
</template>

<script>
import { defineComponent } from 'vue';
import Cabecalho from './components/CabecalhoTodo.vue'
export default defineComponent({
  name: 'App',
  components: {
    Cabecalho
  }
});
</script>

<style></style>
