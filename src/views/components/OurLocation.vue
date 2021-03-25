<template>
  <div class="container">
    <div class="card">
      <h5 class="card-header">
        Nasza lokalizacja
      </h5>
      <div class="card-body">

        <vl-map :load-tiles-while-animating="true" :load-tiles-while-interacting="true"
                data-projection="EPSG:4326" style="height: 400px">
          <vl-view :zoom.sync="zoom" :center.sync="center" :rotation.sync="rotation"></vl-view>

          <vl-overlay id="overlay" :position="overlayCoordinate" :offset="overlayOffset">
            <template>
              
              <div class="card shadow">
                  <div class="card-body">
                    Duolegal <br/>
                    ul. Twarda 18 <br/>
                    00-105 Warszawa (City Office)
                  </div>
              </div>
            </template>
          </vl-overlay>
          
          <vl-feature>
            <vl-geom-point :coordinates="[20.999360, 52.234430]"></vl-geom-point>
          </vl-feature>

          <vl-layer-vector>
            <vl-feature>
              <vl-geom-point
                :coordinates="[20.999360, 52.234430]"
              ></vl-geom-point>

              <vl-style-box>
                <vl-style-circle :radius="10">
                  <vl-style-fill color="red"></vl-style-fill>
                  <vl-style-stroke color="black"></vl-style-stroke>
                </vl-style-circle>
              </vl-style-box>
            </vl-feature>
          </vl-layer-vector>
          <vl-layer-tile id="osm">
            <vl-source-osm></vl-source-osm>
          </vl-layer-tile>
      </vl-map>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return { 
        zoom: 16,
        center: [20.999360, 52.234430],
        rotation: 0,
        max_zoom: 23,
        min_zoom: 8,
        geolocPosition: undefined,
        overlayCoordinate: [20.999360, 52.234430],
        overlayOffset: [10, 10]
      }
    },
  }
</script>
<style>
.overlay-content{
  background-color: white;
}
</style>