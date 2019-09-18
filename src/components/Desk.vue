<template>
    <div>
        <h3 v-for="(item,index) in items" :key="index">
              <h3>{{item}}</h3>
        </h3>
        <h2 v-if="seen">A</h2>
        <h2 v-else>B</h2>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:false,
            items:[
             '西游记',
             '水浒传',
             '三国演义',
             '红楼梦'
            ]
        }
    }
}
</script>
<style>

</style>
