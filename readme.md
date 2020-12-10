# Method Draw 中文版

- 原项目：[methodofaction/Method-Draw](https://github.com/methodofaction/Method-Draw)
- 在线使用：[Method Draw](https://frost-zx.github.io/Method-Draw/)
- Method Draw 是一个基于 Web 的矢量绘图工具。
- Method Draw 的目标是成为一个简单易用的 SVG 编辑器。它去除了一些功能，例如图层、线端样式，以换取更简单、更愉快的体验。如果您正在寻找功能更完整的开源矢量编辑器，可以试试 [SVG Edit](https://github.com/SVG-Edit/svgedit)。

## 开发

在 `src` 目录下运行 Web 服务端并开发

```
cd src
python -m http.server 端口
```

## 构建

安装项目依赖文件：

`npm install`

（可能需要执行一次 `npm install -g gulp` 命令）

然后执行以下命令，构建到 `dist` 中：

`gulp`

部署 `dist` 中的文件到 Web 服务器中即可。
