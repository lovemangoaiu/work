<template>
  <div>
    <homeHeader></homeHeader>
    <ResourcePlat></ResourcePlat>
  </div>
</template>
<script>
import homeHeader from "./Header/index.vue";
import ResourcePlat from "./ResourcePlat/index.vue";
export default {
  name: "HomeV",
  components: {
    homeHeader,
    ResourcePlat,
  },
  data() {
    return {};
  },
  methods: {},
  created() {},
  mounted() {},
};
</script>
<style lang="" scoped></style>
