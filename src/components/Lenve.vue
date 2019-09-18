<template>
    <div>
        <h1 v-for="(item,index) in items" :key='index'>
            {{item}}
        </h1>
        <h3 v-if="seen"></h3>
        <h3 v-else></h3>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:true,
            items:[
                '衣服',
                '裤子',
                '袜子'
            ]
        }
    }
}
</script>
<style>

</style>
