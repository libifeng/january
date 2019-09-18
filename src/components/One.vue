<template>
    <div>
        <div class="red">{{name}}</div>
        <div class="green">{{age}}</div>
        <div class="blue">{{sex}}</div>
        <div class='yello'>{{dataHeight}}-----{{heightOrLow}}</div>
        <div v-if="seen">李碧锋</div>
        <div v-else>MAC</div>
        <div v-for="(item,index) in items " :key="index">
            <h3>{{item}}</h3>
        </div>
    </div>
</template>
<script>
export default {
  props: {
    name: {
      type: String,
      required: true,
      default: 'libifeng'
    },
    age: {
        type: Number,
        required: true,
        default: 15
    },
    height: {
        type: Number,
    },
    sex:{
        type:String,
        required:true,
        default:'男'
    }
  },

  data: function() {
    return {
      seen: false,
      dataHeight: this.height,
      items: ["vue", "angular", "react"]
    };
  },
  computed: {
      heightOrLow: function () {
          return this.height >= 175 ? '你太高了' : '你太低了'
      }
  }
};
</script>
<style>
.red {
  background-color: red;
}
.green {
  background-color: green;
}
.yello{
    background-color: yellow;
}
.blue{
    background-color: blue;
}
</style>
