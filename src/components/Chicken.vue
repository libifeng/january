<template>
    <div>
        <h2 v-for="(item,index) in items" :key='index'>
            <h2>{{item}}</h2>
        </h2>
        <h3 v-if="seen">你可以看到我</h3>
        <h3 v-else>你看不见我</h3>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            seen:true,
            items:[
                '鼠标',
                '键盘',
                '数据线'
            ]
        }
    }
}
</script>
