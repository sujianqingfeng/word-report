---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
title: 年终述职
---

# 年终述职

述职人：贺聂双

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<!--
备注
-->

---
layout: two-cols
---

<div class="directory flex flex-col justify-center items-center h-full text-[70px] ">

<span class="leading-[70px]">目</span>
<br>
<br>
<span class="leading-[70px]">录</span>

</div>


::right::


<div class="flex flex-col justify-center items-start h-full text-[29px]">

- 📝 **工作说明**
- 🎨 **进步**
- 🧑‍💻 **经验总结**
- 🤹 **明年计划**


</div>



<style>

  .directory{
    color: var(--slidev-theme-primary);
  }

</style>

<!--

-->

---
preload: false
---

# 工作说明

项目(江湾荟)

<div class="flex flex-row">
<div class="flex-1">
<owner-chart />
</div>
<div class="flex-1">


### 物业缴费
<br>

- 欠缴
- 预缴
- 缴费记录

<br>
<br>

### 房屋租售
<br>

- 二手房、租房列表
- 房源详情
- 楼盘详情



</div>
</div>

---
preload: false
---

# 工作说明

项目(江湾荟)


<div class="flex flex-row">
<div class="flex-1">
<merchant-chart />
</div>
<div class="flex-1">


### 店铺管理

<br>

- 添加、编辑
- 详情
- 商家入驻

<br>

### 商品管理

<br>

- 商品、折扣、代金券的发布与修改
- 商品、折扣、代金券的详情

<br>

### 账户
<br>

- 现金、豌豆提现 
- 提现记录
- 银行卡管理



</div>
</div>

<!--

-->

---

# 工作说明

产品后台管理


<div class="flex flex-row">

<div class="flex-1">

### V1

<br>

#### 基础配置

- 菜单类型
- 空间类型
- 角色类型

<br>

#### 系统管理

- 员工管理
- 角色管理
- 组织架构

<br>

#### 租户管理

- SAAS创建集团 （版本管理）
- 集团创建公司（公司管理）

</div>



<div class="flex-1" v-click>

### V2

<br>

#### 费用管理

- 费用标准
- 应收账单
- 收款记录
- 作废账单

<br>

#### 权限管理

</div>


<div class="flex-1" v-click>

### V3

<br>

#### 应用管理

<br>

#### 应用中心

- Banner
- 活动
- 内容中心
- 通知公共
- 保修工单

<br>

#### 小程序端

- 接口配置
- 首页配置
- 服务配置
- 授权项目

</div>


</div>


---

# 进步

从工作上来说

- 对公司现有业务的熟悉，以及了解未来产品的规划
- 熟悉 UniApp 开发流程
- Vue3 Hook 更加熟练
- Git 提交规范

- 第一次当面试官

  - 心理素质有所提升
  - 会去了解一些面试题，对自己而言也是一种复习
  - 刚开始与候选人沟通时间把控不好，学会取舍

<!--
  - 老实说，刚开始有些紧张，有些准备的题都忘了，心理素质有所提升
-->

---

# 进步

作为一个技术人员，沉淀自己，总结自我真的是一件很必要的事情

- 看书

  - <<红宝书>> 看了 1/3
  - <<重构>> 看了 1/3
  - <<代码整洁之道>> 买了还没有看

- [Mini-Vue3](https://github.com/sujianqingfeng/my-mini-vue)，一行一行代码去敲，去理解 Vue3 里面的一些实现

- 尝试 Vue3 写一个[模板](https://github.com/sujianqingfeng/vue-admin-new)，为后续 SAAS 升级提供支撑
<br>
<br>

<v-click>

![Local Image](/github.com_sujianqingfeng.png)

</v-click>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/sujianqingfeng" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>


<!-- 之所以有这个打算，是因为在开发 SAAS 的过程中，开发体验有时候比较难受 -->



---

# 经验总结


- 沟通的重要性

- 代码注释

- 组件的管理

- 代码测试

<!-- - 开发过程中，沟通很重要，开发前充分确认需求。要考虑到代码的可扩展行，当需求变更的时候，能够比较好的兼容情况

- 代码注释不多，虽然自己写着很爽，但是也要考虑他人。后续会把注释慢慢写上


- 虽然抽取了一些组件，但是现在分开的，且不是同步的，不能很好管理。等项目稳定下来，会考虑把一些积累的组件抽取成公共库，提升开发效率

- 代码测试这一块不太注重，有时候会出现修改一个需求或者修复一个bug，其他地方也出现了 bug。后续考虑写一些测试，提交代码的时候跑一下

 -->




---

# 明年计划

- 持续迭代产品，考虑升级 Vue3
- 引入代码测试
- 看完买的书籍
- 重新梳理 Js 基础
- Vue3 深入学习
- Neovim 的尝试


---
layout: cover
--- 

# 谢谢大家

为物业开源节流，提升业主服务质量
