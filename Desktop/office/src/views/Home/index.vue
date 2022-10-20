<template>
  <div>
    <homeHeader></homeHeader>
    <ResourcePlat></ResourcePlat>
    <IncubationCompany></IncubationCompany>
    <GraduationCompany></GraduationCompany>
    <ParkCard></ParkCard>
  </div>
</template>
<script>
import homeHeader from "./Header/index.vue";
import ResourcePlat from "./ResourcePlat/index.vue";
import IncubationCompany from "./IncubationCompany/index.vue"
import GraduationCompany from "./GraduationCompany/index.vue"
import ParkCard from "./ParkCard/index.vue"
export default {
  name: "HomeV",
  components: {
    homeHeader,
    ResourcePlat,
    IncubationCompany,
    GraduationCompany,
    ParkCard
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
