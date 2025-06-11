---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: landingpage
title: Alex & Jess
subtitle: 09.13.25 @ sea
header_type: splash
header_img: "/assets/img/gallery/KH_JessicaAlex-ENG-77.jpg"
---

<div style="text-align: center;" markdown="1">
<div id= "fancyH1" class="fancy-h1" style="color: #e8e8e8;">
  Voyage With Us<small id= "fancyH2" class="fancy-h2 text-muted"> on the Alaskan Seas</small> </div>
<h3 style="color:  #e8e8e8" class="col-sm-offset-2 col-sm-12 text-center">{{ site.utc | date: "%A %B %-d, %Y" }}</h3>
<div class="row">
  <div class="row">
  
  </div>  
</div>
  <div class="col-sm-12 text-center">
      <div class="dotgothic16-regular" style="color:  #e8e8e8;">
      <div id="defaultCountdown"></div>
    </div>
  </div> <!-- /row -->
    
  <div class="row">
    <div style="color:  #e8e8e8;" class="col-sm-8 col-sm-offset-2 text-center"></div>
  </div> <!-- /row -->


  </div>

<div style="text-align: center;" markdown="1">
<h2 style="color:  #e8e8e8;"><a name="our-story"> Our Story </a></h2>

<p>
Ten years. From long days and nights at the university compsci labs to epic snowboarding adventures to countless hours exploring virtual worlds to pursuing their big city dreams under the vibrant lights of the 6ix.
</p>

<p> 
Ten years of Alex and Jess building a life together, a life marked by consistent commitment and shared growth. They've weathered every challenge and reached every major milestone side-by-side, proving that their bond is truly unbreakable. Frankly, we're all wondering what took them so long! But now, finally, they're making it official. 
</p>

<p class="lead">
After a decade of love, laughter, and unwavering partnership, they're ready to say 'I do' and celebrate a marriage long overdue.
</p>

{% assign externalgallery = 
"
./assets/img/gallery/KH_JessicaAlex-ENG-78.jpg,
./assets/img/gallery/KH_JessicaAlex-ENG-3.jpg,
./assets/img/gallery/KH_JessicaAlex-ENG-55.jpg,
./assets/img/gallery/KH_JessicaAlex-ENG-104.jpg,
./assets/img/gallery/KH_JessicaAlex-ENG-85.jpg,
./assets/img/gallery/KH_JessicaAlex-ENG-63.jpg,
./assets/img/gallery/KH_JessicaAlex-ENG-6.jpg,
./assets/img/gallery/KH_JessicaAlex-ENG-129.jpg,
./assets/img/gallery/KH_JessicaAlex-ENG-137.jpg" 
%}

{% include snippets/carousel.html external=externalgallery interval=3000 random="true" controls="true" indicators="true" %}

<h2 style="color:  #e8e8e8;"><a name="details"> Details </a></h2>

![Invitation](/assets/img/celebrityedge-inv.png){: style="display:block; margin-left:auto; margin-right:auto;" width="100%" }

<h3 style="color:  #e8e8e8;">Itinerary</h3>

<strong>Cruise Departure</strong>: September 12, 2025

<strong>Port of Departure</strong>: <a href="https://g.co/kgs/WEs2DXW"> Smith Cove Pier 91, Seattle, WA, United States</a>

<strong>Port of Return</strong>: <a href="https://g.co/kgs/sAbEMMK"> Canada Place Cruise Ship Terminal in Vancouver, BC, Canada </a>

<strong class="lead">Destination: Alaska</strong>

![Ports of Call](/assets/img/SEA_KTN_JNU_SGY_ENC_YVR_1200x430.gif){: style="display:block; margin-left:auto; margin-right:auto;" width="100%" }

<a href="https://www.celebritycruises.com/itinerary-details/7-night-alaska-dawes-glacier-cruise-from-seattle-washington?groupId=EG07SEA-1304418576&packageID=EG07A376&sDT=2025-09-12&cCD=CO&country=USA" target="_blank" class="btn chulapa-btn-project" role="button"><button type="button" class="btn btn-light"> Full Itinerary</button></a>

<h3 style="color:  #e8e8e8;">Wedding Day Schedule</h3>
<em class="lead"> September 13, 2025 @ Blu on the Celebrity Edge </em>

<strong>12:30 PM</strong>: Guest Arrival

<strong>1:00 PM</strong>: Symbolic Ceremony

<strong>1:30 PM</strong>: Photos with the newlyweds
<small>cocktails & canapés to follow</small>

<strong>2:00-3:30 PM</strong>: Toasts & Speeches

<strong>3:00-3:30 PM</strong>: Tea Ceremony

<strong>3:30 PM</strong>: Farewells

<h3 style="color:  #e8e8e8;">Group Excursion to Mendenhall Glacier</h3>
<em class="lead"> September 15, 2025 in Juneau, Alaska </em>

<p> As a continuation of our celebration together, we would like to invite our cherished guests to join us on a private bus tour to Mendenhall Glacier on Day 4 of the cruise in Juneau. More details coming soon!</p> 

<script>
  var dateStr = "{{ site.utc | date: '%Y-%m-%dT%H:%M:%SZ' }}";
  var countDownDate = new Date(dateStr).getTime();
  if (isNaN(countDownDate)) {
    console.error("Invalid date:", dateStr);
  }
  var x = setInterval(function() {

    var now = new Date().getTime();
      
    var distance = countDownDate - now;
      
    var days = Math.floor(distance / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);
      
    document.getElementById("defaultCountdown").innerHTML = days + " days " + hours + " hours "
    + minutes + " minutes " + seconds + " seconds ";
      
    if (distance < 0) {
      clearInterval(x);
      document.getElementById("defaultCountdown").innerHTML = "EXPIRED";
    }
  }, 1000);

</script>