<template>
  <div class="stone-use">
    <div class="wrapper-md">
      <div class="stone-use__inner">
        <div class="base-heading">
          <div class="base-heading__accent"></div>
          <div class="base-heading__wrap">
            <div class="base-heading__over-header">У нас огромный выбор камней для декора и строительства</div>
            <div class="base-heading__header">Камень по применению</div>
          </div>
        </div>

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

    </div>

    <div class="slider-stone">
      <div class="slider-stone__inner">
        <div v-for="slide in slides" :key="slide.title" class="slider-stone__slide">
          <div class="slider-stone__image">
            <img :src="slide.img" alt="">
          </div>
          <div class="slider-stone__content">
            <div class="slider-stone__title">{{ slide.title }}</div>
            <div class="slider-stone__action">
              <router-link :to="slide.link" class="slider-stone__link">Узнать подробнее</router-link>
              <span class="slider-stone__icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="52" height="16" viewBox="0 0 52 16" fill="none">
                  <path
                    d="M51.6998 9.116C52.0934 8.72864 52.0985 8.09549 51.7112 7.70183L45.3987 1.28676C45.0114 0.893096 44.3782 0.88799 43.9846 1.27535C43.5909 1.66271 43.5858 2.29586 43.9732 2.68952L49.5842 8.39181L43.8819 14.0029C43.4883 14.3902 43.4831 15.0234 43.8705 15.417C44.2579 15.8107 44.891 15.8158 45.2847 15.4284L51.6998 9.116ZM0.991936 8.99997L50.9903 9.40318L51.0064 7.40325L1.00806 7.00003L0.991936 8.99997Z"
                    fill="currentColor" />
                </svg>
              </span>
            </div>
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
      slides: [
        { title: 'Ландшафтный', img: '/stone-1.jpg', link: '/' },
        { title: 'Облицовочный', img: '/stone-2.jpg', link: '/' },
        { title: 'Печной', img: '/stone-3.jpg', link: '/' },
        { title: 'Мощения', img: '/stone-1.jpg', link: '/' },
        { title: 'Дорожки', img: '/stone-3.jpg', link: '/' },
        { title: 'Габионы', img: '/stone-2.jpg', link: '/' },
      ]
    }
  }
}
</script>

<style>
</style>