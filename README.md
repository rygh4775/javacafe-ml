# 인공지능, 머신 러닝, 강화 학습

지난 해 구글 딥 마인드에서 개발한 인공지능 바둑 프로그램 알파고가 세계 정상급 프로바둑기사인 이세돌 9단을 이기면서 인공지능에 대한 관심은 점차 높아져 가고 있습니다.

알파고 등 최근 인공지능 기술에서 뺄 수 없는 큰 가지 중 하나가 머신러닝 입니다. 머신러닝은 한국말로 기계학습, 간단히 기계가 학습을 하는 것이라고 할 수 있습니다. 대체 기계가 학습을 한다는게 어떤 것일까요?

<img src="http://postfiles8.naver.net/MjAxNzAyMTdfMTE1/MDAxNDg3MzEzNDczODcw.AJBfGCBNXh7f1gR3Q8cio-UNkhGwfpcIhD3xAocclR0g.L-lhAgLtKKIA9WhQlboN2-et_aJLg46KJprr4TYwHnwg.JPEG.akj61300/ml-sample01.jpg?type=w2" width="800px" />

기계가 학습을 한다고 말하면 위 사진 처럼 로봇이 책을 읽거나 공부를 하는 모습을 상상 할지도 모릅니다. 위의 사진도 틀린 얘기는 아니지만 기계학습의 핵심은 로봇이 아닌 스스로 학습을 하는 소프트웨어를 이야기합니다.

현존하는 대부분의 소프트웨어는 프로그래머 또는 개발자라고 불리우는 사람들의 손에서 탄생됩니다. 간단한 프로그램이라도 특정 조건에 따라 프로그램이 어떻게 동작해야 하는지 사람이 일일이 프로그래밍 하는 것이죠. 심하게 말하면 컴퓨터 또는 프로그램이 자동으로 되는 것은 아무것도 없다고 볼수 있습니다. 모두 사람 손에 의해 만들어졌고, 의도한대로 동작되는 것입니다.(의도한대로 동작 안될수도 있지만 그런것은 보통 버그라고 부릅니다.) 

여기서 머신러닝 기반 소프트웨어와 그렇지 않은 소프트웨어의 아이덴티티가 결정됩니다. 일반 소프트웨어는 동작방식을 사람이 일일이 설계하는 것이고, 머신러닝 소프트웨어는 사람이 설계하지 않아도 동작방식을 스스로 바꿀수 있다는 것이죠.

어떻게 이런일이 가능할까요?

머신러닝 소프트웨어를 만들기 위한 방법으로는 크게 3가지 방법을 보통 이야기합니다. 지도학습, 비지도학습, 강화학습이 그것이죠. 각 방법을 간략하게 소개하면 다음과 같습니다.

* 지도학습: 사람이 입력 데이터와 정답을 제공하여 학습 시키는 방법. 예를 들어 이미지(입력)와 이미지에 해당하는 정답(사람, 개, 고양이) 등을 제공하고 학습 후 이미지(입력)가 어떤 정보인지 추측하는 프로그램
 
* 비지도학습: 지도학습과 달리 컴퓨터가 정답이 없는 정보를 적절히 군으로 분류하여 학습하는 방법.

* 강화학습: 주어진 데이터가 아닌, 주어진 환경에서 행위를 반복하며 환경변화를 만들어 학습하는 방법.

이 컨텐츠에서 다룰 내용은 강화학습에 대한 내용입니다. 작년 화제가 되었던 알파고는 여러가지 알고리즘들이 복합되었지만 가장 중요한 부분중 하나가 바로 이 강화학습이라고 볼 수 있습니다.

여기서는 강화학습에 대한 개념들을 정리하고, 개념 이해를 돕기 위해 텐서플로우와 OpenAI Gym 을 사용한 실습을 소개하려 합니다.

또 이 컨텐츠는 [모두를 위한 딥러닝 - 시즌RL 편](http://hunkim.github.io/ml/) 을 본뒤 기타 다른 자료들을 공부하여 작성한 것입니다. 해당 링크에 동영상 강좌 역시 참조하시면 좋다고 생각됩니다.

저자 및 문의 이메일

* 안귀정 - rnlwjd0613@gmail.com
* 유미령 - kioku714@gmail.com
* 이은미 - 
* 조현수 - rygh4775@gmail.com
* 석혜진 -

