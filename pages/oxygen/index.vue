<template>
    <div>
      <Search v-on:search-text="searchText"/>
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
import Search from "../../components/Search";

export default {
  components: {
    Search
  },
  methods: {
    async searchText(){
      const config = {
        headers: {
          Accept: "application/json"
        }
      };

      try {
        const res = await axios.get(
          `localhost:3000/oxygen/${text}`,
          config
        );

        this.oxygen = res.data.results;
      } catch (err) {
        console.log(err)
      }
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