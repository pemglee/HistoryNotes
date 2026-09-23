# 历史学习笔记

## 朝代

### 唐

### 辽 宋 夏 金 元

#### 帝王、官吏等

#### 事件

### 明

#### 帝王、官吏等

```mermaid
gantt
dateFormat YYYY-MM-DD
title 明朝人物

section 明朝帝王

section 明朝人物

section 外藩

```

##### 明太祖 朱元璋

##### 明惠帝 朱允炆

##### 明太宗/成祖 朱棣

##### 明仁宗 朱高炽

##### 明宣宗 朱瞻基

##### 明英宗 朱祁镇

##### 明代宗 朱祁钰

#### 事件

### 清

## 人物

### 李

#### 李牧

### 王

### 曾

#### 曾巩

### 张

#### 张之洞

### 章

#### 章惇

## 心得


--- --- ---
甘特图示例
```mermaid
gantt
dateFormat YYYY-MM-DD
title 使用mermaid语言定制甘特图

section 任务1
已完成的任务 :done, des1, 2014-01-06,2014-01-08
正在进行的任务 :active, des2, 2014-01-09, 3d
待完成任务1 : des3, after des2, 5d
待完成任务2 : des4, after des3, 5d

section 关键任务
已完成的关键任务 :crit, done, 2014-01-06,24h
实现Json文件的解析 :crit, done, after des1, 2d
为Json文件解析器创建测试用例 :crit, active, 3d
关键路径上的计划任务 :crit, 5d
为渲染器创建测试用 :2d
添加到Mermaid :1d
```