<template>
  <div class="our-specialization">
    <div class="wrapper-md">
      <div class="base-heading">
        <div class="base-heading__accent"></div>
        <div class="base-heading__wrap">
          <div class="base-heading__over-header">предоставляем большой спектр услуг в сфере ландшафтного дизайна </div>
          <div class="base-heading__header">Наша специализация</div>
        </div>
      </div>

      <div class="slider-v3">
        <div class="slider-v3__slide">
          <div class="slider-v3__content">
            <h3 class="slider-v3__title h3">Благоустройство</h3>
            <ul class="slider-v3__list">
              <li v-for="item in list" :key="item" class="slider-v3__list-item">{{ item }}</li>
            </ul>

            <router-link to="#" class="btn-link-icon btn-link">
              <span class="btn-link-underline-dashed">Узнать подробнее</span>
              <svg xmlns="http://www.w3.org/2000/svg" width="8" height="12" viewBox="0 0 8 12" fill="none">
                <path
                  d="M7.10387 5.6707L1.55351 0.1357C1.37166 -0.0455414 1.07724 -0.0452367 0.895697 0.136637C0.714292 0.318488 0.714761 0.613073 0.896635 0.794455L6.11661 6.00002L0.896447 11.2056C0.714596 11.387 0.714128 11.6814 0.89551 11.8632C0.986517 11.9544 1.10574 12 1.22497 12C1.34389 12 1.46265 11.9547 1.55349 11.8642L7.10387 6.32931C7.19145 6.24217 7.2406 6.12358 7.2406 6.00002C7.2406 5.87646 7.19131 5.758 7.10387 5.6707Z"
                  fill="currentColor" />
              </svg>
            </router-link>

            <div class="arrow-button">
              <button class="arrow-button__btn">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                  <g clip-path="url(#clip0_2604_501)">
                    <path
                      d="M0.183105 14.5581L9.55811 5.18312C9.80227 4.93896 10.1978 4.93896 10.4419 5.18312C10.686 5.42728 10.686 5.82279 10.4419 6.06689L2.13375 14.375H29.375C29.7204 14.375 30 14.6546 30 15C30 15.3455 29.7204 15.6251 29.375 15.6251H2.13375L10.4419 23.9331C10.686 24.1773 10.686 24.5728 10.4419 24.8169C10.3198 24.9389 10.1599 25 9.99996 25C9.84006 25 9.68016 24.9389 9.55805 24.8169L0.183046 15.4419C-0.0610542 15.1978 -0.0610542 14.8023 0.183105 14.5581Z"
                      fill="currentColor"></path>
                  </g>
                </svg>
              </button>
              <button class="arrow-button__btn">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 40 40">
                  <g clip-path="url(#clip0_2_737)">
                    <path
                      d="M39.7559 19.4102L27.2559 6.91018C26.9303 6.58463 26.403 6.58463 26.0775 6.91018C25.752 7.23572 25.752 7.76307 26.0775 8.08853L37.155 19.166H0.833359C0.372734 19.166 0 19.5388 0 19.9994C0 20.46 0.372734 20.8328 0.833359 20.8328H37.155L26.0775 31.9102C25.752 32.2357 25.752 32.7631 26.0775 33.0885C26.2402 33.2513 26.4535 33.3327 26.6667 33.3327C26.8799 33.3327 27.0931 33.2513 27.2559 33.0885L39.7559 20.5885C40.0814 20.2631 40.0814 19.7357 39.7559 19.4102Z"
                      fill="currentColor"></path>
                  </g>
                </svg>
              </button>
            </div>
          </div>

          <div class="slider-v3__image">
            <img src="/image-1.jpg" alt="">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      list: [
        'Устройство дренажа',
        'Планировка территории',
        'Монтаж системы полива и орошения',
        'Строительство дорожек, площадок, подпорных стенок',
        'Строительство водоемов, каскадов, ручьев, гротов',
        'Разработка, подбор и строительство пергол, беседок, садовой мебели, малых архитектурных форм и т.д.',
        'Строительство спортивных и детских площадок'
      ]
    }
  }
}
</script>

<style>
</style>