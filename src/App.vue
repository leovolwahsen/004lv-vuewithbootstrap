<script setup>

</script>
 <!-- Importent to know here the height i had to set to the actual picture height, if this is not done all the height: 100% css in the child elements will not cange anything!!!
  <div id="carouselExample" class="carousel slide" style="width: 500px; height: 375px; overflow: hidden;"></div> -->
<template>
  <div class="container">
    <h1>Vue3 + Bootsrap</h1>
    <div id="carouselExample" class="carousel slide" style="width: 500px; height: 375px; overflow: hidden;">
      <div class="carousel-inner" style="width: 100%; height: 100%;">
        <div class="carousel-item active">
          <img src="https://images.unsplash.com/photo-1611162617474-5b21e879e113?auto=format&fit=crop&q=60&w=500&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTJ8fGljb25zfGVufDB8fDB8fHww" class="d-block " alt="..." >
        </div>
        <div class="carousel-item">
          <img src="https://images.unsplash.com/photo-1611162616305-c69b3fa7fbe0?auto=format&fit=crop&q=60&w=500&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTl8fGljb25zfGVufDB8fDB8fHww" class="d-block " alt="...">
        </div>
        <div class="carousel-item">
          <img src="https://images.unsplash.com/photo-1611162618071-b39a2ec055fb?auto=format&fit=crop&q=60&w=500&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTh8fGljb25zfGVufDB8fDB8fHww" class="d-block" alt="..." >
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>

<style scoped>


.carousel-item img {
  display: inline-block;
  height: fit-content;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
