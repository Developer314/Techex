---
id: d0c3eb1b-b684-46d7-b4f2-3ab06a97cac4
blueprint: page
title: 'Home 6'
author: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
template: home
header_style: header_1
updated_by: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
updated_at: 1683730937
block_types:
  -
    id: lhhtv3jh
    home_hero_style: hero_1
    edit_main_template: false
    template: |-
      {{if home_hero_style == "hero_1"}}
      {{hero_1_template}}
      {{/if}}

      {{if home_hero_style == "hero_2"}}
      {{hero_2_template}}
      {{/if}}

      {{if home_hero_style == "hero_3"}}
      {{hero_3_template}}
      {{/if}}

      {{if home_hero_style == "hero_4"}}
      {{hero_4_template}}
      {{/if}}

      {{if home_hero_style == "hero_5"}}
      {{hero_5_template}}
      {{/if}}

      {{if home_hero_style == "hero_6"}}
      {{hero_6_template}}
      {{/if}}
    hero_1:
      -
        id: lhhtv6ym
        title_1: 'Solutions For'
        title_2: 'IT Business'
        title_3: 'We Have 25 Years Of Experience In IT Solutions'
        button_1_text: 'Service we provide'
        button_1_target: _self
        image_1: home_hero/stock-photo-detailed-lever-on-old-lathe-645704086.jpg
        image_2: home_hero/stock-photo-steam-locomotive-cabin-521332537.jpg
        button_2_text: 'Learn More'
        button_2_target: _self
        type: new_set
        enabled: true
      -
        id: lhhtvrmq
        title_1: 'Solutions For'
        title_2: 'IT Business'
        title_3: 'We Have 25 Years Of Experience In IT Solutions'
        button_1_text: 'Service we provide'
        button_1_target: _self
        image_1: home_hero/stock-photo-simple-detail-of-a-handlebar-belonging-to-an-old-motorcycle-in-a-state-of-corrosion-1144557941.jpg
        image_2: home_hero/stock-photo-steam-locomotive-cabin-521332537.jpg
        button_2_text: 'Learn More'
        button_2_target: _self
        type: new_set
        enabled: true
    edit_template: true
    hero_1_template: |-
      <section class="hero-slide-wrapper hero-1">
              <div class="hero-slider-active owl-carousel">
      	        
      	        
      	        {{hero_1}}
      	        
                  <div class="single-slide bg-cover">
                      <div class="container">
                          <div class="row">
                              <div class="col-12 col-xl-8 col-lg-10">
                                  <div class="hero-contents">
      	                            
      	                            <h2>{{title_1}}</h2>
      	                            
                                      
                                      <h1 class="fs-lg">{{title_2}}</h1>
                                      <p>{{title_3}}</p>
                                      <a href="{{button_1_link}}" title="{{button_1_text}}" target="{{button_1_target}}" class="theme-btn">{{button_1_text}} <i class="fas fa-arrow-right"></i></a>
                                      <a href="{{button_2_link}}" title="{{button_2_text}}" target="{{button_2_target}}" class="theme-btn minimal-btn">{{button_2_text}} <i class="fas fa-arrow-right"></i></a>
                                  </div>
                              </div>
                          </div>
                      </div>
                      <div class="slide-top-img d-none d-lg-block bg-overlay bg-cover" style="background-image: url('techex/assets/img/home1/hero1.jpg')"></div>
                      <div class="slide-bottom-img d-none d-xl-block bg-overlay bg-cover" style="background-image: url('techex/assets/img/home1/hero2.jpg')"></div>
                  </div>
                  {{/hero_1}}
                    
              </div>
          </section>
    hero_2_template: |-
      <section class="hero-slide-wrapper hero-2">
              <div class="hero-text">{{hero_title}}</div>
              <div class="hero-slider-2 owl-carousel">
      	        {{hero_2}}
                  <div class="single-slide bg-cover" style="background-image: url('{{image}}')">
                      <div class="container-fluid">
                          <div class="row">
                              <div class="col-12 col-lg-10 col-xl-8">
                                  <div class="hero-contents">
                                      <h1>{{title_1}} <br> {{title_2}}</h1>
                                      <p>{{title_3}}</p>
                                      <a href="{{button_link_1}}" target="{{button_target_1}}" class="theme-btn">{{button_2_text}} <i class="fas fa-arrow-right"></i></a>
                                      <a href="{{button_link_2}}" target="{{button_target_2}}" class="theme-btn minimal-btn">{{button_2_text}} <i class="fas fa-arrow-right"></i></a>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  {{/hero_2}}
              </div>
          </section>
    hero_3_template: |-
      {{hero_3}}
      <section class="hero-slide-wrapper hero-3">
              <div class="hero-slider-3">
                  <div class="single-slide bg-cover" style="background-image: url('{{background_image}}')">
                      <div class="container">
                          <div class="row align-items-center">
                              <div class="col-12 col-lg-8 mt-5 mt-lg-0 order-2 order-lg-1 text-center text-lg-left">
                                  <div class="hero-contents text-white">
                                      <p>{{title_1}}</p>
                                      <h1>{{title_2}} <br> {{title_3}}</h1>
                                      <a href="{{button_1_link}}" target="{{button_1_target}}" class="theme-btn">{{button_1_text}} <i class="fas fa-arrow-right"></i></a>
                                      <a href="{{button_2_link}}" target="{{button_2_target}}" class="theme-btn minimal-btn">{{button_2_text}} <i class="fas fa-arrow-right"></i></a>
                                  </div>
                              </div>
                              <div class="col-lg-4 col-12 order-1 order-lg-2 text-center text-lg-right">
                                  <div class="video-play-btn">
                                      <a href="{{youtube_link}}" class="play-video popup-video"><i class="fas fa-play"></i></a>                     
                                  </div> 
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </section>
      {{/hero_3}}
    hero_4_template: |-
      {{hero_4}}
      <section class="hero-slide-wrapper hero-4">
              <div class="hero-slider">
                  <div class="single-slide bg-cover">
                      <div class="container">
                          <div class="row align-items-center">
                              <div class="col-12 col-lg-6">
                                  <div class="hero-contents">
                                      <span>{{title_1}}</span>
                                      <h1>{{title_2}}</h1>
                                      <p>{{title_3}}</p>
                                      <a href="{{button_1_link}}" target="{{button_1_target}}" class="theme-btn">{{button_1_text}} <i class="fas fa-arrow-right"></i></a>
                                      <a href="{{button_2_link}}" target="{{button_2_target}}" class="theme-btn minimal-btn">{{button_2_text}} <i class="fas fa-arrow-right"></i></a>
                                  </div>
                              </div>
                              <div class="col-lg-6 mt-5 mt-lg-0 col-12 pl-lg-5">
                                  <div class="hero-banner">
                                      <div class="dot"></div>
                                      <img src="{{image}}" alt="{{title_1}}">
                                  </div>
                              </div>
                          </div>
                      </div>
                      <div class="small-elements"></div>
                  </div>
              </div>
          </section>
      {{/hero_4}}
    hero_5_template: |-
      <section class="hero-slide-wrapper techex-landing-page">
              <div class="hero-slider-active-2 owl-carousel owl-theme">
      	        
      	        
      	        {{hero_5}}
                  <div class="single-slide bg-cover" style="background-image: url('{{background_image}}')">
                      <div class="container">
                          <div class="row">
                              <div class="col-12">
                                  <div class="hero-contents text-center">
                                      <a class="theme-btn-sm" data-animation="fadeInUp" data-delay="0">{{title_1}}</a>
                                      <h1 data-animation="fadeInUp" data-delay="0.4s">{{title_2}}</h1>
                                      <div data-animation="fadeInUp" data-delay="0.6s">
                                          <p>{{title_3}}</p>
                                      </div>
                                      
                                      <div class="btn__wrapper d-flex flex-wrap justify-content-center" data-animation="fadeInUp" data-delay="0.8s">
                                          <a href="{{button_1_link}}" target="{{button_1_target}}" class="theme-btn">{{button_1_text}}<i class="icon-arrow-right-1"></i></a>
                                          <a href="{{button_2_link}}" target="{{button_2_target}}" class="theme-btn">{{button_2_text}} <i class="icon-arrow-right-1"></i></a>
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  {{/hero_5}}

                  
              </div>
          </section>
    hero_6_template: |-
      {{hero_6}}
      <section class="hero-wrapper section-padding-3">
              <div class="container">
                  <div class="row align-items-center">
                      <div class="col-md-12 col-lg-6">
                          <div class="banner-content">
                              <h2 data-aos="fade-up">{{title_2}} <br> {{title_3}} <br> {{title_3}}</h2>
                              <span>{{title_1}}</span>
                              <a data-aos="fade-up" data-aos-delay="100" href="{{button_link}}" target="{{button_target}}" class="theme-btn mt-40">{{button_text}} <i class="icon-arrow-right-1"></i></a>
                          </div>
                      </div>
                      <div class="col-md-12 col-lg-6">
                          <div class="banner-img">
                              <img src="{{image}}" alt="{{title_2}} {{title_3}}  {{title_3}}">
                          </div>
                      </div>
                  </div>
              </div>
              <div class="dots-element">
                  <img src="{{dot_image}}" alt>
              </div>
              <div class="banner-element ">
                  <img src="{{object_image}}" alt>
              </div>
              <div class="banner-element-2">
                  <img src="{{banner_image}}" alt>
              </div>
          </section>
      {{/hero_6}}
    type: home_hero
    enabled: true
inside_page: false
banner_text: '314'
banner_title: 'About Us'
breadcrumb: |-
  <ol class="breadcrumb">
                            <li class="breadcrumb-item"><a href="/">Home</a></li>
                            <li class="breadcrumb-item active" aria-current="page">team</li>
                          </ol>
meta_title: 'Your Page/Site Name'
meta_description: 'Your Page Meta Description'
meta_keywords: 'Tag 1, Tag 2'
og_title: 'OG Title'
og_description: 'OG Description'
page_header_extra: '<!--Extra Page Header Scripts-->'
page_footer_extra: '<!--Page Footer Extra-->'
---
