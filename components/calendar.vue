<template>
  <div class="calendar">
    <div class="row">
      <month></month>
      <month></month>
      <month></month>
      <month></month>
    </div>

    <div class="row">
      <month></month>
      <month></month>
      <month></month>
      <month></month>
    </div>

    <div class="row">
      <month></month>
      <month></month>
      <month></month>
      <month></month>
    </div>
  </div>
</template>

<script>
import month from "./month";

export default {
  name: "calendar",
  components: {
    month: month
  }
};
</script>

<style scoped>
.calendar {
  width: 1189mm;
  height: 841mm;

  background: aquamarine;
  padding: 30mm;
}

.row {
  display: flex;
  justify-content: space-between;
}
</style>
