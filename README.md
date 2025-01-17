# 웹폰트 서브셋용 글리프 모음

완성형(KS X 1001, EUC-KR, Code Page 51949)은 제정 당시(1974년, 개정 1987년) 현대 한글의 모든 글자 11,172자 중 사용 빈도가 높은 2,350자를 추려내어 만든 것입니다.<br>
하지만 [「국어생활」 1989년 가을호](https://www.korean.go.kr/nkview/nklife/1989_3/18_5.html)에서 이미 지적되었듯이, 실제로 필요하지만 완성형에 포함되지 못한 한글 글자가 다수 있었습니다.

이 문제는 유니코드가 완성형 한글과 조합형 한글을 모두 포함함으로써 종식되었지만, 최근에 와서 이 문제는 웹폰트를 사용하려는 사람들에게 또다시 다가왔습니다.

한글 11,172자가 모두 포함된 웹폰트의 크기는 네트워크로 보내기에는 너무나 큽니다.

웹폰트뿐만이 아닙니다.<br>
모든 파일은 단순히 서버에서 클라이언트로 보내는 것에서 끝나는 것이 아니라, 이를 사용자의 웹브라우저가 받아서 해석하고 화면에 출력하는 것까지가 되어야 그 할일을 다 하는 것입니다.<br>
당연히 서버에서 보내는 파일의 크기가 작을수록, 사용자의 웹브라우저가 이를 최종적으로 사용자에게 보여주는 데까지 걸리는 시간이 짧아집니다.

그래서 다시 완성형이 떠올랐습니다. 일단 국가 표준이기도 하고, 한글 11,172자를 모두 보내는 것보다 2,350자만 보내는 것이 더 가볍기 때문입니다.

하지만 상술했듯이, 완성형에는 빠진 글자가 상당히 많이 존재하고, '완성형의 글자 외에 무엇이 더 필요한가'에 대한 연구도 많이 진행되었습니다.

이 웹폰트 서브셋용 글리프 모음은 여러 연구에서 제안한 완성형에 포함된 한글 글자 외에 추가적으로 필요하다고 생각되는 글자들을 포함하도록 만들어졌습니다.

## 포함된 글리프 목록

`glyph.txt`는 다음 글자를 포함합니다.
  * KS X 1001(완성형) 한글 2,350자
  * 알파벳 및 한글 자모, 숫자, 특수문자
  * 노민지, 윤민구의 [「KS 코드 완성형 한글의 추가 글자 제안」](http://koreantypography.org/ko/paper/paper_view.asp?paper_seq=79)에 따른 한글 224자
  * [「국어생활」 1989년 가을호](https://www.korean.go.kr/nkview/nklife/1989_3/18_5.html)에서 지적한 빠진 한글 217자
  * 그 외 조사 후 추가한 한글 31자
  * 국제 음성 기호 및 영/독/불의 다이어크리틱 62자

> [!CAUTION]
> 가나(히라가나, 가타카나), 한자(정자, 간체자, 신자체 등)가 포함되어 있지 않아 일본어, 한자 등을 표시할 수 없습니다.<br>
> 오직 한글 및 알파벳만 표시되는 환경에 적합합니다.

## 추가된 한글 글자 목록

```c
// 노민지, 윤민구의 「KS 코드 완성형 한글의 추가 글자 제안」
갋갣걥겷괐괢굠굥궸귕귬긂긇긓깄깯꺆꺍껓껕꼉꼳꽅꽸꿘뀰뀼낻냗냡냣냬넏넢넫녇녱놁놑놰뇄뇡뇸눍눝뉻늗늧늼닁닏닽댠됭둗둚뒙딮딷똠똡똣똭똰뙇뙜뚧뜳뜽뜾랃랟랲럔럲럳렜렫롣롹뢔뤤맜맟맫먄몱뫠뫴뭥뮊뮹믁믕믜밷뱜뱡볌볻볿봥뵴붠붴뷁븡븨빋빧뺜뽓뾱뿕뿝쀠쁭샏샾섁섿셱솀솁솓쇵숖슌싥싳싿쎔쎠쎤쎵쎼쏼쑝쒐쒬씃씿앋앜얬얭옏옝옦옫왘왭왰욷웇웟웻윾읩읭읻잌잍쟵젇젉좬즒즤짣짲쫃쫒쬲쮓찓찟쵀췍칢칮칰칻캨캰컄켘콛쾃쿈쿽퀌퀜퀠큲킄탇턻톧퇻툶퉷팓팤팯펵퐉핰핳핻햏햔햣헗헠헡헣헿홥홨횽훕흝힣
// 국어생활 1989년 가을호
걁걌겱괫괾궛궬궵궹귊귭귯긜긥긧깪꺗껠껩꼶꽌꽛꽨꽬꾓꿧뀃뀟낋낐냡녓녭놧놴놸뇦눤눨눳뉀뉄뉍뉏뉐뉫뉸늇늫늽늿닼돜돴됀됄둴뒌뒐뒜뒴딺뙌뙐뙛뙥뙬뙴뚦뚭뛘뛜뛨뜲뢘뢜뤈뤌맀맽멺몐몔몝몟뫌뫗뫤뫨묌뭰뭴뮀뮉뮘뮙밨봘봣봰봴뵊붯빘뼀뼌뼐뾥솄솼쇕숸숼쉇쉤슮싰쌂쌋쌯쌰썻쎅쎗쎳쐇쐔쐘쑷쒄쒈쒓쓔씝앺얫엤엪왤욂욒웂웼읆읎잙쟷젙젰졁졋좐좰줜줠줫줸줼쥈쥥즑짷쫗쫜쫫쫸쫼쬣쬬쭛쭨쭬쭷쯕쳈쳘쳣쵝춴춸췃췔췠췩칬켼콀콈콉쾐쾔쾝쾟쾽큶킸텰퇼툅퉌퉐퉛퉨퉬퉸폇폔퓡헸혯홸횁휍휏휐흿힜
// 기타
겍궨됬됸뚐뚑뚯뚸뜌뜝띡럄묭쁄삗삨샇쑉쑌좠챂챺캪켙퀙큥턋턌텻푈흅
```
---
## 웹폰트 서브셋 목록
본 프로젝트를 이용해 만든 웹폰트 서브셋 목록입니다.
* [리디바탕](https://github.com/TetraTheta/RIDIBatang-subset)
* [Noto Sans KR](https://github.com/TetraTheta/NotoSansKR-subset)
