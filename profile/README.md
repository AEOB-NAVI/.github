# 프로젝트 개요

<!-- ![navi](/uploads/9f10badbe45d88966ba3f57a404a47c2/navi.png) -->
<table>
  <tr>
    <td>
      <img src="navi.png" alt="Navi" width="70px">
    </td>
    <td>
      <b>Navi ( 꿈을 위한 길라잡이 )</b><br/>
       Navigation + Butterfly
    </td>
  </tr>
</table>

<br>

## 목차

1. [서비스 소개](#서비스-소개)
2. [팀원 소개](#팀원-소개)
3. [프로젝트 설계 및 구성](#프로젝트-설계-및-구성)  
   3-1. [ERD 및 구조](#데이터베이스-erd)  
   3-2. [사용 기술](#사용-기술)  
   3-3. [주요 기능](#주요-기능)  

<br>

# 서비스 소개

취업 준비생들의 필수 덕목, **자격증**!  
하지만 취업 준비를 막 시작한 사회 초년생들에게 어떤 자격증이 필요한지, 어떤 직무에서 필요하게 될지 전혀 모르는 경우가 많습니다. 막막한 상황에서 산발적인 정보들을 한 곳에 모아주는 서비스가 있습니다!

**NAVI**는 사용자의 희망 직무에 따라 필요할 자격증들을 추천해줍니다. 목표 자격증을 설정하고 같은 목표를 가진 취준생과 함께 공부할 수 있는 스터디룸까지 제공합니다. 공부 시간을 측정하고, 합격률 예측까지!

**여러분의 꿈을 응원하는 NAVI에서 취업 준비의 한 걸음을 내딛어보세요!**

<br>

# 🗓 프로젝트 기간

2025.01.06 ~ 2025.02.21

<br>


#  팀원 소개

<table align="center">
  <tr>
    <td align="center" width="18%;">
      <img src="profile4.png" alt=""/>
      <br/><sub><b>홍태휘</b><br/>
      <span>팀장</span><br/>
      <span>FE</span>
      </sub>
    </td>
    <td align="center" width="18%;">
      <img src="profile5.webp" alt=""/>
      <br/><sub><b>권희주</b><br>
      <span>BE</span>
      </sub>
    </td>
    <td align="center" width="18%;">
      <img src="profile2.jpg" alt=""/>
      <br/><sub><b>김성조</b><br>
      <span>BE</span>
      </sub>
    </td>
    <td align="center" width="18%;">
      <img src="profile3.jpg" alt=""/>
      <br/><sub><b>박수연</b><br>
      <span>FE</span>
      </sub>
    </td>
    <td align="center" width="18%;">
      <img src="profile6.png" alt=""/>
      <br/><sub><b>박해구</b><br>
      <span>BE</span>
      </sub>
    </td>
    <td align="center" width="18%;">
      <img src="profile1.jpg" alt=""/>
      <br/><sub><b>황석주</b><br>
        <span>FE</span>
      </sub>
    </td>
  </tr>
</table>

## 세부 역할

<table align="center">
  <tr>
    <td>홍태휘 (팀장)</td>
    <td>추가 정보 입력 페이지, 커뮤니티 페이지</td>
  </tr>
  <tr>
    <td>권희주</td>
    <td>DB 설계, 자격증 검색 및 상세 정보 조회, 추천 알고리즘</td>
  </tr>
  <tr>
    <td>김성조</td>
    <td>Infra, 합격 최소 요구 시간 계산 알고리즘, 사용자 통계 조회</td>
  </tr>
  <tr>
    <td>박수연</td>
    <td>메인 페이지 및 전체적인 디자인</td>
  </tr>
  <tr>
    <td>박해구</td>
    <td>DevOps, 추가 정보 입력, 커뮤니티, 화상 통화</td>
  </tr>
  <tr>
    <td>황석주</td>
    <td>자격증 검색 페이지, 스터디룸 페이지</td>
  </tr>
</table>

<br>

# 프로젝트 설계 및 구성


## 데이터베이스 ERD

<img src="navi_erd.png" width=";" alt="ERD"/>

<br>

## 사용 기술

### 운영체제
---
- **로컬 개발 환경:** 
  
  ![windows11](https://img.shields.io/badge/Windows%2011-%230079d6.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)
- **서버 운영 환경:**

  ![amazonec2](https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
  ![linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)


### IDE & Editor
---
  ![IntelliJIDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
  ![vscode](https://img.shields.io/badge/vscode%20V1.97.2-0065A9?style=for-the-badge&logo=vscode&logoColor=white)
  ![mysqlworkbench](https://img.shields.io/badge/MySQL%20Workbench-4479A1?style=for-the-badge&logo=mysql&logoColor=black)


### 버전 & 이슈 관리 및 협업 도구
---
  ![git](https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white)
  ![gitlab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)
  ![notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
  ![jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white)


### 배포 환경 및 빌드 도구
---
  ![amazonec2](https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
  ![jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)
  ![docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
  ![nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
  
  ![gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white)
  ![npm](https://img.shields.io/badge/npm-CA4245?style=for-the-badge&logo=npm&logoColor=white)

  - AWS EC2 (Ubuntu)
  - Nginx
  - Docker ( `27.5.1` ) & Docker Compose ( `v2.32.4` )
  - Jenkins (CI/CD) `2.479.3`
  - Gradle `8.11.1`
  - Npm `9.2.0`

### BackEnd
---
  ![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
  ![springboot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

  ![python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![fastapi](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

  ![openvidu](https://img.shields.io/badge/openvidu-ED8B00?style=for-the-badge&logo=vscode&logoColor=white)

- JAVA (OpenJDK `17.0.13`)
- SpringBoot `3.3.6`
- Python `3.9.21`
- FastAPI `0.155.8`
- Openvidu `2.31.0`

### FrontEnd
---
  ![typescript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
  ![vuedotjs](https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)

  ![pinia](https://img.shields.io/badge/pinia-e6e600?style=for-the-badge&logo=pinia&logoColor=white)
  ![Axios](https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white)

  ![html5](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![css3](https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![tailwindcss](https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

- TypeScript
- Vue.js (ES6) `3.5.13`
- CSS3
- HTML5
- Tailwind CSS `4.0.1`
- Pinia `2.3.1`
- Axios `1.7.9`

### DB & Storage
---
![mysql](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-005571?style=for-the-badge&logo=elasticsearch)
![amazons3](https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

- MySQL `8.0.4`
- Redis `7.4.2`
- ElasticSearch `8.17.1`
- AWS S3

## API & OpenData

- 한국산업인력공단 Open API

<br>

## 주요 기능


### 시작 페이지
---
- 소셜 로그인(구글, 네이버, 카카오)
![start_page](start.gif)

### 메인 페이지
---
- 스크랩 한 자격증 별 합격 최소 요구 시간, 다른 사용자들과의 공부 시간 비교 등 다양한 통계 정보 제공
- 스크랩 한 자격증 시험 일정과 합격 수기, 인기 스터디룸 목록 확인
![main_page](main.gif)

### 스터디룸 페이지
---
- 자격증 별 스터디룸 목록을 확인할 수 있으며, 원하는 자격증에 대한 스터디룸을 생성하고 참여할 수 있습니다.
<img src="studyroom_page.gif" alt="studyroom" width="750">

### 커뮤니티
---
- 카테고리 별 자격증 합격 수기 및 자유 게시판을 통해 다양한 정보 공유
![community](community.gif)

<br>
