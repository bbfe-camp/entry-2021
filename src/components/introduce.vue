<template>
  <div class="introduce">
    <h1>BBFE 前端梦工厂<sup>2021</sup></h1>
    <h2>
      面向人群
    </h2>
    <p>2022-2023年毕业的在校生，有意向做Web前端工程师，并已有初步学习。</p>
    <p>2021年5月24日至29日 能有时间参与培训（每天9:30-18:30）。</p>
    <p><img style="width:100%;max-width:500px" alt="培训日历" src="../assets/calendar.jpg" /></p>  

    <h2>项目介绍</h2>
    <p>本项目，为有志于学习前端的在校大学生，提供为期一周的免费线下前端培训。 课程表如下（可能会有微调）。</p>
    <p>培训后，学员可获得参与培训的相关证书；部分学员可与奇安信双向选择，匹配的学员可以直接获得实习Offer。</p>
    <p><img style="width:100%;max-width:500px" alt="项目课程" src="../assets/camp-plan.png"/></p>
    <h3>参与流程</h3>
    <p></p>
    <h3>温馨提示</h3>
    <p>为期一周的培训时间，如与上课时间冲突，需要提前向学校请假。</p>
    <div class="campus-graduates-button"><a href="https://www.nowcoder.com/job/12933?jobIds=54846">立即网申</a></div>
  </div>
</template>

<script>
export default {
  name: 'bbfe-camp-2021',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
sup {
  font-size: 12px;
  color:gray
}
h2 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.campus-graduates-button {
    text-align: center;
    width: 160px;
    height: 40px;
    background: #2F54EB;
    font-size: 16px;
    color: rgba(255,255,255,1);
    border-radius: 30px;
    line-height: 2.5;
    cursor: pointer;
    margin: 0 auto;
}
.campus-graduates-button > a{
    color: white;
}

</style>
