<template>

   <p class="text-[#5d8392]">业主端功能模块</p>

    <radial-progress-vue3
    :percent="25"
    :width="200"
    :stroke-width="10"
    innerStrokeColor="#eee"
    stroke-color="#5d8392"
    fill-color="white"
    textColor="#5d8392"
    roundedStroke
    font-size="30"
  ></radial-progress-vue3>

</template>

<script>
  import { defineComponent } from "vue";

  import radialProgressVue3 from "radial-progress-vue3";

  export default defineComponent({
    components: { radialProgressVue3 },

    setup() {
      return {};
    },
  });
</script>
