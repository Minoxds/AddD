<script setup>
import { RouterLink, RouterView } from "vue-router";
import topic from "./components/topic.vue";

</script>

<template>
  <div class="d-flex justify-content-center">
    <div class="container">
      <header class="row mt-5" style="height: 200px;">
        <div class="col-2">
          <img alt="Vue logo" class="logo" src="@/assets/MJU_LOGO.svg" width="200" height="200" />
        </div>
        <div class="col-4 d-flex align-items-center">
          <topic msg="Wellcome to MJU" />
        </div>
        <div class="col">
          <div class="tria"></div>
          <nav class="container text-center" style="background-color: #83C25C;">
            <div class="row align-items-center" style="height: 50px;">
              <div class="col">
                <div >
                  <RouterLink to="/" class="text-light mu">หน้าหลัก</RouterLink>
                </div>
              </div>
              <div class="col-3">
                <RouterLink to="/subject" class="text-light mu">รายวิชา</RouterLink>
              </div>
              <div class="col">
                <RouterLink to="/AddDrop" class="text-light mu">เพิ่ม - ถอนรายวิชา</RouterLink>
              </div>
            </div>
          </nav>
        </div>
      </header>


      <RouterView />
    </div>
  </div>
</template>
<style scoped>
.tria {
  position: absolute;

  width: 0; 
  height: 0; 
  border-top: 25px solid transparent;
  border-bottom: 25px solid transparent;
  border-left: 30px solid #296336;
}

.mu{
  text-decoration: none;
  font-size: 15px;
  font-weight: bold;

}
</style>