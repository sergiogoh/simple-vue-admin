<template>
  <div class="made-by-component text--center pb-3">
    <span>
      ©2020. Contributed by
      <a href="https://github.com/sergiogoh/simple-vue-admin" class="link">sergiogoh</a>
    </span>
  </div>
</template>

<script>
export default {
  name: 'made-by',
}
</script>

<style lang="scss">
.made-by-component {
  position: absolute;
  bottom: 0;
  width: 100%;
}
</style>
