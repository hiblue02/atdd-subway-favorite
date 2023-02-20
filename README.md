# 지하철 노선도 미션
[ATDD 강의](https://edu.nextstep.camp/c/R89PYi5H) 실습을 위한 지하철 노선도 애플리케이션

## 1주차 - 로그인
### 기능 요구사항
 - [x] 토큰 생성 API 
   - [x] 아이디와 패스워드를 입력받는다.
   - [x] 토큰을 응답 받는다.
   - [x] AuthAcceptanceTest를 통과시킨다.
   - [x] 인수테스트 데이터 초기화를 수행한다.
 - [x] 토큰을 이용하여 내 정보 조회
   - [x] 로그인하여 생성한 토큰을 이용하여 내 정보를 조회하는 API
   - [x] MemberAcceptanceTest의 getMyInfo 테스트 완성하기
   - [x] MemberController 의 findMemberOfMine 메서드 구현하기
### 프로그래밍 요구사항
 - [x] 토큰을 이용한 인수 테스트를 작성하기

## 2주차 - 로그인
### 기능 요구사항
 - [x] 깃허브를 이용한 로그인 구현(토큰 발행)
 - [x] 가입이 되어있지 않은 경우 회원 가입으로 진행 후 토큰 발행
### 프로그래밍 요구사항
 - [x] GitHub 로그인을 검증할 수 있는 인수 테스트 구현(실제 GitHub에 요청을 하지 않아도 됨)

## 3주차 - 즐겨찾기
### 기능 요구사항
 - [ ] 즐겨찾기 추가 (path: /favorites)
   - [ ] Post 방식으로 출발역과 도착역의 아이디를 입력받는다. 
   - [ ] 출발역과 도착역을 즐겨찾기 1개로 추가한다. 
   - [ ] 로그인이 안된 경우 401 Unauthorized 에러를 반환한다.
   - [ ] 성공했으면  201 Created를 반환한다.
 - [ ] 즐겨찾기 조회 (path: /favorites )
   - [ ] Get 방식으로 즐겨찾기 목록 조회를 요청한다.
   - [ ] 즐겨찾기 아이디, 출발역, 도착역을 목록으로 반환한다.
   - [ ] 로그인이 안된 경우 401 Unauthorized 에러를 반환한다.
 - [ ] 즐겨찾기 삭제 (path: /favorites/{id})
   - [ ] Delete 방식으로 즐겨찾기를 삭제를 요청한다. 
   - [ ] 로그인이 안된 경우 401 Unauthorized 에러를 반환한다.
   - [ ] 삭제 후 204 No content 를 반환한다.
### 프로그래밍 요구사항
 - [ ] 요구사항 설명을 참고하여 인수 조건을 정의
 - [ ] 인수 조건을 검증하는 인수 테스트 작성
 - [ ] 인수 테스트를 충족하는 기능 구현
 - [ ] 인수 조건은 인수 테스트 메서드 상단에 주석으로 작성.
 - [ ] 인수 테스트 이후 기능 구현은 TDD로
 - [ ] 도메인 레이어 테스트는 필수
 - [ ] 서비스 레이어 테스트는 선택
 - [ ] 예외 케이스 검증 테스트 필수
