<template>
    <div>
        <div v-for="(item,index) in items" :key='index'>
            <h3>{{item}}</h3>
        </div>
        <div v-if='seen'>西安</div>
        <div v-else>上海</div>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:false,
            items:[
                'ipad',
                'iphone',
                'mac'
            ]
           
        }
       
    },
}
</script>
