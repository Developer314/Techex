---
id: 2c9c9f9d-d123-44b0-871e-0e1744f6c098
blueprint: page
title: 'Case Study'
author: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
template: case_study/index
header_style: header_2
inside_page: true
banner_image: home_hero/stock-photo-steam-locomotive-cabin-521332537.jpg
banner_text: TECHX
banner_title: 'About Us'
breadcrumb: |-
  <ol class="breadcrumb">
                            <li class="breadcrumb-item"><a href="/">Home</a></li>
                            <li class="breadcrumb-item active" aria-current="page">Case Study</li>
                          </ol>
meta_title: 'Your Page/Site Name'
meta_description: 'Your Page Meta Description'
meta_keywords: 'Tag 1, Tag 2'
og_title: 'OG Title'
og_description: 'OG Description'
page_header_extra: '<!--Extra Page Header Scripts-->'
page_footer_extra: '<!--Page Footer Extra-->'
updated_by: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
updated_at: 1681644125
block_types:
  -
    id: lgja61d4
    title_1: 'OUR RECENT PROJECT'
    title_2: 'Latest Case Studies'
    filters: |-
      <button data-filter="*" class="active">All</button>
                              <button data-filter=".business">Business</button>
                              <button data-filter=".consulting">Consulting</button>
                              <button data-filter=".product">Product</button>
                              <button data-filter=".engineering">Engineering</button>
    show_all: false
    edit_template: true
    template: |-
      <section class="case-study-wrapper section-padding">
              <div class="container">
                  <div class="row mb-50 align-items-center">
                      <div class="col-12 col-md-5">
                          <div class="section-title">
                              <p>{{title_1}}</p>
                              <h1>{{title_2}}</h1>
                          </div>
                      </div>
                      <div class="col-12 col-md-7 mt-4 mt-md-0 text-md-right">
                          <div class="case-cat-filter">
                              {{filters}}                    </div>
                      </div>
                  </div>
                  
                  <div class="row grid" style="position: relative; height: 944px;">
                      
                      
                      
                      {{collection:case_study limit=show_all?100:6}}
                     
                      <div class="col-xl-4 col-md-6 grid-item {{ foreach:category }} {{value:key}} {{ /foreach:category }} " style="position: absolute; left: 0%; top: 0px;">
                          <div class="single-case-study">
                              <div class="features-thumb bg-cover" style="background-image: url('{{main_image}}')"></div>
                              <div class="content">
                                  <h3>{{title}}</h3>
                                  <p>{{client}}</p>
                                  <a href="{{url}}">Read more <i class="fas fa-arrow-right"></i></a>
                              </div>
                          </div>
                      </div>
                      {{/collection:case_study}}
                      
                  </div>
              </div>
          </section>
    type: case_studies
    enabled: true
---
