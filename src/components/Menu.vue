<template>
 <el-menu default-active="2" class="el-menu-vertical-demo">
  <el-submenu index="1">
   <template slot="title">导航一</template>
   <el-submenu index="1-1">
    <template slot="title">选项1-1</template>
    <el-menu-item index="1-1-1">选项1-1-1</el-menu-item>
    <el-menu-item index="1-1-2">选项1-1-2</el-menu-item>
   </el-submenu>
   <el-menu-item index="1-2">选项1-2</el-menu-item>
  </el-submenu>
  <el-menu-item index="2">导航二</el-menu-item>
  <el-menu-item index="3">导航三</el-menu-item>
  <el-menu-item index="4">导航四</el-menu-item>
 </el-menu>
</template>
