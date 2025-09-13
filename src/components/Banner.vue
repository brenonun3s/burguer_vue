<template>
  <div id="main-banner">
    <img src="@/assets/burger.jpg" alt="Banner" />
    <h1>Make Your Burger</h1>
  </div>
</template>

<style scoped>
#main-banner {
  position: relative;
  width: 100%;
  height: 500px;
  overflow: hidden;
}

#main-banner img {
  max-width: 100%; /* ocupa no máximo 80% da largura */
  max-height: 100%;
  object-fit: contain; /* mostra inteira sem cortar */
  background-color: #000; /* fundo se sobrar espaço */
}

#main-banner h1 {
  position: absolute;
  bottom: 20px;
  left: 20px;
  color: #fff;
  font-size: 60px;
  background-color: #222;
  padding: 20px 40px;
}
</style>
