![Thumbnail](https://github.com/red-dev-Mark/devcamp-onboarding-project-Team-2/assets/170427166/ffb2146d-cadd-4629-8a75-32b3516ee855)

# 유학생 홈스테이 중개 서비스

## 팀 소개
|  팀원  |   담당 파트    |                     깃허브 주소                      |
| ---- | ------------- | -------------------------------------------       |
| 권혁준 |  요구사항정의서 작성 |  [red-dev-Mark](https://github.com/red-dev-Mark)  |
| 김난아 |  기능정의서 작성 |   [nanafromjeju](https://github.com/nanafromjeju)  |
| 신혜진 |  다이어그램 작성  |   [clara-shin](https://github.com/clara-shin)      |
| 송병훈 |  프로젝트정의서 작성  |   [sbs1253](https://github.com/sbs1253)            |
| 임효정 |  리드미 작성  |   [dyeongg](https://github.com/dyeongg)            |

## 프로젝트 정의

유학생 홈스테이 중개 서비스는 해외 유학생들이 안전하고 인증된 해당 국가의 홈스테이 숙소를 쉽게 찾을 수 있도록 지원하는 서비스입니다.<br>
유학생과 호스트를 매칭하고, 인증 절차를 통해 안전한 숙소를 제공하며, 사용자 리뷰와 평가를 통해 신뢰성을 높입니다.<br>
해외 유학생과 홈스테이 호스트를 대상으로 하며, 주로 유학생 소속 해외 대학교와의 연계를 통해 인증된 호스트 목록을 제공합니다.

## 설치

유학생 홈스테이 중개 서비스는 서버와 클라이언트 시스템으로 구성되며 Javascript 와 Nodejs 기반으로 구성되어있습니다.<br>
프로젝트 저장소를 다음 설명에 따라 개발자 컴퓨터에 복사하고 설치 명령을 입력하여 설치를 할 수 있습니다.

```bash
git clone https://github.com/ibare/devcamp-onboarding-template.git my-project

cd my-project

npm install
```

프로젝트를 다운로드하고 설치하기 위해선 사용자의 컴퓨터에 Git 과 Nodejs가 설치되어있어야합니다.
만약 설치되어있지 않은 도구가 있다면 다음 링크를 통해 사용자 환경에 맞는 버전을 설치해주세요.

* [Git - Downloads](https://git-scm.com/downloads)
* [Node.js — Download Node.js®](https://nodejs.org/en/download/current)

## 실행

개발자 로컬 환경에서 개발 모드로 실행하기 위해선 프로젝트 루트 디렉토리에서 다음의 명령을 실행하세요.

```bash
npm run dev 
```

## 배포

프로젝트의 배포 버전을 생성하기 위해 빌드 스크립트를 실행합니다.

```bash
npm run build:production
```

개발 환경 배포 빌드는 build:develop 스크립트를 사용해주세요. 
운영 환경 빌드는 build:production 스크립트를 사용해주세요.


## 문서

프로젝트 설계 문서는 design 디렉토리에 마크다운 파일로 기록되어있습니다.
각각의 설계 문서는 다음과 같습니다.

* 요구사항 정의서 
  * 제품이 제공해야되는 기능 요구 정의서입니다.
  * 요구사항 정의서에 기술된 기능은 최소 기능 요구사항이며 추상적일 수 있으며 기능의 구체화는 제품 구현 단계에서 이루어집니다.
* 프로젝트 정의서
  * 요구사항 정의서를 기반으로 프로젝트를 설계합니다.
* 기능 정의서
  * 사용자 스토리 기반으로 세부 기능을 정의합니다.
