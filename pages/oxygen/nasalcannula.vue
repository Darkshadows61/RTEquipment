<template>
    <div>
        <nuxt-link to="/oxygen">Back</nuxt-link>
        <h1>Nasal Cannula</h1>
        <ul>
            <li> Used for low-flow oxygen delivery via two prongs inserted into the nose </li>
            <li> Limited to 1-6L </li>
            <li> Features nonflred tips with adjustable tubing </li>
            <li> Optional soft padding for ears </li>
        </ul>
        <p class="brand"> Brand: Salter Labs</p>
        <img class="device" src="/images/nc.jpg">
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
                content: 'Nasal Cannula'
            }
        ]
        }
    }
}
</script>