[English](README.en.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md)

# GPTSSAM Caption · v0.4.0

这是一款基于 **Gmarket Sans Bold**、在部分笔画末端加入曲线的韩文字幕衍生字体。**GPTSSAM Caption** 是曲线更鲜明的主版本，**GPTSSAM Caption Soft** 是曲线更柔和的备选版本。两款均为 **Bold**，Soft 并不代表更细的字重。

![字幕对比](preview.png)

## 下载与使用

| File | Variant | Style |
|---|---|---|
| [GPTSSAMCaption-Bold.ttf](GPTSSAMCaption-Bold.ttf) | Clear · primary | Bold |
| [GPTSSAMCaptionSoft-Bold.ttf](GPTSSAMCaptionSoft-Bold.ttf) | Soft · alternative | Bold |


打开 TTF 文件后，点击 GitHub 的 **Raw / Download raw file**。完整资料可通过 **Code → Download ZIP** 下载。先解压：macOS 可用“字体册”打开 TTF 并安装；Windows 可右键点击 TTF 安装。如果编辑软件未显示字体，请重新启动软件。同名字体的旧版本应替换，避免重复安装。

无需安装即可比较：下载完整资料，在本地打开 [font-test.html](font-test.html)。页面内嵌两款字体，离线也能修改句子、字号、描边、字距和背景。描边是预览或编辑软件的显示效果，不包含在 TTF 中。

## 修改范围与字符支持

- 支持 11,172 个预组韩文音节，以及 ASCII 英文字母、数字和标点。韩文字形、字符映射和字宽与 v0.3.1 相同。
- v0.4.0 修改了 24 个英文字母和 8 个数字的笔画末端：`ACEFGHILMPSTaefhilmnprst` / `12345679`。
- 其他字符保留原有形态。闭合字形 `O、o、0、8` 保持不变；小写 `l` 的短右脚在两款中相同。
- 四种语言的说明文档不代表完整支持中文或日文字形。请检查自己的文本是否存在缺字。
- [完整英文与数字样张](glyph-proof.png) · [具体范围和字体哈希](manifest.json)。

## 许可

遵守随附 [LICENSE.txt](LICENSE.txt) 的条件，即可个人或商业使用、修改和再分发，无需另行事先申请许可。可用于视频、广告、付费课程和印刷品，使用字体制作的作品无需免费公开。

再分发字体时，请保留原版权声明并附上完整许可文本；修改版须遵守相同许可及命名条件。不得单独销售字体文件，也不得暗示获得 Gmarket 官方推荐。保留 Gmarket Sans 的原版权声明 **eBay Korea Co., Ltd.**。本项目并非 Gmarket 官方制作、推荐或合作字体。

原文完整保留，包括 Gmarket 关于作品图像宣传使用及表达拒绝意愿的附加第 6 条。该条款不要求在修改或再分发前取得许可。本说明为便于理解的摘要，完整条件请阅读 LICENSE.txt。

## 版本

用户于 2026-10-26 确认为 v0.4.0。正式文件保留已批准的 Clear/Soft 预览版轮廓，更新为正式字体名称与版本信息。[变更记录](CHANGELOG.md)。这不表示已逐字人工检查全部字形，或在所有编辑软件中完成安装测试。
