<template>
  <section class="page-home__promo">
    <div class="page-home__promo-inner">
      <div class="page-home__promo-bg"></div>
      <div class="page-home__promo-main">
        <div class="container home-top position-relative">
          <div class="row text-start">
            <div class="col">
              <h1 class="home-slogan">Is your<br />business<br />ready for<br />tomorrow?</h1>
              <button type="button" class="btn btn-dark home-btn">
                Meet your tommorrow managers
              </button>
            </div>
            <div class="col m-auto mt-4">
              <h3 class="home-info px-2">
                The world is being disrupted. Self-driving electric cars, drone delivery, virtual
                goods, robot dogs, VR travels, and even… space tourism. What's next? Embrace it or
                hate it, the future is here. How about your business, is it ready to embrace the
                change?
              </h3>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.home-top {
  min-height: 86.8vh;
  margin-top: 7rem;
}
.home-slogan {
  font-weight: 800;
  font-size: 4rem;
  color: black;
}
.home-btn {
  width: 300px;
  border: none;
  border-radius: 0;
  line-height: 3rem;
  margin-top: 3rem;
  font-size: 18px;
  color: white;
}

@media (max-width: 750px) {
  .home-btn {
    width: 100%;
  }
}
@media (max-width: 1430px) {
  .home-info {
    min-width: 600px;
  }
}
</style>
