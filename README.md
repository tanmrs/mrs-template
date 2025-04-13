# 自建 MRS 规则仓库

本项目用于自动构建 Clash.Meta / Sing-box 使用的 `.mrs` 规则文件。

## 使用方法

1. 编辑 `data/geo/geosite/custom.txt` 添加自定义域名；
2. 推送改动后 GitHub Actions 会自动生成 `output/custom.mrs`；
3. 使用 Raw URL 地址订阅 `.mrs` 文件：

```
https://raw.githubusercontent.com/<你的用户名>/<仓库名>/main/output/custom.mrs
```

适用于 Clash.Meta、Sing-box 的规则订阅。
