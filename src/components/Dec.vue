<template>
    <div>
        <div v-for="(item,index) in items" :key="index">
            <h1>{{item}}</h1>
        </div>
        <div v-if='seen'>A</div>
        <div v-else>B</div>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:false,
            items:[
                'A',
                'B',
                'C'
            ]
        }
    }
}
</script>
