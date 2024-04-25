<template>
  <div id="app">
    <router-view v-if="isRouterAlive" />
  </div>
</template>

<script>
import { mapState } from 'vuex'

export default {
  name: 'App',
  computed: {
    ...mapState({
      isRouterAlive: state => state.common.isRouterAlive
    })
  }
}
</script>

<style>
  .el-dropdown-menu{
    background-color: #111113;
    color: white;
    margin: 1px solid #2a2a2e;
}

  .el-dropdown-menu__item{
    color: white;
  }

  .mobile-menu[data-v-b68dd620]{
    background-color: #111113;
  }

  .menu-main.el-menu[data-v-925fb65c]{
    background-color: #111113;
    color: white;
  }
  .el-menu{
    background-color: #111113;
  }
  .el-menu-item{
    color: white;
  }

  #HomeCard .head-title[data-v-07312b9e]{
    color: white;
  }
  .el-message-box{
    background-color: #111113;
    color: white;
  }
  .el-button--default{
    background-color: #000;
    color:white;
  }
  .el-message-box__title{
    color: white;
  }
  .hamburger-container[data-v-0885fc76]{
    background-color: #000;
    color:white;
  }
  .left-menu.el-menu .el-submenu .el-submenu__title:hover{
    background-color: #111113;
  }
  .el-dialog__wrapper{
    background-color: #000;
    color:white;
  }
  .el-dialog__header{
    background-color: #111113;
    color:white;
  }
  .el-dialog__wrapper[data-v-9a0d807c] .el-dialog__body .tree-table .transition-box{
    background-color: #111113;
    color:white;
  }
  .el-dialog__wrapper[data-v-9a0d807c] .el-dialog__body .tree-table .mini{
    background-color: #111113;
    color:white;
  }
  .el-dialog__wrapper[data-v-2fb85988] .el-dialog__body .tree-table .right{
    background-color: #111113;
    color:white;
  }
  .dialog[data-v-6b5dcbfb] .el-dialog__footer{
    border-top: 1px solid #dee2e6;
    background-color: #111113;
    color:white;
  }
  .filter-field[data-v-243c7ff8] .el-cascader .el-input--suffix .el-input__inner {
    background-color: #111113;
    border: 1px solid #2a2a2e;
    color: white;
  }
  .el-table thead{
    color: white !important;
  }
  .el-table th, .el-table tr{
    background-color: #111113;
    color:white !important;
  }
  .el-data-table[data-v-3d11e000] .el-table td{
    background-color: #18181b;
    color:white !important;
  }
  .label-button[data-v-1e15d7b1] {
    background-color: #3c3f43;
    color:white;
    border: none !important;
  }
  .dialog-footer[data-v-6b5dcbfb] button.el-button {
    background-color: #111113;
    color:white;
  }
  .el-pagination .el-select .el-input .el-input__inner{
    background-color: #111113;
    color:white; 
    border: 1px solid #2a2a2e !important;
  }
  .el-pagination.is-background .btn-prev:disabled{
    background-color: #18181b;
    border: 1px solid #2a2a2e;
    color: white;
  }
  .el-pagination.is-background .btn-next:disabled{
    background-color: #18181b;
    border: 1px solid #2a2a2e;
    color: white;
  }
  .el-pagination.is-background .el-pager li:not(.disabled).active {    
    background-color: #18181b !important;
    border: 1px solid #fbbf24;
    color: #fbbf24 !important;
  }
  .el-card{
    border: 1px solid #2a2a2e !important;
  }
  .el-table--border{
    border: 1px solid #2a2a2e !important;
  }
  .dialog[data-v-6b5dcbfb] .el-dialog__body:has(.el-table) {
    background: #18181b !important;
  }
  .el-dialog__title {
    line-height: 24px;
    font-size: 18px;
    color: white !important;
  }
  .el-alert--success.is-light {
    background-color: #18181b !important;
    border: 1px solid #2a2a2e !important;
    color: #fbbf24 !important;
  }
  .el-alert--success.is-light .el-alert__description {
    color: #fbbf24 !important;
  }
  .el-link.el-link--info {
    color: #fbbf24 !important;
  }
</style>
