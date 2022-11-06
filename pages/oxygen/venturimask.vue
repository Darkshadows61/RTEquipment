<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Venturi Mask</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
        <img src="/images/vm.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Nasal Cannula',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Venturi Mask'
            }
        ]
        }
    }
}
</script>