<template>
  <div>
    <p>Hello, World!</p>
    <counter/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Counter from '@/components/Counter';

@Component({
  components: {
    Counter,
  },
})
export default class App extends Vue {}
</script>

<style lang="scss" scope>

</style>
