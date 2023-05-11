<template>
<header_component/>
<block_1_component/>
  <block_2_comlonent/>
  <block_3_component/>
  <block_4_component/>
</template>

<script>
import header_component from "@/components/header_component.vue";
import block_1_component from "@/components/block_1_component.vue";
import block_2_comlonent from "@/components/block_2_comlonent.vue";
import block_3_component from "@/components/block_3_component.vue";
import block_4_component from "@/components/block_4_component.vue";

export default {
  name: "home_component",
  components: {
    block_4_component,
    block_3_component,
    block_2_comlonent,
    block_1_component,
    header_component
  }
}
</script>

<style scoped>

</style>