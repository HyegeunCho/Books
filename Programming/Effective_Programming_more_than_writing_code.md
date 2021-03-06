# 코딩호러의 이펙티브 프로그래밍

## 아이디어? 실행?

성공이 아이디어의 질에 의해 결정되는 경우는 거의 없다. 그것은 대부분 실행의 질에 의해 결정된다.
아이디어가 정말로 탁월한 것인지 여부를 놓고 걱정하는 것이 아니라 실행 방법이 옳은 것인지 걱정해야 한다.

## 회의

1. 어떤 회의라도 한 시간을 넘기면 안된다. 넘기면 사형이다.
    - 회의를 한 시간 내에 마칠 수 없다면 뭔가 완전히 잘못된 것이므로 그 자리에서 수정해야 한다.
2. 모든 회의에는 명확하게 정의된 목표가 있어야 한다.
    - 이 회의의 목표는 무엇인가? 그것을 하나의 간결한 문장으로 요약할 수 있는가?
3. 회의에 참석하기 전에 회의에서 필요한 일을 하라.
    - 회의에 참석하는 사람들은 모두 회의에 참석하기 전에 자신이 어떤 말을 해야 하는지, 어떤 정보를 공유해야 하는지 등에 대해 준비를 완전히 끝마쳐야 한다.
4. 회의에 참석하는 것을 선택사항으로 만들어라.
    - 회의에 참석하는 사람들에게 책임감을 부여하는 방법 중 하나는 그들에게 회의에 참석하는 것이 선택사항이라고 말하는 것이다.
5. 회의를 마무리할 때 해야 할 일을 정리하라.
    - 회의를 끝마치고 떠나기 전에 자기가 해야 할 일을 정리해서 밝히는 것이 좋다.

## 썩은 사과

팀 안에 썩은 사과가 있음을 나타내는 징후

1. 동료로부터 배우려고 노력하기보다 자신의 무지를 감추기 위해 노력한다.
2. 코드에 대해 지나치게 프라이버시에 집착한다.
3. 업무에 대해 경계선 긋기를 좋아한다.
4. 팀에서 내린 결정에 대해 투덜거리고, 오랜 시간이 지난 뒤에도 낡은 논의를 다시 꺼낸다.
5. 팀원들이 동일한 한 사람에 대해 정기적으로 독설이나 불만을 토로한다.
6. 팀으로써 업무에 잘 참여하지 않는다.

## 버전 1은 엉망이야, 하지만 어쨌든 출시하라고

중요한 것은 소프트웨어가 얼마나 완벽한 것인가가 아니라, 소프트웨어를 출시한 다음에 당신이 어떻게 하느냐다.

당신의 팀이 사용자의 피드백에 반응하는 속도와 태도는 하나의 완벽한 버전이 그렇게 할 수 있는 것에 비해 훨씬 더 강력하게 사용자들이 소프트웨어에 대해 품는 느낌을 결정한다.

그래서 당신이 진짜 잘해야 하는 것은 바로 피드백에 대한 반응이다.

신화적이고 완벽한 소프트웨어를 출시해야 한다는 이상적인 관념에 사로잡히는 것이 아니라, 사용자나 고객의 피드백에 제대로 응답하고 그들의 피드백을 활용해서 소프트웨어를 지속적으로 개선하고 가다듬는 모습을 보여주는 것이 진짜 중요하다.

주어진 비용의 한도 내에서 소프트웨어를 최대한 일찍 출시하고, 나머지 시간을 실제 세상의 피드백에 기초해서 빠르고 반복적인 개선을 수행하는 데 보내는 것은 의심의 여지없이 좋은 소프트웨어를 개발하는 최선의 방법이다.

## 나는 단위 테스틀르 작성하지 않는 바보들에게 동정을 보낸다.

테스트를 우선시하는 태도가 더 좋은 코드를 작성하도록 도움을 주는 12가지 구체적인 방법

