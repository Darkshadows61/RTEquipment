<template>
    <div>
      <Search v-on:search-text='search-text'/>
        <Oxygen v-for="oxygen in oxygens" :key="oxygen.id" :id="oxygen.id" :oxygen="oxygen.oxygen" />
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
      title: 'All About RT Oxygen Equipment',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Landing page for eqiupment'
        }
      ]
    }
  }
}
</script>

<style>

</style>