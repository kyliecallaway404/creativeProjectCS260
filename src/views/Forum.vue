<template>
<div class="title-container">
  <div class="title">
    <h1>Forum</h1>
    <h2>Which game is your favorite?<h2>
  </div>
<div class="Reviews-Container">
    <div class="forum-item">
      <h2 id="person">Moira Rose</h2>
      <p id="reviews">"This place is almost charming. Very rustic cottage... I was half expecting early Unabomber."</p>
    </div>
    <div class="forum-item">
      <h2 id="person">Johnny Rose</h2>
      <p id="reviews">"Let me explain something about business. It's a dance. And sometimes you lead. And sometimes you follow."</p>
    </div>
    <div class="forum-item">
      <h2 id="person">David Rose</h2>
      <p id="reviews">"I would hardly call myself and expert on this subject, and by subject, I mean genuine human emotion, so I am just going to tell you what I know."</p>
    </div>
    <div class="forum-item">
      <h2 id="person">Alexis Rose</h2>
      <p id="reviews">"Every now and again, spending like a little bit of meny on something really special... it might not buy happiness, but it can definitely help make you smile."</p>
    </div>
    <div class="forum-item">
      <h2 id="person">Stevie Bud</h2>
      <p id="reviews">"Best Wishes and Warmest Regards!"</p>
    </div>
</div>
</template>

<style>
/*Reviews Page*/

.forum-item {
  background-color: #D3FAD7;
  display:flex;
  flex-direction: column;
  flex-wrap: wrap;
  margin-bottom: 20px;
  padding: 20px 20px 20px 20px;

}
.forum-Container{
  margin-top: 50px;
  margin-bottom: 50px;
}

#reviews {
  font-style: italic;
  color: #22577A;


  /*Title*/

  .title {
    display: flex;
    text-align: center;
    margin-top: 50px;
    margin-bottom: 50px;
    flex-direction: column;
  }
  .title-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

</style>
