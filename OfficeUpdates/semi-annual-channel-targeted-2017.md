---
title: 2017의 반기 채널 (대상 지정) 릴리스에 대 한 릴리스 정보
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: 2017의 Office 365 ProPlus에 대 한 반기 채널 (대상 지정) 릴리스에 대 한 릴리스 정보를 IT 전문가에 게 제공 합니다.
ms.openlocfilehash: 911626feb56a68ab258b51de78142dfaf6926bbe
ms.sourcegitcommit: 9301d8769d8860013e7b789a3360f48de461ad49
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/13/2020
ms.locfileid: "42615000"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>2017의 반기 채널 (대상 지정) 릴리스에 대 한 릴리스 정보

이러한 릴리스 정보에서는 2017의 Office 365 ProPlus에 대 한 반기 채널 (대상 지정) 업데이트에 포함 된 새로운 기능, 보안 업데이트 및 비보안 업데이트에 대 한 정보를 제공 합니다.
 
> [!NOTE]
> - 또한 Visio Pro for Office 365 및 Project Online 데스크톱 클라이언트에 대한 새로운 기능, 보안 업데이트 및 비보안 업데이트에 대한 정보도 제공합니다.
> - 이 정보는 일부 Office 365 계획에 제공되는 Office 버전(예: Business Premium)인 Office 365 Business에도 적용됩니다.
> - 반기 채널 (대상 지정)은 9 월 2017 이전 지연 채널에 대 한 첫 번째 릴리스입니다.

## <a name="version-1708-december-12"></a>버전 1708:12 월 12 일
*버전 1708(빌드 8431.2131)*

 ### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): Microsoft Excel 원격 코드 실행 취약성

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   매크로가 있는 Office 2007 또는 이전 버전의 통합 문서(.xls 또는 .xla)를 열면 사용자에게 "치명적 오류 발생" 오류 메시지가 잘못 표시되는 문제를 수정합니다.
-   명령줄에서 통합 문서를 열면 셀에서 서식 있는 텍스트가 손실 될 수 있는 문제를 수정합니다.

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Microsoft Office 정보 노출 취약성

### <a name="powerpoint-security-updates"></a>PowerPoint: 보안 업데이트
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint 정보 노출 취약성

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트
-   프로젝트 수준 사용자 지정 필드 데이터가 저장 시 손실될 수 있는 문제를 수정합니다.
-   저장에 실패한 파일이 손상되고 Project가 열려 있을 때 중지하는 문제를 수정합니다.
-   프로젝트 계획을 열면 중지될 수 있는 문제를 수정합니다.

### <a name="word-security-updates"></a>Word: 보안 업데이트
-   [공지 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office 심층 방어 업데이트



## <a name="version-1708-november-14"></a>버전 1708:11 월 14 일
*버전 1708(빌드 8431.2110)*

### <a name="access-non-security-updates"></a>Access: 비보안 업데이트
-   콤보 상자의 텍스트 상자에서 텍스트를 선택하려고 하려고 할 때 선택 영역만 표시되지 않고 모든 텍스트가 선택된 것처럼 나타나는 문제를 해결합니다.

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Microsoft Excel 보안 기능 바이패스 취약성
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Microsoft Excel 메모리 손상 취약성
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Microsoft Office 메모리 손상 취약성

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   파일 이름에 대괄호가 포함되어 있는 경우 사용자가 제한된 보기에서 통합 문서를 닫을 수 없는 문제를 해결합니다.
-   사용자가 기존 통합 문서에서 개체를 삽입하려고 할 때 찾아보기를 클릭하면 Excel이 충돌하는 문제를 해결합니다.
-   “텍스트에 맞게 도형 크기 조정”(도형 서식 창에서 텍스트 옵션/텍스트 상자 부분)을 선택할 경우 도형이 변경되지 않는 문제를 해결합니다.
-   통합 문서를 두 번 클릭하여 열 때 셀 텍스트 글꼴 및 형식이 로드되지 않거나 단일 서식 파일에 대해 두 개의 동일한 통합 문서가 열리는 문제를 해결합니다.
-   Excel이 시작될 때 만들어진 첫 번째 통합 문서가 새 통합 문서를 열거나 만들어도 닫히지 않는 문제를 해결합니다.
-   끌거나 끌어서 채울 시, 도구 설명의 위치가 일치하지 않는 문제를 해결합니다.
-   통합 문서를 파일 \> 다른 이름으로 저장으로 저장할 때, 파일 이름에 마침표가 포함되면 파일이 저장 대화상자에 빈 상태로 혹은 잘려서 나타나는 문제를 수정합니다.
-   동기화 백업 파일을 저장할 때 Office에서 디스크를 쓸 수 없지만 파일을 계속 OneDrive로 업로드하는 문제를 해결합니다. 이 수정 사항을 통해 사용자는 이제 오류 메시지를 확인할 수 있으며 업로드가 진행되지 않습니다.
-   결함이 있는 그래픽 드라이버로 인해 검은색 선 및 헤더가 표시되는 렌더링 관련 문제를 해결합니다.
-   차트를 삽입한 후 Excel이 충돌하거나 통합 문서를 저장할 수 없는 문제를 해결합니다.
-   페이지 나누기 미리 보기에서 페이지 나누기가 제대로 배치되지 않는 문제를 해결합니다.

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   사용자가 메시지를 삭제할 때 메시지 목록의 포커스가 예기치 않게 이동되는 문제를 해결합니다.
-   사용자가 첨부 파일로 상호 작용할 때 인증 프롬프트가 표시되는 문제를 해결합니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   동기화 백업 파일을 저장할 때 Office에서 디스크를 쓸 수 없지만 파일을 계속 OneDrive로 업로드하는 문제를 해결합니다. 이 수정 사항을 통해 사용자는 이제 오류 메시지를 확인할 수 있으며 업로드가 진행되지 않습니다.
-   표에서 실행 취소한 후에 텍스트를 편집하고 서식을 지정할 경우 PowerPoint가 충돌하는 문제를 해결합니다.
-   Flash Player 기반 YouTube 포함 코드에 대한 참조를 수행할 경우 비디오 실행을 위해 새 창이 열리는 문제를 해결합니다. 이제 이전 포함 코드가 HTML5 기반 YouTube 비디오를 참조하도록 업그레이드되므로 올바르게 재생될 수 있습니다.

### <a name="word-security-updates"></a>Word: 보안 업데이트
-   [공지 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Microsoft Office 심층 방어 업데이트

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   비지니스용 OneDrive의 기존 문서를 다른 이름으로 저장 후 취소하거나 기존 변경사항을 병합하려 할 때 Word가 중단되는 문제를 해결합니다.
-   동기화 백업 파일을 저장할 때 Office에서 디스크를 쓸 수 없지만 파일을 계속 OneDrive로 업로드하는 문제를 해결합니다. 이 수정 사항을 통해 사용자는 이제 오류 메시지를 확인할 수 있으며 업로드가 진행되지 않습니다.
-   사용자가 Word를 연 후 삽입 탭으로 바로 이동할 경우 Word가 중지될 수 있는 문제를 해결합니다.
-   문자를 입력할 때 여백을 클릭하면 문자가 화면 왼쪽 위에 표시되는 문제를 해결합니다.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Microsoft Office 메모리 손상 취약성

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   동적 DPI 환경의 Office 추가 기능에서 확대/축소 및 배율 조정 시 발생하는 문제를 해결합니다.
-   Office 365 ProPlus가 현재 설치되어 있더라도 Office CSP(구성 서비스 공급자)의 CurrentStatus 노드가 빈 문자열을 반환하는 문제를 해결합니다.
-   .box 파일이 동일한 컴퓨터의 모든 Office 앱 버전에서 공유되므로 .box 파일 형식이 변경될 경우 같은 컴퓨터설치에 된 이전 Office 버전의 기능에 영향을 미치는 문제를 해결합니다.
-   공유 컴퓨터 정품 인증을 사용하는 특정 상황에서 앱 실행 중에 오류가 발생했다는 오류 메시지가 나타나 앱이 제대로 작동되지 못하고 사용자에게 복구를 실행할지 묻는 문제를 해결합니다.



## <a name="version-1708-october-10"></a>버전 1708:10 월 10 일
*버전 1708(빌드 8431.2107)*

### <a name="access-non-security-updates"></a>Access: 비보안 업데이트
-   쿼리에 Microsoft Dynamics와 연결된 테이블의 기본 키를 사용하는 조인이 있으면 해당 쿼리가 실행되지 않는 문제를 수정합니다.
-   Microsoft Dynamics 테이블에서 통화 값에 소수 자릿수가 표시되지 않는 문제를 수정합니다.

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   .XLL 파일을 열면 Excel 작업이 중단되는 문제를 해결합니다.
-   페이지 레이아웃 보기에서 머리글이나 바닥글을 추가한 후에 셀의 무늬 스타일이 올바르게 렌더링되지 않는 문제를 수정합니다.
-   피벗 테이블의 복사본을 다른 통합 문서에 붙이면 충돌이 일어나는 문제를 수정합니다.
-   바꾸기 명령을 선택해서 찾기 및 바꾸기 대화 상자를 열었을 때 대화 상자의 포커스가 찾기 탭이 아니라 바꾸기 탭에 있는 문제를 수정합니다.
-   SharePoint Server 2016 이전의 SharePoint Server에서 연 통합 문서의 작업 창을 열면 Excel이 충돌하는 문제를 수정합니다.
-   하나 이상의 XLL 추가 기능을 사용하는 경우 Excel이 빈 창을 열어 표시하는 문제를 수정합니다.
-   이미 닫힌 통합 문서에서 양식 단추를 사용하면 Excel이 충돌하는 문제를 수정합니다.
-   SheetBeforeRightClick 이벤트를 사용할 때 병합된 셀을 교차하도록 열을 삽입해도 병합된 셀이 확장되지 않는 문제를 수정합니다.

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): Microsoft Outlook 보안 기능 바이패스 취약성
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): Microsoft Outlook 정보 공개 취약성

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   진한 회색 테마를 사용하면 정책 팁의 "자세한 내용" 링크가 보이지 않는 문제를 수정합니다.
-   사용자가 새 계정을 설정하다가 계정 설정을 완료하지 않은 채로 창을 닫으면 Outlook이 충돌하는 문제를 수정합니다.
-   그룹이 공유하는 받은 편지함에서 읽은 상태와 읽지 않은 상태가 메시지의 옵션으로 표시되는 문제를 수정합니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   SharePoint Server 2016 이전의 SharePoint Server에서 프레젠테이션을 열면 PowerPoint가 충돌하는 문제를 수정합니다.

### <a name="word-security-updates"></a>Word: 보안 업데이트
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): Microsoft Office 메모리 손상 취약성

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   SharePoint Server 2016 이전의 SharePoint Server에서 연 문서의 작업 창을 열면 Word가 충돌하는 문제를 수정합니다.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Microsoft Office 원격 코드 실행 취약성

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   온라인 복구 진행 상황이 사용자에게 표시되지 않는 문제를 수정합니다.
-   파일 탐색기에 Office 파일 속성이 표시되지 않는 문제를 수정합니다.
-   두 번째 문서가 열려 있으면 리본에서 Office 추가 기능 단추가 사라지는 문제를 수정합니다.
-   이름에 더블바이트 문자가 있는 일부 VBA 모듈을 열 수 없는 문제를 수정합니다.



## <a name="version-1708-september-12"></a>버전 1708:9 월 12 일
*버전 1708(빌드 8431.2079)*

