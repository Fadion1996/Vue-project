<template>
  <div class="content">
    <div class="top-content">
      <div class="left">
        <ul class="primary">
          <a href="#"><li><img src="../assets/logo.svg" alt="Logo"></li></a>
          <a href="#"><li>Обзор</li></a>
          <a href="#"><li>Фильмы</li></a>
          <a href="#"><li>Сериалы</li></a>
          <a href="#"><li>Актеры</li></a>
        </ul>
      </div>
      <div class="right">
        <ul class="primary">
          <a href="#"><li>Войти</li></a>
          <a href="#"><li>Зарегистрироваться</li></a>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style  scoped lang="scss">
@import '../assets/Header/Header.css';
</style>
