<template>
  <Generic :item="item">
    <template #indicator>
      <!-- top right area, empty by default -->
    </template>
  </Generic>
</template>

<script>
import Generic from "./Generic.vue";

export default {
  name: "APC_UPS",
  props: {
    item: Object,
  },
  components: {
    Generic,
  }
};
</script>
