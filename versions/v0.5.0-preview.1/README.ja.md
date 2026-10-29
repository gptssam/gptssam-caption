[English](README.en.md) · [한국어](README.ko.md) · [日本語](README.ja.md) · [简体中文](README.zh-CN.md)

# GPTSSAM Compact Soft · v0.5.0-preview.1

9ウェイトのデザインプレビューです。従来のv0.4.0は引き続き利用できます。

Gmarket Sansを基にハングルの字幅・送り幅を調整し、画の端に控えめな曲線を加えました。ThinからBlackまで、各ウェイトにハングル完成形11,172字を収録しています。

![9ウェイト](preview.png)

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


ハングルの字形幅は元の95%、送り幅は0.88emです。英字・数字にはこの幅調整を適用していません。Paperlogyのハングルの比率を参考にしましたが、新しいTTFの基となるアウトラインはGmarketです。

インストール名は **GPTSSAM Compact Soft Preview**。9個の独立TTFで、可変フォントではありません。ZIPを展開して [font-test.html](font-test.html) を開くと、インストールせずオフラインで文章・サイズ・縁取り・字間・背景を比較できます。縁取りは表示効果です。翻訳文書は日本語・中国語の全グリフへの対応を意味しません。

Light・Medium・Boldからアウトラインを拡張・縮小した試作で、互換マスターの補間ではありません。Blackの複雑な終声、ウェイト間の見た目、I/l/1の区別、Windowsの小サイズ表示や編集ソフトでの確認が残っています。旧版の小文字lの足は未移植です。旧Boldに近い元の太さは新ExtraBoldです。

[詳しい仕様と制限（英語）](README.en.md) · [検証結果](verification.json) · [変更履歴](CHANGELOG.md)。原著作権と [LICENSE.txt](LICENSE.txt) を維持しています。Gmarket公式の共同制作・推薦ではありません。
