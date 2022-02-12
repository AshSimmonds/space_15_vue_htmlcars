<template>
  <div class="home">
    <h1 class="logo">&#0133;</h1>
    <HelloWorld msg="Welcome to Your Vue.js + HTMLCARS + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {}
</script>

<style scoped lang="scss">
  .logo {
    border-bottom: unset;
    font-size: 16rem;
    margin-bottom: -2rem;
    color: #42b983;
  }
</style>
