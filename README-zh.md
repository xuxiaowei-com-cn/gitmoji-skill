# Gitmoji Skill

[English](README.md) | [中文](README-zh.md)

基于 [gitmoji](https://gitmoji.dev) 的 Git 提交消息格式化技能。

## 简介

本技能帮助规范 Git 提交消息格式，使用 gitmoji shortcode 作为提交标题前缀，让提交历史更加语义化和可视化。

## 用法

提交 Git 时，从 [gitmoji.md](gitmoji.md) 的 Shortcode 列选择对应的前缀：

```
:shortcode: 提交说明
```

格式规则：

- Shortcode 作为行首时，前面不加空格
- Shortcode 后必须跟一个空格，再接提交正文

## 示例

```bash
git commit -m ":memo: add README"
git commit -m ":bug: fix login error"
git commit -m ":sparkles: add user avatar feature"
```

## 文件

| 文件                       | 说明                                            |
|--------------------------|-----------------------------------------------|
| [gitmoji.md](gitmoji.md) | Gitmoji 速查表（Emoji / Shortcode / English / 中文） |
| [CLAUDE.md](CLAUDE.md)   | 技能定义文件                                        |
