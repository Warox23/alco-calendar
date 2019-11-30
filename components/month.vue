<template>
  <div class="month">
    <div>January</div>
    <div class="days">
      <day
        :day-number="i"
        day-name="Monday"
        v-for="(i, k) in [
          1,
          2,
          3,
          4,
          5,
          6,
          7,
          8,
          9,
          10,
          11,
          12,
          13,
          14,
          15,
          16,
          17,
          18,
          19,
          20,
          21,
          22,
          23,
          24,
          25,
          26,
          27,
          28,
          29,
          30,
          31
        ]"
        :key="k"
      />
    </div>
  </div>
</template>

<script>
import day from "./day";

export default {
  name: "month",
  components: {
    day: day
  }
};
</script>

<style scoped>
.month {
  width: 290mm;
  height: 280mm;
  border: 3px solid #ccc;
}

.days {
  display: flex;
  flex-wrap: wrap;
}
</style>
