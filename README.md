# Newbie-Guideline

해당 문서는 프로그래밍/개발에 입문하려는 뉴비분들(컴퓨터학과 신입생, 비전공 개발 입문자 등)과 새로운 공부 리소스를 찾으려 하는 모든 분들을 위한 지침서입니다.

## Prerequisite

프로그래밍은 다른 분야와 비교하여 선수지식이 적은 편이라고 생각하지만, 그럼에도 불구하고 알아두면 좋은 선수지식이 있습니다.
특정 프로그래밍 분야들은 심도 있는 선수지식이 필요한 때도 있긴 하지만, 아래 내용 하나만큼은 일반적으로 도움이 되는 선수지식입니다:
* 영어 : 보통 선수지식으로 수학을 생각하는 분들이 많은데, 의외로 정말 필요한 선수지식은 영어입니다. 수학은 분야에 따라 많이 쓰이기도 하지만 전혀 쓰이지 않을 수도 있습니다. 반면에 영어는 공부를 하다 보면 필수 불가결한 스킬입니다. 책이나 문서 등 양질의 공부 자료들은 대부분 영어로 작성되어 있으며, 무엇보다 공부하는 과정에서 대단히 많은 검색을 하게 될 텐데 대부분의 원하는 결과는 Stack Overflow나 Quora라는 해외 사이트에서 찾을 수 있습니다. 영어 능력에서 오는 차이는 고급 개발자가 될수록 더욱 심화하므로, 본인의 영어 능력이 부족하다고 한국어로 되어있는 책이나 자료만 고집하지 말고 천천히 공부해서 영어 자료들에 친해지도록 합시다.
  * [IT 개발자의 영어 필살기](http://www.yes24.com/Product/Goods/85385648) : IT 업계에서 주로 사용하는 표현과 단어들을 접해볼 수 있습니다. 난이도는 굉장히 쉬운편이고 굉장히 얇아서 해당 책으로 새로운 공부를 한다는 느낌은 아니고, 해당 책을 통해서 앞으로 어떤 영어를 어떻게 공부할 지 길라잡이로 사용할 수 있습니다.
  * [English for Developers](http://www.yes24.com/Product/Goods/19992192) : IT 업계에서 주로 사용하는 표현과 단어들을 어느 정도 익힐 수 있습니다. 난이도가 높진 않지만 위 책보다는 어려운 편이며, 어느 정도 영어 표현들에 대한 학습을 할 수 있습니다.
  * [Grammar in use intermediate](http://www.yes24.com/Product/Goods/61953545) : 학창 시절 한 번씩은 들어봤을 유명한 영어 문법서입니다. 해당 책을 두세 번 정독하고 나면 영어를 읽고 쓰는데 확실히 도움 되는 것이 체감됩니다.
  * [Computer Science and Technology Vocabulary](https://www.vocabulary.com/lists/1508153) : Computer Science(이후 CS)와 관련된 용어들 리스트와 간단한 뜻이 적혀 있습니다. 한 번씩 눈에 익혀두면 좋습니다.
  * [Glossary of computer science](https://en.wikipedia.org/wiki/Glossary_of_computer_science) : 위와 마찬가지로 용어 리스트와 간단한 뜻들이 적혀 있습니다. 한 번씩 익혀두면 좋습니다.
  * 위 자료들은 굉장히 빠르게 학습할 수 있는 내용입니다. 가볍게 학습하고 나서, 주기적으로 원서를 읽고 Stack Overflow나 Quora 글들을 보며 영어에 친숙해지도록 합시다.

## Computer Language

개발 공부를 시작하면서 가장 처음 접하게 되는 것은 아무래도 컴퓨터 언어일 것입니다. (간혹가다가 컴퓨터구조 같은 것들을 공부하며 입문하는 예외적인 케이스도 보긴 했습니다만..)
컴퓨터 언어는 말 그대로 컴퓨터에서 동작하는 소프트웨어(프로그램)를 작성하기 위한 언어입니다.
처음 공부하는 분들의 입장에서는 정말 수많은 컴퓨터 언어 중에 무엇을 공부하는 것이 가장 좋을지 막막할 수도 있습니다.
또, 어떤 분은 대체 왜 이렇게 많은 컴퓨터 언어가 존재하는지 의아해할 수도 있습니다. (이런 의문을 품는 것은 매우 좋습니다)

컴퓨터 언어들은 저마다 고유한 특색을 가지고 있고, 장단점이 있습니다. 이러한 언어의 특성 때문에 특정 컴퓨터 분야에는 특정 언어가 어울리게 됩니다.
예를 들어, 안드로이드 앱 개발을 할 때는 Java와 Kotlin이라는 언어를 주로 쓰게 됩니다. (NDK개발을 한다면 C/C++도 많이 쓰게 됩니다)
웹 개발자라면 Javascript와 Java를 많이 다루게 될 것이고, 게임 개발자라면 C++이나 C#을 많이 사용할 것입니다.
시스템 개발자라면 C와 C++를 주로 쓰게 될 것이며, 윈도우 응용 프로그램 개발자라면 C#과 일부 C++을 쓸 것입니다.
혹은, 정말 어쩌면, 매니악한 분야를 좋아하여 로우 레벨 개발을 하게 된다면 C와 어셈블리를 사용하게 될 것입니다.

이처럼 많은 분야와 많은 언어가 있는데 이들을 모두 공부해야 하는 것은 아닌가 걱정이 될 수 있습니다.
하지만, 언어는 어디까지나 도구일 뿐이며 해당 언어를 사용하여 무언가를 만들어내는 능력이 중요합니다. (물론, 컴파일러나 언어론 자체를 전공하는 예외적인 케이스는 제외합니다)
그리고 보통 하나의 언어에 숙달하고 나면 다른 언어를 익히는 시간은 굉장히 줄어듭니다.
제 경우 처음 공부한 언어가 C언어였는데, 언어를 처음 공부한 시점부터 해당 언어로 무언가 그럴싸한 프로그램을 만들어내기까지 거지는 6개월이라는 시간이 걸렸던 거 같습니다.
반면, 자바를 공부하기 시작한 지 1주일 만에 정부 사업으로 진행한 앱을 만들었고, 파이썬을 공부한 지 이틀 만에 그럴싸한 프로그램을 만들어냈습니다.
이러한 극단적인 시간 축소에는 언어의 특성적인 측면도 있긴 하지만 프로그래밍 자체에 대한 숙련도 증가로 인한 학습 속도 향상이 지대했습니다.
즉, 여러분은 (취미로 여러 언어를 공부하는 경우를 제외하면) 여러 언어를 공부하는 데에 시간을 과투자할 필요가 없습니다.

그렇다고 언어를 익히는 것이 중요하지 않다는 것은 아닙니다. 도구 자체의 사용법을 익히는 것 또한 필요합니다.
개인적으로 주 무기로 사용할 언어 두 개와 보조 무기로 사용할 언어 하나 정도 익혀두는 것을 추천합니다.
자신이 어떤 분야에서 일을 하게 될지, 어떤 분야를 세부적으로 전공할지 미리 정할 수 있다면 그에 맞춰서 주 무기를 구성하는 게 베스트지만, 그렇지 않은 경우가 더 많을 것입니다.
그렇다면 한국에서 일할 것이라면 Java와 C++을 주 무기로 삼고, Python을 보조 무기로 삼는 것을 추천합니다.
Java는 한국에서 가장 많이 사용하는 언어이고, C++는 잘 공부해두면 다른 언어들을 쉽게 익힐 수 있으며, Python은 범용적으로 쓸 수 있기 때문입니다.
물론, 자신이 끌리는 언어가 따로 있다면 해당 언어를 주 무기로 삼아도 전혀 무방합니다.
참고로 위에서 주 무기라고 하면 해당 언어로 자신이 원하는 로직을 자유롭게 짤 수 있으며 해당 언어의 장단점이 무엇인지 알고 특색을 살려 프로그래밍 할 수 있는 수준을 말하고,
보조 무기라고 하면 해당 언어로 쓸만한 프로그램을 구현할 수 있는 수준을 말합니다.

그 외에도 어떤 언어로 입문을 할 것인지도 매우 많은 분들이 궁금해하는 토픽 중 하나입니다.
컴퓨터공학과 신입생이라면 학교 커리큘럼 상 처음 배우는 언어로, 비전공자분들 중 원하는 분야가 있다면 해당 분야에 적합한 언어가 있기에 해당 언어로 시작하면 되지만, 그렇지 않은 분이라면 Python으로 입문하는 것을 굉장히 추천합니다.
Python은 굉장히 범용적이며 언어에 내장된 기능이 다양하고 프로그램을 빠르게 만들어낼 수 있는 효율적인 언어입니다.
그뿐만 아니라 익히기도 쉽고 코드 생김새 자체가 깔끔하여 입문용으로 제격인 언어입니다.  

이제 아래에는 대표적인 언어들을 공부하기 위한 소스들을 추천해드릴 것입니다.
그런데 이는 세부 설명을 보면 알겠지만, 입문서부터 고급서까지 다양하기 때문에, 필요에 따라 선택하여 학습하면 됩니다.
해당 언어로 입문하여 주 무기로 사용할 예정이라면 전부 읽으면 좋겠지만,
보조 무기로 사용할 것이라면 기초 서적만 봐도 무방합니다.
혹은, 이미 프로그래밍에 익숙해졌는데 특정 언어를 사용하게 됐다면 입문서를 건너뛰고 레퍼런스 북을 볼 수도 있습니다.

### Python

파이썬은 바로 위에 말한 대로 굉장히 범용적으로 쓰이는 언어입니다. 귀찮은 수작업을 자동화하기 위한 개인 툴부터 요즘 인기 많은 AI 분야나 대규모 네트워크 프로그램을 만드는 데에도 사용됩니다. 또한, IT 회사 입사를 위한 코딩 테스트에서 사용하면 가장 효율적이고 유리한 언어 중 하나입니다. 굉장히 장점이 많은 언어긴 하지만, 몇 가지 한계점 때문에 보조 무기로 익혀 두는 것을 추천합니다.
* [점프 투 파이썬](https://wikidocs.net/book/1) : 한국에서 전통적으로 유명한 파이썬 입문 자료입니다. Do It 종이책 시리즈로도 출판되었는데, 웹에서 무료로 볼 수 있습니다. 기초적인 파이썬 내용을 굉장히 쉽게 설명하므로 입문 자료로 사용하기 제격이며, 프로그래밍을 처음 하는 사람도 어렵지 않게 따라 할 수 있습니다. 다만, 파이썬의 세세한 내용을 설명하지는 않기 때문에 입문서 이상의 역할을 하기는 어렵습니다. 프로그래밍을 처음 접하는 분들에게 추천하며, 다른 언어를 공부한 경험이 있는 분은 바로 뛰어넘어서 아래 책으로 시작하는 것을 추천합니다.
* [처음 시작하는 파이썬](http://www.yes24.com/Product/Goods/91870652) : 세계적으로 유명한 파이썬 입문서 중 하나입니다. 점프 투 파이썬보다는 세세하게 설명하고 있으며 파이썬을 이용하여 응용 프로젝트를 만들어내는 내용도 조금 담고 있습니다. 파이썬 언어를 처음 공부하는 분들에게 추천해 드리는 서적입니다. 다만, 해당 책으로 프로그래밍 공부에 입문했는데 내용이 어려워 이해하기 힘들다면 위의 점프 투 파이썬을 한번 보고 오는 것을 추천해 드립니다.
* [Python Tutorial](https://docs.python.org/ko/3/tutorial/index.html) : 파이썬 공식 튜토리얼 사이트입니다. 고맙게도 한국어로 번역이 되어있습니다. 튜토리얼답게 기초적인 내용을 세세하게 설명하고 있지만, 공식 사이트답게(?) 내용이 굉장히 딱딱해서 재미가 없습니다. 프로그래밍 경험자가 파이썬을 처음 공부할 때 필요한 부분들을 찾아볼 경우에 추천해 드립니다.
* [러닝 파이썬](http://www.yes24.com/Product/Goods/59317494) : 파이썬에 대해 정말 세세하게 설명한 서적입니다. 위 서적이나 다른 자료들로 파이썬을 어느 정도 공부한 분들이 파이썬이라는 언어를 좀 더 깊게 공부하는 용도 혹은 레퍼런스 용도로 적합합니다. 비슷한 성격의 유명하고 좋은 서적으로 [파이썬 완벽 가이드](http://www.yes24.com/Product/Goods/6694057)가 있는데, 러닝 파이썬 서적이 조금 더 최신 내용까지 커버하고 있습니다.
* [전문가를 위한 파이썬](http://www.yes24.com/Product/Goods/30231768) : 파이썬을 좀 더 파이썬답게(Pythonic) 쓸 수 있도록 해주는 전문서입니다. 파이썬 언어에 대한 숙련도가 어느 정도 있으며, 파이썬으로 어느 정도 프로젝트를 진행해본 경험이 있는 분이 파이썬을 전문적으로 쓰기 위해서 공부할 자료입니다. 비슷한 성격의 좋은 서적으로 [파이썬 코딩의 기술](http://www.yes24.com/Product/Goods/94197582)이 있습니다.

### C

C언어는 태생이 UNIX라는 운영체제를 만들기 위하여 태어난 언어입니다. C언어가 세상에 나온 이후 오랜 시간 동안 많은 개발자에게 사랑을 받아왔으며, 지금도 임베디드나 시스템 분야에서 압도적인 점유율을 자랑하고 있습니다. 이후에 생겨난 매우 많은 언어들에 영향을 미쳤으며, 따라서 C언어를 익히고 나면 그로 인해 파생된 많은 언어를 좀 더 쉽게 익힐 수 있습니다.
또한, 굉장히 컴팩트한 문법 체계를 추구하여 언어의 문법 자체는 간결하기 때문에 많은 사람이 C언어를 입문용 언어로 배웠으며, 지금도 많은 대학에서 신입생들에게 첫 언어로 C언어를 가르치고는 합니다. 하지만 이 컴팩트한 문법 때문에, 사실 함정이 매우 많은 언어입니다. C언어로 프로그램을 작성할 때 자칫 잘못하면 내 컴퓨터 환경에서의 동작 결과와 친구 컴퓨터 환경에서의 동작 결과가 달라질 수 있습니다. 초보자 때는 별로 신경 쓰이는 내용이 아닐 수도 있지만, 사실 이런 것은 산업적으로 매우 큰 문제를 야기할 수 있기 때문에, C언어를 배운다면 다른 언어들보다 좀 더 신경 써서 정확하게 배워야 합니다. 이와 관련되어 좋은 포스트가 하나 있기에 [링크](https://sunyzero.tistory.com/225)를 첨부하는데, C언어를 공부할 분이라면 꼭 한 번쯤 읽어보길 권장합니다. C언어로는 주로 디바이스 드라이버, Board Support Package, OS, 미들웨어, 시스템 소프트웨어 등을 만들게 됩니다.
* [C Programming : A Modern Approach](http://www.yes24.com/Product/Goods/573769) : C언어를 공부하기 가장 적합한 책입니다. 아쉽지만 번역서가 없기 때문에 원서로 공부해야 합니다. '나는 영어를 잘 못 해서 한국어로 된 책으로 공부하고 싶은데...'라고 생각하시는 분이 있다면 위 선수 지식 영어 파트를 다시 한번 보시기 바랍니다. 정말 아쉽게도, 국내 서적 중에 C언어를 정확하게 설명하고 있는 입문서를 본 적이 없습니다. 따라서 C언어를 공부하고 싶다면 힘들더라도 어느 정도 영어를 익혀서 해당 책으로 공부하기를 권장합니다. (국내 입문서 중 C언어를 정확하게 설명하고 있는 책이 새로 나왔다고 한다면 이슈로 달아주시기 바랍니다. 그리고 나는 대충 공부하고 넘길거니까 그냥 국내 서적으로 볼거야 라는 생각하시는 분이 있다면, 잘못 알고있는 것이 모르는 것보다 위험하다는 것은 인지해두기를 바랍니다.)
* [The C Programming Language](http://www.yes24.com/Product/Goods/5928879) : C언어의 창시자들이 쓴 책입니다. 보면 알겠지만, 생각보다 굉장히 얇습니다. 하지만 그 안에는 C언어의 초기 설계 철학이 담겨있어서 C언어라는 언어 자체를 좀 더 깊이 이해하기에 적합한 책입니다. 그런데 사실 내용이 좀 구식이기 때문에, 단순 언어 학습을 위해서는 오히려 위의 C Programming 책을 더 추천합니다. 그 외에도 zlib같은 전통 있는 소스 코드를 보다 보면 옛날 스타일의 C언어를 접하게 되는데, 이런 소스 코드를 이해하는데에도 큰 도움을 줍니다.
* [C언어 펀더멘탈](http://www.yes24.com/Product/Goods/2935592) : 국내 유일하게 C언어를 정확히 설명한 책이지만, 절대 입문서는 아니고 더군다나 절판입니다. 추천 대상 독자는 '학교 다닐 때 C언어를 국내 서적으로 공부했는데, 어쩌다 보니 C언어로 일할 일이 생겼다.' 하시는 분이 자신이 알고 있는 C언어가 어떻게 잘못되어있는지 알기 위해 보면 정말 적절합니다. 다만 절판이다 보니 도서관에서 빌려봐야겠지요.
* [Linux Kernel](https://elixir.bootlin.com/linux/latest/source/fs/sysfs) : 위에 말한 듯이 C언어는 애초에 운영체제를 만들기 위하여 태어난 언어입니다. 이러한 C언어를 요즘 가장 잘 쓰고 있는 곳 중 하나가 바로 Linux라는 운영체제입니다. Linux 운영체제의 상당한 부분은 C언어로 작성되어 있습니다. 소스 코드를 보다 보면 요즘 스타일의 C언어를 어떻게 쓰고 있는지 확실히 알 수 있습니다. 예를 들어 시스템마다 유동적으로 사용될 구조체에 관련된 자료들과 함께 그 자료들을 제어할 함수 포인터를 두고, 해당 시스템에서 함수 포인터에 제어 함수를 등록하는 방식으로 흔히 객체 지향과 비슷한 방식의 소스 코드를 작성하는 모습도 굉장히 자주 볼 수 있습니다. 링크로는 커널 코드 중 공부용으로 참고하기 좋은 sysfs 소스 코드 부분을 달아두겠습니다.

### C++

처음에는 C언어에 Simula 언어의 객체지향 개념을 추가하여 만들어진 언어입니다. 그런데 이 언어는 시간이 지나며 너무 많은 기능을 추가하려고 하였고 결국 괴물이 되었습니다. 이제는 절대로 단순히 C언어에 Class를 추가한 언어가 아닌, 각종 패러다임을 집어넣은 만능 지향 언어라고 생각해야 합니다. 특히 C++11이라는 표준안부터는 정말 많은 신개념 패러다임과 기능들이 탑재되어 Modern C++이라고 불립니다. 언어적인 기능이 너무나도 방대하며 언어 자체의 난이도가 상당하기 때문에 입문용 언어로는 추천하지 않습니다만, 이 언어 하나만 정말 잘하면 다른 언어들을 좀 더 쉽게 익힐 수 있습니다. C++은 주로 성능이 중요시되는 프로그램을 만들 때 사용합니다. 영상 처리, 게임 제작, 고성능 서버, 웹 브라우저, GUI 데스크톱 환경 등 정말 다양한 곳에 사용합니다.

* [C++ Primer](http://www.yes24.com/Product/Goods/6285665) : C++을 처음 공부하는 입문서로 가장 좋은 책이라고 생각합니다. 1000페이지 정도의 두꺼운 책이지만 입문서가 맞습니다. (그만큼 C++의 기본 기능이 방대합니다) 간혹 C++ Primer Plus라는 책과 혼동되기도 하는데, (실제로 해당 서적도 좋은 책인 것은 맞습니다) 이 책이 더욱 C++를 자세히 설명해줄 뿐 아니라 올바르게 사용하는 방법부터 최신 기능을 왜 사용해야 하는지 등 더 추천할만합니다. 특히 저자인 Stanley Lippman은 C++ 창시자인 Bjarne옹의 제자(?)입니다.
* [Programming : Principles and Practice Using C++](http://www.yes24.com/Product/Goods/23207535) : C++ 창시자인 Bjarne StroupStrup이 학부생을 가르치기 위하여 쓴 서적입니다. 저자인 비야네옹은 프로그래밍 입문을 위한 서적이라고 말씀하시지만, 솔직히 입문서로 쓰기엔 다소 어렵습니다. 추천하는 대상은 프로그래밍을 조금 공부해본 학부생 1~3학년 정도 수준일 때 프로그래밍 스킬을 조금 더 업그레이드시키는 겸 C++을 공부하려고 하면 이 책이 굉장히 좋습니다. 분명 입문서인데 연습문제가 잘 풀리지 않아도 정상이니 좌절하지 마시기 바랍니다. (해당 책의 연습문제들을 다 풀 수 있다면 프로그래밍 스킬에 굉장히 숙련되어 있을 것입니다.)
* [Effective C++](http://www.yes24.com/Product/Goods/17525589) : 구형 C++을 효율적으로 쓰기 위한 필독서입니다. Effective 시리즈의 시조 같은 책인데, 'C++라는 언어를 이렇게는 쓰면 안 되고 이런 식으로 써야 한다'는 것을 조금이나마 깨닫게 해주는 책입니다. 추천하는 대상은 C++ 언어로 일을 해야 하거나 C++ 언어를 잘하고 싶은 모든 분입니다. (사실 이 책 이후에 더욱더 깊게 공부하는 More Effective C++이라는 책도 있지만, Modern의 시대가 열려서 해당 책은 Optional 합니다.)
* [Effective Modern C++](http://www.yes24.com/Product/Goods/20288684) : Modern C++을 사용할 분들이 필수적으로 봐야 하는 필독서입니다. C++로 일을 하거나 C++ 언어를 잘 쓰고 싶다는 분들은 예외 없이 봐야 할 책입니다.
* [The C++ Programming Language](http://www.yes24.com/Product/Goods/23441719) : C++ 창시자인 비야네옹이 쓴 책으로, 레퍼런스 서적입니다. 사실 C++는 아래 사이트에 레퍼런스가 잘 되어있기 때문에 해당 책은 좀 Optional하긴 하지만, C++ 언어에 어느 정도 익숙해 졌을 때 이 언어의 철학을 느끼며 내용을 정리하려는 분들이 공부하기 좋은 책입니다.
* [cppreference](https://en.cppreference.com/w/) : C++ 레퍼런스 사이트입니다. 예를 들어 C++의 std::vector에 무슨 기능이 있고 어떻게 사용해야 하는지 찾아야 한다면 다음 [링크](https://en.cppreference.com/w/cpp/container/vector)를 참조하면 됩니다.
* C++로 만든 프로그램으로는 [구글 크롬](https://chromium.googlesource.com/chromium/src/)을 포함한 수많은 구글 어플리케이션, [비트코인](https://github.com/bitcoin/bitcoin), 리그 오브 레전드, [QT](https://github.com/qt), [KDE](https://github.com/KDE), IE/Office/그림판 등 마이크로소프트 어플리케이션 등이 있습니다.

### Java

Java는 대표적인 객체 지향 프로그래밍 언어입니다. JVM이라는 가상 머신 위에서 돌아가기 때문에 크로스 플랫폼 언어라고도 합니다. 이 언어의 가장 주요한 특징으로는 한국에서 압도적으로 많이 사용하는 언어라는 것입니다. 한국에서 개발자로 취업하기 위해서는 몇 분야를 제외하고는 거의 필수적으로 잘 알아야 하는 언어입니다. (특히 Spring Framework와 함께 잘 알아둬야 합니다.) 자바는 주로 웹 서비스를 개발하거나 안드로이드 애플리케이션을 개발할 때 사용합니다.
* [Java의 정석](http://www.yes24.com/Product/Goods/24259565) : 한국에서 전통적인 Java 입문서입니다. 비슷한 성격의 책으로는 [이것이 자바다](http://www.yes24.com/Product/Goods/15651484)나 [자바의 신](http://www.yes24.com/Product/Goods/42643850)이 있습니다. Java의 정석 책이 주변에서는 평이 가장 좋긴 한데, 서점이나 도서관에서 대충 훑어보며 셋 중 가장 마음에 드는 책으로 골라도 크게 상관은 없습니다. 어차피 기본서의 한계가 있기 때문에 문법을 확실히 익히고 난 후에 다른 자료들로 더욱 공부할 필요가 있습니다.
* [Effective Java](http://www.yes24.com/Product/Goods/65551284) : 유명한 Effective 시리즈 중 하나로 Java를 더욱 효율적으로 사용하기 위한 전문서입니다. Java 또한 C++11 이후에 큰 변화가 있던 것처럼 7버전 이후에 점점 변화가 생겨왔습니다. 해당 서적에는 이런 변화까지 포함하여 Java를 어떻게 해야 잘 쓸 수 있는지 가이드해줍니다. 사실상 Java로 일을 하기 위한 필독서입니다.
* [토비의 스프링](http://www.yes24.com/Product/Goods/7516911) : 사실 Java라는 언어가 아닌 Spring Framework에 관련된 서적입니다. 하지만 사실 한국에서 Java로 일을 하게 되면 대부분 해당 프레임워크를 사용할 것이기에 함께 공부해두면 좋습니다. 국내 Spring 서적 중 가장 유명하고 자세한 서적이 아닌가 싶습니다만 신간이 3.1 구버전임을 감안해야 합니다.

### Javascript

Javascript는 주로 웹 브라우저에서 동적인 페이지를 구성해주기 위한 언어입니다. 최근엔 용도가 늘어나 Node.js와 같이 서버 프로그래밍에도 사용하긴 하지만 기본은 동적 웹 페이지 구성을 위한 언어입니다. 참고로 Javascript는 위의 Java 언어와 관련이 없습니다. Java 언어를 스크립트 언어로 만든 것이 절대 아니므로 Java와 호환되지 않으니 혼동하지 마시기 바랍니다. 결론적으로 Javascript는 주로 웹 개발을 할 때 사용합니다.
* [생활코딩! HTML+CSS+자바스크립트](http://www.yes24.com/Product/Goods/67883315) : 생활코딩으로 유명한 이고잉님의 웹 프론트 입문서입니다. 프로그래밍을 처음 시작하는 분 중에 웹개발로 시작해보고 싶은 분에게 굉장히 추천합니다. 
* [인사이드 자바스크립트](http://www.yes24.com/Product/Goods/11781589) : 자바스크립트 동작 원리를 좀 더 자세하게 설명해주는 책입니다. 책이 굉장히 얇음에도 불구하고 자바스크립트 핵심 개념들을 명확하게 설명해줍니다. 자바스크립트를 공부한 적이 있는 분이 좀 더 자세한 언어 동작 원리를 공부하려고 할 때 추천합니다.
* [자바스크립트 완벽 가이드](http://www.yes24.com/Product/Goods/24769929) : 자바스크립트의 거의 모든 것을 설명해 둔 레퍼런스 책입니다. 자바스크립트 코뿔소 책이라는 명칭으로 유명합니다. 자바스크립트라는 언어의 기능과 동작 원리를 정말 상세하게 공부하고 싶은 분에게 추천합니다.
* [자바스크립트는 왜 그 모양일까?](http://www.yes24.com/Product/Goods/90283410) : 자바스크립트의 대가 더글러스 크락포드의 저서입니다. 저자의 다른 저서로 [자바스크립트 핵심 가이드](http://www.yes24.com/Product/Goods/3071412)라는 좋은 책이 있는데, 절판입니다. 해당 서적은 자바스크립트를 어떻게 해야 잘 쓸 수 있는지 가이드해주는 책으로 자바스크립트로 개발하려고 하는 분들은 필수적으로 봐야 할 서적입니다. 위의 코뿔소 책은 Optional이라면 해당 책은 자바스크립트로 개발하려는 분들에게 필수입니다.
* [자바스크립트는 모든 곳에 존재한다](http://www.yes24.com/Product/Goods/97125368) : 최근 사용처가 늘어난 자바스크립트를 어떻게 다양하게 쓸 수 있는지 가이드해주는 책입니다. 자바스크립트로 개발을 하려는 모든 분들에게 굉장히 추천하는 책입니다.

### C#

C#은 마이크로소프트에서 개발한 객체지향 언어입니다. C 계열의 언어는 맞지만 오히려 Java 언어와 비슷합니다. 여러 언어의 장점을 흡수해 언어적인 완성도가 우수하며, 지속적으로 업데이트 되고 있는 새로운 기능 또한 [MS DOCS](https://docs.microsoft.com/ko-kr/dotnet/csharp/whats-new/)에서 쉽게 확인할 수 있습니다. 태생이 .NET이라는 프레임워크의 한 부분으로 만들어진 언어여서 .NET 플랫폼에 크게 의존하지만 Unity 등의 스크립트 언어로도 사용합니다. 따라서, C#은 주로 .NET 프레임워크를 이용하여 윈도우 애플리케이션을 개발하거나, Unity에서 게임을 개발할 때 사용합니다. 물론, Mono와 .NET Core 덕분에 범용성이 크게 증가하여 다양한 곳에서 사용할 수는 있습니다.
* [이것이 C#이다](http://www.yes24.com/Product/Goods/96674785) : 최신 버전인 C# 9.0을 반영한 입문서입니다. 비슷한 성격의 서적으로는 [시작하세요! C# 9.0 프로그래밍](http://www.yes24.com/Product/Goods/97314203)이 있으니 서점 등에서 비교하여 마음에 드는 책으로 골라 공부해도 좋습니다. C#을 처음 공부하려는 분들에게 추천합니다.
* [C# 6.0 완벽 가이드](http://www.yes24.com/Product/Goods/33085047) : C# 언어를 정말 상세하게 설명한 서적으로 언어의 세부적인 기능을 자세하게 공부할 수 있습니다. 6.0 버전까지만 커버하지만 해당 내용으로도 언어의 깊은 내용을 알 수 있습니다. 언어의 기능을 상세하게 공부하고 싶거나 레퍼런스로 사용하려는 분들에게 추천합니다.
* [이펙티브 C#](http://www.yes24.com/Product/Goods/55864866) : 이번에도 유명한 Effective 시리즈 중 하나로 C#을 더욱 효율적으로 쓸 수 있게 해주는 전문서입니다. 위의 완벽 가이드 책은 Optional 하지만, 해당 책은 C#으로 개발을 하려는 분들에게 필수입니다. C#을 이미 어느정도 공부한 적이 있는 분들이 이 언어로 일을 하기 위해 언어 숙련도를 높이려고 할 때 추천합니다.

### etc.

* Rust
* Swift : Apple사의 플랫폼(macOS, iOS, watchOS, tvOS)을 위한 프로그래밍 언어입니다.
* Kotlin : JetBrains 에서 개발한 JVM 기반의 언어입니다. 2017년에 안드로이드 공식 언어로 채택되었습니다. 장황한 문법을 지닌 Java에 비해 비교적 간결한 문법을 제공합니다. 

## Fundamental Technique

컴퓨터공학/컴퓨터과학의 뼈대를 이루는 기술들이 있습니다. 흔히 컴퓨터 학과 학부 과정의 전공과목인 알고리즘, 컴퓨터구조, 운영체제 등으로 이를 기반 기술이라고 하겠습니다. 사실 요새는 개발 프레임워크 / 개발 플랫폼 등이 너무나도 많이 발전하고 하드웨어 및 최적화 기술의 엄청난 향상에 힘입어 굉장히 추상화된 컴포넌트들을 가지고 간편하게 개발할 수 있게 되었습니다. 그러다 보니 이런 기반 기술들보다는 점유율 높은 프레임워크 사용법이나 요새 핫한 신기술에 좀 더 관심을 두는 양상이 보입니다. 그런 일이 잘못된 것은 아니지만, 기본의 중요성을 간과하지 말았으면 합니다. 후술할 공부 방식 중 Top-Down 방식의 학습을 한다면 기본적인 내용을 뛰어 넘어가며 필요할 때 필요한 내용을 공부하게 될 텐데, 그렇다 하더라도 최종적으로 기본들에 대한 지식이 없다면 속이 빈 강정이 되어 속히 말하는 야매 개발자가 될 확률이 높습니다.
그리고 사실 최신 기술들도 하늘에서 뚝 떨어진 것이 아니라 이런 기반 기술들로부터 영향을 받아 만들어지고 발전한 것입니다. 알고리즘 공부를 열심히 하다가 인공지능을 공부하면 똑같은 내용이 그대로 등장하며, 컴파일러를 공부하고 자연어 처리를 보면 친숙한 내용이 반갑게 맞아줍니다. 운영체제를 공부하며 숨 쉬듯이 보던 컨셉들을 응용 프로그램 개발에서 그대로 볼 수 있습니다. 그러니 최신 기술들에 현혹되어 컴퓨터학과에 입학하신 분 중 이러한 과목들을 공부하며 재미가 없다고 실망하시는 분이 있다면 결국 이러한 내용이 기반이 되는 것들이므로 생각을 다잡으시기 바랍니다.

### Algorithm

알고리즘은 어떠한 문제를 해결하기 위한 절차의 표현으로 Computer Science의 큰 기초가 되는 과목 중 하나입니다. 효율적인 프로그래밍의 근간이 되어주고, AI와 같은 다양한 분야의 근본적인 기술입니다. 특히나 MS와 Google로 시작한 Coding Interview(코딩 테스트)가 국내에도 크게 유행하고 있기에 입사를 위해서 신경 써 공부해야 할 과목입니다.
그런데 학술적인 연구를 위한 알고리즘, 실무에서 사용하는 알고리즘, PS(Problem Solving) 대회를 위한 알고리즘, 코딩 테스트를 위한 알고리즘 등 분야별로 다루는 내용이 크게 달라지기 때문에 목적에 맞춰서 효율적인 공부가 필요합니다.
실무에서 사용하는 알고리즘은 어떤 회사에서 어떤 제품을 개발하는지에 따라 천차만별이기에 제외하고 아래에는 학술, 코딩 테스트, 대회를 위한 공부 리소스들을 설명하겠습니다. 사실 코딩 테스트와 대회를 위한 알고리즘은 공부하는 내용이 굉장히 유사하지만, 대회를 위한 공부가 훨씬 넓은 범위를 깊게 파고들어야 한다는 차이가 있습니다.

#### Academic

* [Foundations of Algorithms](http://www.yes24.com/Product/Goods/11999564) : 아래 책과 함께 학부 알고리즘 수업에 가장 많이 사용되는 바이블입니다. 사실 알고리즘 공부를 한다고 하면 대부분 학술적인 내용보다는 코딩 테스트나 대회를 위한 알고리즘 공부를 할 테지만, 순수하게 알고리즘을 공부해보고 싶은 분들에게는 해당 서적을 추천합니다.
* [Introduction to Algorithms](http://www.yes24.com/Product/Goods/13776831) : CLRS로도 불리는 이 책은 오랜 세월 동안 많은 대학의 교재로 사용되어 왔습니다. 알고리즘의 바이블이지만 개인적으로는 독학용으로는 위의 Foundations of Algorithms를 더 추천해 드리며, 해당 서적은 레퍼런스로 사용하는 것을 추천해 드립니다.
* [The Art of Computer Programming](http://www.yes24.com/Product/Goods/13776831) : Donald Knuth 교수가 집필 중인 서적으로, 알고리즘의 끝판왕이라고 할 수 있습니다. 해당 서적을 다 이해하기만 하더라도 빌 게이츠가 마이크로소프트에 특채하겠다고 할 정도로 극악무도한 난이도로 유명합니다. 컴퓨터과학의 근간은 수학이라는 것을 여실히 보여주는 것처럼 굉장히 수학적인 내용으로 구성되어 있습니다. 솔직히 말해서 순수한 학습용은 아닌 것 같습니다.. (저는 보는 것을 포기하여 책장 장식용으로 사용하고 있습니다) 알고리즘을 전공할 분들에게 추천해 드려봅니다.
* [Project Euler](https://projecteuler.net/) : 유명한 PS 플랫폼으로 여타 다른 플랫폼과는 다르게 수학 문제를 해결하는 사이트입니다. [한국어 번역 사이트](https://euler.synap.co.kr/)도 있지만 몇 기능과 문제들이 넘어오지 않았습니다. 수학 문제들을 프로그래밍을 통해 해결해보고 싶은 분들에게 추천합니다.

#### Coding Interview (Coding Test)

* [파이썬 알고리즘 인터뷰](http://www.yes24.com/Product/Goods/91084402) : 코딩 테스트를 위한 알고리즘 공부 입문으로 굉장히 좋은 서적입니다. 비슷한 성격의 서적으로는 [이것이 취업을 위한 코딩 테스트다 with 파이썬](http://www.yes24.com/Product/Goods/91433923)이 있습니다. 알고리즘 공부를 전혀 해보지 않은 상태에서 인터넷에서 유명한 백준이나 프로그래머스 문제 풀이부터 하려고 하면 굉장히 막막할 것입니다. 이러한 서적을 한번 보면서 어떤 자료구조와 알고리즘들을 어떤 식으로 사용하는지 형식을 잡고 들어가면 굉장히 효율적으로 공부할 수 있습니다.
* [프로그래머스](https://programmers.co.kr/) : 국내에서 많이 사용하는 코딩 테스트 플랫폼 사이트입니다. 많은 회사들이 해당 플랫폼을 사용하여 코딩 테스트를 진행하기 때문에 미리 익숙해지면 굉장히 좋습니다. 질 좋은 문제들과 카카오 기출 문제들을 풀어볼 수 있으며 Level 3, 4 정도의 문제를 풀 수 있으면 코딩 테스트 준비가 잘 되었다고 생각할 수 있습니다. 유일한 단점으로는 문제 수가 좀 적습니다.
* [LeetCode](https://leetcode.com/) : 유명한 해외 PS 플랫폼입니다. 양질의 문제가 매우 많으며 구글, 아마존, 페이스북, 넷플릭스 등 해외 기업들의 기출 문제들도 풀 수 있습니다. 위의 파이썬 알고리즘 인터뷰 서적 또한 해당 플랫폼에 있는 문제들을 풀이하며 설명합니다. 흔히 코딩 테스트 양치기를 하기에 가장 좋은 플랫폼 중 하나입니다.

#### Competition

* [알고리즘 문제 해결 전략 세트](http://www.yes24.com/Product/Goods/8006522) : 종만북으로 유명한 이 책은 알고리즘 대회를 준비하는 분들에게 필독서가 아닌가 싶습니다. 저자의 노하우가 책에 잘 녹아있고 대회에 필요한 알고리즘들을 잘 설명해줍니다. 하지만 굉장히 어려운 난이도로 많은 사람들에게 좌절을 안겨준 서적이기도 합니다. 단순히 입사를 위한 코딩 테스트 준비로 이 서적을 보는 것은 솔직히 크게 추천드리지는 않습니다. 알고리즘 대회를 준비하는 분들이나 자신의 PS 실력을 향상하고 싶은 분이 단단한 뼈대를 만들고 싶을 때 공부하는 것을 추천합니다.
* [백준 온라인 저지](https://www.acmicpc.net/) : 국내에서 가장 유명한 PS 플랫폼입니다. 문제 양이 정말 굉장히 많으며 지원하는 프로그래밍 언어도 매우 많습니다. 국내외 알고리즘 대회 기출 문제나 삼성 코딩 테스트 기출 문제도 풀 수 있습니다. 대회를 준비하시는 분들에게는 거의 필수적인 플랫폼입니다. (사실 대회 준비하시는 분이 해당 사이트를 모를 수가 없긴 합니다.)
* [CodeForces](https://codeforces.com/) : 이 또한 세계적으로 유명한 PS 플랫폼인데, 코딩 테스트보다는 대회 준비에 좀 더 적합한 사이트입니다. 백준 사이트와 연동이 가능하며 국제 대회를 준비하는 경우 필수적으로 이용하게 되는 사이트입니다. 전반적인 문제 난이도가 높습니다.
* [알고스팟](https://www.algospot.com/) : 알고리즘 문제 해결 전략 서적이 해당 사이트의 문제들을 풀이하며 설명합니다. 전반적인 문제 난이도가 굉장히 높습니다. [튜토리얼](https://www.algospot.com/wiki/read/%EC%95%8C%EA%B3%A0%EC%8A%A4%ED%8C%9F_%EC%98%A8%EB%9D%BC%EC%9D%B8_%EC%A0%80%EC%A7%80)을 보면 알겠지만 초보자용 문제도 꽤나 난이도가 있는 편입니다.

### Computer Architecture

* [Computer Organization and Design](http://www.yes24.com/Product/Goods/12716580) : 많은 대학에서 사용하는 컴퓨터 구조의 바이블입니다. [RISC-V 버전](http://www.yes24.com/Product/Goods/68370956)도 나와 있습니다.
* [프로그래머가 몰랐던 멀티코어 CPU 이야기](http://www.yes24.com/Product/Goods/3858484) : 컴퓨터 구조 이론들을 굉장히 쉽게 풀어 써준 서적입니다. 현대 컴퓨터 구조를 이해하는데 필요한 내용을 이해하기 쉽게 설명해준 좋은 서적인데 정말 아쉽게도 절판입니다. 개인적으로 컴퓨터구조를 공부한 적이 없는 채로 프로그래밍을 하는 모든 분이 읽어봤으면 하는 서적입니다. 도서관에서 빌려서라도 볼 수 있다면 좋겠습니다.
* [프로세서를 지탱하는 기술](http://www.yes24.com/Product/Goods/5903582) : 위의 멀티코어 CPU 이야기와 약간 비슷한 성격의 서적인데 좀 더 프로세서의 근간이 되는 내용을 설명해줍니다. 마찬가지로 굉장히 좋은 서적이지만 아쉽게도 절판입니다. 혹시 도서관에서 빌려볼 수 있다면 한번 읽어보기를 추천합니다.

### System Programming

* [UNIX 고급 프로그래밍](http://www.yes24.com/Product/Goods/14528020) : APUE라고 불리는 이 책은 시스템 프로그래밍 전통의 바이블입니다. 전반적인 UNIX-like 환경에서의 시스템 콜 프로그래밍과 주의사항 등을 설명합니다. 시스템 개발을 공부하려는 분들에게 사실상 필독서입니다.
* [리눅스 API의 모든 것](http://www.yes24.com/Product/Goods/7225056) : 원제 The Linux Programming Interface인 이 책은 위의 APUE와 비슷하지만 좀 더 리눅스 환경에 집중되어있고, 내용이 신식입니다. 비록 고 Stevens의 APUE가 공신력으로는 가장 알아주지만, 해당 서적도 리눅스 매뉴얼 페이지를 작성한 Kerrisk의 저서로 그에 못지 않은 편입니다. APUE도 그렇지만 몇 구현 연습문제 난이도가 꽤 상당합니다. 리눅스 환경에서의 시스템 프로그래밍을 공부하고 싶은데 APUE가 싫다면 해당 서적을 추천합니다.
* [Advanced! 리눅스 시스템 네트워크 프로그래밍](http://www.yes24.com/Product/Goods/26902320) : 굉장히 좋은 시스템 프로그래밍 실무 지침서로 저자분의 노하우가 잘 들어가 있습니다. 개념서로 활용해도 좋지만, 위의 APUE나 TLPI 서적으로 개념들을 익히고 해당 서적으로 이러한 개념들을 어떻게 실무 개발에 적용할지 익히는 게 가장 좋을 거 같습니다. 개인적으로, APUE와 해당 서적을 한 번씩 정독한 후 공부한 내용을 활용하여 다중 클라이언트에 동시 서비스되는 웹 프록시 서버를 하나 만들 수 있다면 시스템 프로그래밍에 어느 정도 익숙해졌다고 생각해도 될 것 같습니다.

### Design Pattern

* [Head First Design Patterns](http://www.yes24.com/Product/Goods/1778966) : 유명한 디자인 패턴 입문서입니다. 사실 개인적으로 Head First 시리즈를 선호하는 편은 아니지만, 디자인 패턴만큼은 패턴들을 이해하고 익히기 좋은 예제로 잘 구성되어 있어서 예외로 두고 있습니다. 아래 GoF 서적이 디자인 패턴의 바이블이긴 하지만, 내용이 딱딱하고 일부 이해하기 쉽지 않아서 디자인 패턴을 처음 공부할 시에는 해당 서적으로 공부하는 것을 추천합니다. 참고로 디자인 패턴을 적용할 일이 많은 java로 작성되어 있습니다.
* [GoF의 디자인 패턴](http://www.yes24.com/Product/Goods/17525598) : 디자인 패턴의 바이블입니다. 참고로 GoF는 Gang of Four이라고 불리는 Gamma, Helm, Johnson, Vlissides를 줄인 것입니다. 디자인 패턴을 처음 공부하시는 분들보다는, 디자인 패턴을 한 번 정도 공부한 적이 있고 이제 실제 코드에 적용하려고 할 때 레퍼런스가 필요한 경우 해당 서적을 참고하는 것을 추천해 드립니다. 참고로 C++ 언어를 기반으로 작성되어 있습니다.

### Operating System

* Operating System Concepts
* [64비트 멀티코어 OS 원리와 구조](http://www.yes24.com/Product/Goods/65061299)

### Network

* [TCP/IP가 보이는 그림책](http://www.yes24.com/Product/Goods/73020774)
* [후니의 쉽게 쓴 시스코 네트워킹](http://www.yes24.com/Product/Goods/89520426)
* [TCP/IP Illustrated](http://www.yes24.com/Product/Goods/4739649)

### Web

* [HTTP 완벽 가이드](http://www.yes24.com/Product/Goods/15381085)
* [모던 웹 애플리케이션 개발](http://www.yes24.com/Product/Goods/86038744)

### Database

* [파워 오브 데이터베이스](http://www.yes24.com/Product/Goods/69775589)

## Professional Technique

### Android Application

* [Android Developers Guide](https://developer.android.com/guide)
* [프로페셔널 안드로이드](http://www.yes24.com/Product/Goods/80771938)

### iOS Application

* [Do it! 스위프트로 아이폰 앱 만들기 입문](http://www.yes24.com/Product/Goods/96686142)
* [Apple Developer](https://developer.apple.com/develop/)

### Game

### Embedded System

* [사물인터넷을 위한 리눅스 프로그래밍 with 라즈베리 파이](http://www.yes24.com/Product/Goods/89306782)
* [Raspberry Pi User Guide](http://www.yes24.com/Product/Goods/57750662)
* [임베디드 OS 개발 프로젝트](http://www.yes24.com/Product/Goods/84909414)
* [임베디드 RTOS 입문서 세트](http://www.yes24.com/Product/Goods/2887923)
* [임베디드 엔지니어 교과서](http://www.yes24.com/Product/Goods/91226909)
* [Yocto 프로젝트를 활용한 임베디드 리눅스 개발](http://www.yes24.com/Product/Goods/63826178)

### System Engineering

* [서비스 운영이 쉬워지는 AWS 인프라 구축 가이드](http://www.yes24.com/Product/Goods/68799454)
* [따라하며 배우는 AWS 네트워크 입문](http://www.yes24.com/Product/Goods/93887402)
* [DevOps와 SE를 위한 리눅스 커널 이야기](http://www.yes24.com/Product/Goods/44376723)
* [카프카, 데이터 플랫폼의 최강자](http://www.yes24.com/Product/Goods/59789254)
* [엔터프라이즈 데이터 플랫폼 구축](http://www.yes24.com/Product/Goods/90634328)

### Software Engineering

* [리팩토링](http://www.yes24.com/Product/Goods/89649360)
* [클린 코드 + 클린 아키텍처](http://www.yes24.com/Product/Goods/77988880)
* [실용주의 프로그래머](http://www.yes24.com/Product/Goods/12501565)
* [조엘 온 소프트웨어](http://www.yes24.com/Product/Goods/1469763)

### Security

## Study

### HOW TO

### Bottom Up

### Top Down

### Roadmap

## Projects

### 개인 프로젝트

### 대외 활동

* [차세대 보안리더 양성 프로그램](https://www.kitribob.kr)
* [SW 마에스트로](https://www.swmaestro.org)
* [Microsoft Learn Student Ambassadors](https://studentambassadors.microsoft.com/)
* [Github Campus Experts](https://education.github.com/experts)

### 해커톤

### 대회

## Comments

### Community

#### 개발 관련 커뮤니티 리스트

#### 커뮤니티 이용법

* 질문하는 방법

### Q&A

### 조언

각 분야의 시니어 개발자 분들이 주니어 개발자 혹은 뉴비분들에게 드리고 싶은 조언란입니다.  
시니어 개발자님들의 PR 감사히 받겠습니다.

ex)
```
한국에서 취업하려면 자바, 스프링, AWS 공부하고 코테 준비 잘 하세요 - 익명
```
```
이곳은 고인물 파티야, 도망치세요 - 익명
```
```
프로그래밍은 단거리 경주가 아닌 마라톤입니다 - 익명
```

#### Web

#### System

#### Embedded

#### Network

#### Game
