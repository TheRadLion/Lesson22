<template>
  <li class="card">
    <img v-bind:src="award.imageurl" style="width:100%">
    <div class="container">
      <h4>
        <b>{{ award.title }}</b>
      </h4>
      <p>{{ award.detail }}</p>
    </div>
  </li>
</template>

<script>
export default {
  props: {
    award: {
      type: Object,
      required: true
    }
  }
};
</script>

<style>
.card {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  transition: 0.3s;
  max-width: 500px;
  margin: 10px;
}

/* On mouse-over, add a deeper shadow */
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
  transition: 0.3s;
}

/* Add some padding inside the card container */
.container {
  padding: 2px 16px;
}
</style>
