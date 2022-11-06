<template>
    <div>
        <nuxt-link to="/invasive">Back</nuxt-link>
        <h1>Tracheostomy</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
        <img src="/images/trach.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Tracheostomy',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Tracheostomy'
            }
        ]
        }
    }
}
</script>