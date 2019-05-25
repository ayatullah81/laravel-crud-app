<template>
    <div>
        <div>
            
                <router-view></router-view>
            
        </div>
    </div>
</template>

<style>
    .fade-enter-active, .fade-leave-active {
      transition: opacity .5s
    }
    .fade-enter, .fade-leave-active {
      opacity: 0
    }
</style>

<script>
import Example from './components/ExampleComponent.vue';

    export default{
        name: 'app',
        components: {
            Example,
            
        }
    }
</script>