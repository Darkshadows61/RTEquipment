<template>
    <div>
        <nuxt-link to="/noninvasive">Back</nuxt-link>
        <h1>BiPAP</h1>
        <ul>
            <li> Bi-Level Positive Airway Pressure </li>
            <li> Alternative to invaisve procedures</li>
            <li> Supports HFNC and Full Face Masks </li>
            <li> Delivers up to 40L and 100% FiO2. </li>
        </ul>
        <p class="brand"> Brand: Philips Respironics</p>
        <img src="/images/bipap.jpg">
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