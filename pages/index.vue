<template>
  <main class="main">
  <button class="startBtn"> Start</button>
  </main>
</template>

<script>
export default {
   data(){
        return {
            isStarted: false
        }
    },
    methods: {
        appStart(){
            this.isStarted = true
        }
    }
  
}
</script>

<style>
 .main{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.startBtn{
    padding: 10px 20px;
}
</style>