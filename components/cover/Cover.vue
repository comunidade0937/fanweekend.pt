<template>
  <div class="cover-page">
    <div></div>
    <img class="image" src="./logo.svg" />
    <div class="bottom">
      <p class="has-text-centered">Scroll down for more details...</p>
    </div>
  </div>
</template>

<style scoped>
.cover-page {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;

  padding: 0 2rem;

  min-width: 100vw;
  min-height: 100vh;
  background: url(./background.svg) #458db6;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
  background-attachment: fixed;
}

.bottom {
  padding-bottom: 2rem;
}

.image {
  max-width: 50vw;
  max-height: 50vh;
}
</style>
