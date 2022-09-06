<template>
  <div class="menu-switch">
    <div class="menu-switch__nav">
      <button class="btn">Продукция</button>
      <button class="btn btn_outline btn_outline-access">Услуги</button>
    </div>

    <ul class="menu-switch__list">
      <li v-for="(item, i) in services" :key="item.title" class="menu-switch__item">
        <span class="menu-switch__count">0{{i + 1}}</span>
        <router-link :to="item.link" class="menu-switch__title">{{ item.title }}</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
data() {
  return {
    services: [
      {title: 'Ландшафтный дизайн', link: '/'},
      {title: 'Ладшафтное проектирование', link: '/'},
      {title: 'Посадка\пересадка крупномеров', link: '/'},
      {title: 'Благоустройство', link: '/'},
      {title: 'Озеленение', link: '/'},
      {title: 'Сервисный уход и обслуживание', link: '/'},
    ]
  }
}
}
</script>

<style>

</style>