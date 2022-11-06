<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Oxygen Concentrators</h1>
        <ul>
            <li> Oxygen concentrators take in air from the room and filter out nitrogen. The process provides the higher amounts of oxygen needed for oxygen therapy. Concentrators may be large and stationary or small and portable </li>
        </ul>
        <p class='brand'> Brand: Philips Respironics</p>
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