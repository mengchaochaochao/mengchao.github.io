---
title:  "Markdown语法"
search: false
categories: 
  - computer
tags: 
  - markdown
last_modified_at: 2024-05-19T08:16:34-17:00
---

#标题
```yaml
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
#列表
```yaml
1. 第一项
2. 第二项
3. 第三项
```
#链接
```yaml
[链接名称](链接地址)
```
#图片
```yaml
![图片名称](图片地址)
```
#引用
```yaml
> 这是一个引用
```
#代码
```yaml
```python
print("Hello, world!")
```
#表格
```yaml
| 表头1 | 表头2 | 表头3 |
| --- |
| 单元格1 | 单元格2 | 单元格3 |
| 单元格4 | 单元格5 | 单元格6 |
```
#分割线
```yaml
---
```
#注释
```yaml
<!-- 这是一个注释 -->
```
#其他
```yaml
*斜体*   _斜体_
**粗体**   __粗体__
~~删除线~~
==高亮==
```
#其他
```yaml
# 注释
```
#其他
```yaml
{% include video id="iG9CE55wbtY" provider="youtube" %}
```
#其他
```yaml
{% include video id="iG9CE55wbtY" provider="youtube" %}
```
#其他
```yaml
{% include video id="iG9CE55wbtY" provider="youtube" %}
```
#其他
```yaml
{% include video id="iG9CE55wbtY" provider="youtube" %}
```
#其他
```yaml
{% include video id="iG9CE55wbtY" provider="youtube" %}
```
#其他
```yaml
{% include video id="iG9CE55wbtY" provider="youtube" %}
```
#其他
如下注意
**Note:** `search: false` only works to exclude posts when using **Lunr** as a search provider（注意选项）.
{: .notice--info}

双**可以加粗**   '可以缩小'
To exclude files when using **Algolia** as a search provider add an array to `algolia.files_to_exclude' in your `_config.yml`. For more configuration options be sure to check their [full documentation](https://community.algolia.com/jekyll-algolia/options.html).


```

```yaml
algolia:
  # Exclude more files from indexing
  files_to_exclude:
    - index.html
    - index.md
    - excluded-file.html
    - _posts/2017-11-28-post-exclude-search.md
    - subdirectory/*.html
```