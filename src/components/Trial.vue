<script setup>

import {onMounted, ref} from 'vue'

// defineProps({
//     name : String,
//     isChutiya : Boolean,
// })

// NAMEEEEE
var name = ref("varun")
function changeName(newName){
    name = newName
}
onMounted(() => {
    changeName("SINGH SAHAB")
    console.log("Name updated")
})


// MORONNNNNN
var isMoron = ref(true)
function changeMoronState(){
    isMoron = false
}
onMounted(() => {
    changeMoronState()
    console.log("Moron state updated")
})


//Applying list based applications

var somethingList


</script>

<template>
    <h1>{{ name }}</h1>
</template>