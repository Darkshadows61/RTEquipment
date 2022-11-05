<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Bag Valve Mask</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
        <img src="#">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Bag Valve Mask',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Bag Valve Mask'
            }
        ]
        }
    }
}
</script>