---
title: Office 365 ProPlus의 알려진 문제
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus의 알려진 문제에 대한 정보를 제공합니다.
ms.openlocfilehash: 18082351f0ed6df9b50e5c1193adb2d85a2da40a
ms.sourcegitcommit: 01ac73d10be11b830776836c70d0a0efe4e7aafc
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/04/2019
ms.locfileid: "37391312"
---
# <a name="office-365-proplus-known-issues"></a>Office 365 ProPlus의 알려진 문제

이 알려진 문제는 월별 채널, SACT 및 SAC 업데이트를 비롯한 Office 365용 Visio Pro, Project Online 데스크톱 클라이언트 및 Office 365 Business 그리고 2019년 Office 365 ProPlus에 포함된 비보안 업데이트에 관한 정보를 제공합니다.

이 표에서는 현재 진행 중인 문제와 해결된 문제에 대한 요약을 제공합니다.  아래의 표에는 조사 중인 중요한 문제를 업데이트할 것입니다.

 > [!NOTE]
 >- 이 목록은 포괄적이지 않습니다.

<br>

## <a name="september-2019"></a>2019년 9월

|요약|조사하는 중|해결됨|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|**Excel**
일부 보호된 시트에서 하이퍼링크를 붙여 넣을 수 없는 문제가 있습니다.|SACT 버전 1908 <br> SAC 버전 1902|월간 버전 1909 <br> (16.0.12026.20264)|
Excel 아이디어 기능에서, Win32 클라이언트에 있는 아이디어 버튼을 클릭하여 추가 기능을 로드할 때 오류가 발생하는 것을 발견했습니다.||월간 버전 1909 <br> (16.0.12026.20264)|
추가 기능 관리자에서 검색할 때 16개의 추가 기능만 표시되는 문제를 발견했습니다.|SACT 버전 1908|월간 버전 1909 <br> (16.0.12026.20264)|
|**Outlook**
파일이 WebDAV 위치에 저장되지 않는 문제를 발견하였습니다.||월간 버전 1909 <br> (16.0.12026.20264)|
일부 safelinks에서 간단한 호버 URL이 표시되지 않는 문제를 발견했습니다.|SACT 버전 1908|월간 버전 1909 <br> (16.0.12026.20264)|
Outlook에서 첨부 파일 차단 논리를 업데이트할 시 Python 첨부 파일 또한 차단하는 문제를 확인했습니다.|SACT 버전 1908|월간 버전 1909 <br> (16.0.12026.20264)|
Outlook 프로세스에서 메모리 누수가 사용자에게 관찰되는 문제를 수정했습니다.|SACT 버전 1908|월간 버전 1909 <br> (16.0.12026.20264)|
|**PowerPoint**
PowerPoint에서 공동 작성 및 오프라인 편집을 수반하는 세션에서 데이터가 손실될 수 있는 문제를 발견했습니다.|SACT 버전 1908|월간 버전 1909 <br> (16.0.12026.20264)|
|**프로젝트**
파일 메뉴에서 PDF/XPS를 만들 때 파일이 만들어지지 않는 문제가 발견되었습니다. |SAC 버전 1902||
|**Word**
사용자가 파일을 열 때 발생하는 문제를 확인했습니다.|SACT 버전 1908|월간 버전 1909 <br> (16.0.12026.20264)|
OneDrive 동기화 엔진에서 동기화되는 Office 파일의 경우, 저장 및 다른 이름으로 저장하는 경우에는 필요 속성 및 콘텐츠 형식 요구 사항과 같은 문서 메타데이터가 더 이상 유효성 검사되지 않는 문제가 발견되었습니다.|SAC 버전 1902||
Windows 19H1 빌드의 JAWS가 Caps + 오른쪽 화살표를 사용할 시 단어를 알리지 않는 문제를 발견했습니다.|SAC 버전 1902||
|**Office 제품군**
SHA-1 사용 중단: Office 고객의 보안을 위해 Microsoft Office 업데이트는 이제 SHA-2 알고리듬 만을 사용하여 서명됩니다.|SACT 버전 1908|월간 버전 1909 <br> (16.0.12026.20264)|
이전에 중단되었을 수 있는 다운로드를 다시 시작하여 Office 업데이트를 다운로드 시 발생하는 문제를 확인했습니다.|SACT 버전 1908|월간 버전 1909 <br> (16.0.12026.20264)||
로그인 후 "내 계정 수정" 알림이 사라지지 않는 문제를 발견했습니다.|SAC 버전 1902||



## <a name="may-2019---sample"></a>2019 5월 - 샘플

|요약|조사하는 중|해결됨|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|**Excel**
샘플을 여러 빌드에서 해결했습니다 -- 셀을 삽입하거나 삭제하는 경우 폭포 차트와 깔때기형 차트가 테이블로 동기화되지 않는 문제를 확인했습니다.||SAC 버전 1902 <br> (16.0.11328.20306) <br> 월간 버전 1905 <br> (16.0.11629.20210)|
|**Word**
샘플을 일부 빌드에서 해결했습니다. (전체는 아님) -- 문서 속성 Quick Parts를 활성화하는 경우 성능이 저하되는 문제가 확인되었습니다.|SAC 버전 1808|SACT 버전 1902 <br> (16.0.11328.20340)|

<br>
<br>

> [!NOTE]
> Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.
