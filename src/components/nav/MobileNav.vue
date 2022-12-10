<template>
  <div class="navbar-mbl">
    <nav
      id="nav"
      class="navbar navbar-mobile navbar-expand-lg navbar-light bg-white"
    >
      <div class="d-flex position-static">
        <div class="me-auto">
          <a class="navbar-brand" href="#"
            ><img
              src="https://www.unlimint.com/wp-content/themes/unlimint/assets/images/logo.svg"
          /></a>
        </div>
        <div class="d-flex position-absolute end-0 me-4 mbl-nav-second">
          <div class="ms-2">
            <a class="nav-link" href="#">
              <img
                src="https://www.unlimint.com/wp-content/themes/unlimint/assets/images/search.svg"
              />
            </a>
          </div>
          <div class="mbl-demo-btn ms-2">
            <a class="nav-link demo-btn" href="#">Demo</a>
          </div>
          <div class="ms-2" @click="showNav">
            <svg
              v-if="!openNav"
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <line
                x1="4"
                y1="8.83301"
                x2="28"
                y2="8.83301"
                stroke="black"
              ></line>
              <line x1="4" y1="15.5" x2="28" y2="15.5" stroke="black"></line>
              <line
                x1="4"
                y1="22.167"
                x2="28"
                y2="22.167"
                stroke="black"
              ></line>
            </svg>
            <svg
              v-else
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path d="M24 8L8 24" stroke="black"></path>
              <path d="M8 8L24 24" stroke="black"></path>
            </svg>
          </div>
        </div>
      </div>
    </nav>
    <div v-if="openNav" class="text-start mbl-nav-extend">
      <a class="nav-link demo-btn demo-below" href="#">Demo</a>
      <ul class="navbar-nav nav flex-column me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a
            v-b-toggle.collapse-2-mbl
            class="nav-link nav-link-mbl nav-dropdown"
            href="#"
            >Our Solution</a
          >
          <b-collapse id="collapse-2-mbl" trigger="click blur">
            <b-card class="bg-white border-0 header-dropdown-mbl">
              <div class="row text-start solution-section m-0 p-0">
                <div class="col-6 mb-4 p-0">
                  A constantly evolving business interface for innovators
                </div>
                <div class="col-6 mb-4 me-4 border-start border-dark">
                  <span class="solution-title">Services</span>
                  <div>
                    <p class="solution-subtitle m-0 p-0 mt-2">
                      ACCEPT PAYMENTS
                    </p>
                    <p class="solution-desc">
                      Acquire cards, access alternative payment methods, and
                      receive international transfers.
                    </p>
                  </div>
                  <div>
                    <p class="solution-subtitle m-0 p-0 mt-2">MAKE PAYMENTS</p>
                    <p class="solution-desc">
                      Manage your corporate funds, make payouts, and issue
                      cards.
                    </p>
                  </div>
                </div>
                <div class="col-6 border-start border-dark">
                  <span class="solution-title">Explores</span>
                  <div>
                    <p class="solution-subtitle m-0 p-0 mt-2">Card Acquiring</p>
                    <p class="solution-desc">Card Payment processing</p>
                  </div>
                  <div>
                    <p class="solution-subtitle m-0 p-0 mt-2">
                      Payment Methods
                    </p>
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
                  <div>
                    <p class="solution-subtitle m-0 p-0 mt-2">Gatefi</p>
                    <p class="solution-desc">
                      Fiat solution for Crypto, Defi, GameFi
                    </p>
                  </div>
                  <div>
                    <p class="solution-subtitle m-0 p-0 mt-2">Card Issuing</p>
                    <p class="solution-desc">White-label solutions</p>
                  </div>
                </div>
              </div>
            </b-card>
          </b-collapse>
        </li>
        <li class="nav-item">
          <a class="nav-link nav-link-mbl" href="#">Integration</a>
          <div class="nav-header-active"></div>
        </li>
        <li class="nav-item">
          <a
            v-b-toggle.collapse-3-mbl
            class="nav-link nav-link-mbl nav-dropdown"
            href="#"
            >About</a
          >
          <b-collapse id="collapse-3-mbl" trigger="click blur">
            <b-card class="bg-white border-0 header-dropdown-mbl">
              <div class="row text-start solution-section m-0 p-0">
                <div class="col-6"></div>
                <div class="col-6 me-4 border-start border-dark mb-4">
                  <div>
                    <p class="solution-subtitle m-0 p-0 mt-2">About Company</p>
                    <p class="solution-desc">Discover the story of unlimints</p>
                  </div>
                  <div>
                    <p class="solution-subtitle m-0 p-0 mt-2">Blog</p>
                    <p class="solution-desc">
                      Read insights, grow your business
                    </p>
                  </div>
                  <div>
                    <p class="solution-subtitle m-0 p-0 mt-2">Careers</p>
                    <p class="solution-desc">
                      Join our team of fintech experts
                    </p>
                  </div>
                </div>
                <div class="col-6 border-start border-dark">
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
                <div class="col-6"></div>
              </div>
            </b-card>
          </b-collapse>
        </li>
        <li class="nav-item">
          <a class="nav-link nav-link-mbl" href="#">Partnerships</a>
        </li>
        <li class="nav-item">
          <a class="nav-link nav-link-mbl" href="#">Get in touch</a>
        </li>
      </ul>
      <hr />
      <a class="nav-link nav-link-mbl" href="#">Login</a>
      <hr />
      <a
        v-b-toggle.region-dropdwon-mbl
        class="nav-link nav-link-mbl nav-dropdown"
        href="#"
        >Region</a
      >
      <b-collapse id="region-dropdwon-mbl" trigger="click blur">
        <b-card class="bg-white border-0 header-dropdown-mbl">
          <div class="region-title">
            <p>PRODUCTS MAY VARY</p>
          </div>
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
        </b-card>
      </b-collapse>
      <hr />
      <a
        v-b-toggle.lang-dropdwon-mbl
        class="nav-link nav-link-mbl nav-dropdown"
        href="#"
        >English</a
      >
      <b-collapse id="lang-dropdwon-mbl" trigger="click blur">
        <b-card class="bg-white border-0 header-dropdown-mbl">
          <ul class="list-group list-group-flush ps-0">
            <li class="list-group-item border-0 ps-0">English</li>
            <li class="list-group-item border-0 ps-0">English</li>
            <li class="list-group-item border-0 ps-0">English</li>
            <li class="list-group-item border-0 ps-0">English</li>
          </ul>
        </b-card>
      </b-collapse>
    </div>
  </div>
