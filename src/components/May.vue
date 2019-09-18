<template>
    <div>
        <div v-for="(item,index) in items" :key='index'>
            <h3>{{item}}</h3>
        </div>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
            items:[
                'Java',
                'Web',
                'CDN'
            ]
        }
    },
}
</script>
