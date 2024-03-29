---
layout: post
title: "한국어판 Stack Overflow -  SO 한국 유저 분석 1"
date:   2014-07-14 21:07:00
categories: stackoverflow
---

영어 쓰기를 어려워하는 한국 유저

### 들어가면서

지난 몇 일간 [한국어판 Stack Overflow(한국어판 SO) 제안][1] 활동을 하면서 들었던 우려의 목소리를 정리해보면 크게 한국 개발 문화의 특수성 때문에 기존 Stack Overflow(SO) 복사판(idevelop.kr, codeflow.co.kr)들처럼 성공하기 쉽지 않을 것이란 의견과 이미 영문판 SO를 잘 사용하고 있는데 굳이 한국어판 SO를 만들 필요가 있냐는 의견으로 나눌 수 있었다. 영문판 SO를 사용하자라는 의견을 자세히 살펴보면 영어가 문제가 아니라 참여 의지의 문제이고, 이미 많은 사람들이 어떻게든 영문판 SO를 사용하고 있다는 것이다. 본 글에서는 영문판이 존재하기 때문에 굳이 한국어판이 필요없다라는 의견에 대한 제 생각을 정리하고자 한다.

### Stack Overflow Around the World

Stack Overflow를 만든 조엘 스폴스키가 2011년도에 남긴 [Stack Overflow Around the World][2]([번역:세계의 스택 오버플로우][3]) 글에서 SO를 현지화 했을 때 가장 가치있는 지역을 한국과 일본을 언급하였고, 대규모 프로젝트가 존재하지만 영문판 SO가 명백히 도움을 주고 있지 못하고 있기 때문이라 설명하였다. 이 글에서 인구 수 대비 방문자 수의 한국 순위는 전체 21위였다.

### 잘 활용하고 있는가?

많은 개발자들은 문제가 발생했을 때 구글 검색을 하고 SO에서 답변을 찾아 문제를 해결하곤 한다. SO가 시작한 2008년 이래로 많은 양질의 질문/답변이 쌓여 웬만한 문제는 검색만으로 해결할 수 있는 것이다. 그러면 *SO에서 다루지 않았던 문제는 어떻게 할 것인가?* 맞다, `Ask Question`버튼을 누르고 질문하면 된다. 하지만 과연 그렇게 할 수 있는 개발자가 얼마나 될까? 다시 [Stack Overflow Around the World][2]에 나온 접속자 수 통계에 실제로 질문 또는 답변을 올린 비율을 구해보면 답을 얻을 수 있지 않을까? 

### 읽기만 하는 한국 유저들

SO를 운영하는 Stack Exchange Inc.는 SO를 비롯한 Stack Exchange(SE)에 속한 Q&A 커뮤니티(SO도 SE 중 하나)의 데이터를 [data.stackexchange.com][4]에서 공개하고 있다. 이곳을 이용하여 접속 통계와 같은 기간 지역별(Location) 사용자를 구하는 [Query][5]를 통해 `질문+답변 개수` 등의 결과를 얻을 수 있었다. 그 결과 접속 순위에서는 21위였던 반면에 실제 글을 남긴 30개국 중 30위였다. (정확한 Location을 입력한 유저 비율이 각 나라별로 동일하다는 가정했을 경우)

|순위(A/B)|순위(C/A)|국가|방문횟수(A)|인구수(B)|질문+답변 개수(C)|
|----     |----     |----|----       |----     |----|
|1|5|Sweden|671,605|9,422,661|624|
|2|20|Singapore|324,063|5,076,700|172|
|3|21|Finland|321,438|5,380,000|168|
|4|4|Denmark|329,927|5,560,628|326|
|5|9|Israel|431,482|7,708,400|331|
|6|8|Switzerland|402,720|7,782,900|322|
|7|6|Netherlands|849,640|16,659,800|707|
|8|7|Canada|1,753,086|34,409,000|1456|
|9|2|United Kingdom|2,984,833|62,041,708|3231|
|10|3|Australia|1,066,756|22,611,000|1094|
|11|1|United States|13,134,911|311,108,000|15057|
|12|10|Belgium|406,232|10,827,519|305|
|13|17|Czech Republic|323,624|10,515,818|182|
|14|11|Germany|1,947,367|81,802,000|1362|
|15|18|France|1,222,689|65,821,885|675|
|16|16|Poland|675,256|38,092,000|398|
|17|13|Romania|366,955|21,466,174|242|
|18|25|Spain|746,397|46,152,925|310|
|19|23|Italy|835,370|60,605,053|381|
|20|12|Ukraine|399,344|45,778,500|275|
|21|30|South Korea|370,335|48,988,833|59|
|22|15|Russia|775,040|142,905,200|474|
|23|19|Turkey|361,542|73,722,988|193|
|24|22|Brazil|755,084|190,732,694|384|
|25|29|Vietnam|319,379|86,930,000|53|
|26|27|Philippines|325,977|94,013,200|119|
|27|14|India|4,046,059|1,210,193,422|2561|
|28|28|Japan|369,577|127,960,000|105|
|29|26|Mexico|297,180|112,336,538|111|
|30|24|China|717,011|1,341,000,000|305|

### 마치며

입시를 위해 영어를 배운 우리 대부분은 읽기 능력 대비 쓰기 능력이 현저히 떨어질 것이다. 영어 사용자들이 만들어낸 컨텐츠를 참고하는데 문제는 없지만 그들과 함께 컨텐츠를 만들어 나가는데는 어려움을 느낄수 밖에 없을 것이다. 따라서 한국어판 SO는 우리도 참여할 수 있다는 의미로 생각할 수 있지 않을까? 혹자는 이런 걱정을 하기도 한다. 한국어판 SO에 평판이 SO에서 인정 받을 수 있나? 답변은 간단하다 인정받지 못할 이유가 뭐가 있겠는가. 이미 [*Ask Ubuntu*][7], [*Server Fault*][8], [*Super User*][9] 등에서 쌓은 평판이 SO에는 평판에는 영향을 미치지 않지만, 나름의 가치를 인정 받듯이 한국어판 SO의 평판도 그렇게 될 것이라 생각한다. 

다음 글에서는 최근 데이터(2014년 이후, 실제 위 결과와 비슷 함)를 기반으로한 분석 추가와 SO 활동이 곧 내 이력서가 되는 [Careers 2.0][6]에 관한 글을 작성하고자 한다.


[1]: https://area51.stackexchange.com/proposals/68765/stack-overflow-in-korean
[2]: https://blog.stackoverflow.com/2011/04/stack-overflow-around-the-world
[3]: https://github.com/so-in-korean/sok/wiki/stack-overflow-around-the-world
[4]: https://data.stackexchange.com/
[5]: https://data.stackexchange.com/stackoverflow/query/edit/208327
[6]: https://careers.stackoverflow.com/
[7]: https://askubuntu.com/
[8]: https://serverfault.com/
[9]: https://superuser.com/


