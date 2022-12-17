<script setup></script>
<template>
  <section
    data-aos="fade-right"
    data-aos-duration="1700"
    data-aos-easing="ease-out-back"
    class="info-section"
  >
    <p id="ghost-p2">ghost-p</p>
    <div class="info-flex">
      <img class="info-img" src="@/assets/img/ff.webp" alt="" />
      <div class="info-text-box">
        <h2>about the party</h2>
        <p>
          Festive Christmas bash invite: ugly sweater, holiday cheer, jolly
          games, treats. RSVP by Dec. 20. See you there!
        </p>
        <a href="#ghost-p3"> <button>Know More</button></a>
      </div>
    </div>
  </section>
</template>

<style scoped>
.info-section {
  margin-bottom: 20rem;
  position: relative;
}
#ghost-p2 {
  position: absolute;
  top: -18rem;
  opacity: 0;
}
.info-flex {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10rem;
  max-width: 80%;
  margin-inline: auto;
}
.info-img {
  width: 45rem;
}
.info-text-box {
  width: 40rem;
}
.info-text-box h2 {
  margin-bottom: 1.5rem;
}
.info-text-box p {
  font-size: 2rem;
}
.info-text-box button {
  margin-top: 2.5rem;
  background-color: #ddd;
  border: none;
  padding: 0.8rem 2rem;
  border-radius: 50rem;
  color: #d73e3e;
  font-weight: 800;
  font-size: 1.7rem;
  transition: 0.2s;
}
.info-text-box button:hover {
  transform: translateY(-5%);
}
</style>
