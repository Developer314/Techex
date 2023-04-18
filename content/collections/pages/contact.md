---
id: 487039a4-2045-4e61-9922-0cae0bd72c77
blueprint: page
title: Contact
author: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
template: home
header_style: header_2
inside_page: true
banner_image: home_hero/stock-photo-detailed-lever-on-old-lathe-645704086.jpg
banner_text: TECHX
banner_title: 'Contact Us'
breadcrumb: |-
  <ol class="breadcrumb">
                            <li class="breadcrumb-item"><a href="/">Home</a></li>
                            <li class="breadcrumb-item active" aria-current="page">Contact</li>
                          </ol>
meta_title: 'Contact Us'
meta_description: 'Your Page Meta Description'
meta_keywords: 'Tag 1, Tag 2'
og_title: 'OG Title'
og_description: 'OG Description'
page_header_extra: '<!--Extra Page Header Scripts-->'
page_footer_extra: '<!--Page Footer Extra-->'
updated_by: fd7d2ad8-80ce-45aa-967e-ea1534917ae3
updated_at: 1681655788
block_types:
  -
    id: lgjhqvsg
    boxes:
      -
        id: lgjhqy6n
        icon: fa-envelope
        title_1: 'Email Address'
        title_2: 'Sent mail asap anytime'
        data: |-
          <p>info@revolve314.com</p>
                                          <p>manup.rav@gmail.com</p>
      -
        id: lgjhrfpy
        icon: fa-phone
        title_1: 'Phone Number'
        title_2: 'call us asap anytime'
        data: |-
          <p>+918907289865</p>
                                          <p>+918907289865</p>
      -
        id: lgjhstqz
        icon: fa-map-marker-alt
        title_1: 'Office Address'
        title_2: 'Sent mail asap anytime'
        data: |-
          <p>B2, Miranda City Tower</p>
                                          <p>New York, US</p>
    gmap_iframe: '<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d5457.875323165521!2d144.90402300269133!3d-37.792722838344716!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6ad646b5d2ba4df7%3A0x4045675218ccd90!2sMelbourne%20VIC%2C%20Australia!5e0!3m2!1sen!2sbd!4v1612018663424!5m2!1sen!2sbd" frameborder="0" style="border:0; width:100%" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>'
    edit_template: true
    type: contact_us
    enabled: true
    template: |-
      <section class="contact-page-wrap section-padding">
              <div class="container">
                  <div class="row">
                      {{boxes}}
                      <div class="col-lg-4 col-md-6 col-12">
                          <div class="single-contact-card card1">
                              <div class="top-part">
                                  <div class="icon">
                                      <i class="fal {{icon}}"></i>
                                  </div>
                                  <div class="title">
                                      <h4>{{title_1}}</h4>
                                      <span>{{title_2}}</span>
                                  </div>
                              </div>
                              <div class="bottom-part">                            
                                  <div class="info">
                                      {{data}}
                                  </div>
                                  <div class="icon">
                                      <i class="fal fa-arrow-right"></i>
                                  </div>
                              </div>
                          </div>
                      </div>
                      {{/boxes}}
                  </div>

                  <div class="row">
                      <div class="col-12 col-lg-12">
                          <div class="contact-map-wrap">
                              <div id="map">
                                  {{gmap_iframe}}
                              </div>
                          </div>
                      </div>
                  </div>

                  <div class="row section-padding pb-0">
                      <div class="col-12 text-center mb-20">
                          <div class="section-title">
                              <p>{{form_title_1}}</p>
                              <h1>{{form_title_2}}</h1>
                          </div>
                      </div>

                      <div class="col-12 col-lg-12">
                          <div class="contact-form">    
      	                    
      	                    
      	                  {{ form:contact_us }}
       
          
          {{ if success }}
              <div class="bg-green-300 text-white p-2">
                  {{ success }}
              </div>
          {{ else }}
             
              {{ if errors }}
                  <div class="bg-red-300 text-white p-2">
                      {{ errors }}
                          {{ value }}<br>
                      {{ /errors }}
                  </div>
              {{ /if }}
       
            
              {{ fields }}
                  <div class="p-2">
                      <label>{{ display }}</label>
                      <div class="p-1">{{ field }}</div>
                      {{ if error }}
                          <p class="text-gray-500">{{ error }}</p>
                      {{ /if }}
                  </div>
              {{ /fields }}
       
             
              <input type="hidden" class="hidden" name="{{ honeypot ?? 'honeypot' }}">
       
              
              <button type="submit" class="theme-btn">Submit</button>
          {{ /if }}
       
      {{ /form:contact_us }}
      	                    
      	                    
      	                                                                        
                             
                          </div>
                      </div>
                  </div>
              </div>
          </section>
    form_title_1: 'SEND US MESSAGE'
    form_title_2: "Don't Hesited To Contact Us <br> Say Hello or Message"
---
