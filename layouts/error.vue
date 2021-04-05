<template>
  <div>
    <h1 v-if="error.statusCode">Error Page!</h1>
  </div>
</template>

<script>
export default {
  props: ["error"],
};
</script>