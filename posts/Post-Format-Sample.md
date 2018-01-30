---
title: Post Format Sample 文章格式示例
date: 2018-01-30 17:54:55
tags: [test]
categories: test
---

# Post Format Sample 文章格式示例
目前使用的 Hugo 支持 Markdown Front Matter 语法 https://jekyllrb.com/docs/frontmatter/
主要涉及 title、date、tags、categories四个变量
也就是 .md 文件的开头需要包含如下内容
```
---
title: Post Format Sample 文章格式示例
date: 2018-01-30 17:54:55
tags: [test]
categories: test
---
```
需要注意 Hugo 按照 .md 文件中的 date 变量排序，如果不写或者格式错误，那么就会被排在最后了。
可以在 GitHub 中预览 Markdown Front Matter 语法是否正确，例如上例预览效果为

| title | date | tags | categories |
| - | - | - |-|
| Post Format Sample 文章格式示例 | 2018-01-30 09:54:55 `-0800` | test | test |

预览中在 date 变量看到时区，也就是 `-0800` 或者类似的字样代表正确。
