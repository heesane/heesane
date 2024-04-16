[##_Image|kage@btCTy0/btsGBhtxIUY/UsJWYKeVF8jej8buvxFtuk/img.png|CDM|1.3|{"originWidth":1196,"originHeight":3054,"style":"alignCenter"}_##]

## 개요

많은 사람들이 백엔드로 취업을 원할 때, 가장 많이 검색하는 키워드가 뭘까?

내 생각으로는 어떤 것을 공부해야 할 지에 대한 검색 키워드가 가장 많을 것 같다.  
그렇다면 연관 검색 키워드로 로드맵과 같은 것들이 보일 텐데, 위의 사진과 같은 구조의 글들이 많을 것 같다. 

밑에서 하나씩 다뤄보면서 내 생각에 관한 내용들을 정리해볼 예정이다.

---

[##_Image|kage@dyVX4M/btsGBRg4hKu/K5zw3VsQYQaF4oxiV2vWMK/img.png|CDM|1.3|{"originWidth":1151,"originHeight":446,"style":"alignCenter"}_##]

위의 백엔드 로드맵을 예시로 들면, 가자 먼저 인터넷에 관한 지식들을 먼저 학습하라고 한다.

어떤 이유에서 인터넷 지식들을 학습하라고 하는 것일까?

내 생각으로는, 백엔드라는 것은 웹 서비스를 운영할 때 반드시 필요한 요소일 것이다. 웹이라는 것은 기본적으로 인터넷 위에서 동작하기 때문에, 가장 기초적인 인터넷에 관한 지식들을 학습하는 것을 권장한다고 생각한다.

다음으로는 짧게나마 프론트엔드에 관한 지식을 배워, 추후에 자신이 직접 작성한 API를 테스트할 수 있도록 하는 것 같다.

---

[##_Image|kage@pVwfU/btsGBc0ln2a/IeX3q0S1hDTu7YcYMcpy5K/img.png|CDM|1.3|{"originWidth":1080,"originHeight":314,"style":"alignCenter"}_##]

백엔드는 기본적으로는 Ubuntu, RedHat, OpenSuSe와 같은 Linux 기반의 서버 아래에서 동작하기 때문에, 터미널을 사용하는 방법, 프로세스, 스레드, 메모리, 동시성과 같은 OS 지식들을 배우고 학습하기를 권장하는 것 같다.

---

[##_Image|kage@bn9xYj/btsGAM8H5C4/y9FOeIWuxKobB4xcwhjmB1/img.png|CDM|1.3|{"originWidth":851,"originHeight":168,"style":"alignCenter"}_##]

이제야 비로소 프로그래밍 언어에 관한 지식을 습득할 차례이다.

특히, 여기서 JavaScript에 보라색 마크가 새겨진 것을 확인할 수 있는데, 내 개인적인 생각으로는 백엔드를 배워서 취업을 하더라도 프론트에 관한 지식을 빼놓을 수는 없을 것이고, 프론트엔드는 주로 JavaScript 언어로 작성된다. 이에 따라 해당 로드맵을 작성하신 분은 이러한 이유로 추천 마크를 달아 둔 것 같다. 나머지 언어들은 주로 백엔드 서버를 운영할 수 있는 언어들로 리스트 되어 있다.

특히, 한국에서 백엔드 개발자로 살아남고 싶다면 Java를 하는 것을 적극 추천한다. 나도 Python으로 시작했다가 지금은 Java에 대해서 학습하는 중에 있다.

---

[##_Image|kage@cw2TQh/btsGCY7p2DN/PL36uCikh8ryqG9yEr3ENK/img.png|CDM|1.3|{"originWidth":1137,"originHeight":189,"style":"alignCenter"}_##]

다음은 **Git**과 관련된 부분이다. 해당 부분은 매우 중요한데, 개발자로서 어느 회사에 가더라도 버전 관리에 대한 필요성을 두말할 필요도 없이 중요하다. 왜냐하면, 업데이트 버전에 버그나 이슈가 발생할 경우 롤백의 필요성이 존재하는데, 이런 소스코드를 로컬에 저장할 경우 유실될 가능성이 존재하며, 동료와 함께 공유하고 협업을 진행하기에 상당히 어렵기 때문에 Git과 관련된 지식을 보다 우선적으로 학습하는 것을 권장한다.

---

[##_Image|kage@bFa604/btsGCa1x3zC/xrunNjM1RHjqRkoAgd0Y21/img.png|CDM|1.3|{"originWidth":1178,"originHeight":368,"style":"alignCenter"}_##]

다음은, 데이터베이스에 관한 지식이다.

데이터 베이스에는 크게 2가지의 시스템이 존재한다. A라는 객체에 대한 정보를 표로써 정리하는 것은 관계형 데이터베이스 시스템, 단순한 하나의 객체로 관리하는 것은 비관계형 데이터베이스 시스템이라고한다. 

**관계형 데이터베이스에서는 PostgreSQL**을 추천하는데, 기존에는 사실 MySQL을 더 많이 썼다. 하지만 최근 PostgreSQL에서 다양한 기술들을 많이 릴리스하는 편이기도 하고 가장 강력한 장점인 pgadmin을 사용할 수 있다는 점이 부각되면서 2024 백엔드 로드맵에서는 해당 데이터베이스를 추천하는 것 같다.

**NoSQL 데이터 베이스에서는 MongoDB**를 추천하는데, MongoDB는 도큐먼트형식으로 데이터를 저장하는 방식의 데이터베이스이다.

나도 개인적으로 배워본 적이 없어, 최근에 해당 데이터베이스를 공부하기 위한 책을 구매하여 공부하고 있다.

더 깊은 지식으로는 **ORM, ACID, Transaction, N+1, 정규화, 인덱스**와 같은 지식들이 존재하고, **Sharding, Replication, CAP**과 같은 고급 지식들이 리스트 되어 있다.

추후에 지속적으로 공부를 하게 되면서, 자연스럽게 접하게 될 예정이라 해당 포스팅에서는 다루지 않겠다. 그냥 "이런 것들이 있구나"까지만 생각하고 넘어가도 좋을 것 같다.

---

[##_Image|kage@eyiDMs/btsGCuFvatS/563GBtABg0kKRA9IxsGD20/img.png|CDM|1.3|{"originWidth":1122,"originHeight":243,"style":"alignCenter"}_##]

다음으로는 API에 대해서 학습을 진행한다.

구글이나 네이버 등 다양한 플랫폼에서 API를 검색해 보면 REST API라는 말을 상당히 자주 접하게 될 것인데, 개발자로 취업하기를 원한다면 당연하게 배워야 하는 것이라고 생각하면 좋을 것이다. 또한, Json API, SOAP, gRPC와 같은 종류의 API도 존재한다.

이 부분에서 가장 중요한 부분은 인증 관련 부분인데, 이 부분만 해도 상당히 어렵다.

인증에 대해서 가장 기본적인 부분으로는 Token방식의 인증, Cookie방식의 인증, Session방식의 인증이 존재한다.

특히 **최근에는 Stateless 한 Token방식인 JWT**를 많이 사용하는 추세인 것 같다. 물론 OAuth 역시 많이 사용된다.

---

[##_Image|kage@UX2z8/btsGAMOn20Q/MNfx7pnCURsHFBxkTqgJo1/img.png|CDM|1.3|{"originWidth":553,"originHeight":147,"style":"alignCenter"}_##]

다음은 캐시에 관한 지식이다.

캐시 부분에서는 CDN, 서버사이드, 클라이언트 사이드로 나뉘며 서버사이드는 Redis, Memcached가 있다.

백엔드 개발자라면 AWS, Azure, Google과 같은 호스팅 서비스를 통해서 개발한 내용을 배포하게 된다. 

그러다 보면 이러한 서버들은 주로 해외에 존재하게 되는데, 한국에서 요청을 보낼 경우, 실질적인 거리로 인해서 딜레이가 발생하게 된다.

이러한 점을 극복하기 위해서 CDN을 사용하게 된다. AWS의 경우, 한국에 존재하는 서버를 통해서 사용자에게 정보를 전달하게 된다.

만약 똑같은 요청이 들어올 때, 해외를 경유한다면 오랜 시간이 걸리게 될 것이므로, 한국에 있는 서버에 캐싱을 통해서 더 빠르게 정보를 전달하는 것을 CDN의 역할로 알고 있다.

Redis와 Memcached 역시 사용자에게 정보를 빠르게 전달하고 처리하기 위한 기술이다.

---

[##_Image|kage@vNnFh/btsGCv5rn1b/c5LmtYptuYNzMzUesGGwz1/img.png|CDM|1.3|{"originWidth":575,"originHeight":208,"style":"alignCenter"}_##]

웹 보안 지식에는 **SHA 함수군과 scrypt, bcrypt, MD5와 관련된 내용**을 학습하라고 적혀있다.

**SHA 함수군**에는 SHA-256과 같은 내용들이 포함되어 있으며, JWT를 통한 로그인 기능을 구현할 때, 사용자가 입력한 패스워드를 그대로 사용하는 것이 아니라, SHA 함수군을 통해 해쉬 방법으로 해싱을 하게 되는데 이에 사용하는 함수군이다.

**구현하려는 시스템이 매우 민감한 정보를 다루고, 보안 시스템을 구현하는 데 많은 비용을 투자할 수 있다면 scrypt**를 사용하면 된다.

**매우 강력한 패스워드 다이제스트를 생성하는 시스템을 쉽게 구현하고 싶다면 bcrypt**를 사용하는 것이 좋다.

개발자가 어떻게 개발을 하고 보안을 구성하고 싶은지에 따라 다른 방식의 보안을 채택하게 된다.

---

[##_Image|kage@cE4gNx/btsGBx31aug/TYyl1cjkwhzTEuetHkvtGK/img.png|CDM|1.3|{"originWidth":425,"originHeight":143,"style":"alignCenter"}_##]

백엔드 개발자라면 최소한 한 번 정도는 들어 봤을 법한 테스트에 관한 내용이다.

**기능 테스트**는 함수 하나에 대한 테스트이다.

하나의 서비스 로직을 수행하기 위해서 다양한 기능들이 포함되는데, 이를 묶어 테스트하는 것을 **단위 테스트**라고 한다.

이러한 단위 테스트들이 모인 테스트들을 **통합 테스트**라고하며 실제 배포 환경에서의 테스트를 가정하고 테스트를 진행한다.

---

[##_Image|kage@P3gmW/btsGCdKKSYk/9QEVACzYqms3FVjs59s460/img.png|CDM|1.3|{"originWidth":1115,"originHeight":341,"style":"alignCenter"}_##]

다음으로 개발 설계 원칙, 아키텍처 패턴, 검색 엔진과 같은 내용들이 있는데, 저 한 칸의 키워드로 두꺼운 책 한 편을 펴낼 수 있을 정도로 방대한 내용들이 존재한다.

---

[##_Image|kage@bZYYzO/btsGAzaGymq/kHX4dKbvErQeUMuc4X6L5K/img.png|CDM|1.3|{"originWidth":1064,"originHeight":269,"style":"alignCenter"}_##]

다음은 메시지 브로커, 컨테이너화 대 가상화, GraphQL, GraphDB들이 존재하는데, 이 역시 위와 마찬가지로 너무나도 많은 지식들을 내포하고 있다.

여기에는 내가 가장 재밌어하는 키워드가 존재하는데, Docker가 바로 그 키워드이다. 이것 때문에 개발자를 희망하게 되었고, Docker 기능을 극대화해서 Orchestration을 수행하는 것이 Kubernetes인데, 현재 여러 책들과 공식 문서들을 통해 공부하고 있는 상황이다.

[##_Image|kage@NRDeD/btsGAfJ5HbF/1lbPFA9TGUCkB9K6IretfK/img.png|CDM|1.3|{"originWidth":1170,"originHeight":493,"style":"alignCenter"}_##]

마지막으로, 웹소켓과 웹 서버, 확장성 있는 구축에 관한 내용들인데, 사실 개발입문자로 보기에 확장성 있는 구축은 희망자 입장에서는 건들기가 쉽지 않은 주제라고 생각된다. 

---

### 마치면서..

이렇게 2024 백엔드 로드맵 전체에 대한 순서와 매우 얕은 지식을 통해 포스팅을 작성했는데, 아직도 배울 것이 한참이나 남아있고 현업에 종사를 하게 되어도 계속해서 공부해야 한다는 사실들을 다시 한번 느끼면서 마무리한다. 그리고 언젠간 위에서 잠깐이나마 다뤘던 내용들에 관한 포스팅을 해야겠다는 생각이 들었다.

+) 또한, 글을 쓰면서 어색한 부분들이 많다는 사실과 다소 두서없이 적는 것 같기도 한데, 꾸준히 포스팅을 하면서 글을 적고 내가 아는 내용들을 사람들이 알기 쉽게 하는 연습을 하려고 한다.
