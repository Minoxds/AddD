<template>
  <div class="container mt-5">
   
    <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item">
          <img src="./slide_image/01.jpg" alt="" height="400">
        </div>
        <div class="carousel-item active carousel-item-start">
          <img src="./slide_image/02.jpg" alt="" height="400">
        </div>
        <div class="carousel-item carousel-item-next carousel-item-start">
          <img src="./slide_image/03.png" alt="" height="400">
        </div>
        <div class="carousel-item carousel-item-next carousel-item-start">
          <img src="./slide_image/04.jpg" alt="" height="400">
        </div>
        <div class="carousel-item carousel-item-next carousel-item-start">
          <img src="./slide_image/05.jpeg" alt="" height="400">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>