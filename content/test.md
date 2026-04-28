+++
title = "测试页面"
date = "2025-12-20"
+++

# 测试页面

## 文章列表

{{ $pages := where .Site.RegularPages "Type" "posts" }}

### 文章总数: {{ len $pages }}

{{ if eq (len $pages) 0 }}
  <p>暂无文章，敬请期待</p>
{{ else }}
  <ul>
    {{ range $pages.ByDate.Reverse }}
      <li>
        <a href="{{ .RelPermalink }}">
          {{ .Date.Format "2006-01-02" }} - {{ .Title }}
        </a>
      </li>
    {{ end }}
  </ul>
{{ end }}
