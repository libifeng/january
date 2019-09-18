<template>
    <div>
        <div v-for="(item,index) in items" :key='index'>
            <h3>{{item}}</h3>
        </div>
        <div v-if="seen">神七</div>
        <div v-else>神九</div>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:true,
            items:[
                '汽车',
                '飞机',
                '轮船'
            ]
        }
    }
}
</script>
