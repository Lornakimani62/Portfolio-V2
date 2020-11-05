<template>
  <div class="loader">
            <div class="loader">
        <div class="loading-text-container "><span class="loading-text">Loading</span> <span class="loader_count">0</span></div>
        <div class="loader-anim"></div>
        <div class="loader-anim2 color-bg"></div>
        </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class Loader extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
