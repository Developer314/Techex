---
id: home
blueprint: pages
title: 'Home 1'
template: home
author: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
header_style: header_1
block_types:
  -
    id: lfwjpwhn
    home_hero_style: hero_1
    hero_1:
      -
        id: lfwjpz4x
        title_1: 'Solutions For'
        title_2: 'IT Business'
        title_3: 'We Have 25 Years Of Experience In IT Solutions'
        button_1_text: 'Service we provide'
        button_1_link: 'http://www.revolve314.com'
        button_1_target: _blank
        image_1: home_hero/stock-photo-the-robot-polishes-a-metal-product-automatic-ultraprecise-grinding-of-a-metal-product-by-a-robot-1653625783.jpg
        type: new_set
        enabled: true
        button_2_text: 'Learn More'
        button_2_target: _self
        image_2: home_hero/stock-photo-steam-locomotive-cabin-521332537.jpg
      -
        id: lfwk1ibo
        title_1: 'Solutions For'
        title_2: 'IT Business'
        title_3: 'We Have 25 Years Of Experience In IT Solutions'
        button_1_text: 'Service we provide'
        button_1_link: 'http://www.revolve314.com'
        button_1_target: _self
        image_1: home_hero/stock-photo-simple-detail-of-a-handlebar-belonging-to-an-old-motorcycle-in-a-state-of-corrosion-1144557941.jpg
        type: new_set
        enabled: true
        button_2_text: 'Google me'
        button_2_link: 'http://www.google.com'
        button_2_target: _blank
        image_2: home_hero/stock-photo-detailed-lever-on-old-lathe-645704086.jpg
    type: home_hero
    enabled: true
    edit_template: false
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
                      <div class="slide-top-img d-none d-lg-block bg-overlay bg-cover" style="background-image: url('{{image_1}}')"></div>
                      <div class="slide-bottom-img d-none d-xl-block bg-overlay bg-cover" style="background-image: url('{{image_2}}')"></div>
                  </div>
                  {{/hero_1}}
                    
              </div>
          </section>
  -
    id: lfxkiml5
    image: home_hero/stock-photo-detailed-lever-on-old-lathe-645704086.jpg
    title_1: 'HOW CAN HELP YOU'
    title_2: 'We Help Your IT Business'
    features:
      -
        id: lfxkiv8z
        icon: flaticon-speech-bubble
        text_1: 'IT Consultancy'
        text_2: 'Faster & Smarter Solutions'
      -
        id: lfxkiyo5
        icon: flaticon-unlock
        text_1: 'Cyber Security'
        text_2: 'Faster & Smarter Solutions'
      -
        id: lfxkjblg
        icon: flaticon-mobile-app
        text_1: Development
        text_2: 'Faster & Smarter Solutions'
      -
        id: lfxkjnze
        icon: flaticon-joystick
        text_1: 'UX/UI Strategy'
        text_2: 'Faster & Smarter Solutions'
    type: features_1
    enabled: true
    template: |-
      <section class="features-wrapper features-1 section-padding pb-0">
              <div class="container">
                  <div class="row">
                      <div class="col-12 col-lg-12">
                          <div class="section-title text-center">
                              <p>{{title_1}}</p>
                              <h1>{{title_2}}</h1>
                          </div>
                      </div>
                  </div>

                  <div class="row mt-3 mt-lg-5">
                      <div class="col-xl-4 d-none d-xl-block">
                          <div class="features-banner mt-30 bg-cover" style="background-image: url('{{image}}')">
                          </div>
                      </div>
                      <div class="col-xl-8 col-12">
                          <div class="row">
                              
                              
                              {{features}}
                              <div class="col-md-6 col-12">
                                  <div class="single-features-item">
                                      <div class="icon">
                                          <i class="{{icon}}"></i>
                                      </div>
                                      <div class="content">
                                          <h3>{{text_1}}</h3>
                                          <p>{{text_2}}</p>
                                      </div>
                                  </div>
                              </div>
                              {{/features}}
                              
                              
                              
                              
                              
                              <div class="col-12">
                                  <div class="feature-cta bg-cover bg-center text-white" style="background-image: url('{{description_background}}')">
                                      <p>{{description}}</p>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </section>
    description: 'Sed perspiciatis unde omnis iste natus error voluptatem accusantium doloremque laudantium totam rem aperiam eaque quae'
    description_background: block_types/wave.png
    edit_template: true
  -
    id: lgeunf6l
    title_1: 'ABOUT COMPANY'
    title_2: 'Get’s IT Solutions For'
    title_3: 'Expert Consultants'
    description: 'Sed ut perspiciatis unde omnis natus error sit voluptatem accusa ntium doloremque laudantium totam rem aperiamea queipsa quae abillo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.'
    box_title: 'Professinoal Consultants'
    box_description: 'Quis autem vel eum iure reprehenderit quin voluptate velit esse quam'
    image: home_hero/stock-photo-detailed-lever-on-old-lathe-645704086.jpg
    edit_template: true
    template: |-
      <section class="about-us-wrapper section-padding">
              <div class="container">
                 <div class="row">
                      <div class="col-lg-6 col-12 pr-lg-5 order-2 order-lg-1 mt-5 mt-lg-0">
                          <div class="section-title mb-30">
                              <p>{{title_1}}</p>
                              <h1>{{title_2}} <br>
                                  {{title_3}}</h1>
                          </div>

                          <p class="pr-5">{{description}}</p>
                          
                          <div class="about-icon-box">
                              <div class="icon">
                                  <i class="fal fa-users"></i>
                              </div>
                              <div class="content">
                                  <h3>{{box_title}}</h3>
                                  <p>{{box_description}}</p>
                              </div>
                          </div>
                      </div>

                      <div class="col-lg-6 pl-lg-5 col-12 order-1 order-lg-2">
                          <span class="dot-circle"></span>
                          <div class="about-us-img" style="background-image: url('{{image}}')">
                          </div>
                          <span class="triangle-bottom-right"></span>
                      </div>
                  </div>
                  
                  {{if other_services}}

                  <div class="row mpt-50 pt-100">
      	            {{other_services}}
                      <div class="col-lg-4 col-md-6 col-12">
                          <div class="single-features-item">
                              <div class="icon">
                                  <i class="{{icon}}"></i>
                              </div>
                              <div class="content">
                                  <h3>{{title_1}}</h3>
                                  <p>{{title_2}}</p>
                              </div>
                          </div>
                      </div>
                     {{/other_services}}
                  </div>
                  
                  {{/if}}
                  
              </div>
          </section>
    type: about_company
    enabled: true
    other_services:
      -
        id: QgpeaahP
        icon: flaticon-speech-bubble
        title_1: 'IT Consultancy'
        title_2: 'Faster & Smarter Solutions'
      -
        id: bH8QCO4h
        icon: flaticon-unlock
        title_1: 'Cyber Security'
        title_2: 'Faster & Smarter Solutions'
      -
        id: 8dRG7VXc
        icon: flaticon-unlock
        title_1: Development
        title_2: 'Faster & Smarter Solutions'
  -
    id: lgev8q2l
    title_1: 'POPULAR IT SERVICES'
    title_2: 'Our Professional Solutions'
    title_3: 'For IT Business'
    services:
      -
        id: bjFd8ZHM
        icon: sicon1.png
        title_1: 'Manage IT Services'
        description: 'Sed perspicias unde omnis natus error volute'
        link_text: 'Learn More'
      -
        id: fQaxKyCd
        icon: sicon2.png
        title_1: 'Manage IT Services'
        description: 'Sed perspicias unde omnis natus error volute'
        link_text: 'Learn More'
      -
        id: jdBvPd3Q
        icon: sicon3.png
        title_1: 'Manage IT Services'
        description: 'Sed perspicias unde omnis natus error volute'
        link_text: 'Learn More'
      -
        id: knlXO9ey
        icon: sicon4.png
        title_1: 'Manage IT Services'
        description: 'Sed perspicias unde omnis natus error volute'
        link_text: 'Learn More'
    edit_template: true
    template: |-
      <section class="services-wrapper service-1 section-padding section-bg">
              <div class="container">
                  <div class="row mb-4 mb-lg-5">
                      <div class="col-12 col-lg-12">
                          <div class="section-title text-white text-center">
                              <p>{{title_1}}</p>
                              <h1>{{title_2}}<br>{{title_3}}</h1>
                          </div>
                      </div>
                  </div>

                  <div class="row">
      	            {{services}}
                      <div class="col-md-6 col-xl-3 col-12">
                          <div class="single-service-item">
                              <div class="icon">
                                  <img src="{{icon}}" alt="service">
                              </div>
                              <h4>{{title_1}}</h4>
                              <p>{{descriptoin}}</p>
                              <a href="{{link}}">{{link_text}} <i class="fas fa-arrow-right"></i></a>
                          </div>
                      </div>
                      {{/services}}
                  </div>
              </div>
          </section>
    type: popular_it_services
    enabled: true
  -
    id: lgezyvf7
    our_numbers:
      -
        id: 1k5iBIHD
        icon: fa-gem
        title: 'Project Completed'
        number: '368'
      -
        id: uv9hEQ4S
        icon: fa-drafting-compass
        title: 'Expert Consultants'
        number: '475'
      -
        id: sdwPzBJv
        icon: fa-stars
        title: 'Awards Winning'
        number: '125'
      -
        id: EXXErFUm
        icon: fa-trophy-alt
        title: '5 Stars Rating'
        number: '345'
    background: block_types/funfact-line.png
    edit_template: true
    template: |-
      <section class="funfact-wrapper text-white">
              <div class="container">
                  <div class="funfact-content-grid bg-cover" style="background-image: url('{{backround}}')">
      	            {{our_numbers}}
                      <div class="single-funfact-item">
                          <div class="icon">
                              <i class="fal {{icon}}"></i>
                          </div>
                          <h3>{{number}}</h3>
                          <p>{{title}}</p>
                      </div>
                      {{/our_numbers}}
                      
                  </div>
              </div>
          </section>
    type: our_numbers
    enabled: true
  -
    id: lgfch5a4
    background: block_types/cta_bg1.png
    title: 'Ready To Get Free Consulations For <br> Any Kind Of It Solutions ?'
    button_1_text: 'Get a Quote'
    button_1_link: 'entry::7f64f263-2af4-4bbe-ab76-51f22b909ee5'
    button_1_target: _self
    button_2_text: 'Learn More'
    button_2_link: 'entry::492bd938-8b67-4aaa-8963-6591bcd6f58f'
    button_2_target: _self
    edit_template: true
    template: |-
      <section class="cta-banner">
              <div class="container-fluid bg-cover section-bg" style="background-image: url('{{background}}')">
                  <div class="cta-content">
                      <div class="row align-items-center">
                          <div class="col-xl-7 text-white col-12 text-center text-xl-left">
                              <h1>{{title}}</h1>
                          </div>
                          <div class="col-xl-5 col-12 text-center text-xl-right">
                              <a href="{{button_1_link}}" target="{{button_1_target}}" class="theme-btn mt-4 mt-xl-0">{{button_1_text}} <i class="fas fa-arrow-right"></i></a>
                              <a href="{{button_2_link}}" target="{{button_2_target}}" class="ml-sm-3 mt-4 mt-xl-0 theme-btn minimal-btn">{{button_2_text}}<i class="fas fa-arrow-right"></i></a>
                          </div>
                      </div>
                  </div>
              </div>
          </section>
    type: get_ready_callouts
    enabled: true
  -
    id: lgfctw6j
    template: |-
      <div class="client-brand-logo-wrap">
              <div class="container">
                  <div class="brand-carousel-active pt-60 pb-60 d-flex justify-content-between owl-carousel">

      	            {{companies_work_with:company_logos}}

                      <div class="single-client">
                          <img src="{{url}}" alt="{{alt}}">
                      </div>
                      {{/companies_work_with:company_logos}}
                  </div>
              </div>
          </div>
    type: companies_work_with
    enabled: true
