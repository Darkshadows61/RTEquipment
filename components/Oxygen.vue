<template>
    <nuxt-link :to="'oxygen/' + id">
        <div class="oxygen">
            <p>{{oxygen}}</p>
        </div>
    </nuxt-link>
  </template>
  
  <script>
  export default {
        name:'Oxygen',
        props: ['device', 'id']
  };
  </script>

<style>
    .oxygen{
        padding: 1rem;
        border: 1px dotted #ccc;
        margin: 1rem 0;
    }
</style>