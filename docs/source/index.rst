UW-Madison Agrivoltaics Wiki 
===================================

Agrivoltaics (AV), or agrophotovoltaics (APV), is an innovative method that integrates solar photovoltaic (PV) systems with agriculture, optimizing land use by generating renewable energy and enabling crop production beneath or around the solar panels. Agrivoltaic systems offer versatile benefits: 

1. **Dual Land Use:** They enable simultaneous crop production and solar energy generation on the same land.
2. **Microclimate Regulation:** Solar panels create beneficial microclimates, reducing water evaporation, protecting crops from heat, and potentially enhancing yield and quality.
3. **Water Conservation:** These systems optimize water use by minimizing evaporation, crucial in arid or water-scarce regions.
4. **Renewable Energy Generation:** The solar panels produce clean energy, reducing greenhouse gas emissions and fossil fuel dependence.
5. **Economic Benefits:** Farmers can generate additional income from solar energy while maintaining agricultural productivity.
6. **Biodiversity Support:** Agrivoltaics contribute to biodiversity by creating habitats in agricultural areas.
7. **Research and Innovation:** This field is actively exploring the best crop types, solar panel arrangements, and practices for maximizing agricultural and energy outputs.

.. note::

   The Loheide Hydroecology Lab at the University of Wisconsin-Madison is actively developing and managing this project. For content and details, contact doe.han@wisc.edu.

Latest updates
------------
(Feb. 2nd, 2024) 


Current repository
----------------
A total of 30 articles are summarized. To search for keywords, please type in the textbox on the upper left corner.

Studies by locality
----------------------
.. raw:: html

    <div id="map" style="height:400px;width:100%;"></div>
    <script>
      function initMap() {
        var mapCenter = {lat: 43.07158173090839, lng: -89.409704861399};  // Map center coordinates
        var map = new google.maps.Map(document.getElementById('map'), {
          zoom: 3,
          center: mapCenter,
          mapTypeId: google.maps.MapTypeId.SATELLITE
        });

        var markers = [
          {position: {lat: 43.071581, lng: -89.409705}, title: 'Location 1', description: 'Description for Location 1'},
          {position: {lat: 43.072581, lng: -89.400705}, title: 'Location 2', description: 'Description for Location 2'},
          // Add more marker data here
        ];

        markers.forEach(function(markerData) {
          var marker = new google.maps.Marker({
            position: markerData.position,
            map: map,
            title: markerData.title
          });

          var infowindow = new google.maps.InfoWindow({
            content: markerData.description
          });

          marker.addListener('click', function() {
            infowindow.open(map, marker);
          });
        });
      }
    </script>
    <script async defer src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAsqb9KMZx9asqzLwumBpBPBgBDe0HqncY&callback=initMap"></script>


Studies by soil type
----------------------
.. list-table:: 
   :widths: 25 25 50
   :header-rows: 1

   * - Study
     - Soil type
     - Measurement depth
   * - Row 1, column 1
     -
     - Row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3

Studies by climate
----------------------
.. list-table:: 
   :widths: 25 25 50
   :header-rows: 1

   * - Study
     - Climate
     - Approx. coord.
   * - Row 1, column 1
     -
     - Row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3
Contents
--------

.. toctree::

   main
   ag
   et
   general
   gw_rech
   hazard
   plan
   climate
