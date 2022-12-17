<script setup></script>
<template>
  <section class="main-section">
    <div
      class="left-branch-box"
      data-aos="fade-right"
      data-aos-duration="1800"
      data-aos-easing="ease-out-back"
      data-aos-delay="800"
    >
      <img src="../assets/img/branch.webp" class="left-branch branch" alt="" />
    </div>
    <div
      class="right-branch-box"
      data-aos="fade-left"
      data-aos-duration="1800"
      data-aos-easing="ease-out-back"
      data-aos-delay="400"
    >
      <img src="../assets/img/branch.webp" class="right-branch branch" alt="" />
    </div>

    <div class="main-flex">
      <div
        data-aos="zoom-out"
        data-aos-duration="1800"
        data-aos-easing="ease-out-back"
        class="main-hero-box"
      >
        <h1>Merry <span class="span-h1">Christmas!</span></h1>
        <p>
          Enjoy this winter with your friends and spend a warm night under the
          full moon, sipping hot cocoa and making memories that will last a
          <span class="span-p">lifetime.</span>
        </p>
        <div class="hero-button-box">
          <img class="hero-arrow-left" src="@/assets/img/arrow.webp" alt="" />

          <a href="#ghost-p"
            ><img
              class="hero-button"
              src="@/assets/img/hero-button.webp"
              alt=""
          /></a>
          <img class="hero-arrow-right" src="@/assets/img/arrow.webp" alt="" />
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.main-flex {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
.main-section {
  height: 100vh;
  margin-bottom: 10rem;
  position: relative;
}
.main-hero-box {
  height: 100%;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin-top: 7rem;
}
.main-hero-box h1 {
  font-family: "Great Vibes";
  font-size: 7rem;
  margin-bottom: 1rem;
  color: #eee;
}
.span-h1 {
  font-family: "Great Vibes";
  color: #d22828;
}
/* .span-p {
 color: #5eff00;
} */
.main-hero-box p {
  font-size: 2rem;
  line-height: 1.4;
  width: 50%;
  margin-bottom: 2rem;
}
.hero-button-box {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}
.hero-button {
  width: 12rem;
  opacity: 0.6;
  transition: opacity 0.2s, transform 0.2s;
  /* cursor: pointer; */
}
.hero-button:hover {
  opacity: 0.7;
  transform: scale(1.03);
}
.hero-arrow-left {
  width: 10rem;
}
.hero-arrow-right {
  width: 10rem;
  transform: rotate(180deg);
}
.branch {
  width: 45rem;
  position: absolute;
}
.left-branch {
  left: -7rem;
  transform: rotate(21deg) translateY(-50%);
  animation: left-breeze 3s alternate ease-in-out infinite;
}
.right-branch {
  right: -9rem;
  top: 55%;
  transform: rotate(-29deg) scaleX(-1) translateY(-50%);
  animation: right-breeze 3s alternate ease-in-out infinite;
}
@keyframes left-breeze {
  0% {
    transform: rotate(21deg) translateY(-50%);
  }
  100% {
    transform: rotate(19deg) translateY(-53%);
  }
}
@keyframes right-breeze {
  0% {
    transform: rotate(-29deg) scaleX(-1) translateY(-50%);
  }
  100% {
    transform: rotate(-27deg) scaleX(-1) translateY(-53%);
  }
}
.left-branch-box {
  height: 100vh;
  position: absolute;
  left: 0;
  top: 35%;
}
.right-branch-box {
  height: 100vh;
  position: absolute;
  right: 0;
}
@media (max-width: 1290px) {
  .branch {
    width: 40rem;
  }
}
</style>
