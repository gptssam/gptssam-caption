[English](README.en.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md)

# 지피티쌤체 · GPTSSAM Caption v0.4.0

**Gmarket Sans Bold**를 기반으로 일부 획 끝에 곡선 포인트를 더한 자막용 파생 서체입니다. **지피티쌤체 / GPTSSAM Caption**은 선명한 곡선의 대표형, **지피티쌤체 소프트 / GPTSSAM Caption Soft**는 약한 곡선의 대안형입니다. 두 형 모두 **Bold**이며 소프트가 더 얇은 굵기는 아닙니다.

![자막 비교](preview.png)

## 다운로드와 사용

| File | Variant | Style |
|---|---|---|
| [GPTSSAMCaption-Bold.ttf](GPTSSAMCaption-Bold.ttf) | Clear · primary | Bold |
| [GPTSSAMCaptionSoft-Bold.ttf](GPTSSAMCaptionSoft-Bold.ttf) | Soft · alternative | Bold |


TTF 파일을 연 뒤 GitHub의 **Raw / Download raw file**을 누르세요. 전체 자료는 **Code → Download ZIP**으로 받습니다. 압축을 푼 뒤 macOS에서는 TTF를 서체 관리자로 열어 설치하고, Windows에서는 TTF를 우클릭해 설치합니다. 편집기에 보이지 않으면 편집기를 다시 실행하세요. 같은 이름의 이전 버전은 중복 설치하지 말고 교체하세요.

설치 없이 비교하려면 전체 자료를 내려받아 [font-test.html](font-test.html)을 로컬에서 여세요. 두 폰트가 내장되어 인터넷 없이 문장·크기·외곽선·자간·배경을 비교할 수 있습니다. 외곽선은 화면 효과이며 TTF 자체에 들어 있지 않습니다.

## 수정 범위와 지원 글자

- 한글 완성형 11,172자와 ASCII 영문·숫자·기호를 지원합니다. 한글 모양·문자 매핑·글자 폭은 v0.3.1과 같습니다.
- v0.4.0은 영문 24자와 숫자 8자의 획 끝을 수정했습니다: `ACEFGHILMPSTaefhilmnprst` / `12345679`.
- 나머지 글자는 기존 형태를 유지합니다. 닫힌 `O·o·0·8`은 유지했고, 소문자 `l`의 짧은 오른쪽 꼬리는 두 형에 공통 적용했습니다.
- 문서의 4개 언어는 중국어·일본어 글자 전체 지원을 뜻하지 않습니다. 사용할 문장에 빠진 글자가 없는지 확인하세요.
- [영문·숫자 전체 비교표](glyph-proof.png) · [정확한 범위와 폰트 해시](manifest.json).

## 라이선스

동봉된 [LICENSE.txt](LICENSE.txt) 조건 안에서 개인·상업 이용, 수정·재배포가 허용됩니다. 별도의 사전 승인 절차가 아닙니다. 수익형 영상·광고·유료 강의·인쇄물에도 사용할 수 있으며 제작물을 무료로 공개할 의무는 없습니다.

폰트를 재배포할 때 원저작권 표시와 라이선스 전문을 동봉하고, 수정본에도 같은 라이선스와 이름 관련 조건을 지키세요. 폰트 파일 자체만 별도 상품으로 판매하거나 G마켓의 공식 추천으로 표시하지 마세요. Gmarket Sans 원저작권 **eBay Korea Co., Ltd.** 고지를 유지합니다. G마켓의 공식 제작·추천·협업 서체가 아닙니다.

원문에는 제작물 이미지의 홍보 활용과 거부 의사에 관한 G마켓 추가 6번 문구도 그대로 보존했습니다. 수정·재배포 전에 허가를 받으라는 뜻이 아닙니다. 이 문서는 이해를 돕는 요약이며 전체 조건은 LICENSE.txt를 따릅니다.

## 버전 기록

2026-10-26 사용자가 v0.4.0으로 확정했습니다. 승인한 선명한/약한 곡선 시안의 윤곽은 그대로 두고 정식 이름·버전 메타데이터를 반영했습니다. [변경 기록](CHANGELOG.md). 전 글자 수동 검수나 모든 편집기 설치 검수 완료를 뜻하지 않습니다.
