# Jingwei Bao · 包经纬

个人学术主页，源代码由 **JingweiBao** 自己的仓库维护。

网站地址：https://jingweibao.github.io/

## 内容更新

- `index.html`：个人简介、联系方式、研究方向和教育经历。
- `style.css`：页面样式，含手机屏幕适配。
- 个人照片以原始 JPEG 数据嵌入 `index.html`，无需额外图片请求；本地 `jingwei-bao.jpg` 保留原图。

不依赖框架或构建工具。修改后提交到 `main`，GitHub Pages 会自动发布。

## 本地预览

在本目录执行：

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

打开 http://127.0.0.1:8765/ 。

## GitHub Pages 设置

仓库 Settings → Pages → Build and deployment：

- Source：Deploy from a branch
- Branch：`main`
- Folder：`/ (root)`

## 说明

页面参考 Pengfei Ren 的个人主页风格，重新编写了 HTML 和 CSS；没有复制导师的照片、论文、统计脚本或个人经历。

当前经历根据用户历史资料整理。暂不展示尚未提供的论文、获奖和项目。
