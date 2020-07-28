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
.work-history {
  display: flex;
  flex-direction: row;
  border-bottom: 1px solid rgba(0,0,0,.1);
  padding: 10px;
}
.left-side {
  min-width: 100px;
  border-right: 1px solid rgba(0,0,0,.1);
}
.right-side {
  padding-left: 10px;
}
.position {
  font-weight: bold;
}
.company-and-location {
  font-style: italic;
}
@media (max-width: 768px) { 
  .work-history {
    flex-direction: column;
  }
  .right-side {
    padding-left: 0px;
  }
}
</style>
