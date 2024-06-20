# Robosats

Robosats는 (주로) Tor network를 이용하여 익명성을 강화하면서, 다양한 결제 방식을 제공하는 trustless p2p 비트코인 거래 플랫폼이다. 장점으로는 막강한 익명성과 사기/먹튀 방지를 위한 담보 설정이 있으며, 단점으로는 모바일 환경에서는 tor browser에 익숙하지 않은 사람들에게는 많이 불편할 수 있다는 점이다.

접속 사이트명은 다음과 같다.

- 통합 url: [robosats.com](http://robosats.com)
- Tor onion address:

[***robosats**6tkf3eva7x2voqso3a5wcorsnw34jveyxfqi2fu7oyheasid.onion*](http://robosats6tkf3eva7x2voqso3a5wcorsnw34jveyxfqi2fu7oyheasid.onion/)

- Android app: [깃허브에서 최신 버전의 apk를 다운 받아서 사용](https://github.com/RoboSats/robosats/releases)
- I2P:

[***robosats.i2p**?i2paddresshelper=r7r4sckft6ptmk4r2jajiuqbowqyxiwsle4iyg4fijtoordc6z7a.b32.i2p*](http://robosats.i2p/?i2paddresshelper=r7r4sckft6ptmk4r2jajiuqbowqyxiwsle4iyg4fijtoordc6z7a.b32.i2p)

- Clearnet address (비추천): [*unsafe.robosats.com*](https://unsafe.robosats.com/)
- Umbrel OS: [http://umbrel.local:12596](http://umbrel.local:12596)

첫 사용이라면, 이런 형태로 거래에 사용될 로봇 (익명 ID)를 생성해 줄 것이다. 추후 같은 로봇으로 다시 접속을 해서 거래를 진행해야 하는 경우를 위해, 로봇의 token을 저장해 두는 것이 안전하다. 이미 거래 내역이 있는 로봇이라면, 더 나은 익명성을 위하여 가능하면 새로운 로봇을 만들어서 사용하는 것을 추천한다.

![Untitled](Robosats%20e4fd8911a8564fb9bec23563bbdab6bf/Untitled.png)

생성이 되었다면, 이제 화면 아래에 있는 OFFERS 혹은 CREATE 버튼을 눌러서, 거래에 참여하거나 새로운 거래를 생성할 수 있게 된다.

일단 OFFERS를 들어가 본다. 국내에서는 익숙치 않은 Payment method들이 뜰 것이다.

![Untitled](Robosats%20e4fd8911a8564fb9bec23563bbdab6bf/Untitled%201.png)

위쪽의 지구본 모양을 클릭해서 KRW를 선택해 준다. 아마 KRW (한국 원화)로는 파는 사람이 별로 없기에 익숙한 메뉴는 많이 뜨지 않을 것이다.

본 가이드에서는 이를 해결하기 위해 [**카카오톡 오픈채팅 송금**](https://blog.kakaopay.com/story/post/138-kakaopay-open/) 기능을 이용하여 진행을 해 보았다. 토스의 익명 송금으로도 마찬가지로 진행이 가능할 것으로 생각한다.

사전에 준비할 내용으로는,

- 라이트닝 지갑에 비트코인 충전하기: 판매/구매 시 모두 안전 담보 물량 (기본 거래 금액의 3%)이 필요함.
    - 판매 시: (판매하려는 금액) + (설정된 담보 비율만큼의 금액)만큼은 보유하고 있어야 함.
    - 구매 시: (구매하려는 금액) x (설정된 담보 비율만큼의 금액)만큼은 보유하고 있어야 함.
- 카카오 페이 등록 및 채널 가입: 카카오페이 등록 시 자동으로 가입되지만, 광고가 귀찮아서 채널에서 나왔을 경우에만 해당됨. 송금 및 받기 알림이 해당 채널로만 오기 때문에 가입이 되어있지 않다면 거래를 진행할 수 없음.
- 카카오톡 오픈 채팅 아이디 만들기
- Tor browser 설치

등이 있다. 모바일로는 tor browser 설치 및 사용이 불편할 수 있으니, 가능하면 데스크탑 환경에서 진행하는 것을 추천한다. Clearnet 기반으로도 사용은 가능하나, 플랫폼 운영자는 이에 대하여 강력한 반대 의사를 표명하고 있다. Umbrel OS 기반으로 노드를 돌리고 있다면 그냥 robosats를 설치하고 사용하면 된다.

모든 거래는 기본적으로 생성 이후 24시간 동안 유효하며, 거래를 수락한 이후에는 3시간 이내에 확정 (에스크로 결제 완료)이 되어야 처리가 된다. 이는 거래를 생성할 때 위쪽의 ‘Enable advanced option’ 기능을 켜서 변경할 수 있으며, 사기 방지를 위한 안전 담보 비율 (기본 3%)도 여기서 설정할 수 있다.

![Untitled](Robosats%20e4fd8911a8564fb9bec23563bbdab6bf/Untitled%202.png)

![Untitled](Robosats%20e4fd8911a8564fb9bec23563bbdab6bf/Untitled%203.png)

[판매하기](Robosats%20e4fd8911a8564fb9bec23563bbdab6bf/%E1%84%91%E1%85%A1%E1%86%AB%E1%84%86%E1%85%A2%E1%84%92%E1%85%A1%E1%84%80%E1%85%B5%2075a7d98fe22e4544b69fc44a9241d152.md)

[구매하기](Robosats%20e4fd8911a8564fb9bec23563bbdab6bf/%E1%84%80%E1%85%AE%E1%84%86%E1%85%A2%E1%84%92%E1%85%A1%E1%84%80%E1%85%B5%20deb3ce87e80e49f3ad3c1ee95bd40be8.md)

[수수료](Robosats%20e4fd8911a8564fb9bec23563bbdab6bf/%E1%84%89%E1%85%AE%E1%84%89%E1%85%AE%E1%84%85%E1%85%AD%20bc511d17e011412a89a6cbe8c82bb570.md)

[분쟁 처리](Robosats%20e4fd8911a8564fb9bec23563bbdab6bf/%E1%84%87%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A2%E1%86%BC%20%E1%84%8E%E1%85%A5%E1%84%85%E1%85%B5%209b776f1ca14d4923aa333ba4c1f0ba7b.md)

그 외 자세한 정보는 아래 참고 사이트에서 알아보길 바란다.

[https://learn.robosats.com/](https://learn.robosats.com/)