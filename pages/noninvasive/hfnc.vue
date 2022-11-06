<template>
    <div>
        <nuxt-link to="/noninvasive">Back</nuxt-link>
        <h1>High Flow Nasal Cannula</h1>
        <ul>
            <li> High Flow oxygen therapy via nasal cannula </li>
            <li> Delivers up to 40L and 100% FiO2. </li>
        </ul>
        <p class="brand"> Brand: Philips Respironics</p>
        <img src="/images/hfnc.jpg">
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