<template>
  <div>
    <h1 class="title">
      <slot></slot>
    </h1>
  </div>
</template>

<script>
export default {};
</script>

<style>
.title {
  font-weight: 900 !important;
  font-size: 18px !important;
  margin-bottom: 20px !important;
  margin-left: -20px;
  padding-left: 15px;
  border-left: 5px solid #e38fa9;
  text-align: left;
}
</style>
