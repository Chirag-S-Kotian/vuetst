<script>
export default {
  data() {
    return {
      name: 'chirag ck',
      status: false,
    };
  },
},
</script>

<template>
  <h1>{{ name }}</h1>
  <p v-if="status">User is active</p>
</template>