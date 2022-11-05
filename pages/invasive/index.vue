<template>
    <div>
      <Search v-on:search-text='search-text'/>
        <Oxygen v-for="oxygen in oxygens" :key="oxygen.id" :id="oxygen.id" :oxygen="oxygen.oxygen" />
      <section>
        <ul>
          <li><nuxt-link to='/invasive/mechvent'>Mechanical Ventilation</nuxt-link></li>
          <li><nuxt-link to='/invasive/trach'>Tracheostomy</nuxt-link></li>
          <li><nuxt-link to='/'></nuxt-link></li>
          <li><nuxt-link to='/'></nuxt-link></li>
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
      title: 'Invasive Equipment',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Invasive eqiupment'
        }
      ]
    }
  }
}
</script>

<style>

</style>