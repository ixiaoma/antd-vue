<template>
  <a-card>
    <div class="top-tab">
      <div class="extra-content">
        <div class="stat-item">
          <h1 style="margin-top: 16px;font-weight:bold">全部</h1>
        </div>
      </div>
      <div class="extra-content">
        <div class="stat-item">
          <a-statistic title="审批中" :value="56" />
        </div>
        <div class="stat-item">
          <a-statistic title="员工" :value="8" />
        </div>
        <div class="stat-item">
          <a-statistic title="考勤" :value="2223" />
        </div>
      </div>
      <div class="extra-content">
        <div class="stat-item">
          <a-statistic title="本月通过" :value="56" />
        </div>
        <div class="stat-item">
          <a-statistic title="本月驳回" :value="8" />
        </div>
      </div>
    </div>
  </a-card>
</template>

<script>

export default {
  name: 'Workplace',
  data () {
    return {

    }
  }
}
</script>

<style lang="less" scoped>
  @import "./Workplace.less";
</style>
