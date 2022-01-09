<template>
  <vue-horizontal-timeline :items="items" />
</template>



<script>


import { defineComponent } from "vue";
import VueHorizontalTimeline from "vue-horizontal-timeline";

export default defineComponent({
  components:{VueHorizontalTimeline},
  setup(){


   const items = [
     {
       title:'v1',
       content:'菜单类型'
     }

   ]


   return {
     items
   }
  }
})


</script>
