<template>
  <div class="full-width center-content">
    <hello-component name="World" />
    <img src="../static/img/ThelmaHeadshot.jpeg"><img/>
  </div>
</template>
<script>
import HelloComponent from './components/HelloComponent.vue'
export default {
  components: {
    HelloComponent
  }
}
</script>
