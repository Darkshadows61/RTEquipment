<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Portable Oxygen Cylinders</h1>
        <ul>
            <li> Concentional portable compressed Oxygen tank </li>
            <li> Limited to 1-6L</li>
            <li> Carrying case sold seperately </li>
        </ul>
        <p class="brand"> Brand: Praxair</p>
        <img src="/images/portable.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Portable Oxygen Cylinders',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Portable Oxygen Cylinders'
            }
        ]
        }
    }
}
</script>