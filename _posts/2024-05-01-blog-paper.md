---
title:  "你好，这是第一篇blog"
search: false
categories: 
  - first-post
last_modified_at: 2024-05-19T08:16:34-17:00
---

This post should not appear in the search index because it has the following YAML Front Matter:
（如下可以高亮代码）
```yaml
search: false
```

如下注意
**Note:** `search: false` only works to exclude posts when using **Lunr** as a search provider（注意选项）.
{: .notice--info}

双**可以加粗**   '可以缩小'
To exclude files when using **Algolia** as a search provider add an array to `algolia.files_to_exclude' in your `_config.yml`. For more configuration options be sure to check their [full documentation](https://community.algolia.com/jekyll-algolia/options.html).

'''yaml
print("Hello, world!")
代码区域
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