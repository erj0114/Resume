<template>
  <div class="work-history">
    <div class="left-side">
      <slot name="date"></slot>
    </div>
    <div class="right-side">
      <div class="position">
        <slot name="position"></slot>
      </div>
      <div class="company-and-location">
        <slot name="companyAndLocation"></slot>
      </div>
      <slot name="experience"></slot>
    </div>
  </div>
</template>

<script>
export default {
  name: 'WorkHistory',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.position {
  font-weight: bold;
}
.company-and-location {
  font-style: italic;
}
</style>
