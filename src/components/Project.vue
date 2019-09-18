<template>
    <div>
        <h3 v-for="(item,index) in items" :key='index'>
            <h3>{{item}}</h3>
        </h3>
        <h2 v-if="seen">可以看到</h2>
        <h2 v-else>看不到</h2>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:false,
            items:[
               '省城',
               '县城',
               '城镇'
            ]
        }
    }
}
</script>
