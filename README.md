# Project : Account-Management
- 계좌 관리 시스템
- 프로젝트 기간 : 2024.03.18 ~ 2024.03.24

# Tech Stack
- Language : `Java`
- Build : `Gradle`
- Database : `H2`
- Server : `Spring`
- JDK : `JDK 11`
- Library : `embedded redis`, `redisson`, `lombok`

# 프로젝트 설명
- Account 시스템은 사용자와 계좌의 정보를 저장하고 있습니다.
- 계좌 관리 기능
  - 계좌 추가
  - 계좌 해지
  - 계좌 확인
- 거래 관리 기능
  - 결제
  - 결제 취소
  - 거래 확인
- 계좌 생성 시 계좌 번호는 10자리의 정수로 구성되며 중복이 불가합니다.
- 기본적으로 계좌번호는 순차 증가 방식으로 생성됩니다.

# DB
3명의 ACCOUNT_USER  
![ACCOUNT_USER](https://github.com/IM-GYURI/Account-Management/assets/80020777/653223f3-4f76-4a1d-b98b-e634559cdbcd)  <BR><BR>
그 중 아이디가 1인, Pororo의 3개의 계좌
![ACCOUNT](https://github.com/IM-GYURI/Account-Management/assets/80020777/6b8eed9e-f75f-4c0a-b9cc-063a397d1bf8)  <BR><BR>
Pororo의 3번째 계좌에서 일어난 두 가지 거래 (결제 / 결제 취소)
![TRANSACTION](https://github.com/IM-GYURI/Account-Management/assets/80020777/d33829a8-84bb-4a12-b752-1bfa9d135e7c)
