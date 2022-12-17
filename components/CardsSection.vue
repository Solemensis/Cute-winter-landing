<script setup></script>
<template>
  <section class="cards-section">
    <p id="ghost-p">ghost-p</p>
    <h2 id="protector">Pick Your <br />Protector</h2>
    <div class="cards-flex">
      <a href="#ghost-p2">
        <div
          data-aos="fade-down"
          data-aos-duration="2200"
          data-aos-easing="ease-out-back"
          class="card"
        >
          <img src="../assets/img/card1.webp" alt="" />
          <div class="text-box">
            <h3>Candy Bomb</h3>
            <p>
              The sweet aroma of the candy bomb filled the air, making
              everyone's mouth water.
            </p>
          </div>
        </div>
      </a>
      <a href="#ghost-p2">
        <div
          data-aos="fade-down"
          data-aos-duration="2200"
          data-aos-easing="ease-out-back"
          data-aos-delay="300"
          class="card"
        >
          <img src="../assets/img/card22.webp" alt="" />
          <div class="text-box">
            <h3>Santa's Lollipop</h3>
            <p>
              Santa's lollipop was a magical treat, granting wishes to all who
              licked it.
            </p>
          </div>
        </div>
      </a>
      <a href="#ghost-p2">
        <div
          data-aos="fade-down"
          data-aos-duration="2200"
          data-aos-easing="ease-out-back"
          data-aos-delay="600"
          class="card card-3-box"
        >
          <img class="card-3" src="../assets/img/card3.webp" alt="" />
          <div class="text-box">
            <h3>Giant Candy Rod</h3>
            <p>
              The giant candy cane rod was the ultimate weapon in Santa's
              workshop.
            </p>
          </div>
        </div>
      </a>
    </div>
  </section>
</template>

<style scoped>
.cards-section {
  margin-bottom: 20rem;
  position: relative;
}
#ghost-p {
  position: absolute;
  top: -15rem;
  opacity: 0;
}
h2 {
  text-align: center;
  margin-bottom: 11rem;
}
.cards-flex {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 7rem;
  max-width: 80%;
  margin-inline: auto;
}
.card {
  background-color: #3a3a3a7c;
  border-radius: 3rem;
  width: 24rem;
  height: 21rem;
  position: relative;
}
.card:hover img {
  transform: translate(-50%, -55%);
}
.card img {
  width: 17rem;
  align-self: center;
  transition: transform 0.3s;
  position: absolute;
  left: 50%;
  top: 0;
  transform: translate(-50%, -50%);
}
.card-3 {
  transform: translate(-50%, -50%) rotate(31deg) !important;
}
.card-3-box:hover .card-3 {
  transform: translate(-50%, -55%) rotate(31deg) !important;
}
.text-box {
  position: absolute;
  left: 50%;
  bottom: 10%;
  transform: translateX(-50%);
  width: 100%;
  padding: 0 1.2rem;
}
.card h3 {
  text-align: center;
  color: #d22828;
  margin-bottom: 0.5rem;
}
.card p {
  font-size: 1.5rem;
  text-align: center;
  line-height: 1.35;
}
</style>
