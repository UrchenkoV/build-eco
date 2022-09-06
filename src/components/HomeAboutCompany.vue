<template>
  <div class="about-company">
    <div class="wrapper-lg">
      <div class="about-company__inner">
        <TheMenuWithSwitch />

        <div>
          <div class="base-heading">
            <div class="base-heading__accent"></div>
            <div class="base-heading__wrap">
              <div class="base-heading__over-header">Самый большой склад камня в черноземье</div>
              <div class="base-heading__header">Комплексное благоустройство территорий природными материалами</div>
            </div>
          </div>

          <div class="about-company__stat-wrap">
            <div class="stat-company">
              <div class="stat-company__title">>20</div>
              <div class="stat-company__subtitle">лет на рынке</div>
            </div>
            <div class="stat-company">
              <div class="stat-company__title">>1500</div>
              <div class="stat-company__subtitle">успешно завершенных проектов</div>
            </div>
            <div class="stat-company">
              <div class="stat-company__title">>150</div>
              <div class="stat-company__subtitle">крупномеров пересажено</div>
            </div>
            <div class="stat-company">
              <div class="stat-company__title">>10000 м3</div>
              <div class="stat-company__subtitle">камня в наличии на складе в Воронеже</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import TheMenuWithSwitch from './TheMenuWithSwitch.vue';
export default {
    components: { TheMenuWithSwitch }
}
</script>

<style>
</style>