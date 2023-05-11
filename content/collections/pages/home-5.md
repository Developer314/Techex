---
id: 7f64f263-2af4-4bbe-ab76-51f22b909ee5
blueprint: page
title: 'Home 5'
author: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
template: home
header_style: header_5
updated_by: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
updated_at: 1683728779
block_types:
  -
    id: lfwr3flv
    home_hero_style: hero_5
    edit_main_template: true
    hero_5:
      -
        id: lfwr3kb7
        title_1: 'we are creative it service agency'
        title_2: 'Preparing For Your Success Best IT Solutions'
        title_3: 'Sed ut perspiciatis unde omnis natus error sit voluptatem accusa ntium doloremque laudantium totam rem aperiamea'
        button_1_text: 'Service We Provide'
        button_1_link: 'entry::5e19af90-1859-4290-9ee6-051cc0d65f39'
        button_1_target: _self
        button_2_text: 'Learn More'
        button_2_link: 'entry::492bd938-8b67-4aaa-8963-6591bcd6f58f'
        button_2_target: _self
        background_image: home_hero/stock-photo-steam-locomotive-cabin-521332537.jpg
        type: new_set
        enabled: true
      -
        id: lfwr3wpr
        title_1: 'we are creative it service agency'
        title_2: 'Preparing For Your Success Best IT Solutions'
        title_3: 'Sed ut perspiciatis unde omnis natus error sit voluptatem accusa ntium doloremque laudantium totam rem aperiamea'
        button_1_text: 'Service We Provide'
        button_1_link: 'entry::home'
        button_1_target: _self
        button_2_text: 'Learn More'
        button_2_link: 'entry::5e19af90-1859-4290-9ee6-051cc0d65f39'
        button_2_target: _self
        background_image: home_hero/stock-photo-detailed-lever-on-old-lathe-645704086.jpg
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
    type: home_hero
    enabled: true
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
inside_page: false
banner_text: TECHX
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
