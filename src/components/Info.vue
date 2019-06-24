<template>
  <div class="box-wrapper">
    <div class="row-wrapper">
      <div class="row-1">
        <div class="col-1">● 姜利民 | 男 | 1996</div>
        <div class="col-2">● 湖南城市学院 | 土木工程 | 本科</div>
        <div class="col-3">● 前端开发 | 2 年工作经验</div>
      </div>
    </div>
    <div class="row-2">
      ● Github：
      <a href="#">https://github.com/Mmmmmr</a>
    </div>
    <div class="row-3">
      ● 技术博客：
      <a href="#">https://www.jianshu.com/u/e898eaf465d5</a>
    </div>
    <div></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
a:hover {
  text-decoration: underline;
}
.row-3 {
  padding: 10px 15px;
}
.row-2 {
  padding: 10px 15px;
  border-bottom: 2px #ddd solid;
}
.row-1 .col-3 {
  flex: 0 0 33.33333%;
  max-width: 33.33333%;
  height: 100%;
  position: relative;
  width: 100%;
  height: 100%;
}
.row-1 .col-3:before {
  content: "";
  position: absolute;
  top: -12px;
  left: -15px;
  width: 1px;
  height: 45px;
  border-left: 2px solid #ddd !important;
}

.row-1 .col-2:before {
  content: "";
  position: absolute;
  top: -12px;
  left: -15px;
  width: 1px;
  height: 45px;
  border-left: 2px solid #ddd !important;
}
.row-1 .col-2 {
  position: relative;
  flex: 0 0 33.33333%;
  max-width: 33.33333%;
  height: 100%;
  width: 100%;
  height: 100%;
}
.row-1 .col-1 {
  flex: 0 0 33.33333%;
  max-width: 33.33333%;
  height: 100%;
  width: 100%;
  height: 100%;
}
.row-1 {
  display: flex;
  flex-wrap: wrap;
  width: 100%;
  height: 100%;
}
.row-wrapper {
  padding: 10px 15px;
  width: 100%;
  height: 100%;
  border-bottom: 2px #ddd solid;
}
.box-wrapper {
  border: 2px #ddd solid;
  border-radius: 5px;
  background-color: #f5f5f5;
  margin-bottom: 20px;
  width: 100%;
  height: 100%;
}
</style>
