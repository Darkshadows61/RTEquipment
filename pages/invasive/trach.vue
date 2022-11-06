<template>
    <div>
        <nuxt-link to="/invasive">Back</nuxt-link>
        <h1>Tracheostomy</h1>
        <ul>
            <li> An incision in the windpipe made to relieve an obstruction to breathing. </li>
        </ul>
        <p class="brand"> Brand: Westmed</p>
        <img src="/images/trach.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Tracheostomy',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Tracheostomy'
            }
        ]
        }
    }
}
</script>