<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Humidified Oxygen</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
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