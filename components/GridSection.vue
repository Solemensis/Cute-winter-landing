<template>
  <section class="buyings-section">
    <p id="ghost-p3">ghost-p</p>
    <h2>Select Your <br />Artifact</h2>
    <div class="buyings-grid">
      <a href="#ghost-p4">
        <div
          data-aos="fade-down"
          data-aos-duration="2200"
          data-aos-easing="ease-out-back"
          class="card"
        >
          <img class="product" src="../assets/img/yen/1.webp" alt="" />
          <div class="text-box">
            <h3>Frosty Flier</h3>
            <div class="price-flex">
              <p class="price">$12.99</p>
              <button>
                <img class="icon" src="@/assets/img/yen/heart.webp" alt="" />
              </button>
            </div>
          </div>
        </div>
      </a>
      <a href="#ghost-p4">
        <div
          data-aos="fade-down"
          data-aos-duration="2200"
          data-aos-easing="ease-out-back"
          data-aos-delay="300"
          class="card"
        >
          <img class="product" src="../assets/img/yen/2.webp" alt="" />
          <div class="text-box">
            <h3>Random Wishes</h3>
            <div class="price-flex">
              <p class="price">$7.99</p>
              <button>
                <img class="icon" src="@/assets/img/yen/heart.webp" alt="" />
              </button>
            </div>
          </div>
        </div>
      </a>
      <a href="#ghost-p4">
        <div
          data-aos="fade-down"
          data-aos-duration="2200"
          data-aos-easing="ease-out-back"
          data-aos-delay="600"
          class="card"
        >
          <img class="product" src="../assets/img/yen/3.webp" alt="" />
          <div class="text-box">
            <h3>Elf Fudge</h3>
            <div class="price-flex">
              <p class="price">$15.99</p>
              <button>
                <img class="icon" src="@/assets/img/yen/heart.webp" alt="" />
              </button>
            </div>
          </div>
        </div>
      </a>
      <a href="#ghost-p4">
        <div
          data-aos="fade-down"
          data-aos-duration="2200"
          data-aos-easing="ease-out-back"
          data-aos-delay="900"
          class="card"
        >
          <img class="product" src="../assets/img/yen/4.webp" alt="" />
          <div class="text-box">
            <h3>Icicle Confetti</h3>
            <div class="price-flex">
              <p class="price">$9.99</p>
              <button>
                <img class="icon" src="@/assets/img/yen/heart.webp" alt="" />
              </button>
            </div>
          </div>
        </div>
      </a>
      <a href="#ghost-p4">
        <div
          data-aos="fade-down"
          data-aos-duration="2200"
          data-aos-easing="ease-out-back"
          data-aos-delay="1200"
          class="card"
        >
          <img class="product" src="../assets/img/yen/5.webp" alt="" />
          <div class="text-box">
            <h3>Jingleberry Jars</h3>
            <div class="price-flex">
              <p class="price">$4.99</p>
              <button>
                <img class="icon" src="@/assets/img/yen/heart.webp" alt="" />
              </button>
            </div>
          </div>
        </div>
      </a>
      <a href="#ghost-p4">
        <div
          data-aos="fade-down"
          data-aos-duration="2200"
          data-aos-easing="ease-out-back"
          data-aos-delay="1500"
          class="card"
        >
          <img class="product" src="../assets/img/yen/6.webp" alt="" />
          <div class="text-box">
            <h3>Candy Candles</h3>
            <div class="price-flex">
              <p class="price">$11.99</p>
              <button>
                <img class="icon" src="@/assets/img/yen/heart.webp" alt="" />
              </button>
            </div>
          </div>
        </div>
      </a>
    </div>
  </section>
</template>

<style scoped>
.buyings-section {
  margin-bottom: 20rem;
  position: relative;
}
#ghost-p3 {
  position: absolute;
  top: -3rem;
  opacity: 0;
}
h2 {
  text-align: center;
  margin-bottom: 11rem;
}
.buyings-grid {
  display: grid;
  justify-items: center;
  grid-template-columns: 1fr 1fr 1fr;
  grid-row-gap: 9rem;
  max-width: 50vw;
  margin-inline: auto;
}
.card {
  background-color: #3a3a3a7c;
  border-radius: 2rem;
  width: 20rem;
  height: 19rem;
  position: relative;
}
.card:hover .product {
  transform: translate(-50%, -52%);
}
.product {
  width: 14rem;
  align-self: center;
  transition: transform 0.3s;
  position: absolute;
  left: 50%;
  top: 0;
  transform: translate(-50%, -47%);
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
  margin-bottom: 0.8rem;
  font-family: "Satisfy" !important;
}

.price-flex {
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.price {
  font-size: 1.8rem !important;
  color: #ddd;
  font-weight: 800;
  margin-top: 0.3rem;
}

.icon {
  display: flex;
  width: 3rem;
  transition: 0.1s;
}
.icon:hover {
  transform: scale(1.05);
}
button {
  background-color: transparent;
  border: none;
}
</style>
