<template>
  <main id="main">
    <div class="media">
      <section class="main_content">
        <h2>Откройте для себя новые фильмы и сериалы</h2>
        <div class="results">
          <h2> {{ data }}</h2>
        </div>
      </section>
    </div>
  </main>
</template>

<script>
export default {
  name: 'Search',
  data: fetch('https://api.themoviedb.org/3/movie/550?api_key=784aa5829cc5a6cf9ac915a35ad9be1d')
.then(function(response) {
  console.log(response.headers.get('Content-Type')); // application/json; charset=utf-8
  console.log(response.status); // 200
  return response.json();
 })
.then(
  title => {
  console.log(title.title);
})
.catch( alert );
}

</script>

<style  scoped lang="scss">
@import '../assets/Search/Search.css';
</style>
