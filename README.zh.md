# dsh-client-ui-liang-reasoning

[English](README.md) | [中文](README.zh.md)

本插件修改对话框的思考挡位样式：三档（难梁 / 梁圣 / 梁神）显示为横向滑块，并各配一个图标。
图片使用https://github.com/Lichtspektrum/liang-intensity-calibrator的图片。

![截图](public/sc.png)

## 安装

```sh
dsh plugin --profile web add github:makuralymi/dsh-webui-liang-gear-position
# 没有全局 dsh 时：
npx @deepseek-ai/dsh plugin --profile web add github:makuralymi/dsh-webui-liang-gear-position
```

安装后重启 web 进程，再刷新页面即可。

## 自定义

- 字样：改 `lib/client.js` 里的 `LABELS`。
- 图标：替换 `public/*.png` 后，重新内联进 `lib/client.js` 的 `ICONS`。
