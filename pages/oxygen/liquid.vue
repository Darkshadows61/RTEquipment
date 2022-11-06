<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Liquid Oxygen</h1>
        <ul>
            <li> Portable liquid oxygen system </li>
            <li> Flows up to 5L</li>
            <li> Lasts 12 hours longer than conventional compressed O2 </li>
        </ul>
        <p class="brand"> Brand: Helios</p>
        <img src="/images/liquid.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Liquid Oxygen',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Liquid Oxygen'
            }
        ]
        }
    }
}
</script>