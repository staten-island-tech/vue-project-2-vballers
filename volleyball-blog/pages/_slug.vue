<template>
    <div>
        <h1>{{ post.name }}</h1>
    </div>
</template>

<script>
    export default {
        async asyncData({$content, params}){
            const post = await $content('posts', params.slug).fetch()
            return {post}
        },
        
    }
</script>

<style  scoped>

</style>