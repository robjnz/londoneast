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
      <b-carousel-slide caption="Eastbury Manor House"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1516812522/Eastbury_xxxgfz.jpg">
                        <b-button href="http://bit.ly/2OBHS0Q" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>

      <!-- Slides with custom text -->

      <!-- Text slides with image -->
      <b-carousel-slide caption="Mayesbrook Park"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1516810937/Mayesbrook_l8iqr1.jpg">
                        <b-button href="http://bit.ly/2QqTW20" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>
      <!-- Slides with custom text -->

      <!-- Text slides with image -->
      <b-carousel-slide caption="St. Margaret of Antioch"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1516812153/St-Margaret_o8s4gb.jpg">
                        <b-button href="http://bit.ly/2Pe9Tst" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>
      <!-- Slides with custom text -->

        <!-- Text slides with image -->
      <b-carousel-slide caption="Valence House Museum"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1516808274/Valence_kgjaez.jpg">
                        <b-button href="http://bit.ly/2RtEkMK" target="_blank" variant="info">open</b-button>
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
