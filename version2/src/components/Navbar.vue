<template>
  <div class="nav">
                <!-- navigation menu-->	
                <div class="nav-holder">
                    <div class="nav-holder-wrap but-hol">
                        <div class="nav-container fl-wrap">
                            <!-- nav -->
                            <nav class="nav-inner" id="menu">
                                <ul>
                                    <li>
                                        <a href="#" class="act-link">Home</a>
                                    </li>
                                    <li><a href="#" class="ajax">About</a></li>
                                    <li>
                                        <a href="#">Portfolio</a>
                                    </li>
                                    <li>
                                      <a href="#" class="ajax">Contacts</a>
                                      </li>
                                    <li>
                                      <a href="#" class="ajax" target="_blank">Resume</a>
                                    </li>
                                </ul>
                            </nav>
                            <!-- nav end-->
                        </div>
                        <div class="nav-footer"><span>&#169; nashipaetuukuo 2020  /  All rights reserved. </span></div>
                        <div class="nav-holder-wrap_line"></div>
                        <div class="nav-holder-wrap_dec"></div>
                    </div>
                </div>
                <div class="nav-overlay"></div>
                <!-- navigation menu end  -->	
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class Navbar extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
