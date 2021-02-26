<template>
  <div class="container"></div>
</template>

<script>
import { Header } from 'Header'
import { Footer } from 'Footer'
import { Content } from 'Content'

export default {
  data() {
    return {}
  },
  components: {
    Header,
    Content,
    Footer,
  },
}
</script>

<style>
.container {
  display: grid;
  grid-template-rows: 20% auto 15%;
  grid-template-columns: 10% auto 10%;
}
</style>
