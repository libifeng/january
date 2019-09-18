<template>
    <div>
        <div v-for="(item,index) in items" :key="index">
            <h3>{{item}}</h3>
        </div>
        <div v-if="seen">灰色</div>
        <div v-else>绿色</div>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:false,
            items:[
                '红色',
                '白色',
                '蓝色'
            ]
        }
    }
}
</script>
