<template>
  <div class="card">
    <div class="card-image">
      <span>Image</span>
    </div>
    <div class="card-content">
      <h3>Title</h3>
    </div>
    <div class="card-action">
      <button>Add to card</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
};
</script>

<style scoped>
.card {
  border-radius: 10px;
  overflow: hidden;
  width: 200px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  text-align: center;
  font-family: Arial, sans-serif;
}

.card-image {
  background-color: #bdbdbd;
  padding: 20px;
}

.card-content {
  padding: 10px;
  background-color: #ffffff;
}

.card-action {
  padding: 10px;
}

button {
  border: 1px solid #ccc;
  padding: 10px;
  border-radius: 5px;
  background-color: #f0f0f0;
  cursor: pointer;
}

button:hover {
  background-color: #e0e0e0;
}
</style>
