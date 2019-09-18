<template>
    <div>
        <div v-for="(item,index) in items" :key='index'>
            <h2>{{item}}</h2>
        </div>
        <div v-if='seen'>天</div>
        <div v-else>地</div>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:true,
            items:[
                '水果',
                '食物',
                '饮料'
            ]
        }
    }
}
</script>
