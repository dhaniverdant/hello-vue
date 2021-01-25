<template>
  <div class="desc-text">{{ $data }}</div>
</template>

<script>
  export default {
    name: 'Description',
    data: function() {
      const descTitle = 'contoh data';

      return descTitle;
    }
  }
</script>

<style lang="scss" scoped>
  $color: blue;

  .desc-text {
    color: $color;
    font-size: 20px;
  }
</style>
