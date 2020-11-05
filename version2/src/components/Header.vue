<template>
  <div class="header">
    <header class="main-header">
        <!-- logo  -->
        <a href="index.html" class="ajax logo-holder"><img src="images/logo.png" alt=""></a>
        <!-- logo end -->
        <!-- nav-button-wrap-->
        <div class="nav-button but-hol">
            <span  class="ncs"></span>
            <span class="nos"></span>
            <span class="nbs"></span>
            <div class="menu-button-text">Menu</div>
        </div>
        <!-- nav-button-wrap end--> 
        <!-- header-contacts--> 
        <div class="header-contacts">
            <ul>
                <li><span>01. Call </span> <a href="tel:+254724276722">+254724276722</a></li>
                <li><span>02. Write </span> <a href="mailto:kimanilorna@yahoo.com">kimanilorna@yahoo.com</a></li>
            </ul>
            <a href="contacts.html" class="ajax contacts-btn">Get in touch</a>
        </div>
        <!-- header-contacts end--> 
    </header>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class Header extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
