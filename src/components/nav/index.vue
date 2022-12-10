<template>
  <MobileNav class="navbar-mbl" />
  <nav
    id="nav"
    class="navbar navbar-expand-lg navbar-light bg-white navbar-desktop"
  >
    <div class="container-fluid nav-container h-100 me-4">
      <a class="navbar-brand" href="#"
        ><img
          src="https://www.unlimint.com/wp-content/themes/unlimint/assets/images/logo.svg"
      /></a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarTogglerDemo02"
        aria-controls="navbarTogglerDemo02"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navbarTogglerDemo02" class="collapse navbar-collapse mx-2">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a v-b-toggle.collapse-2 class="nav-link nav-dropdown" href="#"
              >Our Solution</a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Integration</a>
            <div class="nav-header-active"></div>
          </li>
          <li class="nav-item">
            <a v-b-toggle.collapse-3 class="nav-link nav-dropdown" href="#"
              >About</a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Partnerships</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Get in touch</a>
          </li>
        </ul>
        <ul class="navbar-nav me-auto ms-auto mb-2 mb-lg-0">
          <li class="nav-item nav-second">
            <a class="nav-link" href="#">
              <img
                src="https://www.unlimint.com/wp-content/themes/unlimint/assets/images/search.svg"
              />
            </a>
          </li>
          <li class="nav-item nav-second">
            <a class="nav-link demo-btn" href="#">Demo</a>
          </li>
          <li class="nav-item nav-second">
            <a class="nav-link" href="#">Login</a>
          </li>
        </ul>
        <ul class="navbar-nav nav-third me-auto ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a id="popover-3" class="nav-link nav-dropdown" href="#">
              <img
                src="https://www.unlimint.com/wp-content/themes/unlimint/assets/images/flags/svg/global.svg"
                alt=""
              />
            </a>
            <b-popover
              target="popover-3"
              triggers="click blur"
              placement="bottom"
              custom-class="region-popover"
            >
              <template #title>
                <div class="region-title">
                  <h2>SELECT REGION</h2>
                  <p>PRODUCTS MAY VARY</p>
                </div>
              </template>
              <ul class="list-group list-group-flush ps-0">
                <li class="list-group-item border-0 ps-0 mb-2">
                  <img
                    src="https://www.unlimint.com/wp-content/themes/unlimint/assets/images/flags/svg/global.svg"
                    alt=""
                  />
                  Region 1
                </li>
                <li class="list-group-item border-0 ps-0 mb-2">
                  <img
                    src="https://www.unlimint.com/wp-content/themes/unlimint/assets/images/flags/svg/global.svg"
                    alt=""
                  />
                  Region 2
                </li>
                <li class="list-group-item border-0 ps-0 mb-2">
                  <img
                    src="https://www.unlimint.com/wp-content/themes/unlimint/assets/images/flags/svg/global.svg"
                    alt=""
                  />
                  Region 3
                </li>
                <li class="list-group-item border-0 ps-0 mb-2">
                  <img
                    src="https://www.unlimint.com/wp-content/themes/unlimint/assets/images/flags/svg/global.svg"
                    alt=""
                  />
                  Region 4
                </li>
                <li class="list-group-item border-0 ps-0 mb-2">
                  <img
                    src="https://www.unlimint.com/wp-content/themes/unlimint/assets/images/flags/svg/global.svg"
                    alt=""
                  />
                  Region 5
                </li>
              </ul>
            </b-popover>
          </li>
          <li class="nav-item">
            <a id="popover-language" class="nav-link nav-dropdown" href="#"
              >En</a
            >
            <b-popover
              target="popover-language"
              triggers="click blur"
              placement="bottom"
              custom-class="region-popover"
            >
              <template #title>
                <div class="region-title">
                  <h2>LANGUAGE</h2>
                </div>
              </template>
              <ul class="list-group list-group-flush ps-0">
                <li class="list-group-item border-0 ps-0">English</li>
                <li class="list-group-item border-0 ps-0">English</li>
                <li class="list-group-item border-0 ps-0">English</li>
                <li class="list-group-item border-0 ps-0">English</li>
              </ul>
            </b-popover>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <b-collapse id="collapse-2">
    <b-card class="bg-white border-0 header-dropdown">
      <div class="row text-start solution-section mt-0 pt-0">
        <div class="col-6 col-lg-2">
          A constantly evolving business interface for innovators
        </div>
        <div class="col-6 col-lg-2 me-4">
          <span class="solution-title">Services</span>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">ACCEPT PAYMENTS</p>
            <p class="solution-desc">
              Acquire cards, access alternative payment methods, and receive
              international transfers.
            </p>
          </div>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">MAKE PAYMENTS</p>
            <p class="solution-desc">
              Manage your corporate funds, make payouts, and issue cards.
            </p>
          </div>
        </div>
        <div class="col-6 col-lg-2 ms-4 ps-4 border-start border-dark">
          <span class="solution-title">Explores</span>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Card Acquiring</p>
            <p class="solution-desc">Card Payment processing</p>
          </div>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Payment Methods</p>
            <p class="solution-desc">Thousands of payment options</p>
          </div>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Iban Accounts</p>
            <p class="solution-desc">Move your money fast</p>
          </div>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Card Issuing</p>
            <p class="solution-desc">White-label solutions</p>
          </div>
        </div>
        <div class="col-6 col-lg-2">
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Gatefi</p>
            <p class="solution-desc">Fiat solution for Crypto, Defi, GameFi</p>
          </div>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Card Issuing</p>
            <p class="solution-desc">White-label solutions</p>
          </div>
        </div>
      </div>
    </b-card>
  </b-collapse>
  <b-collapse id="collapse-3">
    <b-card class="bg-white border-0 header-dropdown">
      <div class="row text-start solution-section mt-0 pt-0">
        <div class="col-6 col-lg-2"></div>
        <div class="col-6 col-lg-2 me-4">
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">About Company</p>
            <p class="solution-desc">Discover the story of unlimints</p>
          </div>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Blog</p>
            <p class="solution-desc">Read insights, grow your business</p>
          </div>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Careers</p>
            <p class="solution-desc">Join our team of fintech experts</p>
          </div>
        </div>
        <div class="col-6 col-lg-2 ms-4 ps-4 border-start border-dark">
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Events</p>
            <p class="solution-desc">Meet us worldwide</p>
          </div>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Media Room</p>
            <p class="solution-desc">Explore news and resources</p>
          </div>
          <div>
            <p class="solution-subtitle m-0 p-0 mt-2">Contacts</p>
            <p class="solution-desc">Speak with team</p>
          </div>
        </div>
        <div class="col-6 col-lg-2"></div>
      </div>
    </b-card>
  </b-collapse>
