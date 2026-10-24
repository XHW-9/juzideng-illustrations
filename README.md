# 橘子灯 Skill

以原创个人 IP「橘子灯」为主角，为中文文章生成简洁手绘正文配图。

![橘子灯终版角色参考](assets/reference/juzideng-ip-reference.png)

橘子灯是一个会纠结、会累，但总想把事情想明白的橘皮灯罩小旅人。固定特征包括不对称橘帽、露出奶油色内侧的单侧橘皮翻边、侧分头发和情绪叶片；想通时抬起帽沿，亮起两笔短光线。

## 安装与使用

下载 [完整技能包](juzideng-illustrations.zip)，解压后将 `juzideng-illustrations` 文件夹放到你的技能目录，例如 `~/.codex/skills/`。

调用示例：

```text
请用 $juzideng-illustrations 为这篇 Markdown 文章配图。
```

完整工作流见 [SKILL.md](SKILL.md)。每次生成必须同时附上标准角色参考图；支持图像参考输入的生图工具才能执行这一流程。技能包含文章分析、配图安排、单张生成、角色一致性检查与本地素材交付规范。

## 目录

- `SKILL.md`：技能入口。
- `assets/reference/`：终版标准角色图。
- `references/`：角色、画风、构图、提示词与检查清单。
- `agents/openai.yaml`：技能界面元数据。

## 致谢与许可

技能流程基于 Ian 的 [Ian Xiaohei Illustrations](https://github.com/XHW-9/ian-xiaohei-illustrations) 改编，保留原版 [MIT 许可](LICENSE)及 [署名说明](NOTICE.md)。橘子灯为作者原创个人 IP；仓库公开用于展示和技能使用，不表示转让角色名称或品牌身份。
