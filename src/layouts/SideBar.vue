<template>
  <div id="side-bar-main">
    <p>This Renny</p>
    <hr id="hr-side-bar">
    <div class="btn-group-vertical" role="group" aria-label="...">
      <SideBarButton name="Profile"/>
      <SideBarButton name="Projects"/>
      <SideBarButton name="Social Net"/>
    </div>
  </div>
</template>

<script>
import SideBarButton from "../components/sidebar/SideBarButton";

export default {
  components: {
   SideBarButton,
  }
}
</script>

<style>
#side-bar-main {
  width: 230px;
  height: 1000px;
  align-items: center;
  text-align: center;
  justify-content: center;
  position: relative;
  left: 20px;
  background: rgb(247,47,47);
  background: linear-gradient(129deg, rgba(247,47,47,1) 0%, rgba(230,40,50,1) 100%);
  padding: 20px;
  border-radius: 10px;
}

#hr-side-bar {
  width: 192px;
}
</style>