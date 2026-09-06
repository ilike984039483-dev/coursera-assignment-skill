# coursera-assignment-skill

这是一个用于自动完成并提交 Coursera DeepLearning.AI 编程作业（含 Quiz 答题）的本地技能（SKILL.md）。

## 核心方法

- **两段式浏览器派发**：编程作业拆成「补全代码 + 运行 + 保存」与「提交 + 核对记录」两个独立子任务，避免长任务超时与跨域 iframe 失效。
- **Quiz 双人复核制**：作答员与审查员分两遍独立作答/核对后裁决，再单独提交，降低概念判断与多选的失分风险。

## 文件结构

```
coursera-assignment/
└── SKILL.md     # 完整技能说明（适用场景、函数清单、任务模板、踩坑记录）
```

## 使用方式

将本技能目录放入本地 skills 目录，即可在派发 Coursera 编程作业 / Quiz 链接时被调用。详细流程见 SKILL.md。

