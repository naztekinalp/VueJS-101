<template>
  <div class="home">
    <Main/>
    <Sidebar/>
  </div>
</template>

<script>
import Main from '../components/Main.vue';
import Sidebar from '../components/Sidebar.vue';

export default {
  name: 'home',
  components: {
    Main,
    Sidebar,
  },
};
</script>
