<template>
  <div class="about">
   <!-- loader   -->
        <div class="loader">
            <div class="loading-text-container "><span class="loading-text">Loading</span> <span class="loader_count">0</span></div>
            <div class="loader-anim"></div>
            <div class="loader-anim2 color-bg"></div>
        </div>
        <!-- loader  end-->
        <!-- main start  -->
        <div id="main">
            <!-- header--> 
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
            <!-- header end--> 
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
            <!-- wrapper  -->	
            <div id="wrapper">
                <!-- navigation menu-->	
                <div class="nav-holder">
                    <div class="nav-holder-wrap but-hol">
                        <div class="nav-container fl-wrap">
                            <!-- nav -->
                            <nav class="nav-inner" id="menu">
                                <ul>
                                    <li>
                                        <a href="#">Home</a>
                                        <!--level 2 -->
                                        <ul>
                                            <li><a href="index.html" class="ajax">Slider</a></li>
                                            <li><a href="index2.html" class="ajax">Carousel</a></li>
                                            <li><a href="index3.html" class="ajax">Slideshow</a></li>
                                            <li><a href="index4.html" class="ajax">Video</a></li>
                                            <li><a href="index5.html" class="ajax">Image</a></li>
                                        </ul>
                                        <!--level 2 end -->
                                    </li>
                                    <li><a href="about.html" class="ajax act-link">About</a></li>
                                    <li>
                                        <a href="#">Portfolio</a>
                                        <!--level 2 -->
                                        <ul>
                                            <li><a href="portfolio.html" class="ajax">Horizonatal</a></li>
                                            <li><a href="portfolio3.html" class="ajax">Fullscreen Grid </a></li>
                                            <li><a href="portfolio2.html" class="ajax">Column Grid</a></li>
                                            <li><a href="portfolio4.html" class="ajax">Column Grid 2</a></li>
                                            <li>
                                                <a href="#">Single</a>
                                                <!--level 3 -->
                                                <ul>
                                                    <li><a href="portfolio-single.html" class="ajax">Style 1</a></li>
                                                    <li><a href="portfolio-single2.html" class="ajax">Style 2</a></li>
                                                    <li><a href="portfolio-single3.html" class="ajax">Style 3</a></li>
                                                    <li><a href="portfolio-single4.html" class="ajax">Style 4</a></li>
                                                    <li><a href="portfolio-single5.html" class="ajax">Style 5</a></li>
                                                </ul>
                                                <!--level 3 end -->
                                            </li>
                                        </ul>
                                        <!--level 2 end -->
                                    </li>
                                    <li><a href="contacts.html" class="ajax">Contacts</a></li>
                                    <li><a href="blog.html" class="ajax">Blog</a></li>
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
                <!-- content-->    
                <div class="content"  data-pagetitle="about me">
                    <div class="page-scroll-nav">
                        <nav class="scroll-init page-scroll-nav_wrap">
                            <ul class="no-list-style init_hidden_filter">
                                <li><a class="scroll-link fbgs act-sec" href="#sec1" data-bgtext="01"><span>About</span></a></li>
                                <li><a class="scroll-link fbgs" href="#sec2" data-bgtext="02"><span>Services</span></a></li>
                                <li><a class="scroll-link fbgs" href="#sec4" data-bgtext="03"><span>Skills</span></a></li>
                                <li><a class="scroll-link fbgs" href="#sec5" data-bgtext="04"><span>Clients</span></a></li>
                            </ul>
                            <div class="psn_button act-filter"><i class="fal fa-sort"></i> FIlter </div>
                        </nav>
                    </div>
                    <!-- hero-section-dec-->                  
                    <div class="hero-section-dec color-bg">
                        <div class="progress-indicator">
                            <svg xmlns="http://www.w3.org/2000/svg"
                                viewBox="-1 -1 34 34">
                                <circle cx="16" cy="16" r="15.9155"
                                    class="progress-bar__background" />
                                <circle cx="16" cy="16" r="15.9155"
                                    class="progress-bar__progress 
                                    js-progress-bar" />
                            </svg>
                        </div>
                    </div>
                    <!-- hero-section-dec end--> 
                    <!--fixed-column-wrap-->
                    <div class="fixed-column-wrap">
                        <div class="pr-bg"></div>
                        <!--fixed-column-wrap-content-->
                        <div class="fixed-column-wrap-content">
                            <!--slideshow-container-->
                            <div class="slideshow-container">
                                <div class="slideshow-container_wrap fl-wrap full-height">
                                    <div class="swiper-container">
                                        <div class="swiper-wrapper">
                                            <!--ms_item-->
                                            <div class="swiper-slide">
                                                <div class="ms-item_fs fl-wrap">
                                                    <div class="bg par-elem"  data-bg="images/1.jpg"  ></div>
                                                </div>
                                            </div>
                                            <!--ms_item end-->
                                            <!--ms_item-->
                                            <div class="swiper-slide ">
                                                <div class="ms-item_fs fl-wrap">
                                                    <div class="bg par-elem"  data-bg="images/1.jpg"></div>
                                                </div>
                                            </div>
                                            <!--ms_item end-->
                                            <!--ms_item-->
                                            <div class="swiper-slide">
                                                <div class="ms-item_fs fl-wrap">
                                                    <div class="bg par-elem"  data-bg="images/1.jpg"></div>
                                                </div>
                                            </div>
                                            <!--ms_item end-->
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <!--slideshow-container end--> 
                            <div class="overlay"></div>
                            <div class="progress-bar-wrap bot-element">
                                <div class="progress-bar"></div>
                            </div>
                            <!--fixed-column-wrap_title-->
                            <div class="fixed-column-wrap_title first-tile_load">
                                <h2>About <br> Me</h2>
                                <p>I'm a software engineer based in Nairobi, Kenya specializing in building (and occasionally designing) exceptional websites, applications, and everything in between.
                                    </p>
                            </div>
                            <!--fixed-column-wrap_title end-->
                            <div class="fixed-column-dec"></div>
                            <div class="section-counter">
                                <div class="sc_current"><span>01</span></div>
                                <div class="sc_total"></div>
                            </div>
                            <div class="fcwc-pagination fcwc-wrap"></div>
                        </div>
                        <!--fixed-column-wrap-content end-->                                     
                    </div>
                    <!--fixed-column-wrap end-->
                    <!--column-wrap--> 
                    <div class="column-wrap">
                        <!--column-wrap-container -->   
                        <div class="column-wrap-container fl-wrap">
                            <div class="col-wc_dec"></div>
                            <section class="scroll_sec" id="sec1">
                                <div class="container">
                                    <div class="section-title">
                                        <h3>Some   Words About Me  </h3>
                                        <p>Hi there <span style='font-size:20px;'>&#9995;</span>, I'm name is Lorna Nashipae a Software Engineer based in Nairobi,Kenya</p>
                                    </div>
                                    <div class="row">
                                        <div class="col-sm-5">
                                            <div class="dec-img   fl-wrap">
                                                <img src="images/bulb-5665770_1920.jpg" class="respimg" alt="">
                                                <a class="video_link image-popup" href="https://vimeo.com/34741214"><i class="fas fa-play"></i><span>Play Story video</span></a>
                                            </div>
                                        </div>
                                        <div class="col-sm-7">
                                            <div class="main-about fl-wrap">
                                                <h2>Innovative solutions to boost <br><span> your creative </span>  projects</h2>
                                                <p>I have been working with web development since 2018, the period
                                                    during which I have worked in different environments, including startups. I am a self-motivated and self-taught professional who likes to solve
                                                    problems.
                                                    </p>
                                                <p>I merge a passion for usability and user experience with technical
                                                    knowledge to create cool digital experiences. My repertoire includes
                                                    programming languages and tools such as ReactJS, EmberJS, Vuejs,
                                                    Nodejs, Expressjs, WordPress, MySQL, PostgreSQL, Nginx and Apache
                                                    server configuration, Gulp, SASS, LESS, Bootstrap, jQuery, and more.
                                                    </p>
                                                <div class="facts-container fl-wrap">
                                                    <!-- inline-facts -->
                                                    <div class="inline-facts-wrap">
                                                        <div class="inline-facts">
                                                            <div class="milestone-counter">
                                                                <div class="stats animaper">
                                                                    <div class="num" data-content="0" data-num="35">0</div>
                                                                </div>
                                                            </div>
                                                            <h6>Finished projects</h6>
                                                        </div>
                                                    </div>
                                                    <!-- inline-facts end -->
                                                    <!-- inline-facts  -->
                                                    <div class="inline-facts-wrap">
                                                        <div class="inline-facts">
                                                            <div class="milestone-counter">
                                                                <div class="stats animaper">
                                                                    <div class="num" data-content="0" data-num="2000">0</div>
                                                                </div>
                                                            </div>
                                                            <h6>Working hours</h6>
                                                        </div>
                                                    </div>
                                                    <!-- inline-facts end -->
                                                    <!-- inline-facts  -->
                                                    <div class="inline-facts-wrap">
                                                        <div class="inline-facts">
                                                            <div class="milestone-counter">
                                                                <div class="stats animaper">
                                                                    <div class="num" data-content="0" data-num="2">0</div>
                                                                </div>
                                                            </div>
                                                            <h6>Awards won</h6>
                                                        </div>
                                                    </div>
                                                    <!-- inline-facts end --> 
                                                </div>
                                                <a href="portfolio.html" class="btn ajax  color-bg  fl-btn"><span>My Portfolio</span></a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="section-number"> <span>0</span>1. </div>
                            </section>
                            <!-- section end-->
                            <div class="section-separator fl-wrap"><span></span></div>
                            <!-- section  --> 
                            <section class="scroll_sec" id="sec2">
                                <div class="container">
                                    <div class="section-title">
                                        <h3>Services Provided</h3>
                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas in pulvinar neque. Nulla finibus lobortis pulvinar.  </p>
                                    </div>
                                    <!--process-wrap  -->
                                    <div class="process-wrap fl-wrap">
                                        <div class="row">
                                            <div class=" col-sm-6">
                                                <div class="process-details">
                                                    <span class="pd-icon">
                                                    <i class="fal fa-desktop"></i>
                                                    </span>
                                                    <h4>Web Development</h4>
                                                    <div class="clearfix"></div>
                                                    <p>Exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor.</p>
                                                    <span class="process-numder">01.</span>
                                                    <div class="show-phdc"><i class="fal fa-plus"></i> <span>Details</span></div>
                                                    <div class="proces-details-content">
                                                        <div class="close-hidden_pdc"><i class="fal fa-times"></i></div>
                                                        <div class="proces-details-content-wrap">
                                                            <ul class="pdcw_list fl-wrap">
                                                                <li>Concept</li>
                                                                <li>Design</li>
                                                                <li>3D Modeling</li>
                                                            </ul>
                                                            <p>Cras mattis iudicium purus sit amet fermentum at nos hinc posthac, sitientis piros afros. Lorem ipsum dolor sit amet, consectetur adipisici elit, petierunt uti sibi concilium totius Galliae in diem sed eius mod tempor incidunt ut labore et dolore magna aliqua. Pellentesque habitant morbi tristique senectus et netus piros labore et dolore magna.</p>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class=" col-sm-6">
                                                <div class="process-details">
                                                    <span class="pd-icon">
                                                    <i class="fal fa-mobile-android"></i>
                                                    </span>
                                                    <h4>UI/UX Design</h4>
                                                    <div class="clearfix"></div>
                                                    <p>Exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor.</p>
                                                    <span class="process-numder">03.</span>
                                                    <div class="show-phdc"><i class="fal fa-plus"></i> <span>Details</span></div>
                                                    <div class="proces-details-content">
                                                        <div class="close-hidden_pdc"><i class="fal fa-times"></i></div>
                                                        <div class="proces-details-content-wrap">
                                                            <ul class="pdcw_list fl-wrap">
                                                                <li>Concept</li>
                                                                <li>Design</li>
                                                                <li>3D Modeling</li>
                                                            </ul>
                                                            <p>Cras mattis iudicium purus sit amet fermentum at nos hinc posthac, sitientis piros afros. Lorem ipsum dolor sit amet, consectetur adipisici elit, petierunt uti sibi concilium totius Galliae in diem sed eius mod tempor incidunt ut labore et dolore magna aliqua. Pellentesque habitant morbi tristique senectus et netus piros labore et dolore magna.</p>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <!--process-wrap   end-->                                         
                                    <div class="srv-link-text fl-wrap">
                                        <h4>Ready to order your project ? Visit my contacts page :  </h4>
                                        <a href="contacts.html" class="btn ajax color-bg  fl-btn"><span>Contacts</span></a>
                                    </div>
                                </div>
                                <div class="section-number"> <span>0</span>2. </div>
                            </section>
                            <!-- section end-->
                            <div class="section-separator fl-wrap"><span></span></div>     
                            <!-- section  -->                      
                            <section class="scroll_sec" id="sec4">
                                <div class="container">
                                    <div class="section-title">
                                        <h3>Developer  and  Language  Skills</h3>
                                        <p>Here are a few technologies I've been working with alot:</p>
                                    </div>
                                    <div class="row">
                                        <div class="col-md-9">
                                            <div class="skillbar-box animaper">
                                                <div class="pr-bg pr-bg-white"></div>
                                                <!-- skill 1-->
                                                <div class="custom-skillbar-title"><span>Vuejs</span></div>
                                                <div class="skill-bar-percent">75%</div>
                                                <div class="skillbar-bg" data-percent="95%">
                                                    <div class="custom-skillbar"></div>
                                                </div>
                                                <!-- skill 2-->
                                                <div class="custom-skillbar-title"><span>HTML/Css</span></div>
                                                <div class="skill-bar-percent">85%</div>
                                                <div class="skillbar-bg" data-percent="65%">
                                                    <div class="custom-skillbar"></div>
                                                </div>
                                                <!-- skill 3-->
                                                <div class="custom-skillbar-title"><span>Nodejs</span></div>
                                                <div class="skill-bar-percent">80%</div>
                                                <div class="skillbar-bg" data-percent="95%">
                                                    <div class="custom-skillbar"></div>
                                                </div>
                                                <!-- skill 4-->
                                                <div class="custom-skillbar-title"><span>Expressjs</span></div>
                                                <div class="skill-bar-percent">70%</div>
                                                <div class="skillbar-bg" data-percent="70%">
                                                    <div class="custom-skillbar"></div>
                                                </div>
                                                <!-- skill 5-->
                                                <div class="custom-skillbar-title"><span>Javascript</span></div>
                                                <div class="skill-bar-percent">60%</div>
                                                <div class="skillbar-bg" data-percent="60%">
                                                    <div class="custom-skillbar"></div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="col-md-3">
                                            <div class="piechart-holder animaper" data-skcolor="#F57500">
                                                <!-- 1  -->
                                                <div class="piechart">
                                                    <span class="chart" data-percent="85">
                                                    <span class="percent"></span>
                                                    </span>
                                                    <div class="clearfix"></div>
                                                    <h4>English</h4>
                                                </div>
                                                <!-- 1 end -->
                                                <!-- 2  -->
                                                <div class="piechart">
                                                    <span class="chart" data-percent="95">
                                                    <span class="percent"></span>
                                                    </span>
                                                    <div class="clearfix"></div>
                                                    <h4>Swahili</h4>
                                                </div>
                                                <!-- 2 end  -->
                                                <!-- 2  -->
                                                <div class="piechart">
                                                    <span class="chart" data-percent="25">
                                                    <span class="percent"></span>
                                                    </span>
                                                    <div class="clearfix"></div>
                                                    <h4>Korean</h4>
                                                </div>
                                                <!-- 2 end  -->                                                 
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="section-number"> <span>0</span>4. </div>
                            </section>
                            <!--section end-->
                            <div class="section-separator fl-wrap"><span></span></div>
                            <!--section  --> 
                            <section class="scroll_sec" id="sec5">
                                <div class="container">
                                    <div class="section-title">
                                        <h3>Clents And Testimonilas</h3>
                                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas in pulvinar neque. Nulla finibus lobortis pulvinar.  </p>
                                    </div>
                                    <div class="testimonilas-carousel-wrap fl-wrap">
                                        <div class="tc-button tc-button-next"><i class="fal fa-angle-right"></i></div>
                                        <div class="tc-button tc-button-prev"><i class="fal fa-angle-left"></i></div>
                                        <div class="testimonilas-carousel">
                                            <div class="swiper-container">
                                                <div class="swiper-wrapper">
                                                    <!--testi-item-->
                                                    <div class="swiper-slide">
                                                        <div class="testi-item fl-wrap">
                                                            <div class="testi-avatar"><img src="images/avatar/1.jpg" alt=""></div>
                                                            <div class="testimonilas-text fl-wrap">
                                                                <h3>Andy Dimasky</h3>
                                                                <p>"Exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor. Duis autem vel eum  sit amet semiriure dolor consectetur adipiscing elit."</p>
                                                                <span class="testi-number">01.</span>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <!--testi-item end-->
                                                    <!--testi-item-->
                                                    <div class="swiper-slide">
                                                        <div class="testi-item fl-wrap">
                                                            <div class="testi-avatar"><img src="images/avatar/1.jpg" alt=""></div>
                                                            <div class="testimonilas-text fl-wrap">
                                                                <h3>Frank Dellov</h3>
                                                                <p>"Vestibulum orci felis, ullamcorper non condimentum non, ultrices ac nunc. Mauris non ligula suscipit, vulputate mi accumsan, dapibus felis. Nullam sed sapien dui. Nulla auctor sit amet sem non porta. "</p>
                                                                <span class="testi-number">02.</span>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <!--testi-item end-->
                                                    <!--testi-item-->
                                                    <div class="swiper-slide">
                                                        <div class="testi-item fl-wrap">
                                                            <div class="testi-avatar"><img src="images/avatar/1.jpg" alt=""></div>
                                                            <div class="testimonilas-text fl-wrap">
                                                                <h3>Centa Simpson</h3>
                                                                <p>"Vestibulum orci felis, ullamcorper non condimentum non, ultrices ac nunc. Mauris non ligula suscipit, vulputate mi accumsan, dapibus felis. Nullam sed sapien dui. Nulla auctor sit amet sem non porta. "</p>
                                                                <span class="testi-number">03.</span>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <!--testi-item end-->
                                                    <!--testi-item-->
                                                    <div class="swiper-slide">
                                                        <div class="testi-item fl-wrap">
                                                            <div class="testi-avatar"><img src="images/avatar/1.jpg" alt=""></div>
                                                            <div class="testimonilas-text fl-wrap">
                                                                <h3>Nicolo Svensky</h3>
                                                                <p>"Vestibulum orci felis, ullamcorper non condimentum non, ultrices ac nunc. Mauris non ligula suscipit, vulputate mi accumsan, dapibus felis. Nullam sed sapien dui. Nulla auctor sit amet sem non porta. "</p>
                                                                <span class="testi-number">04.</span>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <!--testi-item end-->
                                                </div>
                                            </div>
                                        </div>
                                        <div class="tc-pagination"></div>
                                    </div>
                                    <!-- client-list -->
                                    <div class="fl-wrap client-list">
                                        <ul class="">
                                            <li><a href="#" target="_blank"><img src="images/clients/1.png" alt=""></a></li>
                                            <li><a href="#" target="_blank"><img src="images/clients/1.png" alt=""></a></li>
                                            <li><a href="#" target="_blank"><img src="images/clients/1.png" alt=""></a></li>
                                            <li><a href="#" target="_blank"><img src="images/clients/1.png" alt=""></a></li>
                                        </ul>
                                        <!-- client-list end-->
                                    </div>
                                </div>
                                <div class="section-number"> <span>0</span>5. </div>
                            </section>
                            <!--section end-->                 
                        </div>
                        <!--column-wrap-container end -->          
                    </div>
                    <!--column-wrap end-->    
                    <div class="to-top-btn to-top"><i class="fal fa-long-arrow-up"></i></div>
                </div>
                <!-- content end--> 
                <div class="hero-scroll-down-notifer">
                    <div class="scroll-down-wrap ">
                        <div class="mousey">
                            <div class="scroller"></div>
                        </div>
                    </div>
                    <i class="far fa-angle-down"></i>
                </div>
                <!-- share-wrapper-->
                <div class="share-wrapper">
                    <div class="close-share-btn"><i class="fal fa-long-arrow-left"></i></div>
                    <div class="share-container fl-wrap  isShare"></div>
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
import { Component, Vue } from 'vue-property-decorator';


@Component({
  components: {

  },
})
export default class Home extends Vue {}
</script>

