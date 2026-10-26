[English](README.en.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md)

# GPTSSAM Caption · v0.4.0

**Gmarket Sans Bold**を基に、一部の画の端に曲線を加えた韓国語字幕向けの派生フォントです。**GPTSSAM Caption**は曲線がはっきりした標準版、**GPTSSAM Caption Soft**は曲線を控えめにした別案です。どちらも**Bold**で、Softは細いウェイトではありません。

![字幕の比較](preview.png)

## ダウンロードと使い方

| File | Variant | Style |
|---|---|---|
| [GPTSSAMCaption-Bold.ttf](GPTSSAMCaption-Bold.ttf) | Clear · primary | Bold |
| [GPTSSAMCaptionSoft-Bold.ttf](GPTSSAMCaptionSoft-Bold.ttf) | Soft · alternative | Bold |


TTFファイルを開き、GitHubの **Raw / Download raw file** を選択してください。一式は **Code → Download ZIP** から入手できます。ZIPを展開し、macOSではTTFをFont Bookで開いてインストール、WindowsではTTFを右クリックしてインストールします。表示されない場合は編集ソフトを再起動してください。同じファミリー名の旧版は重複させずに置き換えてください。

インストールせずに比較するには、一式をダウンロードして [font-test.html](font-test.html) をローカルで開いてください。2つのフォントを内蔵しており、オフラインで文章・サイズ・縁取り・字間・背景を変更できます。縁取りは表示上の効果で、TTFには含まれません。

## 変更範囲と収録文字

- ハングル完成形11,172字、ASCIIの英字・数字・記号に対応。ハングルの形・文字マッピング・文字幅はv0.3.1から変更していません。
- v0.4.0では英字24字と数字8字の端を変更しました：`ACEFGHILMPSTaefhilmnprst` / `12345679`。
- その他の文字は従来の形を維持。閉じた形の `O・o・0・8` は変更せず、小文字 `l` の短い右側の足は両版に共通です。
- 4言語の説明書は、中国語・日本語の全グリフへの対応を意味しません。使用する文章の文字を確認してください。
- [英字・数字の一覧](glyph-proof.png) · [変更範囲とハッシュ](manifest.json)。

## ライセンス

同梱の [LICENSE.txt](LICENSE.txt) の条件に従い、個人・商用利用、改変、再配布が可能です。条件を満たす場合、個別の事前許可は不要です。動画・広告・有料講座・印刷物にも利用でき、制作物を無料公開する義務はありません。

再配布時は元の著作権表示とライセンス全文を同梱してください。改変フォントにも同じライセンスと名称に関する条件が適用されます。フォント単体の販売や、Gmarketの公式推薦と誤認させる表示はできません。Gmarket Sansの原著作権表示 **eBay Korea Co., Ltd.** を維持しています。Gmarket公式の制作・推薦・共同制作ではありません。

制作物の画像の宣伝利用と拒否の意思表示に関するGmarketの追加第6項を含め、原文をそのまま保管しています。この条項は改変・再配布前の許可を求めるものではありません。この説明は要約であり、全文はLICENSE.txtをご覧ください。

## リリース

2026-10-26にユーザーがv0.4.0として確定。承認済みClear/Softプレビューのアウトラインを維持し、正式名称とバージョン情報を反映しました。[変更履歴](CHANGELOG.md)。全グリフの目視検査や、すべての編集ソフトでのインストール確認を完了したという意味ではありません。
