<template>
<div class="zhiding">
  <div class="container">
    

    <div class="card border-primary mb-3" style="max-width: 100%;">
        <div class="card-header">
          <div class="title">
          <h1>亚洲飞人苏炳添</h1>
        </div>
     </div>
        <div class="card-body ">
            <div class="row">
      <div class="col-md-6"><img src="https://gss2.bdstatic.com/9fo3dSag_xI4khGkpoWK1HF6hhy/baike/c0%3Dbaike80%2C5%2C5%2C80%2C26/sign=c70c2f319cef76c6c4dff379fc7f969f/faedab64034f78f0d5e767e375310a55b3191c35.jpg" alt=""></div>
      <div class="col-md-6"> <div class="personal">
      <!-- <md-step id="second" md-label="早年经历"> -->
      <p> 初中时期，苏炳添与短跑结缘，上初二时，他为了逃避留校补课而参加学校的田径队。2004年11月，15岁的苏炳添第一次参加了正规的比赛——中山市中学生田径比赛。他自发参加比赛，结果他在100米的比赛上以11秒72的成绩（秒表计时）拿到第一名。  之后，中山市体校田径教师宁德宝把苏炳添招进了麾下。12月，苏炳添被中山市体育运动学校录取，开始接受系统的专业化训练。训练了三个月后，苏炳添第一次参加省里面的邀请赛，100米和200米都进入了决赛，其中100米的成绩达到了电计时11秒7。 2005年11月，苏炳添参加广东省田径公开赛以7秒31获得60米比赛第三名，以11秒34获得100米第三名。  2006年，在香港对抗赛上，苏炳添收获了100米和200米比赛的冠军，在100米跑出10秒59、200米跑出的21秒多的成绩都接近了健将级运动员的水平。9月，苏炳添参加广东省田径邀请赛以10秒66夺得100米冠军。同年12月，苏炳添被招进广东省田径队进行更高级别的训练。  </p>
      <!-- </md-step> -->
    </div></div>
    </div>
      </div>
</div>
    
    <!-- <span class="md-title">Headline</span> -->
  
    
    
   
    <div class="content">
      <md-steppers>
        <md-step id="first" md-label="个人最佳" >
          <div class="table">
            <table class="table">
              <thead>
                <tr>
                  <th>年份/年.月.日</th>
                  <th>成绩/秒</th>
                  <th>风速</th>
                  <th>创造地</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>2015.05.30</td>
                  <td>9.99（全国纪录）</td>
                  <td>+1.5</td>
                  <td>美国尤金</td>
                </tr>
                <tr>
                  <td>2015.08.23</td>
                  <td>9.99（全国纪录）</td>
                  <td>-0.4</td>
                  <td>中国北京</td>
                </tr>
                <tr>
                  <td>2018.0623</td>
                  <td>9.91（亚洲纪录）</td>
                  <td>0.2</td>
                  <td>西班牙马德里</td>
                </tr>
              </tbody>
            </table>
          </div>
        </md-step>
        <md-step id="third" md-label="运动经历"  @click="showDialog = true">
            
    <md-dialog :md-active.sync="showDialog">
      <md-dialog-title>Preferences</md-dialog-title>
      
      <md-tabs md-dynamic-height  >
        <md-tab md-label="初出茅庐">
          <p>2007年，苏炳添进入广东省队开始成为一名专业运动员，并师从中国田径第一个全国百米纪录（电子计时）创造者袁国强教练。  当时他虽未成年但参加了成人组的比赛，并在湖北武汉举行的第六届全国城市运动会上获得了100米第五名的好成绩。</p>
        </md-tab>

        <md-tab md-label="崭露头角">
          <p>2008年，在全国室内田径锦标赛上，苏炳添收获了男子60米的金牌。  并先后获全国田径锦标赛男子4×100米接力、全国田径冠军赛暨系列赛男子4×100米接力两块金牌。  </p>
        </md-tab>

        <md-tab md-label="称霸亚洲">
          <p>2010年，苏炳添受伤病困扰，上半年基本上没有比赛，主要以养伤和力量练习为主。   在年底的第十六届广州亚运会男子4×100米接力决赛中，苏炳添与陆斌、梁嘉鸿、劳义组成的中国队以38秒78夺得冠军，并刷新全国纪录和亚运会纪录，继1990年北京亚运会摘金后，中国接力队时隔20年再度封王亚洲。</p>
        </md-tab>
      </md-tabs>

      <md-dialog-actions>
        <md-button class="md-primary" @click="showDialog = false">Close</md-button>
      
      </md-dialog-actions>
    </md-dialog>
          
        </md-step>
      </md-steppers>
    </div>
    
  </div>
</div>
</template>

<script>


export default {

   data: () => ({
      showDialog: false
    }),

  components:{

  }
};
</script>




<style scoped lang="scss">

content2 {
  position: relative;
    /* overflow-y: scroll; */
}
.content2{
  
  height: 200px;
  overflow: auto;
}
.live{
  height: 200px;
}
img {
    position: relative;
    /* left: 40px; */
}
.row{
  position: relative;
  /* top: -18px; */
}
.title {
    text-align: center;
    position: relative;
}
.personal {
    position: relative;
    // top: -300px;


}
.content {
    position: relative;
    // top: -250px;
}
.table {
    width: 100%;
    height: 400px;
    /* background-color: aquamarine */
}
 .md-dialog {
    max-width: 768px;
  }
  .comt{
      background: white
  }
</style>
