<template>
  <section class="container">
    <div>
      <h1 class="title">
        High-vis Helper
      </h1>
      <h2 class="subtitle">
        helps you organise the people who help you run your event.
      </h2>
    </div>
  </section>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style lang="scss">
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

h1 {
  font-size: 3rem;
  font-weight: bold;
  padding: 0 1rem;
}
h2 {
  font-size: 1.2rem;
  font-weight: lighter;
  padding: 0 1rem;
  span {
    color: #777;
    font-weight: normal;
    vertical-align: top;
  }
}
@media (max-width: 550px) {
  h1 {
    font-size: 1.8rem;
  }
  h2 {
    font-size: 1.8rem;
  }
}

</style>
