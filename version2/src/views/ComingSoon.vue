<template>
  <div class="comingsoon">
    <!-- loader   -->
    <Loader />
    <!-- main start  -->
    <div id="main">
      <!-- header-->
      <Header />
      <!-- social-->
      <Social />
      <!-- Navigation -->
      <Navbar />
      <!-- wrapper  -->
      <div id="wrapper">
        <!-- content-->
        <div class="content full-height" data-pagetitle="Home slideshow">
          <!-- fs-slider-wrap  -->
          <div class="video-holder-wrap hero_entry">
            <!--slideshow-container-->
            <div class="slideshow-container">
              <div class="slideshow-container_wrap fl-wrap full-height">
                <div class="swiper-container">
                  <div class="swiper-wrapper">
                    <!--ms_item-->
                    <div class="swiper-slide">
                      <div class="ms-item_fs fl-wrap">
                        <div class="bg par-elem" data-bg="images/3.jpg"></div>
                      </div>
                    </div>
                    <!--ms_item end-->
                    <!--ms_item-->
                    <div class="swiper-slide">
                      <div class="ms-item_fs fl-wrap">
                        <div class="bg par-elem" data-bg="images/3.jpg"></div>
                      </div>
                    </div>
                    <!--ms_item end-->
                    <!--ms_item-->
                    <div class="swiper-slide">
                      <div class="ms-item_fs fl-wrap">
                        <div class="bg par-elem" data-bg="images/3.jpg"></div>
                      </div>
                    </div>
                    <!--ms_item end-->
                  </div>
                </div>
              </div>
            </div>
            <!--slideshow-container end-->
            <div class="overlay"></div>
            <div class="half-hero-wrap hhw-vis">
              <div class="hhw_header">
                <div class="rotate_text hero-decor-let">
                  <div>Web Development</div>
                  <div><span>Web Hosting</span></div>
                  <div>API Development</div>
                  <div><span>Ecommerce</span></div>
                </div>
              </div>
              <h1>
                Work In Progress - <br /><span>Creating Amazing</span> Designs<br/>Coming by<br><span>April, 2022</span>
              </h1>
              <div class="clearfix"></div>
              <a href="#" class="btn ajax fl-btn color-bg"
                ><span>My portfolio</span></a
              >
            </div>

            <!-- hero-facts-wrap -->
            <div class="hero-facts-wrap">
              <!-- inline-facts -->
              <div class="inline-facts">
                <div class="milestone-counter">
                  <div class="stats animaper">
                    <div class="num" data-content="0" data-num="25">0</div>
                  </div>
                </div>
                <h6>Finished projects</h6>
              </div>
              <!-- inline-facts end -->
              <!-- inline-facts  -->
              <div class="inline-facts">
                <div class="milestone-counter">
                  <div class="stats animaper">
                    <div class="num" data-content="0" data-num="2000">0</div>
                  </div>
                </div>
                <h6>Working hours</h6>
              </div>
              <!-- inline-facts end -->
              <!-- inline-facts  -->
              <div class="inline-facts">
                <div class="milestone-counter">
                  <div class="stats animaper">
                    <div class="num" data-content="0" data-num="4">0</div>
                  </div>
                </div>
                <h6>Awards won</h6>
              </div>
              <!-- inline-facts end -->
            </div>
          </div>
        </div>
        <!-- content end-->
        <!-- share-wrapper-->
        <div class="share-wrapper">
          <div class="close-share-btn">
            <i class="fal fa-long-arrow-left"></i>
          </div>
          <div class="share-container fl-wrap isShare"></div>
        </div>
        <!-- share-wrapper  end -->
      </div>
      <!-- wrapper end -->
      <!-- cursor-->
      <div class="element">
        <div class="element-item"></div>
      </div>
      <!-- cursor end-->
    </div>
    <!-- Main end -->
  </div>
</template>



<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Loader from "@/components/Loader.vue";
import Header from "@/components/Header.vue";
import Social from "@/components/Social.vue";
import Navbar from "@/components/Navbar.vue";

@Component({
  components: {
    Loader,
    Social,
    Header,
    Navbar,
  },
})
export default class ComingSoon extends Vue {}
</script>
