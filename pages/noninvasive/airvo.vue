<template>
    <div>
        <nuxt-link to="/noninvasive">Back</nuxt-link>
        <h1>Airvo 2</h1>
        <ul>
            <li> High Flow oxygen thepary complete with humidification </li>
            <li> Delviers flows from 30-60L and 21-100% O2</li>
            <li> Adjustable Alarm settings </li>
            <li> Compatable with Pediatric to Adult patients </li>
        </ul>
        <p class="brand"> Brand: Airvo</p>
        <img src="/images/airvo.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Airvo',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Airvo'
            }
        ]
        }
    }
}
</script>