<template>
    <div>
        <div v-for="(item,index) in items" :key='index'>
            <h2>{{item}}</h2>
        </div>
        <div v-if="been">黑</div>
        <div v-else>白</div>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            been:true,
            items:[
                '月亮',
                '星星',
                '太阳'
            ]
        }
    }
}
</script>
