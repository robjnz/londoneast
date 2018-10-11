<template>
<section main>
  <b-container>
    <h1 class="title-color">Greenwich</h1>
    <br>

    <Slider />
    <br>
  <b-card-group deck
                  class="mb-3">
        <b-card  bg-variant="dark" text-variant="white" title="Places To Eat">
        <a href="http://bit.ly/2QIMP5h" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1516869644/Spaghetti_cc00eb.jpg" fluid-grow alt="places to eat Bexley" /></a>
</b-card>

        <b-card  bg-variant="dark" text-variant="white" title="Greenwich">
<a href="http://bit.ly/2Oi2UlU" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1522854223/greenwich_aospwn.png" fluid-grow alt="Bexley council" /></a>
</b-card>

<b-card  bg-variant="dark" text-variant="white" title="Greenwich News">
<a href="http://bit.ly/2yx46XT" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1517984323/newspaper_a1ayyc.png" fluid-grow alt="Barking & Dagenham post" /></a>
</b-card>
</b-card-group>

    <b-card-group deck
                  class="mb-3">
        <b-card  bg-variant="dark" text-variant="white" title="Clive Efford MP <br>Eltham ">
        <p class="labour">Labour</p>
        <a href="http://bit.ly/2Egwh3o" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_200/v1522836710/Clive_Efford_ujkjzb.jpg" fluid-grow alt="Clive Efford MP Eltham "/></a>
</b-card>

<b-card  bg-variant="dark" text-variant="white" title="Teresa Pearce MP<br>Erith & Thamesmead">
<p       class="labour">Labour</p>
<a       href="http://bit.ly/2OhkwOE" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_fill,g_face,h_180,w_200/v1516967810/Teresa_Pearce_tsxxty.jpg" fluid-grow alt="Teresa Pearce MP Erith & Thamesmead" /></a>
</b-card>

<b-card  bg-variant="dark" text-variant="white" title="Matthew Pennycook MP <br>Greenwich & Woolwich">
<p       class="labour">Labour</p>
<a       href="http://bit.ly/2yu4aaJ" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_200/v1522837170/pennycook_njkaco.jpg" fluid-grow alt="Matthew Pennycook MP Greenwich & Woolwich" /></a>
</b-card>

  </b-card-group>

  <b-card-group deck
                  class="mb-3">
        <b-card  bg-variant="dark" text-variant="white" title="Len Duvall AM <br>Greenwich and Lewisham">
        <p class="labour">Labour</p>
        <a href="http://bit.ly/2OQulCG" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_200/v1522829824/duvall_buid2q.jpg" fluid-grow alt="Len Duvall AM Greenwich and Lewisham"/></a>
</b-card>

        <b-card  bg-variant="dark" text-variant="white" title="">
        <p class="labour"></p>
<a href="#" target="_blank"><b-img src="" fluid-grow alt="" /></a>
</b-card>

<b-card  bg-variant="dark" text-variant="white" title="">
<p class=""></p>
<a href="" target="_blank"><b-img src="" fluid-grow alt=""/></a>
</b-card>
  </b-card-group>

      <div>
  <b-card-group deck
    class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "">
  <b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.meteoblue.com/en/weather/widget/daily/greenwich_united-kingdom_2647937?geoloc=fixed&days=7&tempunit=CELSIUS&windunit=MILE_PER_HOUR&precipunit=MILLIMETER&coloured=coloured&pictoicon=0&pictoicon=1&maxtemperature=0&maxtemperature=1&mintemperature=0&mintemperature=1&windspeed=0&windspeed=1&windgust=0&windgust=1&winddirection=0&winddirection=1&uv=0&uv=1&humidity=0&humidity=1&precipitation=0&precipitation=1&precipitationprobability=0&precipitationprobability=1&spot=0&spot=1&pressure=0&pressure=1&layout=dark"  frameborder = "0" scrolling = "yes" allowtransparency = "true" sandbox = "allow-same-origin allow-scripts allow-popups allow-popups-to-escape-sandbox" style = "width: 378px;height: 460px"><div><!-- DO NOT REMOVE THIS LINK --><a href="https://www.meteoblue.com/en/weather/forecast/week/greenwich_united-kingdom_2647937?utm_source=weather_widget&utm_medium=linkus&utm_content=daily&utm_campaign=Weather%2BWidget" target="_blank">meteoblue</a></div>
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
import Slider from '@/pages/Greenwich/Slider'



export default {
  components: {
    Slider,
  }
}
</script>


