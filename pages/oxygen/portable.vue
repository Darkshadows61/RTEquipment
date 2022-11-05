<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Portable Oxygen Cylinders</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
        <img src="#">
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