</template>

<script setup>
import MobileNav from "./MobileNav.vue";
</script>
<style>
#nav {
  height: 100px !important;
}
#nav ul a {
  font-size: 16px !important;
  color: #000000;
  line-height: 15px;
  margin-left: 13px;
}
#nav ul a:hover {
  opacity: 0.5;
}
.nav-container,
.solution-section {
  margin: 10px 6.5rem !important;
}
.header-dropdown {
  width: 100vw;
  position: absolute !important;
  z-index: 999;
}
.navbar-brand {
  display: block;
  width: 140px;
  height: 28px;
  margin-right: 71px !important;
}
.demo-btn {
  background-color: #c9f73a;
  border: none;
  width: 6.5rem;
}
.nav-dropdown::after {
  content: "";
  margin-left: 4px;
  display: inline-block;
  vertical-align: middle;
  width: 16px;
  height: 16px;
  background-image: url("data:image/svg+xml,%3Csvg width='16' height='16' viewBox='0 0 16 16' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M4 6L8 10L12 6' stroke='black'/%3E%3C/svg%3E ");
}
.nav-third {
  margin-left: 2rem;
}
.popover .popover-arrow {
  display: none !important;
}
.region-title,
.region-title h2 {
  font-size: 14px !important;
  color: gray;
  letter-spacing: 1px;
}
.region-title p {
  font-size: 7px !important;
}
.region-popover {
  width: 200px !important;
}
.list-group-item {
  font-size: 16px;
}
.solution-section .solution-title,
.solution-subtitle {
  color: gray;
  font-size: 12px;
  text-transform: UPPERCASE;
  font-weight: 600;
  letter-spacing: 0.04em;
}
.solution-subtitle {
  font-size: 15px;
  color: #000000;
}
.solution-desc {
  color: gray;
  font-size: 15px;
  font-size: 14px;
}
@media (max-width: 1430px) {
  .navbar-desktop {
    display: none !important;
  }
}
</style>
