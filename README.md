# MLTD Deck Analyzer

for THE iDOLM@STER MILLION LIVE! THEATER DAYS / MLTD // アイドルマスター ミリオンライブ！ シアターデイズ / ミリシタ // 아이돌 마스터 밀리언 라이브! 시어터 데이즈 / 밀리시타

Automatic Deck Making, Score Calculating and Deck Recommanding for higher High Score / 보유한 아이돌로 구성할 수 있는 가장 높은 점수를 내는 덱을 찾아주는 덱 최적화 프로그램

## Download

### Exe version / Exe 파일

v2.12 for Main(Japan) Server / 일본 본섭용
https://www.dropbox.com/s/0umu3in8td0qkfq/mltdkei_v212M.7z?dl=0

v2.12 for Global(Korea) Server / 한국 글섭용
https://www.dropbox.com/s/26flzyt41xk55pz/mltdkei_v212M_kr.7z?dl=0

### Py version / Py 파일

Python 3.9 or above is required. / Python 3.9 이상의 버전이 필요합니다.

v2.12 for Main(Japan) Server / 일본 본섭용
https://www.dropbox.com/s/pa7qivwswyecob3/mltdkei_v212M.py?dl=0

v2.12 for Global(Korea) Server / 한국 글섭용
https://www.dropbox.com/s/z22koorn3j72345/mltdkei_v212M_kr.py?dl=0

## Information

### New Features

Faster Calculation (up to 3x faster than before) / 분석 속도 개선 (이전 버전보다 최대 3배 빨라짐)

### Bug Fix

[KR] 리더 보상 SR 카드 관련 버그 수정

### Notice

The exe file can be detected malicious by some of antivirus software, including windows defender. It's false positive, so please don't be aware. / 윈도우 디펜더를 포함한 몇몇 백신들이 exe 실행파일을 멀웨어라고 진단하는 경우가 있습니다만, 오진이므로 안심하고 사용해 주세요.

### Others

This program uses data from https://mltd.matsurihi.me/cards and https://imasml-theater-wiki.gamerch.com/%E6%A5%BD%E6%9B%B2%E4%B8%80%E8%A6%A7

이 프로그램은 위에 적어놓은 두 사이트의 데이터를 사용합니다.

## How to Use / 사용 방법

### How to Update from older version / 이전 버전에서 업데이트하기

Copy mltdkei_info.txt and mltdkei_idoldata.sqlite (if Global(Korea) version: mltdkei_info_kr.txt and mltdkei_idoldata_kr.sqlite) from older version folder, and paste them on newer version folder. Unless you will lose your current idol lists and you have to update it again.

기존 버전 프로그램 폴더 내부의 mltdkei_info.txt와 mltdkei_idoldata.sqlite (한섭용이면 mltdkei_info_kr.txt와 mltdkei_idoldata_kr.sqlite) 를 복사해서 새로운 버전 프로그램 폴더 내부에 넣어주면 됩니다. 그렇게 안 해도 상관은 없는데 그러면 아이돌 보유 목록을 다시 편집해야 합니다.

### Update Database / 데이터베이스 업데이트하기

Click "Update DB" button. You will see new window which has two buttons. When necessary, click those buttons to update databases. Do not close window when update is ongoing.

"Update DB" 버튼을 누르면 업데이트 하는 창이 뜹니다. 데이터 갱신 필요할 때 버튼 눌러서 해 주면 됩니다. 업데이트 중에는 창을 닫지 마세요. 파일이 손상될 수도 있습니다. + Music DB 쪽은 수작업으로 직접 업데이트 하는 거라, 업데이트 반영이 약간 늦을 수도 있습니다.

### Configure Current Idol Lists / 아이돌 보유 목록 편집하기

Click "Update Idol List" button. You will see new window which has several buttons. When you click those buttons, the program will load Idol informations with photos. Configure them with combobox and click "Save" button to save. Data will be written on "mltdkei_info.txt" (if Global(Korea) version: on "mltdkei_info_kr.txt"). Do not forget to click "Save" button before closing windows, or you will lose your configurations. + Now you can edit infos shown on the screen with just a few clicks. Use combobox under buttons and click "Change All" button.

"Update Idol List" 버튼을 누르면 여러 개의 버튼이 있는 창이 뜹니다. 각각의 버튼을 누르면, 아이돌의 사진과 함께 보유 여부, 마스터 랭크, 스킬 레벨이 표시됩니다. 편집한 다음에 "Save" 버튼을 눌러 저장합니다. (Tip: 마우스 휠을 사용하면 편합니다) 이 데이터는 "mltdkei_info.txt" (한섭용이면 "mltdkei_info_kr.txt") 에 저장됩니다. 저장 버튼을 누르지 않고 창을 닫아버리면, 편집한 내역이 저장되지 않습니다. + 버튼 아래쪽의 콤보박스를 이용하면 화면에 있는 모든 아이돌의 정보를 한 번에 바꿀 수 있습니다. 설정한 다음에 "Change All" 버튼을 누르면 됩니다.

### Configure Main Setting / 기본 설정

Select "Live Type" if you want to calculate with PSTheater type bonus.

Select "Deck Mode" and "Deck Type" to optimize calculation results. "Deck Mode" option with "+" will make and analyze more decks with more leader idols. It takes longer, but can produce accurate results.

Select "Order By" to determine how to order the results. + You can rearrange them after calculation.

"Live Type"에서 PSTheater 속성 보너스 적용 여부를 선택할 수 있습니다.

"Deck Mode"와 "Deck Type"으로 어떤 속성을 우선하여 덱을 만들지 결정할 수 있습니다. "Deck Mode"의 +가 붙은 옵션은 리더 아이돌을 추가로 선택해 덱을 만들어 분석하여, 더 정확한 결과를 얻을 수 있습니다.

"Order By"에서 결과를 어떤 순서로 정렬할 지 결정합니다. + 분석 후에 다른 옵션으로 재정렬할 수 있습니다.

### Presets Description / 프리셋

All Max: Suppose all of your current idols are max rank and max skill level / 현재 보유한 모든 아이돌의 능력치가 최대일 때의 결과 분석

Theoretical: Find the theoretical maximum score in the game / 현재 게임상에서 가능한 최상의 결과 분석

### Advanced Setting / 고급 설정

Combination: The number of idols for deck building / 덱 구성 시에 사용할 아이돌 수 설정

Ideal Calc: The number of decks for theoretical maximum score calculation / 이론상 최상의 점수를 계산할 덱 개수 설정

Score Calc: The number of decks for real score calculation / 실제 스킬 발동 확률을 적용한 시뮬레이션을 진행할 덱 개수 설정

Time of Calc: The number of score calculation for each deck / 각 덱의 시뮬레이션 횟수 설정
