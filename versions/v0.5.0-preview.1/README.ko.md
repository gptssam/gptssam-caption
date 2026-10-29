[English](README.en.md) · [한국어](README.ko.md) · [日本語](README.ja.md) · [简体中文](README.zh-CN.md)

# 지피티쌤체 컴팩트 소프트 · v0.5.0-preview.1

**9단계 디자인 프리뷰입니다. 기존 v0.4.0 정식판은 그대로 유지됩니다.**

Gmarket Sans를 기반으로 한글의 폭과 배치 간격을 다듬고, 획 끝에 부드러운 곡선을 더한 자막용 파생 서체입니다. Thin부터 Black까지 9단계 굵기를 제공하며, 각 굵기에 한글 완성형 11,172자를 포함합니다.

![9단계 비교](preview.png)

## 다운로드와 테스트

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


9개 파일은 독립된 TTF이며 가변 폰트가 아닙니다. 설치 목록에는 **GPTSSAM Compact Soft Preview**로 나타납니다. macOS에서는 TTF를 서체 관리자로 열고, Windows에서는 우클릭하여 설치하세요. 편집기를 다시 실행해야 목록에 나타날 수 있습니다. 기존 GPTSSAM Caption / Soft와 별도로 설치할 수 있습니다.

설치 없이 테스트하려면 릴리스 ZIP을 풀고 [font-test.html](font-test.html)을 브라우저에서 여세요. 9개 폰트가 내장되어 오프라인에서도 문장·크기·외곽선·자간·배경을 조정할 수 있습니다. 외곽선은 표시 효과이며 TTF에는 포함되지 않습니다. [자막 크기 샘플](caption-proof.png) · [영문·숫자 샘플](latin-proof.png).

## 설계와 지원 범위

- 원본 Gmarket 대비 한글 몸통 너비 95%, 한글 배치 폭 0.88em. 세로 위치와 배치 수치도 조정했습니다.
- 초성의 노출된 끝과 모음 끝에 약한 곡선을 적용하고, 좁은 곳은 장식을 줄였습니다.
- 한글 완성형 11,172자, ASCII 영문·숫자·기호 포함. 4개 언어 안내는 중국어·일본어 전체 지원을 의미하지 않습니다.
- 영문·숫자는 Gmarket 기반이며 한글용 너비 축소와 고정 배치 폭을 적용하지 않았습니다.
- 페이퍼로지의 한글 비례를 참고했습니다. 새 TTF의 실제 기반은 Gmarket이며, 페이퍼로지·Montserrat 글자 윤곽을 사용하지 않았습니다.
- 기존 v0.4.0 Bold와 같은 출발 굵기에 가까운 비교 대상은 이번 **ExtraBold(800)**입니다. 굵기 이름만으로 두 계열을 동일시하지 마세요.

## 프리뷰의 한계

Gmarket Light·Medium·Bold 세 굵기에서 출발했습니다. 중간·극단 굵기는 윤곽 확장·축소로 만들었으며, 호환 마스터의 보간으로 완성한 패밀리가 아닙니다. 획 연결과 속 공간을 보존하기 위해 일부 글자의 변형량을 줄였으므로 글자별 굵기 균형은 추가 검토가 필요합니다.

특히 Black의 복잡한 받침, 굵기 사이 균형, I/l/1 구별을 다듬을 예정입니다. v0.4.0의 소문자 l 구별용 꼬리는 아직 이식하지 않았습니다. 변형과 맞지 않는 힌팅을 제거했으며 작은 크기의 Windows 표시와 실제 편집기 설치는 추가 검수 대상입니다.

모든 굵기의 한글 수·폭·원본 대비 연결 영역과 속 공간 수를 자동 검사했습니다. 이는 전 글자 수동 검수나 모든 편집기에서의 동작 보증을 뜻하지 않습니다. [검증 결과](verification.json) · [파일 해시와 설계 요약](manifest.json).

## 라이선스와 버전 이력

원저작권 eBay Korea Co., Ltd.와 동봉 [LICENSE.txt](LICENSE.txt) 전문을 유지합니다. 이용·수정·재배포 조건은 원문을 따릅니다. Gmarket 공식 제작·추천·협업 서체가 아닙니다.

[변경 기록](CHANGELOG.md) · [v0.4.0 당시 설명과 파일](https://github.com/gptssam/gptssam-caption/tree/v0.4.0) · [모든 릴리스](https://github.com/gptssam/gptssam-caption/releases).
