<template>
  <div class="container">
  <div class="list">
    <strong>销售中:</strong>
    <div>
      <span>1.</span>
      <strong>iphone12</strong>
      <span>2.</span>
      <strong>huawei</strong>
    </div>
  </div>
</div>
</template>

<script>
import CheckEditor from './components/CheckEditor.vue';
const defaultSells = [
  {
    id: 1,
    sell: true,
    title: "iphone12",
  },
  { id: 2, sell: false, title: "xiaomi" },
  { id: 3, sell: true, title: "huawei" },
  { id: 4, sell: true, title: "vivo" },
];

export default {
  components:{
    CheckEditor
  }
};
</script>

<style scoped>
  .container {
    margin-top: 50px;
    width: 880px;
    margin: 50px auto;
  }
  .list {
    display: flex;
    margin: 1em 0;
    align-items: center;
  }
  strong {
    margin-right: 1em;
  }
</style>
