

<br>
<br>

<div align=center>
<h3>NomadLog</h3>
<h4>1팀 - 김정훈, 김진경, 이지연\</h4>
</div>

<br>

<div align=center>
	<h2>📚 Tech Stack 📚</h2>
	<p>✨ Platforms & Languages ✨</p>
</div>
<div align="center">
	<!-- <img src="https://img.shields.io/badge/vuejs-%2335495e.svg?style=flat&logo=vuedotjs&logoColor=%234FC08D" /> -->
	<!-- <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
	<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white" /> -->
	<br>
	<img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=SpringBoot&logoColor=white" />
        <!-- <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=Conda-Forge&logoColor=white" />
	<img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jQuery&logoColor=white" />
	<img src="https://img.shields.io/badge/MariaDB-003545?style=flat&logo=MariaDB&logoColor=white" />
</div>
<br>
<div align=center>
	<h2>🛠 Tools 🛠</h2>
</div>
<div align=center>
	<img src="https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=flat&logo=intellij-idea&logoColor=white" />
	<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white" />
	<!-- <img src="https://img.shields.io/badge/apache-%23D42029.svg?style=flat&logo=apache&logoColor=white" /> -->
</div>
<br>
<br>


<h2>프로젝트 소개</h2>


<h2>팀원 소개</h2>
<div align=center>
	<img src="https://github.com/beyond-sw-camp/be01-2nd-1Team-NomadLog/assets/142721325/4087f048-7e9a-464a-92fb-79849b862ff8" width="100%">
</div>

<h2>프로젝트 기간</h2>
1/30(금): 기획 완료(요구사항정의서, WBS)<br>
2/2(월): ERD 설계 초안 피드백<br>
2/3(화): ERD 설계 완료 및 프로젝트 생성<br>
2/19(목): (설 이후) 백엔드 80% 목표<br>
2/23(월): 화면기획서 피드백<br>
2/27(금): 프론트 개발 80% 이상 완료 목표<br>
3/17(화): 산출물 제출<br>
3/18(수): 팀별 발표<br>

<h2>프로젝트 개요</h2>
<h4>:small_blue_diamond:아이디어 기획</h4>

![iOS 이미지](https://github.com/beyond-sw-camp/be01-2nd-1Team-NomadLog/assets/148880521/1bf9cb85-c073-4cd4-bce8-7b718b49f5e9)


<h4>프로젝트 설계</h4>
<br>
소프트웨어 아키텍쳐
<p align="center">
</p>
<h2>:gift: 요구사항 정의</h2>

<p align="center", width=100%>	
<img width="2816" height="1536" alt="정의 이미지" src="https://github.com/user-attachments/assets/eceae756-39b7-419c-a111-945a4d69c1e4" />
</p>

<h3>요구사항 분석서</h3>
공통 : 회원가입, 로그인, 비밀번호변경

소비자 : 공연예약(공연검색, 좌석선택, SNS결제), 주문내역확인, 내정보확인,

공연책임자 : 공연등록요청(공연장선택, 날짜선택), 공연확인(좌석확인), 주문내역확인(회원정보마스킹),

어드민 : 공연장등록, 공연장정보수정, 공연허가, 공연목록조회, 공연조회, 회원목록조회, 회원조회
<h2>WBS</h2>

<h2>:wrench: DB 모델링</h2>

## - Entity Relationship Diagram (ER Diagram)
 



<p align="center">
	<img width="2213" height="1067" alt="er diagram" src="https://github.com/user-attachments/assets/1409eb09-8163-4502-a678-7bf5c5fd0fec" />
	
</p>

## - Entity Relationship Diagram (ERD)
<p align="center">
</p>


<h2>서비스별 주요 기능 소개</h2>
<h3>계층 구조 설계</h3>

```
C:.
├─.idea
├─.mvn
│  └─wrapper
└─src
   └─main
      ├─java
      │  └─com
      │      └─encore
      │          └─bbs
      │              ├─board
      │              │  ├─controller
      │              │  ├─dto
      │              │  ├─mapper
      │              │  └─service
      │              ├─chat
      │              │  ├─config
      │              │  ├─controller
      │              │  ├─model
      │              │  ├─repository
      │              │  └─service
      │              ├─comment
      │              │  ├─controller
      │              │  ├─dto
      │              │  ├─mapper
      │              │  └─service
      │              ├─config
      │              └─member
      │                  ├─controller
      │                  ├─dto
      │                  ├─handler
      │                  ├─mapper
      │                  └─service
      └─resources
          ├─mapper
          ├─static
          │  ├─css
          │  ├─images
          │  │  └─main
          │  └─js
          └─templates
              ├─bbs
              ├─chat
              ├─common
              │  ├─fragments
              │  └─layout
              └─member
```

<h3>클래스 간 관계도</h3>



<h2>QA</h2>

![image](https://github.com/beyond-sw-camp/be01-2nd-1Team-NomadLog/assets/148880521/cba9aec0-b121-47d6-bbdf-57d9d4ff3474)



<h2>시연영상</h2>




<h2> 개선사항</h2>


<h2>회고 </h2>
<img width="95" height="95" alt="스크린샷 2026-01-29 004004" src="https://github.com/user-attachments/assets/997a68cc-ac08-4790-9c85-ee21de323adf" />정훈:
<img width="99" height="99" alt="스크린샷 2026-01-29 003916" src="https://github.com/user-attachments/assets/8bde8def-d40a-4437-a7c7-080c6090f007" />진경:
<img width="99" height="102" alt="스크린샷 2026-01-29 003946" src="https://github.com/user-attachments/assets/0932dcbe-bfcc-4638-a76e-6edd1dd51f7d" />지연:
