---
title : "CondaVerificationError"
category :
    - Tips
tag :
    - anaconda, torch, pytorch
toc : true
comments: true
toc_sticky: true
---
CondaVerificationError 를 해결해보자.

conda를 이용해 torch를 설치중에 다음과 같은 에러가 발생했다.

구글링을 해보니 이전에 사용했던 버전과 충돌하여 발생하는 문제인 듯하다.

`conda clean --all` 

다음 명령어를 통해 불필요한 패키지들을 모두 삭제한뒤에 다시 실행하면

정상적으로 원하는 패키지를 설치할 수 있다. 