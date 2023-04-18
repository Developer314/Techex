---
id: 00016810-b928-4f9b-adfb-cda02fc60a41
blueprint: page
title: 'About Us'
author: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
template: home
header_style: header_2
inside_page: true
banner_text: TECHX
banner_title: 'About Us'
breadcrumb: |-
  <ol class="breadcrumb">
                            <li class="breadcrumb-item"><a href="/">Home</a></li>
                            <li class="breadcrumb-item active" aria-current="page">About Us</li>
                          </ol>
meta_title: 'About Us'
meta_description: 'Your Page Meta Description'
meta_keywords: 'Tag 1, Tag 2'
og_title: 'OG Title'
og_description: 'OG Description'
page_header_extra: '<!--Extra Page Header Scripts-->'
page_footer_extra: '<!--Page Footer Extra-->'
block_types:
  -
    id: lgjfewau
    title_1: 'ABOUT COMPANY'
    title_2: 'Get’s IT Solutions For'
    title_3: 'Expert Consultants'
    description: 'Sed ut perspiciatis unde omnis natus error sit voluptatem accusa ntium doloremque laudantium totam rem aperiamea queipsa quae abillo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.'
    box_title: 'Professinoal Consultants'
    box_description: 'Quis autem vel eum iure reprehenderit quin voluptate velit esse quam'
    image: home_hero/stock-photo-detailed-lever-on-old-lathe-645704086.jpg
    other_services:
      -
        id: jScQbYkK
        icon: flaticon-mobile-app
        title_1: 'IT Consultancy'
        title_2: 'Faster & Smarter Solutions'
      -
        id: 3HwZtX92
        icon: flaticon-mobile-app
        title_1: 'IT Consultancy'
        title_2: 'Faster & Smarter Solutions'
      -
        id: d3i4FYWZ
        icon: flaticon-mobile-app
        title_1: 'IT Consultancy'
        title_2: 'Faster & Smarter Solutions'
    edit_template: true
    type: about_company
    enabled: true
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
  -
    id: lgjg0wve
    image: home_hero/stock-photo-detailed-lever-on-old-lathe-645704086.jpg
    title_1: 'Why Choose Us'
    title_2: 'Innovating Solutions <br> Digital Mindset'
    accordian:
      -
        id: lgjg14ak
        title: 'Can I Get Internet In My Area?'
        description: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus dolor at libero ultricies ullamcorper vel ut dui. Maecenas sollicitudin'
      -
        id: lgjg16hm
        title: 'Can I Get Internet In My Area?'
        description: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus dolor at libero ultricies ullamcorper vel ut dui. Maecenas sollicitudin'
      -
        id: lgjg185b
        title: 'Can I Get Internet In My Area?'
        description: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus dolor at libero ultricies ullamcorper vel ut dui. Maecenas sollicitudin'
      -
        id: lgjg19o0
        title: 'Can I Get Internet In My Area?'
        description: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus dolor at libero ultricies ullamcorper vel ut dui. Maecenas sollicitudin'
      -
        id: lgjg1b2y
        title: 'Can I Get Internet In My Area?'
        description: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus dolor at libero ultricies ullamcorper vel ut dui. Maecenas sollicitudin'
    edit_template: true
    template: |-
      <section class="faq-section section-padding">
              <div class="faq-bg bg-cover d-none d-lg-block" style="background-image: url('{{image}}')"></div>
              <div class="container">
                  <div class="row">
                      <div class="col-xl-5 col-lg-6 offset-lg-6 offset-xl-7">
                          <div class="col-12 col-lg-12 mb-40">
                              <div class="section-title">
                                  <p>{{title_1}}</p>
                                  <h1>{{title_2}}</h1>
                              </div>
                          </div>

                          <div class="faq-content">
                              <div class="faq-accordion">
                                  <div id="accordion" class="accordion">
                                      
                                     
                                      {{accordian}}
                                      
                                      <div class="card">
                                          <div class="card-header">
                                              <p class="mb-0 text-capitalize">
                                                  <a class="collapsed" role="button" data-toggle="collapse" aria-expanded="false" href="#faq-{{id}}">
                                                      {{title}}
                                                  </a>
                                              </p>
                                          </div>
                                          <div id="faq-{{id}}" class="collapse" data-parent="#accordion" style="">
                                              <div class="card-body">
                                                 {{description}} 
                                              </div>
                                          </div>
                                      </div> <!-- /card -->
                                      {{/accordian}}
                                      
                                      
                                      
                                  </div>                        
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </section>
    type: why_choose_us
    enabled: true
  -
    id: lgjg20i0
    title_1: 'EXCLUSIVE MEMBERS'
    title_2: 'Meet Our Experience Team Members'
    team_page_link: 'entry::9987ee4e-4226-442f-8811-c1d1ab320586'
    edit_template: false
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
  -
    id: lgjg2wao
    background: block_types/cta_bg1.png
    our_numbers:
      -
        id: 2UXojw89
        icon: fa-gem
        title: 'Project Completed'
        number: '368'
      -
        id: q82VMh0y
        icon: fa-gem
        title: 'Project Completed'
        number: '368'
      -
        id: niHPwOr4
        icon: fa-gem
        title: 'Project Completed'
        number: '368'
      -
        id: T8MWUy9h
        icon: fa-gem
        title: 'Project Completed'
        number: '368'
    edit_template: false
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
    id: lgjg3mdr
    title_1: 'POPULAR IT SERVICES'
    title_2: 'Our Professional Solutions'
    title_3: 'For IT Business'
    services:
      -
        id: hTW9wByN
        icon: sicon1.png
        title_1: 'Manage IT Services'
        description: 'Sed perspicias unde omnis natus error volute'
        link_text: 'Learn More'
      -
        id: Z4j5wn7u
        icon: sicon2.png
        title_1: 'Manage IT Services'
        description: 'Sed perspicias unde omnis natus error volute'
        link_text: 'Learn More'
      -
        id: ZmpwZ39r
        icon: sicon3.png
        title_1: 'Manage IT Services'
        description: 'Sed perspicias unde omnis natus error volute'
        link_text: 'Learn More'
      -
        id: DsqOXSAL
        icon: sicon4.png
        title_1: 'Manage IT Services'
        description: 'Sed perspicias unde omnis natus error volute'
        link_text: 'Learn More'
    edit_template: false
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
    id: lgjg514o
    image: home_hero/stock-photo-steam-locomotive-cabin-521332537.jpg
    testimonials:
      -
        id: lgjg58ej
        name: Manup
        designation: 'Programme Manager'
        testimonial: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus dolor at libero ultricies ullamcorper vel ut dui. Maecenas sollicitudin'
        author_image: team_members/360_f_364211147_1qglvxv1tcq0ohz3fawufrtonzz8nq3e.jpg
      -
        id: lgjg5a45
        name: Manup
        designation: 'Programme Manager'
        testimonial: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus dolor at libero ultricies ullamcorper vel ut dui. Maecenas sollicitudin'
        author_image: team_members/photo-1438761681033-6461ffad8d80.jpg
      -
        id: lgjg5c7g
        name: Manup
        designation: 'Programme Manager'
        testimonial: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus dolor at libero ultricies ullamcorper vel ut dui. Maecenas sollicitudin'
        author_image: team_members/360_f_444539901_2gsnvmtx14lelj6edpudusarbcytoegj.jpg
    edit_temlate: false
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
    id: lgjg6q9d
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
  -
    id: lgjg73oi
    background: block_types/cta_bg1.png
    title: 'Ready To Get Free Consulations For <br> Any Kind Of It Solutions ?'
    button_1_text: 'Get a Quote'
    button_1_link: 'entry::home'
    button_1_target: _self
    button_2_text: 'Learn More'
    button_2_link: 'entry::f0cd94c0-6e49-4026-bd64-a2fb4605c2cc'
    button_2_target: _self
    edit_template: false
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
updated_by: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
updated_at: 1681652072
---
