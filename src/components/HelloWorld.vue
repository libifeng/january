<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
   <one height="170"/>
   <two/>
   <march/>
   <may/>
    <june/>
   <july/>
   <august/>
   <mon/>
   <app/>
   <dec/>
   <sep/>
   <for/>
   <banana/>
   <fru/>
   <tree/>
   <box/>
   <baskteball/>
   <chicken/>
   <milk/>
   <project/>
   <desk/>
   <top/>
   <lenve/>  
   <try/>
   
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
import One from "./One.vue";
import Two from "./Two.vue";
import March from "./March.vue";
import May from "./May.vue";
import June from "./June.vue";
import July from "./July.vue";
import August from "./August.vue";
import Mon from "./Mon.vue";
import App from "./App.vue";
import Dec from "./Dec.vue";
import Sep from "./Sep.vue";
import For from "./For.vue";
import Banana from "./Banana.vue";
import Fru from "./Fru.vue";
import Tree from "./Tree.vue";
import Box from "./Box.vue";
import Baskteball from "./Baskteball.vue";
import Milk from "./Milk.vue";
import Chicken from "./Chicken.vue";
import Project from "./Project.vue";
import Desk from "./Desk.vue";
import Top from "./Top.vue";
import Lenve from "./Lenve.vue";
import Try from "./Try.vue";
import Com from "./Com.vue";
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  components: {
    One,
    Two,
    March,
    May,
    June,
    July,
    August,
    Mon,
    App,
    Dec,
    Sep,
    For,
    Banana,
    Fru,
    Tree,
    Box,
    Baskteball,
    Milk,
    Chicken,
    Project,
    Desk,
    Top,
    Lenve,
    Try
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
