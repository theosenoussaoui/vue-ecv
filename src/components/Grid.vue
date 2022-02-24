<template>
  <section class="grid gap-2 grid-cols-2 md:grid-cols-3 xl:grid-cols-6 m-4 grid-flow-row-dense">
    <div class="boxes_style boxes_placement">1</div>
    <div class="boxes_style boxes_placement col-span-3">2 (col-span-3)</div>
    <div class="boxes_style boxes_placement">3</div>
    <div class="boxes_style boxes_placement">4</div>
    <div class="boxes_style boxes_placement">5</div>
    <div class="boxes_style boxes_placement">6</div>
    <div class="boxes_style boxes_placement col-span-2">7 (col-span-2)</div>
    <div class="boxes_style boxes_placement">8</div>
    <div class="boxes_style boxes_placement">9</div>
    <div class="boxes_style boxes_placement row-span-2">10 (row-span-2)</div>
    <div class="boxes_style boxes_placement">11</div>
    <div class="boxes_style boxes_placement">12</div>
    <div class="boxes_style boxes_placement">13</div>
    <div class="boxes_style boxes_placement col-start-5 col-end-7">14 (col-start-5 col-end-7)</div>
    <div class="boxes_style boxes_placement">15</div>
    <div class="boxes_style boxes_placement">16</div>
    <div class="boxes_style boxes_placement col-start-2 col-span-2">17 (col-start-2 col-span-2)</div>
    <div class="boxes_style boxes_placement">18</div>
    <div class="boxes_style boxes_placement">19</div>
    <div class="boxes_style boxes_placement">20</div>
    <div class="boxes_style boxes_placement">21</div>
    <div class="boxes_style boxes_placement">22</div>
  </section>
</template>

<script>
export default {
  name: "GridExample",
};
</script>

<style lang="css">
.boxes_style {
  @apply bg-slate-200 border-2 border-amber-700 p-8 rounded text-amber-700 font-bold text-xl;
}
/*.boxes_placement {*/
/*  @apply self-center;*/
/*}*/
</style>
