<template>
    <div>
        <h3 v-for="(item,index) in items" :key='index'>
            {{item}}
        </h3>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            items:[
              '国庆',
              '中秋',
              '端午'
            ]
        }
    }
}
</script>
