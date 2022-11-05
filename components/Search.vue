<template>
    <div>
        <form @sumbit.prevent="onSubmit">
            <input type="text" v-model="text" placeholder="Search...">
            <input type="submit" value="Search">
        </form>
    </div>
</template>

<script>
export default {
    name: "Search",
    data(){
        return {
            text: ''
        }
    },methods: {
        onSumbit() {
            this.$emit('search-text', this.text);
            this.text="";
        }
    }
}
</script>

<style>

</style>