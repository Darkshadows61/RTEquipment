<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Simple Mask</h1>
        <ul>
            <li> Cannula-style strap sits comfortably over ears </li>
            <li> With and without tubing</li>
            <li> Medium and high concentration versions </li>
            <li> Fits securely on face </li>
        </ul>
        <p class="brand"> Brand: Salter Labs</p>
        <img src="/images/simplemask.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Simple Mask',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Simple Mask'
            }
        ]
        }
    }
}
</script>