<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Liquid Oxygen</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
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