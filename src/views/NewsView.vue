<template>
  <section class="row">
    <div>
      <TitleMessage title="フォトギャラリー"/>
    </div>
  </section>
  <section class="row">
    <main>
      <CardGrid/>
    </main>
  </section>
</template>


<script setup lang="ts">
import CardGrid from "@/components/CardGrid.vue";
import TitleMessage from "@/components/TitleMessage.vue";
</script>