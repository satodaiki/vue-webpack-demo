<template>
  <div>
    <button>-</button>
    <span>{{ count }}</span>
    <button>+</button>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator';

@Component
export default class Counter extends Vue {
  public count: number = 0;
}
</script>
