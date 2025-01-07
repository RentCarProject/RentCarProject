# RentCarProject





### 로고 이미지 
![KakaoTalk_Photo_2025-01-07-11-15-19](https://github.com/user-attachments/assets/1f23a7d6-d682-42ac-938e-3b0782378173)
---


### 1. 개발동기 

       1. 렌트카 산업의 성장과 디지털 전환의 필요성
          최근 렌트카 서비스는 여행, 출장, 또는 개인적 필요로 인해 수요가 꾸준히 증가하고 있습니다. 하지만 많은 렌트카 업체들이 여전히 
          예약, 결제, 관리 시스템에서 디지털 전환을 완전히 이루지 못하고 있습니다. 이를 해결하기 위해 편리하고 효율적인 예약 및 관리 시스템을 개발하고자 했습니다.

       2. 사용자 경험(UX) 개선
          기존의 렌트카 서비스는 예약 과정이 복잡하거나, 차량의 이용 가능 여부를 확인하기 어려운 경우가 많습니다.
          이러한 문제를 해결하기 위해 사용자 중심의 간단한 UI/UX와 실시간 차량 가용성 확인 기능을 제공하는 시스템을 구축하고자 했습니다.

       3. 효율적인 차량 관리 시스템 필요성
          렌트카 업체들은 차량 관리, 예약 충돌 방지, 수익 극대화를 위해 체계적인 관리 시스템이 필요합니다.
          저희 프로젝트는 렌트카 업체가 차량 이용 현황을 한눈에 확인하고 효율적으로 운영할 수 있도록 돕는 관리 도구를 포함하고 있습니다.

       4. 환경적 요인

          전기차, 하이브리드 차량 등 친환경 차량의 대여 수요 증가에 따라 차량 유형별 예약 기능과 필터링 옵션을 추가해 환경 친화적 선택을 지원하고자 했습니다.
          사회적 거리두기 및 비대면 트렌드
          
          팬데믹 이후 비대면 서비스의 중요성이 대두됨에 따라, 완전 온라인 예약 및 결제 시스템을 개발하여 비대면 환경에서도 고객이 안전하고 편리하게 렌트카를 이용할 수 있도록 하고자 했습니다.
---
<br><br><br><br>
### 2. MEMBER
       김현우 배주현 김준영
<br><br><br><br>
       
|이름|역활|
|------|---|
|김현우|웹 크롤링-차량리스트CRUD-날짜선택(예약가능차량리스트)-차량필터|
|배주현|테스트2|
|김준영|테스트2|
---
<br><br><br><br>
### 3. HISTORY
| 헤더1 | 헤더2 | 헤더3 |
| --- | --- | --- |
| 행1 열1 | 행1 열2 | 행1 열3 |
| 행2 열1 | 행2 열2 | 행2 열3 |
| 행3 열1 | 행3 열2 | 행3 열3 |
---
<br><br><br><br>

### 4. SKILLS
---
### Front-End
---
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"> <img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white">

### Back-End
---
<img src="https://img.shields.io/badge/JAVA-507e9c?style=for-the-badge&logo=doubanread&logoColor=white"> <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">

### DataBase
---
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">


### DevOps
---
<img alt="git" src="https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white"> <img alt="github" src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">







### FILE TREES
--- 
```
.
├── BN
│   ├── HELP.md
│   ├── bin
│   │   ├── generated-sources
│   │   │   └── annotations
│   │   └── generated-test-sources
│   │       └── annotations
│   ├── build.gradle
│   ├── gradle
│   │   └── wrapper
│   │       ├── gradle-wrapper.jar
│   │       └── gradle-wrapper.properties
│   ├── gradlew
│   ├── gradlew.bat
│   ├── out
│   │   ├── production
│   │   │   ├── classes
│   │   │   │   ├── com
│   │   │   │   │   └── project
│   │   │   │   │       └── rentcar
│   │   │   │   │           ├── RentcarApplication.class
│   │   │   │   │           ├── config
│   │   │   │   │           │   ├── AppConfig.class
│   │   │   │   │           │   ├── DataSourceConfig.class
│   │   │   │   │           │   ├── JpaConfig.class
│   │   │   │   │           │   ├── PasswordUtil.class
│   │   │   │   │           │   ├── SecretKeyGenerator.class
│   │   │   │   │           │   ├── SecurityConfig.class
│   │   │   │   │           │   ├── WebConfig.class
│   │   │   │   │           │   ├── auth
│   │   │   │   │           │   │   ├── Exception
│   │   │   │   │           │   │   │   ├── CustomAccessDeniedHandler.class
│   │   │   │   │           │   │   │   └── CustomAuthenticationEntryPoint.class
│   │   │   │   │           │   │   ├── JWT
│   │   │   │   │           │   │   │   ├── JwtProperties.class
│   │   │   │   │           │   │   │   ├── JwtProvider.class
│   │   │   │   │           │   │   │   ├── KeyGenerator.class
│   │   │   │   │           │   │   │   ├── TokenInfo$TokenInfoBuilder.class
│   │   │   │   │           │   │   │   └── TokenInfo.class
│   │   │   │   │           │   │   ├── Login
│   │   │   │   │           │   │   │   ├── CustomAuthenticationFailureHandler.class
│   │   │   │   │           │   │   │   └── CustomLoginSuccessHandler.class
│   │   │   │   │           │   │   ├── Logout
│   │   │   │   │           │   │   │   ├── CustomLogoutHandler.class
│   │   │   │   │           │   │   │   └── CustomLogoutSuccessHandler.class
│   │   │   │   │           │   │   ├── PrincipalDetails.class
│   │   │   │   │           │   │   ├── PrincipalDetilsService.class
│   │   │   │   │           │   │   └── provider
│   │   │   │   │           │   │       └── CustomAuthenticationProvider.class
│   │   │   │   │           │   ├── details
│   │   │   │   │           │   │   ├── CustomUserDetails.class
│   │   │   │   │           │   │   └── CustomUserDetailsService.class
│   │   │   │   │           │   └── jwt
│   │   │   │   │           │       ├── JwtTokenFilter.class
│   │   │   │   │           │       └── JwtTokenProvider.class
│   │   │   │   │           ├── controller
│   │   │   │   │           │   ├── AuthRestController.class
│   │   │   │   │           │   ├── CarController.class
│   │   │   │   │           │   ├── HomeController.class
│   │   │   │   │           │   ├── Portone
│   │   │   │   │           │   │   └── PortOneController.class
│   │   │   │   │           │   ├── RentCarController.class
│   │   │   │   │           │   ├── RentController.class
│   │   │   │   │           │   ├── ReviewController.class
│   │   │   │   │           │   ├── TermsAndConditionsController.class
│   │   │   │   │           │   ├── UserController.class
│   │   │   │   │           │   └── UserRestController.class
│   │   │   │   │           └── domain
│   │   │   │   │               ├── CarSpecifications.class
│   │   │   │   │               ├── Filter
│   │   │   │   │               │   └── JWTFilter.class
│   │   │   │   │               ├── dto
│   │   │   │   │               │   ├── CarDto.class
│   │   │   │   │               │   ├── PortOneDto
│   │   │   │   │               │   │   ├── PortOneAuthInfoResponse$AuthInfo.class
│   │   │   │   │               │   │   ├── PortOneAuthInfoResponse.class
│   │   │   │   │               │   │   ├── Response.class
│   │   │   │   │               │   │   └── TokenResponseDto.class
│   │   │   │   │               │   ├── RentDto$RentDtoBuilder.class
│   │   │   │   │               │   ├── RentDto.class
│   │   │   │   │               │   ├── ReviewDto$ReviewDtoBuilder.class
│   │   │   │   │               │   ├── ReviewDto.class
│   │   │   │   │               │   ├── TermsAndConditionsDto$TermsAndConditionsDtoBuilder.class
│   │   │   │   │               │   ├── TermsAndConditionsDto.class
│   │   │   │   │               │   ├── UserDto$UserDtoBuilder.class
│   │   │   │   │               │   ├── UserDto.class
│   │   │   │   │               │   ├── UserRequestDto.class
│   │   │   │   │               │   ├── UserResponseDto.class
│   │   │   │   │               │   └── auth
│   │   │   │   │               │       ├── AuthRequestDto.class
│   │   │   │   │               │       └── AuthResponseDto.class
│   │   │   │   │               ├── entity
│   │   │   │   │               │   ├── Auth$AuthBuilder.class
│   │   │   │   │               │   ├── Auth.class
│   │   │   │   │               │   ├── Car$CarBuilder.class
│   │   │   │   │               │   ├── Car.class
│   │   │   │   │               │   ├── JWTToken$JWTTokenBuilder.class
│   │   │   │   │               │   ├── JWTToken.class
│   │   │   │   │               │   ├── JwtUtil.class
│   │   │   │   │               │   ├── Payments.class
│   │   │   │   │               │   ├── Rent$RentBuilder.class
│   │   │   │   │               │   ├── Rent.class
│   │   │   │   │               │   ├── Review$ReviewBuilder.class
│   │   │   │   │               │   ├── Review.class
│   │   │   │   │               │   ├── Role.class
│   │   │   │   │               │   ├── Signature.class
│   │   │   │   │               │   ├── TermsAndConditions.class
│   │   │   │   │               │   ├── User$UserBuilder.class
│   │   │   │   │               │   └── User.class
│   │   │   │   │               ├── repository
│   │   │   │   │               │   ├── AuthRepository.class
│   │   │   │   │               │   ├── CarRepository.class
│   │   │   │   │               │   ├── JWTTokenRepository.class
│   │   │   │   │               │   ├── PaymentsRepository.class
│   │   │   │   │               │   ├── RentRepository.class
│   │   │   │   │               │   ├── ReviewRepository.class
│   │   │   │   │               │   ├── SignatureRepository.class
│   │   │   │   │               │   ├── TermsAndConditionsRepository.class
│   │   │   │   │               │   └── UserRepository.class
│   │   │   │   │               └── service
│   │   │   │   │                   ├── AuthService.class
│   │   │   │   │                   ├── CarService.class
│   │   │   │   │                   ├── CertificationService.class
│   │   │   │   │                   ├── JWTTokenService.class
│   │   │   │   │                   ├── PaymentService.class
│   │   │   │   │                   ├── RentServiceImpl.class
│   │   │   │   │                   ├── ReviewServiceImpl.class
│   │   │   │   │                   ├── TermsAndConditionsInitializer.class
│   │   │   │   │                   ├── TermsAndConditionsService.class
│   │   │   │   │                   └── UserService.class
│   │   │   │   └── generated
│   │   │   └── resources
│   │   │       └── application.properties
│   │   └── test
│   │       └── classes
│   │           ├── com
│   │           │   └── project
│   │           │       └── rentcar
│   │           │           ├── RentcarApplicationTests.class
│   │           │           └── controller
│   │           │               └── RentControllerTest.class
│   │           └── generated_tests
│   ├── settings.gradle
│   └── src
│       ├── main
│       │   ├── generated
│       │   ├── java
│       │   │   └── com
│       │   │       └── project
│       │   │           └── rentcar
│       │   │               ├── RentcarApplication.java
│       │   │               ├── config
│       │   │               │   ├── AppConfig.java
│       │   │               │   ├── DataSourceConfig.java
│       │   │               │   ├── JpaConfig.java
│       │   │               │   ├── PasswordUtil.java
│       │   │               │   ├── SecretKeyGenerator.java
│       │   │               │   ├── SecurityConfig.java
│       │   │               │   ├── WebConfig.java
│       │   │               │   ├── details
│       │   │               │   │   ├── CustomUserDetails.java
│       │   │               │   │   └── CustomUserDetailsService.java
│       │   │               │   └── jwt
│       │   │               │       ├── JwtTokenFilter.java
│       │   │               │       └── JwtTokenProvider.java
│       │   │               ├── controller
│       │   │               │   ├── AuthRestController.java
│       │   │               │   ├── CarController.java
│       │   │               │   ├── HomeController.java
│       │   │               │   ├── Portone
│       │   │               │   │   └── PortOneController.java
│       │   │               │   ├── RentCarController.java
│       │   │               │   ├── RentController.java
│       │   │               │   ├── ReviewController.java
│       │   │               │   ├── TermsAndConditionsController.java
│       │   │               │   └── UserRestController.java
│       │   │               └── domain
│       │   │                   ├── CarSpecifications.java
│       │   │                   ├── Filter
│       │   │                   │   └── JWTFilter.java
│       │   │                   ├── dto
│       │   │                   │   ├── CarDto.java
│       │   │                   │   ├── PortOneDto
│       │   │                   │   │   ├── PortOneAuthInfoResponse.java
│       │   │                   │   │   ├── Response.java
│       │   │                   │   │   └── TokenResponseDto.java
│       │   │                   │   ├── RentDto.java
│       │   │                   │   ├── ReviewDto.java
│       │   │                   │   ├── TermsAndConditionsDto.java
│       │   │                   │   ├── UserDto.java
│       │   │                   │   ├── UserRequestDto.java
│       │   │                   │   ├── UserResponseDto.java
│       │   │                   │   └── auth
│       │   │                   │       ├── AuthRequestDto.java
│       │   │                   │       └── AuthResponseDto.java
│       │   │                   ├── entity
│       │   │                   │   ├── Auth.java
│       │   │                   │   ├── Car.java
│       │   │                   │   ├── JwtUtil.java
│       │   │                   │   ├── Payments.java
│       │   │                   │   ├── Rent.java
│       │   │                   │   ├── Review.java
│       │   │                   │   ├── Role.java
│       │   │                   │   ├── Signature.java
│       │   │                   │   ├── TermsAndConditions.java
│       │   │                   │   └── User.java
│       │   │                   ├── repository
│       │   │                   │   ├── AuthRepository.java
│       │   │                   │   ├── CarRepository.java
│       │   │                   │   ├── PaymentsRepository.java
│       │   │                   │   ├── RentRepository.java
│       │   │                   │   ├── ReviewRepository.java
│       │   │                   │   ├── SignatureRepository.java
│       │   │                   │   ├── TermsAndConditionsRepository.java
│       │   │                   │   └── UserRepository.java
│       │   │                   └── service
│       │   │                       ├── AuthService.java
│       │   │                       ├── CarService.java
│       │   │                       ├── CertificationService.java
│       │   │                       ├── PaymentService.java
│       │   │                       ├── RentServiceImpl.java
│       │   │                       ├── ReviewServiceImpl.java
│       │   │                       ├── TermsAndConditionsInitializer.java
│       │   │                       ├── TermsAndConditionsService.java
│       │   │                       └── UserService.java
│       │   ├── resources
│       │   │   └── application.properties
│       │   └── webapp
│       │       └── WEB-INF
│       │           └── views
│       │               ├── cars
│       │               │   ├── add.jsp
│       │               │   ├── cars.jsp
│       │               │   ├── delete.jsp
│       │               │   ├── details.jsp
│       │               │   ├── edit.jsp
│       │               │   ├── list.jsp
│       │               │   ├── search.jsp
│       │               │   └── searchResults.jsp
│       │               ├── index.jsp
│       │               ├── login.jsp
│       │               ├── main.jsp
│       │               ├── rent
│       │               │   ├── add.jsp
│       │               │   ├── carList.jsp
│       │               │   ├── carReturn.jsp
│       │               │   └── dayUpdate.jsp
│       │               ├── review
│       │               │   ├── addReview.jsp
│       │               │   ├── deleteReview.jsp
│       │               │   ├── reviewMain.jsp
│       │               │   ├── reviewRead.jsp
│       │               │   └── updateReview.jsp
│       │               ├── signup-success.jsp
│       │               ├── signup.jsp
│       │               └── terms.jsp
│       └── test
│           └── java
│               └── com
│                   └── project
│                       └── rentcar
│                           ├── RentcarApplicationTests.java
│                           └── controller
│                               └── RentControllerTest.java
└── FN
    ├── README.md
    ├── package-lock.json
    ├── package.json
    ├── public
    │   ├── favicon.ico
    │   ├── index.html
    │   ├── logo192.png
    │   ├── logo512.png
    │   ├── manifest.json
    │   └── robots.txt
    └── src
        ├── App.css
        ├── App.js
        ├── App.test.js
        ├── HeadFoot
        │   ├── Logo
        │   │   └── CRUVIX.png
        │   ├── footer
        │   │   ├── Footer.css
        │   │   └── Footer.js
        │   └── header
        │       ├── Header.css
        │       └── Header.js
        ├── api
        │   ├── AuthAPI.js
        │   ├── MyInfo.js
        │   ├── MyPage.js
        │   ├── Navigation.js
        │   ├── ReviewAPI.js
        │   └── UserAPI.js
        ├── components
        │   ├── Car
        │   │   ├── CarCard.css
        │   │   ├── CarCard.js
        │   │   ├── CarFilter.css
        │   │   ├── CarFilter.js
        │   │   ├── CarList.css
        │   │   ├── CarList.js
        │   │   ├── CarMain.css
        │   │   ├── CarMain.jsx
        │   │   ├── DateSelector.js
        │   │   ├── Details
        │   │   │   ├── CarDetail.css
        │   │   │   ├── CarDetail.js
        │   │   │   ├── Identity-pay.js
        │   │   │   └── Map.js
        │   │   ├── Pagination.css
        │   │   ├── Pagination.js
        │   │   └── ParentComponent.jsx
        │   ├── HeadFoot
        │   │   ├── Logo
        │   │   │   └── CRUVIX.png
        │   │   ├── footer
        │   │   │   ├── Footer.css
        │   │   │   └── Footer.js
        │   │   └── header
        │   │       ├── Header.css
        │   │       └── Header.js
        │   ├── Homepage.jsx
        │   ├── IdentityPage.jsx
        │   ├── MyPage
        │   │   ├── MyInfo.jsx
        │   │   ├── MyPage.jsx
        │   │   ├── MyPageCss
        │   │   │   ├── MyInfo.css
        │   │   │   └── MyPage.css
        │   │   ├── addr.js
        │   │   └── addrdetail.js
        │   ├── PaymentPage .jsx
        │   ├── ReivewFindById.jsx
        │   ├── ReivewUpdate.jsx
        │   ├── Rent
        │   │   ├── RentAPI.js
        │   │   └── RentList.js
        │   ├── ReviewAdd.jsx
        │   ├── ReviewList.jsx
        │   ├── ReviewPage.jsx
        │   ├── SignInPage.jsx
        │   ├── SignUpPage.jsx
        │   ├── assets
        │   │   ├── Cruvix.png
        │   │   ├── booking.jpg
        │   │   ├── cars.jpg
        │   │   └── road.jpg
        │   └── css
        │       ├── MainPage.css
        │       ├── ReviewPage.css
        │       ├── SignInPage.css
        │       └── SignUpPage.css
        ├── index.css
        ├── index.js
        ├── logo.svg
        ├── reportWebVitals.js
        └── setupTests.js



