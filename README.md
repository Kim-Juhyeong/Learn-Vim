# Learn Vim with Docsify

##Goal

Vim 사용법에 대하여 학습할 수 있는 문서들을 Docsify 기반 정적 웹사이트로 구성함으로써, 누구나 쉽게 Vim을 배울 수 있는 문서화 프로젝트를 진행했습니다.

- 주요 목표:
    - Vim의 다양한 기능을 챕터별로 정리
    - Markdown 기반 문서들을 Docsify를 통해 브라우저에서 탐색 가능하도록 제공
    - 웹을 기반으로 학습 문서 배포 환경을 구성


##Requirements
- 설치된 라이브러리
    - node >= 18.0.0
    - docsify-cli >= 4.12.2
    - python3-pip
    - python3 >=3.12
    - npm >= 9.2.0
    - setuptools >= 68.1.2


##How to install & Run

1. Docker Image 설치

2. Docker Container 생성
    - docker run -it -p 3000:3000 --name [컨테이너이름] final_2023040004:v1

3. 리포지토리 이동 후 docsify 실행
    - cd ~/Learn-Vim/
    - docsify serve ./vimGuide/

4. 로컬 호스트 접속
Serving /root/Learn-Vim/vimGuide now.
Listening at http://localhost:3000
    - 브라우저로 위 로컬 호스트에 접속

5. 종료
    - ctrl + c 로 로컬 호스트 종료
    - ctrl + d 로 컨테이너 종료

디렉토리 구조
![Screenshot 2025-06-08 230516](https://github.com/user-attachments/assets/06f81f2d-e903-4910-bd82-e63bb02adc1b)
