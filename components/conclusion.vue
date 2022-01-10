<template>
  <div class="list grid grid-cols-4 gap-8">
    <div class="item py-20 text-center border-1">
      <div class="header">
        <clarity-talk-bubbles-solid class="text-[50px]" />
      </div>
      <div class="content p-8  text-[36px]">沟通</div>

    </div>

    <div class="item py-20 text-center border-1">
      <div class="header">
        <vaadin-code class="text-[50px]" />
      </div>
      <div class="content p-8  text-[36px]">注释</div>
    </div>


    <div class="item py-20 text-center border-1">
      <div class="header">
        <icon-park-outline-components class="text-[50px]" />
      </div>
      <div class="content p-8  text-[36px]">组件管理</div>
    </div>


    <div class="item py-20 text-center border-1">
      <div class="header">
        <file-icons-testcafe class="text-[50px]" />
      </div>
      <div class="content p-8  text-[36px]">测试</div>
    </div>
  </div>
</template>

<style>
  .list {
  }

  .item {
    /* border: 1px solid #eee; */
  }
</style>

<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    setup() {
      return {};
    },
  });
</script>
