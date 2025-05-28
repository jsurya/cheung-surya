---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: landingpage
title: Alex & Jess
subtitle: 09.13.25 @ sea
header_type: splash
header_img: "/assets/img/celebrityedge-shipL.jpg"
project_links:
    - url: https://www.celebritycruises.com/ca/itinerary-details/7-night-alaska-dawes-glacier-from-seattle-washington
      label: Onboard the Celebrity Edge
---

<div style="text-align: center;" markdown="1">
<h1 style="color: #e8e8e8;"> Voyage With Us <small class="text-muted">on the Alaskan Seas</small></h1>

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

<h2 style="color:  #e8e8e8;"><a name="details"> Details </a></h2>

  <div class="row">
    <div class="col-sm-12 text-center">
        <h3 style="color:  #e8e8e8;" class="background-highlight">{{site.name}}</h3>
        <h2 style="color:  #e8e8e8;" class="background-highlight">09.13.25</h2>
          <a href="{{site.externalLink}}"><img src="/assets/img/celebrityedge-inv.png"/></a>
      </div>
    </div> <!-- /row -->
    
  <div class="row">
    <div style="color:  #e8e8e8;" class="col-sm-8 col-sm-offset-2 text-center"><div id="defaultCountdown"></div></div>
  </div> <!-- /row -->

  <div class="row">
    <div style="color:  #e8e8e8;" class="col-sm-12 text-center">
      <h3 style="color:  #e8e8e8;" class="background-highlight">{{ site.utc | date: "%A %B %-d, %Y" }}</h3>
    </div>
  </div>  
  </div>

<div style="text-align: center;" markdown="1">
<h3 style="color:  #e8e8e8;">Itinerary </h3>

<strong>Wedding Date</strong>: September 13, 2025 @ 1:00 PM PDT

<strong>Cruise Departure</strong>: September 12, 2025

<strong>Port of Departure</strong>: Seattle, Washington

<strong>Port of Return</strong>: Vancouver, British Columbia

<strong>Destination</strong>: Alaska

![Ports of Call](/assets/img/SEA_KTN_JNU_SGY_ENC_YVR_1200x430.gif){: style="display:block; margin-left:auto; margin-right:auto;" width="100%" }

<a href="https://www.celebritycruises.com/ca/itinerary-details/7-night-alaska-dawes-glacier-from-seattle-washington" target="_blank" class="btn chulapa-btn-project" role="button"><button type="button" class="btn btn-light"> Full Itinerary</button></a>

<script>
  var countDownDate = new Date(" {{site.utc}} ").getTime();
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