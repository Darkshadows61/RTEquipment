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