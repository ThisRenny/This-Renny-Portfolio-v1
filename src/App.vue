<template style="">
  <Profile />
</template>

<script>
import Profile from "./views/Profile";

export default {
  components: {
    Profile,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');

#app {
  background: rgb(30,30,40);
  background: linear-gradient(200deg, rgba(30,30,40,1) 0%, rgba(50,50,70,1) 100%);
  color: #ffffff;
  font-family: 'Roboto', sans-serif;
}
</style>