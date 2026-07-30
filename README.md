# 椒盐音乐 EQ 配置转换器

将 AutoEQ 格式的 EQ 滤波器配置转换为 Salt Player 的 JSON 格式。

## 使用方式

1. 用浏览器打开 `eq_converter.html`
2. 在左侧文本框粘贴 EQ 配置（如 `Apple AirPods Max (USB C) Filters ALL PK.txt` 的内容）
3. 填写**标题**（耳机名称）和**作者**
4. 点击 **立刻转换** 按钮
5. 右侧文本框输出 Salt Player EQ JSON，复制使用

快捷键：`Ctrl + Enter` 触发转换。

## 限制

- 仅支持 **PK (Peak)** 类型的滤波器
- 若输入中含有非 PK 且增益非 0 dB 的配置，转换将拒绝并报错
