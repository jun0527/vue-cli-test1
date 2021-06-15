<template>
  <div class="about">
    <h1>This is an about page</h1>
    {{name}}
    <Card></Card>
  </div>
</template>

<script>
import Card from '@/components/Card.vue';

export default {
  data() {
    return {
      name: process.env.VUE_APP_NAME,
    };
  },
  components: {
    Card,
  },
};
</script>
