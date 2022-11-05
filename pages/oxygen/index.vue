<template>
    <div>
      <Search v-on:search-text='search-text'/>
        <Oxygen v-for="oxygen in oxygens" :key="oxygen.id" :id="oxygen.id" :oxygen="oxygen.oxygen" />
      <section>
        <ul>
          <li><nuxt-link to='/oxygen/nasalcannula'>Nasal Cannula</nuxt-link></li>
          <li><nuxt-link to='/oxygen/simplemask'>Simple Mask</nuxt-link></li>
          <li><nuxt-link to='/oxygen/venturimask'>Venturi Mask</nuxt-link></li>
          <li><nuxt-link to='/oxygen/bubbler'>Humidified Cannula or Mask</nuxt-link></li>
          <li><nuxt-link to='/oxygen/nonrebreather'>Non-Rebreather</nuxt-link></li>
          <li><nuxt-link to='/oxygen/bvm'>Bag Valve Mask</nuxt-link></li>
          <li><nuxt-link to='/oxygen/concentrator'>Concentrators</nuxt-link></li>
          <li><nuxt-link to='/oxygen/portable'>Portable Oxygen</nuxt-link></li>
          <li><nuxt-link to='/oxygen/liquid'>Liquid Oxygen</nuxt-link></li>
        </ul>
      </section>
    </div>
</template>

<script>
import Oxygen from '../../components/Oxygen';
import Search from "../../components/Search";

export default {
  components: {
    Oxygen,
    Search
  },
  methods: {
    async searchText(text){
      
    }
  },
  head() {
    return {
      title: 'Oxygen Equipment',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Oxyegn eqiupment'
        }
      ]
    }
  }
}
</script>

<style>

</style>