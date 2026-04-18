---
layout: archive
title: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育背景
======
* 认知科学博士，东南科技学院，2023
* 计算认知系统硕士，东南科技学院，2020
* 软件工程学士，东华理工大学，2018

工作经历
======
* 2024–至今：研究科学家
  * 东南科技学院
  * 领导人机协同、交互可视化和科研可重复性项目。
  * 导师：赵明教授

* 2021–2023：研究助理
  * 东南科技学院
  * 开发认知建模和可视化仪表盘的机器学习管道。
  * 导师：陈瑞博士

* 2020–2021：助教
  * 东南科技学院
  * 支持数据科学和人机交互本科课程。
  * 协调员：刘霞教授
  
技能
======
* 人机交互设计
* 数据可视化和探索性分析
* Python、R、JavaScript
* 机器学习和统计建模
* 开源科研工具和可重复性

出版物
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
演讲
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
教学
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
服务与领导
======
* 国际人机交互会议评审员
* 贡献开源工具以提高科研可重复性