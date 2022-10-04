<template>
    <div>
        <h1>{{counter}}</h1>
        <button @click="counter++">+1</button>
        <button @click="counter--">-1</button>
        <button @click="counter=counter+5">+5</button>
        <button @click="counter=counter-5">-5</button>
        
    </div>
</template>
<script>
    export default{
        data(){
            return{
                counter:0
            }
        }
    }
</script>