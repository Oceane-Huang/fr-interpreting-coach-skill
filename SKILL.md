---
name: fr-interpreting-coach
description: Prepare French-to-Chinese interpreting practice from audio or transcripts, produce oral-style reference translations and focused learning notes, or build and improve a local interpreting practice app using these teaching requirements.
---

# 法汉口译自主训练

将法语素材转化为可反复练习的法译汉任务。默认用中文交流。先判断用户需要教学材料、处理现有素材，还是开发／部署应用，只完成所请求的部分。

## 核心约定

- “源语”指用户音频的法语自动转写及其明确校订版本；不是参考译文，也不是学习者中文录音。保留原始识别结果与校订结果的区别。
- 参考译文只依据对应段法语源语生成；中文学生转写不作为翻译来源。上下文只用于消歧，不提前翻译下一段信息。听不清、缺上下文、专名不确定时标明，不补造。
- 不把演示文本或模型示例当作实际音频转写。无法访问素材或没有识别工具时明确说明当前可完成的范围。
- 用户偏好的学习流程是：译前准备 → 分段播放／暂停 → 中文口译录音 → 按需查看参考 → 重译比较 → 导出可编辑报告。默认不做自动评分或自动优缺点评价；用户明确请求教师式反馈时再处理。
- Skill 是助手的工作方法；播放、录音、模型推理、存储与导出需要真实应用和相应工具。不能声称安装 Skill 就获得完整应用。

## 按任务读取

- 处理音频、转写、切分、译前准备、参考译文或报告：读取 [训练规范](references/training.md)。
- 构建、修复、部署、打包或讨论分享变现：读取 [应用与发布规范](references/product.md)。

## 交付原则

使用已有项目和真实素材，先检查再修改。只声称实际完成且可验证的工作。教学结果应能追溯到具体法语段落；应用修改应说明实际验证结果与未验证范围。缺少运行条件时提供明确降级，不能伪装识别或模型输出。
