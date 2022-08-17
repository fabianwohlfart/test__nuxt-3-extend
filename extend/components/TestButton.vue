<template>
  <button
    type="button"
    @click.native="handleClick"
    >
    <slot></slot>
  </button>
</template>
<script setup>
  const handleClick = () => {
    console.log('Handle Click')
  }
</script>
