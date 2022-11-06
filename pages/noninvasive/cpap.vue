<template>
    <div>
        <nuxt-link to="/noninvasive">Back</nuxt-link>
        <h1>CPAP</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
        <img src="/images/cpap.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'CPAP',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'CPAP'
            }
        ]
        }
    }
}
</script>