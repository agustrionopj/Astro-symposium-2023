---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Registration"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2023-03-10T16:11:49+07:00
lastmod: 2023-03-10T16:11:49+07:00
featured: false
draft: false
show_breadcrumb: true
share: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
<style>
  .card:hover {
    box-shadow: none;
  }
</style>

<body>
<div class="container" style="margin-bottom:3rem;">
  <div class="row d-flex justify-content-center">
    <div class="col-12 col-md-4 mt-3">
      <div class="card">
          <!-- <img src="img/in-person.svg" class="card-img-top" alt="..." style="width:50%; margin-top:1rem; margin-bottom:0; "> -->
          <div class="card-body">
            <h3 class="card-title text-center">Registration Fee</h3>
            <!-- <br> -->
            <h3 class="card-title text-primary text-center">USD 180</h3>
            <h5 class="text-center"><b>In-person participation</b></h5>
            <br>
            <p ><b>Expenses covered by registration fee:</b></p>
              <ul style="font-size:0.85rem;">
                <li>Coffee breaks (twice per day) and lunch (once per day)</li>
                <li>Conference dinners for participant (accompanying person pays separately)</li>
                <li>Transportation for tour to Bosscha Observatory</li>
                <li>Symposium Proceedings</li>
                <li>Symposium management</li>
              </ul>
          </div>
      </div>
    </div>
    <div class="col-12 col-md-4 mt-3">
      <div class="card">
          <!-- <img src="img/online.svg" class="card-img-top" alt="..." style="width:50%; margin-top:1rem; margin-bottom:0; "> -->
          <div class="card-body">
            <h3 class="card-title text-center">Registration Fee</h3>
            <!-- <br> -->
            <h3 class="card-title text-primary text-center">USD 100</h3>
            <h5 class="text-center"><b>Online participation</b></h5>
            <br>
            <p ><b>Expenses covered by registration fee:</b></p>
            <ul style="font-size:0.85rem;">
              <li>Symposium Proceedings</li>
              <li>Symposium management</li>
            </ul>
          </div>
      </div>
    </div>
  </div>
</div>

<div class="container">
    <div class="alert alert-info">
      <h4>Important dates:</h4>
      <ul>
        <li><b>26 Jun 2023</b>: open registration and abstract submission</li>
        <li><b>26 Aug 2023</b>: deadline for registration, abstract submission, and registration fee payment</li>
        <li><b>15 Sep 2023</b>: symposium programme finalised</li>  
      </ul>
      <p>Even though the deadline is 26 August 2023, we would really appreciate early registration and abstract submission for detail program and venue preparation.</p>
    </div>
</div>
<br>
<div class="container">
  <iframe src="https://script.google.com/macros/s/AKfycbz4P8Itknx7AsJK3SM6ClwDJgwBlWm47OMv63iXXPkeFjoa9U2ZBqqA4hhr3WXRYw8M/exec" frameborder="0" width="100%" id="iframe_1" scrolling="no"></iframe>
</div>

<!-- <div class="container">
  <div class="alert alert-info">
    If you already made a payment, please upload the payment proof using the form below.
  </div>

  <iframe src="https://script.google.com/macros/s/AKfycbw1YTxWIfq9f17EicPTnNHZ5dKOoDQKvfOmJR5w8HYlC3h0X3RHbsMY0Em_WPoHJ0Ad/exec" frameborder="0" width="100%" height=480px id="iframe_2" ></iframe>
</div> -->

<!-- hanya untuk deploy di subdomain Bosscha -->
<!-- ---------------------------------------- -->
<script src="/symposium-2023/js/iframeResizer.js"></script>

<!-- hanya untuk deploy lokal/netlify -->
<!-- <script src="/js/iframeResizer.js"></script> -->
<script>
  window.addEventListener(
  'message',
  (event) => {
    if (event.data === 'gasFrame') {
      window.gasFrame = event.source;
      iFrameResize({
        log: false,
        checkOrigin: false
      }, '#iframe_1');
    }
  },
  false
);

</script>
</body>