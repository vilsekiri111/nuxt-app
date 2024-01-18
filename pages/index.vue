<template>
  <div class="banner">
    <div>
      <img src="assets\images\leaf.png">
      <img class="offer" src="assets\images\offer.png" alt="">
      <div class="leftbanner">
        <img src="assets\images\todayspecial.png">
        <h1>
          The Online <br> Grocery store
        </h1>
        <button class="shopnow"> shop now </button>
      </div>
      <img class="avaco" src="assets\images\avacoda.png" alt="">
    </div>
    <div class="image">
      <img src="assets\images\side-image.png" alt="">
    </div>
  </div>
  <hr>
  <category/>
</template>

<style scoped>
.banner {
  display: flex;
  justify-content: center;
gap: 1rem;
 margin-left: 100px;
}

.shopnow {
  padding: 15px;
  border-radius: 25px;
  border-color: #678e61;
  background-color: #678e61;
}

.leftbanner {
  display: flex;
  flex-direction: column;
  gap: 1rem;

}

.avaco {
  position: relative;
  left: 200px;
}

.offer {
  position: relative;
  top: 0px;
  right: -499px;

}
</style>