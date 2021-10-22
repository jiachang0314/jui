<template>
  <div class="j-button">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'j-button',
  props: {
    type: String
  }
}
</script>

<style scoped>
  .j-button {
      display: inline-block;
      padding: 3px 6px;
      background: #000;
      color: #fff;
  }
</style>
