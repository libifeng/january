<template>
<div>
    <div v-for="(item,index) in items" :key="index">
        <h3>{{item}}</h3>
    </div>
    <div v-if="seen">环普</div>
    <div v-else>软件园</div>
    <div>{{name}}</div>
    </div>
</template>
<script>
export default {
    props: ['name'],
    data:function(){
        return{
            seen:false,
            items:[
                '高新',
                '曲江',
                '雁塔'
            ]
        }
    }
}
</script>
