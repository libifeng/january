<template>
    <div>
        <div v-for="(item,index) in items" :key="index">
            <h4>{{item}}</h4>
        </div>
       <div v-if="been">南顺</div>
       <div v-else>新池</div>
    </div>
</template>
<script>
export default {
    data: function(){
       return{
           been:true,
         items:[
             '北京',
             '天津',
             '上海'
         ]
       }
    },
}
</script>
<style>

</style>

