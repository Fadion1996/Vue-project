<template>
  <div class="search-bar">
    <section class="search">
      <div class="search-media">
        <form id="serch_form" action="/search" method="get">
          <span>
            <input id="search_film" type="text" name="query" value="" placeholder="Найти фильм, сериал, актера">
          </span>
        </form>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Search'
}
</script>

<style  scoped lang="scss">
@import '../assets/Search/Search.css';
</style>
