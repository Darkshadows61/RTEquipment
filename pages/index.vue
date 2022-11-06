<template>
  <div>
    <h2>Welcome to the best place to learn about different Respiratory Care Equipment</h2>
    <p>Please click on a section below to learn more about each area of therapy</p>
    <ul>
            <li>
                <nuxt-link to='/oxygen'>Oxygen</nuxt-link>
            </li>
            <li>
                <nuxt-link to='/noninvasive'>CPAP/BiPAP</nuxt-link>
            </li>
            <li>
                <nuxt-link to='/invasive'>Invasive</nuxt-link>
            </li>
        </ul>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Welcome to RT Equipment',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Best place to learn about RT equipment'
        }
      ]
    }
  }
};
</script>

<style>
h2{
  text-decoration: none;
}</style>