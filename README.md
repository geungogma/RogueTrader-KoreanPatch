# 로그 트레이더 한국어 자동 패치

이 모드는 `Warhammer 40,000: Rogue Trader`의 영어 번역 파일(`enGB.json`)을 자동으로 최신 한국어 패치 버전으로 교체해주는 모드입니다.(DLC2 중 아직 번역되지 않은 곳은 영어로 나옵니다!)

## ✅ 주요 기능
- 매번 게임을 실행할 때 자동으로 최신 `enGB.json`을 다운로드하여 적용합니다.
- Unity Mod Manager(UMM)를 통해 쉽게 설치 및 사용 가능합니다.

## 📁 설치 방법
1. 우측 [Releases](https://github.com/geungogma/RogueTrader-KoreanPatch/releases) 탭에서 최신 버전의 압축 파일을 다운로드합니다.
2. C:\Users%USERNAME%\AppData\LocalLow\Owlcat Games\Warhammer 40000 Rogue Trader\UnityModManager로 가셔서 `여기에 풀기`로 풀어주세요.


## ⚠️ 주의 사항
- 이 모드는 게임 폴더의 `StreamingAssets/Localization/enGB.json` 파일을 직접 덮어씌웁니다.
- 게임을 **관리자 권한으로 실행**해 주세요(실행법: 게임을 설치한 드라이브:\steam\steamapps\common\Warhammer 40,000 Rogue Trader 경로로 가셔서 `WH40KRT.exe`를 `우클릭`하여 `속성`을 여시고, `호환성` 탭에 들어가셔서 `관리자 권한으로 이 프로그램으로 실행`을 클릭해주세요.)
- 기존 `enGB.json` 파일을 백업해두는 것이 좋습니다.

## 📄 파일 구성
- `KoreanPatch_AutoUpdate.dll` - 핵심 로직을 수행하는 모드 코드
- `info.json` - Unity Mod Manager용 메타 정보
- `README.md` - 사용 설명서

## 📄 현재 번역된 부분
1. 본편
- 프롤로그
- 1막
    1. 유락V
    2. 라이카디 필리아
    3. 라이카드 마이너리스(스타포트 중후반 파트 제외)
    4. 최후반부 함교

2. DLC
- 렉스 임페리알리스(DLC2)
    1. 1막
    2. 2막 도입부
 
## 👤 제작자
- geungogma
