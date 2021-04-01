<template>
  <div class="hello">
    <div class="heard">
      <div class="title">
        <img src="../assets/logo.png">
      </div>
      <div class="middle">
        <div class="name">A-2021031600</div>
        <div class="table">
          <div>容器：【5】20L白胶瓶</div>
          <div>容器：【5】20L白胶瓶</div>
          <div>容器：【5】20L白胶瓶</div>
          <div>容器：【5】20L白胶瓶</div>
          <div>容器：【5】20L白胶瓶</div>
        </div>
        <div class="table">
          <div>容器：【5】20L白胶瓶</div>
          <div>容器：【5】20L白胶瓶</div>
          <div>容器：【5】20L白胶瓶</div>
          <div>容器：【5】20L白胶瓶</div>
          <div></div>
        </div>
      </div>

      <div class="state">
        <div class="grey">状态</div>
        <div class="green">库中</div>
      </div>
    </div>
    <div class="title2">生命周期时间轴</div>
    <div class="ivu-steps ivu-steps-horizontal">
      <div class="ivu-steps-item ivu-steps-status-finish">
        <div class="ivu-steps-tail"><i></i></div>
        <div class="ivu-steps-head">
          <div class="ivu-steps-head-inner"></div>
        </div>
        <div class="ivu-steps-main">
          <div class="ivu-steps-title">采样</div>
          <div class="ivu-steps-content">
            <div>记录人员：</div>
            <div>记录日期：</div>
            <div>记录编号：</div>
            <div>检测方法：</div>
            <div>责任单位：</div>
            <div>检测地点：</div>
            <div>超标级别：</div>
            <div>不合格项：</div>
          </div>
        </div>
      </div>
      <div class="ivu-steps-item ivu-steps-status-finish">
        <div class="ivu-steps-tail"><i></i></div>
        <div class="ivu-steps-head">
          <div class="ivu-steps-head-inner"><span class="ivu-steps-icon ivu-icon ivu-icon-ios-checkmark"></span></div>
        </div>
        <div class="ivu-steps-main">
          <div class="ivu-steps-title">送样</div>
          <div class="ivu-steps-content">
            <div class="ivu-steps-content">
              <div>申请人员：</div>
              <div>申请日期：</div>
              <div>申请编号：</div>
              <div>送样人员：</div>
              <div>期望复检送样日期：</div>
              <div>样本数量：</div>
            </div>
          </div>
        </div>
      </div>
      <div class="ivu-steps-item ivu-steps-status-finish">
        <div class="ivu-steps-tail"><i></i></div>
        <div class="ivu-steps-head">
          <div class="ivu-steps-head-inner"><span class="ivu-steps-icon ivu-icon ivu-icon-ios-checkmark"></span></div>
        </div>
        <div class="ivu-steps-main">
          <div class="ivu-steps-title">接样</div>
          <div class="ivu-steps-content">
            <div>回复人员：</div>
            <div>回复日期：</div>
            <div>检测人员：</div>
            <div>检测日期：</div>
            <div>期望复检送样日期：</div>
            <div>样本数量：</div>
          </div>
        </div>
      </div>
      <div class="ivu-steps-item ivu-steps-status-finish">
        <div class="ivu-steps-tail"><i></i></div>
        <div class="ivu-steps-head">
          <div class="ivu-steps-head-inner"><span class="ivu-steps-icon ivu-icon ivu-icon-ios-checkmark"></span></div>
        </div>
        <div class="ivu-steps-main">
          <div class="ivu-steps-title">分发</div>
          <div class="ivu-steps-content">
            <div>通知人员：</div>
            <div>通知日期：</div>
            <div>不合格事实：</div>
          </div>
        </div>
      </div>
      <div class="ivu-steps-item ivu-steps-status-finish">
        <div class="ivu-steps-tail"><i></i></div>
        <div class="ivu-steps-head">
          <div class="ivu-steps-head-inner"><span class="ivu-steps-icon ivu-icon ivu-icon-ios-checkmark"></span></div>
        </div>
        <div class="ivu-steps-main">
          <div class="ivu-steps-title">领用</div>
          <div class="ivu-steps-content">
            <div>纠正人员：</div>
            <div>纠正日期：</div>
            <div>原因分析：</div>
            <div>纠正措施及实施：</div>
          </div>
        </div>
      </div>
      <div class="ivu-steps-item ivu-steps-status-finish">
        <div class="ivu-steps-tail"><i></i></div>
        <div class="ivu-steps-head">
          <div class="ivu-steps-head-inner"><span class="ivu-steps-icon ivu-icon ivu-icon-ios-checkmark"></span></div>
        </div>
        <div class="ivu-steps-main">
          <div class="ivu-steps-title">销毁</div>
          <div class="ivu-steps-content">
            <div>纠正人员：</div>
            <div>纠正日期：</div>
            <div>原因分析：</div>
            <div>纠正措施及实施：</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {

      }
    }
  }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .heard {
    padding: 30px;
    display: flex;
    margin-bottom: 30px;
    border: 1px solid #ccc;
  }
  .title img{
    width:50px;
    margin-right: 20px;
  }

  .name {
    font-size: 20px;
    font-weight: 600;
    text-align: left;
  }

  .table {
    display: flex;
  }
  .middle{
    flex: 3;
  }

  .table div {
    flex: 1;
    text-align: left;
  }
  .grey{
    color: #333;
  }
  .green{
    color: #19be6b;
    font-size: 30px;
  }
  .state{
    padding: 0 10px;
    border-left: 1px solid #ccc;
  }
  .title2{
    text-align: left;
    font-size: 18px;
    font-weight: 600;
    margin-bottom: 30px;
    padding: 0 30px;
  }
</style>
