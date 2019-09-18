<template>
    <div>
        <h3 v-for="(item,index) in items" :key="index">
            <h3>{{item}}</h3>
        </h3>
        <h3 v-if="seen">菊花茶</h3>
        <h3 v-else>茉莉花茶</h3>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:false,
            items:[
               '铁观音',
               '龙井',
               '毛尖茶'
            ]
        }
    }
}
</script>
<style>

</style>
