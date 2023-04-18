---
id: 5e19af90-1859-4290-9ee6-051cc0d65f39
blueprint: page
title: 'Home 4'
author: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
template: home
header_style: header_4
updated_by: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
updated_at: 1680278584
block_types:
  -
    id: lfwqb12x
    home_hero_style: hero_4
    edit_main_template: true
    hero_4:
      -
        id: lfwqb65p
        title_1: 'ABOUT COMPANY'
        title_2: 'Best IT Solutions For Business'
        title_3: 'Sed ut perspiciatis unde omnis natus error sit voluptatem accusa ntium doloremque laudantium totam rem aperiamea'
        button_1_text: 'Our Service'
        button_1_link: 'entry::492bd938-8b67-4aaa-8963-6591bcd6f58f'
        button_1_target: _self
        button_2_text: 'Learn More'
        button_2_link: 'entry::7fd5929c-2deb-4a8d-b9f3-56d657b09482'
        button_2_target: _self
        image: home_hero/stock-photo-simple-detail-of-a-handlebar-belonging-to-an-old-motorcycle-in-a-state-of-corrosion-1144557941.jpg
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
    type: home_hero
    enabled: true
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
---
