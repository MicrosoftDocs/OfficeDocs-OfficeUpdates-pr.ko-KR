---
title: 2019년 반기 채널(대상 지정) 릴리스에 대한 보관된 릴리스 정보
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 2019년 Office 365 ProPlus에 대한 반기 채널(대상 지정) 릴리스의 릴리스 정보를 IT 전문가에게 제공합니다.
ms.openlocfilehash: 2b9b90ef7e1d9bc792be381ba35a94f883156e90
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169608"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a>반기 기업 채널(프리뷰) 릴리스에 대한 보관된 릴리스 정보

이 릴리스 정보는 Office 365용 Visio Pro, Project Online 데스크톱 클라이언트 및 Office 365 Business를 비롯한 Office 365 ProPlus의 반기 기업 채널(대상 지정) 업데이트에 포함된 새로운 기능 및 비보안 업데이트에 관한 정보를 제공합니다.

> [!NOTE]
> - Microsoft는 일정 기간 동안 반기 기업 채널(프리뷰)에 기능(및 경우에 따라 수정 사항)을 롤아웃합니다. 아래에서 설명했던 내용이 바로 보이지 않으면 곧 예측할 수 있습니다. [자세한 정보](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams는 버전 1902부터 반기 기업 채널(프리뷰)의 새 설치에 포함됩니다. 버전 1908 이상으로 업데이트 되는 경우 기존 반기 기업 채널(프리뷰) 설치에 Teams가 추가됩니다. 자세한 내용은 [Office 365 ProPlus와 함께 Microsoft Teams 배포](/deployoffice/teams-install)를 참조하세요.

## <a name="version-1908-december-10"></a>버전 1908: 12월 10일
*버전 1908 (빌드 11929.20516)*

나열된 보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제
### <a name="access"></a>Access

- 원격 테이블(예: SQL Server 테이블)로의 참조를 포함하는 통합 쿼리가 Access를 닫고 다시 시작하도록 할 수 있는 문제를 해결했습니다.

- 합계와 같은 집계가 결과를 정수로 줄일 수 있는 문제를 해결했습니다.

### <a name="excel"></a>Excel

- 스크롤 후 셀을 선택하면 잘못된 셀이 선택되었던 문제를 해결했습니다.

- OLAP PivotTable의 필터가 큐브에서 제거된 값으로 설정되었던 문제를 해결했습니다.

- 이 변경 사항은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.

- Lookup 함수에서 오류가 반환될 수 있는 문제를 해결했습니다.

- 병합된 셀이 있는 열을 삭제하는 성능이 크게 개선됨.

- 최소화된 창을 활성화하는 매크로 런타임 오류를 발생시켰던 문제를 해결했습니다.

### <a name="outlook"></a>Outlook

- SMIME 알고리듬 선택의 문제를 수정하였습니다.

- 규칙 대화 상자를 열 때 &quot;이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다&quot; 프롬프트가 표시되는 문제를 해결했습니다.

- 웹 추가 기능이 디지털 권한 관리 메시지에 액세스하지 않아야 함에도 액세스하게 만드는 문제를 해결했습니다.

### <a name="word"></a>Word

- 때때로 무한 루프로 들어가는 변경 내용 추적 기능 상의 문제를 해결했습니다.

### <a name="office-suite"></a>Office 제품군

- PowerPoint의 세로 텍스트 상자에서 가타카나 반각글자가 제대로 회전하지 않는 문제를 해결했습니다.

- Office 업데이트에서 로컬 또는 네트워크 공유 또는 Configuration Manager에서 제공하는 위치와 같은 의도된 원본 대신 Office CDN에서 파일을 예기치 않게 다운로드했을 수 있는 문제를 해결하였습니다.

- Office 고객의 보안을 위해 Microsoft Office 업데이트는 이제 SHA-2 알고리듬 만을 사용하여 서명됩니다.



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-november-22"></a>버전 1908: 11월 22일
*버전 1908(빌드 11929.20494)*


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제

### <a name="access"></a>Access

- 업데이트 쿼리를 실행하면 "쿼리가 손상되었습니다"라는 오류 메시지가 잘못 발생하는 문제가 해결되었습니다.

### <a name="excel"></a>Excel

- 파일에 광범위한 조건부 서식이 있는 경우 글꼴색 단추를 클릭하면 성능이 저하되는 문제.

- 인쇄 미리 보기의 인쇄 영역이 올바르지 않았던 문제를 해결했습니다.

- 신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 오류를 발생시킬 수 있습니다.

- 통합 문서가 열려있지 않은 상태에서 최근 파일을 검색할 때 충돌이 발생할 수 있는 문제를 해결했습니다.

### <a name="outlook"></a>Outlook

- 사용자가 계정 만들기 컨텍스트에서 지원 센터에 문의하려고 할 때 &quot;확인&quot; 버튼이 있는 빈 메시지 상자가 표시되는 문제를 해결했습니다.

- 관리자가 정책을 사용하여 UPN에 대한 자동 검색 인증 프롬프트에서 제공된 계정 전자 메일을 원하는 대로 변경할 수 있도록 했습니다. 기본적으로 AutoDiscover는 가능한 경우 계정 UPN을 선호합니다.

- 사용자가 Modern Groups에 대한 검색 실패를 보게 되는 문제를 해결했습니다.

- 사용자가 &quot;놓친 대화 메시지&quot;에서 규칙을 만들려고 할 때 충돌이 발생하는 문제를 해결했습니다.

- 사용자가 Modern Groups에 대한 검색 실패를 보게 되는 문제를 해결합니다.

### <a name="word"></a>Word

- Deskjet 프린터로 인쇄할 때 배율 문제가 발생할 수 있는 문제를 해결 했습니다.

### <a name="office-suite"></a>Office 제품군

- 온라인을 발표할 때 PowerPoint 사용자가 오류를 보내지 못하는 문제가 해결되었습니다.

- 레지스트리 무결성과 관련된 Office 업데이트 프로세스의 안정성이 향상되었습니다.

- 데이터 통신 네트워크에서 업데이트가 예기치 않게 차단되었을 수 있는 문제를 수정했습니다.

- 상대적인 기한이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정의 문제가 수정되어 후속 업데이트에 대한 상대적인 기한이 실행됩니다.

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-november-12"></a>버전 1908: 11월 12일
*버전 1908(빌드 11929.20436)*

나열된 보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제

### <a name="excel"></a>Excel

- 차트 템플릿을 사용하여 차트를 삽입할 때 미리 보기에 사용되는 색을 수정합니다.
- 시리즈 컬렉션을 변경할 때 분산형 차트가 제대로 렌더링되지 않을 수 있는 문제를 해결했습니다.
- 매크로가 실행되는 사용자 지정 속성을 변경할 때 공동 작성 작업을 중단시키는 문제를 해결했습니다.
- 함수를 동기적으로 실행하게 만드는 비동기적인 사용자 정의 함수의 성능 문제를 해결했습니다.
- 색 기준 필터링의 성능이 크게 향상되었습니다.
- 이전 버전의 Office에서 작성한 통합 문서를 현재 버전의 Office에서 열었을 때 Excel이 중단될 수 있는 문제를 해결했습니다.
- cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.

### <a name="outlook"></a>Outlook

- cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.
- 기본 일정의 항목을 그룹 일정에 복사할 때 사용 권한 오류가 발생하는 문제를 해결했습니다.
- 매우 긴 Outlook 세션에서 메모리 누수를 발생시키는 문제를 해결했습니다.
- 사용자가 특정 Safelinks와 상호 작용할 때 Outlook에서 오류가 발생하는 문제를 해결했습니다.
- 일부 AutoDiscover 응답을 처리할 때 사용자에게 오류가 발생하는 문제를 해결했습니다.
- 보조 Exchange 계정을 추가할 때 일부 사용자에게 만들어진 중복된 특수 폴더를 보이게 하였던 문제를 해결했습니다.
- 피드백 검색 환경을 중단시키는 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint

- cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.
- 안정성 픽스: 타사 추가 기능으로 인해 PowerPoint에서 오류가 발생하는 문제를 해결했습니다.

### <a name="project"></a>Project

- 모두 균등화 명령이 리소스의 초과 할당을 제대로 해결하지 못하던 문제를 해결했습니다.
- 과업에 대한 작업이 0인 과제가 있는 경우 해당 과업이 완성으로 표시되지 않고 항상 99%로 표시되는 문제를 해결했습니다.
- 읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 확인했습니다.

### <a name="word"></a>Word

- cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.
- 종료 시 앱이 중단될 수 있는 다양한 문제를 해결했습니다. 또한 특정 추가 기능 관련 오류도 해결했습니다.

### <a name="office-suite"></a>Office 제품군

- 타사의 플러그인에서 Textbox/Shape Autofit 속성과 관련된 문제를 해결했습니다.

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="october-15"></a>10월 15일

### <a name="non-security-updates"></a>비보안 업데이트

### <a name="office-suite"></a>Office 제품군
- 16.0.11929.20396 이전 빌드에 대해 2019년 10월 14일에 게시한 저장 문제를 해결하기 위해 클라우드 저장 대화 상자를 일시적으로 사용하지 않도록 설정했습니다. 이 기능은 곧 다시 활성화됩니다.

## <a name="version-1908-october-14"></a>버전 1908: 10월 14일
*버전 1908(빌드 11929.20396)*


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a>비보안 업데이트
### <a name="excel"></a>Excel

- <div>첫 번째 항목을 발견한 후 대화 상자에서 포커스가 있던 위치가 찾기 및 바꾸기로 변경되는 문제가 해결되었습니다.</div>

### <a name="office-suite"></a>Office 제품군

- 16.0.11929.20396 이전 빌드에 대해 Word, Excel 및 PowerPoint 2019 문서를 저장할 수 없는 문제를 해결했습니다.  이 문제는 새 파일을 만든 후 저장 아이콘을 클릭하거나 Ctrl + S를 눌러 "다른 이름으로 저장" 대화 상자를 표시하는 사용자에게 영향을 줍니다.

- 특정 상황에서 Office 바로 가기가 업데이트 후에 사라지는 문제를 해결했습니다.  이 업데이트는 Office 바로 가기를 게시할 때 안정성을 높입니다.

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-october-08"></a>버전 1908: 10월 8일
*버전 1908 (빌드 11929.20388)*

보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)에 나열되어 있습니다.

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a>비보안 업데이트
### <a name="excel"></a>Excel

- 일부 보호된 시트에서 하이퍼링크를 붙여 넣을 수 없는 문제를 해결했습니다.

- 추가 기능 관리자에서 검색할 시 16개 이상의 추가 기능을 표시하기 위한 문제를 수정했습니다.

- Excel 아이디어 기능에서, Win32 클라이언트에 있는 아이디어 버튼을 클릭하여 추가 기능을 로드할 때 발생하는 오류를 수정했습니다.

### <a name="outlook"></a>Outlook

- 일부 safelinks에서 간단한 호버 URLl이 표시되지 않게 하는 문제를 해결했습니다.

- Outlook에서 Python 첨부 파일도 또한 차단하기 위해 첨부 파일 차단 논리를 업데이트하였습니다.

- Outlook 프로세스에서 메모리 누수가 사용자에게 관찰되는 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint

- PowerPoint에서 공동 작성 및 오프라인 편집을 수반하는 세션에서 데이터가 손실될 수 있는 문제를 수정했습니다.

### <a name="office-suite"></a>Office 제품군

- 사용자가 파일을 열 때 발생하는 충돌 문제를 수정했습니다.

- 백스테이지의 정보 위치판에 접근성 정보가 표시 되지 않는 문제를 수정했습니다.

- 이전에 중단되었을 수 있는 다운로드를 다시 시작하여 Office 업데이트를 다운로드 시의 안정성을 개선했습니다.

- Office 고객의 보안을 위해 Microsoft Office 업데이트는 이제 SHA-2 알고리듬 만을 사용하여 서명됩니다.

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-september-10"></a>버전 1908: 9월 10일
*버전 1908 (빌드 11929.20300)*

보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)에 나열되어 있습니다.

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a>기능 업데이트
### <a name="access"></a>Access

