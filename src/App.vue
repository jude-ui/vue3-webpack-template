<template>
  <HelloWorld :msg="message" />
  <HelloWorld msg="Good" />
</template>

<script>
import HelloWorld from '~/components/HelloWorld'

export default {
  components: {
    HelloWorld
  },
  data() {
    return {
      message: 'Hello Vue!'
    }
  }
}
</script>