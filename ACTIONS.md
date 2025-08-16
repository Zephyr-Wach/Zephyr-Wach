# 本地化 GitHub Actions 说明

本仓库中部分 GitHub Actions 已经本地化，避免依赖外部仓库，提升稳定性。以下列出了各个 Action 的来源和说明。

---

## github-breakout

- **来源**：[cyprieng/github-breakout](https://github.com/cyprieng/github-breakout)
- **版本**：v1.0.0
- **本地路径**：`.github/actions/github-breakout`
- **说明**：用于生成贡献图 Breakout 动画 SVG。已本地化，保留 MIT LICENSE。
- 使用示例：

```html
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="results/breakout/breakout-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="results/breakout/breakout-light.svg" />
    <img alt="Breakout Game" src="results/breakout/breakout-light.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  </picture>
</div>
<br>
```

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="results/breakout/breakout-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="results/breakout/breakout-light.svg" />
    <img alt="Breakout Game" src="results/breakout/breakout-light.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  </picture>
</div>
<br>

---

## ## 

- **来源**：[yoshi389111/github-profile-3d-contrib](https://github.com/yoshi389111/github-profile-3d-contrib)
- **版本**：v0.9.0
- **本地路径**：`.github/actions/github-profile-3d-contrib`
- 使用示例：

```html
<div align="center">
    <img src="results/3D-Contrib/profile-gitblock.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
    <img src="results/3D-Contrib/profile-green-animate.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
    <img src="results/3D-Contrib/profile-green.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
    <img src="results/3D-Contrib/profile-night-green.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
    <img src="results/3D-Contrib/profile-night-rainbow.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
    <img src="results/3D-Contrib/profile-night-view.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
    <img src="results/3D-Contrib/profile-season-animate.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
    <img src="results/3D-Contrib/profile-season.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
    <img src="results/3D-Contrib/profile-south-season-animate.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
    <img src="results/3D-Contrib/profile-south-season.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
</div>
```
<div align="center">
  <img src="results/3D-Contrib/profile-gitblock.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  <img src="results/3D-Contrib/profile-green-animate.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  <img src="results/3D-Contrib/profile-green.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  <img src="results/3D-Contrib/profile-night-green.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  <img src="results/3D-Contrib/profile-night-rainbow.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  <img src="results/3D-Contrib/profile-night-view.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  <img src="results/3D-Contrib/profile-season-animate.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  <img src="results/3D-Contrib/profile-season.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  <img src="results/3D-Contrib/profile-south-season-animate.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
  <img src="results/3D-Contrib/profile-south-season.svg" style="width: 90%; max-width: 600px; min-width: 300px;" />
</div>