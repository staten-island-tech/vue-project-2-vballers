<template>
    <div>
        <h1>Test</h1>
    </div>
</template>

<script>
    export default {
        async asyncData({$content, params}){
            const article = await $content('posts', params.slug).fetch()
            return {article}
        },
        
    }
</script>

<style  scoped>

</style>