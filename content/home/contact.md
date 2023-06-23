---
title: 
subtitle:
weight: 90
active: true
# widget: hero
design:
  columns: '1'
  background:
    color: 'black'
    text_color_light: true 
---
<div class="container-md">
  <div class="row">
    <div class="col-md-6 .d-flex .align-items-center">
    <h3 style="margin-bottom:2rem;">Organized by:</h3>
      <div class="row">
        <div class="col-md-3 .d-flex .align-items-center cols">
          <img src="media/logo-itb-white.svg" class="img-fluid transparansi hero-gambar2">
        </div>
        <div class="col-md-3 .d-flex .align-items-center cols">
          <img src="media/100thOB-white.svg" class="img-fluid transparansi hero-gambar2">
        </div>
      </div>
    </div>
    <div class="col-md-6 .d-flex .align-items-center">
      <h3>Contact:</h3>
      <!-- <h4><i class="fa fa-envelope" aria-hidden="true"></i> Email</h4> -->
      <h4 style="margin-top:2rem;">SOC & LOC Co-Chairs</h4>
      <p>
        <ul style="font-size:0.85rem">
          <li>Premana W. Premadi</li>
          <ul style="list-style-type:none;padding-left:0;">
            <li>{{< icon name="envelope" pack="fa">}}: <a href="mailto:premana@office.itb.ac.id">premana@office.itb.ac.id</a></li>
            <li>{{< icon name="envelope" pack="fa">}}: <a href="mailto:n.premadi@yahoo.com">n.premadi@yahoo.com</a></li>
          </ul>
          <li style="margin-top:0.85rem;">Anton T. Jaelani</li>
          <ul style="list-style-type:none;padding-left:0;">
            <li>{{< icon name="envelope" pack="fa">}}: <a href="mailto:antontj@office.itb.ac.id">antontj@office.itb.ac.id</a></li>
            <li>{{< icon name="envelope" pack="fa">}}: <a href="mailto:jaelani.at@gmail.com">jaelani.at@gmail.com</a></li>
          </ul>
        </ul>
      </p>
      <!-- <h4 style="margin-top:2rem;"><i class="fa-solid fa-phone"></i> Phone</h4> -->
      <h4 style="margin-top:2rem;">{{< icon name="phone" pack="fas">}} Phone or Fax</h4>
      <p>
        <ul style="font-size:0.85rem">
          <li>+62 22 2786027</li>
          <li>+62 811 246601</li>
        </ul>
      </p>
      <!-- <h4 style="margin-top:2rem;"><i class="fa-solid fa-location-dot"></i> Postal Address</h4> -->
      <h4 style="margin-top:2rem;">{{< icon name="location-dot" pack="fas">}} Address</h4>
      <p style="font-size:0.85rem; margin-bottom:2rem;">Bosscha Observatory, Institut Teknologi Bandung<br>Lembang 40391, Indonesia</p>
    </div>
  </div>
</div>

<style>
 @media (max-width: 767px) {
      .hero-gambar2 {
        display: block;
        margin-left: auto;
        margin-right: auto;
        max-width: 50%;
        height: auto;
      }
    }
    
    .transparansi {
      opacity: 0.7;
    }
    
    .kontainer {
      display: flex;
      align-items: center;
    }
</style>