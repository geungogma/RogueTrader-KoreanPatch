# 로그 트레이더 한국어 자동 패치

- `Warhammer 40,000: Rogue Trader`의 영어 번역 파일(`enGB.json`)을 자동으로 최신 한국어 패치 버전으로 교체해주는 모드입니다.(DLC2에서 아직 번역되지 않은 분량은 영어로 나옵니다!)
- 노트북을 바꾼 뒤로 세이브가 유락V를 벗어나질 못해서 검수를 못하는 바람에 주인공 선택지나 NPC들 말투가 오락가락할수 있습니다(누가 누구한테 말하는건지 안 나와 있어서...)

## ✅ 주요 기능
- 매번 게임을 실행할 때 자동으로 최신 `enGB.json`을 다운로드하여 적용합니다.

## 📁 설치 방법
1. 우측 [Releases](https://github.com/geungogma/RogueTrader-KoreanPatch/releases) 탭에서 최신 버전의 압축 파일을 다운로드합니다.
2. C:\Users%USERNAME%\AppData\LocalLow\Owlcat Games\Warhammer 40000 Rogue Trader\UnityModManager로 가셔서 `여기에 풀기`로 풀어주세요.


## ⚠️ 주의 사항
- 이 모드는 게임 폴더의 `StreamingAssets/Localization/enGB.json` 파일을 직접 덮어씌웁니다.
- 게임을 **관리자 권한으로 실행**해 주세요(실행법: 게임을 설치한 드라이브:\steam\steamapps\common\Warhammer 40,000 Rogue Trader 로 가셔서 `WH40KRT.exe`를 `우클릭`하여 `속성`을 여시고, `호환성` 탭에 들어가셔서 `관리자 권한으로 이 프로그램으로 실행`을 클릭해주세요.)
- 또한, 게임이 관리자 권한으로 실행되면 스팀 스샷 기능이 작동하지 않을 수 있으므로, 스팀도 **관리자 권한으로 실행**해주세요.
- 기존 `enGB.json` 파일을 백업해두는 것이 좋습니다.

## 📄 파일 구성
- `KoreanPatch_AutoUpdate.dll` - 핵심 로직을 수행하는 모드 코드
- `info.json` - Unity Mod Manager용 메타 정보

## 📄 손번역 완료된 부분
1. 본편
- 프롤로그
- 1막
    1. 유락V
    2. 라이카디 필리아
    3. 라이카드 마이너리스(스타포트 중후반 파트 제외)
    4. 최후반부 함교

2. DLC
렉스 임페리알리스(DLC2) (완료. 차차 검수해나갈 예정입니다!)

## 👤 제작자
- 군고그마