updated_by: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
updated_at: 1681404698
meta_title: 'Your Page/Site Name'
meta_description: 'Your Page Meta Description'
meta_tags: 'Tag 1, Tag 2'
og_title: 'OG Title'
og_description: 'OG Description'
page_header_extra: '<!--Extra Page Header Scripts-->'
page_footer_extra: '<!--Page Footer Extra-->'
meta_keywords: 'Tag 1, Tag 2'
other_meta_tags:
  -
    id: lgfb3m7o
    meta_tag_name: name
    meta_tag_value: Author
    meta_tag_value_name: content
    meta_tag_value_name_value: 'John Doe'
---
## Welcome to your brand new Statamic site!

Not sure where to do next? Here are a few ideas, but feel free to explore in your own way, in your own time.

- [Jump into the Control Panel](/cp) and edit this page or begin setting up your own collections and blueprints.
- [Head to the docs](https://statamic.dev) and learn how Statamic works.
- [Watch some Statamic videos](https://youtube.com/statamic) on YouTube.
- [Join our Discord chat](https://statamic.com/discord) and meet thousands of other Statamic developers.
- [Start a discussion](https://github.com/statamic/cms/discussions) and get answers to your questions.
- [Star Statamic on Github](https://github.com/statamic/cms) if you enjoy using it!