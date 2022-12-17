<script setup></script>
<template>
  <section
    data-aos="fade-left"
    data-aos-duration="1700"
    data-aos-easing="ease-out-back"
    class="info-section"
  >
    <p id="ghost-p4">ghost-p</p>
    <div class="info-flex">
      <div class="info-text-box">
        <h2>About The Elven Shenanigans</h2>
        <p>
          The Christmas elves were busy making toys in the workshop. They worked
          hard every day to make sure all the good boys and girls had presents
          under the tree on Christmas morning.
        </p>
        <a href="#"> <button>Know More</button></a>
      </div>
      <img class="info-img" src="@/assets/img/aa.webp" alt="" />
    </div>
  </section>
</template>

<style scoped>
.info-section {
  margin-bottom: 20rem;
}
#ghost-p4 {
  position: absolute;
  top: -15rem;
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
