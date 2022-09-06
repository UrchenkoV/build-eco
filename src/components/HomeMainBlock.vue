<template>
  <div class="main-block">
    <div class="main-block__slider">
      <div class="main-block__slider-marks">
        <div class="main-block__slider-mark"></div>
        <div class="main-block__slider-mark main-block__slider-mark_active"></div>
        <div class="main-block__slider-mark"></div>
        <div class="main-block__slider-mark"></div>
      </div>



      <div class="main-block__slider-slides">
        <div class="main-block__slider-slide" style="background-image: url('/1.png')">
          <div class="wrapper-sm">
            <div class="main-block__slider-slide-content">
              <div>
                <h2 class="main-block__slider-slide-title h1">Самый большой <br> склад камня в Черноземье</h2>

                <router-link to="/" class="btn btn_green btn_lg">Узнать подробнее</router-link>
              </div>
              <div>
                <div class="main-block__slider-slide-mark">
                  <p>10 000 м3</p>
                  <span>в наличии</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="main-block__arrow-wrapper">
        <div class="wrapper-sm">
          <div class="arrow-button">
            <button class="arrow-button__btn">
              <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                <g clip-path="url(#clip0_2604_501)">
                  <path
                    d="M0.183105 14.5581L9.55811 5.18312C9.80227 4.93896 10.1978 4.93896 10.4419 5.18312C10.686 5.42728 10.686 5.82279 10.4419 6.06689L2.13375 14.375H29.375C29.7204 14.375 30 14.6546 30 15C30 15.3455 29.7204 15.6251 29.375 15.6251H2.13375L10.4419 23.9331C10.686 24.1773 10.686 24.5728 10.4419 24.8169C10.3198 24.9389 10.1599 25 9.99996 25C9.84006 25 9.68016 24.9389 9.55805 24.8169L0.183046 15.4419C-0.0610542 15.1978 -0.0610542 14.8023 0.183105 14.5581Z"
                    fill="currentColor" />
                </g>
              </svg>
            </button>
            <button class="arrow-button__btn">
              <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 40 40">
                <g clip-path="url(#clip0_2_737)">
                  <path
                    d="M39.7559 19.4102L27.2559 6.91018C26.9303 6.58463 26.403 6.58463 26.0775 6.91018C25.752 7.23572 25.752 7.76307 26.0775 8.08853L37.155 19.166H0.833359C0.372734 19.166 0 19.5388 0 19.9994C0 20.46 0.372734 20.8328 0.833359 20.8328H37.155L26.0775 31.9102C25.752 32.2357 25.752 32.7631 26.0775 33.0885C26.2402 33.2513 26.4535 33.3327 26.6667 33.3327C26.8799 33.3327 27.0931 33.2513 27.2559 33.0885L39.7559 20.5885C40.0814 20.2631 40.0814 19.7357 39.7559 19.4102Z"
                    fill="currentColor" />
                </g>
              </svg>
            </button>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
</style>