### <a name="access-feature-updates"></a>Access: 기능 업데이트
-   **레이블 이름 속성:** 양식에서 레이블을 컨트롤과 연결하여 접근성을 향상합니다.
-   **더 편리하게 새 항목 편집:** 빠른 바로 가기 키(Ctrl+E)를 사용하여 콤보 상자 또는 목록 상자에서 새 항목을 편집합니다.
-   **Dynamics 커넥터:** Microsoft Dynamics에 저장된 데이터를 가져오거나 해당 데이터에 연결합니다. [추가 정보](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Salesforce 커넥터:** Salesforce에 저장된 데이터를 가져오거나 해당 데이터에 연결합니다. [추가 정보](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel: 기능 업데이트
-   **향상된 “예제에서 열 추가” 기능:** 자세한 날짜/시간, 수학 및 인덱스 열 변환을 지원합니다.
-   **성능 개선:** Excel에서 여러 개의 시트가 있는 복잡한 통합 문서를 빠르게 열어 큰 범위의 수식을 확인하고, 여러 개의 행을 필터링하거나 신속하게 복사하여 붙여넣을 수 있습니다.
-   **온라인 사진 삽입:** 선택한 이미지 및 속성 정보에 대한 새 방문 페이지가 이미지를 사용하여 자동 삽입됩니다.
-   **Azure Data Lake Store 커넥터:** 이제 사용자가 Azure Data Lake Store에서 데이터를 가져올 수 있습니다.
-   **향상된 "예제에서 열 추가" 기능:** 제안, 더 많은 날짜/시간 작업 및 추가 변환을 지원합니다.
-   **데이터 탭**: 데이터 탭의 리본 단추가 다음 2개의 새 그룹으로 다시 배열되었습니다. 데이터 가져오기 및 변환, 쿼리 및 연결
-   **쿼리 공유**: 쿼리 정의를 ODC(Office 데이터베이스 연결) 파일로 내보낸 후 통합 문서 또는 다른 사용자와 공유합니다.
-   **데이터 로드:** 데이터 모델에 데이터를 저장하지 않고 쿼리의 데이터를 피벗 테이블 또는 피벗 차트로 직접 로드합니다.
-   **공유 파일 작업:** 파일의 오른쪽 위 구석에 있는 작업 단추를 선택하면 비즈니스용 OneDrive 또는 SharePoint에서 공유되는 파일을 공유하거나, 편집하거나, 이름을 바꾸거나, 복원하는 경우를 알 수 있습니다.
-   **안전한 링크:** 사용자가 링크를 클릭하면 Office 365 ATP(Advanced Threat Protection)에서 해당 링크의 악성 여부를 검사합니다. 링크가 악성으로 간주되면 사용자는 기존 대상 URL이 아닌 경고 페이지로 리디렉션됩니다. [추가 정보](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **향상된 데이터 가져오기 기능:** 다양한 소스에서 데이터를 쉽게 가져오고 형성할 수 있습니다. 쿼리 및 연결 왼쪽 창에서 통합 문서 쿼리 및 연결을 관리하고 ODC 파일을 통해 다른 사람과 쿼리를 공유합니다. [추가 정보](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **공유 파일의 변경 내용** 공유 통합 문서를 변경한 사람을 확인하고 이전 버전을 복원합니다. [추가 정보](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **펜 단추를 사용하여 올가미 선택:** 리본 메뉴를 방문하지 않고 올가미 선택 잉크에 지원되는 디지털 펜 단추를 사용합니다.

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Microsoft Office 메모리 손상 취약성
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Microsoft Office 메모리 손상 취약성
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): Microsoft Office 메모리 손상 취약성
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): Microsoft Office 메모리 손상 취약성

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   피벗 테이블을 확장 또는 축소할 때 피벗 테이블 머리글이 화면 밖으로 이동될 경우 Excel이 일시적으로 응답하지 않는 문제를 해결합니다.
-   탭으로 구분된 텍스트를 Word에서 복사하여 붙여넣으면 탭이 무시되어 텍스트가 열로 구문 분석되지 않는 문제를 해결합니다.
-   웹 페이지 게시 대화 상자를 열 때 Excel이 충돌하는 문제를 해결합니다.
-   SQL Server Analysis Services 서버의 데이터를 사용하는 경우 데이터 새로 고침이 성공하지 못하거나 Excel이 중단되고 Excel의 로캘과 SQL Server Analysis Services 서버의 로캘이 다른 문제를 수정합니다.
-   OneDrive 클라이언트와 동기화되는 문서에 변경 내용을 저장하려고 할 때 오류가 나타나는 문제를 수정합니다.
-   필터 영역에 필드가 있는 피벗 테이블이 있지만 다른 어느 곳에도 필드가 없을 때, 워크시트 아무 곳에서도 변경할 수 없는 문제를 수정합니다.

### <a name="outlook-feature-updates"></a>Outlook: 기능 업데이트
-   **접근성 개선:** 화면 판독기를 사용하는 경우 텍스트, 표, 목록 및 이미지를 더욱 쉽게 읽고 편집할 수 있습니다.
-   **새 계정 구성:** 필요한 수동 단계가 줄어든 새 마법사로 새 계정을 설정합니다.
-   **링크 첨부 대화:** 리본에서 파일 첨부를 사용하여 링크를 첨부할 때, 링크로 추가할지 첨부 파일로 추가할지를 선택할 수 있습니다. 이 대화를 매번 표시하지 않으려면 파일 \> 옵션 \> 일반으로 이동한 다음, “첨부 파일 옵션”에서 링크를 첨부할 방법을 지정하세요.
-   **온-프레미스 첨부 파일에 대한 지원:** 온-프레미스 SharePoint Server의 파일은 메시지 \> 파일 첨부 아래에 최신 파일로 표시되고 온-프레미스 비즈니스용 OneDrive 및 SharePoint 팀 사이트는 파일 첨부 \> 웹 위치 찾아보기 아래에 표시되며, 로컬 파일은 온-프레미스 비즈니스용 OneDrive 사이트에 업로드될 수 있습니다.
-   **그룹에 대한 비즈니스 분류:**  Confidential과 같이 테넌트 관리자가 정의한 비즈니스 분류 수준은 그룹을 만들거나 편집하는 경우 할당될 수 있으며 해당 분류는 그룹 헤더에 표시됩니다.
-   **Office 365의 그룹에 대한 게스트 액세스:** 그룹 대화, 파일, 일정 초대 및 그룹 전자 필기장에 대한 액세스 권한을 부여하 여 조직 외부의 사용자와 공동으로 작업합니다. [추가 정보](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **실행 가능한 메시지:** 개발자는 사용자가 외부 웹 사이트나 별도 앱으로 전환하지 않고도 Outlook에서 간편하고 빠르게 조치를 취할 수 있도록 메시지를 만들 수 있습니다. [추가 정보](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Microsoft Office Outlook 보안 기능 바이패스 취약성
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Microsoft Office Outlook 정보 노출 취약성
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Microsoft Office Outlook 메모리 손상 취약성

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   Outlook에서 IMAP 계정을 구성할 수 없는 문제를 수정합니다.
-   Outlook을 여는 경우 일시적으로 작동이 중지하는 문제를 수정합니다.

### <a name="powerpoint-feature-updates"></a>PowerPoint: 기능 업데이트
-   **온라인 사진 삽입:** 선택한 이미지 및 속성 정보에 대한 새 방문 페이지가 이미지를 사용하여 자동 삽입됩니다.
-   **동영상의 선택 캡션:** 동영상에 더 쉽게 액세스할 수 있도록 선택 캡션을 추가합니다. [추가 정보](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **기록 내레이션** 프레젠테이션을 기록할 때 내레이션하는 자신의 목소리를 포함합니다. 기록에는 애니메이션, 잉크, 오디오 및 비디오가 포함될 수 있습니다.
-   **공유 파일 작업:** 파일의 오른쪽 위 구석에 있는 작업 단추를 선택하면 비즈니스용 OneDrive 또는 SharePoint에서 공유되는 파일을 공유하거나, 편집하거나, 이름을 바꾸거나, 복원하는 경우를 알 수 있습니다.
-   **대체 텍스트 만들기:** 클라우드 기반 서비스는 프레젠테이션의 그림에 대한 대체 텍스트를 자동으로 생성합니다.
-   **안전한 링크:** 사용자가 링크를 클릭하면 Office 365 ATP(Advanced Threat Protection)에서 해당 링크의 악성 여부를 검사합니다. 링크가 악성으로 간주되면 사용자는 기존 대상 URL이 아닌 경고 페이지로 리디렉션됩니다. [추가 정보](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **향상된 디자이너 기능:** 동작 기반 목록에 대한 전문적인 디자인 아이디어를 권장합니다.
-   **공유 파일의 변경 내용:** 공유 프레젠테이션을 변경한 사람을 확인하고 이전 버전을 복원합니다. [추가 정보](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint: 보안 업데이트
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): PowerPoint 원격 코드 실행 취약성
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): PowerPoint 원격 코드 실행 취약성

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   글꼴에 연결된 최종 사용자 정의 문자(EUDC)가 표시되지 않는 문제를 수정합니다.

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트
-   Project Online에서 특정 파일을 열 때 Project가 충돌하는 문제를 해결합니다.
-   남은 작업을 설정할 때 실제 시작 날짜가 잘못 지워지는 문제를 해결합니다.
-   할당 실제 시작 날짜에 Project Web App의 상태를 통해 리소스에서 보고된 것과 다른 데이터가 표시될 수 있는 문제를 해결합니다.
-   작업 완료 날짜가 변경되면 실제 작업 일정이 재조정될 수 있는 문제를 해결합니다.
-   비용 필드를 복사하여 붙여넣으면 반올림 문제로 인해 붙여넣은 값과 복사한 값이 정확히 일치하지 않을 수 있는 문제를 해결합니다.
-   하나의 기준에서 다른 기준으로 저장할 때 예산 리소스에 대한 시간대별 데이터가 복사되지 않는 문제를 해결합니다.
-   상태 필드가 때때로 요약 작업을 정확하게 계산하지 않는 문제를 해결합니다.
-   로컬 리소스를 대체하고 보호된 작업을 사용할 때 실제 작업이 Enterprise 리소스로 잘못 전송되는 문제를 수정합니다.
-   테이블 첫 번째 열이 작업 이름이고 잠겨 있는 경우 작업을 클릭하면 Project가 중지하는 문제를 수정합니다.
-   작업 배정 현황 보기를 통해 동일한 작업에 동일한 리소스를 여러 번 지정할 수 있는 문제를 수정합니다.
-   XML 파일을 열 때 번호 사용자 정의 필드의 값이 손실될 수 있는 문제를 수정합니다.
-   최상위 수준의 작업 들여쓰기가 Project에서 SharePoint 작업 목록으로 올바르게 동기화되지 않는 문제를 수정합니다.
-   Excel 통합 문서에서 작업, 리소스 또는 할당 정보를 가져오는 경우 작업 필드의 값이 무시될 수 있는 문제를 수정합니다.
-   프로젝트를 XML 파일 형식으로 저장하면 시간대별 기본값이 초기값과 일치하지 않는 문제를 해결합니다.
-   프로젝트 클라이언트가 실제로는 프로젝트를 확인하지 않았으나 이를 확인한 것으로 간주하여 열지 않는 문제를 해결합니다.
-   대기 시간이 긴 파일 서버에서 프로젝트 파일을 더 빨리 열 수 있도록 문제를 해결합니다.

### <a name="skype-for-business-security-updates"></a>비즈니스용 Skype: 보안 업데이트
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): Windows GDI+ 정보 공개 취약성
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): 그래픽 구성 요소 정보 노출 취약성
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): Microsoft 그래픽 구성 요소 원격 코드 실행 문제

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
-   특정 포트가 차단되거나 IP가 허용 목록에 없는 경우 사용자가 모임에 참가할 수 없는 이유를 설명하는 대화 상자를 추가합니다.
-   IM 대화 탭을 클릭하면 영구 대화방의 읽지 않은 메시지가 읽음으로 표시되는 문제를 수정합니다.
-   들어오는 IM 알림이 몇 초 동안 지연되는 문제를 수정합니다.
-   Exchange와의 동기화를 사용할 수 없는 경우 AD 연락처가 연락처 이름이 아닌 전화번호로 표시되는 문제를 수정합니다.
-   페더레이션을 사용할 수 없고 모임 이끌이가 명시적으로 익명 참가를 차단하지 않은 경우 익명 참가 사용자가 참가하지 못하는 문제를 수정합니다.
-   제한을 초과하는 모임에 대해 모임 이끌이에게 초대 대상자의 수가 잘못 표시되는 문제를 수정합니다.
-   인바운드 PSTN 통화에서 알림에 전화번호가 표시되지 않는 문제를 수정합니다.
-   연락처 목록 그룹 이름을 바꾸는 도중 Delete 키를 사용하면 전체 그룹이 삭제되는 문제를 수정합니다.
-   공유가 중지되기 전에 IM 대화의 공유 알림이 해제되는 문제를 수정합니다.
-   영어가 아닌 일부 언어의 경우 로그인 화면이 표시되지 않는 문제를 해결합니다.
-   채팅 및 채팅 기록에서 영어가 아닌 문자는 왜곡되어 표시되는 문제를 해결합니다.
-   사용자 이름을 알 수 없는 경우 조직 자동 전화 교환에서 처리하는 수신 전화의 발신자 전화 번호를 표시합니다.
-   "모두(제한 없음)"의 제한을 허용하는 인밴드 설정을 "바로 입장할 사람 지정"의 옵션으로 추가합니다.
-   VDIv2에서 P2P 비디오 통화를 위해 셀프 비디오를 켜고 끄는 기능을 추가합니다.
-   통화 드롭다운 메뉴에서 연락처에 중복된 번호가 표시되는 문제를 수정합니다.
-   비즈니스용 Skype와 비즈니스용 Skype Basic 간을 이동하는 사용자의 대리인이 삭제되는 문제를 수정합니다.
-   오프라인으로 표시 사용 및 사용자 정의 상태 URL 클라이언트 정책을 사용할 때 오프라인으로 표시가 나타나지 않는 문제를 수정합니다.
-   모임 참가 단추를 확장하여 일부 지역화된 언어가 잘리는 문제를 수정합니다.
-   채팅에서 중요도가 높은 메시지를 더욱 강조합니다.
-   Office 및 비즈니스용 Skype 파일 확장 형식을 허용 가능한 파일 전송 차단 목록에 추가합니다.
-   모임 바닥글 텍스트에 대한 Outlook 모임 초대의 사용자 지정 수정 항목을 영어가 아닌 언어로 설정합니다.
-   보낸 사람 이름이 여러 사용자의 대화에서 전환될 수 있는 문제를 해결합니다.
-   모임에 참가할 때까지 빈 대화 창이 나타나지 않는 문제를 해결합니다.
-   직함 필드가 비어 있으면 검색 결과에 연락처 카드의 부서 필드 정보가 비는 문제를 해결합니다.
-   방화벽 규칙으로 인해 온-프레미스에서 온라인으로 마이그레이션한 사용자에게 발생하는 로그인 오류를 해결합니다.
-   새 DWORD 레지스트리 키를 추가하여 사용자가 LyncAutoD를 수행하는 외부 네트워크의 클라이언트에 로그인할 때 클라이언트가 OAuthUsed 레지스트리 키를 False로 재설정하는 문제를 수정합니다. 이 문제를 수정하려면 HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>에서 EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket의 값을 1로 설정합니다.

### <a name="visio-feature-updates"></a>Visio: 기능 업데이트
-   **Excel 데이터에서 다이어그램 만들기:** 새 데이터 시각화 도우미 템플릿을 사용하여 Excel 데이터에서 기본 순서도 또는 부서간 업무 흐름도를 자동으로 만듭니다. [추가 정보](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **안전한 링크:** 사용자가 링크를 클릭하면 Office 365 ATP(Advanced Threat Protection)에서 해당 링크의 악성 여부를 검사합니다. 링크가 악성으로 간주되면 사용자는 기존 대상 URL이 아닌 경고 페이지로 리디렉션됩니다. [추가 정보](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio: 비보안 업데이트
-   파일 아이콘이나 파일 이름을 두 번 클릭하여 Visio 파일을 열 때 COM 추가 기능에서 이벤트가 열린 문서를 받지 못하는 문제를 수정합니다.

### <a name="word-feature-updates"></a>Word: 기능 업데이트
-   **온라인 사진 삽입:** 선택한 이미지 및 속성 정보에 대한 새 방문 페이지가 이미지를 사용하여 자동 삽입됩니다.
-   **대체 텍스트 만들기:** 클라우드 기반 서비스는 문서의 그림에 대한 대체 텍스트를 자동으로 생성합니다.
-   **공유 파일 작업:** 파일의 오른쪽 위 구석에 있는 작업 단추를 선택하면 비즈니스용 OneDrive 또는 SharePoint에서 공유되는 파일을 공유하거나, 편집하거나, 이름을 바꾸거나, 복원하는 경우를 알 수 있습니다.
-   **안전한 링크:** 사용자가 링크를 클릭하면 Office 365 ATP(Advanced Threat Protection)에서 해당 링크의 악성 여부를 검사합니다. 링크가 악성으로 간주되면 사용자는 기존 대상 URL이 아닌 경고 페이지로 리디렉션됩니다. [추가 정보](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **공유 파일의 변경 내용:** 공유 문서를 변경한 사람을 확인하고 이전 버전을 복원합니다. [추가 정보](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   Grammarly 추가 기능을 로드하는 도중 Word가 갑자기 닫히는 문제를 수정합니다.
-   클라우드 기반 파일을 복구하는 도중 특정 조건에서 Word가 중지하는 문제를 수정합니다.
-   그리기 캔버스 내의 셰이프를 회전할 수 없는 문제를 수정합니다.
-   한국어를 입력할 때 자음과 모음 정확하지 않게 구분되는 문제를 수정합니다.
-   문서를 PDF로 저장하면 문서가 버전 1.7 PDF로 저장됩니다.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): Microsoft Office 메모리 손상 취약성
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): Microsoft Office 메모리 손상 취약성

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   새 소식 대화 상자가 나타나지 않는 문제를 해결합니다.
-   그리기 탭을 클릭하면 일부 사용자의 응용 프로그램이 중단되는 문제를 수정합니다.
-   도구 설명이 있는 일반 컨트롤을 가리킬 때 응용프로그램이 중단되는 문제를 수정합니다.
-   일반 컨트롤을 사용하는 경우 라이선스 오류 메시지가 나타나는 문제를 수정합니다.
-   일부 프로그램 파일이 서명되는 방식으로 인해 바이러스 백신 프로그램이 이러한 파일에 플래그를 지정하는 문제와 WIP(Windows Information Protection)의 데이터 보호 및 액세스에 발생하는 문제를 수정합니다.
-   Office 64비트 버전에서 작업하는 사용자가 mscomctl.ocx 컨트롤이 포함된 매크로 파일을 열 수 있도록 하는 지원을 추가합니다.
-   mscomctl.ocx에서 사용되는 컨트롤의 가용성을 개선합니다.
-   리본 또는 빠른 실행 도구 모음 사용자 지정 대화 상자에서 명령이 누락되는 문제를 수정합니다.



## <a name="version-1705-august-8"></a>버전 1705:8 월 8 일
*버전 1705(빌드 8201.2171)*

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   메시지 목록을 통해 이동하는 경우 스크롤바를 끌 때 발생하는 문제를 해결합니다.

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   일부 프로그램 파일이 서명되는 방식으로 인해 바이러스 백신 프로그램이 이러한 파일에 플래그를 지정하는 문제와 WIP(Windows Information Protection)의 데이터 보호 및 액세스에 발생하는 문제를 수정합니다.
-   새 소식 대화 상자가 나타나지 않는 문제를 해결합니다.



## <a name="version-1705-july-27"></a>버전 1705:7 월 27 일
*버전 1705(빌드 8201.2158)*

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   OneDrive 클라이언트와 동기화되는 문서에 변경 내용을 저장하려고 할 때 오류가 나타나는 문제를 수정합니다.
-   워크시트 데이터를 데이터 모델에 추가할 때 Excel이 중지되고 대비 테마가 검정색으로 설정되는 문제를 수정합니다.

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Microsoft Office Outlook 보안 기능 바이패스 취약성
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Microsoft Office Outlook 정보 노출 취약성
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Microsoft Office Outlook 메모리 손상 취약성

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   다른 사용자가 레이아웃을 변경한 후 모양을 추가하면 병합 오류가 발생하는 문제를 수정합니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   한국어를 입력할 때 자음과 모음 정확하지 않게 구분되는 문제를 수정합니다.
-   받는 사람 주소가 봉투 왼쪽 가장자리에 너무 가깝게 인쇄되는 문제를 수정합니다.



## <a name="version-1705-july-13"></a>버전 1705:7 월 13 일
*버전 1705(빌드 8201.2136)*

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Microsoft Office 메모리 손상 취약성
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Microsoft Office 메모리 손상 취약성

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   통합 문서에 외부 링크가 포함되면 Excel이 중지되는 문제를 수정합니다.
-   Excel에서 Word로 셀을 붙여 넣은 경우, "0값이 있는 셀에 0 표시" 설정을 선택하지 않아도 셀에 0이 표시되는 문제를 수정합니다.

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트
-   차트/테이블에 대해 선택한 값이 차트/테이블 창에 표시되지 않는 문제를 수정합니다.

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
-   모임에 참가할 때 대화 창이 나타나지 않고 오디오 장치 조인 대화 상자가 사용자에게 표시되는 문제를 수정합니다.
-   Outlook에서 모임 링크가 내부 URI를 항상 제대로 전달하지 않는 문제를 수정합니다.
-   모임 조인 단추를 확장하여 일부 지역화된 언어가 잘리는 문제를 수정합니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   특정 작업을 수행한 후에 테이블이 제대로 표시되지 않는 문제를 수정합니다.
-   인용에 대한 다중 편집이 간혹 연속 개별 작업이 아닌 단일 실행 취소 작업으로 표시되는 문제를 수정합니다.
-   특정 작업을 수행한 후에 실행 취소를 사용할 수 없는 문제를 수정합니다.
-   특정 실행 취소 작업을 수행한 후에 가능한 데이터 손실을 방지하기 위해 문제를 수정합니다.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Microsoft Office 원격 코드 실행 취약성

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   Configuration Manager를 사용 하는 경우 Office 2013에서 Office 2016로의 무인 업그레이드에 실패 하는 문제를 해결 합니다.
-   회사 카탈로그를 통해 스토어에서 배포된 레거시 추가 기능이 로드되지 않는 문제를 수정합니다.



## <a name="version-1705-june-13"></a>버전 1705:6 월 13 일
*버전 1705(빌드 8201.2102)*

### <a name="access-feature-updates"></a>Access: 기능 업데이트
-   **새로운 기능 대화 상자:** 새 기능으로 Access를 업데이트한 후에 Access를 열 때 나타나는 새로운 Access 기능을 강조 표시하는 대화 상자입니다. 파일 \> 계정 \> 새로운 기능으로 이동하여 이 대화 상자를 사용할 수도 있습니다.
-   **큰 수(bigint) 지원:** Access 테이블에서 많은 큰 수 데이터 형식을 사용하여 큰 숫자를 계산할 수 있고 SQL Server 내의 bigint와 같이 동일한 데이터 형식을 사용하는 외부 데이터베이스에서 가져오거나 연결할 수 있습니다. [추가 정보](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel: 기능 업데이트
-   **WIP (Windows Information Protection) 지원:**    Excel은 이제 인식 된 앱 이며 구성 된 정책에 따라 보호할 내용을 올바르게 결정 하면서 회사 및 개인 데이터를 구분할 수 있습니다.   [추가 정보](https://aka.ms/wiptechnet)
-   **향상된 가져오기 및 변환 기능:** 쿼리 편집기에서 샘플 값을 제공하여 새 열을 만듭니다. 입력하는 동안 Excel은 필수 변형을 검색하고 새 열의 미리 보기를 표시합니다.
-   **최근 링크 삽입:** 최근 클라우드 기반 파일이나 웹 사이트에 간단하게 하이퍼링크를 연결하고 화면 읽기 프로그램을 사용하는 사람들에게 의미 있는 화면 이름을 만들어줄 수 있습니다. [추가 정보](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **기본 피벗 테이블 레이아웃 개인 설정** 원하는 대로 피벗 테이블을 설정하고 새 피벗 테이블을 만들 때마다 해당 레이아웃으로 시작할 수 있습니다. [추가 정보](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **향상된 가져오기 및 변환 기능:** 사용자는 예제로 새 열을 만들고 테이블 열을 행으로 분할할 수 있습니다. 더 쉽게 매개 변수를 SAP HANA로 지정하고 데이터를 그룹화할 수 있습니다.
-   **추가 기능의 중앙 집중식 배포**: 관리자는 Office 365 관리 센터에서 사용자 또는 그룹에게 추가 기능을 배포하고 업데이트할 수 있습니다. [추가 정보](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **빠른 실행 도구 모음 사용자 지정:** 아래 첨자 및 아래 첨자 아이콘을 빠른 실행 도구 모음에 추가할 수 있습니다.
-   **향상된 가져오기 및 변환 기능:** 쿼리 편집기를 사용하여 열을 분할할 때 구분 기호 문자를 자동으로 감지하고, 이진 조합에서 사용할 샘플 파일을 선택하고, DB2 커넥터를 사용할 때 연결할 패키지 컬렉션을 지정할 수 있습니다.
-   **두바이 글꼴:** 아랍어 스크립트를 사용하는 주요 언어와 서유럽 언어를 모두 지원하는 글꼴 집합입니다. [추가 정보](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **배경 제거:** 자유 형식 그리기 도구를 사용하여 배경 그림을 제거합니다.
-   **향상된 가져오기 및 변환 기능:** ODCB 및 OLEDB 커넥터로 찾기 대화 상자에서 "관련 테이블 선택"을 사용하여, 폴더 데이터 미리 보기 대화 상자에서 바로 여러 파일을 결합하고, 쿼리 편집기 내의 새 상황에 맞는 메뉴 옵션을 사용하여 기존 쿼리의 새 단계를 삽입합니다.
-   **펜을 사용하여 개체를 선택한 후 변경:** 디지털 펜의 개체 핸들을 사용하여 크기 조정, 회전, 이동 등을 수행할 수 있습니다.
-   **지도 차트:** 값을 비교하고 지역별 범주를 표시합니다. [추가 정보](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **SVG 이미지:** 통합 문서에 SVG(확장 가능한 벡터 그래픽)를 삽입하고 편집합니다. [추가 정보](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **아이콘 삽입:**   삽입 \> 그림 \> 아이콘으로 이동 하 여 SVG (확장 가능한 벡터 그래픽) 파일의 표준 라이브러리에 있는 아이콘을 사용 합니다. [추가 정보](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **최근 폴더에 저장:** 파일 \> 다른 이름으로 저장으로 이동한 후 최근에 사용한 항목 탭을 사용하여 최근에 사용한 폴더에 통합 문서를 저장합니다.
-   **향상된 내게 필요한 옵션:** 키보드, 내레이터 및 기타 보조 기술을 사용하여 통합 문서를 읽고 편집할 수 있도록 지원이 향상되었습니다. [추가 정보](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   Microsoft 보안 공지 [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office용 보안 업데이트(3217868)

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   Excel 2010 또는 이전 버전에서 만든 통합 문서에 프로그래밍 방법으로 적용하면 Excel에서 시트 보호 암호를 설정하지 않는 문제를 해결합니다.
-   그룹화된 워크시트에서 병합하고 가운데 맞춤이 작동하지 않는 문제를 수정합니다.
-   TEXTJOIN, CONCAT, IFS, MAXIFS 및 MINIFS와 같이 Office 2016 출시 이후 도입된 새로운 기능이 누락된 문제를 해결합니다.
-   사용자가 셀 수준 사용 권한을 적용하면 Excel이 충돌하는 문제를 해결합니다.
-   비즈니스용 OneDrive에 대용량 파일을 저장하면 파일이 잠기고 사용자가 해당 파일을 닫고 Excel을 다시 열기 전까지 편집할 수 없는 문제를 해결합니다.
-   .xls 통합 문서를 열면 새 창이 회색으로 표시되는 문제를 해결합니다.
-   하이퍼링크를 삽입하면 Excel이 중지할 수도 있는 문제를 해결합니다.
-   XML 맵을 추가하면 Excel이 실패할 수도 있는 문제를 해결합니다.
-   추가 기능이 업그레이드된 후 또는 Office 스토어에서 추가 기능을 제거하고 다시 다운로드한 후에 추가 기능 명령 단추가 작동하지 않는 문제를 해결합니다.
-   VBA를 통해 DLL 시트를 조작하면 Excel이 중지할 수도 있는 문제를 해결합니다.
-   차트 시트에서 컨트롤 콤보 상자를 선택 하는 경우 Excel이 작동 중지하는 문제를 해결합니다.

### <a name="onenote-feature-updates"></a>OneNote: 기능 업데이트
-   **WIP(Windows Information Protection) 지원:** OneNote는 이제 인식된 앱이며 구성된 정책에 따라 보호할 대상을 정확하게 결정하면서 회사 및 개인 데이터를 구분할 수 있습니다. [추가 정보](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote: 비보안 업데이트
-   OneNote 캔버스가 뷰에 많은 단락이 있을 때 콘텐츠를 숨기거나 업데이트 하는 문제를 해결합니다.

### <a name="outlook-feature-updates"></a>Outlook: 기능 업데이트
-   **WIP (Windows Information Protection) 지원:**    Outlook은 이제 인식 된 앱 이며, 구성 된 정책에 따라 보호할 사항을 정확히 결정 하면서 회사 및 개인 데이터를 구분할 수 있습니다.   [추가 정보](https://aka.ms/wiptechnet)
-   **최근 링크 삽입:** 최근 클라우드 기반 파일이나 웹 사이트에 하이퍼링크를 연결하고 화면 읽기 프로그램을 사용하는 사람들에게 의미 있는 화면 이름을 만들어줄 수 있습니다. [추가 정보](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **두바이 글꼴:** 아랍어 스크립트를 사용하는 주요 언어와 서유럽 언어를 모두 지원하는 글꼴 집합입니다. [추가 정보](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **배경 제거:** 자유 형식 그리기 도구를 사용하여 배경 그림을 제거합니다.
-   **공유 파일에 대한 액세스를 확인하십시오.** Outlook은 받는 사람이 첨부된 OneDrive나 SharePoint 파일에 액세스 하지 못하는 경우 사용자에게 미리 알려주며 해당 문제를 해결할 방안을 제안합니다.
-   **첨부 파일에 대한 사용 권한 설정:** OneDrive 또는 SharePoint 첨부 파일에 대해 사용자는 조직 내부 혹은 외부의 받는 사람이 첨부 파일을 읽었거나 첨부 파일에 대한 권한을 편집할지 여부를 설정할 수 있습니다.
-   **고정 가능 작업창:** 사서함에서 메시지 간에 전환하는 동안 추가 기능 작업창을 열어 둡니다. [추가 정보](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **SVG 이미지:** 전자 메일에 SVG(확장 가능한 벡터 그래픽)를 삽입하고 편집합니다. [추가 정보](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **아이콘 삽입:**   삽입 \> 그림 \> 아이콘으로 이동 하 여 SVG (확장 가능한 벡터 그래픽) 파일의 표준 라이브러리에 있는 아이콘을 사용 합니다.   [추가 정보](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Microsoft Outlook 원격 코드 실행 취약성
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): Microsoft Office 보안 기능 바이패스 취약성
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506): Microsoft Office 원격 코드 실행
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507): Microsoft Office 메모리 손상 취약성
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508): Microsoft Office 보안 기능 바이패스 취약성

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   컴퓨터의 메모리가 부족한 경우 Outlook 탐색 창의 렌더링이 멈추는 문제를 해결합니다.
-   첨부 파일 너비가 파일 이름 및 사용 권한 정보에 맞게 시각적으로 확장됩니다.
-   사용자가 PST 파일을 검색할 수 없는 문제를 해결합니다.
-   사용자가 "새 Outlook 데이터 파일" 대화 상자의 새 "Microsoft Exchange" 저장 유형을 확인한 후 이 새 데이터 유형을 선택하면 사용자 프로필이 사용할 수 없는 상태가 되는 문제를 해결합니다.
-   높은 DPI를 사용하는 컴퓨터에서 전송된 메시지에 포함된 이미지가 블랙아웃되는 문제를 해결합니다.

### <a name="powerpoint-feature-updates"></a>PowerPoint: 기능 업데이트
-   **WIP (Windows Information Protection) 지원:**    PowerPoint는 이제 인식 된 앱 이며 구성 된 정책에 따라 보호할 사항을 정확히 결정 하면서 회사 및 개인 데이터를 구분할 수 있습니다.   [추가 정보](https://aka.ms/wiptechnet)
-   **최근 링크 삽입:** 최근 클라우드 기반 파일이나 웹 사이트에 하이퍼링크를 연결하고 화면 읽기 프로그램을 사용하는 사람들에게 의미 있는 화면 이름을 만들어줄 수 있습니다. [추가 정보](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **추가 기능의 중앙 집중식 배포**: 관리자는 Office 365 관리 센터에서 사용자 또는 그룹에게 추가 기능을 배포하고 업데이트할 수 있습니다. [추가 정보](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **두바이 글꼴:** 아랍어 스크립트를 사용하는 주요 언어와 서유럽 언어를 모두 지원하는 글꼴 집합입니다. [추가 정보](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **배경 제거:** 자유 형식 그리기 도구를 사용하여 배경 그림을 제거합니다.
-   **SVG 이미지:** 프레젠테이션에 SVG(확장 가능한 벡터 그래픽)를 삽입하고 편집합니다. [추가 정보](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **아이콘 삽입:**   삽입 \> 그림 \> 아이콘으로 이동 하 여 SVG (확장 가능한 벡터 그래픽) 파일의 표준 라이브러리에 있는 아이콘을 사용 합니다. [추가 정보](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **공동 작성 시 실시간 입력:** 다른 사용자가 프레젠테이션에서 작업 중인 위치를 확인 하 고 입력 시 변경 내용을 확인 합니다. [추가 정보](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **최근 폴더에 저장:** 파일 \> 다른 이름으로 저장으로 이동한 후 최근에 사용한 항목 탭을 사용하여 최근에 사용한 폴더에 프레젠테이션을 저장합니다.
-   **정확한 잉크 개체 만들기:** 세그먼트 지우개를 끌어 가장 가까운 선까지 불필요한 잉크를 제거합니다.
-   **펜으로 개체를 선택한 후 조작:** 디지털 펜의 핸들을 사용하여 개체를 이동, 크기 조정 또는 회전하거나, 올가미 선택 잉크에 지원되는 펜 단추를 사용합니다.
-   **향상된 내게 필요한 옵션:** 키보드, 내레이터 및 기타 보조 기술을 사용하여 프레젠테이션을 읽고 편집할 수 있도록 지원이 향상되었습니다. [추가 정보](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   사용자가 mfplat.dll 파일이 컴퓨터에 설치되어 있지 않은 상태에서 디자인 아이디어 창을 열었을 때 PowerPoint 작동이 중단되는 문제를 해결합니다.
-   추가 기능이 업그레이드된 후 또는 Office 스토어에서 추가 기능을 제거하고 다시 다운로드한 후에 추가 기능 명령 단추가 작동하지 않는 문제를 해결합니다.

### <a name="project-feature-updates"></a>Project: 기능 업데이트
-   **선행 작업 설정에 대한 빠른 드롭다운:** Gantt 차트 드롭다운을 사용해서 작업에 대한 링크를 연결하려는 선행 작업이나 후속 작업을 선택합니다.
-   **작업 요약 이름:**   작업의 요약 작업 이름을 보여주는 읽기 전용 작업 필드입니다.  

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트
-   Project Online에서 각 EPT(Enterprise 프로젝트 템플릿)가 프로젝트 사이트에 대한 자체 URL을 갖게 되므로 사이트에 대한 올바른 위치를 표시하도록 프로젝트 사이트 만들기 대화 상자를 수정합니다.
-   저장 프롬프트 전에 VBA BeforeClose 이벤트가 발생하며, 프로그래밍 방식으로 저장 프롬프트에 대한 사용자의 응답을 확인할 방법이 없는 문제를 수정합니다.
-   실제 완료율이 프로젝트 상황 보고 날짜 이후에 시작되는 작업에 대해 제대로 롤업되지 않는 문제를 수정합니다.
-   비용 및 작업 자원이 동일한 작업에 할당될 때 작업의 상태 관리자를 변경할 수 없는 문제를 수정합니다.
-   특정 프로젝트의 경우 전체 프로젝트를 평준화하면 무한 루프가 발생할 수 있는 문제를 수정합니다.
-   특정 스페인어 국가별 설정을 사용하는 경우 작업 시작 날짜 및 완료 날짜가 SharePoint 작업 목록과 제대로 동기화되지 않는 문제를 수정합니다.
-   Project 클라이언트에서 상태 승인 프로세스를 시작할 경우 프로젝트가 절대 완료되지 않고 사용 불가능 상태가 되는 문제를 수정합니다.
-   중국어 및 영어 단어를 사용할 경우 인쇄 미리 보기 중에 작업 이름이 제대로 배치되지 못하는 문제를 수정합니다.
-   PowerPoint에 시간 표시줄을 개별 셰이프로 복사할 수 없는 문제를 해결합니다.
-   "프로젝트 연결" 대화 상자가 예기치 않게 "파일 찾을 수 없습니다."로 표시되는 문제를 해결합니다.
-   리소스를 0의 최대 단위로 할당할 때 일치하지 않는 결과가 나오는 문제를 해결합니다.
-   과제에 리딩 분할 하는 선행 작업을 무시하고 작업의 시작일을 삭제할 경우 작업 시작일이 ‘가능한 빠른 시일’로 리셋 되는 문제를 해결합니다.
-   최근 메뉴를 통해 SharePoint에서 파일을 여는 경우 세팅이 “문서가 편집 될수 있기 전에 체크 아웃을 요구합니까?”가 활성화 되어 있음에도 프로젝트가 자동으로 체크 아웃되는 문제를 해결합니다.
-   프로젝트 프로필 응용 프로그램에 직접 이동하는 경우 프로젝트의 작동이 중단되는 문제를 해결합니다.
-   프로젝트 2013에서 업그레이드 한 유저들 중 수동 일정 작업이 제대로 업데이트 되지 않은 문제를 해결합니다.
-   SharePoint 작업 목록에서 프로젝트를 열 경우, 프로젝트가 작업 동기화 프로세스를 시작하면서 작업이 중단되는 문제를 해결합니다.
-   빌드 팀에게 갈 때 프로젝트 작동이 때때로 중단 되는 문제를 해결합니다.
-   프로젝트를 저장할 때 기준 정보가 손실되는 문제를 해결합니다.
-   큰 프로젝트 계획에 대한 인쇄물을 읽기 어려운 문제를 해결합니다.
-   Project Web App에서 편집된 프로젝트가 수식 필드에 올바른 값이 표시가 안 되는 문제를 해결합니다.
-   자원 Enterprise의 사용자 지정 필드 정보가 프로젝트 계획에 제대로 저장이 안 되는 문제를 해결합니다.
-   작업의 작업 완료율 정보의 업데이트가 작업의 완료율 정보를 업데이트하는 문제를 해결합니다.
-   프로젝트가 저장되고 프로젝트 소유권이 변경되는 문제를 해결합니다.
-   요약 작업에 대한 CPI가 잘못 계산된 문제를 해결합니다.
-   복사 및 붙여넣기 작업이 기준 데이터로 전송되고 사용자가 보호 기준 데이터 저장의 권한이 없음에도 저장되는 문제를 해결합니다.
-   작업과 과제에 대한 잘못된 날짜 정보가 있는 Excel 결과 데이터를 가져오는 문제를 해결합니다.
-   보고서를 열고 나서 닫을 때 프로젝트 작동이 중단되는 문제를 해결합니다.
-   유효성 검사 설정이 사용자 지정 목록에 포함된 프로젝트를 저장할 때 프로젝트가 멈추는 문제를 해결합니다.
-   필터 정의에 테스트 열에서 ‘\>’ 문자를 입력할 때 대화 상자에서 ‘보다 큽니다'로 해석하지 못하는 문제를 해결합니다.
-   ‘기본 계획’에 관한 진행선의 표시 문제를 해결합니다.
-   필터를 사용자 지정할 때 드롭다운 목록에 필드 이름이 나타나지 않는 문제를 해결합니다.
-   막대 스타일 대화 상자에서 막대 스타일 미리 보기 안 나타나는 문제를 해결합니다.

### <a name="publisher-non-security-updates"></a>Publisher: 비보안 업데이트
-   게시자가 CMYK TIF 이미지를 표시하지 않는 문제를 해결합니다.

### <a name="skype-for-business-feature-updates"></a>Skype for Business: 기능 업데이트
-   **링크 삽입:** IM 및 그룹 채팅에 링크를 추가하고, 전체 URL 대신 링크를 적절히 설명하는 텍스트를 제공합니다.
-   **Screen sharing notification:** A notification displays in the conversation window when you’re sharing a screen in an IM conversation or when screen sharing continues after you leave a meeting. The notification reminds you that you are still sharing your screen and makes it easy to stop sharing by using the “Stop Sharing” button.
-   **WIP(Windows Information Protection) 지원:** 비즈니스용 Skype는 이제 WIP 작업 전용 앱으로 지원됩니다.허용된 앱 목록에 Skype를 추가하면 Skype에서 개인 데이터를 처리하지 않음을 Windows에 나타냅니다.Windows가 비즈니스용 Skype 대신 데이터를 보호 합니다.   [추가 정보](https://aka.ms/wiptechnet)
-   **암호 재설정 옵션:** 한 번 이상 로그인하지 못하면 로그인 창에 재설정 단추 링크가 나타납니다.

### <a name="skype-for-business-security-updates"></a>비즈니스용 Skype: 보안 업데이트
-   Microsoft 보안 공지 [MS17-013](https://technet.microsoft.com/library/security/ms17-013): Microsoft 그래픽 구성 요소용 보안 업데이트(4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283): Windows Uniscribe 원격 코드 실행 취약성
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550): 비즈니스용 Skype 원격 코드 실행 취약성

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
-   Change message for attempted calls to users with audio disabled by policy from "Cannot complete the call" to "Cannot call because an IT administrator has restricted audio. Try using instant messaging or email instead and ask to check with their IT administrator."
-   비즈니스용 Skype Online의 PSTN 회의 지원 사용자에 대한 모임 초대에 "전화 접속 PIN을 잊으셨습니까?" 하이퍼링크를 추가합니다.
-   비즈니스용 Skype Online에서 팀 회의에 참가할 수 있도록 합니다.
-   기본 확성기 세션 볼륨을 40%에서 75%로 변경합니다.
-   탭 목록 크기를 더 작은 최소 너비로 조정할 수 있도록 합니다.
-   탭 순서와 일치하도록 바로 가기 키를 업데이트합니다.
-   모바일 장치에서 전송할 때 히브리어 텍스트의 잘못된 방향을 수정합니다.
-   데스크톱 프레젠테이션/제어권 제공 기능을 위해 화면 판독기에서 설명하는 정보의 문제를 수정합니다.
-   방 선택 목록에서 팔로우한 방뿐만 아니라 열어본 방도 표시합니다.
-   사용자 지정 RCC 앱을 사용하는 동안 VoIP 기능을 사용하지 않도록 설정하는 기능을 추가합니다.
-   오프라인 IM 기타 정보를 "비즈니스용 Skype 모바일 앱을 사용해보세요"로 변경합니다.
-   자동으로 수락된 대화의 대화 창이 최소화되지 않고 일반 창으로 열리며, 예기치 않게 다른 창에서 초점을 벗어나는 문제를 해결합니다.
-   Skype 모임 옵션 대화 상자에서 화면 읽기 프로그램을 사용할 때 발생하는 문제를 해결합니다.
-   초대장의 첫 번째 메시지가 부재 중 대화 전자 메일에 표시되지 않는 문제를 해결합니다.
-   새 Skype 모임 단추를 사용하여 Outlook에서 모임 초대를 만들 때 중복 전화 접속 번호가 표시되는 문제를 해결합니다.
-   스크롤바가 나타나면 Ctrl+A를 사용해서 모두 선택해도 IM 기록의 모든 대화가 선택되지 않는 문제를 해결합니다.
-   Export-CsArchivingData cmdlet을 사용하면 출력 텍스트가 정확한 형식이 아닐 수도 있는 문제를 해결합니다.
-   3명 이상의 참가자와 모임 시작을 사용하면 모임 이끌이가 원격 참가자의 비디오를 볼 수 없는 문제를 해결합니다.
-   사용자가 참가자 목록에서 다른 사용자의 이름을 마우스 오른쪽 단추로 클릭할 때 모임 명단의 첫 번째 줄이 비어있는 문제를 해결합니다.
-   회사 내부 및 외부 네트워크를 전환할 때 사용자가 로그인할 수 없는 문제를 해결합니다.
-   문의 후 전송에서 IM에서 오디오로 에스컬레이션할 때 채팅 영역이 닫히지 않는 문제를 해결합니다.
-   두 끝점의 동시 신호 울림을 사용하는 경우 알림에서 이름이 잘리는 문제를 해결합니다.
-   파일 공유 알림에서 파일 이름이 잘리는 문제를 해결합니다.
-   통화로 돌아가기 및 전송 단추에 대한 도구 설명을 추가합니다.
-   문의 후 전송 창에서 보류되는 시간을 내레이터와 같은 화면 판독기에서 사용할 수 있도록 합니다.
-   IM 또는 통화 중에서 문의 후 전송에 대한 기본 설정을 선택할 수 있는 기능을 추가합니다.
-   연락처 전화 번호 목록을 보려면 ‘전송’ 단추를 마우스 오른쪽 단추로 클릭하여 컨설팅 전송 시 기능을 추가합니다.
-   사용자가 유효하지 않은 라이선스를 가지고 있거나 라이선스가 할당되지 않았다는 메시지를 확실하게 할 수 있도록 일반 오류 메시지를 개선합니다.
-   사용자가 연락처 상대와 다른 대화 상대와 대화를 시작할 때 모든 연락처 대화 상대가 대화창 타이틀에 표시되지 않는 문제를 해결합니다.
-   내레이터가 2번째 줄의 알림을 읽지 않는 문제를 해결합니다.
-   컨설팅된 번호 대신으로 VOIP로 호출이 전달되는 문제를 해결합니다.
-   사용자가 콘텐츠 창에서 정보를 탐색 할 때 내레이터가 잘못된 정보를 알려 주는 문제를 해결합니다.
-   화이트 보드에서 주석을 가리킬 때 작성자 및 수정자 이름이 나타나지 않는 문제를 해결합니다.

### <a name="visio-feature-updates"></a>Visio: 기능 업데이트
-   **타사 스텐실 찾기:** 선택한 콘텐츠 공급자가 제공한 타사 스텐실을 검색합니다.
-   **슬라이드 조각:** Visio 드로잉의 조각을 가져다 PowerPoint 슬라이드로 내보냅니다. [추가 정보](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word: 기능 업데이트
-   **WIP (Windows Information Protection) 지원:**    Word는 이제 인식 된 앱 이며 구성 된 정책에 따라 보호할 사항을 정확히 결정 하면서 회사 및 개인 데이터를 구분할 수 있습니다.   [추가 정보](https://aka.ms/wiptechnet)
-   **최근 링크 삽입:** 최근 클라우드 기반 파일이나 웹 사이트에 하이퍼링크를 연결하고 화면 읽기 프로그램을 사용하는 사람들에게 의미 있는 화면 이름을 만들어줄 수 있습니다. [추가 정보](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **추가 기능의 중앙 집중식 배포**: 관리자는 Office 365 관리 센터에서 사용자 또는 그룹에 추가 기능을 배포 하 고 업데이트할 수 있습니다.   [추가 정보](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **두바이 글꼴:** 아랍어 스크립트를 사용하는 주요 언어와 서유럽 언어를 모두 지원하는 글꼴 집합입니다. [추가 정보](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **배경 제거:** 자유 형식 그리기 도구를 사용하여 배경 그림을 제거합니다.
-   **나란히:** 인쇄 레이아웃 보기에서 용지 더미처럼 나란히 밀어서 페이지를 탐색합니다. [추가 정보](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **펜을 사용하여 개체를 선택한 후 변경:** 디지털 펜의 개체 핸들을 사용하여 크기 조정, 회전, 이동 등을 수행할 수 있습니다.
-   **SVG 이미지:** 문서에 SVG(확장 가능한 벡터 그래픽)를 삽입하고 편집합니다. [추가 정보](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **아이콘 삽입:**   삽입 \> 그림 \> 아이콘으로 이동 하 여 SVG (확장 가능한 벡터 그래픽) 파일의 표준 라이브러리에 있는 아이콘을 사용 합니다.   [추가 정보](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **최근 폴더에 저장:** 파일 \> 다른 이름으로 저장으로 이동한 후 최근에 사용한 항목 탭을 사용하여 최근에 사용한 폴더에 문서를 저장합니다.
-   **학습 도구를 사용한 읽기 개선:** 읽기 모드에서 문서를 큰 소리로 읽을 때 텍스트 간격을 조정하고, 음절 사이에 구분선을 표시하고, 각 단어를 강조함으로써 읽기 기술을 높이는 새 명령이 추가되었습니다. [추가 정보](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **도형 인식:** 그리기 \> 도형으로 변환을 사용하여 그림을 자동으로 도형으로 변환합니다. [추가 정보](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word: 보안 업데이트
-   Microsoft 보안 공지 [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office용 보안 업데이트(3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Microsoft Office 메모리 손상 취약성
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292): Windows PDF 원격 코드 실행 취약성 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509): Microsoft Office 원격 코드 실행 취약성  

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   사용자가 PST 파일을 검색할 수 없는 문제를 해결합니다.
-   사용자가 "새 Outlook 데이터 파일" 대화 상자의 새 "Microsoft Exchange" 저장 유형을 확인한 후 이 새 데이터 유형을 선택하면 사용자 프로필이 사용할 수 없는 상태가 되는 문제를 해결합니다.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Windows API를 사용한 Microsoft Office/워드패드 원격 코드 실행 취약성
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260): Microsoft Office 원격 코드 실행
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512): Microsoft Office 원격 코드 실행 취약성



## <a name="version-1701-may-9"></a>버전 1701:5 월 9 일부
*버전 1701(빌드 7766.2084)*

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   메시지를 삭제하면 메시지 목록의 메시지 선택 사항이 예기치 않게 이동하여 사용자에게 간헐적으로 표시되는 문제를 해결합니다.
-   간헐적으로 작동이 중지하는 문제를 해결합니다.
-   HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableSupportBackstage 레지스트리 키를 추가하면 관리자가 파일 탭에서 지원 선택 항목을 숨길 수 있습니다.
-   HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableOutlookFeedbackFeatures 레지스트리 키를 추가하면 관리자가 파일 \> 의견에서 “Outlook 2016 의견” 및 “Outlook 블로그” 옵션을 끌 수 있습니다.

### <a name="skype-for-business-security-updates"></a>비즈니스용 Skype: 보안 업데이트
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 원격 코드 실행 취약성

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
-   자동으로 수락된 대화의 대화 창이 최소화되지 않고 일반 창으로 열리며, 예기치 않게 다른 창에서 초점을 벗어나는 문제를 해결합니다.

### <a name="word-security-updates"></a>Word: 보안 업데이트
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Microsoft Office 메모리 손상 취약성
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 원격 코드 실행 취약성

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Microsoft Office 원격 코드 실행 취약성
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office 원격 코드 실행 취약성



## <a name="version-1701-april-11"></a>버전 1701:4 월 11 일
*버전 1701(빌드 7766.2076)*

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   .xls 통합 문서를 열면 새 창이 회색으로 표시되는 문제를 해결합니다.

### <a name="outlook-security-updates"></a>Outlook: 보안 업데이트
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Microsoft Outlook 원격 코드 실행 취약성
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): Microsoft Office 보안 기능 바이패스 취약성

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   사용자가 "새 Outlook 데이터 파일" 대화 상자의 새 "Microsoft Exchange" 저장 유형을 확인한 후 이 새 데이터 유형을 선택하면 사용자 프로필이 사용할 수 없는 상태가 되는 문제를 해결합니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   사용자가 USB 분리형 드라이브와 같은 이동식 미디어에 저장된 PowerPoint 파일의 다른 위치에 “다른 이름으로 저장”을 수행하면 이미지 누락 오류가 발생하는 문제를 해결합니다.

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
-   회사 내부 및 외부 네트워크를 전환하면 사용자가 로그인 할 수 없는 문제를 해결합니다.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Windows API를 사용한 Microsoft Office/워드패드 원격 코드 실행 취약성



## <a name="version-1701-march-14"></a>버전 1701:3 월 14 일
*버전 1701(빌드 7766.2071)*

### <a name="access-non-security-updates"></a>Access: 비보안 업데이트
-   플라이아웃 메뉴를 해제할 수 없는 문제를 해결합니다.

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   Microsoft 보안 공지 [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office용 보안 업데이트(3217868)

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   하이퍼링크를 삽입하면 Excel이 중지할 수도 있는 문제를 해결합니다.
-   XML 맵을 추가하면 Excel이 실패할 수도 있는 문제를 해결합니다.
-   추가 기능이 업그레이드된 후 또는 Office 스토어에서 추가 기능을 제거하고 다시 다운로드한 후에 추가 기능 명령 단추가 작동하지 않는 문제를 해결합니다.
-   VBA를 통해 DLL 시트를 조작하면 Excel이 중지할 수도 있는 문제를 해결합니다.

### <a name="onenote-non-security-updates"></a>OneNote: 비보안 업데이트
-   Windows 10 버전 1607(Windows 주년 업데이트라고도 함)에서 PIN을 사용하여 인증한 후 마우스 클릭에 OneNote 페이지 캔버스가 응답하지 않는 문제를 해결합니다.
-   사용자가 .docx 또는 .pptx와 같은 편집 가능한 문서를 삽입하면 최적화된 EDU 관련 출력 동작을 비활성화합니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   공동 작성 시 병합 충돌이 잘못 나타나는 문제를 해결합니다.
-   추가 기능이 업그레이드된 후 또는 Office 스토어에서 추가 기능을 제거하고 다시 다운로드한 후에 추가 기능 명령 단추가 작동하지 않는 문제를 해결합니다.
-   차트의 도형에 VBA 개체 모델을 호출할 때 런타임 오류가 발생하는 문제를 해결합니다.

### <a name="publisher-non-security-updates"></a>Publisher: 비보안 업데이트
-   게시자가 CMYK TIF 이미지를 표시하지 않는 문제를 해결합니다.

### <a name="skype-for-business-security-updates"></a>비즈니스용 Skype: 보안 업데이트
-   Microsoft 보안 공지 [MS17-013](https://technet.microsoft.com/library/security/ms17-013): Microsoft 그래픽 구성 요소용 보안 업데이트(4013075)

### <a name="word-security-updates"></a>Word: 보안 업데이트
-   Microsoft 보안 공지 [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office용 보안 업데이트(3217868)

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   특정 모니터 구성을 사용하면 발생하는 메모리 소모량 문제를 해결했습니다.
-   추가 기능이 업그레이드된 후 또는 Office 스토어에서 추가 기능을 제거하고 다시 다운로드한 후에 추가 기능 명령 단추가 작동하지 않는 문제를 해결합니다.



## <a name="version-1701-february-22"></a>버전 1701:2 월 22 일
*버전 1701(빌드 7766.2060)*

### <a name="excel-feature-updates"></a>Excel: 기능 업데이트
-   **데이터 변환 및 연결성 향상:** 값 사이의 구분 기호를 사용하여 목록을 새 텍스트 열로 확장하고 SQL에 연결할 경우 장애 조치 옵션을 지정할 수 있습니다.
-   **데이터 변환 및 연결성 향상:** 이제 백분율 데이터 형식이 지원되며 이진 결합 함수 작성 환경이 개선되었습니다.
-   **OLEDB 커넥터:** 가져오기 및 변환 기능의 OLEDB 커넥터를 사용하여 연결 문자열 및 경우에 따라 실행할 SQL 문을 지정하여 데이터를 가져올 쿼리를 만듭니다.
-   **잉크 리플레이:** 그리기 \> 잉크 리플레이로 이동하여 필기를 앞뒤로 재생하여 콘텐츠를 숨기거나 표시하거나 단계별 지침을 제공하거나 다른 사람이 가진 생각의 흐름을 보다 잘 이해할 수 있습니다. [추가 정보](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **CSV(UTF-8) 지원:** UTF-8 문자 인코딩을 사용하는 CSV 파일을 열고 저장합니다.
-   **데이터 변환 및 연결성 향상:** OData 원본에서 데이터를 로드할 때 관련된 테이블을 가져오거나, 함수 계산에서 나오는 값이 포함된 사용자 지정 열을 추가하거나, 전용 보기를 사용하여 쿼리 간의 종속성을 표시하도록 선택합니다.
-   **공유한 항목:** 파일 \> 열기 \> 공유한 항목으로 이동하여 다른 사용자가 나에게 공유한 문서를 확인하세요. [추가 정보](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **색 변경:** 입력 상자를 사용하여 글꼴, 강조 표시, 도형 채우기 등에 대한 색을 설정합니다. [추가 정보](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel: 보안 업데이트
-   Microsoft 보안 공지 [MS16-148](https://technet.microsoft.com/library/security/ms16-148): Microsoft Office용 보안 업데이트(3204068)

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   Office 테마를 검은색으로 설정할 경우 통합 문서 쿼리 창에서 쿼리를 마우스 오른쪽 단추로 클릭할 때 "예기치 않은 오류" 오류 메시지가 표시되는 문제를 해결합니다.
-   피벗 테이블 옵션에 액세스하려고 할 때 Excel이 충돌하는 문제를 해결합니다.
-   CSV 또는 CSV UTF-8로 저장하는 경우 텍스트와 큰따옴표가 있는 셀 값을 올바르게 내보낼 수 없는 문제를 해결합니다.
-   Excel을 닫을 때 Excel이 응답하지 않거나 작동이 중단하는 문제를 해결합니다.
-   연결 수식을 포함하는 하이퍼링크가 연결 결과의 일부를 무시하는 문제를 해결합니다.
-   RTF(서식 있는 텍스트) 형식의 Excel 표를 Word에 붙여 넣을 때 표 형식이 유지되지 않는 문제를 해결합니다.
-   통합 문서에 MS Excel 4.0 매크로 워크시트가 포함되어 있을 때 다른 이름으로 저장을 수행할 수 없는 문제를 해결합니다.
-   다른 응용 프로그램처럼 선택 영역을 개체 계층으로 이동하기 위한 바로 가기로 Ctrl+Alt+5를 지정합니다.
-   수식 입력줄에 입력하고 드롭다운이 포함된 함수(예: VLOOKUP)를 사용할 때 수식을 완료하기 위해 Enter 키를 누르면 입력한 값을 그대로 유지하지 않고 자동 완성 드롭다운에서 맨 위 항목을 선택하는 문제를 해결합니다.
-   보호된 시트 안에 하이퍼링크를 포함하고 있는 Excel 97 - Excel 2003 이진 파일 형식(BIFF8) 파일을 열면 Excel에서 해당 파일이 손상되었다고 생각하여 읽을 수 없는 콘텐츠를 복구하거나 제거하려고 하는 문제를 수정합니다.

### <a name="onedrive-for-business-non-security-updates"></a>비즈니스용 OneDrive: 비보안 업데이트
-   GrooveIntlResource.dll을 로드할 수 없는 경우(일반적이지 않음), 사용자가 파일을 열거나 동기화된 폴더에 파일을 저장하는 경우 Office 앱이 충돌하거나, 사용자가 Windows Explorer를 사용하여 동기화된 폴더로 이동하는 경우 Windows Explorer가 충돌하는 문제를 해결합니다.
-   비즈니스용 OneDrive를 사용하지 않도록 해당 레지스트리 키가 설정되어 있더라도 Office가 Office CDN(콘텐츠 전달 네트워크) 이외의 다른 위치에서 업데이트를 수신하도록 구성된 경우 비즈니스용 OneDrive를 사용하지 않도록 설정할 수 없는 문제를 해결합니다.

### <a name="onenote-feature-updates"></a>OneNote: 기능 업데이트
-   **파일 및 이미지 동기화 제어:** 파일 \> 옵션 \> 동기화로 이동하여 전자 필기장의 모든 페이지에 대해 모든 파일 및 이미지를 자동으로 다운로드할지 여부를 제어할 수 있습니다.

### <a name="onenote-non-security-updates"></a>OneNote: 비보안 업데이트
-   페이지보다 큰 이미지를 인쇄할 때 OneNote가 충돌하는 문제를 해결합니다.
-   사용자가 사용자 지정 페이지 템플릿을 삭제할 수 없는 문제를 수정합니다.

### <a name="outlook-feature-updates"></a>Outlook: 기능 업데이트
-   **첨부 파일에 대한 실시간으로 공동 작업:** 비즈니스용 OneDrive에 첨부 파일을 업로드하여 모든 사람이 최신 버전으로 작업하도록 할 수 있습니다. 첨부 파일에서 드롭다운 메뉴를 사용하여 업로드하거나 저장할 수 있습니다.
-   **여행 예약 및 패키지에 대한 요약 카드:** 받은 편지함 및 일정에 자동으로 생성되는 요약 카드를 사용하여 여행 예약 및 패키지 전달을 확인하고 추적합니다. [추가 정보](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **편집기:** 상황별 고급 교정을 제공하여 글쓰기를 향상합니다. [추가 정보](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook: 비보안 업데이트
-   대화에 대한 첨부 파일 목록에서 첨부 파일을 마우스 오른쪽 단추로 클릭할 경우 해당 메뉴 항목 대신 모든 상황에 맞는 메뉴 항목이 표시되는 문제를 해결합니다.
-   정보 권한 관리를 사용하여 RTF(서식 있는 텍스트) 전자 메일 메시지를 보낸 경우 수신자가 해당 메시지를 열 수 없는 문제를 해결합니다.

### <a name="powerpoint-feature-updates"></a>PowerPoint: 기능 업데이트
-   **선택 캡션:** 슬라이드에 선택 캡션이 있는 비디오가 포함되어 있을 때 캡션을 슬라이드 쇼에서 재생할 수 있습니다.
-   **여러 오디오 트랙:** 슬라이드에 여러 오디오 트랙이 있는 비디오가 포함되어 있을 때 트랙을 슬라이드 쇼에서 재생할 수 있습니다.
-   **섹션 복사:** 프레젠테이션 간에 섹션을 복사하고 붙여넣습니다.
-   **공유한 항목:** 파일 \> 열기 \> 공유한 항목으로 이동하여 다른 사용자가 나에게 공유한 문서를 확인하세요. [추가 정보](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **잉크 리플레이:** 필기를 앞뒤로 재생하여 콘텐츠를 숨기거나 나타내고, 단계별 지침을 제공하거나 다른 사람이 가진 생각의 흐름을 보다 잘 이해할 수 있습니다. [추가 정보](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **향상된 녹화 기능:** 녹화한 슬라이드, 화면 녹화 및 삽입한 비디오로 구성된 프레젠테이션을 만들고 녹화한 콘텐츠를 공유하여 원격으로 볼 수 있습니다. 잉크 색을 변경하고 좀 더 간편한 컨트롤을 통해 내레이션 및 오디오를 녹음할 수 있을 뿐 아니라 원격 학습을 위한 퀴즈를 포함하고 프레젠테이션의 대화형 기능을 강화할 수 있습니다.
-   **향상된 디자이너 기능:** 글머리 기호 프로세스 목록에 SmartArt를 사용하여 추천 디자인을 제공합니다.
-   **녹화 리본 탭:** 리본 메뉴를 사용자 지정하여 녹화 탭을 추가합니다.
-   **색 변경:** 입력 상자를 사용하여 글꼴, 강조 표시, 도형 채우기 등에 대한 색을 설정합니다. [추가 정보](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **확대/축소:** 자동 탐색 링크를 사용하여 프레젠테이션의 대화형 요약을 만듭니다. [추가 정보](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **하이퍼링크 열기:** 프레젠테이션을 편집할 때 Ctrl 키를 누른 채 클릭하여 하이퍼링크를 엽니다.
-   **텍스트 강조 표시:** 텍스트 형광펜을 사용하여 중요한 텍스트를 강조합니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   이미지를 자를 때 이미지의 잘린 부분이 어둡게 표시되는 문제를 해결합니다.
-   위치, 슬라이드 쇼 모드 및 내레이터가 실행되고 있을 때 사용자가 하이퍼링크를 클릭하면 PowerPoint가 충돌하고 사이트가 느리게 로드되는 문제를 해결합니다.
-   공동 작업 시 표에 대해 실시간 입력을 수행할 수 없는 문제를 해결합니다.
-   Malwarebytes 3.0이 설치된 컴퓨터에서 PowerPoint를 여는 경우 "작동이 중지됨" 오류가 나타나거나 PowerPoint 작동이 중단되는 문제를 해결합니다.
-   파일 \> 새로 만들기에서 기본 템플릿이 나타나지 않는 문제를 해결합니다.
-   폰트를 포함한 파일이 자동 저장되는 경우 텍스트 입력이 중단되거나 지연되는 문제를 해결합니다.
-   Adobe Illustrator에서 SVG(확장 가능한 벡터 그래픽) 이미지를 복사할 때의 문제를 해결합니다.

### <a name="project-feature-updates"></a>Project: 기능 업데이트
-   **잠긴 필드:** 팀 구성원이 작업에 대한 업데이트를 제출하지 못하게 하려면 이 값을 ‘예’로 설정합니다.
-   **시간 표시 막대 레이블:** 레이블을 통해 설명이 포함된 이름을 지정하여 시간 표시 막대를 구분합니다.
-   **시간 표시 막대 진행률 표시기:** 시간 표시 막대 보기에서 확인 표시 및 색으로 구분된 진행률 표시줄을 사용하여 각 작업을 얼마나 진행했는지 나타냅니다.
-   **향상된 내게 필요한 옵션:** 키보드, 내레이터 및 기타 보조 기술을 사용하여 프로젝트를 읽고 편집할 수 있도록 지원이 향상되었습니다.

### <a name="project-non-security-updates"></a>Project: 비보안 업데이트
-   마스터 프로젝트와 하위 프로젝트 간에 프로젝트 간 의존 관계를 만들 때 연결선이 표시되지 않는 문제를 해결합니다.
-   시간대별 초기 계획 값, 부분 기간이 포함된 작업 및 비용 값이 간혹 XML 형식으로 올바르게 저장되지 않는 문제를 해결합니다.
-   상태 업데이트를 적용할 때 팀 구성원이 보고하지 않은 배정에 실제 작업이 추가되는 문제를 해결합니다.
-   리소스에 대한 초기 계획을 만들지 않은 경우에도 해당 리소스에 대해 초기 계획 값이 표시되는 문제를 해결합니다.
-   인쇄 미리 보기에서 텍스트가 잘려 보이지 않는 문제를 해결합니다.
-   바로 가기 URL을 사용하여 SharePoint에서 .mpp 파일을 열 때 "문서를 편집하기 전에 체크 아웃해야 합니까?" 설정을 사용하는 경우에도 파일이 체크 아웃된 상태로 열리는 문제를 해결합니다.
-   Project Web App에서 재료 자원을 업데이트한 경우 시간대별 데이터가 올바르게 변경되지 않는 문제를 해결합니다.
-   중요 시점 작업이 있는 프로젝트를 열 때 해당 작업이 마지막으로 저장된 시점에 실제 시작 날짜가 없었던 경우에도 실제 시작 날짜가 추가될 수 있는 문제를 해결합니다.
-   WBS(작업 분할 구조) 번호 다시 매기기 문제를 해결합니다.
-   그리드 기반 보기 및 내레이터 해제 기능이 켜져 있을 때 Project가 충돌하는 무제를 해결합니다.
-   XML 파일을 열 때 시간대별 데이터 잘림에 대해 잘못된 오류 메시지가 표시되는 문제를 해결합니다.
-   초기 계획을 저장할 때 시간대별 값이 제대로 설정되지 않는 문제를 해결합니다.
-   XML 파일에서 프로젝트 데이터를 읽을 때 배정 연기가 무시되는 문제를 해결합니다.
-   Project Online에서 파일을 열 때 마지막으로 수정한 날짜에 표준 시간대 조정 시간이 아닌 UTC 시간이 표시되는 문제를 해결합니다.
-   시트 보기를 인쇄할 때 비그룹 행에 대해 그룹 색 줄무늬가 나타나지 않는 문제를 해결합니다.
-   사용자가 최대 단위 이상이 배정된 작업을 조사할 때 복구 옵션이 잘못 표시되는 문제를 해결합니다.
-   프로젝트를 게시한 후 개요 코드 필드의 값을 변경할 수 없는 문제를 해결합니다.
-   Gantt 막대가 175% 디스플레이의 높은 DPI 화면에서 크기가 제대로 조정되지 않는 문제를 해결합니다.
-   사용자가 작업 정보 대화 상자를 통해 지연 기간을 설정할 때 경과된 기간으로 제대로 설정되지 않는 문제를 해결합니다.
-   특정 XML 파일을 열 때 할당 문제 때문에 작업 시작 날짜가 제대로 설정되지 않는 문제를 해결합니다.

### <a name="skype-for-business-feature-updates"></a>Skype for Business: 기능 업데이트
-   **Windows 알림 스타일:** 들어오는 호출 및 대화에 대한 알림의 모양이 변경되었습니다. [추가 정보](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **문의 후 transfer:** 통화 내에서 다른 사용자에 게 통화를 전송 하기 전에 IM 또는 통화를 통해 해당 사용자에 게 문의 하세요. [추가 정보](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **마이크 알림:** 운영 체제에서 마이크가 음소거되어 있거나 마이크에서 오디오를 선택하지 경우 대화 창에 알림 메시지를 표시합니다.
-   **"내 번호" 사용 안 함:** DisableDisplayMyNumber 레지스트리 항목을 사용하여 다이얼 패드에서 "내 번호"를 사용하지 않도록 설정합니다.

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
-   참가자의 입장을 허용하거나 거부하는 데 사용되는 대기실 단추가 텍스트에서 이미지(X 또는 확인 표시)로 변경되었습니다.
-   모임 미리 알림 텍스트가 "수락"에서 "참가"로 변경되었습니다.
-   받는 사람의 상태가 방해 금지로 설정된 경우 IM 보낸 사람에게 표시되는 메시지가 업데이트되었습니다.
-   받는 사람이 오프라인 상태이고 "기록에 저장"이 사용하지 않도록 설정된 경우 받는 사람에게 메시지가 수신되지 않는다는 것을 명확히 하기 위해 IM 보낸 사람에게 표시되는 메시지가 업데이트되었습니다.
-   채팅 기록과 그룹 채팅 명단 사이의 세로 분할 막대를 이동하는 기능이 추가되었습니다.
-   IM 또는 대화방 창의 탭 목록 크기를 조정하는 기능이 추가되었습니다.
-   주제 피드를 만들 때 검색한 대화방을 선택하는 기능이 추가되었습니다.
-   대화 도중 채팅 기록에서 메시지 표시가 중지되는 문제를 해결합니다.
-   중복된 메시지가 대화 창에 표시되는 문제를 해결합니다.
-   많은 양의 알림이 있는 경우 알림 메시지 동작(허용 및 무시)이 제대로 표시되지 않는 문제를 해결합니다.
-   Alt+Tab을 사용하여 최소화된 대화 창을 연 후 사용자가 메시지를 입력할 수 없는 문제를 해결합니다.
-   IM을 사용할 수 있는 경우에도 사용자의 대화 상대 카드에 IM 단추가 회색으로 표시되는 문제를 해결합니다.
-   여러 대화 창을 닫았다가 다시 열면 이전 크기와 위치로 다시 열리지 않는 문제를 해결합니다.
-   사용자 지정 링크를 선택한 경우 해당 링크가 시작되지 않는 문제를 해결합니다.
-   영역 필드의 온라인 모임 텍스트가 영어가 아닌 문자인 경우 제대로 표시되지 않는 문제를 해결합니다.
-   통화 시간 등의 알림 정보가 오른쪽에서 왼쪽으로 쓰는 언어로 올바르게 렌더링되지 않는 문제를 해결합니다.
-   주제 피드를 만들 때 검색 결과를 지운 경우 다음 방 목록으로 결과가 다시 설정되지 않는 문제를 해결합니다.
-   여러 대화 창이 동시에 열려 있는 경우 비즈니스용 Skype가 중지되는 문제를 해결합니다.
-   다른 모든 탭을 닫으면 마지막 대화 창이 빈 상태가 되는 문제를 해결합니다.
-   탭 형식 대화가 사용되지 않도록 설정되어 있는 경우 채팅 입력 영역에 기본 포커스가 없는 문제를 해결합니다.
-   모임 초대에 "전화 접속 PIN를 잊으셨습니까?" 링크가 나타나지 않는 문제를 해결합니다.
-   175% 이상 디스플레이에서 높은 DPI 화면을 사용할 때 일반 및 오디오 장치 페이지에서 일부 텍스트가 잘리는 문제를 해결합니다.
-   네트워크가 없고 컴퓨터가 “AOAC(Always on, Always connected)” 컴퓨터인 경우 컴퓨터가 일시 중지되거나 다시 시작될 때 비즈니스용 Skype가 중단되는 문제를 해결합니다.
-   Polycom CX100 장치를 사용하는 경우 호출 시 마이크가 검색되지 않는 문제를 해결합니다.
-   IM 메시지에서 \\\\servername 또는 file://와 같은 링크를 선택할 때 해당 위치가 열리지 않고 오류 메시지가 표시되는 문제를 해결합니다.
-   위치 기반 라우팅을 사용하는 VDI(가상 데스크톱 인프라) 환경에서 서버가 사용자 위치를 PSTN 호출에 유효하지 않다고 판단하기 때문에 사용자가 PSTN 호출을 하거나 받지 못하는 문제를 해결합니다.
-   Change the subject line of the email sent for a missed message, when the user's status is set to Do Not Disturb or Presenting, from "Missed conversation with \<name\>" to "\<Name\> sent you a message in Skype for Business."
-   로그인 안정성 추세를 파악하기 위한 인구 조사 데이터의 일부로 [장치의 처음 로그인에 대한](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices) 타임스탬프 캡처를 시작합니다.
-   보조 모니터를 공유할 수 있는 옵션이 Windows 10 버전 1607(1주년 업데이트라고도 함)의 특정 모니터 구성에 나타나지 않는 문제를 해결합니다.
-   공유자가 타사 RDP 구현을 사용 중일 때 공유 콘텐츠를 확대하면 비즈니스용 Skype가 충돌하는 문제를 해결합니다.
-   VDI(가상 데스크톱 인프라) 환경에서 음성 통화의 컨트롤 단추를 클릭해도 오디오 제어판이 나타나지 않는 문제를 해결합니다.
-   사용자가 Windows 7을 실행하고 있으며 주 모니터를 먼저 공유한 다음 또 다른 모니터를 공유하려고 전환할 때 보기 권한자에게 검은색 화면이 표시되는 문제를 해결합니다.
-   문제를 해결할 경우 특정 특수 같이 앰퍼샌드(&)와 같은 특수 문자를 검색 입력 상자 또는 "새로운 소식" 섹션 상자에 입력할 수 없는 문제를 해결합니다.
-   오프라인 IM이 누락될 때 읽지 않은 IM 수가 표시되지 않는 문제를 해결합니다.
-   "전자 메일로 초대" 템플릿에 Skype 대신 Lync가 언급되는 문제를 해결합니다.
-   다이얼 패드 아래의 "내 번호" 영역에 회선 번호가 누락되는 문제를 해결합니다.
-   채팅에서 메시지를 보낸 후 IM 입력 영역에 마우스 포인터가 표시되지 않는 문제를 해결합니다.
-   로그인 시 비즈니스용 Skype가 중단되고 캐시 풀을 로드할 수 없는 문제를 해결합니다.
-   로그인 후 대화를 복원할 때 비즈니스용 Skype가 충돌하는 문제를 해결합니다.
-   다시 시작한 후 로그인할 때 비즈니스용 Skype가 중단되는 문제를 해결합니다.
-   두 조직의 Exchange 서버에서 TNEF가 사용되지 않도록 설정된 경우 모임 링크를 사용할 수 없는 문제를 해결합니다.
-   진행 중인 IM 대화가 하나만 있는 경우 음성 통화를 다시 시작할 수 없는 문제를 해결합니다.
-   화이트보드를 PNG 파일로 저장할 때 화이트보드의 텍스트 주석이 손실되는 문제를 해결합니다.
-   IM 창에서 일본어로 2줄 넘게 입력하면 첫 번째 줄이 숨겨지는 문제를 해결합니다.
-   이름에서 앰퍼샌드 문자(&)가 밑줄로 잘못 바뀌는 문제를 해결합니다.
-   예약된 모임에서 "온라인 모임 참석" URL의 문제를 해결합니다.
-   운영 체제 구성과 다르게 창 위로 마우스를 가져가도 창이 활성화되지 되지 않는 문제를 해결합니다.
-   발신 전화 대화 내역 항목에 호출한 상대방 대신 발신자가 표시되는 문제를 해결합니다.
-   F12 키를 눌러도 대화 내용이 로컬로 저장되지 않는 문제를 해결합니다.
-   부재 중 대화 메일에 초기 IM이 포함되지 않는 문제를 해결합니다.
-   발표자가 IM 참여를 사용하지 않도록 설정하더라도 IM 텍스트 영역에 이모지를 추가할 수 있는 문제를 해결합니다.
-   벨소리 및 소리 옵션 대화 상자의 레이아웃 문제를 해결합니다.
-   대화 창을 닫을 때 비즈니스용 Skype가 충돌하는 문제를 해결합니다.
-   도메인이 베니티 도메인으로 등록되어 있을 때 DNS 없는 로그인이 실패하는 문제를 해결합니다.
-   영구 채팅 알림 설정이 제대로 저장되지 않거나 로드되지 않는 문제를 해결합니다.
-   대화를 다시 여는 설정을 지정했더라도 로그인 후에 기존 피어 투 피어 대화 창 또는 대화방이 표시되지 않는 문제를 해결합니다.
-   활성 창을 음소거 또는 음소거 해제할 경우 다른 대화 창이 마치 읽지 않은 메시지가 있는 것처럼 표시되는 문제를 해결합니다.
-   미디어 바이패스용으로 구성된 사용자가 통화를 보류한 후에 PSTN 게이트웨이에서 호출을 다시 시작할 수 없는 문제를 해결합니다.
-   타사의 RDP 구현을 사용할 때 URL을 통해 모임에 참여할 경우 비디오 대신 파란색 상자가 표시되는 문제를 해결합니다.
-   알림 경고에 표시 이름 대신 SIP 주소의 사용자 부분이 표시되는 문제를 해결합니다.
-   비즈니스용 Skype가 포트 443을 통해 SIP 서버에 연결하고 프록시 서버가 있는 경우 프록시가 이러한 연결을 허용하지 않으면 로그인 프로세스가 상당히 지연되는 문제를 해결합니다. EnableDetectProxyForAllConnections DWORD 레지스트리 항목을 HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync에 추가하고 값을 1로 설정해서 문제를 해결할 수 있습니다.
-   탭된 대화를 사용할 때 탭을 두 번 클릭하고 입력하기 시작하면 때때로 포커스가 다른 탭으로 이동하게 만들어 해당 대화 창에 계속 입력하는 문제를 해결합니다.
-   인스턴트 메시지에 포함된 URL을 키보드를 사용하여 채팅 기록 창에서 선택할 수 없는 문제를 수정합니다.
-   벨 소리 및 소리 옵션에서 "IM 대화를 볼 때 및 누군가가 입력을 할 때 소리 재생" 확인란이 선택된 경우 입력 소리가 들리는 문제를 수정합니다.
-   내레이터와 같은 화면 읽기 프로그램을 사용하는 경우 표시되지 않는 대화 상자가 들리지 않는 문제를 수정합니다.
-   첫 번째 실행 자습서를 키보드로 탐색할 수 없으며 내레이터와 같은 화면 읽기 프로그램으로 읽을 수 없는 문제를 수정합니다.
-   높은 DPI 설정에서 작업 표시줄 상태 아이콘을 확장할 수 없는 문제를 수정합니다.
-   키보드를 사용하여 검색 상자의 필드 지우기 단추를 선택할 수 없는 문제를 수정합니다.
-   다른 풀의 사용자가 초대를 보낸 경우 사용자가 모임을 시작할 수 없는 문제를 수정합니다.
-   모임에 자기 자신을 추가하는 사용자가 다른 사용자로 잘못 표시되는 문제를 수정합니다.
-   상태 변경 알림의 대화 상대 현재 상태 아이콘이 상사의 걸려오는 전화에 숨겨지는 문제를 수정합니다.
-   IM 창의 텍스트 커서 깜박임 속도가 Windows의 키보드 속성 설정과 일치하지 않는 문제를 수정합니다.
-   화면 읽기 프로그램이 그룹 대화에 대해 잘못된 연락처 이름을 알리는 문제를 수정합니다.
-   사용자가 키보드를 사용하여 여러 연락처를 선택할 수 없는 문제를 수정합니다.
-   Exchange에서 사용자 사진을 검색할 수 없는 문제를 수정합니다.
-   사용자가 직접 액세스를 사용하여 연결할 때, 비즈니스용 Skype 클라이언트가 외부 네트워크 대신, 내부 네트워크의 비즈니스용 Skype 서버에 연결되는 문제를 수정합니다.
-   회의 소유자 이름을 확인하려고 할 때 비즈니스용 Skype 클라이언트가 충돌하는 문제를 수정합니다.
-   비즈니스용 Skype가 시작되거나 종료되는 동안 Windows 설정을 변경하면 비즈니스용 Skype가 충돌하는 문제를 수정합니다.
-   영구 채팅방에서 참석자 목록을 열고 키보드 포커스를 참가자 목록으로 이동하려고 하면 비즈니스용 Skype가 충돌하는 문제를 수정합니다.
-   네트워크가 없으면 비즈니스용 Skype를 다시 시작할 때 충돌하는 문제를 수정합니다.

### <a name="visio-feature-updates"></a>Visio: 기능 업데이트
-   **데이터베이스 모델링 추가 기능:** 새 데이터베이스를 계획하거나 기존 데이터베이스를 이해하기 위해 이 추가 기능을 사용하여 기존 데이터베이스의 데이터베이스 모델을 만들 수 있습니다. [추가 정보](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614), [추가 기능 다운로드](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **향상된 내게 필요한 옵션:** 키보드, 내레이터 및 기타 보조 기술을 사용하여 도형 관련 작업을 수행하고 다른 사용자와 함께 편집하는 등의 작업이 가능하도록 지원이 개선되었습니다.
-   **타사 템플릿 및 다이어그램:** 선별된 타사 콘텐츠 공급자에게서 사용 가능한 새 템플릿 및 샘플 다이어그램을 찾거나 검색합니다. 타사 공급자의 이름이 축소판에 표시됩니다.
-   **수동 입력 지원:** 새 그리기 탭의 도구를 사용하여 펜이나 손가락으로 그림을 그리고 주석을 답니다.

### <a name="word-feature-updates"></a>Word: 기능 업데이트
-   **향상된 내게 필요한 옵션:** 키보드, 내레이터 및 기타 보조 기술을 사용하여 문서를 읽고 편집할 수 있도록 지원이 향상되었습니다. [추가 정보](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **편집기:** 상황별 고급 교정을 제공하여 글쓰기를 향상합니다. [추가 정보](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **잉크 리플레이:** 그리기 \> 잉크 리플레이로 이동하여 필기를 앞뒤로 재생하여 콘텐츠를 숨기거나 표시하거나 단계별 지침을 제공하거나 다른 사람이 가진 생각의 흐름을 보다 잘 이해할 수 있습니다. [추가 정보](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **기본 펜 제스처를 사용하여 편집:** 원을 그려 선택하거나 선을 그어 삭제함으로써 문서를 변경합니다. [추가 정보](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **공유한 항목:** 파일 \> 열기 \> 공유한 항목으로 이동하여 다른 사용자가 나에게 공유한 문서를 확인하세요. [추가 정보](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **색 변경:** 입력 상자를 사용하여 글꼴, 강조 표시, 도형 채우기 등에 대한 색을 설정합니다. [추가 정보](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   하나의 문서를 읽기 모드로 표시한 경우 인쇄 모양 보기로 표시된 두 번째 문서에서 Tab 키가 작동하지 않는 문제를 해결합니다.
-   둘 이상의 문법 라이브러리가 로드될 때 Word가 중단되는 문제를 해결합니다.
-   Fix an issue where inked strokes disappear after two or three strokes.
-   Google IME(입력기)를 사용할 때 따옴표가 사라지는 문제를 해결합니다.
-   사용자가 콘텐츠 컨트롤을 사용하거나 인접하지 않은 항목을 선택한 경우 수동 입력을 사용할 수 없는 문제를 수정합니다.

### <a name="office-suite-feature-updates"></a>Office 제품군: 기능 업데이트
-   **의견 제공:** 파일 \> 의견으로 이동하여 Microsoft에 새로운 기능을 제안하거나 만족스러운 점 또는 작동하지 않는 사항을 알려주세요.

### <a name="office-suite-security-updates"></a>Office 제품군: 보안 업데이트
-   Microsoft 보안 공지 [MS16-148](https://technet.microsoft.com/library/security/ms16-148): Microsoft Office용 보안 업데이트(3204068)

### <a name="office-suite-non-security-updates"></a>Office 제품군: 비보안 업데이트
-   독일어 키보드에서 Ctrl+Alt+7 또는 Ctrl+Alt+8을 사용할 때 해당 문자가 삽입되는 대신 사용자 의견 도구가 열리는 문제를 해결합니다.
-   Office를 설치하거나 업데이트할 때 추적 로깅으로 인해 Windows 7의 작동이 중단되는 문제를 해결합니다.
-   잉크 및 마우스를 사용하여 그림을 그릴 때 마우스 단추를 떼면 잉크가 살짝 이동되는 문제를 해결합니다.
-   Office 문서에 SVG 이미지를 삽입한 후에 문서를 저장했다가 다시 열 경우 SVG 이미지가 사라지는 문제를 해결합니다.
-   Fix an issue where Office shows the following error message during activation for non-English users: "The maximum length of the product key is 25 characters."
-   프레임의 z 좌표가 제대로 작동하지 않거나 잘못 표시되게 만들 수 있는 VBA 양식의 문제를 해결합니다.
-   Configuration Manager에서 업데이트 잘못 된 레지스트리 내의 UpdateChannel 설정이 유효한 업데이트 채널이 아닌 항목으로 변경 되는 문제를 해결 합니다.



## <a name="version-1609-january-10"></a>버전 1609:1 월 10 일
*버전 1609(빌드 7369.2102)*

참고: Microsoft 보안 공지 [MS17-002](https://technet.microsoft.com/library/security/ms17-002) 에서 설명 하는 보안 업데이트는이 채널 릴리스의 Word 버전에는 적용 되지 않습니다.

### <a name="excel-non-security-updates"></a>Excel: 비보안 업데이트
-   측정값 편집 대화 상자를 사용하면 Excel이 중단되는 문제를 해결합니다.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: 비보안 업데이트
-   도형을 작업하는 경우 PowerPoint가 중단되는 문제를 해결합니다.

### <a name="skype-for-business-non-security-updates"></a>비즈니스용 Skype: 비보안 업데이트
-   보조 모니터를 공유할 수 있는 옵션이 Windows 10 버전 1607(1주년 업데이트라고도 함)의 특정 모니터 구성에 나타나지 않는 문제를 해결합니다.
-   공유자가 타사 RDP 구현을 사용 중일 때 공유 콘텐츠를 확대하면 비즈니스용 Skype가 충돌하는 문제를 해결합니다.
-   비즈니스용 Skype가 포트 443을 통해 SIP 서버에 연결하고 프록시 서버가 있는 경우 프록시가 이러한 연결을 허용하지 않으면 로그인 프로세스가 상당히 지연되는 문제를 해결합니다. EnableDetectProxyForAllConnections DWORD 레지스트리 항목을 HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync에 추가하고 값을 1로 설정해서 문제를 해결할 수 있습니다.

### <a name="word-non-security-updates"></a>Word: 비보안 업데이트
-   InsertXML 메서드를 사용하는 경우 실제 이미지 대신 끊어진 그림 링크의 자리 표시자가 나타나는 문제를 해결합니다.

