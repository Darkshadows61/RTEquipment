<template>
    <div>
        <nuxt-link to="/noninvasive">Back</nuxt-link>
        <h1>BiPAP</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
        <img src="#">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'BiPAP',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'BiPAP'
            }
        ]
        }
    }
}
</script>