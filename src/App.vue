<template>
  <div id="app">
    <Header></Header>
    <main class="page">
      <section>
        <Title>联系方式</Title>
        <ContactList></ContactList>
      </section>
      <section>
        <Title>个人信息</Title>
        <Info></Info>
      </section>
      <section>
        <Title>技术优势</Title>
        <SkillList></SkillList>
      </section>
      <section>
        <Title>开源项目</Title>
        <ProjectList></ProjectList>
      </section>
      <section>
        <Title>工作经历</Title>
        <Work></Work>
      </section>
    </main>
  </div>
</template>

<script>
import Header from "./components/Header";
import ContactList from "./components/ContactList";
import Title from "./components/Title";
import Info from "./components/Info";
import SkillList from "./components/SkillList";
import ProjectList from "./components/ProjectList";
import Work from "./components/Work";

export default {
  name: "app",
  components: {
    Header,
    ContactList,
    Title,
    Info,
    SkillList,
    ProjectList,
    Work
  }
};
</script>

<style>
.page {
  max-width: 800px;
  margin: 20px auto;
  padding: 20px;
  box-shadow: 1px 1px 8px rgba(0, 0, 0, 0.15);
  background-color: #fff;
  color: #3f1c1c;
  font-size: 14px;
}
</style>
