<template>
<section main>
  <b-container>
    <h1 class="title-color">Lewisham</h1>
    <br>

    <Slider />
    <br>
  <b-card-group deck
                  class="mb-3">
        <b-card  bg-variant="dark" text-variant="white" title="Places To Eat">
        <a href="http://bit.ly/2OihgT7" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1516869644/Spaghetti_cc00eb.jpg" fluid-grow alt="places to eat Bexley" /></a>
</b-card>

        <b-card  bg-variant="dark" text-variant="white" title="Hackney">
<a href="http://bit.ly/2PrkoIP" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1518971695/hackneymap_nkdoyp.png" fluid-grow alt="Bexley council" /></a>
</b-card>

<b-card  bg-variant="dark" text-variant="white" title="Hackney Gazettes">
<a href="http://bit.ly/2NFZ1SE" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1517984323/newspaper_a1ayyc.png" fluid-grow alt="Barking & Dagenham post" /></a>
</b-card>
</b-card-group>

    <b-card-group deck
                  class="mb-3">
        <b-card  bg-variant="dark" text-variant="white" title="Diane Abbott MP <br>Hackney North <br>& Stoke Newington">
        <p class="labour">Labour</p>
        <a href="http://bit.ly/2OUUqAq" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_200/v1518970119/abbott_epnzxr.jpg" fluid-grow alt="Diane Abbott MP Hackney North & Stoke Newington"/></a>
</b-card>

<b-card  bg-variant="dark" text-variant="white" title="Meg Hillier MP<br> Hackney South <br>& Shoreditch">
<p       class="labour">Labour</p>
<a       href="http://bit.ly/2QKiEdR" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_200/v1518970496/Hillier_vd9kdp.jpg" fluid-grow alt="Meg Hillier MP Hackney South & Shoreditch"/></a>
</b-card>

<b-card  bg-variant="dark" text-variant="white" title="Jennette Arnold AM<br> North East <br>London">
<p       class="labour">Labour</p>
<a       href="http://bit.ly/2C9Odd5" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_200/v1518971008/arnold_wkw31e.jpg" fluid-grow alt="Jennette Arnold AM North East London"/></a>
</b-card>

  </b-card-group>

      <div>
  <b-card-group deck
    class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "">
  <b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.meteoblue.com/en/weather/widget/daily/hackney_united-kingdom_2647694?geoloc=fixed&days=7&tempunit=CELSIUS&windunit=MILE_PER_HOUR&precipunit=MILLIMETER&coloured=coloured&pictoicon=0&pictoicon=1&maxtemperature=0&maxtemperature=1&mintemperature=0&mintemperature=1&windspeed=0&windspeed=1&windgust=0&windgust=1&winddirection=0&winddirection=1&uv=0&uv=1&humidity=0&humidity=1&precipitation=0&precipitation=1&precipitationprobability=0&precipitationprobability=1&spot=0&spot=1&pressure=0&pressure=1&layout=dark"  frameborder = "0" scrolling = "NO" allowtransparency = "true" sandbox = "allow-same-origin allow-scripts allow-popups allow-popups-to-escape-sandbox" style = "width: 378px;height: 460px"><div><!-- DO NOT REMOVE THIS LINK --><a href="https://www.meteoblue.com/en/weather/forecast/week/hackney_united-kingdom_2647694?utm_source=weather_widget&utm_medium=linkus&utm_content=daily&utm_campaign=Weather%2BWidget" target="_blank">meteoblue</a></div>
          allowfullscreen
  ></b-embed>
  <b-button-group>
  <b-button href="http://bit.ly/2OCnpZM" target="_blank" variant="info">Check Air Pollution</b-button>
  </b-button-group>
  </b-card>
  </b-card-group>
</div>
      </b-container>
      </section>

</template>

<script>
import Slider from '@/pages/Lewisham/Slider'



export default {
  components: {
    Slider,
  }
}
</script>


