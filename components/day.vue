<template>
  <div class="card">
    <div class="left-side">
      <span class="alco-date"> {{ dayNumber }} of {{ dayName }} </span>
    </div>
    <div class="right-side"></div>
  </div>
</template>

<script>
export default {
  props: ["dayNumber", "dayName"],
  name: "day"
};
</script>

<style scoped>
.card {
  height: 40mm;
  width: 40mm;
  background: green;
  display: flex;
  flex-direction: column;
}

.left-side {
  background: red;
  display: flex;
  justify-content: center;
  align-items: center;
}

.right-side {
  background: blue;
}

.alco-date {
  font-size: 16px;
}
</style>
