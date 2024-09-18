<template>
  <div>
    <h2>Danh sách kết quả</h2>
    <ul>
      <li>{{ num1 }} + {{ num2 }} = {{ add(num1, num2) }}</li>
      <li>{{ num1 }} - {{ num2 }} = {{ subtract(num1, num2) }}</li>
      <li>{{ num1 }} * {{ num2 }} = {{ multiply(num1, num2) }}</li>
      <li>{{ num1 }} / {{ num2 }} = {{ divide(num1, num2) }}</li>
    </ul>
  </div>
</template>
<script>
export default {
  name: 'Calculation',
  data() {
    return {
      num1: 10,
      num2: 10
    };
  },
  methods: {
    add(a, b) {
      return a + b;
    },
    subtract(a, b) {
      return a - b;
    },
    multiply(a, b) {
      return a * b;
    },
    divide(a, b) {
      return a / b;
    }
  }
}
</script>