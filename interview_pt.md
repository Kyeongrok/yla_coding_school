# 야놀자 pt
   - 경력기술서의 내용을 10분 내에 요약해서 설명
   - 커리어 상 개발적으로 가장 기억에 남거나 인상 깊었던 프로젝트에 대해서 10분 내외로 설명
 
## 경력기술서 10분 요약
* 6년차 개발자
* 그 때에 꼭 필요한 것들을 하는 개발자
* php로 입사했으나 java 할 일이 생겨서 java를 함
* java를 하다가 레거시 php코드가 너무 효율이 안나와서 react.js를 함
* MSA를 할 때 배포를 한 후에 확인 할 수 있는 것들이 있어서 배포 자동화를 함

## 기억에 남는 프로젝트
배포 자동화 하기
aws 다른 서비스와 연동해야 하는 기능
local에서 unit test를 하면서 개발함

연동하는 이슈는 올려봐야 정확히 알 수 있다.



eb를 사용했다.
1.maven build
2.aws web console 로그인
3.eb -> environment
4.찾아보기 -> 해당 .war파일 찾아서 업로드
5.배포 될 때까지 로그 보면서 대기
6.로그 확인

### 어떻게 바꾸었는가
sh deploy.sh dev v1.1
위 한줄로 배포 할 수 있도록 변경함

### 무엇이 바뀌었는가?
10분 걸리던 배포를 30초로 바꿈
하루에 5번 배포하면 50분 걸림(dev, qa 포함)
작업할 시간 확보 할 수 있었음


