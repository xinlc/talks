# 多个入口点

你可以拆分幻灯片。使用' src '属性将它们组织成多个文件。

#### `slides.md`

```markdown
# Page 1

Page 2 from main entry.

---
src: ./subpage.md
---
```

<br>

#### `subpage.md`

```markdown
# Page 2

Page 2 from another file.
```

[了解更多](https://cn.sli.dev/guide/syntax.html#multiple-entries)
