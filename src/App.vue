<script>
export default {
  data() {
    return {
      name: 'chirag ck',
      status: 'active',
    };
  },
};
</script>

<template>
  <h1>{{ name }}</h1>
  <p v-if="status">User is active</p>
  <p v-else-if="status === 'inactive'">User is inactive</p>
  <p v-else>User is not active</p>
</template>