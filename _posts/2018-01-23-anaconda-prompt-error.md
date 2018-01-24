---
layout: post
title: 윈도우에서 아나콘다(Anaconda) 설치 후 프롬프트(Prompt) 실행 시 오류가 발생할 경우
tags: anaconda, how-to 
comments: true    
---

윈도우에서 아나콘다 설치를 반복해서 하다보면 몇 가지 문제가 발생할 때가 있다. 삭제 후 재설치를 반복해도 안되는 경우 아나콘다를 삭제 후 **재부팅**을 해보자. 그 후 (마우스 오른쪽 버튼을 눌러)관리자 권한으로 재설치를 하게 되면 괴롭혔던 몇 가지 문제가 해결되어 있을 것이다.
    
### 에러증상
1. Cound not create menu와 같이 메뉴 바로가기를 만들지 못했다고 나오는 경우
2. 설치된 폴더에서 Anaconda Prompt를 눌렀는데 Scripts/activate.bat 파일이 없다는 에러 메시지가 나오는 경우
3. 특정 파일의 바로가기가 깨진 경우 (이 경우는 여러번 설치/삭제를 반복하면 간혹 바로가기가 삭제되지 않고 남아있어 발생)

### 체크포인트
1. 기설치된 Anaconda 삭제
2. 윈도우 재부팅
3. 관리자 권한으로 Anaconda 재설치
  