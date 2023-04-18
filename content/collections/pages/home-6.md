---
id: d0c3eb1b-b684-46d7-b4f2-3ab06a97cac4
blueprint: page
title: 'Home 6'
author: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
template: home
header_style: header_6
updated_by: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
updated_at: 1680281938
block_types:
  -
    id: lfwsbhj6
    home_hero_style: hero_6
    edit_main_template: true
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
    hero_6:
      -
        id: lfwsbvj8
        title_1: TECHEX
        title_2: 'Provide Best It'
        title_3: 'Services For Your'
        title_4: Business
        button_text: 'Discover More'
        button_link: 'entry::7f64f263-2af4-4bbe-ab76-51f22b909ee5'
        button_target: _self
        image: home_hero/stock-photo-steam-locomotive-cabin-521332537.jpg
        dot_image: home_hero/dots_01.svg
        object_image: home_hero/object_01.svg
        banner_image: home_hero/banner_02.svg
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
---
