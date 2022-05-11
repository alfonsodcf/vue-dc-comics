<template>
    <div>
        <img :src="detail.thumb" :alt="detail.series">
        <h3>{{detail.series}}</h3>
        

    </div>
</template>

<script>
    export default {
        name: 'AppCard',
        data(){
            return{

            }
        },
        props: {
            detail: Object
        }
    }
</script>

<style scoped lang="scss">
div{
    display: inline-block;
    padding: 20px;
    text-align: center;
    h3{
        color: white;
    }
}



</style>