# 마이슈
> 바쁜 현대인들을 위한 숏 콘텐츠 기반 뉴스 플랫폼

## 개발자
### 모바일(안드로이드)
| | [박승준](https://github.com/ootr47) | [윤석찬](https://github.com/alsdal) |
|-----------|:------------------------:|:---------------------------:|
| **프로필** | <img src="https://avatars.githubusercontent.com/u/83055885?v=4" width="150"/> | <img src="https://avatars.githubusercontent.com/u/52294696?v=4" width="150"/> |
| **기술 스택** | <img src="https://www.vectorlogo.zone/logos/android/android-icon.svg" width="40" height="40"/> | <img src="https://www.vectorlogo.zone/logos/android/android-icon.svg" width="40" height="40"/>|
| **R&R** | 팟캐스트 개발 <br> 네컷뉴스 개발 <br> 마이페이지 개발 <br> 챗봇 ui 개발 | 뉴스 메인 화면 구현 <br> 뉴스 검색 개발 <br> 뉴스 알림 개발 |

### 백엔드
| | [김진현](https://github.com/jinhyun-kimm) | [홍시은](https://github.com/XIOZ119) |
|-----------|:------------------------:|:---------------------------:|
| **프로필** | <img src="https://avatars.githubusercontent.com/u/113009472?v=4" width="150"/> | <img src="https://avatars.githubusercontent.com/u/63907578?v=4" width="150"/> |
| **기술 스택** | <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" width="40" height="40"/> | <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" width="40" height="40" /> |
| **R&R** | 챗봇 서버 개발 <br> 네컷 뉴스 서버 개발 <br> 뉴스 서버 개발 | CI/CD 파이프라인 구현 <br> 팟캐스트 서버 개발 <br> 알림 서버 개발 |

### AI*데이터 분석
| | [이승훈](https://github.com/tmdgnsle) | [한동근](https://github.com/l0o0lv) |
|-----------|:------------------------:|:---------------------------:|
| **프로필** | <img width="130" height="130" alt="image" src="https://avatars.githubusercontent.com/u/65535314?v=4" /> | <img src="https://avatars.githubusercontent.com/u/128709695?v=4" width="150"/>
| **기술 스택** | <img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" width="40" height="40"/> | <img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" width="40" height="40"/> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" width="40" height="40" />  |
| **R&R** | GA4, BigQuery 연결 <br> 데이터 EDA <br> 개인화 추천 알고리즘 | 뉴스 크롤링 자동화 <br> 뉴스 검색 ES 도입 <br> 비개인화 추천 알고리즘 |

## 프로젝트 기획 배경
최근 뉴스 소비 트렌드는 긴 텍스트 기사보다 짧고 직관적인 콘텐츠를 선호하는 방향으로 변화하고 있습니다. 특히 20‧30대는 빠르게 스크롤하며 핵심만 확인할 수 있는 SNS 기반 숏폼 뉴스를 더 많이 찾습니다.  
실제로 **한국언론진흥재단(2024) 조사 결과**에서도 20‧30대 뉴스 이용자의 47%가 소셜미디어를 통해 뉴스를 소비한다는 통계 결과가 나왔습니다, 주요 플랫폼으로는 유튜브와 인스타그램이 꼽혔습니다.  
이러한 흐름에 따라 여러 언론사들도 기존 기사 외에 인스타그램·유튜브용 짧은 콘텐츠를 함께 제작해 배포하고 있습니다. 그러나 여전히 기존 뉴스 앱은 긴 텍스트 기사 위주로 제공되어, 짧고 재미있는 콘텐츠를 원하는 사용자의 수요를 충족시키지 못하고 있습니다.  

우리는 이러한 뉴스 소비 행태의 변화와 숏폼 콘텐츠의 확산에 주목하여, **바쁜 현대인도 빠르고 흥미롭게 뉴스를 접할 수 있는 숏콘텐츠 기반 뉴스 플랫폼 ‘마이슈(My-Issue)'** 를 기획하게 되었습니다.

## 프로젝트 소개
**마이슈(My-Issue)** 는 바쁜 현대인을 위해 뉴스를 더 빠르고, 더 쉽고, 더 재미있게 전달하는 숏콘텐츠 기반 뉴스 플랫폼입니다. <br>
기존 뉴스 앱이 긴 텍스트 기사에 집중하고 있는 반면, 마이슈는 네컷 만화(네컷뉴스), 팟캐스트를 통해 사용자가 언제 어디서나 짧은 시간 안에 뉴스를 이해하고 즐길 수 있도록 설계되었습니다.

## 주요 기능
- 📰 **맞춤형 뉴스 피드(추천 뉴스)** : 사용자의 관심사를 학습해 개인화된 뉴스 제공
- 🎨 **네컷뉴스**: 복잡한 이슈도 네 컷 만화 형식으로 직관적·재미있게 전달
- 🎧 **팟캐스트**: 매일 주요 뉴스를 두 명의 진행자가 대화 형식으로 읽어주는 음성 콘텐츠
- 🔔 **맞춤형 알림**: 사용자 관심 키워드 기반 뉴스 푸시 알림
- 🔎 **HOT & 최신 뉴스**: 실시간 트렌드 반영 및 최신 소식 빠른 제공

## 화면 구성 

| **네컷뉴스** | **팟캐스트** | **홈 화면(추천)** |
|:--:|:--:|:--:|
| ![Image](/profile/네컷뉴스.gif) | ![Image](/profile/팟캐스트.gif) | ![Image](/profile/홈(추천).gif) |

## 시스템 아키텍처
![Iamge](/profile/시스템아키텍처.png)

### Environment
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat&logo=AndroidStudio&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-2C2255?style=flat&logo=intellij-idea&logoColor=white)
![VScode](https://img.shields.io/badge/Visual%20Studio%20Code-1E97E8?style=flat&logo=visual-studio-code&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-E34124?style=flat&logo=Gitlab&logoColor=white)
![Git](https://img.shields.io/badge/git-F05032?style=flat&logo=git&logoColor=white)

### Backend
![Java21](https://img.shields.io/badge/Java21-4D7896?style=flat&logo=Java&logoColor=white)
![SpringBoot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=Spring&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-012F38?style=flat&logo=Gradle&logoColor=white)
![Spring Security](https://img.shields.io/badge/SpringSecurity-6BB344?style=flat&logo=SpringSecurity&logoColor=white)

### Mobile
![Kotlin](https://img.shields.io/badge/Kotlin-B916DD?style=flat&logo=Kotlin&logoColor=white)
![Retrofit](https://img.shields.io/badge/Retrofit-45B37F?style=flat&logo=Retrofit&logoColor=white)
![KotlinCoroutines](https://img.shields.io/badge/KotlinCoroutines-5468F1?style=flat&logo=KotlinCoroutines&logoColor=white)
![Android](https://img.shields.io/badge/android-3DDC84?style=flat&logo=android&logoColor=white)
![Androidstudio](https://img.shields.io/badge/Android%20studio-3DDC84?style=flat&logo=androidstudio&logoColor=white)

### Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-306091?style=flat&logo=PostgreSQL&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-A41E11?style=flat&logo=Redis&logoColor=white)

### Search Engine
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=Elasticsearch&logoColor=white)

### Infra
![AWS](https://img.shields.io/badge/AWS-333664?style=flat&logo=aws&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-CC3631?style=flat&logo=Jenkins&logoColor=white)

### AI
![FASTAPI](https://img.shields.io/badge/fastapi-009688?style=flat&logo=fastapi&logoColor=white)
![PANDAS](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![SCIPY](https://img.shields.io/badge/scipy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![GOOGLE ANALYTICS](https://img.shields.io/badge/google%20analytics-E37400?style=flat&logo=googleanalytics&logoColor=white)
![GOOGLE BIGQUERY](https://img.shields.io/badge/google%20bigquery-669DF6?style=flat&logo=googlebigquery&logoColor=white)
![SQLALCHEMY](https://img.shields.io/badge/sqlalchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)

### Communication
![GitLab](https://img.shields.io/badge/GitLab-E34124?style=flat&logo=Gitlab&logoColor=white)
![Mattermost](https://img.shields.io/badge/Mattermost-284077?style=flat&logo=Mattermost&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=Notion&logoColor=white)
![JIRA](https://img.shields.io/badge/jira-0052CC?style=flat&logo=jira&logoColor=white)
