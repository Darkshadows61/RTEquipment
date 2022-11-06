<template>
    <div>
        <nuxt-link to="/invasive">Back</nuxt-link>
        <h1>Mechanical Ventilation</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
        <img src="/images/mechvent.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Mechanical Ventilation',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Mechanical Ventilation'
            }
        ]
        }
    }
}
</script>