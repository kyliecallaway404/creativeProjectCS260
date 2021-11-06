<template>
<!--Intro Content-->
<div>
<div class="Intro-content-container">
  <div class="Intro-content">
    <h1>Battle of the Boardgames!</h1>

    <a href="/Forum.vue" style="color: #22577A" id="subtitle"><em>Which is your favorite?</em></a>
  </div>
</div>
<!--Photo Bar-->
<div class="photo-container-home">
  <div class="photo-home"><a class="anch-link" href="https://www.amazon.com/Asmodee-SEV07-7-Wonders-Duel/dp/B014DMSTXK"><img class="photosize" src="../../public/images/7Wondersduelimage.jpg" alt="Picture of 7 Wonders Duel Boardgame"></a></div>
  <div class="photo-home"><a class="anch-link" href="https://www.amazon.com/Rio-Grande-Games-Bohnanza-Duel/dp/B071RVLJNZ"><img class="photosize" src="../../public/images/Bohnanzaimage.jpg" alt="Picture of Bohnanza Boardgame"></a></div>
  <div class="photo-home"><a class="anch-link" href="https://www.amazon.com/Catan-Studios-cantan2017/dp/B00U26V4VQ"><img class="photosize" src="../../public/images/Settlerpicture.jpg" alt="Picture of Setters of Catan Boardgame"></a></div>
</div>
</div>
</template>

<script>

</script>

<style>
/*Home Page*/
.Intro-content-container{
  display:flex;
  margin: 25px 25px 25px 25px;
  justify-content: center;
}

.photo-container-home, .photo-container-portfolio, .pricing-container {
  display: flex;
  flex-direction: row;
  justify-content: center;
  flex-wrap: wrap;
}

.photo-home{
  margin: 1rem 1rem 1rem 1rem;
  justify-content: center;
  margin: 50px;
}

.photo{
  margin: 2rem;
  display: flex;
  justify-content: center;
  padding: 1rem;
}

</style>
