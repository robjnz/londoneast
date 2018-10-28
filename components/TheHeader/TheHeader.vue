<template>
<section nav class="nav-bar">
  <b-navbar toggleable="md" type="dark" variant="info">


  <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
  <img src="/logo_transparent.png" height="50" width="50" class="d-inline-block align-top" alt="LondonEast logo">


  <b-navbar-brand href="/" class="title">London East</b-navbar-brand>

  <b-collapse is-nav id="nav_collapse">

    <b-navbar-nav class="nav">
      <b-nav-item href="/">Home</b-nav-item>
      <b-nav-item-dropdown text="Links" right>
        <b-dropdown-item href="/computers">Computer software</b-dropdown-item>
        <b-dropdown-item href="/education">Education</b-dropdown-item>
        <b-dropdown-item href="/housing">Housing</b-dropdown-item>
        <b-dropdown-item href="/goods">Second hand goods</b-dropdown-item>
        <b-dropdown-item href="/links">Other Links</b-dropdown-item>
      </b-nav-item-dropdown>

      <b-nav-item-dropdown text="Health" right>
        <b-dropdown-item href="/hospitals">Hospitals</b-dropdown-item>
        <b-dropdown-item href="/support">Support groups</b-dropdown-item>
        <b-dropdown-item href="/welfare">Welfare Rights</b-dropdown-item>
        <b-dropdown-item href="/esa">Claiming ESA</b-dropdown-item>
      </b-nav-item-dropdown>

      <b-nav-item-dropdown text="Travel" right>
        <b-dropdown-item href="/travel">Live Train Times</b-dropdown-item>
        <b-dropdown-item href="/twitter-tfl">Twitter tfl</b-dropdown-item>
        <b-dropdown-item href="/travel-links">Travel Links</b-dropdown-item>
      </b-nav-item-dropdown>

      <b-nav-item-dropdown text="East London Boroughs" right>
        <b-dropdown-item href="/Barking">Barking</b-dropdown-item>
        <b-dropdown-item href="/Bexley">Bexley</b-dropdown-item>
        <b-dropdown-item href="/Greenwich">Greenwich</b-dropdown-item>
        <b-dropdown-item href="/Hackney">Hackney</b-dropdown-item>
        <b-dropdown-item href="/Havering">Havering</b-dropdown-item>
        <b-dropdown-item href="/Lewisham">Lewisham</b-dropdown-item>
        <b-dropdown-item href="/Newham">Newham</b-dropdown-item>
        <b-dropdown-item href="/Redbridge">Redbridge</b-dropdown-item>
        <b-dropdown-item href="/Tower-Hamlets">Tower Hamlets</b-dropdown-item>
        <b-dropdown-item href="/Waltham-Forest">Waltham Forest</b-dropdown-item>
        </b-nav-item-dropdown>

      <b-nav-item href="/visit">Places To Visit</b-nav-item>

      <b-nav-item-dropdown text="Entertainment" right>
        <b-dropdown-item href="/cinemas">Cinemas</b-dropdown-item>
        <b-dropdown-item href="/TV">Television & Movies</b-dropdown-item>
        <b-dropdown-item href="/theatres">Theatres</b-dropdown-item>
        <b-dropdown-item href="/restaurants">Restaurants Guides</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item-dropdown text="Jobs" right>
        <b-dropdown-item href="/Barking">Barking</b-dropdown-item>
        <b-dropdown-item href="/Bexley">Bexley</b-dropdown-item>
        <b-dropdown-item href="/Greenwich">Greenwich</b-dropdown-item>
        <b-dropdown-item href="/Hackney">Hackney</b-dropdown-item>
        <b-dropdown-item href="/Havering">Havering</b-dropdown-item>
        <b-dropdown-item href="/Lewisham">Lewisham</b-dropdown-item>
        <b-dropdown-item href="/Newham">Newham</b-dropdown-item>
        <b-dropdown-item href="/Redbridge">Redbridge</b-dropdown-item>
        <b-dropdown-item href="/Tower-Hamlets">Tower Hamlets</b-dropdown-item>
        </b-nav-item-dropdown>
    </b-navbar-nav>

    <!-- Right aligned nav items -->
    <b-navbar-nav class="ml-auto">
    </b-navbar-nav>

  </b-collapse>
</b-navbar>
</section>

</template>

<style scoped>



.title{
  color    : gold;
  font-size: 2rem;

}

.nav{
  font-size: 21px;
}

.dropdown-item{
background: #343A40;
color     : whitesmoke;
}
</style>
