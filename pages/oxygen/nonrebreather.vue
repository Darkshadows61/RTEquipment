<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Non Rebreather</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
        <img src="#">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Non Rebreather',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Non Rebreather'
            }
        ]
        }
    }
}
</script>