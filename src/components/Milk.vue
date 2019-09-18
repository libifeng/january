<template>
<div>
    <div v-for="(item,index) in items" :key='index'>
        {{item}}
    </div>
    <h2 v-if='seen'>前端</h2>
    <h2 v-else>后台</h2>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:false,
            items:[
                'WEB',
                'JAVA',
                'JS'
            ]
        }
    }
}
</script>
