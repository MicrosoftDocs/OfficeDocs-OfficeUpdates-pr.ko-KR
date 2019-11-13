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
ms.openlocfilehash: f863015cbf8680697509fdaf0bbd5c7000e4c142
ms.sourcegitcommit: e46d02cd54b8c164b853a130ca07ce9c85f586c5
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/12/2019
ms.locfileid: "38282166"
---
# <a name="office-365-proplus-known-issues"></a>Office 365 ProPlus의 알려진 문제

이 알려진 문제는 월별 채널, SACT 및 SAC 업데이트를 비롯한 Office 365용 Visio Pro, Project Online 데스크톱 클라이언트 및 Office 365 Business 그리고 2019년 Office 365 ProPlus에 포함된 비보안 업데이트에 관한 정보를 제공합니다.

이 표에서는 현재 진행 중인 문제와 해결된 문제에 대한 요약을 제공합니다.  아래의 표에는 조사 중인 중요한 문제를 업데이트할 것입니다.

> [!NOTE]
>- 이 목록은 포괄적이지 않습니다.
>- 해결됨으로 표시된 채널이 아닌 채널에서 문제가 발생하는 경우 곧 해결을 기대할 수 있습니다. [자세한 정보](https://docs.microsoft.com/ko-KR/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- 해결된 문제는 해당 채널 페이지에도 문서화되어 있습니다.

<br>

### <a name="last-updated-november-12-2019"></a>마지막 업데이트 날짜: 2019년 11월 12일

### <a name="excel"></a>Excel

- OneDrive에서 파일을 개체로 삽입하는 경우 발생 하는 문제를 확인했습니다.<br><br> **해결됨**: 월간 버전 1910 (12130.20272)

- 이전 버전의 Office에서 만든 통합 문서를 현재 버전의 Office에서 열었을 때 Excel이 중단될 수 있는 문제를 확인했습니다.<br><br>
**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20436), SAC 버전 1902 (11328.20468)

- 범위를 삭제한 후 입력된 값이 표시되는 데 지연이 되는 문제를 확인했습니다.<br><br>
**해결됨**: SAC 버전 1902 (11328.20468)

- 스크롤 후 셀을 선택하면 잘못된 셀이 선택되었던 문제를 확인했습니다.<br><br>
**조사 중**: SACT <br>**해결됨**: 월간 버전 1910 (12130.20272)

- 시리즈 컬렉션을 변경할 때 분산형 라인 차트가 제대로 렌더링되지 않을 수 있는 문제를 확인했습니다.<br><br>
**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20300)

### <a name="outlook"></a>Outlook

- 보조 Exchange 계정을 추가할 때 일부 사용자가 만들어진 중복된 특수 폴더를 보게 하였던 문제를 확인했습니다.<br><br>
**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20436)

- 메모리 누수를 발생시킬 수 있는 문제를 확인했습니다. <br><br>
**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20388), SAC 버전 1902 (11328.20468)

- 보조 Exchange 계정을 추가할 때 일부 사용자가 만들어진 중복된 특수 폴더를 보게 하였던 문제를 해결했습니다.<br><br>
**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20436)

- 사용자가 Skype에서 '부재 중 대화' 메시지를 받을 시 때때로 충돌이 발생할 수 있는 문제를 확인했습니다.<br><br>
**해결됨**: 월간 버전 1910 (12130.20272)

- DisableBGSave를 사용하도록 설정된 기기에서 첨부 파일을 열 때 일반적인 ""작업을 수행하지 못했습니다" 오류가 발생하는 문제를 확인했습니다.<br><br>
**해결됨**: 월간 버전 1910 (12130.20272)

- cid의 링크 관련 문제를 확인했습니다. 이미지 (Outlook 전자 메일 기반 이미지)가 나누어질 수 없음.<br><br>
**해결됨**: SACT 버전 1908 (11929.20436)

- S/MIME 암호화 전자 메일을 보내려고 할 때 잘못된 오류 메시지를 발생시킬 수 있었던 문제를 확인했습니다.<br><br>**해결됨**: 월간 버전 1910 (12130.20272)

### <a name="powerpoint"></a>PowerPoint

- 하이퍼링크를 사용하여 텍스트를 붙여넣을 때 하이퍼링크를 만들지 못하게 하였던 문제를 확인했습니다. <br><br>**해결됨**: 월간 버전 1910 (12130.20272)

- 슬라이드 마스터 및 슬라이드 레이아웃에서 머리글/바닥글/슬라이드 번호의 플레이스홀더에 텍스트를 붙여 넣은 후 TextRanges를 중단시킬 수 있었던 문제를 확인했습니다. <br><br>**해결됨**: 월간 버전 1910 (12130.20272)

- Win7에서 모든 앱의 리본 메뉴에서 도형 갤러리 삽입을 표시하는 데 약 4초가 걸리는 성능 문제를 확인했습니다.<br>
<br>**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20396), SAC 버전 1902 (11328.20468)

### <a name="project"></a>Project

- 읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 확인했습니다.<br><br>
**해결됨**: 월간 버전 1910 (12130.20344), SACT 버전 1908 (11929.20436)

### <a name="word"></a>Word
- OneDrive에서 파일을 개체로 삽입하는 경우 발생 하는 문제를 확인했습니다.<br><br> **해결됨**: 월간 버전 1910 (12130.20272)



<br>
<br>

> [!NOTE]
> Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.
