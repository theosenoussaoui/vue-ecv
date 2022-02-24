<template>
  <section class="grid gap-2 grid-cols-3 place-items-center h-96">
    <div class="boxes_style boxes_placement">1</div>
    <div class="boxes_style boxes_placement">2</div>
    <div class="boxes_style boxes_placement">3</div>
    <div class="boxes_style boxes_placement">4</div>
    <div class="boxes_style boxes_placement">5</div>
    <div class="boxes_style boxes_placement">6</div>
  </section>
</template>

<script>
export default {
  name: "GridPlacementExample",
};
</script>

<style lang="css" scoped>
.boxes_style {
  @apply bg-green-200 border-2 border-green-700 rounded text-green-700 font-bold text-xl w-24 h-24;
}
/*.boxes_placement {*/
/*  @apply self-center;*/
/*}*/
</style>
