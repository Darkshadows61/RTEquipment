<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Venturi Mask</h1>
        <ul>
            <li> Venturi mask with 5 different set oxygen levels; 24%, 28%, 35%, 40%, and 50% </li>
            <li> Features 7' oxygen tubing and humidity cap</li>
        </ul>
        <p class="brand"> Brand: Salter Labs</p>
        <img src="/images/vm.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Nasal Cannula',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Venturi Mask'
            }
        ]
        }
    }
}
</script>