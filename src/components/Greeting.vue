<template>
    <div id="name">
        <span>
            Name не крутой
        </span>
    </div>
</template>

<script setup>

import { ref } from "vue";


</script>

<style scoped>
#name {
    border: 1px solid black;
    margin-top: 100px;
    padding: 10px;
}

@keyframes moving {
    0%   {left: -400px;}
    100% {left: 450px;}
}

#name span {
    position: relative;
    font-size: 36px;
    font-family: 'Courier New', Courier, monospace;
    animation-name: moving;
    animation-duration: 4s;
    animation-iteration-count: infinite;
    animation-timing-function: ease-in-out;
}
</style>