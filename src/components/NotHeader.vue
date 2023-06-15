<template>
    <h1>COUNT ALL YOUR OMGS HERE!</h1>
    <img src="" alt="">
    <div @click="omgCounter" class="button-color">
        You just said OMG {{ count }} times!
    </div>
</template>

<script>
    export default{
        data() {
            return {
                count: 0
            }
        },

        methods: {
            omgCounter(){
                this.count++;
            }
        },
    }
</script>

<style scoped>
h1{
    font-size: 4rem;
}
.button-color{
    background-color: aqua;
    border: 1px solid magenta;
    border-radius: 10px;
    padding: 5px 10px;
    color: purple;
    font-weight: 500;
    margin-bottom: 30px;
}

.button-color:hover{
    cursor: pointer;
}
</style>