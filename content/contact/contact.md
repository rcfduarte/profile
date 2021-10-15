+++
# Contact widget.
widget = "contact"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "Contact"
subtitle = "Get in touch"

# Automatically link email and phone?
autolink = true

# Email form provider
#   0: Disable email form
#   1: Netlify (requires that the site is hosted by Netlify)
#   2: formspree.io
email_form = 0
+++

<div id="map" style="width:400px;height:400px;background:yellow"></div>
<script>
function myMap() {
    var uluru = {lat: 51.81917297113252, lng: 5.861992029606369};
    var map = new google.maps.Map(document.getElementById('map'), {
      zoom: 12,
      center: uluru
    });
    var marker = new google.maps.Marker({
      position: uluru,
      map: map
    });
}
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAinQj4O_t_RrQRF2xDNBj2Png0jERffIU&callback=myMap"></script>

