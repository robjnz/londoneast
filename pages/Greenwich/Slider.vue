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
      <b-carousel-slide caption="Eltham Palace"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1522943038/Eltham_Palace_au062d.jpg">
                        <b-button href="http://bit.ly/2ytwxWx" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>

      <!-- Slides with custom text -->

      <!-- Text slides with image -->
      <b-carousel-slide caption="Ranger’s House"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1522943311/Ranger_s_House_yior1q.jpg">
                        <b-button href="http://bit.ly/2OgMGcC" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>
      <!-- Slides with custom text -->

      <!-- Text slides with image -->
      <b-carousel-slide caption="Severndroog Castle"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1522943702/Severndroog_Castle_fpdzow.jpg">
                        <b-button href="http://bit.ly/2RHEfF6" target="_blank" variant="info">open</b-button>
                        </b-carousel-slide>
      <!-- Slides with custom text -->

        <!-- Text slides with image -->
      <b-carousel-slide caption="Thames Barrier"
                        img-src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_480,w_1024/v1522942608/thames_hpxd4i.jpg">
                        <b-button href="http://bit.ly/2C8YJkN" target="_blank" variant="info">open</b-button>
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
