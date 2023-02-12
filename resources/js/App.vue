<template>
  <div>
    <div class="text-red-500">test</div>
    <div class="flex flex-col">
      <dix class="flex bg-red-200">a</dix>
      <dix class="flex bg-gray-600">b</dix>
    </div>
    <HelloWorld msg="Hello Vue 2 + Vite" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
export default {
  components: {
    HelloWorld,
  },
};
</script>
