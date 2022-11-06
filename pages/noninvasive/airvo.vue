<template>
    <div>
        <nuxt-link to="/noninvasive">Back</nuxt-link>
        <h1>Airvo 2</h1>
        <p>This is an app that displays common Respiratory Equipment</p>
        <img src="/images/airvo.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'High Flow Nasal Cannula',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'High Flow Nasal Cannula'
            }
        ]
        }
    }
}
</script>