<template>
  <section class="contacts">Контакты</section>
  <section class="title">
    <span>Цифровая визитка</span>
    <div class="title__wrapper">
      <img src="@/shared/images/logo.webp" alt="logo" class="title__logo" />
      <span class="title__text">NFC-КОНТАКТ</span>
    </div>
  </section>
  <section></section>
</template>
<script setup></script>
<style scoped lang="scss">
.title {
  &__logo {
    width: 100px;
  }
  &__wrapper {
    display: flex;
    flex-direction: row;
  }
}
</style>
