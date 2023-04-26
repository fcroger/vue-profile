<script setup>

</script>

<template>
  <div class="basic">
    <div class="left">
      <div class="name">王志强 RogerWang</div>
      <div class="job">讲师 Lecturer</div>
      <div class="university">北京工业大学 BJUT</div>
      <div class="item">Email: wzqcg@bjut.edu.cn</div>
      <div class="item">Wechat: t07297</div>
    </div>
    <div class="right">
      <img src="./assets/rw.jpg" />
    </div>
  </div>
  <div class="section">
    <div class="title">个人简介Profile</div>
    <div class="content">
      <p>幼时柔弱，心地清纯，</p>
      <p>青涩求学，无知无瑕。</p>
      <p>弱冠徘徊，浮沉不定，</p>
      <p>三十觉悟，奋发劳苦。</p>
      <p>四十不惑，孜孜不倦，</p>
      <p>手握经卷，守正求新。</p>
      <p>不息为体，日新为道，</p>
      <p>锲而不舍，精益求精。</p>
    </div>
  </div>
  <div class="section">
    <div class="title">教育简历Past Education</div>
    <div class="content">
      <P>1994.9至1998.7 天津纺织工学院 机械设计与制造 本科</P>
      <P>2005.9至2008.7 北京工业大学 计算机应用技术 硕士</P>
      <P>2013.9至2019.7 北京工业大学 软件工程 因故未完成学业未取得博士学位</P>
    </div>
  </div>
  <div class="section">
    <div class="title">工作履历Work Experience</div>
    <div class="content">
      <p>1998.7至2008.6 先后在家具制造、游戏制作、数字电影、展览设计等公司供职</p>
      <p>2008.7至今 北京工业大学 教师</p>
    </div>
  </div>
  <div class="section">
    <div class="title">技能Skillset</div>
    <div class="content">
      ...
    </div>
  </div>
</template>

<style scoped>
.basic{
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  margin-bottom: 20px;
}
.basic .left{
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
}

.basic .left .name{
  font-family: "Simonetta", "Trebuchet MS", Arial, sans-serif;
  color: #454545;
  font-size: 2.1em;
  margin-bottom: 6px;
}
.basic .left .job{
  font-family: "Trebuchet MS", Verdana, Arial, sans-serif;
  color: #777;
  font-weight: normal;
  font-size: 0.9em;
  margin-bottom: 10px;
}
.basic .left .university{
  font-family: "Balthazar", "Droid Serif", serif;
  color: #656565;
  font-size: 0.9em;
  display: block;
  margin-bottom: 6px;
}
.basic .left .item {
  font-family: "Balthazar", "Droid Serif", serif;
}
.basic .right img{
  width: 12em;
  height: auto;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
  -webkit-box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  -moz-box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 5px;
}
.section {
  margin-bottom: 20px;
}
.section .title{
  font-family: "Simonetta", "Trebuchet MS", Arial, sans-serif;
    color: #484848;
    font-size: 1.5em;
    margin-bottom: 10px;
    text-decoration: underline;
}
.section .content p{
  font-family: "Balthazar", "Droid Serif", serif;
  color: #565656;
  font-size: 1.1em;
  line-height: 1.1em;
  margin-bottom: 15px;
  padding-left: 35px;
}

</style>
