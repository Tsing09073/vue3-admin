<template>
  <span class="title">摆烂：进厂之路就在脚下</span>
  <el-timeline>
    <el-timeline-item
      v-for="(activity, index) in activities"
      :key="index"
      :timestamp="activity.timestamp"
      :color="activity.color"
    >
      {{ activity.content }}
    </el-timeline-item>
  </el-timeline>
</template>

<script setup>
const activities = [
  {
    content:
      "进厂深造",
    timestamp: "2023-09-08",
    color: "#eebe77",
  },
  {
    content:
      "寝室摆烂",
    timestamp: "2022-05-03",
  },
  {
    content:
      "持续性摆烂",
    timestamp: "2021-11-02",
  },
  
  {
    content:
      "间接性图强",
    timestamp: "2021-10-16",
  },
  {
    content:
      "半途而废",
    timestamp: "2021-09-16",
  },
  {
    content:
      "参加比赛",
    timestamp: "2021-03-09",
  },
  {
    content:
      "灰常勤奋",
    timestamp: "2020-11-02",
  },
  {
    content:
      "初入大学''",
    timestamp: "2020-09-18",
  },
];
</script>

<style>
</style>