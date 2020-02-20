---
title: 2020년 반기 채널(대상 지정) 릴리스에 대한 릴리스 정보
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 2020년 Office 365 ProPlus에 대한 반기 채널(대상 지정) 릴리스의 릴리스 정보를 IT 전문가에게 제공합니다.
ms.openlocfilehash: 64270156e5985b3214a0e75c56f4bdb1713125fa
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978716"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a>2020년 반기 채널(대상 지정) 릴리스에 대한 릴리스 정보

이 릴리스 정보는 Office 365용 Visio Pro, Project Online 데스크톱 클라이언트 및 Office 365 Business를 비롯한 2020년 Office 365 ProPlus의 반기 채널(대상) 업데이트에 포함된 새로운 기능 및 비보안 업데이트에 관한 정보를 제공합니다.

> [!NOTE]
>
> - Microsoft는 일정 기간 동안 반기 채널(대상) 기능(및 경우에 따라 수정 사항)을 롤아웃합니다. 아래에서 설명했던 내용이 바로 보이지 않으면 곧 예측할 수 있습니다. [자세한 정보](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams는 버전 1902부터 반기 채널(대상 지정)의 새 설치에 포함됩니다. 버전 1908 이상으로 업데이트 되는 경우 기존 반기 채널(대상 지정) 설치에 Teams가 추가됩니다. 자세한 내용은 [Office 365 ProPlus와 함께 Microsoft Teams 배포](https://docs.microsoft.com/deployoffice/teams-install)를 참조하세요.

## <a name="version-1908-february-11"></a>버전 1908: 2월 11일
*버전 1908(빌드 11929.20606)*

[여기](https://docs.microsoft.com/ko-KR/officeupdates/office365-proplus-security-updates) 나열된 보안 업데이트


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제
### <a name="excel"></a>Excel

- 이 업데이트는 VBA를 사용하여 차트의 머리글/바닥글에 이미지를 추가할 때마다 오류가 발생하는 문제를 해결합니다.

- 인쇄 미리보기 또는 인쇄 시 그룹 상자 컨트롤의 테두리가 보이지 않던 문제를 수정했습니다.

- 사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.

- 차트가 포함된 통합 문서를 저장할 때 차트 머리글의 이미지 파일 크기가 커지는 문제가 해결되었습니다.


- 선택 범위를 상호 참조 도서와 동기화하여 상호 참조 도서에서 DBCS 문자가 손상되는 문제를 수정했습니다.

- 자동 맞춤을 사용하여 행 높이를 조정할 때 확인란 컨트롤이 축소될 수있는 문제를 해결했습니다.


### <a name="outlook"></a>Outlook

- 잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.

- 충돌 메시지를 처리할 때 사용자에게 동기화 오류가 발생하는 문제를 해결했습니다.

- Outlook을 시작할 때 사용자가 프로필을 로딩할 때 화면이 중단되는 문제를 해결했습니다.

- 보기를 변경할 때 사용자에게 간헐적인 충돌이 발생하는 문제를 해결했습니다.


- Citrix 환경에서 30개 이상의 캘린더를 볼 때 사용자에게 충돌이 발생하는 문제를 해결했습니다. [여기](https://support.microsoft.com/ko-KR/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)에는 이전 버전에 대해 문서화된 개별 KB가 있습니다.

- 사용자가 공유 일정 폴더를 OST와 동기화하는 데 문제가있어 이러한 폴더와 상호 작용할 때 권한 오류가 발생하는 문제를 해결합니다.


### <a name="powerpoint"></a>PowerPoint

- 복사-붙여넣기 시나리오 개선 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.


- 공동 작업 사용자 간에 성능이 저하되는 문제를 해결했습니다.

- 증분 방식으로 열린 파일에 둘 이상의 포함된 미디어 스트림이 있는 슬라이드가 포함되어 있을 때 발생할 수있는 문제를 수정했습니다.

- PowerPoint를 처음 시작할 때 신뢰할 수 없는 추가 기능에 대해 보안 경고 메시지 표시줄이 나타나지 않는 문제가 수정되었습니다.

### <a name="project"></a>Project

- 기본 일정이 변경될 때 리소스 일정이 업데이트되지 않아 작업표와 프로젝트 계획 간에 실제 작업이 다를 수 있는 문제가 해결되었습니다.

### <a name="word"></a>Word

- 더 이상 사용되지 않는 API에서 이동하여 Word의 충돌 문제가 해결되었습니다.

### <a name="office-suite"></a>Office 제품군

- 이 변경은 손상된 파일을 연 후 이미지를 올바르게 렌더링하는 문제를 해결합니다.



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-january-14"></a>버전 1908: 1월 14일
*버전 1908(빌드 11929.20562)*

나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a>해결된 문제
### <a name="excel"></a>Excel

- 문서 타이틀에 대한 네덜란드어 단축키가 Alt-G로 변경되었습니다.

- 포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.

- 추가 기능을 통해 연 WPF(Windows Presentation Foundation) 양식의 콤보 상자에서 항목을 선택할 수 없는 문제가 발생했습니다.

### <a name="outlook"></a>Outlook

- 사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 현저하게 지연이 발생하는 문제를 해결했습니다.

- 대체 보낸 사람을 사용할 때 정책 팁이 표시되지 않게 하는 문제를 해결했습니다.

- 사용자가 현재 상태 정보를 업데이트할 때 일시적으로 작동이 중지되는 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint

- 한 프레젠테이션에서 다른 프레젠테이션으로 슬라이드를 복사하여 중복하는 경우 마스터가 복제되는 문제를 해결했습니다.
- 최신 메모가 포함된 파일에는 지원되지 않는 버전에서 열었을 경우 노란색 경고가 표시됩니다.

### <a name="office-suite"></a>Office 제품군

- Office 업데이트 메시지가 다른 언어로 표시되는 문제를 해결했습니다. 앞으로 Office 업데이트 메시지 언어가 Windows 표시 언어와 정확하게 일치할 것입니다.  

- 사용자가 관리자가 아니거나 시스템 계정에 네트워크 연결이 없는 경우에 업데이트가 적용되지 않는 문제를 해결했습니다.


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

> [!NOTE]
> Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.