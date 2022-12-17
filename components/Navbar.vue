<template>
  <header class="header-section">
    <div class="header-flex">
      <div class="logo-box">
        <img class="logo" src="@/assets/img/ss.webp" alt="" />
      </div>
      <nav class="navbar">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#ghost-p">Protector</a></li>
          <li><a href="#ghost-p2">Party</a></li>
          <li><a href="#ghost-p3"> Artifacts</a></li>
        </ul>
      </nav>
      <div
        class="balls-box"
        data-aos="fade-down"
        data-aos-duration="1400"
        data-aos-delay="1000"
        data-aos-easing="ease-out-back"
      >
        <img src="../assets/img/ss2.webp" class="balls" alt="" />
      </div>
      <div class="empty-div"></div>
    </div>
  </header>
</template>

<style scoped>
.header-section {
  /* position: fixed; */
  position: absolute;
  width: 100%;
}
.header-flex {
  padding-top: 2rem;
  width: 90%;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: relative;
}
.logo {
  width: 9rem;
}
.empty-div {
  width: 8rem;
}
.balls {
  position: absolute;
  right: -15rem;
  top: -5rem;
  transform: translateX(-50%) scaleX(-1);
  width: 27rem;
  opacity: 0.7;
  /* animation: up-down 5s alternate ease-in-out infinite; */
}
@keyframes up-down {
  0% {
    transform: translateX(-50%) scaleX(-1);
  }
  100% {
    transform: translateX(-50%) translateY(-2%) scaleX(-1);
  }
}
.balls-box {
  position: absolute;
  right: 0;
  top: 0;
}
.navbar {
  padding: 1rem 2rem;
  border-radius: 1rem;
}
.navbar ul {
  display: flex;
  list-style: none;
}

.navbar li {
  font-size: 2rem;
  font-weight: 500;
  margin-right: 5rem;
  z-index: 100;
}
.navbar a {
  color: #ddd;
  transition: 0.1s;
  z-index: 100;
  text-decoration: none;
}
.navbar a:hover {
  color: #d73e3e;
  cursor: pointer;
}
.navbar li:last-child {
  margin-right: 0;
}
</style>
