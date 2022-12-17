<template>
  <footer class="footer-section">
    <div class="footer-flex">
      <div class="footer-tree-box">
        <img class="footer-tree" src="@/assets/img/ss.webp" alt="" />

        <div>
          <p class="footer-description">
            Enjoy the <span class="span-warmest">warmest</span>
            <br />
            night of your life...
          </p>
          <span class="footer-copy"
            >&#169; Copyright Solemensis. All rights reserved</span
          >
        </div>
      </div>
      <div class="footer-grid">
        <div>
          <h3 class="footer-title">About Us</h3>
          <ul class="footer-links">
            <li><a href="#" class="footer-link">About us</a></li>
            <li><a href="#" class="footer-link">Features</a></li>
            <li><a href="#" class="footer-link">News & Blog</a></li>
          </ul>
        </div>
        <div>
          <h3 class="footer-title">Services</h3>
          <ul class="footer-links">
            <li><a href="#" class="footer-link">Pricing</a></li>
            <li><a href="#" class="footer-link">Discounts</a></li>
            <li><a href="#" class="footer-link">Send a gift</a></li>
          </ul>
        </div>
        <div>
          <h3 class="footer-title">Company</h3>
          <ul class="footer-links">
            <li><a href="#" class="footer-link">Blog</a></li>
            <li><a href="#" class="footer-link">Celebrations</a></li>
            <li><a href="#" class="footer-link">About</a></li>
          </ul>
        </div>
        <!-- <div>
          <h3 class="footer-title">Social Media</h3>
          <ul class="footer-social">
            <a
              href="https://www.facebook.com/"
              target="_blank"
              class="footer-social-link"
              ><i class="ri-facebook-circle-fill"></i
            ></a>
            <a
              href="https://www.instagram.com/"
              target="_blank"
              class="footer-social-link"
              ><i class="ri-instagram-fill"></i
            ></a>
            <a
              href="https://twitter.com/"
              target="_blank"
              class="footer-social-link"
              ><i class="ri-twitter-fill"></i
            ></a>
          </ul>
        </div> -->
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer-section {
  margin-bottom: 3rem;
  max-width: 85%;
  margin-inline: auto;
}
.footer-tree-box {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  gap: 1rem;
}
.footer-tree-box div {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}
.footer-tree {
  width: 14rem;
}
.footer-tree-box p {
  font-size: 2rem;
}
.footer-description {
  line-height: 1.4;
}
.footer-flex {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10rem;
}
.span-warmest {
  color: #cf4343;
}
.footer-grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  column-gap: 4rem;
  justify-items: center;
  justify-content: center;
  align-items: center;
  align-content: center;
}
.footer-title {
  font-size: 2.2rem;
  margin-bottom: 1rem;
  color: #cf4343;
}
.footer-grid a,
a:active {
  text-decoration: none;
  color: #bbb;
  font-size: 1.8rem;
}
a:hover {
  cursor: pointer;
}
.footer-copy {
  color: #999;
}
</style>