- **더 많은 공간을 사용하여 확대/축소:** 확대/축소 상자의 크기를 키우고, 글꼴을 변경할 수 있습니다. 확대/축소에 이러한 설정이 모두 저장됩니다. [자세한 정보](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- **데이터베이스 개체에 탭 유지:** 활성 탭이 무엇인지 명확하게 구분할 수 있고, 간편하게 끌어서 순서를 변경할 수 있고, 클릭 한 번으로 데이터베이스 개체를 닫을 수 있습니다.

- **원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다. 회사 및 개인 계정 간 전환이 매우 용이합니다. [자세한 정보](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a>Excel

- **자세한 데이터 분석:** 새로운 아이디어 단추는 데이터에서 패턴을 찾아서 인텔리전트 맞춤형 제안을 만듭니다. [자세히 알아보기](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까? 파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.

- **콘텐츠 도달 범위 늘리기:** 접근성 높은 프레젠테이션을 만들어야 하나요? 진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다. 검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.

- **원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다. 회사 및 개인 계정 간 전환이 매우 용이합니다. [자세한 정보](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **생동감 있는 워크시트 보기:** 애니메이션 3D 그래픽을 삽입하여 워크북을 통해 심장 박동, 행성 궤도, 공룡 난동 모습 등을 표시합니다. [자세한 정보](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **공동 작업이 쉬워졌습니다.** 공동 작성 기능이 향상되면 조건부 서식, 셀 스타일 등을 사용하여 작업할 때 변경 내용이 공동 작업자와 원활하게 통합됩니다.

- **유사한 열의 테이블 조인:** 가져오기 및 변환 기능(파워 쿼리)은 테이블 병합을 위해 열을 비교하는 경우 근사 텍스트 매칭 논리(퍼지 매칭)를 특징으로 합니다. [자세한 정보](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **파워 쿼리 기능 향상을 통한 신속한 코드:** 자동 완성 및 구문 색상을 사용하여 신속하게 코드를 완성하세요. 함수, 열, 매개 변수를 쉽게 검색할 수 있습니다.

- **검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다. 그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다. [자세한 정보](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a>Outlook

- **메시지를 전달하는 동안에도 작업 지속 가능:** Outlook이 이제 백그라운드에서 메시지를 전달합니다. 따라서 폴더 간에 많은 메시지를 주고 받는 동안에도 작업을 계속할 수 있습니다.

- **연달아 있는 모임 사이에 시간 넣기:** 모임이 기본적으로 5~10분 일찍 끝나도록 설정하여 참석자에게 잠시 숨을 돌리거나 장소를 이동할 시간을 줄 수 있습니다.

- **밈하는 항목 표시:** 텍스트 또는 정적 이미지로 가능하지 않은 경우 애니메이션 GIF를 의도하는 바를 나타냅니다. [자세히 알아보기](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **Outlook 사용자 환경이 업데이트됨:** 출시 예정을 사용하여 이전에 미리 볼 수 있었던 간소화된 환경은 가장 중요한 작업에 집중할 수 있도록 설계되었습니다. [자세한 정보](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **보통 또는 더 좁은 간격 선택:** 더 좁은 간격을 사용하면 항목 간에 더 넓은 공백을 할지 또는 더 좁은 레이아웃을 사용하여 더 많은 항목을 표시할지를 결정할 수 있습니다.

- **사용자 지정이 가능한 간소화된 리본:** 가장 많이 사용하는 단추가 한 행에 표시되어 간편합니다. 클래식 및 요약 보기 간의 간편한 전화 및 명령 고정/고정 해제 [자세한 정보](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **빠르게 계정 추가:** 계정 설정 기능이 향상되어 Outlook에서 2단계 인증을 사용하여 Outlook.com 및 Gmail 계정을 추가하는 것이 그 어느 때보다 쉬워졌습니다. [자세한 정보](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **자주 하는 작업 선택:** 플래그 및 삭제를 사용하지 않나요? [보관] 또는 [읽은 상태로 표시]는 어떤가요? 가장 많이 사용하는 명령으로 빠른 작업 메뉴를 사용자 지정합니다.

- **동기화 제한 문제 해결:** Outlook의 기능 향상으로 폴더 제한이 사라지고 공유된 편지함을 동기화할 수 있습니다.

- **검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다. 그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다. [자세한 정보](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a>PowerPoint

- **대상 그룹에 퀴즈를 내거나 설문 조사하기:** 슬라이드에 퀴즈 또는 설문 조사를 넣습니다. Office가 응답을 수집하고 저장합니다. [자세한 정보](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까? 파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.

- **콘텐츠 도달 범위 늘리기:** 접근성 높은 프레젠테이션을 만들어야 하나요? 진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다. 검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.

- **변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.

- **그 어느 때보다 쉬운 온라인 비디오 삽입:** 슬라이드에 Vimeo 또는 YouTube 비디오를 삽입해야 하나요? 비디오 페이지 링크만 있으면 됩니다. [자세히 알아보기](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **더 나은 변신:** 셰이프에 이름을 지정하여 셰이프의 모핑 과정을 더 효율적으로 관리하세요. [자세한 정보](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다. 회사 및 개인 계정 간 전환이 매우 용이합니다. [자세한 정보](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **온라인 비디오의 새로운 홈:** 조직의 모든 사람이 볼 수 있도록 비디오를 Microsoft Stream에 저장하세요. 비디오 링크를 삽입하고 파일 크기의 일부로 멀티미디어 프레젠테이션을 즐겨보세요. [자세한 정보](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다. 그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다. [자세한 정보](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a>Project

- **원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다. 회사 및 개인 계정 간 전환이 매우 용이합니다. [자세한 정보](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **깨진 Excel 링크 해결:** 데이터 시각화 도우미 다이어그램에 연결된 Excel 통합 문서를 찾을 수 없습니까? 링크를 다시 연결하면 정상으로 돌아옵니다. [자세히 알아보기](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **기본적으로 제공되는 Azure 스텐실:** 수십 개의 Azure 스텐실을 사용하여 클라우드 앱을 디자인하거나 아키텍처를 계획합니다. [자세한 정보](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **놀랄 만한 수준의 데이터 순서도:** 데이터 시각화 도우미 순서도를 위한 멋진 새 레이아웃은 깔끔하고 정돈되어 있으며 이해하기 쉽습니다. 디자인 탭을 클릭하여 옵션을 확인하세요.

- **원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다. 회사 및 개인 계정 간 전환이 매우 용이합니다. [자세한 정보](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **프로세스 다이어그램을 Word로 내보내기:** Word 문서에 셰이프 및 메타데이터 등의 다이어그램 콘텐츠를 자동으로 추가합니다. 그런 후 문서를 사용자 지정하여 프로세스 지침 및 작업 설명서를 만듭니다. [자세한 정보](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **Power BI에서 Visio 시각적 개체 내보내기** Power BI 보고서를 PDF, PowerPoint 파일 등으로 내보낼 때 Power BI용 Visio 시각적 개체가 올바르게 표시됩니다. [자세한 정보](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **잉크 편집기로 자연스럽게 편집 가능:** 펜을 사용하여 단일 스트로크로 단어를 분할 또는 조인하거나, 새 줄을 추가하거나, 단어를 삽입할 수 있습니다. [자세한 정보](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **평범한 문서를 훌륭한 문서로 개선하기:** 모든 장치에서 문서가 잘 보이도록 공유하기 쉬운 대화형의 웹 페이지로 변환합니다. [자세히 알아보기](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **\@@멘션으로 주의 끌기:** 메모에 @멘션을 사용하여 입력이 필요하다는 사실을 동료들에게 알립니다. [자세한 정보](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **라인 포커스로 가독성 개선:** 부드럽게 줄 단위로 문서를 넘길 수 있습니다. 한 번에 볼 때 1줄, 2줄, 또는 5줄에 포커스를 두도록 조정합니다. [자세히 알아보기](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까? 파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.

- **변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.

- **콘텐츠 도달 범위 늘리기:** 접근성 높은 문서를 만들어야 하나요? 진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다. 검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.

- **더 많은 페이지 색상을 사용하도록 학습 도구 모드에 추가 지원 제공:** Word의 학습 도구에 페이지 테마 색상에 대한 지원이 추가되어, 페이지의 배경색을 변경할 수 있습니다. 많은 사람들이 흑백 또는 검정색 배경으로 읽는 것에 어려움을 느끼고 있으므로 PC 및 Mac의 Word에서 색상 선택을 확장했습니다.

- **원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다. 회사 및 개인 계정 간 전환이 매우 용이합니다. [자세한 정보](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- **검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다. 그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다. [자세한 정보](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a>Office 제품군

- **Microsoft Teams 설치:** Teams가 Office 365 ProPlus의 기존 설치에 추가되었습니다. [자세한 정보](/deployoffice/teams-install)

- **변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.

- **개인 정보 제어:** 진단 데이터 및 연결된 환경에 대한 업데이트 및 향상된 신규 컨트롤 작업 [자세한 정보](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- **Office 아이콘이 새롭게 단장했습니다.** 간단하고 강력하며 지능적인 Office 환경을 반영하여 Office 아이콘이 다시 디자인되었습니다.

- **Microsoft Teams 설치:** Microsoft Teams는 기본적으로 Office 365 ProPlus 기존 설치에 설치됩니다. [자세한 정보](/DeployOffice/teams-install)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a>비보안 업데이트
### <a name="excel"></a>Excel

- 도형 또는 양식 컨트롤에 할당된 매크로가 잘못된 오류 메시지를 표시하거나 잘못된 대상 범위에서 작동하는 Excel의 문제가 해결되었습니다.

- 다른 사용자와의 공동 작성 세션에서 실패할 수 있는 동안 피벗 테이블의 정렬 방식을 변경하고 새로 고치는 문제가 해결되었습니다.

- 셀을 삽입하거나 삭제하는 경우 폭포 차트와 깔때기형 차트가 테이블로 동기화되지 않는 문제를 해결했습니다.

- 사용자에게 통합 문서를 다시 열어서 변경 내용을 적용하라는 메시지가 표시되는 Excel의 병합 충돌 문제를 해결했습니다.

- 다른 사용자와 공동 작성하는 경우 표의 옆에 잘라내어 붙여 넣는 작업이 실패하는 문제를 해결했습니다.

### <a name="outlook"></a>Outlook

- 사서함을 기본 인증에서 최신 인증으로 업그레이드한 사용자가 Outlook 프로필에 연결된 잘못된 계정으로 끝나는 문제가 해결되었습니다.

- POP3 사용자의 하위 집합에서 설정에 관계없이 일반 텍스트로 서식이 지정된 모든 전자 메일을 표시하는 문제가 해결되었습니다. 이 수정은 HTML 서식이 지정된 메시지의 보기를 복원합니다.

- 사용자가 화면 판독기를 통해 위치 제안에 액세스할 수 없게 된 문제가 해결되었습니다.

- 일부 사용자가 Outlook에 대한 클라우드 설정을 검색할 때 인증 오류가 발생하는 문제가 해결되었습니다.

- 대리인이 이미 모임 요청에 응답했는지 여부에 대해 관리자에게 모호함을 야기하는 문제가 해결되었습니다.

- 특정 시나리오에서 Outlook 사용자가 “비밀번호 필요”상태에 멈춰있는 문제가 해결되었습니다.

- 현재 폴더 검색이 간헐적으로 실패하는 문제가 해결되었습니다.

- 사용자에게 회의실의 가용 시간 이외의 시간에 발생한 모임에 대해 회의실 제안이 나타나는 문제가 해결되었습니다.

- 사용자가 클라우드 첨부를 사용할 때 “해당 파일을 찾을 수 없습니다. 경로 및 파일 이름이 맞는지 확인하세요”의 오류 메시지가 나타나는 일시적인 서비스 문제가 해결되었습니다. [자세한 정보](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- Outlook에서 OneDrive 또는 Sharepoint로 업로드 된 파일의 이름이 밑줄로 인해 여러 개의 문자로 변경되는 오류가 해결되었습니다.

- 메일의 제목 줄이 너무 작을 경우 비영어 사용자를 위한 문제가 해결되었습니다.


### <a name="powerpoint"></a>PowerPoint

- 일부 추가 기능이 차트의 도형 주변에 예기치 않은 오류를 발생시키는 문제가 해결되었습니다.

- PowerPoint 비디오 컨트롤에 대해 액세스 가능한 이름을 복원하는 문제가 해결되었습니다.

- 일부 애니메이션이 시작되지 않도록 하는 문제를 해결했습니다.

### <a name="project"></a>Project

- Windows 7 사용자가 Project Web App 및 SharePoint 사이트에서 프로젝트를 열 수 있도록 하는 문제가 해결되었습니다.


### <a name="visio"></a>Visio

- Visio에서 SVG로 내보내기가 다양한 도형에서 작동하지 않습니다.

### <a name="word"></a>Word

- 사용자가 Word 문서에서 공동 작업하는 동안 오류 메시지를 받는 문제가 해결되었습니다.

- SharePoint 2016에 저장된 파일을 공유하려고 할 때 "죄송합니다. 어떤 요인으로 인해 이 파일을 공유할 수 없습니다."라는 메시지가 표시되는 문제가 해결되었습니다.


### <a name="office-suite"></a>Office 제품군

- 일부 인스턴스에서 동기화 엔진 백업 Sharepoint 파일에 ‘저장됨’이 표시되지만 실제로 변경 내용이 저장되지 않은 문제가 해결되었습니다.

- 큰 트리뷰가 실패하는 문제가 해결되었습니다.

- 히라가나와 한자에서 새로운 연호 "레이와"의 철자가 틀리거나 비문법적 표현으로 잘못 식별되는 문제가 해결되었습니다.


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1902-august-13"></a>버전 1902: 8월 13일
*버전 1902 (빌드 11328.20392)*

보안 업데이트가 [여기](./microsoft365-apps-security-updates.md)에 나열되어 있습니다.

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
- 표에서 필터링된 슬라이서와 필터링되지 않은 슬라이서 모두에 대해 필터 지우기 아이콘이 표시되는 문제가 해결되었습니다.

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
- 사서함을 기본 인증에서 최신 인증으로 업그레이드한 사용자가 Outlook 프로필에 연결된 잘못된 계정으로 끝나는 문제가 해결되었습니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
- 문서에서 다른 사용자와 공동 작업 중에 응용 프로그램이 예기치 않게 종료되는 문제가 해결되었습니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
- 필드를 업데이트하는 동안 VBA가 느려지는 문제가 해결되었습니다.
- 일부 DOC 파일을 열 때 파일이 손상되었다고 표시되는 문제가 해결되었습니다.
- 문서에서 다른 사용자와 공동 작업 중에 응용 프로그램이 예기치 않게 종료되는 문제가 해결되었습니다.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
- 특정한 경우에 Office JavaScript 라이브러리에서 API 설정이 수행되지 않는 문제가 해결되었습니다. [자세한 정보](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)

## <a name="version-1902-july-09"></a>버전 1902: 7월 9일
*버전 1902(빌드 11328.20368)*

보안 업데이트가 [여기](./microsoft365-apps-security-updates.md)에 나열됨


### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
- 필터링된 Excel 행을 삭제하는 경우 지나치게 속도가 느려지는 문제가 해결되었습니다.
- 두 손가락으로 스크롤하면 회색 직사각형이 워크시트에 그려지고 Excel이 중단되는 문제가 해결되었습니다.


### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
- 중국어 단어를 선택할 수 있도록 IME 후보 창이 열려 있도록 유지하는 것이 아니라 가끔씩 Outlook에서 영어 핀인 문자를 삽입하는 문제를 해결합니다.
- 해당 회의실의 가용성을 초과하여 예약된 모임의 회의실이 제안되는 문제를 해결합니다.
- 사용자가 대신에 마스터 되풀이 항목을 열기 위해 모임 되풀이 항목에 대한 예외 열기를 시도하는 문제를 해결합니다.
- 지운 편지함 폴더의 항목에 대해 만료 날짜가 잘못 계산되는 문제를 해결합니다.


### <a name="teams-non-security-updates"></a>Teams: Excel: 비보안 업데이트

- 이제 Teams 설치자가 설치 완료 후 자동 실행을 해제하는 정책을 사용할 수 있습니다.


### <a name="visio-non-security-updates"></a>Visio: 비보안 업데이트

- riched20.dll을 찾을 수 없다고 표시된 오류 메시지에서 보듯이, Visio용 ActiveX 솔루션이 Office 365에서 작동하지 않는 문제를 해결합니다.


### <a name="word--non-security-updates"></a>Word: 비보안 업데이트

- 서식 파일 검색 창을 비활성화할 수 있도록 GPO 설정이 수정되었습니다.
- 오프라인 상태에서 서버 전용 문서를 편집 한 후 일부 변경 내용이 분실되는 문제를 해결했습니다.
- 문서 속성에 빠른 문서 요소를 사용하는 경우 성능이 향상되었습니다.
- 서버의 첫 번째 다운로드 수정 버전이 실패하는 문제가 해결되었습니다.


### <a name="office-suite--non-security-updates"></a>Office 제품군: 비보안 업데이트

- 추가 Office 제품이나 언어 팩을 설치할 때 공유 컴퓨터 활성화를 사용하는 장치가 예기치 않게 사용자 기반 활성화로 되돌아가는 문제를 해결했습니다.
- 프록시 인증이 SYSTEM으로 실행될 때 Office 업데이트를 차단하는 문제가 해결되었습니다.
- Office 추가 기능이 사용자 프로필 변경 내용에서 사라지는 문제를 해결했습니다.


## <a name="version-1902-june-11"></a>버전 1902: 6월 11일
*버전 1902(빌드 11328.20318)*
<br/>보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)에 나열됩니다.

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
 - XML 맵이 포함된 파일을 PDF로 저장할 때 충돌이 발생하는 문제를 해결했습니다.
 - 잘못된 시트 이름이 포함된 통합 문서를 로드할 때 외부 링크가 제거되는 문제를 해결했습니다.
 - Excel에서 카메라 도구를 사용하면 스프레드시트가 중단되는 문제가 수정되었습니다.
 - 셀을 삽입하거나 삭제하는 경우 폭포 차트와 깔때기형 차트가 테이블로 동기화되지 않는 문제를 해결했습니다.
 - 테이블에 따라 다른 시트의 배열식을 사용하여 워크시트 계산을 하는 동안 데이터 테이블을 다시 계산할 때 충돌이 발생하는 문제를 해결했습니다. 
 - 파일을 체크 아웃 하지 않고 암호로 보호 된 통합 문서를 SharePoint에서 열지 못하도록 하는 문제가 해결 되었습니다.
 - 자동 저장을 공유하거나 토글하는 경우 BeforeSave 이벤트를 처리하도록 변경되었습니다.

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
 - "그룹화 기준"에 두 번째 조건을 추가할 때 고객에게 작업이 표시되지 않는 문제를 해결했습니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
 - 문서에 대해 현재 공동 작업 중인 문서를 공유하면 확장자가 .asd인 파일이 생성되는 문제가 해결되었습니다.
 - 메모가 임의의 작성자에 속하는 문제가 해결되었습니다.
 - 문서를 확인할 때 서명 제거에 발생하는 문제가 해결되었습니다.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
 - "실행 취소" 작업 후 VBA에서 잘못된 도형 채우기 상태를 보고할 때 발생하는 버그를 해결했습니다.


## <a name="version-1902-may-14"></a>버전 1902: 5월 14일
*버전 1902(빌드 11328.20286)*

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
 -  Excel에서 카메라 도구를 사용하면 스프레드시트가 중단되는 문제가 수정되었습니다.
 - 차트 시트가 있는 비활성 창에서 마우스 스크롤 휠을 사용하면 충돌이 발생하는 문제가 해결되었습니다.
 - SharePoint에서 스프레드시트를 가져올 때 "예기치 않은 오류" 라는 메시지가 표시되는 문제가 해결되었습니다.
 - 규칙 및 사용자 지정 보기에 이름을 사용하는 조건부 서식이 포함된 통합 문서를 열 때 Excel이 중단되는 문제가 해결되었습니다.
 - 255자보다 긴 수식으로 데이터 유효성 검사를 사용하여 매크로를 실행하면 런타임 오류가 발생하기도 했습니다. 이제 이 문제가 해결되었습니다.
 - 다른 통합 문서에 연결된 피벗 테이블을 포함하는 파일이 느리게 로드되는 문제가 발생 했습니다. 이 문제가 해결되었습니다.
 - HTML 파일을 열고 "파일 형식 및 확장명이 일치하지 않음" 오류가 수신되는 문제가 해결되었습니다.
 - 비활성 창에서 마우스 휠을 스크롤할 때 발생하는 문제를 해결하기 위해 변경되었습니다.  

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
 - 마이그레이션된 항목의 일부 필드를 편집할 수 없는 문제를 처리합니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
- 드물게 사용자 변경 사항을 클라우드에 업로드할 때 PowerPoint가 중지되는 문제가 수정되었습니다.

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
 - Lync(비즈니스용 Skype)에서 참가자가 7 명 이상인 온라인 모임에서 모임 창이 사라질 수있는 문제가 해결되었습니다.
 - 다른 Office 응용 프로그램에 로그인할 때 사용하는 자격 증명으로 비즈니스용 Skype에 로그인하세요.
 - 공유 컴퓨터 인증으로 설치할 때 비즈니스용 Skype 앱을 적절하게 인증하세요.

### <a name="visio-non-security-updates"></a>Visio: 비보안 업데이트
 - Dynamic DPI 기능을 비활성화하여 Visio를 확장하는 타사 솔루션의 깨진 창 계층 문제를 초래하는 문제가 해결되었습니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
 - SharePoint에서 추가된 관련 사용자를 편집하면 충돌할 수 있는 문제가 수정되었습니다.
 - Word가 시작할 때 “리소스를 로드하지 못했습니다” 대화 상자가 표시되는 문제가 수정되었습니다.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
 - 이 문제는 Apache WebDAV 폴더에 파일을 저장할 수 없는 문제를 해결합니다.
 - 고객이 일부 클라우드 저장 파일을 열 때 Office가 갑자기 닫히는 문제를 해결합니다.
 - 히라가나와 한자에서 새로운 연호 "레이와"의 철자가 틀리거나 비문법적 표현으로 잘못 식별되는 문제가 수정되었습니다.
 - Windows 10에서 최근 파일 목록이 많은 사용자에게 삭제된 것처럼 표시되는 문제가 수정되었습니다.
 - 진행 중인 관리자 트리거 업데이트가 있는 경우에도 최종 사용자에게 Office 업데이트 비즈니스 막대가 표시되는 문제가 수정되었습니다.
 - 간헐적으로 발생하는 빈 로그인 프롬프트와 관련된 문제가 수정되었습니다.
 

## <a name="version-1902-april-9"></a>버전 1902: 4월 9일
*버전 1902(빌드 11328.20230)*

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트

- 정의된 이름으로 끝나는 수식이 포함된 셀에서 Tab 키를 누르면 다음 셀로 이동하지 않는 문제가 해결되었습니다.
- 셀 서식으로 인해 파일 크기가 불필요하게 커지는 문제를 해결했습니다.
- 통합 문서 사이에 피벗 테이블을 자르고 붙여넣으면 함께 작업하는 다른 사람을 위한 피벗 테이블 없이 데이터가 붙여넣기되는 문제가 해결됨.

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트

- 시스템 작업 표시줄이 화면의 왼쪽이나 위쪽에 있을 때 윈도우가 올바른 위치에 나타나지 않는 문제가 수정되었습니다.
- 연락처 카드에 사진을 로드 할 때 고객에게 충돌이 발생하는 문제를 해결합니다.
- 일부 고객이 Office 응용 프로그램을 시작할 때 충돌을 일으키는 문제를 해결합니다.
- 시스템 작업 표시줄이 화면의 왼쪽이나 위쪽에 있을 때 윈도우가 올바른 위치에 나타나지 않는 문제가 수정되었습니다.
- 마이그레이션된 항목의 일부 필드를 편집할 수 없는 문제를 처리합니다.

### <a name="visio-non-security-updates"></a>Visio: 비보안 업데이트

- Dynamic DPI 기능을 비활성화하여 Visio를 확장하는 타사 솔루션의 깨진 창 계층 문제를 초래하는 문제가 해결되었습니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트

- 파일이 읽기 전용 모드로 열리고 '정보'창에서 '다른 이름으로 저장'을 클릭하면 저장 UI가 표시되도록 문제가 해결됩니다.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트

- Office 업데이트의 일부가 배달 최적화 피어 캐싱을 사용하지 않는 문제가 해결되었습니다. [자세한 정보](/windows/deployment/update/waas-delivery-optimization)
- Office 배포 도구를 사용하여 Office를 설치하고 대소 문자가 일치하지 않는 경우, 제품이 제거되거나 활성화되지 않을 수 있는 버그를 수정합니다.
- Windows 10 (버전 1803 이상) 장치에서 과도한 로그인 프롬프트를 유발하는 문제가 해결되었습니다.
- 링크된 그림을 다운로드 할 때 원인이 되는 고정 회귀의 중단
- Word, Excel, PowerPoint에 붙여넣은 대형 EMF 파일의 흐림 수정.
- 몇가지 케이스에서 문서가 읽기전용으로 열리는 등 버전 기록 분석 논리에서 버그가 수정.

## <a name="version-1902-march-12"></a>버전 1902: 3월 12일
*버전 1902(빌드 11328.20158)*

### <a name="access-feature-updates"></a>Access: 기능 업데이트

- **연결된 테이블 새로 고침, 다시 연결 또는 제거** 업데이트된 연결된 테이블 관리자에서 모든 데이터 원본 및 연결된 테이블을 관리할 수 있습니다. [자세한 정보](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **검은색으로 페인트, 회색으로 페인트:** Access의 모양을 원하는 만큼 자주 변경할 수 있습니다. 색상형, 진한 회색, 검은색 또는 흰색의 네 가지 테마 중에서 선택할 수 있습니다. [자세히 알아보기](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **새로운 모습의 Office:**  Office 앱의 아이콘이 최신 아이콘으로 업데이트되어 더 간편하고 접근성이 높아졌습니다. 또한 Office 앱에서 사용할 수 있는 풍부한 공동 작업 기능이 두드러지게 표시되도록 리본 디자인이 업데이트되었습니다.

### <a name="excel-feature-updates"></a>Excel: 기능 업데이트

- **빠른 시작** 새로 디자인 된 시작 페이지는 최근에 열어 본 문서를 앞면과 가운데에 배치합니다. 더 적은 클릭으로 파일로 이동하고 여기에서 계정 설정 또는 옵션을 엽니다.
- **메모를 사용하여 공동 작업:** 기본 제공 회신 상자를 사용하여 스프레드시트에서 바로 대화를 진행합니다. [자세한 정보](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **새로운 모습의 리본 아이콘:** 모든 기능은 동일하니 걱정하지 마세요. 새 아이콘은 모든 크기의 화면에서 잘 보입니다. [자세한 정보](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **필터가 적용된 SVG 삽입:** Office 사용자는 이제 필터가 적용된 SVG를 삽입할 수 있습니다. [자세히 알아보기](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **그림 뒤에 있는 내용 표시:** 워크시트에 그림을 넣고, 사전 설정을 선택하고, 투명도 변경을 확인합니다. 바로 이 기능으로요! [자세히 알아보기](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **모든 가져오기 및 변환 팬 호출:** 가져오기 및 변환 작업을 많이 사용하는 편이라면 개선된 예제의 열 기능으로 유용하게 작업할 수 있습니다. 또한 많은 커넥터도 개선되었습니다. [자세한 정보](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다. [자세한 정보](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **빠른 조회** 더 빠른 답변을 얻을 수 있도록 VLOOKUP, HLOOKUP 및 MATCH 계산을 가속화했습니다. [자세한 정보](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook: 기능 업데이트

- **소리내어 읽기를 사용하여 전자 메일 듣기:** Outlook에서 텍스트를 강조 표시하며 전자 메일을 소리내어 읽어 줍니다. 소리내어 읽기를 설정하려면 접근성 설정으로 이동하세요. [자세히 알아보기](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **핸즈 프리 입력:** 마이크가 있나요? 받아쓰기를 클릭하고 말하는 동안 Outlook에 입력되는 내용을 확인하세요. [자세한 정보](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **새로운 모습의 리본 아이콘:** 모든 기능은 동일하니 걱정하지 마세요. 새 아이콘은 모든 크기의 화면에서 잘 보입니다. [자세한 정보](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **SMIME 암호화 및 서명된 전자 메일에서 기본적으로 외부 콘텐츠 다운로드 차단:** SMIME 프로토콜의 취약성으로 인해 Outlook이 SMIME을 통해 암호화되거나 서명된 메시지의 외부 콘텐츠 다운로드를 차단합니다. 사용자는 보안 취약성을 보호하기 위해 Outlook UI를 통해 한 번의 클릭으로 외부 콘텐츠를 다운로드할 수 없습니다. 옵션 대화 상자에 사용자가 이전 동작으로 되돌릴 수 있도록 허용하는 새 옵션이 있습니다.
- **모임 전달 해제:** 참석자가 모임을 다른 사용자에게 전달하지 못하도록 합니다. 리본으로 이동한 후 응답 옵션을 클릭하면 됩니다. [자세한 정보](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **일정 도우미의 사용자 제안:** 모임을 예약할 때 참석자가 추가하는 권장 사항을 참조하세요. 이제 일정 도우미와 받는 사람 줄 사이를 전환할 필요가 없습니다. [자세히 알아보기](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **더욱 간편해진 회의실 예약:** 둘 이상의 회의실 목록을 사용하여 회의실을 찾고, 선택한 회의실을 그대로 유지하면서 목록을 전환합니다.
- **되풀이 범위의 새로운 기본값:** 되풀이 대화 상자에서 되풀이 범위의 기본값은 원래 "종료 날짜 없음"이었습니다. 이 기본값을 사용하면 기간이 긴 되풀이를 손쉽게 만들 수 있었지만, 시간이 지나면 손상될 가능성이 있었습니다. 기본값이 일정 관리의 권장 모범 사례를 따르도록, 이제 되풀이 대화 상자의 기본값이 "종료 날짜"로 변경됩니다.
- **Outlook 미리 알림 대화 상자에서 Teams 모임에 참가:** Outlook이 사용자에게 예정된 모임을 미리 알릴 때 예정된 모임이 Teams 온라인 모임인 경우 온라인 참석 단추를 표시합니다. 이는 Outlook 미리 알림 대화 상자의 비즈니스용 Skype 모임 참가 기능과 비슷합니다.
- **지난 이벤트에 대한 미리 알림 표시 안 함:** 이벤트가 종료된 후에 이벤트의 미리 알림을 자동으로 해제하도록 일정을 설정할 수 있습니다. [자세한 정보](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **안전한 링크 뒤에 URL 표시:** 안전한 링크는 전자 메일에 수신된 악의적인 URL로부터 보호하지만 원래 URL을 숨깁니다. 원래 URL을 보려면 URL에 마우스를 올리세요. Advanced Threat Protection 라이선스가 필요합니다. [자세한 정보](https://products.office.com/exchange/advance-threat-protection)
- **확대/축소 및 고정:** 메시지를 읽을 때마다 확대/축소를 조정하지 않고, 모든 메시지에 사용할 기본값을 선택합니다. [자세한 정보](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **메시지 암호화: 암호화 전용 IRM 정책:** Office 365 메시지 암호화 사용자를 위해 옵션 > 권한 메뉴에 새로운 암호화 전용 옵션이 표시됩니다. 이 옵션을 사용하여 메시지를 암호화하고 조직 내부 또는 외부의 원하는 사람에게 메시지를 보낼 수 있습니다.
- **숨은 참조에 포함되어 있을 경우 표시되는 경고:** 내가 숨은 참조에 포함되어 있을 때 실수로 메일에 전체 회신하기 전에 숨은 참조 정보 팁이 경고를 표시합니다.
- **더 스마트해진 받는 사람: 줄:** 받는 사람: 줄을 클릭하여 메시지에 주소를 지정하려고 하면 선택할 수 있는 추천 받는 사람이 표시됩니다. 또한 사진도 확인할 수 있으므로 올바른 사람에게 보내는지도 알 수 있습니다. [자세한 정보](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **필터가 적용된 SVG 삽입:** Office 사용자는 이제 필터가 적용된 SVG를 삽입할 수 있습니다. [자세히 알아보기](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다. [자세한 정보](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint: 기능 업데이트

- **빠른 시작** 새로 디자인 된 시작 페이지는 최근에 열어 본 문서를 앞면과 가운데에 배치합니다. 더 적은 클릭으로 파일로 이동하고 여기에서 계정 설정 또는 옵션을 엽니다.
- **핸즈 프리 입력:** 마이크가 있나요? 받아쓰기를 클릭하고 말하는 동안 PowerPoint에 입력되는 내용을 확인하세요. [자세한 정보](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **새로운 모습의 리본 아이콘:** 모든 기능은 동일하니 걱정하지 마세요. 새 아이콘은 모든 크기의 화면에서 잘 보입니다. [자세한 정보](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다. [자세한 정보](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **생생한 색상의 하이퍼링크:** 이제 파란색 외의 다양한 색상으로 하이퍼링크를 표시할 수 있습니다. 원하는 글꼴 색을 적용해 보세요. [자세한 정보](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **슬라이드에 생동감 주기:** 화면에서 애니메이션 3D 그래픽을 삽입하여 심장 박동, 행성 궤도 및 공룡 난동 모습을 표시합니다. [자세한 정보](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **스케치를 세련되게 변형:** 손으로 그린 텍스트와 도형을 세련된 다이어그램으로 바꾸어 드립니다. 시작하려면 잉크 스트로크만 선택하면 됩니다. [자세히 알아보기](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **그림 뒤에 있는 내용 표시:** 워크시트에 그림을 넣고, 사전 설정을 선택하고, 투명도 변경을 확인합니다. 바로 이 기능으로요! [자세히 알아보기](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Microsoft Stream에 게시:** Microsoft Stream을 사용하여 조직 내에서 프레젠테이션을 비디오로 더 안전하게 공유할 수 있습니다. [자세한 정보](https://support.office.com/article/C140551F-CB37-4818-B5D4-3E30815C3E83)
- **4K 비디오로 내보내기:** 프레젠테이션을 동영상으로 내보낼 때 4K 해상도를 선택할 수 있습니다.  [자세한 정보](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **필터가 적용된 SVG 삽입:** Office 사용자는 이제 필터가 적용된 SVG를 삽입할 수 있습니다. [자세히 알아보기](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **이제 큰 파일이 열리는 속도 향상:** OneDrive 또는 SharePoint에 저장된 파일을 열 때 이미지, 비디오 및 다른 큰 요소가 백그라운드에서 계속 다운로드됩니다.

### <a name="word-feature-updates"></a>Word: 기능 업데이트

- **빠른 시작** 새로 디자인 된 시작 페이지는 최근에 열어 본 문서를 앞면과 가운데에 배치합니다. 더 적은 클릭으로 파일로 이동하고 여기에서 계정 설정 또는 옵션을 엽니다.
- **핸즈 프리 입력:** 마이크가 있나요? 받아쓰기를 클릭하고 말하는 동안 Word에 입력되는 내용을 확인하세요. [자세한 정보](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **문서에 생동감 주기:** 페이지에서 애니메이션 3D 그래픽을 삽입하여 심장 박동, 행성 궤도 및 공룡 난동 모습을 표시합니다. [자세히 알아보기](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **새로운 모습의 리본 아이콘:** 모든 기능은 동일하니 걱정하지 마세요. 새 아이콘은 모든 크기의 화면에서 잘 보입니다. [자세한 정보](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **그림 뒤에 있는 내용 표시:** 워크시트에 그림을 넣고, 사전 설정을 선택하고, 투명도 변경을 확인합니다. 바로 이 기능으로요! [자세히 알아보기](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **필터가 적용된 SVG 삽입:** Office 사용자는 이제 필터가 적용된 SVG를 삽입할 수 있습니다. [자세히 알아보기](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다. [자세한 정보](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **LinkedIn의 도움을 받아 최상의 이력서 또는 CV를 작성하세요.** 이력서 도우미를 사용하여 지정된 직책에 대한 경력 사항, 추천 기술 등을 확인하세요. [자세한 정보](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project: 기능 업데이트

- **작업 보드 카드에 자세한 정보 표시:** 제목만으로 이야기를 전달하지 못할 경우 중요한 세부 사항을 표시하도록 작업 보드 카드를 사용자 지정합니다. [자세한 정보](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **새로운 모습의 Office:**  Office 앱의 아이콘이 최신 아이콘으로 업데이트되어 더 간편하고 접근성이 높아졌습니다. 또한 Office 앱에서 사용할 수 있는 풍부한 공동 작업 기능이 두드러지게 표시되도록 리본 디자인이 업데이트되었습니다.

### <a name="publisher-feature-updates"></a>Publisher: 기능 업데이트

- **새로운 모습의 Office:**  Office 앱의 아이콘이 최신 아이콘으로 업데이트되어 더 간편하고 접근성이 높아졌습니다. 또한 Office 앱에서 사용할 수 있는 풍부한 공동 작업 기능이 두드러지게 표시되도록 리본 디자인이 업데이트되었습니다.

### <a name="visio-feature-updates"></a>Visio: 기능 업데이트

- **다음 다이어그램에서 상징적 순간 즐기기:** 분석, 예술, 경축, 얼굴, 스포츠 등에 대한 아이콘이 있는 새 스텐실 26가지 중에서 선택할 수 있습니다.
- **새로운 모습의 Office:**  Office 앱의 아이콘이 최신 아이콘으로 업데이트되어 더 간편하고 접근성이 높아졌습니다. 또한 Office 앱에서 사용할 수 있는 풍부한 공동 작업 기능이 두드러지게 표시되도록 리본 디자인이 업데이트되었습니다.

### <a name="office-suite-feature-updates"></a>Office 제품군: 기능 업데이트

- **이제 Office 타사 응용 프로그램에서 office.js API를 사용하는 SVG 삽입 지원:** Office에서 추가 기능으로도 알려져 있는 타사 응용 프로그램에 SVG 삽입 기능이 제공되므로 SVG 개인 컬렉션을 Office에 연결할 수 있습니다. 개발자들은 Office.js API를 통해 이 기능을 사용할 수 있습니다.
- **Microsoft Teams 설치:** Microsoft Teams는 기본적으로 Office 365 ProPlus 기존 설치에 설치됩니다. [자세한 정보](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>비즈니스용 Skype: 기능 업데이트

- **고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다. [자세한 정보](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams: 기능 업데이트

- **고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다. [자세한 정보](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a>버전 1808: 2월 12일
*버전 1808(빌드 10730.20280)* 

### <a name="access-non-security-updates"></a>Access: 비보안 업데이트 

- 이 업데이트는 Access에 대한 새로운 일본 시간대 지원을 추가합니다.

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트 

- 더 이상 존재하지 않는 폴더를 참조하는 규칙이 포함된 사용자로 인해 발생하는 문제를 해결합니다. 규칙을 관리하려 할 때 오류가 표시됩니다. 클라이언트 측 규칙 실행 실패를 참조하세요.
- 캐시된 대리인 사서함을 가진 사용자로 인해 예측할 수 없는 간격마다 주기적인 중단이 발생하는 문제를 해결합니다.
- 회의의 종료 시간이 다음날 자정으로 설정되어 종일 회의가 일부 보기에서 의도한 날보다 하루 더 많이 표시되는 문제를 해결합니다.
- 일본 시간대를 참조하는 새 약속 또는 회의를 만들 때 중단되는 문제를 해결했습니다.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트

- [O365 Office 중앙 집중식 배포](/office/dev/add-ins/publish/centralized-deployment)를 사용하여 배포된 추가 기능이 중지되고 사용할 수 없는 문제를 해결했습니다.


## <a name="version-1808-january-8"></a>버전 1808: 1월 8일
*버전 1808 (빌드 10730.20264)* 

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트 

- 일정 동기화 오류가 발생하는 문제를 해결했습니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트

- 열기 성능을 개선합니다.

## <a name="version-1808-december-11"></a>버전 1808: 12월 11일
*버전 1808(빌드 10730.20262)*

### <a name="excel-security-updates"></a>Excel: 보안 업데이트 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): Microsoft Excel 원격 코드 실행 취약성 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): Microsoft Excel 정보 노출 취약성 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): Microsoft Excel 정보 노출 취약성 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): Microsoft Excel 원격 코드 실행 취약성 

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook 원격 코드 실행 취약성 

### <a name="powerpoint-security-updates"></a>PowerPoint: 보안 업데이트 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint 원격 코드 실행 취약성 

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트 

- 다른 사용자가 슬라이서에서 데이터에 열 필터를 적용 한 후 슬라이서가 제대로 업데이트되지 않는 공동 작성 세션에서의 문제를 해결했습니다.
- 사용자 중 하나가 슬라이서에 대한 설명을 지우고 이것이 공동 작성 세션에서 다른 사용자가 Excel 충돌을 경험하게 하는 공동 작성 세션에서의 문제를 해결했습니다.
- 데이터의 같은 열에 바인딩된 여러 표 슬라이서를 만든 다음 데이터의 해당 열을 삭제할 때 발생할 수 있는 충돌을 해결했습니다.
- 열 너비를 자동으로 조정하는 옵션이 해제되었을 때 셀의 래핑된 텍스트를 포함하는 필터링된 쿼리 테이블을 새로 고치는 동안 Excel이 이따금씩 충돌하는 문제를 해결했습니다.
- 슬라이서에 표시된 항목의 수가 변경되면 Excel 2007에서 저장된 슬라이서가 최신 버전의 Excel에서 열 때 충돌을 트리거할 수 있는 문제를 해결했습니다.
- 지원 요청에 대한 조사를 간편하게 하기 위한 진단 가져오기 버튼에 대한 지원을 소개합니다.

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트

- "규칙 및 알림 관리" 대화 상자를 시작하면 사용자에게 오류가 표시되는 문제를 해결했습니다.
- 사용자가 데이터 통신 연결을 사용하는 경우 DirectAccess를 통해 사서함에 연결하지 못할 수 있는 문제를 해결했습니다.
- 사용자가 공용 폴더에 저장된 무료 문서를 오류로 "제한된 보기"로 열리는 것을 보게 되는 문제를 해결했습니다.
- 사용자가 인라인 첨부 파일이 포함된 항목을 전달할 때 예기치 않은 첨부 파일을 보게 되는 문제를 해결했습니다.
- OFT 파일이 첨부 파일로 전송된 후 잘 못 표현되는 문제를 해결했습니다.
- 공유 캘린더에 모임을 추가할 때 일부 추가 기능 사용자가 충돌을 경험하는 문제를 해결했습니다.
- 대화 기록 폴더를 열 때 사용자가 작동 중단을 경험하는 문제를 해결했습니다.

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트

- Project에서 새 베네수엘라 통화를 지원하는 것에 관한 문제를 해결했습니다.
- 외부 모니터에 연결된 Surface 4를 사용하는 경우 Project가 중단될 수 있는 문제를 해결했습니다.
- Project를 XML 형식으로 저장할 때 Project가 충돌할 수 있는 문제를 해결했습니다.
- 자원의 캘린더를 편집한 후 Enterprise 자원 사용자 정의 필드가 삭제될 수 있는 문제를 해결했습니다.
- 한국어 표시 이름을 검색할 때 사용자가 충돌을 경험하는 문제를 해결했습니다.

## <a name="version-1808-november-13"></a>버전 1808: 11월 13일
*버전 1808(빌드 10730.20205)*

### <a name="excel-security-updates"></a>Excel: 보안 업데이트

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): Microsoft Excel 원격 코드 실행 취약성 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): Microsoft Excel 원격 코드 실행 취약성 

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook 원격 코드 실행 취약성 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook 원격 코드 실행 취약성 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook 정보 공개 취약성 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook 원격 코드 실행 취약성 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook 정보 공개 취약성 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook 원격 코드 실행 취약성 

### <a name="project-security-updates"></a>Project: 보안 업데이트 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): Microsoft Word 원격 코드 실행 취약성 

### <a name="word-security-updates"></a>Word: 보안 업데이트 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): Microsoft Word 원격 코드 실행 취약성 

### <a name="skype-for-business-security-updates"></a>비즈니스용 Skype: 보안 업데이트 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): Microsoft 비즈니스용 Skype 서비스 거부 취약성 

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트 

- 일부 빌드/버전에서는 Power Pivot이 표시되지 않는 버그를 수정했습니다.

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트 

- 사용자가 계정 컨트롤 버튼을 이용하여 사용자 지정 양식의 계정 간을 전환할 수 없는 문제를 해결했습니다.
- 사용자가 ScanPST를 이용하여 OST/PST 파일을 복구할 때 작동이 중단되는 문제를 해결했습니다.
- 온라인 모드 프로필이 있는 사용자에게 특정 메일 메시지의 CC: 필드가 표시되지 않는 문제를 해결했습니다.

### <a name="onenote-non-security-updates"></a>OneNote: 비보안 업데이트 

- 동기화 및 삭제된 섹션으로의 이동과 관련해서 발생할 수 있는 안정성 문제를 해결했습니다.

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트 

- 새로운 최신 환경에 있는 SharePoint 문서 라이브러리의 프로젝트 파일을 사용하는 경우 체크 아웃 필요 및 읽기 전용 작업이 올바르게 연결되지 않는 문제를 해결했습니다.


## <a name="version-1808-october-9"></a>버전 1808: 10월 9일
*버전 1808(빌드 10730.20155)*

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): Microsoft Excel 원격 코드 실행 취약성 

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office 심층 방어 업데이트 

### <a name="powerpoint-security-updates"></a>PowerPoint: 보안 업데이트 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): PowerPoint 원격 코드 실행 취약성

### <a name="word-security-updates"></a>Word: 보안 업데이트 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): Microsoft Word 원격 코드 실행 취약성 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office 심층 방어 업데이트 

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432) Microsoft 그래픽 구성 요소 원격 코드 실행 취약성 

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트 
-   2190...2194 범위에 있는 기호가 Cambria Math로 전환되는 문제를 해결했습니다. 이 때문에 Excel 셀 높이가 3배로 증가하고 있습니다.
-   이는 사용자가 정의된 이름이 많은 통합 문서의 서식 옵션 위로 마우스를 가져가면 Excel이 응답하지 않을 수도 있고, 옵션에 실시간 미리 보기가 비활성화되어 있는데도 Excel이 빠른 분석 도구에서 응답하지 않을 수도 있는 Excel의 문제를 해결합니다.
-   현재 한 데스크톱에서 다른 데스크톱으로 Excel 응용 프로그램 창을 이동하면 나타나는 성능 저하 문제를 조사하고 있습니다. 그동안 이 저하 문제를 알게 된 경우에 고려할 만한 해결 방법은 파일 옵션 대화 상자의 "일반" 탭에서 "다중 디스플레이를 사용하는 경우"에 대한 "호환성 최적화"를 선택하는 것입니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   ActiveX 콘텐츠가 있는 파일을 저장할 때 발생할 가능성이 있는 파일 손상 문제를 해결했습니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   Word 문서 개체를 삽입할 때 수식 편집기가 표시되는 문제를 해결했습니다.

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트
-   인쇄용 머리글 또는 바닥글을 설정하는 경우 변경 사항이 다음에 프로젝트를 인쇄하려고 할 때 유지되지 않는 문제를 해결했습니다.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   내게 필요한 옵션 및 성능 설정을 통해 애니메이션을 해제해도 애니메이션을 표시하는 앱 문제를 해결했습니다. 
-   형광펜 그리기 도구를 사용할 때 배경색이 빈 화면으로 바뀌는 문제를 해결했습니다.

## <a name="version-1808-september-11"></a>버전 1808: 9월 11일
*버전 1808(빌드 10730.20102)*

### <a name="access-feature-updates"></a>Access: 기능 업데이트
 - **새 차트로 데이터 시각화:** 11개 차트 중에서 선택한 후 폼 및 보고서에 추가하여 데이터를 보다 잘 시각화하고 합리적인 의사 결정을 내릴 수 있습니다. [자세한 정보](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)
 
 ### <a name="access-security-updates"></a>Access: 보안 업데이트
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access 원격 코드 실행 Use After Free 취약성

### <a name="excel-feature-updates"></a>Excel: 기능 업데이트
 - **공동 작업 편집:** 통합 문서에서 다른 사용자와 동시에 작업합니다. [자세히 알아보기](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **이제 클라우드 파일용 자동 저장이 기본적으로 사용하도록 설정됨:** 자동 저장이 2018년 9월 반기 채널(대상 지정)에 기본적으로 사용하도록 설정되었습니다. 이러한 변화는 사용자가 OneDrive 또는 SharePoint Online에 저장된 문서에서 자신의 변경 내용이 손실될까 봐 걱정할 필요가 없음을 의미합니다. 변경 내용이 클라우드에 자동으로 저장되어 사용자가 더 이상 Ctrl + S 또는 저장 단추를 명확하게 누르지 않아도 됩니다. 그러나 사용자가 이 동작의 변화를 이해해야 문서를 실수로 변경하지 않습니다. 사용자는 화면 맨 위에 있는 자동 저장 토글을 이용하여 자동 저장을 끌 수 있습니다. 이 예정된 변화에 대해 사용자에게 알리고 Office 365에서 이 새로운 기능을 가장 잘 활용하는 방법에 대해 교육하는 것이 좋습니다. [자동 저장에 대해 자세히 알아보기](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [IT 관리자가 자동 저장과 관련해 알아야 할 사항에 대해 자세히 알아보기](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **향상된 셀 및 수식 입력줄 편집:** 이제 Ctrl+A를 사용하여 셀이나 수식 입력줄에서 텍스트를 선택할 수 있습니다. 이모지 및 기타 복잡한 문자에 대한 지원도 개선되었습니다. [자세히 알아보기](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **접근성 검사 개선:** 접근성 검사에서는 통합 문서에 보다 쉽게 액세스할 수 있도록 국제 표준 및 권장 사항에 대한 지원을 업데이트했습니다. [자세히 알아보기](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **원치 않는 편집 방지:** 통합 문서를 실수로 변경하지 않도록 읽기 전용으로 설정합니다. 파일 > 정보 > 통합 문서 보호 > 항상 읽기 전용으로 열기로 이동합니다.

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): Microsoft Excel 원격 코드 실행 취약성
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): Microsoft Excel 정보 노출 취약성
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): Microsoft Excel 원격 코드 실행 취약성 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Microsoft Excel 원격 코드 실행 취약성 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): Microsoft Excel 정보 노출 취약성
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Microsoft Excel 정보 노출 취약성
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Microsoft Excel 원격 코드 실행 취약성
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Microsoft Excel 원격 코드 실행 취약성
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Microsoft Excel 원격 코드 실행 취약성
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Microsoft Excel 원격 코드 실행 취약성
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Microsoft Excel 정보 노출 취약성
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Microsoft Excel 원격 코드 실행 취약성

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   셀의 원래 설정에서 차트의 원본 데이터를 변경할 때 Excel의 작동이 중단될 수도 있는 문제를 해결합니다.
-   FullCalcOnLoad 속성이 설정되어 있는데도 다시 계산이 열려 있을 때 실행되지 않을 수도 있는 문제를 해결합니다.  
-   일본 Era 달력이 날짜 셀 형식으로 사용될 때 잘못된 연도가 표시되는 문제를 해결합니다.
-   Excel 데이터 모델에 데이터를 가져올 때 들어오는 음의 0 값이 오류를 발생합니다. 수정 프로그램은 이러한 값을 0으로 가져옵니다.
-   Excel 피벗 테이블의 그룹화(또는 그룹 해제) 작업이 경우에 따라 충돌이 발생할 수 있는 문제를 해결합니다.
-   차트 작업으로 인해 Excel 작동이 중단될 수도 있는 문제를 해결합니다.
-   일부 사용자가 파워 뷰 추가 기능을 사용할 수 없는 문제를 해결합니다.
-   문서 복구 중에 생성된 임시 자동 복구 파일이 정리되지 않는 문제를 해결합니다.
-   보호된 통합 문서의 텍스트 파일에 새 연결을 시도하면 “통합 문서가 보호되어 변경할 수 없습니다”라는 오류 메시지가 나타나는 문제를 해결합니다.
-   Outlook 전자 메일에 첨부된 Excel 통합 문서를 빠른 인쇄 기능으로 인쇄하지 못할 수도 있는 문제를 해결합니다.
-   하이퍼링크를 클릭하면 Excel의 작동이 중단되는 문제를 해결합니다.
-   큐브 함수를 사용할 때 Excel의 작동이 중단되는 문제를 해결합니다.

### <a name="outlook-feature-updates"></a>Outlook: 기능 업데이트
 - **접근성 검사 개선:** 접근성 검사에서는 메시지에 보다 쉽게 액세스할 수 있도록 국제 표준 및 권장 사항에 대한 지원을 업데이트했습니다. [자세히 알아보기](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **프로필 선택기에서 프로필 관리:** Outlook을 시작할 때 프로필 선택기를 사용하는 경우 이제 제어판으로 이동하지 않고도 내용을 변경할 수 있습니다. 프로필 선택기에서 모두 프로필을 만들고 삭제하며, 설정을 변경합니다.
- **기본 제공된 접근성:** 이미지에 설명이 포함된 대체 텍스트를 추가하여 모든 사용자가 메시지에 액세스하도록 할 수 있습니다.
- **Outlook 추가 기능 경고:** 가끔씩 Outlook COM 추가 기능에 문제가 발생하여 Outlook의 나머지 속도가 느려질 수 있습니다. 이러한 문제는 Outlook 폴더 사이의 전환, 새 이메일의 도착, Calendar 항목 열기 등과 같은 이벤트의 대기 시간 때문에 일어날 수 있습니다. 이러한 문제가 발생하면 Outlook의 알림 표시줄에 경고 메시지가 표시됩니다.
- **모임에 함께할 대상 파악:** 이제 이끌이가 아니더라도 모임 요청에 대한 다른 사람의 응답을 볼 수 있습니다.
- **미리 알림 누락 방지:** 미리 알림이 작업 중인 창 위에 팝업되도록 설정합니다. 그렇지 않은 경우 Outlook이 주의를 끌기 위해 작업 표시줄에서 깜박입니다. [자세히 알아보기](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **삭제된 항목을 읽은 상태로 표시:** 이제 삭제하는 모든 메시지를 읽은 상태로 설정할 수 있습니다. 파일 \> 옵션 \> 메일 \> 기타로 이동하여 옵트인합니다.
- **세 가지 표준 시간대 보기:** 표준 시간대가 다른 지역 간에 모임을 예약해야 하나요? 여러 표준 시간대를 캘린더에 추가하여 모든 사용자의 가용성을 쉽게 확인하고 모두가 참여할 수 있는 시간을 선택할 수 있습니다. [자세히 알아보기](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **그룹을 만들기 위한 사용자 환경 개선:** 그룹을 보다 현대적이고 깔끔해 보이도록 만들기 위해 사용자 환경을 개선했습니다. [자세히 알아보기](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): Microsoft Office 변조 취약성
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook 권한 상승 취약성
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook 보안 기능 바이패스 취약성
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): Microsoft Office 심층 방어 업데이트

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   시스템 언어를 일본어로 전환하고 Outlook 안에 로드된 경우 VBA IDE에 일본어 문자를 입력하려고 하면 Outlook이 중단되는 문제를 해결합니다. 
-   보낼 편지함 또는 보낸 편지함 폴더로 전환하면 Outlook의 작동이 중단되는 문제를 해결합니다.
-   모임 본문 또는 첨부 파일이 변경될 때 참석자에게 선택적으로만 모임 업데이트를 보내지 않고, 모든 참석자가 모임 업데이트를 받게 되는 문제를 해결합니다.
-   사용자가 User-Agent 문자열 변경 때문에 EWS 및 REST 끝점에 연결할 수 없게 되는 문제를 해결합니다.
-   참석자에 대한 모임 장소 업데이트 시 새 위치가 아닌 이전 위치가 표시되는 문제를 해결합니다.
-   읽기 창에서 첨부 파일을 미리 볼 때 오류가 표시되는 문제를 해결합니다.
-   사용자가 전자 메일을 작성할 때 표시 이름이 전자 메일 주소로 확인될 경우 Outlook이 중단되는 문제를 해결합니다.
-   일부 사용자가 해당 테넌트 관리자에 대해 사용되도록 설정된 지원 기능을 받지 못하는 문제를 해결합니다.

### <a name="powerpoint-feature-updates"></a>PowerPoint: 기능 업데이트 
- **이제 클라우드 파일용 자동 저장이 기본적으로 사용하도록 설정됨:** 자동 저장이 2018년 9월 반기 채널(대상 지정)에 기본적으로 사용하도록 설정되었습니다. 이러한 변화는 사용자가 OneDrive 또는 SharePoint Online에 저장된 문서에서 자신의 변경 내용이 손실될까 봐 걱정할 필요가 없음을 의미합니다. 변경 내용이 클라우드에 자동으로 저장되어 사용자가 더 이상 Ctrl + S 또는 저장 단추를 명확하게 누르지 않아도 됩니다. 그러나 사용자가 이 동작의 변화를 이해해야 프레젠테이션을 실수로 변경하지 않습니다. 사용자는 화면 맨 위에 있는 자동 저장 토글을 이용하여 자동 저장을 끌 수 있습니다. 이 예정된 변화에 대해 사용자에게 알리고 Office 365에서 이 새로운 기능을 가장 잘 활용하는 방법에 대해 교육하는 것이 좋습니다. [자동 저장에 대해 자세히 알아보기](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [IT 관리자가 자동 저장과 관련해 알아야 할 사항에 대해 자세히 알아보기](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **잉크 변환:** 메모와 그림을 낙서한 후, 읽을 수 있는 텍스트와 정돈된 모양으로 세련되게 변환합니다. [자세한 정보](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **개선된 SVG 지원:** 필터가 적용된 SVG를 삽입할 수 있습니다. [자세히 알아보기](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **펜으로 슬라이드 제목 쓰기:** 펜을 사용하여 제목을 잉크로 쓰면 PowerPoint에서 텍스트로 변환합니다. [자세히 알아보기](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **원치 않는 편집 방지:** 통합 문서를 실수로 변경하지 않도록 읽기 전용으로 설정합니다. 파일 > 정보 > 통합 문서 보호 > 항상 읽기 전용으로 열기로 이동합니다.
- **접근성 검사 개선:** 접근성 검사에서는 프레젠테이션에 보다 쉽게 액세스할 수 있도록 국제 표준 및 권장 사항에 대한 지원을 업데이트했습니다. [자세히 알아보기](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   테이블이 두꺼운 테두리로 잘못 렌더링되는 문제를 해결합니다.
-   Shape.Visibile 속성을 변경할 때 잠재적인 작동 중단이 발생할 수 있는 문제를 해결합니다.
-   공동 작성된 문서를 변경하면 병합되지 못하는 문제를 해결합니다.
-   ActiveX 컨트롤을 포함하는 문서의 공동 작성이 실패하도록 하는 문제를 해결합니다.
-   모양에서 맞춤법 검사를 진행하면 PowerPoint의 작동이 중지하는 문제를 해결합니다.
-   SharePoint Onoline에서 파일을 열면 PowerPoint 작업이 중단되는 문제를 해결합니다.
-   자동 저장이 켜져 있을 때 복구 창이 올바르게 표시되지 않는 문제를 해결합니다.
-   로그인이 표시되지 않아 사용자가 파일에 액세스하지 못하게 되는 문제를 해결합니다.
-   여러 사용자가 동일한 프레젠테이션을 공동으로 작성할 경우 슬라이드 마스터가 잘못 복제되는 문제를 해결합니다.
-   OneDrive에 저장된 파일을 열 경우 제한된 보기를 끝낼 때 PowerPoint의 작동이 중단되는 문제를 해결합니다.

### <a name="project-feature-updates"></a>Project: 기능 업데이트 
- **스프린트 관리:** Agile 스프린트를 빠르게 추가, 업데이트하거나 삭제합니다.
- **작업 보드 필터링:** 주요 리소스 또는 요약 작업을 필터링하여 작업 보드를 간소화합니다.
- **작업 보드에서 완료율 설정:** 각 열에 대한 완료율을 선택한 다음, 끌어서 놓기를 통해 작업 완료 상태를 업데이트합니다.
- **스프린트 탐색:** 스프린트 보기 간을 전환하고 스프린트 간에 작업을 빠르게 이동합니다.
- **스프린트를 관리하는 새로운 방법:** 작업 보드에서 작업할 때 Agile 접근 방법을 선택합니다. 스프린트 관리로 이동하여 프로젝트가 발전함에 따라 스프린트를 추가하고 제거합니다.
- **최근 저장 위치 유지:** Project에서는 다른 프로젝트를 저장한 위치 목록을 유지합니다. 프로젝트를 저장할 준비가 되면 최근 저장 위치 중 하나를 선택하여 편리하게 저장할 수 있습니다.

### <a name="project-non-security-updates"></a>Project 비보안 업데이트
- 마스터 프로젝트의 컨텍스트를 통해 작업할 때 하위 프로젝트를 저장하지 못하는 문제를 해결합니다.

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
-   TLS 1.2 지원과 관련된 문제를 해결합니다(참고: 4월 10일의 메모에 언급된 것과 동일한 수정 사항으로, 9월 롤업의 일부로 여기에서 다시 언급함)
-   모임에서 'Skype 통화'를 선택하여 사용자를 추가하면 오류가 발생하는 문제를 해결합니다.
-   Skype 룸이 위치에 추가되고 모임에 팀 모임 좌표가 이미 포함되어 있는 경우 모임에 Skype 좌표를 추가하도록 사용자에게 요청하는 메시지를 제거합니다.
-   UseLocationForE911Only가 true로 설정되어 있어도 위치가 채워지는 문제를 수정합니다.
-   “회의 센터를 사용하여 통화” 옵션을 사용하여 로스터에서 사용자를 초대할 때 비즈니스용 Skype가 중지되는 문제를 수정합니다.
-   비즈니스용 Skype 모임을 만드는 동안 터미널 서버에서 실행하는 Outlook이 중지되는 문제를 수정합니다.
-   EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket의 기본값을 true로 변경합니다.

### <a name="visio-feature-updates"></a>Visio: 기능 업데이트
- **다이어그램 및 원본을 동기화 상태로 유지:** Visio에서 데이터 시각화 도우미 다이어그램을 편집하면 연결된 Excel 원본 데이터를 최신 다이어그램 콘텐츠로 업데이트하는 옵션이 제공됩니다.
- **데이터 시각화 도우미 감사 서식 파일:** Excel에서 콘텐츠를 가져와 금융 거래, 재고 관리 등을 위한 감사 다이어그램을 만들 수 있습니다.
- **시작 다이어그램:** 이제 조직도, 브레인스토밍 및 SDL 서식 파일에 더 빨리 시작하고 작동하기 위한 새로운 시작 다이어그램이 포함되어 있습니다.
 - **Visio 셰이프로 Word 문서 만들기** 셰이프, 메타데이터 등의 다이어그램 콘텐츠를 Word 문서에 자동으로 추가합니다. 그런 다음, 문서를 사용자 지정하여 프로세스 지침 및 작업 설명서를 만듭니다. [자세히 알아보기](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="word-feature-updates"></a>Word: 기능 업데이트
- **이제 클라우드 파일용 자동 저장이 기본적으로 사용하도록 설정됨:** 자동 저장이 2018년 9월 반기 채널(대상 지정)에 기본적으로 사용하도록 설정되었습니다. 이러한 변화는 사용자가 OneDrive 또는 SharePoint Online에 저장된 문서에서 자신의 변경 내용이 손실될까 봐 걱정할 필요가 없음을 의미합니다. 변경 내용이 클라우드에 자동으로 저장되어 사용자가 더 이상 Ctrl + S 또는 저장 단추를 명확하게 누르지 않아도 됩니다. 그러나 사용자가 이 동작의 변화를 이해해야 프레젠테이션을 실수로 변경하지 않습니다. 사용자는 화면 맨 위에 있는 자동 저장 토글을 이용하여 자동 저장을 끌 수 있습니다. 이 예정된 변화에 대해 사용자에게 알리고 Office 365에서 이 새로운 기능을 가장 잘 활용하는 방법에 대해 교육하는 것이 좋습니다. [자동 저장에 대해 자세히 알아보기](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)[IT 관리자가 자동 저장과 관련해 알아야 할 사항에 대해 자세히 알아보기]
- **접근성 검사 개선:** 접근성 검사에서는 문서에 보다 쉽게 액세스할 수 있도록 국제 표준 및 권장 사항에 대한 지원을 업데이트했습니다. [자세히 알아보기](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **개선된 SVG 지원:** 필터가 적용된 SVG를 삽입할 수 있습니다. [자세히 알아보기](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-security-updates"></a>Word: 보안 업데이트
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Word PDF 원격 코드 실행 취약성
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Microsoft Office 정보 노출 취약성

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   메모리 부족 메시지가 표시되는 문제를 해결합니다.
-   다른 조직의 사용자가 이 조직의 사용자에게 IRM으로 보호되는 문서와 이메일을 공유하는 경우 이러한 문서를 열지 못하던 일련의 문제를 수정했습니다.
-   몇 가지 성능 문제를 해결했습니다.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): Win32k 그래픽 원격 코드 실행 취약성
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): Microsoft Office 정보 노출 취약성
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Microsoft Office 정보 노출 취약성
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Microsoft Office 원격 코드 실행 취약성
-   
  **보안상의 이유로 Office에서 Flash, Silverlight 및 Shockwave 컨트롤이 활성화되지 않도록 차단:** 보안상의 이유로 Windows의 Office 365용 Microsoft Office의 새 빌드는 Flash, Silverlight 및 Shockwave 컨트롤의 활성화를 차단합니다. [여기](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) 및 [여기](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US)에서 자세히 알아보세요.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-  특정 시나리오에서 업데이트 설치 시간이 오래 걸리는 문제를 해결했습니다.
-  응용 프로그램을 열 때 안전 모드에서 시작된다는 메시지가 표시된 후 응용 프로그램이 열리지 않는 문제를 해결합니다.
-  몇 가지 성능 문제를 해결했습니다.

## <a name="version-1803-august-14"></a>버전 1803: 8월 14일
*버전 1803(빌드 9126.2275)*

### <a name="access-security-updates"></a>Access: 보안 업데이트
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access 원격 코드 실행 Use After Free 취약성

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): Microsoft Excel 원격 코드 실행 취약성 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Microsoft Excel 원격 코드 실행 취약성 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): Microsoft Excel 정보 노출 취약성 

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): Microsoft Office 심층 방어 업데이트 

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): Microsoft Office 정보 노출 취약성 

## <a name="version-1803-july-10"></a>버전 1803: 7월 10일
*버전 1803(빌드 9126.2259)*

### <a name="access-security-updates"></a>Access: 보안 업데이트
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access 원격 코드 실행 Use After Free 취약성

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): Microsoft Office 변조 취약성

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): Microsoft Office 원격 코드 실행 취약성

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   일본 Era 달력이 날짜 셀 형식으로 사용될 때 잘못된 연도가 표시되는 문제를 해결합니다.
-   Excel 데이터 모델에 데이터를 가져올 때 들어오는 음의 0 값이 오류를 발생합니다. 수정 프로그램은 이러한 값을 0으로 가져옵니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   테이블이 두꺼운 테두리로 잘못 렌더링되는 문제를 해결합니다.

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트
-   작업을 비용 자원으로 분할할 경우 비용 자원이 올바르게 업데이트되지 않고 비용손이 실되는 문제가 해결되었습니다.
-   시간 표시 막대 보기의 시간 표시 막대에 기존 작업 추가 대화 상자에서 첫 번째 요약 작업의 작업만 표시되는 문제가 해결되었습니다.
-   Project Online 또는 Project Server에서 마스터 프로젝트를 XML로 저장하면 실패하는 문제가 해결되었습니다.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   특정 시나리오에서 업데이트 설치 시간이 오래 걸리는 버그를 수정합니다. 
-   SVG 테스트가 실패하는 문제를 해결합니다.
-   Configuration Manager를 사용하여 Office 응용 프로그램을 실행하는 클라이언트에 업데이트를 배포할 때 Office 응용 프로그램이 실행되는 동안 장치를 다시 시작한 후에 업데이트가 적용되지 않는 문제를 해결합니다.


## <a name="version-1803-june-12"></a>버전 1803: 6월 12일
*버전 1803(빌드 9126.2227)*

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Microsoft Excel 정보 노출 취약성
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Microsoft Excel 원격 코드 실행 취약성

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   Excel 피벗 테이블의 그룹화(또는 그룹 해제) 작업이 경우에 따라 충돌이 발생할 수 있는 문제를 해결합니다.

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook 권한 상승 취약성

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   Shape.Visibile 속성을 변경할 때 잠재적인 작동 중단이 발생할 수 있는 문제를 해결합니다.
-   공동 작성된 문서를 변경하면 병합되지 못하는 문제를 해결합니다.
-   ActiveX 컨트롤을 포함하는 문서의 공동 작성이 실패하도록 하는 문제를 해결합니다.

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트
-   시간 표시 막대 보기의 시간 표시 막대에 기존 작업 추가 대화 상자에서 첫 번째 요약 작업의 작업만 표시되는 문제를 해결합니다.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   Configuration Manager를 사용하여 Office 응용 프로그램을 실행하는 클라이언트에 업데이트를 배포할 때 Office 응용 프로그램이 실행되는 동안 장치를 다시 시작한 후에 업데이트가 적용되지 않는 문제를 해결합니다.



## <a name="version-1803-may-18"></a>버전 1803: 5월 18일
*버전 1803(빌드 9126.2210)*

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
- 차트 작업으로 인해 Excel 작동이 중단될 수도 있는 문제를 해결합니다.
- 일부 사용자가 파워 뷰 추가 기능을 사용할 수 없는 문제를 해결합니다.
- 문서 복구 중에 생성된 임시 자동 복구 파일이 정리되지 않는 문제를 해결합니다.
- 보호된 통합 문서의 텍스트 파일에 새 연결을 시도하면 “통합 문서가 보호되어 변경할 수 없습니다”라는 오류 메시지가 나타나는 문제를 해결합니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
- 모양에서 맞춤법 검사를 진행하면 PowerPoint의 작동이 중지하는 문제를 해결합니다.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
- 응용 프로그램을 열 때 안전 모드에서 시작된다는 메시지가 표시된 후 응용 프로그램이 열리지 않는 문제를 해결합니다.



## <a name="version-1803-may-8"></a>버전 1803: 5월 8일
*버전 1803(빌드 9126.2191)*

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Microsoft Excel 원격 코드 실행 취약성
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Microsoft Excel 원격 코드 실행 취약성
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Microsoft Excel 원격 코드 실행 취약성
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Microsoft Excel 정보 노출 취약성

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   SharePoint Onoline에서 파일을 열면 Excel 작업이 중단되는 문제를 해결합니다.
-   인쇄 또는 인쇄 미리 보기에서 워크시트 일부만 인쇄되거나 표시되고 워크시트의 슬라이서에서 콘텐츠가 잘리는 문제를 해결합니다.

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook 보안 기능 바이패스 취약성

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   보낼 편지함 또는 보낸 편지함 폴더로 전환하면 Outlook이 중단되는 문제를 해결합니다.
-   모임 본문 또는 첨부 파일이 변경될 때 참석자에게 선택적으로만 모임 업데이트를 보내지 않고, 모든 참석자가 모임 업데이트를 받게 되는 문제를 해결합니다.
-   사용자가 User-Agent 문자열 변경 때문에 EWS 및 REST 끝점에 연결할 수 없게 되는 문제를 해결합니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   SharePoint Onoline에서 파일을 열면 PowerPoint 작업이 중단되는 문제를 해결합니다.
-   자동 저장이 켜져 있을 때 복구 창이 올바르게 표시되지 않는 문제를 해결합니다.
-   로그인이 표시되지 않아 사용자가 파일에 액세스하지 못하게 되는 문제를 해결합니다.

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트
-   날짜 열에서 자동 필터 드롭다운을 사용할 경우 프로젝트의 모든 작업이 숨겨지는 문제를 해결합니다.
-   시간 표시 막대 보기 상태에서 시간 표시 막대에 기존 작업을 추가할 때 첫 번째 요약 작업의 작업만 대화 상자에 표시되는 문제를 해결합니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   SharePoint Onoline에서 파일을 열면 Word 작업이 중단되는 문제를 해결합니다.
-   소문자 로마 숫자 페이지 번호가 대문자로 잘못 변환되는 문제를 해결합니다.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Microsoft Office 원격 코드 실행 취약성



## <a name="version-1803-april-10"></a>버전 1803: 4월 10일
*버전 1803(빌드 9126.2152)*

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Microsoft Excel 원격 코드 실행 취약성

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   여러 사용자가 동일한 프레젠테이션을 공동으로 작성할 경우 슬라이드 마스터가 잘못 복제되는 문제를 해결합니다.
-   OneDrive에 저장된 파일을 열 경우 제한된 보기를 끝낼 때 PowerPoint가 중단되는 문제를 해결합니다.

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
-   TLS 1.2 지원와 관련된 문제를 해결합니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   메모리 부족 메시지가 표시되는 문제를 해결합니다.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Microsoft Office 정보 노출 취약성
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Microsoft Office 원격 코드 실행 취약성



## <a name="version-1803-march-20"></a>버전 1803: 3월 20일
*버전 1803(빌드 9126.2098)*

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   Outlook 전자 메일에 첨부된 Excel 통합 문서를 빠른 인쇄 기능으로 인쇄할 수 없는 문제를 해결합니다.
-   하이퍼링크를 클릭하면 Excel의 작동이 중단되는 문제를 해결합니다.
-   큐브 함수를 사용할 때 Excel의 작동이 중단되는 문제를 해결합니다.

### <a name="onedrive-for-business-non-security-updates"></a>비즈니스용 OneDrive: 비보안 업데이트
-   비즈니스용 OneDrive(Groove.exe)가 오랫 동안 작업 관리자에서 CPU 코어 1개에 해당하는 CPU(예: 4개 코어 CPU의 25%)를 소비하게 되는 문제를 해결합니다.

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   참석자에 대한 모임 장소 업데이트 시 새 위치가 아닌 이전 위치가 표시되는 문제를 해결합니다.
-   읽기 창에서 첨부 파일을 미리 볼 때 오류가 표시되는 문제를 해결합니다.
-   사용자가 전자 메일을 작성할 때 표시 이름이 전자 메일 주소로 확인될 경우 Outlook이 중단되는 문제를 해결합니다.
-   일부 사용자가 해당 테넌트 관리자에 대해 사용되도록 설정된 지원 기능을 받지 못하는 문제를 해결합니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   Windows 7 실행 컴퓨터에서 고객 환경 및 원격 분석에 대한 [업데이트가 설치되지 않은 경우 Word가 열리지 않는 문제를](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry)해결합니다.
-   목록의 글머리 기호가 인쇄되지 않는 문제를 해결합니다.



## <a name="version-1803-march-13"></a>버전 1803: 3월 13일
*버전 1803(빌드 9126.2072)*

### <a name="access-security-updates"></a>Access: 보안 업데이트
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Microsoft Access 원격 코드 실행 취약성

### <a name="access-non-security-updates"></a>Access: 비보안 업데이트
-   Access 런타임 응용 프로그램(.accde 파일)을 열면 "인식할 수 없는 데이터베이스"라는 오류 메시지가 표시되면서 응용 프로그램이 열리지 않는 문제를 수정합니다.
-   콤보 상자의 텍스트 상자에서 텍스트를 선택하려고 하려고 할 때 선택 영역만 표시되지 않고 모든 텍스트가 선택된 것처럼 나타나는 문제를 해결합니다.

### <a name="excel-feature-updates"></a>Excel: 기능 업데이트
-   **Microsoft Translator:** Microsoft Translator를 사용하여 단어, 구 또는 문장을 다른 언어로 번역할 수 있습니다. 리본 메뉴에 있는 검토 탭에서 이 작업을 수행할 수 있습니다.
-   **SVG 아이콘을 도형으로 변환:** 모든 SVG 그림 및 아이콘의 색, 크기 또는 질감을 변경할 수 있도록 Office 도형으로 변환합니다.
-   **셀 선택 취소:** 워크시트에서 선택을 수행한 후, 실수로 클릭한 셀을 선택 취소할 수 있으므로 처음부터 다시 시작할 필요가 없습니다.
-   **사이트와 그룹에 대한 빠른 액세스:** 파일 메뉴를 사용하여 자주 사용하는 사이트와 그룹에 저장된 문서를 사용할 수 있습니다.
-   **디지털 펜슬:** 새로운 연필 텍스처로 아이디어를 쓰거나 스케치하세요. 지원되는 디지털 펜을 기울여서 음영을 표현하세요.
-   **LinkedIn 기능 설정:** 파일 \> 옵션 \> 일반으로 이동하여 Office 응용 프로그램에 표시되는 LinkedIn 기능을 제어합니다. [자세한 정보](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D 모델:** 3D를 사용하여 통합 문서의 시각적 효과 및 창의적 효과를 향상시킬 수 있습니다.  3D 모델을 간편하게 삽입한 후 360도로 회전할 수 있습니다. [자세한 정보](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **새 잉크 효과:** 금속 펜과 무지개, 은하수, 용암, 해양, 금, 은 등의 잉크 효과를 사용하여 세련된 아이디어를 표현할 수 있습니다.
-   **파일 공유 UI:** 비즈니스용 OneDrive 또는 SharePoint 파일의 경우 리본의 오른쪽 상단 모서리에 있는 공유 단추를 클릭하거나 파일 \> 공유로 이동하면 간단하게 향상된 공유 대화 상자가 나타납니다. 새 파일 또는 로컬에 저장한 파일의 경우 UI는 사용자가 OneDrive에 쉽게 파일을 업로드하여 공동 작업을 시작할 수 있게 합니다.
-   **위험한 확장 차단:** 위험을 초래할 것으로 간주되며, OLE 패키지 개체로 포함되어 있는 확장명은 기본적으로 활성화되지 않도록 차단됩니다. 예로 .exe, .vbs 및 .js가 있습니다. [자세한 정보](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **유용한 사운드로 접근성 향상:** 오디오 신호를 켜면 작업할 때 안내를 받을 수 있습니다. 파일 \> 옵션 \> 접근성에서 확인할 수 있습니다. 추가 기능은 필요하지 않습니다. [자세한 정보](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **계정별 파일 위치:** 파일을 열거나 저장할 때 위치 목록이 연결된 계정을 기준으로 구성됩니다.
-   **펜 사용자 지정:** 잉크 입력을 위해 펜 및 형광펜의 개인 설정을 선택합니다. 사용자 지정 설정을 모든 Windows PC에서 사용할 수 있습니다.

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Microsoft Excel 보안 기능 바이패스 취약성
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Microsoft Excel 메모리 손상 취약성
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Microsoft Office 메모리 손상 취약성
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Microsoft Excel 원격 코드 실행 취약성
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Microsoft Excel 원격 코드 실행 취약성
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel 보안 기능 바이패스
-   [공지 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office 심층 방어 업데이트

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   홈 탭에서 새 글꼴을 선택하려고 하거나 편집할 때 편집 언어가 일본어, 중국어 또는 한국어인 경우 Excel이 중단되는 문제를 해결합니다.
-   Excel을 초기화한 상태에서 통합 문서를 열 때 스크롤 막대가 없어지는 문제를 해결합니다.
-   파일 탐색기에서 파일 이름을 두 번 클릭하여 여러 통합 문서를 열 때 통합 문서 참조가 실패하는 문제를 해결합니다.
-   프로그래밍 방식으로 피벗 테이블을 생성한 후 프로그래밍 방식으로 새로 고칠 경우 Excel이 중단되는 문제를 해결합니다.
-   Workbook.Open()을 프로그래밍 방식으로 호출하면 Excel 작동이 중단될 수 있는 문제를 해결합니다.
-   매크로가 있는 Office 2007 또는 이전 버전의 통합 문서(.xls 또는 .xla)를 열면 사용자에게 "치명적 오류 발생" 오류 메시지가 잘못 표시되는 문제를 수정합니다.
-   사용자가 상황에 맞는 메뉴를 열면 Excel이 중지할 수도 있는 문제를 수정합니다.
-   사용자가 기존 통합 문서에서 개체를 삽입하려고 할 때 찾아보기를 클릭하면 Excel이 충돌하는 문제를 해결합니다.
-   암호로 범위를 보호할 때 암호를 입력하여 범위를 잠금 해제할 수 있는 대화 상자가 표시되지 않는 문제를 수정합니다.
-   파일 이름에 대괄호가 포함되어 있는 경우 사용자가 제한된 보기에서 통합 문서를 닫을 수 없는 문제를 해결합니다.
-   끌거나 끌어서 채울 시, 도구 설명의 위치가 일치하지 않는 문제를 해결합니다.
-   통합 문서를 파일 \> 다른 이름으로 저장으로 저장할 때, 파일 이름에 마침표가 포함되면 파일이 저장 대화상자에 빈 상태로 혹은 잘려서 나타나는 문제를 수정합니다.
-   동기화 백업 파일을 저장할 때 Office에서 디스크를 쓸 수 없지만 파일을 계속 OneDrive로 업로드하는 문제를 해결합니다. 이 수정 사항을 통해 사용자는 이제 오류 메시지를 확인할 수 있으며 업로드가 진행되지 않습니다.

### <a name="outlook-feature-updates"></a>Outlook: 기능 업데이트
-   **간편하게 전자 메일을 정렬합니다.** 여러분의 의견에 따라, 메시지 목록 위에 정렬 기능을 다시 추가했으며 중요 받은 편지함을 사용하지 않는 사용자를 위해 읽지 않음 필터도 추가했습니다.
-   **SVG 아이콘을 도형으로 변환:** 모든 SVG 그림 및 아이콘의 색, 크기 또는 질감을 변경할 수 있도록 Office 도형으로 변환합니다.
-   **Office 365 그룹의 향상된 기능:** 그룹 메시지를 두 번 클릭하여 자체 창에서 열 수 있으므로 이전보다 더 쉽게 그룹 변환을 읽고 대응할 수 있습니다.
-   **LinkedIn 기능 설정:** 파일 \> 옵션 \> 일반으로 이동하여 Office 응용 프로그램에 표시되는 LinkedIn 기능을 제어합니다. [자세한 정보](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D 모델:** 3D를 사용하여 전자 메일의 시각적 효과 및 창의적 효과를 향상시킬 수 있습니다.  3D 모델을 간편하게 삽입한 후 360도로 회전할 수 있습니다. [자세한 정보](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **프로필 카드:** 데스크톱, 웹 또는 모바일 앱을 사용하는지 여부에 상관없이 사용자 및 그룹에 대해 관련성이 가장 높은 정보를 표시합니다.
-   **그룹 일정에 약속 추가:** 이제는 사용자가 부재 중인 경우 전자 메일로 모임을 보내지 않고도 그룹의 모든 구성원에게 알릴 수 있습니다.
-   **클라우드 첨부 파일 다운로드:** OneDrive 첨부 파일을 컴퓨터에 저장하거나 끌어서 놓으면 파일이 다운로드됩니다.
-   **유용한 사운드로 접근성 향상:** 오디오 신호를 켜면 작업할 때 안내를 받을 수 있습니다. 파일 \> 옵션 \> 접근성에서 확인할 수 있습니다. 추가 기능은 필요하지 않습니다. [자세한 정보](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **중요 받은 편지함:** 받은 편지함은 두 개의 탭, 중요 받은 및 기타로 분리됩니다. 메시지는 메시지의 콘텐츠와 가장 자주 상호 작용하는 사람을 기준으로 정렬됩니다. [자세한 정보](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **가장 자주 사용하는 그룹을 빠르게 실행:** 이제 가장 자주 상호 작용하는 그룹이 폴더 창의 그룹 아래 목록 상단에 표시됩니다.

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Microsoft Office 정보 노출 취약성
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook 원격 코드 실행 취약성
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook 원격 코드 실행 취약성
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook 권한 상승 취약성
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Microsoft Office Outlook 메모리 손상 취약성

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   검색 범위가 모든 사서함으로 지정된 경우 "일치하는 항목이 없습니다."를 표시하며 검색이 실패하는 문제를 해결합니다.
-   액세스 가능한 이벤트 감시자(AccEvent.exe)를 사용하여 모니터링하는 경우 폴더를 전환하면 Outlook이 중단되는 문제를 수정합니다.

### <a name="powerpoint-feature-updates"></a>PowerPoint: 기능 업데이트
-   **Microsoft Translator:** Microsoft Translator를 사용하여 단어, 구 또는 문장을 다른 언어로 번역할 수 있습니다. 리본 메뉴에 있는 검토 탭에서 이 작업을 수행할 수 있습니다.
-   **3D 애니메이션:** 가볍게 흔들거나 점프 및 회전하는 것과 같은 애니메이션으로 3D 모델에 생동감을 줄 수 있습니다.
-   **SVG 아이콘을 도형으로 변환:** 모든 SVG 그림 및 아이콘의 색, 크기 또는 질감을 변경할 수 있도록 Office 도형으로 변환합니다.
-   **수정 내용 추적 정보 로밍:** 다른 사용자가 수정한 공유 슬라이드를 강조 표시하기 위한 읽음/읽지 않음 상태가 이제 사용자의 로컬 컴퓨터 대신 로밍 서비스에 저장되므로, 여러 장치 또는 플랫폼에서 이 정보를 동기화 할 수 있습니다.
-   **사이트와 그룹에 대한 빠른 액세스:** 파일 메뉴를 사용하여 자주 사용하는 사이트와 그룹에 저장된 문서를 사용할 수 있습니다.
-   **디지털 펜슬:** 새로운 연필 텍스처로 아이디어를 쓰거나 스케치하세요. 지원되는 디지털 펜을 기울여서 음영을 표현하세요.
-   **LinkedIn 기능 설정:** 파일 \> 옵션 \> 일반으로 이동하여 Office 응용 프로그램에 표시되는 LinkedIn 기능을 제어합니다. [자세한 정보](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **디지털 펜으로 슬라이드 쇼 실행:** Surface 펜 또는 Bluetooth 단추가 있는 기타 펜을 사용하여 슬라이드를 넘깁니다. Windows 10 가을 크리에이터 업데이트가 필요합니다. [자세한 정보](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)
-   **3D 모델:** 3D를 사용하여 프레젠테이션의 시각적 효과 및 창의적 효과를 향상시킬 수 있습니다. 슬라이드 사이에 시네마틱 애니메이션을 만드는 모핑과 같은 전환을 통해 프레젠테이션에서 3D 모델을 구현할 수 있습니다. [자세한 정보](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **새 잉크 효과:** 금속 펜과 무지개, 은하수, 용암, 해양, 금, 은 등의 잉크 효과를 사용하여 세련된 아이디어를 표현할 수 있습니다.
-   **파일 공유 UI:** 비즈니스용 OneDrive 또는 SharePoint 파일의 경우 리본의 오른쪽 상단 모서리에 있는 공유 단추를 클릭하거나 파일 \> 공유로 이동하면 간단하게 향상된 공유 대화 상자가 나타납니다. 새 파일 또는 로컬에 저장한 파일의 경우 UI는 사용자가 OneDrive에 쉽게 파일을 업로드하여 공동 작업을 시작할 수 있게 합니다.
-   **위험한 확장 차단:** 위험을 초래할 것으로 간주되며, OLE 패키지 개체로 포함되어 있는 확장명은 기본적으로 활성화되지 않도록 차단됩니다. 예로 .exe, .vbs 및 .js가 있습니다. [자세한 정보](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **수정 내용 강조 표시:** 다른 사용자가 수정한 슬라이드가 강조 표시됩니다.
-   **부재 중 변경 내용:** PowerPoint에는 마지막 방문 이후에 공유한 프레젠테이션을 다른 사용자가 편집한 내용이 표시됩니다.
-   **향상된 디자이너 기능:** 이제 디자이너가 글머리 기호 목록의 시간 표시 막대에 대한 디자인 아이디어를 추천합니다.
-   **유용한 사운드로 접근성 향상:** 오디오 신호를 켜면 작업할 때 안내를 받을 수 있습니다. 파일 \> 옵션 \> 접근성에서 확인할 수 있습니다. 추가 기능은 필요하지 않습니다. [자세한 정보](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **계정별 파일 위치:** 파일을 열거나 저장할 때 위치 목록이 연결된 계정을 기준으로 구성됩니다.
-   **펜 사용자 지정:** 잉크 입력을 위해 펜 및 형광펜의 개인 설정을 선택합니다. 사용자 지정 설정을 모든 Windows PC에서 사용할 수 있습니다.
-   **향상된 디자이너 기능:** 이제 디자이너에서 슬라이드에 추가된 차트에 대한 디자인 아이디어를 추천합니다.
-   **빠른 시작:** 사용자가 선택한 주제에 대해 연구를 시작하는 데 도움이 되는 개요를 자동으로 작성합니다. [자세한 정보](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)
-   **디지털 눈금자:** 터치 스크린이 있는 장치에서 그리기 \> 눈금자로 이동한 후 펜이나 손가락을 이용하여 직선을 그리거나 개체 집합을 정렬할 수 있습니다. [자세한 정보](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)

### <a name="powerpoint-security-updates"></a>PowerPoint: 보안 업데이트
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint 정보 노출 취약성

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   문서 속성 및 개인 정보를 제거하면 SharePoint에 저장하지 못하는 문제를 해결합니다.
-   Flash Player 기반 YouTube 포함 코드에 대한 참조를 수행할 경우 비디오 실행을 위해 새 창이 열리는 문제를 해결합니다. 이제 이전 포함 코드가 HTML5 기반 YouTube 비디오를 참조하도록 업그레이드되므로 올바르게 재생될 수 있습니다.
-   동기화 백업 파일을 저장할 때 Office에서 디스크를 쓸 수 없지만 파일을 계속 OneDrive로 업로드하는 문제를 해결합니다. 이 수정 사항을 통해 사용자는 이제 오류 메시지를 확인할 수 있으며 업로드가 진행되지 않습니다.

### <a name="project-feature-updates"></a>Project: 기능 업데이트
-   **작업 보드 보기:** 작업 보드 보기에서 카드의 작업을 정렬합니다. Agile 프로젝트에서와 같이 보드의 열 사이에서 카드 순서를 다시 매기고 이동합니다.
-   **Agile 프로젝트:** 백로그, 작업 보드, 스프린트 등을 사용하여 Agile 프로젝트를 관리합니다. Scrum 또는 Kanban 방법론이 모두 지원됩니다. [추가 정보](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **Planner에서 작업 관리:** Planner에 Project 작업을 연결하고 계획을 세울 수 있습니다. 작업을 하위 작업으로 나누고, 팀을 추가하고, 작업을 할당하고 작업 보드에서 작업을 관리합니다.

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트
-   세션 집합에서 둘 이상의 기준을 설정하면 MOD\_DATE 값이 동일하게 설정되는 문제를 수정합니다.
-   공유용으로 저장 세션에서 제거한 후에도 보고 테이블에 실제 작업이 계속 표시되는 문제를 해결합니다.
-   예약 시, 주 날짜 형식을 사용할 경우 오류가 반환되는 독일어 버전 문제를 해결합니다.
-   일정 웹 파트에서 완료 날짜를 편집할 때 태스크가 시간에 따라 분산되지 않고 하루 8시간을 유지하는 문제를 해결합니다.
-   "진행점 모양"이 예기치 않은 위치에 그려지는 문제를 해결합니다.
-   VBA 코드가 프로젝트에서 손실되는 문제를 해결합니다.
-   작업이 남았지만 완료 상태로 표시되는 문제를 수정합니다.
-   작업 경로 기능을 사용하면 프로젝트가 중단되는 문제를 수정합니다.
-   날짜 표시줄에 날짜 표시줄 레이블이 표시되지 않는 문제를 수정합니다.
-   시각적 정보가 불완전한 정보를 표시하거나 완전히 표시하지 못하는 문제를 수정합니다.
-   저장에 실패한 파일이 손상되고 Project가 열려 있을 때 중지하는 문제를 수정합니다.
-   시간 표시줄 및 팀 플래너 보기에 작업을 끌 수 없는 문제를 수정합니다.
-   리소스 가용성이 팀 구성에 표시되지 않는 문제를 수정합니다.
-   그래픽 표시기가 올바르게 표시되지 않는 문제를 수정합니다.
-   시간 단위 또는 일 단위로 평준화할 때 Project가 정지되는 문제를 수정합니다.
-   SharePoint 문서 라이브러리에서 마스터/하위 프로젝트 작업을 수행할 때 발생하는 문제를 수정합니다.
-   고정된 기간 작업에 과제를 추가할 때 이름 없는 리소스가 나타나는 문제를 수정합니다.
-   보호되는 작업이 변경되었다는 잘못된 오류 메시지가 생성되는 문제를 수정합니다.
-   여러 이미지가 포함된 보고서를 실행할 때 프로젝트가 중단될 수 있는 문제를 해결합니다.

### <a name="publisher-feature-updates"></a>Publisher: 기능 업데이트
-   **위험한 확장 차단:** 위험을 초래할 것으로 간주되며, OLE 패키지 개체로 포함되어 있는 확장명은 기본적으로 활성화되지 않도록 차단됩니다. 예로 .exe, .vbs 및 .js가 있습니다. [자세한 정보](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="publisher-non-security-updates"></a>Publisher: 비보안 업데이트
-   편지 병합 마법사를 실행할 때, null 값이 포함된 데이터 원본 필드를 필터링하지 못하는 문제를 해결합니다.

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
-   모임에서 'Skype 통화'를 선택하여 사용자를 추가하면 오류가 발생하는 문제를 해결합니다.
-   Skype 룸이 위치에 추가되고 모임에 팀 모임 좌표가 이미 포함되어 있는 경우 모임에 Skype 좌표를 추가하도록 사용자에게 요청하는 메시지를 제거합니다.
-   UseLocationForE911Only가 true로 설정되어 있어도 위치가 채워지는 문제를 수정합니다.
-   “회의 센터를 사용하여 통화” 옵션을 사용하여 로스터에서 사용자를 초대할 때 비즈니스용 Skype가 중지되는 문제를 수정합니다.
-   비즈니스용 Skype 모임을 만드는 동안 터미널 서버에서 실행하는 Outlook이 중지되는 문제를 수정합니다.
-   EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket의 기본값을 true로 변경합니다.
-   모임이 전체 화면 모드일 때 "기타 옵션" 및 "다른 사용자 초대" 단추가 숨겨지는 문제를 해결합니다.
-   P2P 화상 회의 창 또는 전화 회의 창에 참여하려고 하면 창이 투명해지는 문제를 해결합니다.
-   예정된 Skype 모임이 모임 탭에 표시되지 않는 문제를 해결합니다.
-   비즈니스용 Skype가 오디오 없이 모임에 참여하도록 구성되어 있을 때, 모임에 오디오를 추가하면 기존 모임에 오디오가 추가되지 않고 사용자 자신에 대한 새 P2P 호출이 시작되는 문제를 해결합니다.
-   Outlook의 모임 요청에서 ‘Skype 모임 참가’ 링크를 클릭할 때 “이 Skype 모임을 찾을 수 없습니다.” 오류 메시지가 표시되는 문제를 해결합니다.
-   들어오는 PSTN 호출에 대한 알림 UI에서 통화 전달 단추를 추가할 수 있습니다.
-   ChatDefaultClient 및 CallDefaultClient가 Teams로 설정될 경우 통화 및 채팅이 팀에 전달될 것임을 나타내는 알림이 사용자에게 전송될 수 있습니다.
-   사용자가 모임에 참여하지 않고 비즈니스용 Skype에서 사용되지 않도록 설정되고, 모임 참가 환경이 Native Limited Client로 설정될 때 사용자의 현재 상태를 오프라인으로 표시할 수 있습니다.
-   비즈니스용 Skype가 알림 영역으로 최소화될 때 열기 및 끝내기를 제외한 모든 옵션을 사용하지 않도록 설정할 수 있습니다.
-   Aries 휴대폰과 연결되고 RedirectClient가 사용되도록 설정될 경우 새 통화 및 대화가 표시되지 않도록 할 수 있습니다.
-   날짜 형식이 미국 형식(mm/dd/yy)이 아닐 경우 PChat의 메시지를 날짜별로 검색하지 못하는 문제를 해결합니다.
-   EnableExternalP2PFileTransfer 정책을 false로 설정하는 경우에도 사용자가 모임에 파일을 첨부할 수 있는 문제를 해결합니다.
-   대화 내용에 호출한 상대방이 아닌 발신자가 표시되는 문제를 수정합니다. 이러한 문제는 호출한 상대방의 직장 번호가 Active Directory를 사용하여 수정된 경우에 발생합니다.
-   모바일 전화번호에 걸린 발신 PSTN 통화의 경우 대화 내용의 통화 기록에 수신자 정보가 표시되지 않는 문제를 수정합니다.
-   Outlook의 전자 메일에서 메신저를 시작하면 전자 메일의 제목 줄이 메신저의 제목에 포함되지 않는 문제를 수정합니다.
-   메신저 대화 창을 한쪽으로 끌어오면 대화가 두 번 누적되어 표시되는 문제를 수정합니다.
-   VDIv2 환경에서 VbSS 화면 공유 요청이 RDP 기반 요청으로 표시되는 문제를 수정합니다.
-   통화 전송이 실패한 경우 실패 알림에 없는 수신자가 아닌 발신자가 나열되는 문제를 수정합니다.
-   "Teams 사용 시작" 버튼이 클라이언트 업그레이드 리디렉션 배너 내에 숨겨져 있는 문제를 수정합니다.
-   메신저 창에서의 DPI 조정 문제를 수정합니다.
-   LinkedIn 데이터가 비즈니스용 Skype 대화 상대 카드에 표시되지 않는 문제를 수정합니다.
-   사용자가 헌트 그룹을 대신하여 통화 수신을 중단할 수 있는 기능을 추가합니다.
-   비즈니스용 Skype 또는 Teams에서 통화가 활성화되어 있고 새로운 통화가 수신되거나 시작된 경우 자동으로 통화를 보류할 수 있는 기능을 추가합니다.
-   전체 화면 공유 후에 사용자가 메시지를 보낼 수 없는 문제를 수정합니다.
-   사용자가 모임 참석을 거부당하면 대기실에 있는 사용자가 공지받지 못하는 문제를 수정합니다.
-   통화하는 동안 자동 게인 컨트롤이 통제할 수 없이 늘어나는 문제를 수정합니다.
-   회의실 리소스 사서함이 모임 초대에 추가될 때 사용자가 모임 옵션에서 발표자를 선택할 수 없는 문제를 해결합니다.
-   AllowlPVideo가 False로 설정되어 있는 경우 피어 투 피어 화상 통화를 하는 동안 바탕 화면 공유 단추가 흐리게 되는 문제를 해결합니다.
-   메신저 사용 제한으로 만들어진 기존 모임에 대해 모임 옵션 설정을 메신저 사용을 변경한 후에 메신저가 유지되지 않는 문제를 해결합니다.
-   채팅 창에서 "링크 삽입" 단추를 가리키고, 단추를 선택했을 때 접근성 이름이 없으면 도구 설명이 표시되지 않는 문제를 해결합니다.

### <a name="visio-feature-updates"></a>Visio: 기능 업데이트
-   **기본 제공 데이터베이스 모델 다이어그램:** 새 데이터베이스 모델 다이어그램 템플릿을 사용하여 데이터베이스를 Visio 다이어그램으로 정확하게 모델링합니다. 추가 기능은 필요하지 않습니다.
-   **비즈니스 다이어그램용 추가 스텐실:** 최신 셰이프를 사용하거나, 데이터를 벤 다이어그램과 비교 및 대조하거나, 주기형, 매트릭스 또는 피라미드형 다이어그램을 그려 의미를 보다 잘 전달할 수 있습니다.
-   **웹 사이트에 대한 와이어프레임 다이어그램 만들기:** 인터페이스, 탐색 및 작동 방식을 비롯한 웹 사이트의 와이어프레임 다이어그램을 신속하게 만듭니다. [자세한 정보](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **모바일 응용 프로그램의 와이어프레임 만들기:** 템플릿을 사용하여 모바일 응용 프로그램의 와이어프레임을 만들 수 있습니다. [추가 정보](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **데이터 시각화 도우미 다이어그램에 데이터 그래픽 적용:** 도형 데이터를 자동으로 데이터 그래픽으로 적용하여 데이터 시각화 도우미 다이어그램을 만들 때 시간을 절약할 수 있습니다. [자세한 정보](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)
-   **그리기 공동 작업** 비즈니스용 OneDrive 또는 SharePoint Online에서 다른 사용자와 그림을 공유하여 함께 작업합니다. 그리기 작업 중인 사람을 확인하고 메모를 추가하거나 파일 활동을 볼 수 있습니다. [자세한 정보](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)
-   **위험한 확장 차단:** 위험을 초래할 것으로 간주되며, OLE 패키지 개체로 포함되어 있는 확장명은 기본적으로 활성화되지 않도록 차단됩니다. 예로 .exe, .vbs 및 .js가 있습니다. [자세한 정보](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="word-feature-updates"></a>Word: 기능 업데이트
-   **SVG 아이콘을 도형으로 변환:** 모든 SVG 그림 및 아이콘의 색, 크기 또는 질감을 변경할 수 있도록 Office 도형으로 변환합니다.
-   **문자 수:** 입력할 때 상태 표시줄에 문자 수가 표시됩니다. 상태 표시줄 사용자 지정 메뉴에서 이 기능을 사용할 수 있습니다.
-   **사이트와 그룹에 대한 빠른 액세스:** 파일 메뉴를 사용하여 자주 사용하는 사이트와 그룹에 저장된 문서를 사용할 수 있습니다.
-   **Microsoft Translator:** Word에서 Microsoft Translator를 사용하여 단어, 구문 또는 문서 전체를 다른 언어로 번역합니다. [자세한 정보](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)
-   **디지털 펜슬:** 새로운 연필 텍스처로 아이디어를 쓰거나 스케치하세요. 지원되는 디지털 펜을 기울여서 음영을 표현하세요.
-   **LinkedIn 기능 설정:** 파일 \> 옵션 \> 일반으로 이동하여 Office 응용 프로그램에 표시되는 LinkedIn 기능을 제어합니다. [자세한 정보](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **SharePoint 속성 패널:** 문서 내에서 SharePoint 문서 라이브러리 열 값을 표시 및 편집합니다. 보기 탭의 리본 단추를 사용하면 패널에 쉽게 액세스할 수 있으며 SharePoint 관리자는 문서 라이브러리 설정을 사용하여 속성 패널을 자동으로 열 수 있습니다.
-   **3D 모델:** 3D를 사용하여 문서의 시각적 효과 및 창의적 효과를 향상시킬 수 있습니다.  3D 모델을 간편하게 삽입한 후 360도로 회전할 수 있습니다. [자세한 정보](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **새 잉크 효과:** 금속 펜과 무지개, 은하수, 용암, 해양, 금, 은 등의 잉크 효과를 사용하여 세련된 아이디어를 표현할 수 있습니다.
-   **파일 공유 UI:** 비즈니스용 OneDrive 또는 SharePoint 파일의 경우 리본의 오른쪽 상단 모서리에 있는 공유 단추를 클릭하거나 파일 \> 공유로 이동하면 간단하게 향상된 공유 대화 상자가 나타납니다. 새 파일 또는 로컬에 저장한 파일의 경우 UI는 사용자가 OneDrive에 쉽게 파일을 업로드하여 공동 작업을 시작할 수 있게 합니다.
-   **위험한 확장 차단:** 위험을 초래할 것으로 간주되며, OLE 패키지 개체로 포함되어 있는 확장명은 기본적으로 활성화되지 않도록 차단됩니다. 예로 .exe, .vbs 및 .js가 있습니다. [자세한 정보](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **학습 도구를 사용한 편집:** 이제 Word의 웹 모양에서 학습 도구를 사용할 수 있습니다. 편집하는 동안 텍스트 간격을 조정하고 음절을 표시합니다. 모든 뷰에서 문서를 소리내어 읽을 때 각 단어가 강조 표시되는 것을 확인합니다. [자세한 정보](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
-   **LaTeX 구문:** LaTeX 구문을 사용하여 수학식을 만들고 편집합니다.
-   **유용한 사운드로 접근성 향상:** 오디오 신호를 켜면 작업할 때 안내를 받을 수 있습니다. 파일 \> 옵션 \> 접근성에서 확인할 수 있습니다. 추가 기능은 필요하지 않습니다. [자세한 정보](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **계정별 파일 위치:** 파일을 열거나 저장할 때 위치 목록이 연결된 계정을 기준으로 구성됩니다.
-   **펜 사용자 지정:** 잉크 입력을 위해 펜 및 형광펜의 개인 설정을 선택합니다. 사용자 지정 설정을 모든 Windows PC에서 사용할 수 있습니다.
-   **편집기 창의 향상된 쓰기 지원:** 편집기 창에서 고급 맞춤법, 문법 및 쓰기 스타일 권장 사항을 볼 수 있습니다. 보조 기술에 대한 향상된 지원을 통해 이러한 창 기능에 액세스할 수 있습니다.

### <a name="word-security-updates"></a>Word: 보안 업데이트
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook 원격 코드 실행 취약성
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Microsoft Office 메모리 손상 취약성
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Microsoft Office 메모리 손상 취약성
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Microsoft Word 메모리 손상 취약성
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Microsoft Office 정보 노출 취약성
-   [공지 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Microsoft Office 심층 방어 업데이트

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   비지니스용 OneDrive의 기존 문서를 다른 이름으로 저장 후 취소하거나 기존 변경사항을 병합하려 할 때 Word가 중단되는 문제를 해결합니다.
-   편지 병합 마법사를 실행할 때, null 값이 포함된 데이터 원본 필드를 필터링하지 못하는 문제를 해결합니다.
-   동기화 백업 파일을 저장할 때 Office에서 디스크를 쓸 수 없지만 파일을 계속 OneDrive로 업로드하는 문제를 해결합니다. 이 수정 사항을 통해 사용자는 이제 오류 메시지를 확인할 수 있으며 업로드가 진행되지 않습니다.
-   문서에 IRM 보호 제거를 할 경우 보호가 제거되지 않는 문제를 해결합니다.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Microsoft Office 메모리 손상 취약성
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Microsoft Office 메모리 손상 취약성
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Microsoft Office 정보 노출 취약성
-   [공지 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Microsoft Office 심층 방어 업데이트

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   응용 프로그램을 열 때 안전 모드에서 시작된다는 메시지가 표시된 후 응용 프로그램이 열리지 않는 문제를 해결합니다.
-   Office 365 클라이언트 업데이트가 Configuration Manager에 의해 관리되도록 Office COM 개체가 사용 가능하게 업데이트될 때 지금 업데이트 옵션이 파일 \> 계정 \> 업데이트 옵션에서 숨겨집니다.
-   사용자가 Office 정품 인증 대화 상자를 사용하여 Office의 정품을 인증하려고 시도하면 Office 앱이 중지하는 문제를 수정합니다.
-   동적 DPI 환경의 Office 추가 기능에서 확대/축소 및 배율 조정 시 발생하는 문제를 해결합니다.
-   Office 365 ProPlus가 현재 설치되어 있더라도 Office CSP(구성 서비스 공급자)의 CurrentStatus 노드가 빈 문자열을 반환하는 문제를 해결합니다.
-   .box 파일이 동일한 컴퓨터의 모든 Office 앱 버전에서 공유되므로 .box 파일 형식이 변경될 경우 같은 컴퓨터설치에 된 이전 Office 버전의 기능에 영향을 미치는 문제를 해결합니다.



## <a name="version-1708-february-13"></a>버전 1708: 2월 13일
*버전 1708(빌드 8431.2215)*

### <a name="access-non-security-updates"></a>Access: 비보안 업데이트
-   다중 항목 폼을 사용할 때 마우스 휠이나 스크롤 막대 위치 조정 컨트롤의 위치를 조정해도 폼에 표시되는 항목이 달라지지 않는 문제를 해결합니다.

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Microsoft Excel 원격 코드 실행 취약성

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook 권한 상승 취약성
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Microsoft Office Outlook 메모리 손상 취약성

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Microsoft Office 메모리 손상 취약성
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Microsoft Office 정보 노출 취약성



## <a name="version-1708-january-9"></a>버전 1708: 1월 9일
*버전 1708(빌드 8431.2153)*

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Microsoft Excel 원격 코드 실행 취약성
-   [공지 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office 심층 방어 업데이트

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   프로그래밍 방식으로 피벗 테이블을 생성한 후 프로그래밍 방식으로 새로 고칠 경우 Excel이 중단되는 문제를 해결합니다.

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook 원격 코드 실행 취약성
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook 원격 코드 실행 취약성

### <a name="word-security-updates"></a>Word: 보안 업데이트
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook 원격 코드 실행 취약성
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Microsoft Office 메모리 손상 취약성
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Microsoft Office 메모리 손상 취약성
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Microsoft Word 원격 코드 실행 취약성
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Microsoft Word 메모리 손상 취약성

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Microsoft Office 원격 코드 실행 취약성
-   [공지 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Microsoft Office 심층 방어 업데이트

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   ID가 온-프레미스 Active Directory와 페더레이션되는 Office 365 Germany 요금제의 도메인 사용자에 대한 SSO(Single Sign-On)를 추가적으로 지원합니다.
-   미성년자가 Office 스토어에 제공되는 Office 추가 기능을 획득하고 정품 인증을 받지 못하도록 하는 기능이 추가되었습니다.


> [!NOTE]
> Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.