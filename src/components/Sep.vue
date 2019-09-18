<template>
    <div>
        <div v-for="(item,index) in items" :key='index'>
            <h1>{{item}}</h1>
        </div>
        <h3 v-if="seen">李碧锋</h3>
        <h3 v-else>雁塔区</h3>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:false,
            items:[
                '早餐',
                '午餐',
                '晚餐'
            ]
        }
    }
}
</script>
