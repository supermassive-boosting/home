<script setup lang="ts">
import { ref } from "vue";

const count = ref(0);
</script>

<template>
  <h1>House of Naked Dreams</h1>

  <div class="card">
    <button type="button" @click="count++">
      bastıkça artan buton: {{ count }}
    </button>
  </div>
</template>
