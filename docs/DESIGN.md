# 设计

## 项目管理
项目名称, (测试人员, 开发人员), 报警邮箱, 钉钉地址, 项目描述

## 测试用例管理
### 输入 
用例名称, 所属项目, 接口级别, 通用配置

接口信息: url, Method, Param, Headers, Variable, Extract, Validators
每个用例可以含有多个接口, 用例内串行

### 结果
显示最近一次接口验证结果
点击详情时, 展示接口的历史结果

## 定时任务管理
任务名称, 执行时间, 项目名称, 接口级别(只执行此级别或以上的), 备注信息

### 列表
展示定时任务的结果 + 运行时间 + 结果 + 
可以开始, 停止, 查看测试报告

### 定时测试任务
按照定时任务执行的接口维度进行查看

## 统计与报告
按照项目维度筛选报告

## 配置管理
为指定 URL 设置统一 Header 和 变量绑定(预设变量) 