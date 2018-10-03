<template>
<section main>
  <b-container>
    <h1 class="title-color">Live Train Information</h1>
  <div>
  <Barking />
  <Bexley />
  <Greenwich />
  <Hackney />
  <Havering />
  <Lewisham />
  <Newham />
  <Redbridge />
  <TowerHamlets />

    </div>
      </b-container>
    </section>
</template>


<script>
import Barking from '@/components/LiveTrain/Barking'
import Bexley from '@/components/LiveTrain/Bexley'
import Greenwich from '@/components/LiveTrain/Greenwich'
import Hackney from '@/components/LiveTrain/Hackney'
import Havering from '@/components/LiveTrain/Havering'
import Lewisham from '@/components/LiveTrain/Lewisham'
import Newham from '@/components/LiveTrain/Newham'
import Redbridge from '@/components/LiveTrain/Redbridge'
import TowerHamlets from '@/components/LiveTrain/TowerHamlets'



export default {
  components: {
    Barking,
    Bexley,
    Greenwich,
    Hackney,
    Havering,
    Lewisham,
    Newham,
    Redbridge,
    TowerHamlets,
  }
}
</script>







