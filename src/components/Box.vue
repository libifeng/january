<template>
    <div>
        <h3 v-for="(item,index) in items" :key="index">
            {{item}}
        </h3>
        <h1 v-if='seen'>mac</h1>
        <h1 v-else>Air</h1>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:false,
            items:[
                'a',
                'b',
                'c'
            ]
        }
    }
}
</script>
