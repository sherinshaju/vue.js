<template>
  <div class="col-md-4">
    <div class="card">
      <div class="card-body">
        <p>This is some text within a card body {{ counter }}</p>
        <button v-on:click="greet">Add 1</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  data: {
    counter: 0
  },
  methods: {
    greet: function() {
      console.log("HI");
    }
  }
};

// console.log(counter)
</script>

    <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
