---
type: Reference
source:
  - "[[_Second-Brain-설계-근거]]"
tags:
  - 사용안내
---

# Second Brain — CODE · PARA · Zettelkasten

수집한 정보가 생각과 실행으로 이어지도록 구성한 한국어 Obsidian 시작 볼트입니다. CODE의 흐름, PARA의 배치 기준, 제텔카스텐의 연결 방식을 함께 사용합니다.

**검토용 초안입니다.** 개인 노트·첨부파일·계정 설정·기존 Git 이력은 포함하지 않았습니다. 안내 17개, 템플릿 6개, 가상의 예시 4개와 새로 작성한 최소 설정으로 구성했습니다.

## 5분 시작하기

1. GitHub의 Code → Download ZIP으로 다운로드하고 압축을 풉니다.
2. Obsidian에서 **폴더를 볼트로 열기**로 압축을 푼 폴더를 선택합니다.
3. [[_Second-Brain-시작하기]]를 읽습니다. 안내와 예시 읽기는 플러그인 없이 가능합니다.
4. 자동 생성 기능을 쓰려면 설정 → 커뮤니티 플러그인에서 **Templater**, **Periodic Notes**를 설치하고 활성화합니다. 플러그인 실행 파일은 배포본에 포함하지 않습니다.
5. 아래 설정을 확인하고 노트를 만듭니다. 새로 설치한 플러그인의 버전에 따라 저장된 설정이 초기화될 수 있으므로 경로를 확인합니다.

## 템플릿 사용

Templater의 템플릿 폴더:
`20. Organize/23. Resources/📖1000. 참고자료/📚1090. Setting/📚1091. Templates`

Templater의 **Create new note from template** 명령에서 **TPL - Basic Note**를 선택하세요. Idea·Reference·Book·Project 중 하나를 고르면 목적에 맞는 본문을 만들고 폴더로 이동합니다.

프로젝트를 만들 때는 Basic의 Project 선택이 폴더와 파일명까지 처리합니다. 별도 Project 템플릿은 이미 준비한 프로젝트 노트의 본문을 만드는 용도로도 사용할 수 있습니다.

영구 노트는 `30. Express/31. Zettelkasten-PermanentNotes`에 노트를 만들고 **Insert template** 명령으로 **TPL - Permanent Note**를 넣습니다.

배포본은 파일 생성 시 자동 템플릿 적용을 꺼두었습니다. 안내 노트가 의도치 않게 템플릿으로 변하는 것을 막고, 사용할 템플릿을 직접 선택하도록 했습니다. 시스템 명령 실행도 사용하지 않습니다.

## 일간·주간·월간 기록

Periodic Notes 설정에서 아래 폴더·형식을 확인하고 각 TPL 템플릿을 지정합니다. Templater도 활성화해야 템플릿의 날짜·본문 생성 코드가 처리됩니다.

| 종류 | Periodic Notes 폴더 끝부분 | 형식 | 템플릿 |
|---|---|---|---|
| Daily | 1011. Daily | YYYY-MM-DD (ddd) | TPL - Daily Note |
| Weekly | 1012. Weekly | GGGG-[W]WW | TPL - Weekly Note |
| Monthly | 1013. Monthly | YYYY-MM | TPL - Monthly Note |

공통 상위 경로는 `20. Organize/23. Resources/📖1000. 참고자료/📚1010. Perodic Notes`입니다.
자동 적용을 끈 상태에서 생성된 내용에 `<%` 코드가 남아 있으면 Templater의 **Replace templates in the active file** 명령을 실행하세요. 주간 노트는 ISO 주차 제목(예: 2026-W45)을 기준으로 기간을 계산합니다.

## 구조와 예시

- 10. Capture: 생각과 자료의 입구, 시작 안내와 Distill 사용법
- 20. Organize: Projects·Areas·Resources·Archives
- 30. Express: 연결하고 재사용할 영구 노트

Resources의 주제 분류는 개인적 출발점이므로 자신의 관심사에 맞춰 바꿀 수 있습니다. 폴더를 변경하면 템플릿과 설정의 이동 경로도 함께 맞춰주세요.

예시는 모두 새로 작성한 가상의 내용입니다.

- [[예시 - 다음 행동을 남기는 아이디어]]
- [[예시 - 헤밍웨이 다리 참고 기록]]
- [[📦P-예시 독서 기록 실험]]
- [[예시 - 다음 행동은 작업 재개를 돕는다]]

## 검토할 부분

- 폴더와 안내가 의도한 지식 관리 철학을 충분히 전달하는지
- 처음 사용하는 사람이 예시를 따라 수집부터 활용까지 진행할 수 있는지
- 관심 분야별 폴더를 기본 제공할지, 더 일반적인 분류로 줄일지
- 공개 배포 전에 이용·수정·재배포를 허용할 라이선스를 무엇으로 정할지

현재는 검토용으로 라이선스를 확정하지 않았습니다. 책의 본문, 개인 독서 기록, 타사 플러그인 코드를 재배포하지 않습니다.

템플릿의 생성·취소·중복 파일명·특수문자·주차 경계 등 11개 시나리오를 모의 실행해 통과했고 내부 링크 117개를 확인했습니다. 실제 Obsidian에서 플러그인을 설치하고 생성하는 전체 흐름은 별도 확인이 필요합니다.
