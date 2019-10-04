# Hyperledger-study-26

하이퍼레져 앱 만들기 실습 26일차 - fabcar 예제 실행

참고 : https://miiingo.tistory.com/47

1. 환경설정 (window) - ubuntu 16.04 LTS를 설치 후 가상 드라이브 아래 항목 설치
  1) cURL
  2) node.js
  3) python
  4) go-language
  5) docker
  6) docker-compose
  
2. 환경설정 (mac) 터미널을 이용하여 아래의 항목 설치
  1) cURL
  2) node.js
  3) python
  4) go-language
  5) docker
  6) docker-compose
  
3. 예제 설치

        sudo curl -sSL http://bit.ly/2ysbOFE | bash -s 1.4.1 (1.4.1 버전으로 설치)

4. 경로 변경

        cd fabric-samples/fabcar

5. 테스트 네트워크 얻기

        ./startFabric.sh

6. 경로 변경

        cd javascript

7. npm 설치

        npm install

8. 만약 run `npm audit fix` to fix them, or `npm audit` for details 라고 나오면

        npm audit fix

7. 하이퍼레저 관리자 등록

        node enrollAdmin.js
        
8. 하이퍼레저 사용자 등록

        node registerUser.js

9. 하이퍼레저 생성 데이터 확인

        node query.js

10. 하이퍼레저 데이터 추가 시

        node invoke.js

