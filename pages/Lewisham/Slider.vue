<template>
  <div>
  <b-carousel id="carousel1"
              style = "text-shadow: 1px 1px 2px #333;"
              controls
              indicators
                                background     = "#ababab"
                              :interval        = "4000"
                                img-width      = "1024"
                                img-height     = "480"
                                v-model        = "slide"
                                @sliding-start = "onSlideStart"
                                @sliding-end   = "onSlideEnd"
    >

      <!-- Text slides with image -->
      <b-carousel-slide caption="Geffrye Museum"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1519142135/geffrye_tkoekn.jpg">
                        <b-button href="http://bit.ly/2RHYC59" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>

      <!-- Slides with custom text -->

      <!-- Text slides with image -->
      <b-carousel-slide caption="Hackney City Farm"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1519143040/cityfarm_p7qcbs.jpg">
                        <b-button href="http://bit.ly/2RIuOFK" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>
      <!-- Slides with custom text -->

      <!-- Text slides with image -->
      <b-carousel-slide caption="Victoria Park"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1519143381/victoriapark_rz0are.jpg">
                        <b-button href="http://bit.ly/2NA06v5" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>
      <!-- Slides with custom text -->

        <!-- Text slides with image -->
      <b-carousel-slide caption="Viktor Wyne Museum"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1519142785/victor_x9wwlg.jpg">
                        <b-button href="http://bit.ly/2CHwY42" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>

      <!-- Slides with custom text -->


    </b-carousel>
    <h2>places to visit</h2>

  </div>
</template>

<script>
export default {
  data () {
    return {
      slide  : 0,
      sliding: null
    }
  },
  methods: {
    onSlideStart (slide) {
      this.sliding = true
    },
    onSlideEnd (slide) {
      this.sliding = false
    }
  }
}
</script>
<!-- carousel-1.vue -->
