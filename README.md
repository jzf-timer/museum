|         |            |
| ------------- |:-------------:|
| 更新日期     | 2019年1月1日 |
| 产品名称      |  智能博物馆  |
| 文档状态 | 基本完成      |
| 设计者       | 江泽锋 |
| 开发者       | 江泽锋 |
| QA | 江泽锋  |


## 加值宣言
- 人体检测与属性识别
> 便于识别出残疾人身体信息，便于为四肢残疾人提供下一步的服务，如识别到身体不便时，通过轮椅出行，在到达有辅助升降工具时，将自动为此类人群开启。
- 实时语音识别
> 将导览讲解实时转换为文字，为听力障碍人士提供文字讲解服务。
- 语音合成
> 将博物馆文物的文字介绍转换为语音，为视力障碍人士提供导览服务。

## 核心价值
核心价值宣言：最小可用产品
- 实时语音转换为文字，提供文字讲解
- 文物介绍转换为语音，为听力障碍人士提供讲解服务
- 检测人员是否为躯体残疾，识别后，为其提供便利服务

## 用户痛点宣言：
- 听力障碍人士无法听到导览讲解
- 视觉障碍人士无法看到文物的文字介绍
- 躯体残疾人士往往只能人工识别，无法让便捷措施自动为这一类群体提供服务
## 人工智能概率性与用户痛点
- 目前百度实时语音识别、语音合成、人体检测与属性识别率均在99%以上。

## 需求列表与人工智能API加值
|优先级|用户需求|功能实现|api加值
| ---------- | --------- |----------- |------
| 重要 |轮椅出行不便，且便捷措施无法自动开启，需要人工配合 |百度人体检测与属性识别API | 检测人员是否为躯体残疾，识别后，为其提供便利服务
| 次重要 |听力障碍人士无法听到导览讲解|百度实时语音识别API| 实时将导览讲解语音转换为文字，提供文字讲解
| 次重要 | 视力障碍人士无法看到文物介绍|百度语音合成API| 文物介绍转换为语音，为听力障碍人士提供讲解服务

## 原型设计
[交互界面](https://gitee.com/NFUNM036/api_prjB)

[原型文档 ](http://nfunm036.gitee.io/api_prjb)

[原型文档下载](https://gitee.com/NFUNM036/api_prjB)
