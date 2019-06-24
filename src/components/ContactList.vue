<template>
  <div>
    <div class="box-wrapper">
      <div class="row">
        <div class="col-1">● 手机：18975945550</div>
        <div class="col-3">● QQ：82474481</div>
        <div class="col-2">● Email：jianglimin999@gmail.com</div>
      </div>
    </div>
  </div>
</template>

<script>
import Title from "./Title";
export default {
  components: {
    Title
  }
};
</script>

<style scoped>
.row .col-3 {
  flex: 0 0 33.33333%;
  max-width: 33.33333%;
  height: 100%;
  position: relative;
  width: 100%;
  height: 100%;
}
.row .col-3:before {
  content: "";
  position: absolute;
  top: -12px;
  left: -15px;
  width: 1px;
  height: 45px;
  border-left: 2px solid #ddd !important;
}

.row .col-2:before {
  content: "";
  position: absolute;
  top: -12px;
  left: -15px;
  width: 1px;
  height: 45px;
  border-left: 2px solid #ddd !important;
}
.row .col-2 {
  position: relative;
  flex: 0 0 33.33333%;
  max-width: 33.33333%;
  height: 100%;
  width: 100%;
  height: 100%;
}
.row .col-1 {
  flex: 0 0 33.33333%;
  max-width: 33.33333%;
  height: 100%;
  width: 100%;
  height: 100%;
}
.row {
  display: flex;
  flex-wrap: wrap;
  width: 100%;
  height: 100%;
}
.box-wrapper {
  border: 2px #ddd solid;
  border-radius: 5px;
  background-color: #f5f5f5;
  padding: 10px 15px;
  margin-bottom: 20px;
  width: 100%;
  height: 100%;
}
</style>
