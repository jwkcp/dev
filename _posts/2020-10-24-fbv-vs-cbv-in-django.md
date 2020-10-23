---
layout: post
title: 장고(Django) 함수 기반 뷰 vs 클래스 기반 뷰, 무엇이 더 나을까?
tags: django
comments: true
---

장고에서 함수 기반 뷰를 쓰는 것이 나을지, 클래스 기반 뷰를 쓰는 것이 나을지 하는 질문은 너무도 자주 볼 수 있고 장고를 시작하는 사람이면 누구나 드는 질문입니다. 간편하고 강력한 클래스 기반 뷰가 정답일까요? 디테일하게 내가 하나 하나 조절할 수 있는 함수 기반 뷰가 정답일까요?  

제 대답은 "둘 다 필요하다"입니다. 이런 답변을 들으면 답답하시죠. 하지만 이 답변을 들었을 때 드는 감정이 중요한 것 같습니다. 만약 둘 중에 하나만 배우고 싶고 익숙해지고 싶은데 이런 어중간한 답변이 나왔다면 아직 적어도 둘 중 하나는 익숙치 않은 상태이고 많은 부분이 낯선 상태일 가능성이 높습니다. 이런 경우라면 두 가지 방법으로 로직을 구현해보면서 좀 친해지고 익숙해지는 방법 뿐입니다. 어떤 방법을 선택할 때 그 이유가 장, 단점이 아닌 나의 숙련도 정도이거나 귀차니즘을 줄이기 위해서라면 그건 올바른 판단 기준이 아닐 수 있습니다. 익숙치 않다면 둘 다 간단한 예제를 스스로 구현해보면서 익숙해지세요.  

익숙해졌다면 스스로 판단하게 됩니다.   
"이 경우는 클래스 기반 뷰가 딱이네." "이건 함수 기반 뷰가 더 쉽겠네." 이건 굳이 오버라이딩할 필요가 있나..? 함수 오버라이딩을 하면 한 번만 조회하면 되는 경우인데 두 번 이상 씩 해야하는 경우가 생기는데.. 하는 생각이 들게 됩니다. 그렇지 않다면 아직 시행착오를 줄이기 위해 검색만 하고 있을 수 있고 아마 그 시간이 점점 더 커지다 압도적이게 될 겁니다.  

먼저 익숙해지고 고민하세요. 그렇지 않다면 시행착오 시간보다 검색에 쏟아붇는 시간이 많게 될 수 있습니다. : )  건투를 빕니다.  