<style>
@media (max-width: 600px) {
  .member-block {
    flex-direction: column !important;
    align-items: center !important;
    text-align: center;
  }
  .member-block img {
    margin-bottom: 10px;
  }
}

/* Default (light mode) text color */
body, .member-block, .member-block p, .member-block ul, .member-block li, #TableOfContents a {
  color: #000;
}

/* Dark mode override */
.dark body, .dark .member-block, .dark .member-block p, .dark .member-block ul, .dark .member-block li, .dark #TableOfContents a {
  color: #fff;
}

body {
    background-image: url('/img/test11.svg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    background-repeat: no-repeat;
    position: relative;
}

body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.1); /* Dark overlay - adjust opacity */
    z-index: -1;
}

</style>

<h1 style="margin-bottom: 1rem;">Members</h1>
<hr style="margin-top: 1rem; margin-bottom: 3.5rem;">

## Rishi Gupta

<div class="member-block" style="display: flex; align-items: flex-start; gap: 20px; flex-wrap: wrap; margin-bottom: 40px;">

  <img src="rishi.png"
       alt="Snoopy"
       style="width: 150px; height: 160px; object-fit: cover; border-radius: 25%; object-position: center; flex-shrink: 0;">

  <div style="flex: 1; text-align: left;">
    <p style="margin: 0; padding-top: 0.5em;">
      Rishi is a rising senior from the Bay Area. 
    </p>
    <ul style="margin: 0; padding-left: 20px;">
      <li>Plays three instruments: piano, guitar, and flute</li>
      <li>Loves to play chess and runs a chess club</li>
      <li>Eagle Scout</li>
    </ul>
  </div>

</div>

---

## Elaine Wang

<div class="member-block" style="display: flex; align-items: flex-start; gap: 20px; flex-wrap: wrap; margin-bottom: 40px;">

  <img src="elaine.png"
       alt="Woodstock"
       style="width: 150px; height: 160px; object-fit: cover; border-radius: 25%; object-position: center; flex-shrink: 0;">

  <div style="flex: 1; text-align: left;">
    <p style="margin: 0; padding-top: 0.5em;">
      Elaine is a rising junior from the Bay Area. She loves to dance, listen to music, and take photos in her free time.
    </p>
    <ul style="margin: 0; padding-left: 20px;">
      <li>Snoopy and fruit lover </li>
      <li>Matcha addict</li>
      <li>Teaches STEM to middle schoolers and volunteers at a food organization in outside of school</li>
    </ul>
  </div>

</div>

---

## Allen Jin

<div class="member-block" style="display: flex; align-items: flex-start; gap: 20px; flex-wrap: wrap; margin-bottom: 40px;">

  <img src="allen.png"
       alt="Allen"
       style="width: 150px; height: 160px; object-fit: cover; border-radius: 25%; object-position: center; flex-shrink: 0;">

  <div style="flex: 1; text-align: left;">
    <p style="margin: 0; padding-top: 0.5em;">
      Allen is a rising senior from SoCal
    </p>
    <ul style="margin: 0; padding-left: 20px;">
      <li>Loves listening to music</li>
      <li>Likes watching sports like football and basketball</li>
      <li>Enjoys going out with friends</li>
    </ul>
  </div>
  
</div>

---

## Saanvi Sheoran

<div class="member-block" style="display: flex; align-items: flex-start; gap: 20px; flex-wrap: wrap; margin-bottom: 40px;">

  <img src="saanvi.png"
       alt="Lucy Van Pelt"
       style="width: 150px; height: 160px; object-fit: cover; border-radius: 25%; object-position: center; flex-shrink: 0;">

  <div style="flex: 1; text-align: left;">
    <p style="margin: 0; padding-top: 0.5em;">
      Saanvi is a rising senior from San Diego.
    </p>
    <ul style="margin: 0; padding-left: 20px;">
      <li>Enjoys Painting, Drawing</li>
      <li>Interested in Real-World Applications of Data Science and ML</li>
      <li>Volunteers at STEM programs such as All Girls STEM Society and Girls Who Code</li>
    </ul>
  </div>
  
</div>
