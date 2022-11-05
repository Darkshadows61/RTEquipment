<template>
    <div>
      <Search v-on:search-text='search-text'/>
        <Oxygen v-for="oxygen in oxygens" :key="oxygen.id" :id="oxygen.id" :oxygen="oxygen.oxygen" />
      <section>
        <ul>
          <li><nuxt-link to='/noninvasive/cpap'>CPAP</nuxt-link></li>
          <li><nuxt-link to='/noninvasive/bipap'>BiPAP</nuxt-link></li>
          <li><nuxt-link to='/noninvasive/airvo'>AirVo</nuxt-link></li>
          <li><nuxt-link to='/noninvasive/hfnc'>High Flow Nasal Cannula</nuxt-link></li>
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
      title: 'CPAP/BiPAP',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Non-Invasive equipment'
        }
      ]
    }
  }
}
</script>

<style>

</style>