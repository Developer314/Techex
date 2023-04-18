---
id: 492bd938-8b67-4aaa-8963-6591bcd6f58f
blueprint: page
title: 'Home 3'
author: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
template: home
header_style: header_3
block_types:
  -
    id: lfwp6vqp
    home_hero_style: hero_3
    edit_main_template: true
    hero_3:
      -
        id: lfwp75ra
        title_1: 'We Have 25 Years Of Experience In IT Solutions'
        title_2: 'Grow Tech'
        title_3: Solutions
        button_1_text: 'SERVICE WE PROVIDE'
        button_1_link: 'entry::7fd5929c-2deb-4a8d-b9f3-56d657b09482'
        button_1_target: _self
        button_2_text: 'Learn More'
        button_2_link: 'entry::home'
        button_2_target: _self
        youtube_link: 'https://www.youtube.com/watch?v=LN6zOrJJGKQ&t=7s'
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
  -
    id: lgj3rwsz
    image: home_hero/stock-photo-detailed-lever-on-old-lathe-645704086.jpg
    testimonials:
      -
        id: lgj3s4pn
        name: Manup
        designation: 'Programme Manager'
        testimonial: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus dolor at libero ultricies ullamcorper vel ut dui. Maecenas sollicitudin'
        author_image: authors/screen-shot-2023-04-15-at-9.47.06-pm.png
      -
        id: lgj3sdvn
        name: Ratheesh
        designation: 'Project Manager'
        testimonial: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus dolor at libero ultricies ullamcorper vel ut dui. Maecenas sollicitudin'
        author_image: authors/screen-shot-2023-04-15-at-9.48.09-pm.png
    edit_temlate: true
    template: |-
      <section class="testimonial-wrapper section-padding">
              <div class="testimonial-bg bg-cover" style="background-image: url('{{image}}')"></div>
              <div class="container">
                  <div class="row">
                      <div class="col-12 col-lg-8 offset-lg-4 col-xl-5 offset-xl-7">
                          <div class="testimonial-carousel-active owl-carousel owl-theme">
      	                    {{testimonials}}
                              <div class="single-testimonial">
                                  <div class="icon">
                                      <i class="flaticon-right-quote"></i>
                                  </div>
                                  <h2>{{testimonial}}</h2>
                                  <div class="client-info">
                                      <div class="client-img bg-cover" style="background-image: url('{{author_image}}')"></div>
                                      <div class="client-bio">
                                          <h3>{{author}}</h3>
                                          <p>{{designation}}</p>
                                      </div>
                                  </div>
                              </div>

                              {{/testimonials}}
                          </div>
                      </div>
                  </div>
              </div>
          </section>
    type: testimonial
    enabled: true
  -
    id: lgj8o3se
    title_1: 'EXCLUSIVE MEMBERS'
    title_2: 'Meet Our Experience Team Members'
    team_page_link: 'entry::9987ee4e-4226-442f-8811-c1d1ab320586'
    edit_template: true
    template: |-
      <section class="our-team-wrapper section-padding">
              <div class="container">
                  <div class="row align-items-center mb-40">
                      <div class="col-12 col-md-6">
                          <div class="section-title">
                              <p>{{title_1}}</p>
                              <h1>{{title_2}}</h1>
                          </div>
                      </div>
                      <div class="col-12 col-md-6 mt-4 mt-md-0 text-md-right">
                          <a href="{{team_page_link}}" class="theme-btn off-white">View all Member <i class="fas fa-arrow-right"></i></a>
                      </div>
                  </div>

                  <div class="team-members-list row">
                      {{collection:our_team limit="4"}}
                      <div class="col-12 col-md-6 col-xl-3">
                          <div class="single-team-member">
                              <div class="member-img bg-cover bg-center" style="background-image: url('{{image}}')">
                              </div>
                              <div class="member-bio">
                                  <h4>{{title}}</h4>
                                  <p>{{designation}}</p>
                              </div>
                              <div class="social-profile">
                                  {{social_media}}
                                          <a href="link" target="_blank"><i class="fab {{icon}}"></i></a>
                                          {{/social_media}}
                              </div>
                          </div>
                      </div>
                      {{/collection:our_team}}
                  </div>
              </div>
          </section>
    type: exclusive_members
    enabled: true
updated_by: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
updated_at: 1681640046
inside_page: false
banner_text: TECHX
banner_title: 'Our Awesome Team'
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
banner_image: home_hero/stock-photo-detailed-lever-on-old-lathe-645704086.jpg
---
