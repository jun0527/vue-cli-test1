<template>
  <div class="card">
    <div class="card-body">This is some text within a card body.</div>
    {{text}}
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: '我是內容',
    };
  },
};
</script>