1. 단위 테스트는 당신의 코드가 실제로 동작한다는 것을 증명한다.
2. 낮은 수준에서 동작하는 회귀 테스트 한 벌을 가질 수 있다.
3. 설계를 망가뜨리지 않으면서 개선할 수 있다.
4. 단위 테스트와 함께 코드를 작성하는 것은 그렇지 않는 것보다 더 재미있다.
5. 구체적인 전진 과정을 보여준다.
6. 단위 테스트는 샘플 코드의 형태를 취한다.
7. 코딩을 시작하기 전에 일정한 계획을 세우게 해준다.
8. 버그에 따르는 비용을 줄여준다.
9. 코드 조사(code inspection)에 비해 훨씬 더 효과적이다.
10. 실질적으로 코더의 블록을 제거해준다. 코더의 블록이란 프로그래머가 심리적으로 갑자기 아무 생각도 떠올릴 수 없는 상태를 의미한다.
11. 단위 테스트는 더 나은 설계를 가능하게 해준다.
12. 테스트 없는 코드를 작성하는 것보다 더 빠르다.

디버깅을 위한 출력 명령문에 뭔가를 집어넣고 싶은 생각이 든다면 대신 테스트를 작성하라.

## 커뮤니티의 의견을 들어라, 하지만 그들이 당신이 어떻게 할지 말하게 하지 마라.

- 트럭을 만들라는 달콤한 유혹에 넘어가지 말라. 본래의 임무에 충실하라.
- 하지 않을 일에 대해 솔직하게 말하라.

## 반복한다: 사용자의 말을 듣지 마라.

어느 디자인이 가장 잘 동작하는지 보려면, 사람들이 실제로 사용하는 모습을 관찰해야 한다.

사용성 디자인을 잘못하게 되는 가장 흔한 이유는 그들이 실제로 무엇을 하는지 관찰하는 것이 아니라 그들이 하는 말만 경청하기 때문이다.

사용자 요구사항은 언제나 잘못된 것이다. 그러한 요구사항은 빨리 프로토타입으로 전환하고, 그것을 사용자에게 실제로 보여줌으로써 그들이 정말로 무엇을 필요로 하는지 파악해야 한다.

## 행복을 구매하기

1. 물건 대신 경험을 구매하라. 돈을 텔레비전과 같은 물건이 아니라 가족과 함께 디즈니 월드로 여행가는 것처럼 경험에 사용하라.
2. 자기 자신보다 다른 사람을 도와라. 돈을 이용해 다른 사람과의 연결을 강화할 수 있는 것이라면 무엇이든 그것은 우리의 사회적 연결을 강화하고 우리 자신과 다른 사람들에 대한 감정을 긍정적인 것으로 만든다.
3. 적고 큰 기쁨보다 많고 작은 기쁨을 구매하라. 우리는 변화에 매우 잘 적응하기 때문에 금방 익숙해지고 말 거대한 변화만 추구하지 말고 잦은 변화를 추구하는 것이 좋다.
4. 보험은 더 적게 들어라. 
5. 돈은 지금 지불하고 나중에 사용하라. 최대한의 행복을 위해서는 구매할 것인지, 구매한다면 무엇을 구매할 것인지에 대한 판단을 실제적인 욕망이 발생할 때까지 절제하라. (심지어 판단을 유보하라!)
6. 생각하고 있지 않은 것에 대해 생각하라. 당신이 살아가는 매일매일의 삶을, 거의 시간단위로 상세하게 상상하라.
7. 비교 쇼핑을 염두에 둬라. 비교자체를 위해 비교하는 함정에 빠지지 말라. 자신의 즐거움과 경험에 실제로 문제가 되는 속성을 따져보려고 노력하라.
8. 자신의 머리가 아니라 군중을 따라라. 뭔가를 구매하려고 할 때 다른 사람들의 의견과 사용자 리뷰에 큰 비중을 두고 경청하라.

