<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Oxygen Concentrators</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
        <img src="/images/concentrator.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Oxygen Concentrators',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Oxygen Concentrators'
            }
        ]
        }
    }
}
</script>