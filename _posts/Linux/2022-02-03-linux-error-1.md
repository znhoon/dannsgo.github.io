---
title: "[Error] Linux 가상 머신 재설치 오류"
categories:
 - Linux
tags:
 - [Linux, Error]
toc: ture
toc_sticky: true
---

## E_INVALIDARG (0x80070057)

- ```
  rm -f *
  ```
  명령어 잘못 사용으로 인해서 가상머신 재설치
  => Oracle VM VirtualBox 가져오기 할 때, 디렉터리 경로 변경해서 ova 파일 가져오기 실행
  => 재설치를 원하는 가상머신 디렉터리 잘라내기 & 붙여넣기

- Error 발생

![image](https://user-images.githubusercontent.com/90893596/152355193-831b78a2-b5fe-4fcc-8b2b-ab94948a9d8c.png){: .align-center}

<br />

### 오류 해결한 방법

- [설정]-[네트워크]-MAC 주소 새로고침

![image](https://user-images.githubusercontent.com/90893596/152355654-1d2aaecf-358e-4d64-80be-d5105d9d6a1c.png){: .align-center}
