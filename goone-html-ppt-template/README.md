# 古壹户外 HTML PPT 模板

这是从当前古壹户外招商 HTML PPT 中提取的可复用模板。模板保留：

- 古壹户外视觉背景，包括浅色和深色 WebGL 动态背景
- 内容页右上角的古壹户外标志
- 页眉、页码和页脚样式
- 封面、双栏内容、卡片列表、图片展示、流程页和结束页示例
- 键盘翻页、索引和动态背景开关

## 使用方式

直接打开 `index.html` 即可预览，无需安装依赖或执行构建命令。

快捷键：

- `←` / `→`：前后翻页
- `ESC`：打开或关闭页面索引
- `B`：切换动态或静态背景

## 编辑页面

所有页面都在 `index.html` 中，以 `<section class="slide ...">` 为单位。

新增内容页时，建议复制已有页面，并保留以下右上角品牌标志：

```html
<img class="brand-mark" src="images/goone-logo.png" alt="古壹户外">
```

调整页面数量后，需要同步修改每页 `.chrome` 中的页码，例如：

```html
<div class="chrome"><div>Section · Overview</div><div>02 / 06</div></div>
```

## 图片

品牌标志文件位于：

```text
images/goone-logo.png
```

业务图片可继续放在 `images/` 目录中，通过相对路径引用。

## GitHub Pages

将此文件夹上传到 GitHub 仓库后，可以通过以下形式访问：

```text
https://你的用户名.github.io/仓库名/goone-html-ppt-template/
```

如果上传到用户主页仓库的根目录，则访问：

```text
https://你的用户名.github.io/
```
