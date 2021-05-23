<template>
  <div>
    <service/>
    <skills />
  </div>
</template>

<script>
import Service from '../components/Service.vue';
import Skills from "../components/Skills.vue";
export default {
  components: { Skills, Service },
};
</script>

