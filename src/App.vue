<template>
    <div>
        <TeleportTest />
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import TeleportTest from "./TeleportTest.vue";

export default defineComponent({
  name: 'App',
  components: {
      TeleportTest
  }
})
</script>
