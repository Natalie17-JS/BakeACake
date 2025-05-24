<template>
  <div class="home-container">
    <!-- Верхняя полоса с логотипом -->
    <div class="logo-bar">
      <img src="/logo.svg" alt="logo" class="logo-image" />
    </div>

    <!-- Центральная часть: окно и дверь -->
    <div class="middle-section">

        <div>
         <img src="/plant.svg" alt="plant" class="plant-image" />
      <div class="window"></div>
       <img src="/plant.svg" alt="plant" class="plant-image" />
       </div>

      <div class="door">
        <img src="/door.svg" alt="door" class="door-image" />
      </div>
    </div>

    <!-- Нижняя часть: дорога -->
    <div class="road"></div>
  </div>
</template>


<style scoped>
.logo-bar{
    width: 100vw;
    height: 30vh;
    background-color: coral;
}

</style>