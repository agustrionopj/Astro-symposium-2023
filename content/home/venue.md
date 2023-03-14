---
title: 
subtitle:
widget: blank
headless: true
weight: 50
active: true
design:
  columns: '1'
css_style: 
---
<style>
  /********************************
* Buat tombol baru
********************************/
.tombol {
  background-color: #4CAF50;
  /* Green */
  border: none;
  color: white;
  /* padding: 16px 32px; */
  padding: 10px 40px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 0.9rem;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.tombol3 {
  background-color: white;
  color: #CA4B6F;
  border: 2px solid #CA4B6F;
  border-radius: 0.5rem;
}

.tombol3:hover {
  background-color: #CA4B6F;
  color: white;
}
</style>

<div class="container-md">
  <h1 style="text-align: center; margin-bottom: 3rem; margin-top: 3rem;">The Venue</h1>
  <div class="row align-items-center">
    <div class="col-md-4" style="margin-bottom:1rem;">
      <img class="rounded" src="media/crcs_f3.jpg" style="margin-bottom:1em;">
      <img class="rounded" src="media/crcs_f2.jpg">
    </div>
    <div class="col-md-8">
      <h3>Institut Teknologi Bandung, CRCS Building, 2nd and 3rd floor</h3>
      <p style="font-size:0.85rem">Aliquam cursus odio quis lorem efficitur, nec vehicula ipsum commodo. Integer finibus, diam non tempus ultricies, libero odio rhoncus ipsum, nec porta tortor ligula non leo. Nullam quis justo quis leo efficitur interdum non lacinia lorem. In fermentum nisi ut dictum ullamcorper. Fusce a lacus eu neque tempor consectetur. Maecenas nec mi dictum, sollicitudin ligula at, lacinia quam. Mauris dictum odio a lacus vehicula sodales id et odio. <br><br>
      Curabitur quis tellus nibh. Duis laoreet sapien lacinia faucibus vestibulum. Quisque volutpat enim porta, eleifend tellus et, congue massa. Curabitur pharetra lectus nec metus varius dignissim. Nunc posuere pharetra porta. Cras pharetra quam sed nisl fringilla egestas. Duis lobortis nec arcu vel vulputate. Vivamus dapibus, neque sit amet ultricies aliquet, purus sem egestas leo, vel mattis quam dui a velit. Cras varius elit tempus consequat placerat. Vestibulum sit amet rhoncus neque. Maecenas mattis mattis tellus, eget ultrices magna elementum nec.
      </p>
    </div>
  </div>
</div>
<div class="d-flex justify-content-center mt-5 mb-3">
      <p>
        <a href="venue/" class="tombol tombol3">{{< icon name="book-open" pack="fas">}} View more</a>
      </p>
<div>