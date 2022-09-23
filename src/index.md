---
layout: default
page_class: home
title: "Home"
---

<div class="app-hero">
  <div class="container">
    <small class="app-hero__subheading">Bangkok, Thailand</small>
    <div class="app-hero__heading display-1">9-10 December, 2022</div>
    <div class="app-hero__heading display-4">Tickets now on sale</div>
    <a href="https://www.eventpop.me/e/13417/rubyconfth-2022" target="_blank" class="btn btn--outline-light">
      Buy Tickets {% render "icon", icon: "icon-arrow-right-circle" %}
    </a>
  </div>
</div>

<div class="app-content__text">
  <div class="container">
    <section class="cfp">
      <h3>Want to submit a proposal?</h3>
      <p>The call for papers is still open</p>
      <a class="btn btn--primary" href="https://www.papercall.io/rubyconfth2022" target="_blank">View CFP</a>
    </section>
    <section class="sponsors">
      <h3>The event is made possible thanks to the support of our oustanding sponsors</h3>

      {% render "list_sponsor", sponsors: site.data.sponsors %}

      <h4>Interested in sponsoring the conference?</h4>
      <p>Promote your company to the world's top Ruby devs</p>
      <a class="btn btn--primary" href="https://drive.google.com/file/d/1Rgt9qWPaaMf6juoEHyLF_mnltm915IBh/view?usp=sharing" target="_blank">View sponsorship deck</a>
    </section>
  </div>
</div>



