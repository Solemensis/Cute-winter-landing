<template>
  <div>
    <Navbar />
    <MainSection />
    <CardsSection />
    <InfoSection />
    <GridSection />
    <InfoSection2 />
    <Footer />
  </div>
</template>

<style>
/* @import url("https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap"); */
@import url("https://fonts.googleapis.com/css2?family=PT+Sans:ital,wght@0,400;0,700;1,400;1,700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,400;0,500;1,300;1,400;1,500&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Shadows+Into+Light&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Satisfy&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Kalam:wght@300;400;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Butcherman&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Kalam";
}
html {
  font-size: 62.5%;
  user-select: none;
  scroll-behavior: smooth;
}

h3 {
  color: #eee;
}
h2 {
  font-family: "Butcherman";
  line-height: 1.25;
  font-size: 4.2rem;
  font-weight: 300;
  color: #ca5a15ea;
}
h3 {
  font-family: "Kalam";
  font-size: 2.3rem;
}
p {
  color: #ddd;
}
body {
  background-image: linear-gradient(#00000084, #00000084),
    url(@/assets/img/11.jpg);
  background-position: center;
  background-size: cover;
  background-attachment: fixed;
  background-repeat: no-repeat;
  overflow-x: hidden;
}
a {
  cursor: default;
}

/*=============== scroll bar ===============*/
::-webkit-scrollbar {
  width: 1rem;
  /* border-radius: 0.5rem; */
  background-color: hsl(22, 8%, 10%);
}
::-webkit-scrollbar-thumb {
  border-radius: 0.5rem;
  background-color: hsl(22, 8%, 15%);
}
::-webkit-scrollbar-thumb:hover {
  background-color: hsl(22, 8%, 20%);
}

/*=============== media query ===============*/
@media (min-width: 1800px) {
  html {
    font-size: 78%;
  }
}

@media (max-width: 1520px) {
  html {
    font-size: 71%;
  }
}
@media (max-width: 1390px) {
  html {
    font-size: 58%;
  }
}
@media (max-width: 1290px) {
  html {
    font-size: 58%;
  }
}
@media (max-width: 1150px) {
  html {
    font-size: 50%;
  }
}
@media (max-width: 1050px) {
  html {
    font-size: 47%;
  }
}
@media (max-width: 950px) {
  html {
    font-size: 38%;
  }
}
@media (dimension: portrait) {
  html {
    font-size: 38%;
  }
}
</style>
