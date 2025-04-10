<script setup lang="ts">
import { MasonryGrid, JustifiedGrid, FrameGrid, PackingGrid } from "@egjs/vue-grid";
</script>

<template>
  <masonry-grid
      class="container"
      :gap="10"
      align="justify"
  >
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
    <div class="item">5</div>
    <div class="item">6</div>
    <div class="item">7</div>
    <div class="item">8</div>
    <div class="item">9</div>
    <div class="item">10</div>
  </masonry-grid>
</template>
