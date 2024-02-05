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
          zoom: 2,
          center: mapCenter,
          mapTypeId: google.maps.MapTypeId.SATELLITE
        });

        var markers = [
          {position: {lat: 40.12199438142346, lng: -105.13073897309246}, title: 'Sturchio et al., 2022', description: 'Jacks Solar Garden, Longmont, CO; Sturchio et al., 2022'},
          {position: {lat: 43.072581, lng: -89.400705}, title: 'UW-Madison Engineering Hall', description: 'UW-Madison Engineering Hall'},
          {position: {lat: 30.7062755556439, lng:  103.86265378041618}, title: 'Fan et al., 2018', description: 'Teaching and Experimental Farm of Sichuan Agricultural University; Fan et al., 2018'}
        ];

        markers.forEach(function(markerData) {
          var marker = new google.maps.Marker({
            position: markerData.position,
            map: map,
            title: markerData.title,
            icon: {
               url: "http://maps.google.com/mapfiles/ms/icons/blue-dot.png",
               scaledSize: new google.maps.Size(30, 30) 
             }
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
     - 1
     - Row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3

Studies by climate
----------------------
.. list-table:: 
   :widths: 25 25 50
   :header-rows: 1

   * - Climate
     - Study
     - Approx. coord.
   * - Subtropical, humid
     - Fan et al., 2018
     - 30.7058, 103.8624
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3

Studies by plant
----------------------
.. list-table:: 
   :widths: 25 25
   :header-rows: 1

   * - Plant
     - Study
   * - Bromus inermis
     - Sturchio et al., 2022
   * - Tragopogon dubius
     - Sturchio et al., 2022
   * - Medicago sativa (alfalfa)
     - Sturchio et al., 2022
   * - Dactylis glomerata
     - Sturchio et al., 2022
   * - Maize
     - Fan et al., 2018
   * - Soybean
     - Fan et al., 2018

Studies by PV axis
----------------------
.. list-table:: 
   :widths: 25 25
   :header-rows: 1

   * - Axis
     - Study
   * - Single-axis tracking
     - Sturchio et al., 2022
   * - 1
     - 1
   * - 2
     - 2
   * - 3
     - 3

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
