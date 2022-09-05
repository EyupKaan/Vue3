<template>
  <h4>Something went wrond!</h4>
  <p>{{ error }}</p>
</template>

<script>
export default {
  props: ['error']
}
</script>
