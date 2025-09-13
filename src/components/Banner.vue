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
}

#main-banner img {
  width: 100%;
  height: auto;
  object-fit: contain;
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
