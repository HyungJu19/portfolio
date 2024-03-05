# 📜 송민호 포트폴리오

> 송민호(MinHo Song) - Hyungju19 포트폴리오

<br />

# 👋 Intro

> 안녕하세요! ***"항상 새로운 것을 배우고 즐기는"*** 송민호입니다!  
> 6개월간 ***팀장***을 맡으며 팀 프로젝트를 진행하여 백엔드, 프론트엔드 개발자 역량을 길렀고 
> 이해한 내용들은 같이 공부하는 동료들에게 설명하며 다시한번 학습했고 <a href="https://hyungju91.tistory.com/">
> <img src="https://img.shields.io/badge/tstory-FF5722?style=for-the-badge&logo=tistory&logoColor=white" alt="블로그"></a> 티스토리에 정리하고있습니다.

<br />
<br />

# 2.📝Projects
이번 프로젝트에서는 JPA 관계 매핑을 심도 있게 적용하여 Hibernate가 효율적인 쿼리를 생성할 수 있도록 노력했습니다. 특히, @ManyToOne과 @OneToMany 어노테이션을 활용해 복잡한 객체 관계를 명확히 설정하며, 쿼리 성능을 크게 개선했습니다. 프로젝트 구조는 스프링 부트 기반의 RESTful 백엔드와 리액트 프론트엔드로 분리하여 구현, 기존 세션 기반 인증 대신 JWT 토큰 방식을 도입함으로써 보다 안전하고 유연한 인증 방식을 구현했습니다. 공식 문서를 통한 버전 호환성 문제 해결 과정은 제 문제 해결 능력을 키우는 데 큰 도움이 되었습니다. 번외로  AWS s3 를 이용해서 이미지파일을 첨부하면 저장을하고 저장한 경로(path) 를 데이터베이스 이미지url 로 저장하는 방법을 사용해봤는데 기존에 프로젝트파일안에 폴더에 이미지를 저장하고 가져오는거보다 간단하고 성능면에서도 빠르면서 간편한 좋은 경험 이였습니다.

리액트 또한 배운걸 사용해보면서 SPA (Single Page Application) 이 어떤느낌인지 알게됬고 타임리프 템플릿 엔진을 사용했을때보다 편안하고 특히 여러 라이브러리들을 사용해면서 재미를 느꼈습니다.  swiper 를 사용한 드래그 슬라이드배너와 각 컴포넌트들이 부모자식간에 props 로 상속이켜 상태값을 공유하는 등 여러가지 기능을 사용해볼수있어서 좋았습니다.

이번 프로젝트는 JPA, Hibernate, AWS S3, JWT, 그리고 리액트와 같은 다양한 기술들을 실제로 적용해보며, 복잡한 문제를 해결하고 새로운 기술을 배우는 과정에서 좋은경험이 되었습니다.

## 2. 🍽 음식점 실시간웨이팅 , 리뷰커뮤니티 , 간편한 업체 입점등록

> 음식점 웨이팅, 음식점 정보, 리뷰 커뮤니티, 업체등록 관리 (국비지원교육 - Eatalbe 팀프로젝트)_
>
> 
> - 개발기간 : 2024 01.26 - 02.26
> - 핵심 역할 : 팀장, 백엔드 SpringBoot JPA Entity클래스들간에 릴레이션 연결 JWT 로그인 RestFulAPI  json 통신
> - 프론트엔드 React사용,  리뷰 타임라인 , 사용자간 구독, 좋아요  , 팀원들이 만든 컴포넌트 조합 props 연결
> - AWS s3 를 이용한  이미지파일 저장 및 path 경로 데이터베이스 저장 활용 
> - 협업툴 - 깃허브
>

진행중입니다.
>> [프로젝트 상세 설명(SpringBoot Back-end)](https://github.com/HyungJu19/Eatable_App_Frontend)
>> [프로젝트 상세 설명(React Front-end)](https://github.com/HyungJu19/EatTable_Backend)


<br />
<br />

# 1.📝Projects
2023년 11월 23일부터 시작해서 한달간 진행한 프로젝트 입니다. 
팀장으로서는 운영적인 면과 프로젝트 일정 관리 등 많은 경험을 할 수 있었고,
SpringBoot MVC 이해도가 많이 올라갔고 마이바티에스에서 직접 쿼리를 만들어 적용해보면서 
MySQL RDB 이해도도 많이 올라갈수있었던 좋은 기회였습니다.
linex 명령어로 AWS EC2 와  RDS 를 사용해서 배포도 해보면서 새로운 경험도 하였습니다.
여러가지 라이브러리, api , 기술스텍을 사용하고 경험해보면서 협업하는  즐거운 시간들이였습니다!

##  🚗 국내 투어 스케줄추천  (헤커톤 본선진출 장려상)

> 여행지역 여행일정 추천 _(국비지원교육 - hot조 팀프로젝트)_
>
> - 기획기간 : 2023 11.23-12.4
> - 개발기간 : 2023 12.4- 12.27 
> - 핵심 역할 : 팀장, 공공데이터 api mysql 데이터베이스 구축 , jpa 를이용한 실시간좋아요 반영
> - 마이바티스 이용 관광지 맞춤정보 리스트 출력 여행스케줄 작성페이지 구현
> - 카카오모빌리티 api 와  구글 맵 api 그리고 데이터베이스 정보를 융합하여  여행스케줄 구현 (선택한 여행지 목록에서  여행지 간 거리 시간 계산해서 지도에표시)
>

>> [프로젝트 상세 설명(Back-end)](https://github.com/HyungJu19/HotProject)


<br />


<br />


<br />
<br />

# 📞 Contact

- 이메일 : hyungju911@gmail.com
- 티스토리 : <a href="https://hyungju91.tistory.com/">
  <img src="https://img.shields.io/badge/tstory-FF5722?style=for-the-badge&logo=tistory&logoColor=white" alt="블로그">
  </a>
- 깃허브 : <a href="https://github.com/HyungJu19">
  <img src="https://user-images.githubusercontent.com/68724828/185908612-22f4d219-78a7-4de7-bb02-deecaa63bffa.png" height="28px" style="margin-top: 10px" />
  </a>
