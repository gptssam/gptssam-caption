[English](README.en.md) · [한국어](README.ko.md) · [日本語](README.ja.md) · [简体中文](README.zh-CN.md)

# GPTSSAM Compact Soft · v0.5.0-preview.1

这是包含9种字重的设计预览版，原有v0.4.0仍然保留。

基于Gmarket Sans，调整韩文字形宽度和排版间距，并在笔画末端加入柔和曲线。Thin至Black的每种字重均包含11,172个预组韩文音节。

![9种字重](preview.png)

| Weight | TTF |
|---|---|
| 100 Thin | [Thin](GPTSSAMCompactSoftPreview-Thin.ttf) |
| 200 ExtraLight | [ExtraLight](GPTSSAMCompactSoftPreview-ExtraLight.ttf) |
| 300 Light | [Light](GPTSSAMCompactSoftPreview-Light.ttf) |
| 400 Regular | [Regular](GPTSSAMCompactSoftPreview-Regular.ttf) |
| 500 Medium | [Medium](GPTSSAMCompactSoftPreview-Medium.ttf) |
| 600 SemiBold | [SemiBold](GPTSSAMCompactSoftPreview-SemiBold.ttf) |
| 700 Bold | [Bold](GPTSSAMCompactSoftPreview-Bold.ttf) |
| 800 ExtraBold | [ExtraBold](GPTSSAMCompactSoftPreview-ExtraBold.ttf) |
| 900 Black | [Black](GPTSSAMCompactSoftPreview-Black.ttf) |


韩文字形宽度为原字体的95%，字符前进宽度为0.88em。英文字母和数字不采用这套宽度调整。参考了Paperlogy的韩文比例，但新TTF的基础轮廓来自Gmarket。

安装名称为 **GPTSSAM Compact Soft Preview**。这是9个独立TTF，不是可变字体。解压ZIP后打开 [font-test.html](font-test.html)，无需安装即可离线比较文本、字号、描边、字距和背景。描边是显示效果。多语言说明不代表完整支持中文或日文字形。

基于Light、Medium和Bold，通过轮廓扩张或收缩生成试作，不是兼容母版插值。Black复杂收音、字重间的视觉平衡、I/l/1辨识、Windows小字号显示和编辑器安装仍需检查。旧版小写l的短脚尚未移植。新ExtraBold的基础粗细更接近旧Bold。

[完整规格与限制（英文）](README.en.md) · [验证结果](verification.json) · [更新记录](CHANGELOG.md)。保留原版权和完整 [LICENSE.txt](LICENSE.txt)。并非Gmarket官方合作或推荐字体。
