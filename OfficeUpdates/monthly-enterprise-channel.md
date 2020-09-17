---
title: 2020년 Monthly Enterprise Channel 릴리스에 대한 릴리스 정보
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 2020년 Microsoft 365 Apps에 대한 Monthly Enterprise Channel 릴리스 정보를 IT 전문가에게 제공합니다.
ms.openlocfilehash: a9301d0f53144a666571e563472f88b3bc5da924
ms.sourcegitcommit: b7cd1fc37ece6cf0399d89549f7916a4dc40d829
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/16/2020
ms.locfileid: "47942805"
---
# <a name="release-notes-for-monthly-enterprise-channel-releases-in-2020"></a>2020년 Monthly Enterprise Channel 릴리스에 대한 릴리스 정보

이러한 릴리스 정보는 기업용 Microsoft 365 Apps, 비즈니스용 Microsoft 365 Apps 및 Project와 Visio용 데스크톱 앱의 구독 버전에 대한 2020년 Monthly Enterprise Channel 업데이트에 포함된 새로운 기능 및 비보안 업데이트 관련 정보를 제공합니다.

> [!IMPORTANT]
> 당사는 Microsoft 365 앱에 대한 업데이트 채널을 일부 변경하고 있습니다. 여기에는 새 업데이트 채널 추가(월별 엔터프라이즈 채널) 및 기존 업데이트 채널의 이름 변경 등이 포함됩니다. 자세한 내용은 [이 문서를 검토하세요](https://go.microsoft.com/fwlink/p/?linkid=2127441).

[//]: # (제거하지 마세요)



## <a name="version-2007-september-08"></a>버전 2007: 9월 8일
*버전 2007(빌드 13029.20534)*

[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a>기능 업데이트
### <a name="outlook"></a>Outlook

- **IT 관리자에 대한 인시던트 알림:** Microsoft 365 테넌트 전역 관리자 및 Office 앱 관리자는 Windows용 Outlook의 새로운 오른쪽 패널 알림을 통해 사용자에게 영향을 주는 Outlook 및 O365 Exchange 인시던트에 대한 알림을 받습니다. [자세한 정보](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **이전 세션에서 항목을 빠르게 다시 열기:** 이전 Outlook 세션에서 항목을 빠르게 다시 여는 옵션을 추가했습니다. Outlook에서 충돌이 발생하든 사용자가 Outlook을 닫든 이제 앱을 다시 열 때 항목을 빠르게 다시 시작할 수 있습니다. 이 기능은 기본적으로 켜져 있습니다. 이 기능을 끄려면 옵션 > 일반 > 시작 옵션으로 이동합니다.

### <a name="word"></a>Word

- **벡터의 텍스트 보존:** 이제 Excel, Word 및 PowerPoint에서 이러한 개체를 변환할 때 맵, 차트 및 기타 SVG 벡터의 텍스트를 유지할 수 있습니다.

### <a name="office-suite"></a>Office 제품군

- **탭 창:** 이제 앱의 오른쪽에 있는 탭 UI를 사용하여 여러 창 간에 전환할 수 있습니다. UI는 2개 이상의 창이 열려있는 경우에만 표시됩니다.<br />[블로그 게시물](https://blog-insider.office.com/2020/02/20/improved-pane-management/)에서 세부 정보 보기


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제
### <a name="access"></a>액세스

- 이 수정은 특정 쿼리를 실행하려고 하면 이전에 '쿼리가 너무 복잡합니다'라는 오류 메시지가 발생한 문제를 해결합니다.


### <a name="excel"></a>Excel

- 페이지 나누기 미리 보기에서 여러 시트가 포함 된 통합 문서를 로드할 때 오류 또는 중단이 발생할 수 있는 문제를 해결 했습니다.


- LET() 함수를 사용하여 수식이 들어 있는 파일을 저장할 때 오류가 발생할 수 있습니다.


### <a name="outlook"></a>Outlook

- 인시던트 알림 경고에서 서식 문제가 발생하는 문제를 해결했습니다.


- 아웃룩 사용자가 컴팩트 뷰에서 탐색 관련 문제를 볼 수 있는 문제를 해결했습니다.


- 개인 정보 검색 시 사용자가 때때로 충돌하는 문제를 해결했습니다.


- 일정 정리 페이지가 표시되지 않는 문제를 해결했습니다.


- 보안 대화 상자에서 "저장" 옵션을 선택할 때 사용자가 테넌트 외부에서 로컬 컴퓨터에 OneDrive 첨부 파일을 저장할 수 없는 문제가 해결되었습니다.


- 공유 폴더 다운로드를 선택하지 않은 경우에 “전달 허용” 옵션이 공유 일정 모임 "응답 옵션"에서 누락되는 문제가 해결되었습니다.


- Outlook에서 검색 제안을 검색하지 못한 문제를 해결했습니다.


- SharePoint 파일에 스마트 링크를 추가할 때 일부 문자 집합 사용자에게 파일 이름을 잘못 표시되는 문제를 해결했습니다.


- 보호되는 컨텍스트에서 보호되지 않은 컨텍스트로 회신 보낸 사람 주소를 전환할 때 CLP 사용자에게 충돌이 발생하는 문제를 해결했습니다.

- 사용자가 새 메일에 회신하거나 작성할 때 충돌이 발생한 문제를 해결합니다.


### <a name="powerpoint"></a>PowerPoint

- PowerPoint 앱에서 충돌 문제를 해결했습니다.


### <a name="project"></a>Project

- Project에서 SharePoint 문서 라이브러리에 PDF/XPS를 저장 할 수 없는 문제가 수정되었습니다.


- 여러 종속성이 있는 작업을 붙여 넣는 경우 일부 종속성이 제대로 복사 되지 않는 문제가 해결되었습니다.


- 자원 배정 대화 상자에서 선택한 작업이 작업 게시판 보기에서 선택 된 작업과 같지 않은 문제를 해결 했습니다.


- 상태가 좋지 않은 프로젝트를 열 수 없는 문제를 해결했습니다.



### <a name="office-suite"></a>Office 제품군

- 사용자가 특정 조건에서 UI 요소 또는 콘텐츠가 표시되지 않는 문제를 해결했습니다. 특히 프리젠터 뷰를 드나드는 경우 또는 여러 모니터를 사용하는 경우 문제가 해결되었습니다.


- 전체 제품으로 전환이 완료되었음에도 런타임 메시지가 표시되는 문제를 해결했습니다. 서비스가 올바르게 계산 된 제품이 추가 되었는지 확인하여 수정 할 수 있습니다. 새로 추가한 제품(새 구성에도 존재 하는지 확인)을 필터링하고 기존 제품 출시 ID 끝에 추가 했습니다.


- 이전 웹 서비스 기반 공유 창의 경우 공유 창이 열려 있는 동안 문서를 닫으면 충돌이 발생할 수 있습니다. 이제 이 문제는 해결되었습니다.



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2006-september-08"></a>버전 2006: 9월 8일
*버전 2006(빌드 13001.20648)*

[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트

## <a name="version-2006-august-11"></a>버전 2006: 8월 11일
*버전 2006(빌드 13001.20520)*

[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a>기능 업데이트
### <a name="excel"></a>Excel

- **대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.

- **다른 사용자를 방해하지 않고 필터링 및 정렬:** 이제 시트 뷰로 다른 사용자와 공동 작업하면서 Excel 파일을 정렬하고 필터링할 수 있습니다. 이 새 기능을 사용하면 문서를 공동 작성하는 동안 다른 사용자의 정렬 및 필터에 영향을 받지 않습니다. [자세한 정보](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

### <a name="outlook"></a>Outlook

- **그룹의 데이터 보호 지원:** 그룹을 만들 때 선택한 민감도 레이블이 그룹 전자 메일, 문서, 팀 사이트에 적용됩니다.

- **애니메이션 GIF로 이야기하기: **애니메이션 GIF가 오피스 편집기에서 지원되므로 문서가 더 복잡해집니다.

- **Outlook에서 메일 작성 시 @멘션 제안을 사용하지 않는 새 옵션:** @멘션 선택기가 유용하기보다는 불편하게 느껴지나요? 원하는 경우 바로 지금 비활성화할 수 있습니다.<br />[블로그 게시물](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)에서 세부 정보 보기

- **사진을 전자 메일의 일부로 보낼 때 사진을 높은 정확도로 보관합니다.** 새 Outlook 설정을 사용하여 전자 메일 내용의 일부로 사진을 보낼 때 사진 압축을 제한할 수 있습니다.

### <a name="powerpoint"></a>PowerPoint

- **대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.

- **PowerPoint의 스트림 비디오 성능 향상:** Microsoft Stream 비디오의 재생 성능을 개선하여 비디오 로드 시간을 최소화하고 원활한 보기 환경을 조성했습니다. Microsoft Stream의 회사 비디오를 사용하여 더 나은 프레젠테이션을 만들 수 있습니다.

### <a name="word"></a>Word

- **대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.

- **다른 방식으로 말하기:** 다르게 표현하는 경우 재작성은 도움을 줍니다. 재작성은 표현을 기교있게 만들어주는 대안을 제공합니다.<br />[블로그 게시물](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)에서 세부 정보를 참조하세요.

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제
### <a name="access"></a>Access

- 쿼리 실행이 예상했던 시간보다 거의 두 배 이상 걸리는 문제를 해결했습니다.

- ID(예: 일련 번호) 필드를 포함하는 연결된 SQL 테이블을 삽입할 때 발생하는 문제를 해결했습니다.


### <a name="excel"></a>Excel

- SharePoint/OneDrive에 저장하는 경우 사용자 지정 리본 탭이 CustomUI XML을 제거하는 문제가 해결되었습니다.

- 페이지 구분 미리보기의 여러 시트로 워크북을 로드할 때 오류 또는 중단이 발생할 수 있는 문제를 해결했습니다.

- 계정에서 로그아웃한 경우 데이터 연결을 만들 때 발생할 수 있는 충돌을 수정했습니다.

- 읽기 전용 모드에 있는 문제집에 대해 자동 문서 분류가 수행되었을 수 있습니다.

### <a name="onenote"></a>OneNote

- 리소스 사용률을 줄이기 위해 공동 작성 상태의 검색 기능을 개선했습니다.

### <a name="outlook"></a>Outlook

- SVG 이미지 복사하여 붙여넣기 문제를 해결 했습니다.

- 기능 제안에서 기능을 검색하여 결과를 반환하지 않고 사용자에게 새 기능 아이디어를 제출할 수 있는 옵션이 없는 문제를 해결합니다.

- 클라우드 설정을 사용하도록 설정한 경우 Ctrl+클릭이 작동을 중지하도록 만든 문제를 해결합니다.

- 보안 대화 상자에서 "저장" 옵션을 선택할 때 사용자가 테넌트 외부에서 로컬 컴퓨터에 OneDrive 첨부 파일을 저장할 수 없는 문제를 해결합니다.

- 사용자에게 Outlook에서 받은 편지함 복구 도구를 실행하라는 메시지가 지속적으로 나타나는 문제가 해결됩니다.

- 공유 일정 향상 사용자에게 일정 오류가 표시되는 문제를 해결합니다.

- 4501년 1월 1일로 설정된 드래그 앤 드롭을 통해 파일 시스템에 복사한 첨부 파일의 작성 날짜를 볼 수 있는 문제를 해결합니다.

### <a name="project"></a>프로젝트

- 프로젝트 요약 작업(프로젝트 시작/작업 필드)이 변경될 때 ProjectBeforeTaskChange 이벤트가 발생하지 않는 문제를 해결했습니다.

- 100% 완료로 표시된 작업이 100% 미만으로 잘못 변경되는 문제를 해결했습니다.

- URL이 .com으로 끝나는 경우 Project Web App에서 Project Desktop Client에서 프로젝트를 열 수 없는 문제를 해결했습니다.

### <a name="word"></a>Word

- SVG 이미지 복사하여 붙여넣기 문제를 해결 했습니다.

### <a name="office-suite"></a>Office 제품군

- 이전 AppV51의 회귀 분석을 수정하기 위해 새로운 AppV51 드롭을 다시 보고했습니다.

- 시간 문제 때문에 Office 파일을 닫을 때 충돌이 발생할 수 있습니다.

- 레지스트리 TabProcGrowth 값이 REG_SZ 유형이면 추가 기능이 활성화될 때 Office 호스트가 Windows에서 충돌하는 문제를 해결했습니다.


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2005-august-11"></a>버전 2005: 8월 11일
*버전 2005(빌드 12827.20656)*

나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2005-july-14"></a>버전 2005: 7월 14일
*버전 2005(빌드 12827.20538)*

[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)에 보안 업데이트가 나열됩니다.


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a>기능 업데이트
### <a name="outlook"></a>Outlook

- **즉시 더 나은 결과 얻기:** 이전보다 더 스마트하고, 빠르고, 안정적이 되도록 검색 환경을 업데이트했습니다. [자세한 정보](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)




[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제
### <a name="access"></a>Access

- 앱에서 충돌 없이 날짜/시간 확장 데이터 형식을 코드로 호출할 수 있도록 문제가 해결되었습니다.

- 최근에 업데이트된 Access 버전으로 되돌리고 DAO/VBA를 사용하여 10진수 데이터 형식을 관리하고 편집할 수 있도록 문제가 해결되었습니다.

### <a name="excel"></a>Excel

- 팀을 통해 Excel 창을 공유할 때 Ctrl+Shift+화살표 키를 사용하여 스크롤한 후 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.

- 경우에 따라 동일한 통합 문서 안의 위치에 대한 하이퍼링크를 클릭하면 통합 문서이 숨겨집니다.

- SharePoint/OneDrive에 저장하는 경우 사용자 지정 리본 탭이 CustomUI XML을 제거하는 문제가 해결되었습니다.

- 도표 시트에 PivotTables를 삽입하려고 할 때 Excel이 충돌할 수 있는 문제가 해결됩니다.

### <a name="outlook"></a>Outlook

- 관리자 알림에서 피드백을 제출할 때 사용자가 충돌을 경험하게 되는 문제가 해결됩니다.

- 기능 제안에서 기능을 검색하여 결과를 반환하지 않고 사용자에게 새 기능 아이디어를 제출할 수 있는 옵션이 없는 문제를 해결합니다.

- 사용자에게 Outlook에서 받은 편지함 복구 도구를 실행하라는 메시지가 지속적으로 나타나는 문제가 해결됩니다.

- Windows 10 서버 버전 사용자에게 “바이러스 백신 상태: 올바르지 않음”이라는 경고 메시지가 표시되는 문제를 해결합니다. 이 Windows 버전에서는 바이러스 백신 감지를 지원하지만 바이러스 백신 프로그램이 올바르게 설치되었음에도 불구하고 해당 프로그램을 찾을 수 없습니다.

- 일부 시나리오에서 사용자가 간헐적 중단과 충돌을 경험하는 문제가 해결됩니다.

- 공유 일정 향상 사용자에게 일정 오류가 표시되는 문제를 해결합니다.

- Outlook에서 규칙을 업데이트할 때 “이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다.” 메시지가 표시되는 문제를 해결합니다.

- 4501년 1월 1일로 설정된 드래그 앤 드롭을 통해 파일 시스템에 복사한 첨부 파일의 작성 날짜를 볼 수 있는 문제를 해결합니다.

- Outlook에서 M365 Business Plus 계획에 있는 서비스 비용을 지불한 사용자에게 데이터 손실 보호 정책 팁을 활성화하지 못하는 문제가 해결됩니다.

- 회신/전송 레이블에 대한 CLP 감사 이벤트와 관련된 문제가 해결됩니다.


### <a name="powerpoint"></a>PowerPoint

- 이렇게 하면 사용자가 파일에 최신 및 기존 주석을 모두 가지고 있을 때 충돌이 발생하여 주석을 업그레이드하게 됩니다.

- 제안 창에서 발생하는 충돌 문제를 해결했습니다.


### <a name="project"></a>Project

- 프로젝트 요약 작업(프로젝트 시작/작업 필드)이 변경될 때 ProjectBeforeTaskChange 이벤트가 발생하지 않는 문제를 해결했습니다.

- 100% 완료로 표시된 작업이 100% 미만으로 잘못 변경되는 문제를 해결했습니다.

### <a name="skype"></a>Skype

- 사용자에게 Teams 전용으로 이동하는 정책이 지정되어도 Skype for Business Outlook 추가 기능을 사용하여 모임을 예약할 수 있었습니다. 이 업데이트 후, 클라이언트가 사용자가 Teams 전용임을 나타내는 정책을 읽고 모임 참가 전용 모드로 들어간 후에는 더 이상 Skype for Business 모임을 예약할 수 없습니다. 또한 Skype for Business Outlook 추가 기능은 Skype for Business 클라이언트가 미팅 참가 모드인 경우 시작하는 동안 자체적으로 활성화되지 않습니다.

### <a name="word"></a>Word

- 앱의 일부 콘텐츠를 끌 때 충돌이 발생할 수 있는 문제가 해결되었습니다.

### <a name="office-suite"></a>Office 제품군

- 이 변경 사항은 GIF 또는 3D 모델과 같은 애니메이션 콘텐츠를 로드하고 재생할 때 발생할 수 있는 중단 현상을 해결합니다.

- 검증을 확인했습니다.기본적으로 Bing Addon 설치 검증을 true로 설정하고 MSI 반환 성공을 설치 성공으로 간주하여 설치 실패율 문제를 해결합니다.

- 이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. 

- 이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.

- 레지스트리 키 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth가 0으로 설정되어있는 동안 추가 기능이 활성화될 때 사무실 호스트가 Windows에서 충돌했습니다. 이렇게 변경하면 이 문제가 해결됩니다.


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-july-14"></a>버전 2004: 7월 14일
*버전 2004(빌드 12730.20602)*

[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)에 보안 업데이트가 나열됩니다.

## <a name="version-2004-june-09"></a>버전 2004: 6월 9일
*버전 2004(빌드 12730.20430)*

[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a>기능 업데이트
### <a name="access"></a>Access

- **더 적은 수의 클릭으로 테이블 추가:** 작업하는 동안 열려 있는 테이블 추가 작업창을 사용하여 관계와 쿼리에 테이블을 추가합니다. [자세한 정보](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.<br />[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보 보기

- **Facebook 커넥터 지원 종료:** 2020년 4월부터는 Excel에서 Facebook 커넥터를 사용하는 외부 데이터 연결을 더 이상 지원하지 않습니다.

- **통합 문서에 활기를 불어넣어줄 새로운 이미지:** 수천 개의 무료 스톡 이미지, 아이콘 및 스티커를 통합 문서에서 사용할 수 있습니다. 시작 하려면 삽입 > 사진 > 스톡 이미지로 이동합니다. [자세한 정보](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />[블로그 게시물](https://blog-insider.office.com/2020/04/06/premium-creative-content/)에서 세부 정보 보기

### <a name="outlook"></a>Outlook

- **완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.<br />[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.

- **사용자가 소유한 그룹으로 전자 메일 끌기:** 메시지와 대화를 받은 편지함에서 끌어서 이동하고 복사합니다. 끌어 놓은 메시지는 모든 그룹 구성원과 공유됩니다.<br />[블로그 게시물](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)에서 세부 정보를 참조하세요.

- **일정 모양 변경:** 일정을 더욱 쉽게 훑어볼 수 있도록 하는 시각적 업데이트를 참조하세요. [자세한 정보](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />[블로그 게시물](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)에서 세부 정보 보기

- **메시지에 활기를 불어넣어줄 새로운 이미지:** 수천 개의 무료 스톡 이미지, 아이콘 및 스티커를 전자 메일 메시지에서 사용할 수 있습니다. 시작 하려면 삽입 > 사진 > 스톡 이미지로 이동합니다. [자세한 정보](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />[블로그 게시물](https://blog-insider.office.com/2020/04/06/premium-creative-content/)에서 세부 정보 보기

### <a name="powerpoint"></a>PowerPoint

- **완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.<br />[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.

- **발표하는 동안 변경 내용 동기화:** 프레젠테이션이 슬라이드 쇼 모드에 있더라도 내용이 변경될 때마다 동기화됩니다. [자세한 정보](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />[블로그 게시물](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)에서 세부 정보 보기

- **슬라이드에 활기를 불어넣어줄 새로운 이미지:** 수천 개의 무료 스톡 이미지, 아이콘 및 스티커를 프레젠테이션에서 사용할 수 있습니다. 시작 하려면 삽입 > 사진 > 스톡 이미지로 이동합니다. [자세한 정보](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />[블로그 게시물](https://blog-insider.office.com/2020/04/06/premium-creative-content/)에서 세부 정보 보기

### <a name="word"></a>Word

- **잉크 올가미:** 그리기 탭의 올가미 도구를 사용하면 잉크로 그린 개체를 선택할 수 있습니다. 개별 스트로크를 선택하거나 단어 전체를 선택합니다. [자세한 정보](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.<br />[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.

- **문서에 활기를 불어넣어줄 새로운 이미지:** 수천 개의 무료 스톡 이미지, 아이콘 및 스티커를 문서에서 사용할 수 있습니다. 시작 하려면 삽입 > 사진 > 스톡 이미지로 이동합니다. [자세한 정보](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />[블로그 게시물](https://blog-insider.office.com/2020/04/06/premium-creative-content/)에서 세부 정보 보기

### <a name="office-suite"></a>Office 제품군

- **민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제
### <a name="excel"></a>Excel

- 파일 경로가 너무 길면 파일을 다시 연 후 외부 링크가 작동하지 않는 문제를 해결했습니다.

- 일부 경우에 Application.Evaluate(VBA)가 사용자 정의 함수에서 제대로 작동하지 않았습니다.

- Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.

- 일부 경우에 피벗 테이블을 포함하는 시트를 복사한 후 Excel 작동이 중단되는 문제가 해결되었습니다.

### <a name="outlook"></a>Outlook

- 관리자 알림에서 피드백을 제출할 때 사용자가 충돌을 겪게 하는 문제를 해결했습니다.

- Outlook을 종료하는 동안 사용자 작업이 중단되었던 문제를 해결했습니다.

- 토스트 알림을 표시할 때 충돌이 발생하는 문제를 해결했습니다.

- Windows 업데이트 후 로컬로 저장된 .msg 혹은 .oft 파일을 열 때 Outlook의 작동이 중단되었던 문제를 해결했습니다.

- 일부 Windows 빌드에서 Outlook이 중단되었던문제를 해결했습니다.

- 폴더 창의 너비가 예기치 않게 변경되는 문제를 해결했습니다.

### <a name="project"></a>Project

- 양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChange 이벤트가 실행됩니다.

- Project Web App에 연결된 Project를 사용하는 경우 소수 구분 기호가 쉼표이면 TaskDependencies Add 메서드가 종속성에 지연 시간을 추가하려할 때 실패하는 문제를 수정습니다.

### <a name="office-suite"></a>Office 제품군

- 기호 링크를 하드 링크하려고 할 때 업데이트 오류가 발생하는 간편 실행 문제를 해결했습니다.

- 레지스트리 키 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth가 0으로 설정되어있는 동안 추가 기능이 활성화될 때 사무실 호스트가 Windows에서 충돌했습니다. 이렇게 변경하면 이 문제가 해결됩니다.

- 이 수정은 액세스의 제한과 동시에 파일을 암호로 보호하는 작업을 할 수 없게 하는 오류를 해결합니다.

- 이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.

- 이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. 



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-june-09"></a>버전 2003: 6월 9일
*버전 2003(빌드 12624.20708)*

[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제
### <a name="office-suite"></a>Office 제품군

- 이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. 

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-may-12"></a>버전 2003: 5월 12일
*버전 2003 (빌드 12624.20588)*

나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a>기능 업데이트
### <a name="access"></a>Access

- **Query Designer, SQL 보기 및 관계 창에서 생산성을 향상시킬 수 있습니다.** 테이블을 마우스 오른쪽 단추로 클릭하여 열고 디자인하고 크기를 조정하고 숨겨보세요. SQL 보기에서 텍스트를 검색하고 바꾸세요. 관계 창에서 테이블을 여러 개 선택하세요.

### <a name="excel"></a>Excel

- **다중값을 반환하는 공식을 입력:** 다중값을 반환하는 공식을 신속히 입력하면 자동으로 인접한 셀들로 입력됩니다. [자세한 정보](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br />[블로그 게시물](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)에서 세부 정보를 참조합니다

- **더 이상 브라우저로 바운스하지 않음:** 사용자가 브라우저나 앱에서 Office 문서로의 링크를 여는 방법을 결정합니다.

- **유용한 함수 6개:** 스프레드시트를 더욱 유용하게 사용할 수 있는 함수 6개(FILTER, SORT, SORTBY, UNIQUE, SEQUENCE 및 RANDARRAY)가 추가되었습니다. [자세한 정보](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **왼쪽을 보고, 오른쪽을 보십시오… XLOOKUP이 여기 있습니다! ** 행별로 XLOOKUP을 사용하여 테이블 또는 범위에서 필요한 것을 모두 찾으십시오. [자세한 정보](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br />[블로그 게시물](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)에서 세부 정보를 참조합니다

- **읽고 즉시 회신:** 통합 문서를 열지 않고 전자 메일에서 바로 메모와 멘션을 통해 회신합니다.

### <a name="outlook"></a>Outlook

- **사람을 검색할 때 전자 메일 제안 받기:** 검색 상자에 사람의 이름을 입력하면 가장 관련성이 높은 전자 메일 메시지가 검색 제안에 포함됩니다. [자세한 정보](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- **그룹 명명 정책:** 그룹 명명 정책을 사용하면 IT 관리자가 조직의 사용자가 만든 그룹의 이름을 표준화하고 관리할 수 있습니다. 관리자는 그룹 이름을 만들 때 특정 접두사와 접미사를 추가하도록 요구할 수 있으며, 특정 단어를 사용할 수 없도록 차단할 수 있습니다. 이는 그룹 이름에 부적절한 단어의 사용을 최소화하는데 도움을 줄뿐만 아니라 IT가 해당 디렉터리의 그룹의 표현을 관리하는 데 도움이 됩니다. 명명 정책은 또한 팀 사이트를 배포하는 조직이 부서를 기준으로 분류하는데 도움을 줍니다.

- **받은 편지함을 벗어나지 않고 모임 참가:** 온라인 모임에 참가하기 위해 일정으로 전환할 필요가 없습니다. 일정을 할 일 창에 고정하고 클릭 한 번만으로 모든 모임에 참여하세요.

- **종속적인 Wi-Fi 네트워크에 대한 새로운 경험: ** 로그인하기 위해 웹 페이지가 필요한 Wi-Fi 네트워크에 가입한 적이 있습니까? 이제 Outlook이 이를 감지하여 연결하는 데 도움을 줍니다.

### <a name="powerpoint"></a>PowerPoint

- **PowerPoint에서 빠르게 실시간 공동 작업 수행:** PowerPoint에서 빠르게 실시간 공동 작업 수행

- **온라인 비디오의 새로운 홈:** 조직의 모든 사람이 볼 수 있도록 비디오를 Microsoft Stream에 저장하세요. 비디오 링크를 삽입하고 파일 크기의 일부로 멀티미디어 프레젠테이션을 즐겨보세요. [자세한 정보](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.

- **GIF 즉시 만들기:** 하나의 슬라이드, 하나의 프레임. PowerPoint에서 쉽게 루핑 GIF를 만들 수 있습니다. [자세한 정보](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />[블로그 게시물](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)에서 세부 정보를 참조하세요

- **향상된 다이어그램:** 더욱 향상된 커넥터와 원활한 잉크 변환 프로세스를 통해 아이디어를 더욱 확신을 가지고 잉크로 표현할 수 있습니다. [자세한 정보](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **슬라이드 쇼 중에 슬라이드 업데이트:** 프레젠테이션을 진행하는 동안 다른 작성자가 변경한 슬라이드를 업데이트합니다.<br />[블로그 게시물](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)에서 세부 정보를 참조하세요

### <a name="word"></a>Word

- **더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.

- **다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다.** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.

### <a name="office-suite"></a>Office 제품군

- **대용량 파일을 증분 방식으로 열기:** 프레젠테이션의 일부(예: 대형 비디오 또는 이미지)가 아직 다운로드를 완료하지 않은 경우에도 대규모 Powerpoint 프레젠테이션을 다운로드하고, 열고, 공유할 수 있습니다.


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제

### <a name="excel"></a>Excel

- 경우에 따라 Application.Evaluate(VBA)가 사용자 정의 함수에서 제대로 작동하지 않았습니다.

- 원본 주소록이 닫힌 경우 외부 링크가 채우기에 업데이트되지 않는 문제를 해결했습니다.


### <a name="onenote"></a>OneNote

- 페이지 버전 기록이 생성되는 빈도를 일시적으로 변경하여 동기화 및 서비스 안정성을 향상시켰습니다.


- 휴지통으로 페이지 이동을 일시적으로 비활성화하여 동기화 및 서버 안정성이 향상을 향상시켰습니다. 대신 페이지를 삭제하려는 사용자에게는 페이지를 영구적으로 삭제할 것인지를 묻는 대화 상자가 표시됩니다.


- OneNote 2016에서 새로운 내장형 첨부 파일의 최대 허용 크기를 50MB로 일시적으로 줄여 동기화 및 서비스 안정성을 개선했습니다. 이 제한을 초과하는 파일의 경우 사용자는 파일을 OneDrive에 업로드하고 OneNote에 링크를 삽입할 수 있습니다.


- OneNote 2016에서 앱 내 비디오 녹화를 일시적으로 사용하지 않도록 설정하여 동기화 및 서비스 안정성을 향상시켰습니다. 로컬 노트북은 이 조치의 영향을받지 않습니다.


- OneNote 2016에서 동기화 빈도를 일시적으로 조정하여 동기화 및 서비스 안정성을 개선했습니다.


- InfoBar를 통해 사용자에게 Microsoft OneNote의 임시 조정 사항에 대해 알려, 전 세계적으로 사용량이 많은 시간에 동기화 및 서비스 가용성을 향상시키는 데 도움이 됩니다.


### <a name="outlook"></a>Outlook

- 사용자가 종료 후 작업 관리자에 남아 있는 Outlook 프로세스를 보게 되는 문제를 해결했습니다.


- 마우스 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.


- 타사의 MAPI 응용 프로그램에서 충돌이 발생하게 하였던 문제를 해결했습니다.


- Windows 업데이트 후 로컬로 저장된 .msg 혹은 .oft 파일을 열 때 Outlook의 작동이 중단되었던 문제를 해결했습니다.


- 일부 Windows 빌드에서 Outlook이 중단되었던문제를 해결했습니다.


- 폴더 창의 너비가 예기치 않게 변경되는 문제를 해결했습니다.


### <a name="project"></a>Project

- 작업이 완료됨으로 표시된 후 작업 완료율이 100%보다 낮은 값으로 잘못 변경되는 문제가 해결되었습니다.


- OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.


- 요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.


- 비활성 단추를 통해 작업이 비활성화/활성화된 때를 ProjectBeforeTaskChange 이벤트에서 감지하지 못하는 문제를 해결했습니다. 


- 비활성 단추를 통해 작업이 비활성화/활성화된 때를 ProjectBeforeTaskChange 이벤트에서 감지하지 못하는 문제를 해결했습니다. 


- 이전 버전의 Project에서 만든 프로젝트를 저장하면 Project가 충돌할 수 있는 문제를 해결했습니다.


- 실제 작업 시간을 보호하는 설정이 설정된 경우 사용자가 기간별 초기 작업 시간을 입력할 수 없는 문제가 해결되었습니다.


- 양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChange 이벤트가 실행됩니다.


### <a name="word"></a>Word

- 마우스에서 "X" 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.

### <a name="office-suite"></a>Office 제품군

- 이 수정은 액세스의 제한과 동시에 파일을 암호로 보호하는 작업을 할 수 없게 하는 오류를 해결합니다.

- 이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

[//]: # (제거하지 마세요. 끝)

> [!NOTE]
> Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.


[//]: # (관리 센터 메타데이터 콘텐츠를 수정하지 마세요. 시작)
[//]: # (|Win32|MEC|Production|Feature|16.0.13029.20534|version-2007-september-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13001.20520|version-2006-august-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.12827.20538|버전 2005년 7월 14일|)
[//]: # (관리 센터 메타데이터 콘텐츠를 수정하지 마세요. 끝)