</template>
<script setup>
import { ref } from "vue";
const openNav = ref(false);
const showNav = () => {
  openNav.value = !openNav.value;
};
</script>
<style>
.demo-btn {
  width: 65px;
  line-height: 30px;
}
.demo-below {
  width: 100% !important;
  text-align: center;
  font-size: 2px;
  line-height: 3rem;
  margin-bottom: 2rem;
}
.nav-link-mbl {
  width: auto;
  font-size: 20px !important;
  font-weight: 500px !important;
}
.mbl-nav-extend {
  position: absolute;
  width: 100vw;
  min-height: 100vh;
  z-index: 9999;
  background: white;
}
@media (min-width: 1430px) {
  .navbar-mbl {
    display: none !important;
  }
}
@media (max-width: 1430px) {
  .solution-section {
    flex-direction: column;
    margin: 0 !important;
    padding: 0 !important;
    width: 100vw;
    text-align: start;
  }
  .solution-title {
    margin-bottom: 1rem !important;
  }
  .solution-desc {
    display: none !important;
  }
  .header-dropdown-mbl {
    position: relative !important;
  }
}
@media (max-width: 750px) {
  .mbl-demo-btn {
    display: none;
  }
}
@media (750px <= width <= 1430px) {
  .demo-below {
    display: none !important;
  }
}
.navbar-mobile,
.mbl-nav-extend {
  padding-left: 3rem !important;
  padding-right: 2rem !important;
}
</style>
