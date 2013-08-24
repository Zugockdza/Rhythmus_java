Rhythmus Java Edition
=====================

BMS Player for Android

libGdx 엔진 기반으로 짠 안드로이드용 BMS Player입니다.

ARM 기반의 CPU에서 얼마나 구동이 답답한지 느껴보실 수 있습니다.

BMS 파일을 많이 넣으면 (bms 파일 20개 이상?) 로딩에 한세월 걸리니 주의하세요.

PC용 버전도 있습니다.

iOS로도 포팅 가능하다던데 Mac 가지고 계신 분은 도움 좀 (...)

현재 미지원 사항들 (혹은 적용예정)
----------------------------------
- 파일 포멧이 완전히 지원되지는 않고 있음 (일부 에러가 있는 파일 존재, 롱노트 미지원, #IF 조건분기문 및 #RANDOM 미지원 등)
- 라이브러리 자체의 한계로 인해 audio 음 동시재생 한계 있음 (PC에서 특히 심함)
- 라이브러리 자체의 한계로 인해 bitmap 및 audio 파일 포멧을 많이 가리고 movie 지원하지 않음
- 라이브러리의 컬러키 미지원으로 인한 #7번 BGA Overlay 미지원
- 안드로이드에서 일부 BGM이 나오지 않는 문제 (곡 Select와 Result 화면 리소스 로딩이 안 됨)

Bugfix & Update
---------------

* 130824
1. 곡 개수가 적을때 정상적으로 선곡이 안 되는 문제 수정
2. 노트 밀림 표시 추가
3. 마지막 비트에서 멈추지 않도록 수정
4. 플레이 화면 마지막에 여유분의 시간을 추가함
5. 안드로이드에서 입력이 없을 시 화면이 꺼지지 않도록 함