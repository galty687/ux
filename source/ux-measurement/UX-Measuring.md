# 用户体验度量

产品或服务设计后，就需要对其体验进行度量，这里将介绍常见的度量方法。



## 总结性评价与形成性评价

以学生作文为例，总结性评估就是老师直接将论文给分为优良中差，并不给学生具体的分值。形成性评价，就需要给出具体的得分和扣分原因，解释为什么学生得分为良或不及格。



## 软件形成的总结性评估

使用量表对软件产品进行度量是常见的总结性评估方法。

常见量表：

- SUS
- SUMI

### SUS的应用示例



Gitlab的用研团队[使用SUS](https://about.gitlab.com/handbook/engineering/ux/performance-indicators/system-usability-scale/)来追踪用户感知到的系统可用性。



**[2022财年第一季度SUS分值](https://gitlab.com/groups/gitlab-org/-/epics/5927)**



```
68.1 (-2.7 difference from Q4FY21)

- 455 complete responses
- Margin of error: +/- 1.3
- Grade: C / Adjective: "OK"
```



有了该总分（68.1分），用研团队或管理者就可以对公司的系统有一个宏观了解，或者基于此设置部门的KPI，例如Gitlab Q1FY22比 Q4FY21 还降低了，该指标的降低，必然会引起重视要进一步分析原因。

Summative Evaluation可以从宏观层面给出一个趋势性的说明，对于细节的成因是不了解的。





## 形成性评估

和总结性评估相比，形成性评估则可以展示更多的细节，让用研人员能清楚的了解可用性高或低的原因。

形成性评估关键步骤：

1. 确定典型用户
2. 确定典型任务
3. 请典型用户完成典型任务
4. 观察和记录实验过程
5. 分析实验数据（任务完成率，完成时间、出错数、出错类型）



## 量表

### 量表与问卷的区别

量表是度量工具，可以等同于体重计或温度计。就像体重计可以量出一个人的体重，抑郁量表可以量出来一个人是否抑郁。

量表作为一个度量工具，是需要有一定的信度和效度的。就以最近的体温枪为例，这种测温方式，使用了红外线进行非接触式测温，在出厂前一定要做校验的。一个是信度，有的体温枪，每次测温度都不一样，第一次测31，第二次33，第三次有35了。类似于量表，同一个人用同一个量表，有的时候量出来也不一样，就是内部一致性不够。

还有就是效度了，就是体温枪能不能量出体温，这个时候也需要跟传统水银温度计做一个校准的，看结果是否一致。

一个量表，尤其是标准量表一定是需要精密测试，然后才能作为检测工具的，所以我们在做用户体验度量的时候，可以尽可能选用标准量表。



### 量表的常见研制过程

以[SUMI为例](https://sumi.uxp.ie/)，研究者需要确定度量目标……（待补充）

- [量表内容](https://sumi.uxp.ie/en/)
- [量表报告示例](https://sumi.uxp.ie/about/400example/index.html)

### 常见量表



| 指标              | 量表                                            | 说明                                                         |
| ----------------- | ----------------------------------------------- | ------------------------------------------------------------ |
| 系统可用性        | SUMI                                            |                                                              |
| 满意度            | QUIS                                            |                                                              |
| 体验              | [UEQ](https://www.ueq-online.org/)              |                                                              |
| Online Trust      |                                                 |                                                              |
| 正向情绪/负向情绪 | **PANAS**                                       | [更多介绍](https://positivepsychology.com/positive-and-negative-affect-schedule-panas/) |
| 用户体验          | [supr-q](https://measuringu.com/product/suprq/) |                                                              |
|                   |                                                 |                                                              |



## Tools

- [常见统计值计算器](https://measuringu.com/calc/)

## Reference

1. [The ABC’s of measuring the user experience of your product or service](https://uxplanet.org/the-abcs-of-measuring-the-user-experience-of-your-product-or-service-f079d0676d5e)
2. [Rating Scales in UX Research: Likert or Semantic Differential?](https://www.nngroup.com/articles/rating-scales/)