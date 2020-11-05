<template>
  <div class="social">
                <!-- left-header-->      
            <aside class="left-header">
                <span class="lh_dec color-bg"></span>
                <div class="left-header_social">
                    <ul >
                        <li><a href="https://www.linkedin.com/in/lorna-kimani-16186bb2/" target="_blank"><i class="fab fa-linkedin-in"></i></a></li>
                        <li><a href="https://github.com/Lornakimani62" target="_blank"><i class="fab fa-github"></i></a></li>
                        <li><a href="https://codepen.io/lornakimani62" target="_blank"><i class="fab fa-codepen"></i></a></li>
                    </ul>
                </div>
            </aside>
            <!-- left-header end--> 
            <!-- share button--> 
            <div class="share-btn showshare color-bg"><span>Share <i class="fal fa-plus"></i></span></div>
            <!-- share button end--> 
            <!-- right header--> 
            <div class="hc_dec_color">
                <div class="page-subtitle"><span></span></div>
            </div>
            <!-- right header end--> 
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class Social extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
