<template>
  <div class="header">
    <div class="header-box">
      <img src="../assets/avatar.jpg" alt="我的头像">
    </div>
    <div class="name">
      <p class="my-id">Mmmm</p>
    </div>
    <ul class="my-sort">
      <li v-for="(item, index) in sort" :key="index">
        <a href="#">{{ item.name }}</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      sort: [{ name: "简历" }, { name: "点滴" }, { name: "留言" }]
    };
  }
};
</script>

<style>
.header {
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: center;
}
.header .header-box {
  flex-basis: 100%;
  text-align: center;
}
.header .header-box img {
  max-width: 120px;
  border-radius: 50%;
}
.header .name {
  flex-basis: 100%;
  text-align: center;
}
.header .name .my-id {
  display: inline-block;
  padding: 0 0.5em;
  line-height: 2em;
  letter-spacing: 0.1em;
  margin: 2em 0;
  font-size: 1.3em;
  color: #948c76;
  background: #f7f3ee;
}
.header .my-sort li {
  display: inline-block;
  margin-bottom: 2em;
}
.header .my-sort a {
  font-size: 0.8em;
  margin: 0 1em;
  display: inline-block;
  color: #948c76;
}
</style>
