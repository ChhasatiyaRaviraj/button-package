<script setup>
</script>

<template>
  <main>
    <button>
      hello
    </button>
  </main>
</template>

<style lang="scss">
button {
  background: blue;
  margin: 12px;
  padding: 12px;
  border: 1px solid white;
  border-radius: 12px;
  color: white;
  font: 700;
  font-size: 16px;
  transition: 1s all;
  cursor: pointer;

  &:hover {
    font-size: 20px;
    background: red;
  }
}
</style>
