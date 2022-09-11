<template>
  <div class="our-contact">
    <div class="wrapper-md">
      <div class="base-heading">
        <div class="base-heading__accent"></div>
        <div class="base-heading__wrap">
          <div class="base-heading__over-header">Контакты</div>
          <div class="base-heading__header">Наши филиалы</div>
        </div>
      </div>
    </div>

    <div class="our-contact__content-external">
      <div class="wrapper-lg">
        <div class="our-contact__content">
          <div>
            <ul class="our-contact__list">
              <li v-for="(a, i) in list" :key="a" class="our-contact__list-item">
                <span class="our-contact__address" :class="i === 0 && 'our-contact__active'">{{ a.address }}</span>
                <span class="our-contact__route">Построить маршрут</span>
              </li>
            </ul>
          </div>

          <div class="our-contact__contact-external">
            <div class="our-contact__contact-wrap">
              <div class="our-contact__contact-title">Телефон:</div>
              <div class="our-contact__contact-value">+7 (495) 333-55-77</div>
            </div>
            <div class="our-contact__contact-wrap">
              <div class="our-contact__contact-title">E-mail:</div>
              <div class="our-contact__contact-value">prosto@mail.ru</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="our-contact__map">
      <img src="/map.jpg" alt="">
    </div>
  </div>
</template>

<script>
export default {
data() {
  return {
    list: [
      {address: 'г. Воронеж, Монтажный проезд, 7'},
      {address: 'г. Воронеж, микрорайон Репное, ул. Придорожная, 28а'},
      {address: 'г. Воронеж, Нечаевка пос., ул. Рубежная, 62'},
      {address: 'Московская обл., п. Десна'},
    ]
  }
}
}
</script>

<style>

</style>