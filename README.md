# Vault_Kai

用于学习、研究笔记和艺术创作的个人 Obsidian 知识库。

## 目录

```text
Vault_Kai/
├── .obsidian/   # Obsidian 配置
├── Notes/       # 日常笔记、随手记录、使用指南
├── Projects/    # 创作项目、反馈记录
├── Research/    # 阅读清单、读书笔记、研究资料
├── Assets/      # 图片与其他附件
├── README.md
├── .gitignore
└── .gitattributes  # 保留原有 Git 换行规范
```

- `Notes/DailyNotes/`：每日记录。
- `Notes/Dumping ground.md`：暂未归类的想法。
- `Projects/FeedbackNotes/`：反馈记录及原有模板。
- `Research/ReadingList/`：阅读清单。
- `Research/Reading Reflections/`：读书笔记，包括 *The Order of Time*。
- `Assets/`：保留原图片分类 `ArtistExamples`、`MySketches`、`RandomImages`。

## 在 Obsidian 中使用

打开文件夹作为仓库（Open folder as vault），选择最外层 `Vault_Kai`。
默认新笔记保存到 `Notes/`，每日笔记保存到 `Notes/DailyNotes/`，新附件保存到 `Assets/`。
现有图片嵌入使用唯一文件名（如 `![[StickFigure.png]]`），整理后仍可解析。

## Git 同步

个人仓库：<https://github.com/ZCAI004/Vault_Kai>。
`origin` 指向个人仓库，`upstream` 保留为原始模板的参考来源。
整理保留本地和远程的原有提交历史；现有笔记、图片和阅读清单的勾选状态均保留。

`.DS_Store` 和设备专用的 `.obsidian/workspace*.json` 不再纳入版本控制，电脑上的文件仍可保留。
其他 Obsidian 配置继续同步。日常使用 GitHub Desktop 提交笔记，然后 Push origin。

## 原始资料

- [Obsidian 使用指南](Notes/Help%20using%20Obsidian.md)
- [原仓库说明全文（历史参考）](Notes/Reference/Original%20repository%20setup.md)
- 模板来源：<https://github.com/ktwindmill/StudioPracticeExampleVault>，用于 Goldsmiths Computational Arts studio practice。

原仓库说明全文保留在上面的历史参考中，其中的旧目录及同步步骤以本页为准。
