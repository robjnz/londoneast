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
      <b-carousel-slide caption="Bexley Park Wood"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1516983220/bexleywoods_gx6k1u.jpg">
                        <b-button href="http://bit.ly/2E7182l" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>

      <!-- Slides with custom text -->

      <!-- Text slides with image -->
      <b-carousel-slide caption="Hall Place & Gardens"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1516981696/hallplace_nyzmz9.jpg">
                        <b-button href="http://bit.ly/2QyDQ6A" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>
      <!-- Slides with custom text -->

      <!-- Text slides with image -->
      <b-carousel-slide caption="Danson House"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1516982336/damson_gmq5q2.jpg">
                        <b-button href="http://bit.ly/2E3h5pW" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>
      <!-- Slides with custom text -->

        <!-- Text slides with image -->
      <b-carousel-slide caption="Red House"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1516982711/redhouse_b8ufux.jpg">
                        <b-button href="http://bit.ly/2OK74SV" target="_blank" variant="info">open</b-button>
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
