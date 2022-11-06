<template>
  <div class="container">
      <AppHeader/>
      <nuxt />
  </div>
</template>

<script>
import AppHeader from '../components/AppHeader';

export default {
  components: {
      AppHeader
  }
}
</script>

<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

@viewport {
  width: device-width ;
  zoom: 1.0 ;
}

@media screen and (max-width: 320px) {
  /* comes into effect for screens less than or equal to 320 pixels */
  #somethingorother {
    width: 120px ;
  }
}
@media screen and (min-width: 321px) and (max-width: 480px) {
  /* comes into effect for screens between 321 and 480 pixels (inclusive) */
  #somethingorother {
    width: 320px ;
  }
}
@media screen and (min-width: 481px) {
  /* comes into effect for screens larger than or equal to 481 pixels */
  #somethingorother {
    width: 480px ;
  }
}

body{
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  background: #f4f4f4;
}

a{
  color: #666;
  text-decoration: none;
}

ul {
  list-style: none;
}

.device{
  max-width: 800px;
}

.brand{
  font-size:larger;
}

.container{
  max-width: 1440px;
  margin: 2rem auto;
  overflow: hidden;
  padding: 1rem 2rem;
  background: #fff;
}
</style>