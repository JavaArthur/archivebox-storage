# ArchiveBox 存档仓库

个人网页存档集合，由 ArchiveBox Skill 自动生成。

## 目录结构

```
archivebox-storage/
├── 2026/
│   ├── 02/
│   │   ├── 05/
│   │   │   ├── example-com-article/
│   │   │   │   ├── index.html          # 完整网页
│   │   │   │   ├── article.md          # Markdown
│   │   │   │   ├── article.pdf         # PDF（可选）
│   │   │   │   ├── screenshot.png      # 截图（可选）
│   │   │   │   └── metadata.json       # 元数据
│   │   │   └── ...
│   │   └── ...
├── index.json          # 全局索引（可搜索）
└── README.md           # 仓库说明
```

## 使用方式

### 保存网页
```bash
cd /root/.openclaw/workspace/skills/archivebox-skill
python3 archivebox_skill.py save <URL> --tags "标签"
```

### 搜索存档
```bash
python3 archivebox_skill.py search "关键词"
```

### 查看统计
```bash
python3 archivebox_skill.py stats
```

## 存档统计

- 总存档数：见 index.json
- 最后更新：2026-02-05

---

*本仓库由 OpenClaw ArchiveBox Skill 自动管理*
