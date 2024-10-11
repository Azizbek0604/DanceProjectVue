<template>
  <div>
    <MainPageVue />
    <WorksProjectVue/>
    <MotobikesVue/>
    <JustRideVue/>
    <your-city-vue/>
    <ChangePage/>
  </div>
</template>

<script>
import JustRideVue from './components/JustRide.vue';
import MainPageVue from "./components/MainPage.vue";
import MotobikesVue from './components/Motobikes.vue';
import WorksProjectVue from './components/WorksProject.vue';
import YourCityVue from './components/YourCity.vue';
import ChangePage from './components/ChangePage.vue';

export default {
  components: {
    MainPageVue,
    WorksProjectVue,
    MotobikesVue,
    JustRideVue,
    YourCityVue,
    ChangePage,
  }
}
</script>