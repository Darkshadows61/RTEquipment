<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Non Rebreather</h1>
        <ul>
            <li> Provides high flow Oxygen up to 15L and 80-100% O2 </li>
            <li> Available with or without safety vent</li>
            <li> Tubing is bonded to mask to prevent disconnects</li>
        </ul>
        <p class="brand"> Brand: Westmed</p>
        <img src="/images/nrb.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Non Rebreather',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Non Rebreather'
            }
        ]
        }
    }
}
</script>