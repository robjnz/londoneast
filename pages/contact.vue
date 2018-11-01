<template>
<section main>
  <b-container>
    <h1 class="title-color">Contact me</h1>
  <div>

<b-card-group deck
      class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">

<form name="contact" method="POST" netlify>
  <p>
    <label>Your Name: <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
</b-card>


</b-card-group>



</div>

      </b-container>
    </section>
</template>






