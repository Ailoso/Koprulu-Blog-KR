---
layout: post
title:  SC Evo Crossover 모드 출시 v. 1.0
description: 스타1 vs 스타2 모드를 크로스오버 모드로 재출시하며 새로운 메커니즘과 여러 밸런스 패치를 가하였습니다.
date:   2024-04-08 00:01:35 +0900
image:  '/images/Crossover1_0.png'
tags:   [크로스오버, 출시]
---

## 이보 크로스오버 출시 v. 1.0

오늘 저희는 스타 이보 크로스오버 모드를 출시합니다. 크로스오버 모드는 기존의 이보 컴플리트 모드보다 스타1과 스타2 간의 대결에 더욱 심도있게 파고들어 새로운 유닛, 능력과 업그레이드를 추가하고 인공지능의 대결 능력을 향상시켰습니다.

저희는 먼저 크로스오버 1.0 패치 노트를 게시함으로써 이 새 사이트를 시작하고자 합니다. 이 프로젝트가 가능하게 한 모든 분들께 감사드리며, 특히 한국 커뮤니티가 보여준 열정과 사랑은 이 업데이트에 더욱 박차를 가하게 하였습니다.

이번 업데이트에서 저희는 SardineS의 너그러운 배려로 그의 데이터와 업그레이드를 받아서 리버를 개선하였습니다. 그의 [트위치](https://www.twitch.tv/sardinestv) 나 [유튜브](https://www.youtube.com/@SardineS_tv)에서 그를 만나보실 수 있습니다. 그럼 이제 지체없이 아래에 패치 내용과 그 이유에 관한 개발팀의 코멘트를 기술하겠습니다.

이번 업데이트를 위하여 저희는 다음 부분에서 한국어 로컬라이징을 마쳤습니다:
- 모든 텍스트
- 한국어 음성
- 한국어에 맞는 유닛 립싱크

***

![]({{site.baseurl}}/images/Divider_Crossover.png)

_첫째로 저희는 스타1이 스타2와 더 공평한 대결을 펼칠 수 있도록 밸런스를 조절하였으며, 레거시 모드나 캠페인에만 포함되어 있던 몇몇 기능을 삭제하였습니다._

* 폭발형과 진동형 공격 타입의 실드 대상 추가 피해량을 삭제하였습니다.
* 일반형 공격타입 유닛을 제외한 나머지 스타1 유닛의 추가 피해량 방식을 재구성하였습니다.
* 방어력의 공격 경감량이 공격 타입에 따라 달라지던 점을 삭제하였습니다.
* 스타1 유닛의 속성을 대거 조정하였습니다.
* 스타1 기술과 스타2 기술 사이의 상호작용을 일부 조정하였습니다.
* 대부분 스타1 유닛의 공격속도를 조정하였습니다.

_이로써 스타2와 스타1 간의 추가 피해 상호작용이 더욱 잘 호환되는 것을 목표로 하였습니다._

* 공격력 및 방어력 업그레이드 연구 시간이 스타2의 최신 버전과 상응하도록 조정하였습니다.
* 스타1의 가스 채취 건물 비용이 스타2와 동일하도록 조정하였습니다.

_스타1 테란이 스타2를 상대로 유닛 생산 시간을 개선할 수단이 부재하다는 피드백을 받았습니다. 아직 저희도 해법을 찾지는 못하였지만, 몇 가지 가능성을 고려하고 있으며 제안해주실 내용이 생길 경우에는 언제든지 저희 디스코드 서버로 오셔서 던져주시기 바랍니다._

* 섬멸전 인공지능이 일시적으로 비활성화됩니다

_섬멸전 인공지능은 아직 저희가 시행한 밸런스 패치에 호응하도록 수정하지 못하였습니다. 더군다나 스타1 인공지능은 스타2 인공지능에 비하여 상당히 약한 상태에 머물러있습니다. 현재 인공지능 개선을 위한 데이터가 조정 중이며, 다음 주요 패치 때 출시될 예정입니다._


![]({{site.baseurl}}/images/Divider_Terran.png)

* 새 유닛 추가: *스팅어 Stinger* (비용: 125/50, 머신 샵 요구)
* 새 유닛 업그레이드 추가: *헬리오스 예광 탄환* (머신 샵에서 연구, 아머리 요구)

![]({{site.baseurl}}/images/stinger-showcase.png)
*스팅어 모습*

![]({{site.baseurl}}/gifs/2024-07-04-stinger1.gif)
*기본 스팅어*
![]({{site.baseurl}}/gifs/2024-07-04-stinger2.gif)
*헬리오스 예광 탄환 연구*


_새 유닛 스팅어는 테란 플레이어들이 사이클론에 더 잘 대응할 수 있도록 하며, 머신 샵이 부착된 팩토리에서 생산할 수 있습니다. 스팅어는 각각 8(기계 대상 +8)의 피해량을 입히는 두 개의 개틀링 건으로 무장하였으며, 오직 건물을 대상으로 20의 피해량을 입히는 유탄 발사기를 장착하였습니다. 더불어 스팅어는 *헬리오스 예광 탄환* 업그레이드를 통하여 이동 중에도 적에게 공격할 수 있습니다._

_저희는 더 많은 플레이어들이 이 유닛을 사용하며 새로운 전략을 시험해볼 것을 기대합니다. 저희는 이 유닛과 관련된 어떠한 변화 가능성에도 열려있으며, 이로써 저희가 혁신과 변화에 유연하고 열정적으로 대처할 준비되어있다는 점을 강조합니다._


* 컨트롤 타워에 드랍십의 긴급 추진기 업그레이드를 추가하였습니다.
* 드랍십에 긴급 추진기 능력을 추가하였습니다.

![]({{site.baseurl}}/gifs/2024-07-04-dropship.gif)
*긴급 추진기를 사용 중인 드랍십*

_드랍십을 위한 새 업그레이드는 스타2 의료선과 동일하게 작용하지만 컨트롤 타워에서 연구 비용 100/100의 사전 연구를 요구합니다. 일시적 속도 상승을 통하여 드랍십은 곤란한 상황을 벗어나거나 목표 지점까지 신속히 유닛을 이송할 수 있게 됩니다._


* 벙커에 회수 능력을 추가하였습니다.
* 아머리의 차량 방어력 업그레이드와 우주선 방어력 업그레이드를 하나로 통합하였습니다.
* 배틀크루저의 체력이 500에서 550으로 증가하였습니다.
* 배틀크루저의 이동 속도가 1.406에서 1.875로 증가하였습니다.
* 드랍십의 체력이 150에서 165로 증가하였습니다.
* 드랍십의 가속도가 1.06에서 1.5로 증가하였습니다.
* 커맨드 센터의 미네랄 비용이 400에서 350으로 감소하였습니다.
* 팩토리의 미네랄 비용이 200에서 150으로 감소하였습니다.
* 고스트의 피해량이 5 (경장갑 대상 10)에서 8 (경장갑 대상 16)으로 증가하였습니다.
* 고스트의 이동 속도가 2.25에서 2.5로 증가하였습니다.
* 마린의 시야 범위가 8에서 9로 상승하였습니다.
* 마린의 공격 주기가 0.9375에서 0.8608로 감소하였습니다.
* SCV의 체력이 60에서 45로 감소하였습니다.
* 파이어뱃의 공격 주기가 1.375에서 1.25로 감소하였습니다.
* 파이어뱃의 미네랄 비용이 75에서 50으로 감소하였습니다.
* 파이어뱃과 마린의 스팀팩 체력 소모가 10에서 5로 감소하였습니다.
* 시즈 탱크의 보급 소모량이 2에서 3으로 증가하였고, 가스 비용이 100에서 125로 증가하였습니다.
* 시즈 모드된 시즈 탱크의 사거리가 12에서 13으로 증가하였습니다.
* 시즈 탱크의 공격 주기가 2.3125에서 2.05로 감소하였습니다.
* 골리앗의 공중 공격 주기가 1.5에서 1.25로 감소하였습니다.
* 골리앗의 지상 공격 주기가 1.375에서 1.22로 감소하였습니다.
* 미사일 터렛의 공격 주기가 0.9375에서 0.8608로 감소하였습니다.
* 발키리의 공격 주기가 4에서 3.7631로 감소하였습니다.
* 레이스의 공중 공격 주기가 1.375에서 1.25로 감소하였습니다.
* 벌처의 공격력이 10 (경장갑 대상 20)에서 7 (경장갑 대상 14)로 감소하였습니다.
* 벌처에 경장갑 속성이 추가되었습니다.
* 벌처가 스파이더 마인을 심을 수 있는 범위가 3에서 1로 감소하였습니다.
* 더 이상 스파이더 마인이 '부유'속성 유닛과 충돌하지 않습니다.
* 스파이더 마인의 크기가 조금 증가하였습니다.

***

_다른 종족과 마찬가지로 프로토스 또한 스타2의 차원관문과 비교하였을 때 생산 속도에서 뒤처졌습니다. 이를 해결하고자 저희는 경기의 중후반을 위한 새로운 게이트웨이 업그레이드를 추가하였습니다. 이 업그레이드 요구사항에 대한 피드백을 받는 중입니다._

![]({{site.baseurl}}/images/Divider_Protoss.png)

* 시타델 오브 아둔에 게이트웨이의 공명 매트릭스 연구를 추가하였습니다.
* 게이트웨이에 공명 매트릭스 패시브 능력을 추가하였습니다.

![]({{site.baseurl}}/gifs/2024-07-04-matrix.gif)
*공명 매트릭스를 통해 동시에 두 유닛을 생산하는 모습*

_이 새 업그레이드는 프로토스의 후반 생산 능력 문제를 해결하고자 나왔습니다. 아비터 트라이뷰널을 요구하며, 시타델 오브 아둔에서 200/200의 비용으로 연구가 가능합니다. 이로써 게이트웨이는 동시에 두 유닛을 생산할 수 있습니다._


* SardineS의 리버 모드를 기반으로 리버 개편
    - 이제 스캐럽이 스타1 방식으로 이동경로를 찾습니다.
    - 기본 피해량이 100에서 60(실드 대상 +20)으로 감소하였습니다.
    - 이제 리버는 공격력 업그레이드에 영향 받으며, 한 단계당 공격력이 6만큼 상승합니다.
    - 이제 리버의 스캐럽 피해량 업그레이드가 중장갑을 대상으로 +40의 추가 피해를 가합니다.
    - 새 업그레이드 '고취된 렌즈'가 추가되었습니다. 고취된 렌즈는 리버의 시야를 2만큼 증가시킵니다.
    - 리버 수용량 증가 업그레이드를 삭제하였습니다.
    - 스캐럽의 비용이 15/0 에서 0/5로 바뀌었습니다.

<iframe src="https://www.youtube.com/embed/6R4cK9bLCYo?si=JjSYI_btacRr-WLK" frameborder="0" allowfullscreen></iframe>
*SardineS의 리버 시연 영상*

* 옵저버가 감시 모드로 전환하는 능력을 추가하였습니다.

![]({{site.baseurl}}/gifs/2024-07-04-observer.gif)
*감시 모드를 사용 중인 옵저버*

_감시 모드로 전환하는 옵저버는 관측 모드로 전환하기 전까지 이동할 수 없는 대신 시야가 증가합니다._


* 하이 템플러에 무기를 추가하였습니다.
* 다크 아콘에 무기를 추가하였습니다.

_본래 다크 아콘이나 하이 템플러는 무기를 가지지 않지만, 그들이 적에게 그대로 돌진하는 것을 막기 위하여 매우 낮은 피해량의 공격을 추가하였습니다._


* 넥서스의 미네랄 비용이 400에서 350으로 감소하였습니다.
* 드라군의 기본 피해량이 15에서 14로 감소하였습니다.
* 다크 템플러의 공격력이 40에서 45로 증가하였습니다.
* 다크 템플러의 공격 주기가 1.875에서 1.694로 감소하였습니다.
* 질럿과 다크 템플러의 공격 선딜레이가 1.0에서 1.3686로 증가하였습니다.
* 질럿의 공격 주기가 1.375 에서 1.3686로 감소하였습니다.
* 다크 아콘의 피드백이 더 이상 구조물이나 아군을 대상으로 할 수 없습니다.
* 다크 아콘의 피드백이 더 이상 광란 속성의 유닛을 대상으로 할 수 없습니다.
* 다크 아콘의 피드백의 에너지 1당 가하는 피해량이 1에서 0.5로 감소하였습니다.
* 하이 템플러의 속도가 1.875에서 2.0156로 증가하였습니다.
* 하이 템플러의 가속도가 1.6875에서 2.5로 증가하였습니다.
* 셔틀의 이동 속도가 2.4882에서 2.5507로 증가하였습니다.
* 아비터의 공격 주기가 2.8125에서 2.5312로 감소하였습니다.
* 아비터의 스테이시스 필드에 적중당한 유닛은 더 이상 동맹 유닛에 의하여 움직일 수 없습니다.
* 포톤 캐논의 공격 주기가 1.375에서 1.25로 감소하였습니다.
* 포톤 캐논의 실드와 생명력이 100에서 150으로 증가하였습니다.
* 파일런의 실드와 생명력이 300에서 250으로 감소하였습니다.
* 실드 배터리의 범위 및 회복 속도가 스타2의 보호막 충전소와 일치하도록 조정하였습니다.
* 더 이상 할루시네이션이 다양한 스타1 기술에 의하여 즉시 소멸당하지 않습니다.

***

_여태까지 저희가 확인한 저그의 가장 큰 문제는 여왕의 부재로 오는 생산력 부족에 있었기에 저희는 라바를 통하여 변혁을 꾀하였습니다. 저그 종족에 비단 이 문제만 있는 것은 아니지만, 후에 추가 수정을 위한 피드백을 더 수집하고자 합니다._

![]({{site.baseurl}}/images/Divider_Zerg.png)

* 퀸의 인스네어를 속박 크립 능력으로 대체하였습니다.

![]({{site.baseurl}}/gifs/2024-07-04-queencreep.gif)
*퀸이 새 속박 크립 능력을 사용하는 모습*

_퀸에 인스네어를 대체할 능력을 부여하였습니다. 이 능력은 크립과 기존 인스네어를 혼합한 물질을 발사하여 적의 이동 속도를 감소시키고 그 주변에 크립을 생성합니다. 이 능력은 다양한 잠재력을 지니고 몰래 나이더스 커널 등의 방식으로 활용될 수 있습니다._


* 레어의 최대 라바 개수가 3에서 5로 증가하였습니다.
* 하이브의 최대 라바 개수가 3에서 7로 증가하였습니다.
* 해처리, 레어 및 하이브의 라바 생성 간격이 12에서 10으로 감소하였습니다.

![]({{site.baseurl}}/gifs/2024-07-04-lairlarva.gif)
*라바를 5기 보유한 레어*

![]({{site.baseurl}}/gifs/2024-07-04-hivelarva.gif)
*라바를 7기 보유한 하이브*

_저그 플레이어의 유닛 생산을 돕기 위하여 저희는 모든 저그 기본 건물의 라바 대기 시간을 줄이고 최대 보유 라바 수를 늘렸습니다._

* 해처리의 미네랄 비용이 300에서 250으로 감소하였습니다.
* 레어로의 변이 시간이 60에서 80으로 증가하였습니다.
* 하이브로의 변이 시간이 60에서 100으로 증가하였습니다.
* 스포어 콜로니로의 변이 시간이 21에서 16으로 감소하였습니다.
* **오버로드가 더 이상 디텍터가 아닙니다**
    - 이제 오버로드가 디텍터가 되기 위해서는 안테나 업그레이드가 필요합니다.
* 오버로드 이동 속도 증가 업그레이드의 연구 시간이 43에서 60으로 증가하였습니다.
* 오버로드의 이동 속도가 0.9375에서 0.6445로 감소하였습니다.
* 오버로드의 가속도가 1.6875에서 1.0625로 감소하였습니다.
* 퀸의 패러사이트 능력이 이제 168초의 지속시간을 지닙니다.
* '브루들링 소환' 능력의 연구 시간이 60에서 140으로 증가하였습니다.
* 히드라리스크의 보급품 비용이 2에서 1로 감소하였습니다.
* 히드라리스크의 공격 주기가 0.9375에서 0.8437로 감소하였습니다.
* 히드라리스크의 사거리 업그레이드 연구 시간이 100에서 79로 감소하였습니다.
* 히드라리스크의 이동 속도 업그레이드 연구 시간이 100에서 90으로 감소하였습니다.
* 울트라리스크의 크기가 스타2 울트라리스크와 일치하도록 조정하였습니다.
* 뮤탈리스크의 가스 비용이 100에서 75로 감소하였습니다.
* 뮤탈리스크의 공격 주기가 1.875에서 1.5246로 감소하였습니다.
* 디바우러 변태의 미네랄 비용이 150에서 100으로 감소하였습니다.
* 디바우러의 보급품 비용이 2에서 3으로 증가하였습니다.
* 가디언의 이동 속도가 1.406에서 2.25로 증가하였습니다.
* 가디언의 공격 주기가 1.875에서 1.5로 감소하였습니다.
* 가디언의 사거리가 8에서 10으로 증가하였습니다.
* 가디언의 보금품 비용이 2에서 4로 증가하였습니다.
* 스커지의 비용이 24/74에서 25/75로 바르게 수정되었습니다.
* 이제 다크 스웜이 원거리 공격을 90% 감소시키고 마법 공격을 55% 감소시킵니다.
* 이제 저그 유닛이 불사조에 의해 들어올려질 때 제대로 언버로우 됩니다.
* 더 이상 퀸의 인스네어나 디파일러의 플레이그 능력이 시야 밖으로 벗어난 대상을 드러내지 않습니다.

***

![]({{site.baseurl}}/images/Divider_CoreMods.png)

* **긴급 추진기** 능력의 데이터를 추가하였습니다.
* **속박 크립** 능력의 데이터를 추가하였습니다.
* **공명 매트릭스** 능력의 데이터를 추가하였습니다.
* **헬리오스 예광 탄환** 능력의 데이터를 추가하였습니다.
* **스팅어** 유닛의 데이터를 추가하였습니다.
* 울트라리스크의 이동 속도 업그레이드에 따른 시각 효과를 추가하였습니다.
* 통합된 아머리 방어력 업그레이드 데이터를 추가하였습니다.
* 변신수가 스타1 종족으로 변이할 수 있는 능력을 추가하였습니다.
* 크로스오버 모드 업데이트를 위한 작은 데이터 추가
* 이제 게임 메뉴의 디스코드 버튼에 커서를 대면 활성화되기까지 약간의 대기 시간이 필요합니다.
* 디파일러의 마법 애니메이션을 조정하였습니다.
* 메딕의 블라인드 타격 시각 효과를 조정하였습니다.
* 아비터의 무기 및 타격 시각 효과를 조정하였습니다.
* 오버로드의 이동 속도 기본값이 너무 높았던 버그를 수정하였습니다.
* 셔틀이 더 쉽게 클릭될 수 있도록 조정하였습니다.
* 옵저버의 크기가 커지도록 조정하였습니다.
* 더 이상 다크 아콘의 피드백이 구조물을 대상으로 할 수 없습니다.
* 버로우와 언버로우 능력이 스타2의 인터페이스와 동일한 위치에 있도록 조정하였습니다.
* 이제 버로우와 언버로우 명령이 현재 선택중인 다른 유닛에게도 시행됩니다.
* 버로우 단축키 기본값이 스타2와 동일하도록 조정하였습니다.
* 아콘이 다크 스웜에서 제대로 방사 피해를 가하지 못하던 문제를 수정하였습니다.
* 텍스트 스타일 에러 몇 개를 수정하였습니다.
* 스캐너 스윕의 범위 표시 부재를 수정하였습니다.
* 레어 및 하이브 변이 중 취소할 시 변이 애니메이션이 건물에 남아있던 문제를 수정하였습니다.
* SCV가 공격력 업그레이드의 영향을 받는 버그를 수정하였습니다.
* 일부 옵저버토리 사망 모션이 제대로 작동하지 않는 문제를 수정하였습니다.
* 플릿 비콘이 사망 시 크기가 바뀌는 문제를 수정하였습니다.
* 셔틀의 차원 분광기 부모값을 삭제하였습니다.
* 몇몇 미사용 텍스트 키를 삭제하였습니다.
* 기존의 바르지 않던 라바 생성 시간을 19.8로 수정하였습니다.
* 몇몇 텍스쳐 자산을 최적화하였습니다.

***
