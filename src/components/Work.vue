<template>
  <div>
    <div class="box-wrapper">
      <div class="row">● 成都深珀数据公司 （ 2016 年 10 月 ~ 至今 ）</div>
      <div class="row">
        <p>某大数据项目 （APP）</p>
        <p>
          <span>工作内容：</span>
          <span>项目需求整理、页面设计、代码实现、接口对接及后续维护。</span>
        </p>
        <p>
          <span>项目内容：</span>
          <span>技术栈使用 Vue + Vuex + Axios + YD-UI + Cordova，项目功能涉及手机原生接口调用、加密登陆认证、用户权限划分以及大量接口数据糅合展示。</span>
        </p>
        <p>
          <span>难点攻克：</span>
          <span>展示人员信息页面，人员信息列表、人员头像是不同接口。在遍历人员列表调用人员照片时，人员照片接口耗时较久，同步调用并未达到理想效果。 最终使用 async await 异步调用照片接口，解决问题。除此之外，项目多处用到 async await 异步调用，并使用 resolve reject 函数 传参，解决回调传参等问题。</span>
        </p>
        <p>
          <span>项目结果：</span>
          <span>做项目过程中，客户要求时间较紧。我在保持高效率的同时兼顾代码质量及用户体验，最终按时交付应用。客户比较满意，目前此应用 用户数过万，客户已将应用推广至外省。</span>
        </p>
        <p>
          <span>心得感受：</span>
          <span>通过此项目，让我了解到做一个合格的系统，系统构架要设计清晰、有扩展性；代码逻辑要简洁明了、避免嵌套；页面展示将通用组件封装、便于复用；面对后期需求变化及项目维护才能游刃有余。</span>
        </p>
      </div>
      <div class="row">
        <div class="row">
          <p>公安质量基础服务 （微信小程序</p>
          <p>
            <span>工作内容：</span>
            <span>项目需求整理、页面设计、代码实现、接口对接及后续维护。</span>
          </p>
          <p>
            <span>项目内容：</span>
            <span>调用微信小程序API，实现用户登陆注册、视频播放、新闻阅读、文件下载、信息上传、信息展示等功能。</span>
          </p>
          <p>
            <span>难点攻克：</span>
            <span>微信规定了只能手动点击button获取用户信息，用户每次退出小程序后，再次进入系统会要求用户重新手动登陆。为了改善用户体验，让用户登陆过一次后系统记住用户登陆状态。 解决办法是:第一次调用微信登陆成功后，将用户信息存入数据库并分配唯一id,用wx.setStorage在小程序端存储用户id； 下次进入小程序时调用wx.getStorage获取用户id，再对接后台接口自动登陆即可，不再需要用户手动点击获取个人信息。</span>
          </p>
          <p>
            <span>项目结果：</span>
            <span>小程序已上线，页面风格简洁清新，操作流畅，持续更新迭代中。</span>
          </p>
          <p>
            <span>心得感受：</span>
            <span>各种前端框架原理都是通的，只是各自规则不一样。</span>
          </p>
        </div>
      </div>
    </div>
    <div class="box-wrapper">
      <div class="row">● 成都深珀数据公司 （ 2016 年 10 月 ~ 至今 ）</div>
      <div class="row">
        <p>某大数据项目 （APP）</p>
        <p>
          <span>工作内容：</span>
          <span>项目需求整理、页面设计、代码实现、接口对接及后续维护。</span>
        </p>
        <p>
          <span>项目内容：</span>
          <span>项目需求整理、页面设计、代码实现、接口对接及后续维护。</span>
        </p>
        <p>
          <span>难点攻克：</span>
          <span>项目需求整理、页面设计、代码实现、接口对接及后续维护。</span>
        </p>
        <p>
          <span>项目结果：</span>
          <span>项目需求整理、页面设计、代码实现、接口对接及后续维护。</span>
        </p>
        <p>
          <span>心得感受：</span>
          <span>项目需求整理、页面设计、代码实现、接口对接及后续维护。</span>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
p {
  margin: 10px 0;
}
p span:first-child {
  color: #d56386;
  min-width: 5em;
}
.row:not(:last-child) {
  border-bottom: 2px #ddd solid;
}
.row {
  padding: 10px 15px;
}
.box-wrapper {
  border: 2px #ddd solid;
  border-radius: 5px;
  background-color: #f5f5f5;
  margin-bottom: 20px;
  width: 100%;
  height: 100%;
  margin-bottom: 20px;
}
</style>
