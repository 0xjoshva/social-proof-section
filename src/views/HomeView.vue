<template>
 <main>
  <div class="top">
  <div class="header">
  <h1>10,000+ of our users love our products.</h1>
  <p>We only provide great products combined with excellent customer service. See what our satisfied customers are saying about our services.</p>
  </div>
  <div class="ratings">
    <div class="bar">
      <div class="stars">
      <img src="../assets/icon-star.svg" alt="">
      <img src="../assets/icon-star.svg" alt="">
    <img src="../assets/icon-star.svg" alt="">
  <img src="../assets/icon-star.svg" alt="">
<img src="../assets/icon-star.svg" alt="">
      </div>
      <p>Rated 5 Stars in Reviews</p>
    </div>
    <div class="bar">
      <div class="stars">
      <img src="../assets/icon-star.svg" alt="">
      <img src="../assets/icon-star.svg" alt="">
    <img src="../assets/icon-star.svg" alt="">
  <img src="../assets/icon-star.svg" alt="">
<img src="../assets/icon-star.svg" alt="">
      </div>
      <p>Rated 5 Stars in Report Guru</p>
    </div>
    <div class="bar">
      <div class="stars">
      <img src="../assets/icon-star.svg" alt="">
      <img src="../assets/icon-star.svg" alt="">
    <img src="../assets/icon-star.svg" alt="">
  <img src="../assets/icon-star.svg" alt="">
<img src="../assets/icon-star.svg" alt="">
      </div>
      <p>Rated 5 Stars in BestTech</p>
    </div>
  </div>
</div>
<div class="bottom">
    <div class="card">
    <div class="info">
      <img src="../assets/image-colton.jpg" alt="">
      <div class="nametitle">
        <p id="name">Colton Smith</p>
        <p id="title">Verified Buyer</p>
      </div>
    </div>
    <p class="para">"We needed the same printed design as the one we had ordered the week prior. Not only did the find the original order, but we also received it in time. Excellent!"</p>
  </div>
    <div class="card">
    <div class="info">
      <img src="../assets/image-colton.jpg" alt="">
      <div class="nametitle">
        <p id="name">Colton Smith</p>
        <p id="title">Verified Buyer</p>
      </div>
    </div>
    <p class="para">"We needed the same printed design as the one we had ordered the week prior. Not only did the find the original order, but we also received it in time. Excellent!"</p>
  </div>
    <div class="card">
    <div class="info">
      <img src="../assets/image-colton.jpg" alt="">
      <div class="nametitle">
        <p id="name">Colton Smith</p>
        <p id="title">Verified Buyer</p>
      </div>
    </div>
    <p class="para">"We needed the same printed design as the one we had ordered the week prior. Not only did the find the original order, but we also received it in time. Excellent!"</p>
  </div>
  
</div>
 </main>
</template>

<script>
export default {
  
}
</script>
<style>
:root{
  /* primary */
  --VeryDarkMagenta: hsl(300, 43%, 22%);
  --SoftPink: hsl(333, 80%, 67%);

  /* neutral */
  --DarkGrayishMagenta: hsl(303, 10%, 53%);
  --LightGrayishMagenta: hsl(300, 24%, 96%);
  --White: hsl(0, 0%, 100%);
}
main{
  height: 100vh;
  width: 100%;
  background: var(--white);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.top{
  display: flex;
  width: 60%;
  justify-content: space-between;
}
.header{
  width: 40%;
  display: flex;
  flex-direction: column;
  row-gap: 2rem;
}
.header h1{
  color: var(--VeryDarkMagenta);
  font-size: 4rem;
  line-height: 3.2rem;
}
.header p{
font-weight: 500;
font-size: 1.2rem;
line-height: 1.5rem;
color: var(--DarkGrayishMagenta);
}

.ratings{
  display: flex;
  flex-direction: column;
  row-gap: 1rem;
}
.bar{
  display: flex;
  align-items: center;
  padding: 1.2rem;
  width: fit-content;
  height: fit-content;
  background: var(--LightGrayishMagenta);
  column-gap: 2.5rem;
  width: 30rem;
  border-radius: 6px;
  padding-left: 2rem;
  padding-block: 1.5rem;
}
.bar p{
  line-height: 0rem;
  font-size: 1.1rem;
  font-weight: 700;
  color: var(--VeryDarkMagenta);
}
.stars{
  display: flex;
  column-gap: .5rem;
}
.bar:nth-child(1){
  transform: translateX(-50px);
}
.bar:nth-child(3){
  transform: translateX(50px);
}
.bottom{
  width: 60%;
  display: flex;
  padding-top: 5rem;
  column-gap: 2.5rem;
  justify-content: space-between;
}
.card{
  background: var(--VeryDarkMagenta);
  border-radius: 12px;
  display: flex;
  flex-direction: column;
  row-gap: 2rem;
  width:25rem;
  height: fit-content;
  padding: 2rem;
}
.card:nth-child(1){
  transform: translateY(-15px);
}
.card:nth-child(3){
  transform: translateY(15px);
}
.card .para{
  width: 100%;
  color: var(--White);
  font-weight: 500;
  font-size:
  1.1rem;
  display: flex;
  justify-self: center;
  text-align: left;
}
.info{
  display:flex;
  column-gap: 1.5rem;
  width: fit-content;
  height: fit-content;
}
.info img{
  border-radius: 50%;
  height: 50px;
  width:auto;
}
#name{
  color: var(--White);
  font-size: 1.2rem;
  font-weight: 600;
}
#title{
font-size: 1.2rem;
font-weight: 500;
color: var(--SoftPink);
}
</style>
