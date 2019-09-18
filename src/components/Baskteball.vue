<template>
    <div>
        <h3 v-for="(item,index) in items" :key="index">
            {{item}}
        </h3>
        <h1 v-if="seen">课桌</h1>
        <h1 v-else>书本</h1>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:true,
            items:[
                '肉',
                '牛奶',
                '鸡蛋'
            ]
        }
    }
}
</script>
