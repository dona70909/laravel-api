<template>
    <div class="container">
        <div class="row justify-content-center">
            <Post/>
        </div>
    </div>
</template>

<script>

import Post from '../components/Post.vue'; 

    export default {

        name:'Posts',
        mounted() {
            console.log('Component mounted.')
        },
        
        components: {
            Post,
        }
    }
</script>
