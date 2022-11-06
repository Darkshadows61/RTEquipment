<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Humidified Oxygen</h1>
        <ul>
            <li> Used to add humidification to low flow oxygen delivery devices </li>
            <li> Limited to 1-6L and features a pop off valve at 6L</li>
            <li> 90 degree elbow removes torque </li>
            <li> Distilled water seperate </li>
        </ul>
        <p class="brand"> Brand: Westmed</p>
        <img src="/images/bubbler.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Bubblers',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Bubblers'
            }
        ]
        }
    }
}
</script>