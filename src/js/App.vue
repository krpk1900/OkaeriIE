<template>
  <div id="myapp">
    <vue-star animate="animated rubberBand" color="#F05654">
      <i slot="icon" class="fa fa-heart"></i>
    </vue-star>
  </div>
</template>

<script>
import VueStar from 'vue-star'

export default {
  name: "app",
  components: {
    VueStar
  }
};
</script>
