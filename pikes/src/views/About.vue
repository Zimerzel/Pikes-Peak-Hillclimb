<template>
  <div class="about">
    <HelloWorld msg="Pikes Peak International Hill Climb"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'About',
  components: {
    HelloWorld
  }
}
</script>
