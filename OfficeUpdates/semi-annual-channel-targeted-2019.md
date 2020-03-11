---
title: 2019년 반기 채널(대상 지정) 릴리스에 대한 릴리스 정보
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 2019년 Office 365 ProPlus에 대한 반기 채널(대상 지정) 릴리스의 릴리스 정보를 IT 전문가에게 제공합니다.
ms.openlocfilehash: 2384ed54f8e18e89981cdd875d46bfd9ba7e95a5
ms.sourcegitcommit: 59f243dfec169ff246cd68ca7f796fde696e2981
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/06/2020
ms.locfileid: "42549329"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2019"></a><span data-ttu-id="d4a04-103">2019년 반기 채널(대상 지정) 릴리스에 대한 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-103">Release notes for Semi-Annual Channel (Targeted) releases in 2019</span></span>

<span data-ttu-id="d4a04-104">이 릴리스 정보는 Office 365용 Visio Pro, Project Online 데스크톱 클라이언트 및 Office 365 Business를 비롯한 2019년 Office 365 ProPlus의 반기 채널(대상) 업데이트에 포함된 새로운 기능 및 비보안 업데이트에 관한 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel (Targeted) updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
> - <span data-ttu-id="d4a04-105">Microsoft는 일정 기간 동안 반기 채널(대상) 기능(및 경우에 따라 수정 사항)을 롤아웃합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-105">We often roll out features (and sometimes even fixes) to Semi-Annual Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="d4a04-106">아래에서 설명했던 내용이 바로 보이지 않으면 곧 예측할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="d4a04-107">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - <span data-ttu-id="d4a04-108">Microsoft Teams는 버전 1902부터 반기 채널(대상 지정)의 새 설치에 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-108">Microsoft Teams is included in new installations of Semi-Annual Channel(Targeted), starting with Version 1902.</span></span> <span data-ttu-id="d4a04-109">버전 1908 이상으로 업데이트 되는 경우 기존 반기 채널(대상 지정) 설치에 Teams가 추가됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-109">Teams will be added to existing installations of Semi-Annual Channel(Targeted) when those are updated to Version 1908 or later.</span></span> <span data-ttu-id="d4a04-110">자세한 내용은 [Office 365 ProPlus와 함께 Microsoft Teams 배포](https://docs.microsoft.com/DeployOffice/teams-install)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-110">For more information, see [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install).</span></span>

## <a name="version-1908-december-10"></a><span data-ttu-id="d4a04-111">버전 1908: 12월 10일</span><span class="sxs-lookup"><span data-stu-id="d4a04-111">Version 1908: December 10</span></span>
<span data-ttu-id="d4a04-112">*버전 1908 (빌드 11929.20516)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-112">*Version 1908 (Build 11929.20516)*</span></span>

<span data-ttu-id="d4a04-113">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d4a04-113">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d4a04-115">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d4a04-115">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d4a04-116">Access</span><span class="sxs-lookup"><span data-stu-id="d4a04-116">Access</span></span>

- <span data-ttu-id="d4a04-117">원격 테이블(예: SQL Server 테이블)로의 참조를 포함하는 통합 쿼리가 Access를 닫고 다시 시작하도록 할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-117">Fixed an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="d4a04-118">합계와 같은 집계가 결과를 정수로 줄일 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-118">Fixed an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

### <a name="excel"></a><span data-ttu-id="d4a04-119">Excel</span><span class="sxs-lookup"><span data-stu-id="d4a04-119">Excel</span></span>

- <span data-ttu-id="d4a04-120">스크롤 후 셀을 선택하면 잘못된 셀이 선택되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-120">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="d4a04-121">OLAP PivotTable의 필터가 큐브에서 제거된 값으로 설정되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-121">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="d4a04-122">이 변경 사항은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-122">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="d4a04-123">Lookup 함수에서 오류가 반환될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-123">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="d4a04-124">병합된 셀이 있는 열을 삭제하는 성능이 크게 개선됨.</span><span class="sxs-lookup"><span data-stu-id="d4a04-124">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="d4a04-125">최소화된 창을 활성화하는 매크로 런타임 오류를 발생시켰던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-125">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

### <a name="outlook"></a><span data-ttu-id="d4a04-126">Outlook</span><span class="sxs-lookup"><span data-stu-id="d4a04-126">Outlook</span></span>

- <span data-ttu-id="d4a04-127">SMIME 알고리듬 선택의 문제를 수정하였습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-127">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="d4a04-128">규칙 대화 상자를 열 때 &quot;이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다&quot; 프롬프트가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-128">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="d4a04-129">웹 추가 기능이 디지털 권한 관리 메시지에 액세스하지 않아야 함에도 액세스하게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-129">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

### <a name="word"></a><span data-ttu-id="d4a04-130">Word</span><span class="sxs-lookup"><span data-stu-id="d4a04-130">Word</span></span>

- <span data-ttu-id="d4a04-131">때때로 무한 루프로 들어가는 변경 내용 추적 기능 상의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-131">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d4a04-132">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d4a04-132">Office Suite</span></span>

- <span data-ttu-id="d4a04-133">PowerPoint의 세로 텍스트 상자에서 가타카나 반각글자가 제대로 회전하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-133">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="d4a04-134">Office 업데이트에서 로컬 또는 네트워크 공유 또는 Configuration Manager에서 제공하는 위치와 같은 의도된 원본 대신 Office CDN에서 파일을 예기치 않게 다운로드했을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-134">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="d4a04-135">Office 고객의 보안을 위해 Microsoft Office 업데이트는 이제 SHA-2 알고리듬 만을 사용하여 서명됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-135">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-november-22"></a><span data-ttu-id="d4a04-137">버전 1908: 11월 22일</span><span class="sxs-lookup"><span data-stu-id="d4a04-137">Version 1908: November 22</span></span>
<span data-ttu-id="d4a04-138">*버전 1908(빌드 11929.20494)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-138">*Version 1908 (Build 11929.20494)*</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d4a04-140">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d4a04-140">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="d4a04-141">Access</span><span class="sxs-lookup"><span data-stu-id="d4a04-141">Access</span></span>

- <span data-ttu-id="d4a04-142">업데이트 쿼리를 실행하면 "쿼리가 손상되었습니다"라는 오류 메시지가 잘못 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-142">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

### <a name="excel"></a><span data-ttu-id="d4a04-143">Excel</span><span class="sxs-lookup"><span data-stu-id="d4a04-143">Excel</span></span>

- <span data-ttu-id="d4a04-144">파일에 광범위한 조건부 서식이 있는 경우 글꼴색 단추를 클릭하면 성능이 저하되는 문제.</span><span class="sxs-lookup"><span data-stu-id="d4a04-144">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="d4a04-145">인쇄 미리 보기의 인쇄 영역이 올바르지 않았던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-145">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="d4a04-146">신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 오류를 발생시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-146">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="d4a04-147">통합 문서가 열려있지 않은 상태에서 최근 파일을 검색할 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-147">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

### <a name="outlook"></a><span data-ttu-id="d4a04-148">Outlook</span><span class="sxs-lookup"><span data-stu-id="d4a04-148">Outlook</span></span>

- <span data-ttu-id="d4a04-149">사용자가 계정 만들기 컨텍스트에서 지원 센터에 문의하려고 할 때 &quot;확인&quot; 버튼이 있는 빈 메시지 상자가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-149">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="d4a04-150">관리자가 정책을 사용하여 UPN에 대한 자동 검색 인증 프롬프트에서 제공된 계정 전자 메일을 원하는 대로 변경할 수 있도록 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-150">Made a change that allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="d4a04-151">기본적으로 AutoDiscover는 가능한 경우 계정 UPN을 선호합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-151">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="d4a04-152">사용자가 Modern Groups에 대한 검색 실패를 보게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-152">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="d4a04-153">사용자가 &quot;놓친 대화 메시지&quot;에서 규칙을 만들려고 할 때 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-153">Addressed an issue that caused users to experience a crash when attempting to create a rule from a &quot;Missed Conversation&quot; message.</span></span>

- <span data-ttu-id="d4a04-154">사용자가 Modern Groups에 대한 검색 실패를 보게 되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-154">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

### <a name="word"></a><span data-ttu-id="d4a04-155">Word</span><span class="sxs-lookup"><span data-stu-id="d4a04-155">Word</span></span>

- <span data-ttu-id="d4a04-156">Deskjet 프린터로 인쇄할 때 배율 문제가 발생할 수 있는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-156">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d4a04-157">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d4a04-157">Office Suite</span></span>

- <span data-ttu-id="d4a04-158">온라인을 발표할 때 PowerPoint 사용자가 오류를 보내지 못하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-158">Fixed an issue to prevent PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="d4a04-159">레지스트리 무결성과 관련된 Office 업데이트 프로세스의 안정성이 향상되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-159">Improved reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="d4a04-160">데이터 통신 네트워크에서 업데이트가 예기치 않게 차단되었을 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-160">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="d4a04-161">상대적인 기한이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정의 문제가 수정되어 후속 업데이트에 대한 상대적인 기한이 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-161">Fixed an issue in ODT and GPO Updae Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-november-12"></a><span data-ttu-id="d4a04-163">버전 1908: 11월 12일</span><span class="sxs-lookup"><span data-stu-id="d4a04-163">Version 1908: November 12</span></span>
<span data-ttu-id="d4a04-164">*버전 1908(빌드 11929.20436)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-164">*Version 1908 (Build 11929.20436)*</span></span>

<span data-ttu-id="d4a04-165">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d4a04-165">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d4a04-167">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d4a04-167">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="d4a04-168">Excel</span><span class="sxs-lookup"><span data-stu-id="d4a04-168">Excel</span></span>

- <span data-ttu-id="d4a04-169">차트 템플릿을 사용하여 차트를 삽입할 때 미리 보기에 사용되는 색을 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-169">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>
- <span data-ttu-id="d4a04-170">시리즈 컬렉션을 변경할 때 분산형 차트가 제대로 렌더링되지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-170">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>
- <span data-ttu-id="d4a04-171">매크로가 실행되는 사용자 지정 속성을 변경할 때 공동 작성 작업을 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-171">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>
- <span data-ttu-id="d4a04-172">함수를 동기적으로 실행하게 만드는 비동기적인 사용자 정의 함수의 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-172">We resolved an performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>
- <span data-ttu-id="d4a04-173">색 기준 필터링의 성능이 크게 향상되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-173">We have significantly improved the performance of filtering by color.</span></span>
- <span data-ttu-id="d4a04-174">이전 버전의 Office에서 작성한 통합 문서를 현재 버전의 Office에서 열었을 때 Excel이 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-174">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>
- <span data-ttu-id="d4a04-175">cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-175">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

### <a name="outlook"></a><span data-ttu-id="d4a04-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="d4a04-176">Outlook</span></span>

- <span data-ttu-id="d4a04-177">cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-177">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="d4a04-178">기본 일정의 항목을 그룹 일정에 복사할 때 사용 권한 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-178">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>
- <span data-ttu-id="d4a04-179">매우 긴 Outlook 세션에서 메모리 누수를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-179">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>
- <span data-ttu-id="d4a04-180">사용자가 특정 Safelinks와 상호 작용할 때 Outlook에서 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-180">Addressed an issue that would cause users to experience a failure in Outlook when interacting with certain safelinks.</span></span>
- <span data-ttu-id="d4a04-181">일부 AutoDiscover 응답을 처리할 때 사용자에게 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-181">Addressed an issue that caused users to experience a failure when processing some AutoDiscover responses.</span></span>
- <span data-ttu-id="d4a04-182">보조 Exchange 계정을 추가할 때 일부 사용자에게 만들어진 중복된 특수 폴더를 보이게 하였던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-182">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>
- <span data-ttu-id="d4a04-183">피드백 검색 환경을 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-183">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d4a04-184">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d4a04-184">PowerPoint</span></span>

- <span data-ttu-id="d4a04-185">cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-185">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span></div>
- <span data-ttu-id="d4a04-186">안정성 픽스: 타사 추가 기능으로 인해 PowerPoint에서 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-186">Reliability fix: Fixed an issue where third party add-in might cause PowerPoint to fail.</span></span>

### <a name="project"></a><span data-ttu-id="d4a04-187">Project</span><span class="sxs-lookup"><span data-stu-id="d4a04-187">Project</span></span>

- <span data-ttu-id="d4a04-188">모두 균등화 명령이 리소스의 초과 할당을 제대로 해결하지 못하던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-188">Fixed an issue where the Level All command wasn't properly resolving a resource overallocation.</span></span>
- <span data-ttu-id="d4a04-189">과업에 대한 작업이 0인 과제가 있는 경우 해당 과업이 완성으로 표시되지 않고 항상 99%로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-189">Fixed an issue where if you have an assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>
- <span data-ttu-id="d4a04-190">읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-190">Identified an issue where users could get several messages when opening a read-only project.</span></span>

### <a name="word"></a><span data-ttu-id="d4a04-191">Word</span><span class="sxs-lookup"><span data-stu-id="d4a04-191">Word</span></span>

- <span data-ttu-id="d4a04-192">cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-192">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="d4a04-193">종료 시 앱이 중단될 수 있는 다양한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-193">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="d4a04-194">또한 특정 추가 기능 관련 오류도 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-194">Also fixed certain add-in related failures.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d4a04-195">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d4a04-195">Office Suite</span></span>

- <span data-ttu-id="d4a04-196">타사의 플러그인에서 Textbox/Shape Autofit 속성과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-196">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="october-15"></a><span data-ttu-id="d4a04-198">10월 15일</span><span class="sxs-lookup"><span data-stu-id="d4a04-198">October 15</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="d4a04-199">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-199">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="d4a04-200">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d4a04-200">Office Suite</span></span>
- <span data-ttu-id="d4a04-201">16.0.11929.20396 이전 빌드에 대해 2019년 10월 14일에 게시한 저장 문제를 해결하기 위해 클라우드 저장 대화 상자를 일시적으로 사용하지 않도록 설정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-201">We have temporarily disabled the Cloud Save dialog to address the saving issue we posted on October 14, 2019 for builds older than 16.0.11929.20396.</span></span> <span data-ttu-id="d4a04-202">이 기능은 곧 다시 활성화됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-202">This feature will be re-enabled soon.</span></span>

## <a name="version-1908-october-14"></a><span data-ttu-id="d4a04-203">버전 1908: 10월 14일</span><span class="sxs-lookup"><span data-stu-id="d4a04-203">Version 1908: October 14</span></span>
<span data-ttu-id="d4a04-204">*버전 1908(빌드 11929.20396)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-204">*Version 1908 (Build 11929.20396)*</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="d4a04-206">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-206">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="d4a04-207">Excel</span><span class="sxs-lookup"><span data-stu-id="d4a04-207">Excel</span></span>

- <div><span data-ttu-id="d4a04-208">첫 번째 항목을 발견한 후 대화 상자에서 포커스가 있던 위치가 찾기 및 바꾸기로 변경되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-208">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span></div>

### <a name="office-suite"></a><span data-ttu-id="d4a04-209">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d4a04-209">Office Suite</span></span>

- <span data-ttu-id="d4a04-210">16.0.11929.20396 이전 빌드에 대해 Word, Excel 및 PowerPoint 2019 문서를 저장할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-210">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint 2019 documents for builds older than 16.0.11929.20396.</span></span>  <span data-ttu-id="d4a04-211">이 문제는 새 파일을 만든 후 저장 아이콘을 클릭하거나 Ctrl + S를 눌러 "다른 이름으로 저장" 대화 상자를 표시하는 사용자에게 영향을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-211">This issue affects users that create a new file and bring up the “Save As” dialog after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="d4a04-212">특정 상황에서 Office 바로 가기가 업데이트 후에 사라지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-212">Resolved an issue where in certain circumstances, Office shortcuts may disappear following an update.</span></span>  <span data-ttu-id="d4a04-213">이 업데이트는 Office 바로 가기를 게시할 때 안정성을 높입니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-213">This update improves reliability when publishing of Office shortcuts.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-october-08"></a><span data-ttu-id="d4a04-215">버전 1908: 10월 8일</span><span class="sxs-lookup"><span data-stu-id="d4a04-215">Version 1908: October 08</span></span>
<span data-ttu-id="d4a04-216">*버전 1908 (빌드 11929.20388)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-216">*Version 1908 (Build 11929.20388)*</span></span>

<span data-ttu-id="d4a04-217">보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)에 나열되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-217">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="d4a04-219">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-219">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="d4a04-220">Excel</span><span class="sxs-lookup"><span data-stu-id="d4a04-220">Excel</span></span>

- <span data-ttu-id="d4a04-221">일부 보호된 시트에서 하이퍼링크를 붙여 넣을 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-221">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="d4a04-222">추가 기능 관리자에서 검색할 시 16개 이상의 추가 기능을 표시하기 위한 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-222">Fixed an issue to enable more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="d4a04-223">Excel 아이디어 기능에서, Win32 클라이언트에 있는 아이디어 버튼을 클릭하여 추가 기능을 로드할 때 발생하는 오류를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-223">Fixed issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="d4a04-224">Outlook</span><span class="sxs-lookup"><span data-stu-id="d4a04-224">Outlook</span></span>

- <span data-ttu-id="d4a04-225">일부 safelinks에서 간단한 호버 URLl이 표시되지 않게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-225">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="d4a04-226">Outlook에서 Python 첨부 파일도 또한 차단하기 위해 첨부 파일 차단 논리를 업데이트하였습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-226">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="d4a04-227">Outlook 프로세스에서 메모리 누수가 사용자에게 관찰되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-227">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d4a04-228">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d4a04-228">PowerPoint</span></span>

- <span data-ttu-id="d4a04-229">PowerPoint에서 공동 작성 및 오프라인 편집을 수반하는 세션에서 데이터가 손실될 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-229">Fixed an issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d4a04-230">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d4a04-230">Office Suite</span></span>

- <span data-ttu-id="d4a04-231">사용자가 파일을 열 때 발생하는 충돌 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-231">Fixed an issue for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="d4a04-232">백스테이지의 정보 위치판에 접근성 정보가 표시 되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-232">Fixed an issue where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="d4a04-233">이전에 중단되었을 수 있는 다운로드를 다시 시작하여 Office 업데이트를 다운로드 시의 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-233">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="d4a04-234">Office 고객의 보안을 위해 Microsoft Office 업데이트는 이제 SHA-2 알고리듬 만을 사용하여 서명됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-234">To protect Office customer’s security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-september-10"></a><span data-ttu-id="d4a04-236">버전 1908: 9월 10일</span><span class="sxs-lookup"><span data-stu-id="d4a04-236">Version 1908: September 10</span></span>
<span data-ttu-id="d4a04-237">*버전 1908 (빌드 11929.20300)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-237">*Version 1908 (Build 11929.20300)*</span></span>

<span data-ttu-id="d4a04-238">보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)에 나열되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-238">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d4a04-240">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-240">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="d4a04-241">Access</span><span class="sxs-lookup"><span data-stu-id="d4a04-241">Access</span></span>

- <span data-ttu-id="d4a04-242">**더 많은 공간을 사용하여 확대/축소:** 확대/축소 상자의 크기를 키우고, 글꼴을 변경할 수 있습니다. 확대/축소에 이러한 설정이 모두 저장됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-242">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="d4a04-243">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-243">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- <span data-ttu-id="d4a04-244">**데이터베이스 개체에 탭 유지:** 활성 탭이 무엇인지 명확하게 구분할 수 있고, 간편하게 끌어서 순서를 변경할 수 있고, 클릭 한 번으로 데이터베이스 개체를 닫을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-244">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="d4a04-245">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-245">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="d4a04-246">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-246">Switching between them has never been easier.</span></span> [<span data-ttu-id="d4a04-247">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-247">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a><span data-ttu-id="d4a04-248">Excel</span><span class="sxs-lookup"><span data-stu-id="d4a04-248">Excel</span></span>

- <span data-ttu-id="d4a04-p110">**자세한 데이터 분석:** 새로운 아이디어 단추는 데이터에서 패턴을 찾아서 인텔리전트 맞춤형 제안을 만듭니다. [자세히 알아보기](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p110">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="d4a04-251">**해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="d4a04-251">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="d4a04-252">파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-252">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="d4a04-253">**콘텐츠 도달 범위 늘리기:** 접근성 높은 프레젠테이션을 만들어야 하나요?</span><span class="sxs-lookup"><span data-stu-id="d4a04-253">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="d4a04-254">진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-254">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="d4a04-255">검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-255">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="d4a04-256">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-256">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="d4a04-257">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-257">Switching between them has never been easier.</span></span> [<span data-ttu-id="d4a04-258">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-258">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="d4a04-259">**생동감 있는 워크시트 보기:** 애니메이션 3D 그래픽을 삽입하여 워크북을 통해 심장 박동, 행성 궤도, 공룡 난동 모습 등을 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-259">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="d4a04-260">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-260">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="d4a04-261">**공동 작업이 쉬워졌습니다.** 공동 작성 기능이 향상되면 조건부 서식, 셀 스타일 등을 사용하여 작업할 때 변경 내용이 공동 작업자와 원활하게 통합됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-261">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="d4a04-262">**유사한 열의 테이블 조인:** 가져오기 및 변환 기능(파워 쿼리)은 테이블 병합을 위해 열을 비교하는 경우 근사 텍스트 매칭 논리(퍼지 매칭)를 특징으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-262">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="d4a04-263">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-263">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="d4a04-264">**파워 쿼리 기능 향상을 통한 신속한 코드:** 자동 완성 및 구문 색상을 사용하여 신속하게 코드를 완성하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-264">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="d4a04-265">함수, 열, 매개 변수를 쉽게 검색할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-265">Easily discover functions, columns, and parameters, too.</span></span>

### <a name="outlook"></a><span data-ttu-id="d4a04-266">Outlook</span><span class="sxs-lookup"><span data-stu-id="d4a04-266">Outlook</span></span>

- <span data-ttu-id="d4a04-267">**메시지를 전달하는 동안에도 작업 지속 가능:** Outlook이 이제 백그라운드에서 메시지를 전달합니다. 따라서 폴더 간에 많은 메시지를 주고 받는 동안에도 작업을 계속할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-267">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="d4a04-268">\*\*연달아 있는 모임 사이에 시간 넣기: \*\*모임이 기본적으로 5~10분 일찍 끝나도록 설정하여 참석자에게 잠시 숨을 돌리거나 장소를 이동할 시간을 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-268">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="d4a04-p117">**밈하는 항목 표시:** 텍스트 또는 정적 이미지로 가능하지 않은 경우 애니메이션 GIF를 의도하는 바를 나타냅니다. [자세히 알아보기](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p117">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="d4a04-271">**Outlook 사용자 환경이 업데이트됨:** 출시 예정을 사용하여 이전에 미리 볼 수 있었던 간소화된 환경은 가장 중요한 작업에 집중할 수 있도록 설계되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-271">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="d4a04-272">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-272">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="d4a04-273">**보통 또는 더 좁은 간격 선택:** 더 좁은 간격을 사용하면 항목 간에 더 넓은 공백을 할지 또는 더 좁은 레이아웃을 사용하여 더 많은 항목을 표시할지를 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-273">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="d4a04-274">**사용자 지정이 가능한 간소화된 리본:** 가장 많이 사용하는 단추가 한 행에 표시되어 간편합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-274">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="d4a04-275">클래식 및 요약 보기 간의 간편한 전화 및 명령 고정/고정 해제</span><span class="sxs-lookup"><span data-stu-id="d4a04-275">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="d4a04-276">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-276">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="d4a04-277">**빠르게 계정 추가:** 계정 설정 기능이 향상되어 Outlook에서 2단계 인증을 사용하여 Outlook.com 및 Gmail 계정을 추가하는 것이 그 어느 때보다 쉬워졌습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-277">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="d4a04-278">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-278">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="d4a04-279">**자주 하는 작업 선택:** 플래그 및 삭제를 사용하지 않나요?</span><span class="sxs-lookup"><span data-stu-id="d4a04-279">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="d4a04-280">[보관] 또는 [읽은 상태로 표시]는 어떤가요?</span><span class="sxs-lookup"><span data-stu-id="d4a04-280">How about Archive or Mark as Read?</span></span> <span data-ttu-id="d4a04-281">가장 많이 사용하는 명령으로 빠른 작업 메뉴를 사용자 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-281">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="d4a04-282">**동기화 제한 문제 해결:** Outlook의 기능 향상으로 폴더 제한이 사라지고 공유된 편지함을 동기화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-282">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d4a04-283">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d4a04-283">PowerPoint</span></span>

- <span data-ttu-id="d4a04-p122">**대상 그룹에 퀴즈를 내거나 설문 조사하기:** 슬라이드에 퀴즈 또는 설문 조사를 넣습니다. Office가 응답을 수집하고 저장합니다. [자세한 정보](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p122">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="d4a04-287">**해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="d4a04-287">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="d4a04-288">파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-288">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="d4a04-289">**콘텐츠 도달 범위 늘리기:** 접근성 높은 프레젠테이션을 만들어야 하나요?</span><span class="sxs-lookup"><span data-stu-id="d4a04-289">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="d4a04-290">진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-290">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="d4a04-291">검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-291">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="d4a04-292">**변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-292">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="d4a04-p125">**그 어느 때보다 쉬운 온라인 비디오 삽입:** 슬라이드에 Vimeo 또는 YouTube 비디오를 삽입해야 하나요? 비디오 페이지 링크만 있으면 됩니다. [자세히 알아보기](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p125">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="d4a04-296">**더 나은 변신:** 셰이프에 이름을 지정하여 셰이프의 모핑 과정을 더 효율적으로 관리하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-296">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="d4a04-297">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-297">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="d4a04-298">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-298">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="d4a04-299">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-299">Switching between them has never been easier.</span></span> [<span data-ttu-id="d4a04-300">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-300">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="d4a04-301">**온라인 비디오의 새로운 홈:** 조직의 모든 사람이 볼 수 있도록 비디오를 Microsoft Stream에 저장하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-301">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="d4a04-302">비디오 링크를 삽입하고 파일 크기의 일부로 멀티미디어 프레젠테이션을 즐겨보세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-302">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="d4a04-303">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-303">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

### <a name="project"></a><span data-ttu-id="d4a04-304">Project</span><span class="sxs-lookup"><span data-stu-id="d4a04-304">Project</span></span>

- <span data-ttu-id="d4a04-305">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-305">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="d4a04-306">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-306">Switching between them has never been easier.</span></span> [<span data-ttu-id="d4a04-307">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-307">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="d4a04-308">Visio</span><span class="sxs-lookup"><span data-stu-id="d4a04-308">Visio</span></span>

- <span data-ttu-id="d4a04-p130">**깨진 Excel 링크 해결:** 데이터 시각화 도우미 다이어그램에 연결된 Excel 통합 문서를 찾을 수 없습니까? 링크를 다시 연결하면 정상으로 돌아옵니다. [자세히 알아보기](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p130">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="d4a04-312">**기본적으로 제공되는 Azure 스텐실:** 수십 개의 Azure 스텐실을 사용하여 클라우드 앱을 디자인하거나 아키텍처를 계획합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-312">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="d4a04-313">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-313">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="d4a04-314">**놀랄 만한 수준의 데이터 순서도:** 데이터 시각화 도우미 순서도를 위한 멋진 새 레이아웃은 깔끔하고 정돈되어 있으며 이해하기 쉽습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-314">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="d4a04-315">디자인 탭을 클릭하여 옵션을 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-315">Click the Design tab for options.</span></span>

- <span data-ttu-id="d4a04-316">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-316">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="d4a04-317">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-317">Switching between them has never been easier.</span></span> [<span data-ttu-id="d4a04-318">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-318">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="d4a04-319">**프로세스 다이어그램을 Word로 내보내기:** Word 문서에 셰이프 및 메타데이터 등의 다이어그램 콘텐츠를 자동으로 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-319">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="d4a04-320">그런 후 문서를 사용자 지정하여 프로세스 지침 및 작업 설명서를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-320">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="d4a04-321">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-321">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="d4a04-322">**Power BI에서 Visio 시각적 개체 내보내기** Power BI 보고서를 PDF, PowerPoint 파일 등으로 내보낼 때 Power BI용 Visio 시각적 개체가 올바르게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-322">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="d4a04-323">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-323">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="d4a04-324">Word</span><span class="sxs-lookup"><span data-stu-id="d4a04-324">Word</span></span>

- <span data-ttu-id="d4a04-p136">**잉크 편집기로 자연스럽게 편집 가능:** 펜을 사용하여 단일 스트로크로 단어를 분할 또는 조인하거나, 새 줄을 추가하거나, 단어를 삽입할 수 있습니다. [자세한 정보](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p136">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="d4a04-p137">**평범한 문서를 훌륭한 문서로 개선하기:** 모든 장치에서 문서가 잘 보이도록 공유하기 쉬운 대화형의 웹 페이지로 변환합니다. [자세히 알아보기](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p137">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="d4a04-329">**\@@멘션으로 주의 끌기:** 메모에 @멘션을 사용하여 입력이 필요하다는 사실을 동료들에게 알립니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-329">**Get Their Attention with \@Mentions:** Use @mentions in comments to let others know when you need their input.</span></span> [<span data-ttu-id="d4a04-330">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-330">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="d4a04-p139">**라인 포커스로 가독성 개선:** 부드럽게 줄 단위로 문서를 넘길 수 있습니다. 한 번에 볼 때 1줄, 2줄, 또는 5줄에 포커스를 두도록 조정합니다. [자세히 알아보기](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p139">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="d4a04-334">**해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="d4a04-334">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="d4a04-335">파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-335">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="d4a04-336">**변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-336">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="d4a04-337">**콘텐츠 도달 범위 늘리기:** 접근성 높은 문서를 만들어야 하나요?</span><span class="sxs-lookup"><span data-stu-id="d4a04-337">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="d4a04-338">진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-338">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="d4a04-339">검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-339">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="d4a04-340">**더 많은 페이지 색상을 사용하도록 학습 도구 모드에 추가 지원 제공:** Word의 학습 도구에 페이지 테마 색상에 대한 지원이 추가되어, 페이지의 배경색을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-340">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="d4a04-341">많은 사람들이 흑백 또는 검정색 배경으로 읽는 것에 어려움을 느끼고 있으므로 PC 및 Mac의 Word에서 색상 선택을 확장했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-341">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="d4a04-342">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-342">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="d4a04-343">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-343">Switching between them has never been easier.</span></span> [<span data-ttu-id="d4a04-344">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-344">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="d4a04-345">**더 이상 혼란을 겪지 마세요:** Mac에서 자주 사용되는 기능이 Windows에 도입되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-345">**Say goodbye to distractions:** A favorite Mac feature comes to Windows.</span></span> <span data-ttu-id="d4a04-346">보기 메뉴에서 포커스로 전환하면 주의를 산만하게 하는 요인들을 제거하고 작업에 집중할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-346">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> [<span data-ttu-id="d4a04-347">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-347">Learn more</span></span>](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

### <a name="office-suite"></a><span data-ttu-id="d4a04-348">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d4a04-348">Office Suite</span></span>

- <span data-ttu-id="d4a04-349">**Microsoft Teams 설치:** Teams가 Office 365 ProPlus의 기존 설치에 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-349">**Installation of Microsoft Teams:** Teams is added to existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="d4a04-350">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-350">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

- <span data-ttu-id="d4a04-351">**변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-351">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="d4a04-352">**개인 정보 제어:** 진단 데이터 및 연결된 환경에 대한 업데이트 및 향상된 신규 컨트롤 작업</span><span class="sxs-lookup"><span data-stu-id="d4a04-352">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="d4a04-353">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-353">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="d4a04-354">**Office 아이콘이 새롭게 단장했습니다.** 간단하고 강력하며 지능적인 Office 환경을 반영하여 Office 아이콘이 다시 디자인되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-354">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="d4a04-355">**Microsoft Teams 설치:** Microsoft Teams는 기본적으로 Office 365 ProPlus 기존 설치에 설치됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-355">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="d4a04-356">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-356">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="d4a04-359">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-359">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="d4a04-360">Excel</span><span class="sxs-lookup"><span data-stu-id="d4a04-360">Excel</span></span>

- <span data-ttu-id="d4a04-361">도형 또는 양식 컨트롤에 할당된 매크로가 잘못된 오류 메시지를 표시하거나 잘못된 대상 범위에서 작동하는 Excel의 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-361">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="d4a04-362">다른 사용자와의 공동 작성 세션에서 실패할 수 있는 동안 피벗 테이블의 정렬 방식을 변경하고 새로 고치는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-362">Fixed an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could cause it to fail.</span></span>

- <span data-ttu-id="d4a04-363">셀을 삽입하거나 삭제하는 경우 폭포 차트와 깔때기형 차트가 테이블로 동기화되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-363">Fixed an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="d4a04-364">사용자에게 통합 문서를 다시 열어서 변경 내용을 적용하라는 메시지가 표시되는 Excel의 병합 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-364">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="d4a04-365">다른 사용자와 공동 작성하는 경우 표의 옆에 잘라내어 붙여 넣는 작업이 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-365">Fixed an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

### <a name="outlook"></a><span data-ttu-id="d4a04-366">Outlook</span><span class="sxs-lookup"><span data-stu-id="d4a04-366">Outlook</span></span>

- <span data-ttu-id="d4a04-367">사서함을 기본 인증에서 최신 인증으로 업그레이드한 사용자가 Outlook 프로필에 연결된 잘못된 계정으로 끝나는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-367">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="d4a04-368">POP3 사용자의 하위 집합에서 설정에 관계없이 일반 텍스트로 서식이 지정된 모든 전자 메일을 표시하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-368">Fixed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="d4a04-369">이 수정은 HTML 서식이 지정된 메시지의 보기를 복원합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-369">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="d4a04-370">사용자가 화면 판독기를 통해 위치 제안에 액세스할 수 없게 된 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-370">Fixed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="d4a04-371">일부 사용자가 Outlook에 대한 클라우드 설정을 검색할 때 인증 오류가 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-371">Fixed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="d4a04-372">대리인이 이미 모임 요청에 응답했는지 여부에 대해 관리자에게 모호함을 야기하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-372">Fixed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="d4a04-373">특정 시나리오에서 Outlook 사용자가 “비밀번호 필요”상태에 멈춰있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-373">Fixed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="d4a04-374">현재 폴더 검색이 간헐적으로 실패하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-374">Fixed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="d4a04-375">사용자에게 회의실의 가용 시간 이외의 시간에 발생한 모임에 대해 회의실 제안이 나타나는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-375">Fixed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="d4a04-376">사용자가 클라우드 첨부를 사용할 때 “해당 파일을 찾을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-376">Fixed temporary service issue that caused users to see the error "Cannot find this file.</span></span> <span data-ttu-id="d4a04-377">경로 및 파일 이름이 맞는지 확인하세요”의 오류 메시지가 나타나는 일시적인 서비스 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-377">Verify the path and file name are correct" when using cloud attachments.</span></span> [<span data-ttu-id="d4a04-378">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-378">Learn More</span></span>](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- <span data-ttu-id="d4a04-379">Outlook에서 OneDrive 또는 Sharepoint로 업로드 된 파일의 이름이 밑줄로 인해 여러 개의 문자로 변경되는 오류가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-379">Fixed an issue that caused users to see uploaded files from Outlook to OneDrive or Sharepoint have the file name changed where several characters replaced by underscores.</span></span>

- <span data-ttu-id="d4a04-380">메일의 제목 줄이 너무 작을 경우 비영어 사용자를 위한 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-380">Fixed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d4a04-381">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d4a04-381">PowerPoint</span></span>

- <span data-ttu-id="d4a04-382">일부 추가 기능이 차트의 도형 주변에 예기치 않은 오류를 발생시키는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-382">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="d4a04-383">PowerPoint 비디오 컨트롤에 대해 액세스 가능한 이름을 복원하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-383">Fixed an issue to restore the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="d4a04-384">일부 애니메이션이 시작되지 않도록 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-384">Fixed an issue which could prevent some animations from starting</span></span>

### <a name="project"></a><span data-ttu-id="d4a04-385">Project</span><span class="sxs-lookup"><span data-stu-id="d4a04-385">Project</span></span>

- <span data-ttu-id="d4a04-386">Windows 7 사용자가 Project Web App 및 SharePoint 사이트에서 프로젝트를 열 수 있도록 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-386">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>


### <a name="visio"></a><span data-ttu-id="d4a04-387">Visio</span><span class="sxs-lookup"><span data-stu-id="d4a04-387">Visio</span></span>

- <span data-ttu-id="d4a04-388">Visio에서 SVG로 내보내기가 다양한 도형에서 작동하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-388">Export to SVG from Visio was not working for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="d4a04-389">Word</span><span class="sxs-lookup"><span data-stu-id="d4a04-389">Word</span></span>

- <span data-ttu-id="d4a04-390">사용자가 Word 문서에서 공동 작업하는 동안 오류 메시지를 받는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-390">Fixed an issue where users would get error messages while collaborating with others on a Word document.</span></span>

- <span data-ttu-id="d4a04-391">SharePoint 2016에 저장된 파일을 공유하려고 할 때 "죄송합니다. 어떤 요인으로 인해 이 파일을 공유할 수 없습니다."라는 메시지가 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-391">Fixed an issue which caused users to get the message "Sorry, something is preventing us from sharing this"  when trying to share files stored on SharePoint 2016.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d4a04-392">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d4a04-392">Office Suite</span></span>

- <span data-ttu-id="d4a04-393">일부 인스턴스에서 동기화 엔진 백업 Sharepoint 파일에 ‘저장됨’이 표시되지만 실제로 변경 내용이 저장되지 않은 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-393">Fixed an issue where in some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes.</span></span>

- <span data-ttu-id="d4a04-394">큰 트리뷰가 실패하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-394">Fixed an issue where large tree views were failing.</span></span>

- <span data-ttu-id="d4a04-395">히라가나와 한자에서 새로운 연호 "레이와"의 철자가 틀리거나 비문법적 표현으로 잘못 식별되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-395">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1902-august-13"></a><span data-ttu-id="d4a04-397">버전 1902: 8월 13일</span><span class="sxs-lookup"><span data-stu-id="d4a04-397">Version 1902: August 13</span></span>
<span data-ttu-id="d4a04-398">*버전 1902 (빌드 11328.20392)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-398">*Version 1902 (Build 11328.20392)*</span></span>

<span data-ttu-id="d4a04-399">보안 업데이트가 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)에 나열되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-399">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="d4a04-400">Excel: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-400">Excel: Non-security updates</span></span>
- <span data-ttu-id="d4a04-401">표에서 필터링된 슬라이서와 필터링되지 않은 슬라이서 모두에 대해 필터 지우기 아이콘이 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-401">Fixed an issue where the clear filter icon was shown for both filtered and unfiltered Slicers in tables.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="d4a04-402">Outlook: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-402">Outlook: Non-security updates</span></span>
- <span data-ttu-id="d4a04-403">사서함을 기본 인증에서 최신 인증으로 업그레이드한 사용자가 Outlook 프로필에 연결된 잘못된 계정으로 끝나는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-403">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="d4a04-404">PowerPoint: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-404">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="d4a04-405">문서에서 다른 사용자와 공동 작업 중에 응용 프로그램이 예기치 않게 종료되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-405">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="d4a04-406">Word: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-406">Word: Non-security updates</span></span>
- <span data-ttu-id="d4a04-407">필드를 업데이트하는 동안 VBA가 느려지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-407">Fixed an issue which VBA updating fields were slow.</span></span>
- <span data-ttu-id="d4a04-408">일부 DOC 파일을 열 때 파일이 손상되었다고 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-408">Fixed in issue when opening some DOC file, it says it is corrupt.</span></span>
- <span data-ttu-id="d4a04-409">문서에서 다른 사용자와 공동 작업 중에 응용 프로그램이 예기치 않게 종료되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-409">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="d4a04-410">Office 제품군: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-410">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="d4a04-411">특정한 경우에 Office JavaScript 라이브러리에서 API 설정이 수행되지 않는 문제가 해결되었습니다. [자세한 정보](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span><span class="sxs-lookup"><span data-stu-id="d4a04-411">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>

## <a name="version-1902-july-09"></a><span data-ttu-id="d4a04-412">버전 1902: 7월 9일</span><span class="sxs-lookup"><span data-stu-id="d4a04-412">Version 1902: July 09</span></span>
<span data-ttu-id="d4a04-413">*버전 1902(빌드 11328.20368)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-413">*Version 1902 (Build 11328.20368)*</span></span>

<span data-ttu-id="d4a04-414">보안 업데이트가 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)에 나열됨</span><span class="sxs-lookup"><span data-stu-id="d4a04-414">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


### <a name="excel-non-security-updates"></a><span data-ttu-id="d4a04-415">Excel: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-415">Excel: Non-security updates</span></span>
- <span data-ttu-id="d4a04-416">필터링된 Excel 행을 삭제하는 경우 지나치게 속도가 느려지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-416">Fixed extreme slowness Issue in deleting filtered excel rows.</span></span>
- <span data-ttu-id="d4a04-417">두 손가락으로 스크롤하면 회색 직사각형이 워크시트에 그려지고 Excel이 중단되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-417">Fixed two finger scrolling causes grey rectangles to be drawn over worksheet and Excel to hang.</span></span>


### <a name="outlook-non-security-updates"></a><span data-ttu-id="d4a04-418">Outlook: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-418">Outlook: Non-security updates</span></span>
- <span data-ttu-id="d4a04-419">중국어 단어를 선택할 수 있도록 IME 후보 창이 열려 있도록 유지하는 것이 아니라 가끔씩 Outlook에서 영어 핀인 문자를 삽입하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-419">Addresses an issue that caused users to occasionally see Outlook inserting English pinyin letters rather than keeping the IME candidate window open to allow the selection of Chinese words.</span></span>
- <span data-ttu-id="d4a04-420">해당 회의실의 가용성을 초과하여 예약된 모임의 회의실이 제안되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-420">Addresses an issue that caused users to see rooms being suggested for meetings that were scheduled outside of that room's availability.</span></span>
- <span data-ttu-id="d4a04-421">사용자가 대신에 마스터 되풀이 항목을 열기 위해 모임 되풀이 항목에 대한 예외 열기를 시도하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-421">Addresses an issue that caused users attempting to open an exception to a meeting series to instead open the master series.</span></span>
- <span data-ttu-id="d4a04-422">지운 편지함 폴더의 항목에 대해 만료 날짜가 잘못 계산되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-422">Addresses an issue that caused users to see expiry dates being calculated incorrectly for items in Deleted Items folder.</span></span>


### <a name="teams-non-security-updates"></a><span data-ttu-id="d4a04-423">Teams: Excel: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-423">Teams: Non-security updates</span></span>

- <span data-ttu-id="d4a04-424">이제 Teams 설치자가 설치 완료 후 자동 실행을 해제하는 정책을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-424">Teams installer has now available Policy to turn off auto-launch after installation is completed.</span></span>


### <a name="visio-non-security-updates"></a><span data-ttu-id="d4a04-425">Visio: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-425">Visio: Non-security updates</span></span>

- <span data-ttu-id="d4a04-426">riched20.dll을 찾을 수 없다고 표시된 오류 메시지에서 보듯이, Visio용 ActiveX 솔루션이 Office 365에서 작동하지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-426">Addresses issue related to ActiveX solutions for Visio not working with Office 365, expressed as an error message stating that riched20.dll can't be found.</span></span>


### <a name="word--non-security-updates"></a><span data-ttu-id="d4a04-427">Word: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-427">Word:  Non-security updates</span></span>

- <span data-ttu-id="d4a04-428">서식 파일 검색 창을 비활성화할 수 있도록 GPO 설정이 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-428">Fixed GPO setting to disable template search bar</span></span>
- <span data-ttu-id="d4a04-429">오프라인 상태에서 서버 전용 문서를 편집 한 후 일부 변경 내용이 분실되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-429">Fixed an issue where users could lose some of their changes after being offline and editing a document that was server-only.</span></span>
- <span data-ttu-id="d4a04-430">문서 속성에 빠른 문서 요소를 사용하는 경우 성능이 향상되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-430">Improved performance when enabling Quick Parts for Document properties</span></span>
- <span data-ttu-id="d4a04-431">서버의 첫 번째 다운로드 수정 버전이 실패하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-431">Fixed an issue where first download revision from the server might fail</span></span>


### <a name="office-suite--non-security-updates"></a><span data-ttu-id="d4a04-432">Office 제품군: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-432">Office Suite:  Non-security updates</span></span>

- <span data-ttu-id="d4a04-433">추가 Office 제품이나 언어 팩을 설치할 때 공유 컴퓨터 활성화를 사용하는 장치가 예기치 않게 사용자 기반 활성화로 되돌아가는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-433">Addressed an issue where devices using shared computer activation may unexpectedly revert to user-based activation upon installation of additional Office products or language packs.</span></span>
- <span data-ttu-id="d4a04-434">프록시 인증이 SYSTEM으로 실행될 때 Office 업데이트를 차단하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-434">Fixed an issue that blocked Office Updates when proxy authentication runs as SYSTEM.</span></span>
- <span data-ttu-id="d4a04-435">Office 추가 기능이 사용자 프로필 변경 내용에서 사라지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-435">Fixes to address Office add-ins disappearing on user profile changes.</span></span>


## <a name="version-1902-june-11"></a><span data-ttu-id="d4a04-436">버전 1902: 6월 11일</span><span class="sxs-lookup"><span data-stu-id="d4a04-436">Version 1902: June 11</span></span>
<span data-ttu-id="d4a04-437">*버전 1902(빌드 11328.20318)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-437">*Version 1902 (Build 11328.20318)*</span></span>
<br/><span data-ttu-id="d4a04-438">보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)에 나열됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-438">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="d4a04-439">Excel: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-439">Excel: Non-security updates</span></span>
 - <span data-ttu-id="d4a04-440">XML 맵이 포함된 파일을 PDF로 저장할 때 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-440">Resolved an issue that caused a crash when saving a file containing an XML map to PDF.</span></span>
 - <span data-ttu-id="d4a04-441">잘못된 시트 이름이 포함된 통합 문서를 로드할 때 외부 링크가 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-441">Resolved an issue that caused external links to be removed when workbooks containing invalid sheet names are loaded.</span></span>
 - <span data-ttu-id="d4a04-442">Excel에서 카메라 도구를 사용하면 스프레드시트가 중단되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-442">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="d4a04-443">셀을 삽입하거나 삭제하는 경우 폭포 차트와 깔때기형 차트가 테이블로 동기화되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-443">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>
 - <span data-ttu-id="d4a04-444">테이블에 따라 다른 시트의 배열식을 사용하여 워크시트 계산을 하는 동안 데이터 테이블을 다시 계산할 때 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-444">Resolved a crash when a data table is recalculated during Worksheet Calculate with an array formula on another sheet depending on the table.</span></span> 
 - <span data-ttu-id="d4a04-445">파일을 체크 아웃 하지 않고 암호로 보호 된 통합 문서를 SharePoint에서 열지 못하도록 하는 문제가 해결 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-445">Resolved an issue that prevented password protected workbooks from being opened from SharePoint without checking out file first.</span></span>
 - <span data-ttu-id="d4a04-446">자동 저장을 공유하거나 토글하는 경우 BeforeSave 이벤트를 처리하도록 변경되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-446">A change was made to ensure the BeforeSave event is handled when sharing or toggling AutoSave.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="d4a04-447">Outlook: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-447">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="d4a04-448">"그룹화 기준"에 두 번째 조건을 추가할 때 고객에게 작업이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-448">Addressed an issue that caused customers to see their tasks seem to disappear when adding a 2nd condition to "Group by".</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="d4a04-449">Word: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-449">Word: Non-security updates</span></span>
 - <span data-ttu-id="d4a04-450">문서에 대해 현재 공동 작업 중인 문서를 공유하면 확장자가 .asd인 파일이 생성되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-450">Fixed when sharing a document which is currently being collaborated upon the document produces attachment with .asd extension.</span></span>
 - <span data-ttu-id="d4a04-451">메모가 임의의 작성자에 속하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-451">Fixed an issue with comments get attributed to random authors.</span></span>
 - <span data-ttu-id="d4a04-452">문서를 확인할 때 서명 제거에 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-452">Fixed an issue in the remove signature when checking out a document.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="d4a04-453">Office 제품군: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-453">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="d4a04-454">"실행 취소" 작업 후 VBA에서 잘못된 도형 채우기 상태를 보고할 때 발생하는 버그를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-454">This fixed a bug in VBA reporting incorrect shape fill state after an "undo" action.</span></span>


## <a name="version-1902-may-14"></a><span data-ttu-id="d4a04-455">버전 1902: 5월 14일</span><span class="sxs-lookup"><span data-stu-id="d4a04-455">Version 1902: May 14</span></span>
<span data-ttu-id="d4a04-456">*버전 1902(빌드 11328.20286)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-456">*Version 1902 (Build 11328.20286)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="d4a04-457">Excel: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-457">Excel: Non-security updates</span></span>
 -  <span data-ttu-id="d4a04-458">Excel에서 카메라 도구를 사용하면 스프레드시트가 중단되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-458">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="d4a04-459">차트 시트가 있는 비활성 창에서 마우스 스크롤 휠을 사용하면 충돌이 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-459">An issue that caused a crash when using the mouse scroll wheel on an in-active window with a chart sheet was fixed.</span></span>
 - <span data-ttu-id="d4a04-460">SharePoint에서 스프레드시트를 가져올 때 "예기치 않은 오류" 라는 메시지가 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-460">A problem that caused an "Unexpected Error" message to appear when importing a spreadsheet in SharePoint has been resolved.</span></span>
 - <span data-ttu-id="d4a04-461">규칙 및 사용자 지정 보기에 이름을 사용하는 조건부 서식이 포함된 통합 문서를 열 때 Excel이 중단되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-461">A problem that caused Excel to crash when opening a workbook containing conditional formatting that uses a Name for its rule and a custom view is applied has been resolved.</span></span>
 - <span data-ttu-id="d4a04-462">255자보다 긴 수식으로 데이터 유효성 검사를 사용하여 매크로를 실행하면 런타임 오류가 발생하기도 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-462">Macros using data validation with formulas longer than 255 characters may have produced run-time errors.</span></span> <span data-ttu-id="d4a04-463">이제 이 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-463">This issue has now been corrected.</span></span>
 - <span data-ttu-id="d4a04-464">다른 통합 문서에 연결된 피벗 테이블을 포함하는 파일이 느리게 로드되는 문제가 발생 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-464">A problem which caused files containing PivotTables linked to other workbooks to load slowly.</span></span> <span data-ttu-id="d4a04-465">이 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-465">This issue has been resolved.</span></span>
 - <span data-ttu-id="d4a04-466">HTML 파일을 열고 "파일 형식 및 확장명이 일치하지 않음" 오류가 수신되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-466">An issue with opening HTML files and receiving a "file format and extension do not match" error has been resolved.</span></span>
 - <span data-ttu-id="d4a04-467">비활성 창에서 마우스 휠을 스크롤할 때 발생하는 문제를 해결하기 위해 변경되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-467">A change has been made to resolve issues with mouse-wheel scrolling on inactive windows.</span></span>  

### <a name="outlook-non-security-updates"></a><span data-ttu-id="d4a04-468">Outlook: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-468">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="d4a04-469">마이그레이션된 항목의 일부 필드를 편집할 수 없는 문제를 처리합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-469">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="d4a04-470">PowerPoint: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-470">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="d4a04-471">드물게 사용자 변경 사항을 클라우드에 업로드할 때 PowerPoint가 중지되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-471">Fixed an issue that PowerPoint stops uploading user changes to the cloud in rare situations.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="d4a04-472">비즈니스용 Skype: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-472">Skype for Business: Non-security updates</span></span>
 - <span data-ttu-id="d4a04-473">Lync(비즈니스용 Skype)에서 참가자가 7 명 이상인 온라인 모임에서 모임 창이 사라질 수있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-473">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>
 - <span data-ttu-id="d4a04-474">다른 Office 응용 프로그램에 로그인할 때 사용하는 자격 증명으로 비즈니스용 Skype에 로그인하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-474">Sign into Skype for Business with credentials used to sign into another Office application.</span></span>
 - <span data-ttu-id="d4a04-475">공유 컴퓨터 인증으로 설치할 때 비즈니스용 Skype 앱을 적절하게 인증하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-475">Properly activate the Skype for Business app when installed with shared computer activation.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="d4a04-476">Visio: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-476">Visio: Non-security updates</span></span>
 - <span data-ttu-id="d4a04-477">Dynamic DPI 기능을 비활성화하여 Visio를 확장하는 타사 솔루션의 깨진 창 계층 문제를 초래하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-477">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="d4a04-478">Word: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-478">Word: Non-Security updates</span></span>
 - <span data-ttu-id="d4a04-479">SharePoint에서 추가된 관련 사용자를 편집하면 충돌할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-479">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>
 - <span data-ttu-id="d4a04-480">Word가 시작할 때 “리소스를 로드하지 못했습니다” 대화 상자가 표시되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-480">Fixed where the "Failed to load resource" dialog when Word launches.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="d4a04-481">Office 제품군: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-481">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="d4a04-482">이 문제는 Apache WebDAV 폴더에 파일을 저장할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-482">This is a fix for an issue where files cannot be saved to Apache WebDAV folders.</span></span>
 - <span data-ttu-id="d4a04-483">고객이 일부 클라우드 저장 파일을 열 때 Office가 갑자기 닫히는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-483">Fixes an issue where Office closes abruptly when customers open some cloud-stored files.</span></span>
 - <span data-ttu-id="d4a04-484">히라가나와 한자에서 새로운 연호 "레이와"의 철자가 틀리거나 비문법적 표현으로 잘못 식별되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-484">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
 - <span data-ttu-id="d4a04-485">Windows 10에서 최근 파일 목록이 많은 사용자에게 삭제된 것처럼 표시되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-485">Fixed an issue where the recent files list appeared to have been cleared for many users on Windows 10.</span></span>
 - <span data-ttu-id="d4a04-486">진행 중인 관리자 트리거 업데이트가 있는 경우에도 최종 사용자에게 Office 업데이트 비즈니스 막대가 표시되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-486">Fixed an issue that caused an end-user to see an Office Update business bar, even though there is an Admin-triggered update in progress.</span></span>
 - <span data-ttu-id="d4a04-487">간헐적으로 발생하는 빈 로그인 프롬프트와 관련된 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-487">Fixed an issues related to intermittent blank sign-in prompts.</span></span>
 

## <a name="version-1902-april-9"></a><span data-ttu-id="d4a04-488">버전 1902: 4월 9일</span><span class="sxs-lookup"><span data-stu-id="d4a04-488">Version 1902: April 9</span></span>
<span data-ttu-id="d4a04-489">*버전 1902(빌드 11328.20230)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-489">*Version 1902 (Build 11328.20230)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="d4a04-490">Excel: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-490">Excel: Non-Security updates</span></span>

- <span data-ttu-id="d4a04-491">정의된 이름으로 끝나는 수식이 포함된 셀에서 Tab 키를 누르면 다음 셀로 이동하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-491">Resolved an issue where pressing the Tab key would not move to the next cell when in a cell containing a formula ending in a defined name.</span></span>
- <span data-ttu-id="d4a04-492">셀 서식으로 인해 파일 크기가 불필요하게 커지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-492">Resolved an issue where cell formatting was causing the file size to grow unnecessarily.</span></span>
- <span data-ttu-id="d4a04-493">통합 문서 사이에 피벗 테이블을 자르고 붙여넣으면 함께 작업하는 다른 사람을 위한 피벗 테이블 없이 데이터가 붙여넣기되는 문제가 해결됨.</span><span class="sxs-lookup"><span data-stu-id="d4a04-493">Resolved an issue where cutting and pasting a PivotTable between workbooks may result in the data being pasted, without a PivotTable for others you are collaborating with.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="d4a04-494">Outlook: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-494">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="d4a04-495">시스템 작업 표시줄이 화면의 왼쪽이나 위쪽에 있을 때 윈도우가 올바른 위치에 나타나지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-495">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="d4a04-496">연락처 카드에 사진을 로드 할 때 고객에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-496">Addresses an issue that caused customers to experience a crash when loading pictures on the contact card.</span></span>
- <span data-ttu-id="d4a04-497">일부 고객이 Office 응용 프로그램을 시작할 때 충돌을 일으키는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-497">Addresses an issue that caused some customers to experience crashes when starting office applications.</span></span>
- <span data-ttu-id="d4a04-498">시스템 작업 표시줄이 화면의 왼쪽이나 위쪽에 있을 때 윈도우가 올바른 위치에 나타나지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-498">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="d4a04-499">마이그레이션된 항목의 일부 필드를 편집할 수 없는 문제를 처리합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-499">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="d4a04-500">Visio: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-500">Visio: Non-Security updates</span></span>

- <span data-ttu-id="d4a04-501">Dynamic DPI 기능을 비활성화하여 Visio를 확장하는 타사 솔루션의 깨진 창 계층 문제를 초래하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-501">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling the Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="d4a04-502">Word: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-502">Word: Non-Security updates</span></span>

- <span data-ttu-id="d4a04-503">파일이 읽기 전용 모드로 열리고 '정보'창에서 '다른 이름으로 저장'을 클릭하면 저장 UI가 표시되도록 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-503">If a file is opened in read-only mode and you click 'Save As' from the 'Info' pane, fixes issue so that the save UI is displayed.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="d4a04-504">Office 제품군: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-504">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="d4a04-505">Office 업데이트의 일부가 배달 최적화 피어 캐싱을 사용하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-505">Fixed an issue where parts of an Office update do not use Delivery Optimization peer caching.</span></span> [<span data-ttu-id="d4a04-506">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-506">Learn more</span></span>](https://docs.microsoft.com/windows/deployment/update/waas-delivery-optimization)
- <span data-ttu-id="d4a04-507">Office 배포 도구를 사용하여 Office를 설치하고 대소 문자가 일치하지 않는 경우, 제품이 제거되거나 활성화되지 않을 수 있는 버그를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-507">Fix to a bug that could lead to products being removed or not activated if Office was installed using the Office Deployment Tool and there was a case mis-match.</span></span>
- <span data-ttu-id="d4a04-508">Windows 10 (버전 1803 이상) 장치에서 과도한 로그인 프롬프트를 유발하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-508">Fixed an issue which was causing excessive sign-in prompts on Windows 10 (version 1803 or later) devices.</span></span>
- <span data-ttu-id="d4a04-509">링크된 그림을 다운로드 할 때 원인이 되는 고정 회귀의 중단</span><span class="sxs-lookup"><span data-stu-id="d4a04-509">Fixed regression that causes hangs when downloading linked pictures.</span></span>
- <span data-ttu-id="d4a04-510">Word, Excel, PowerPoint에 붙여넣은 대형 EMF 파일의 흐림 수정.</span><span class="sxs-lookup"><span data-stu-id="d4a04-510">Fixed blurriness of large EMF files pasted in Word, Excel, PowerPoint.</span></span>
- <span data-ttu-id="d4a04-511">몇가지 케이스에서 문서가 읽기전용으로 열리는 등 버전 기록 분석 논리에서 버그가 수정.</span><span class="sxs-lookup"><span data-stu-id="d4a04-511">Fixed the bug in version history parsing logic that in few cases caused the documents to be opened in read-only.</span></span>

## <a name="version-1902-march-12"></a><span data-ttu-id="d4a04-512">버전 1902: 3월 12일</span><span class="sxs-lookup"><span data-stu-id="d4a04-512">Version 1902: March 12</span></span>
<span data-ttu-id="d4a04-513">*버전 1902(빌드 11328.20158)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-513">*Version 1902 (Build 11328.20158)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="d4a04-514">Access: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-514">Access: Feature updates</span></span>

- <span data-ttu-id="d4a04-515">**연결된 테이블 새로 고침, 다시 연결 또는 제거** 업데이트된 연결된 테이블 관리자에서 모든 데이터 원본 및 연결된 테이블을 관리할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-515">**Refresh, relink, or remove linked tables:** The updated Linked Table Manager is the location for managing all data sources and linked tables.</span></span> [<span data-ttu-id="d4a04-516">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-516">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- <span data-ttu-id="d4a04-p154">**검은색으로 페인트, 회색으로 페인트:** Access의 모양을 원하는 만큼 자주 변경할 수 있습니다. 색상형, 진한 회색, 검은색 또는 흰색의 네 가지 테마 중에서 선택할 수 있습니다. [자세히 알아보기](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p154">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>
- <span data-ttu-id="d4a04-520">**새로운 모습의 Office:**  Office 앱의 아이콘이 최신 아이콘으로 업데이트되어 더 간편하고 접근성이 높아졌습니다. 또한 Office 앱에서 사용할 수 있는 풍부한 공동 작업 기능이 두드러지게 표시되도록 리본 디자인이 업데이트되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-520">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="d4a04-521">Excel: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-521">Excel: Feature updates</span></span>

- <span data-ttu-id="d4a04-522">**빠른 시작** 새로 디자인 된 시작 페이지는 최근에 열어 본 문서를 앞면과 가운데에 배치합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-522">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="d4a04-523">더 적은 클릭으로 파일로 이동하고 여기에서 계정 설정 또는 옵션을 엽니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-523">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="d4a04-524">**메모를 사용하여 공동 작업:** 기본 제공 회신 상자를 사용하여 스프레드시트에서 바로 대화를 진행합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-524">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box.</span></span> [<span data-ttu-id="d4a04-525">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-525">Learn more</span></span>](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- <span data-ttu-id="d4a04-526">**새로운 모습의 리본 아이콘:** 모든 기능은 동일하니 걱정하지 마세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-526">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="d4a04-527">새 아이콘은 모든 크기의 화면에서 잘 보입니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-527">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="d4a04-528">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-528">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="d4a04-p158">**필터가 적용된 SVG 삽입:** Office 사용자는 이제 필터가 적용된 SVG를 삽입할 수 있습니다. [자세히 알아보기](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p158">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="d4a04-p159">**그림 뒤에 있는 내용 표시:** 워크시트에 그림을 넣고, 사전 설정을 선택하고, 투명도 변경을 확인합니다. 바로 이 기능으로요! [자세히 알아보기](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p159">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="d4a04-534">**모든 가져오기 및 변환 팬 호출:** 가져오기 및 변환 작업을 많이 사용하는 편이라면 개선된 예제의 열 기능으로 유용하게 작업할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-534">**Calling all Get & Transform fans:** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved.</span></span> <span data-ttu-id="d4a04-535">또한 많은 커넥터도 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-535">And, many connectors have been improved as well.</span></span> [<span data-ttu-id="d4a04-536">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-536">Learn more</span></span>](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- <span data-ttu-id="d4a04-537">**고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-537">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="d4a04-538">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-538">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="d4a04-539">**빠른 조회** 더 빠른 답변을 얻을 수 있도록 VLOOKUP, HLOOKUP 및 MATCH 계산을 가속화했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-539">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster.</span></span> [<span data-ttu-id="d4a04-540">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-540">Learn more</span></span>](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a><span data-ttu-id="d4a04-541">Outlook: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-541">Outlook: Feature updates</span></span>

- <span data-ttu-id="d4a04-p163">**소리내어 읽기를 사용하여 전자 메일 듣기:** Outlook에서 텍스트를 강조 표시하며 전자 메일을 소리내어 읽어 줍니다. 소리내어 읽기를 설정하려면 접근성 설정으로 이동하세요. [자세히 알아보기](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p163">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read. To turn on Read Aloud, go to the Ease of Access settings. [Learn more](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span></span>
- <span data-ttu-id="d4a04-545">**핸즈 프리 입력:** 마이크가 있나요?</span><span class="sxs-lookup"><span data-stu-id="d4a04-545">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="d4a04-546">받아쓰기를 클릭하고 말하는 동안 Outlook에 입력되는 내용을 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-546">Click Dictate and watch Outlook type while you talk.</span></span> [<span data-ttu-id="d4a04-547">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-547">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="d4a04-548">**새로운 모습의 리본 아이콘:** 모든 기능은 동일하니 걱정하지 마세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-548">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="d4a04-549">새 아이콘은 모든 크기의 화면에서 잘 보입니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-549">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="d4a04-550">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-550">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="d4a04-551">**SMIME 암호화 및 서명된 전자 메일에서 기본적으로 외부 콘텐츠 다운로드 차단:** SMIME 프로토콜의 취약성으로 인해 Outlook이 SMIME을 통해 암호화되거나 서명된 메시지의 외부 콘텐츠 다운로드를 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-551">**Block download of external content by default in SMIME encrypted and signed emails:** Due to a vulnerability in the SMIME protocol - Outlook will block download of external content on messages that have been encrypted or signed over SMIME.</span></span> <span data-ttu-id="d4a04-552">사용자는 보안 취약성을 보호하기 위해 Outlook UI를 통해 한 번의 클릭으로 외부 콘텐츠를 다운로드할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-552">Users will not be able to single-click download external content through Outlook UI to protect from the security vulnerability.</span></span> <span data-ttu-id="d4a04-553">옵션 대화 상자에 사용자가 이전 동작으로 되돌릴 수 있도록 허용하는 새 옵션이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-553">There is a new option in the Options dialog to allow for users to revert to old behavior.</span></span>
- <span data-ttu-id="d4a04-554">**모임 전달 해제:** 참석자가 모임을 다른 사용자에게 전달하지 못하도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-554">**Turn off forwarding for a meeting:** Prevent attendees from forwarding your meeting to others.</span></span> <span data-ttu-id="d4a04-555">리본으로 이동한 후 응답 옵션을 클릭하면 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-555">Just go to the ribbon and click Response Options.</span></span> [<span data-ttu-id="d4a04-556">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-556">Learn more</span></span>](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- <span data-ttu-id="d4a04-p168">**일정 도우미의 사용자 제안:** 모임을 예약할 때 참석자가 추가하는 권장 사항을 참조하세요. 이제 일정 도우미와 받는 사람 줄 사이를 전환할 필요가 없습니다. [자세히 알아보기](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p168">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="d4a04-560">**더욱 간편해진 회의실 예약:** 둘 이상의 회의실 목록을 사용하여 회의실을 찾고, 선택한 회의실을 그대로 유지하면서 목록을 전환합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-560">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="d4a04-p169">**되풀이 범위의 새로운 기본값:** 되풀이 대화 상자에서 되풀이 범위의 기본값은 원래 "종료 날짜 없음"이었습니다. 이 기본값을 사용하면 기간이 긴 되풀이를 손쉽게 만들 수 있었지만, 시간이 지나면 손상될 가능성이 있었습니다. 기본값이 일정 관리의 권장 모범 사례를 따르도록, 이제 되풀이 대화 상자의 기본값이 "종료 날짜"로 변경됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-p169">**New default for range of recurrence:** For the Recurrence dialog, the range of recurrence used to default for "No end date". This facilitated the creation of long-running recurring series, which can become corrupted over time. We are updating the default for the Recurrence dialog to "End by", such that our default value matches recommended best practices for calendaring.</span></span>
- <span data-ttu-id="d4a04-p170">**Outlook 미리 알림 대화 상자에서 Teams 모임에 참가:** Outlook이 사용자에게 예정된 모임을 미리 알릴 때 예정된 모임이 Teams 온라인 모임인 경우 온라인 참석 단추를 표시합니다. 이는 Outlook 미리 알림 대화 상자의 비즈니스용 Skype 모임 참가 기능과 비슷합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-p170">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>
- <span data-ttu-id="d4a04-566">**지난 이벤트에 대한 미리 알림 표시 안 함:** 이벤트가 종료된 후에 이벤트의 미리 알림을 자동으로 해제하도록 일정을 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-566">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended.</span></span> [<span data-ttu-id="d4a04-567">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-567">Learn more</span></span>](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- <span data-ttu-id="d4a04-568">**안전한 링크 뒤에 URL 표시:** 안전한 링크는 전자 메일에 수신된 악의적인 URL로부터 보호하지만 원래 URL을 숨깁니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-568">**See the URL behind Safe Links:** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="d4a04-569">원래 URL을 보려면 URL에 마우스를 올리세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-569">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="d4a04-570">Advanced Threat Protection 라이선스가 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-570">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="d4a04-571">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-571">Learn more</span></span>](https://products.office.com/exchange/advance-threat-protection)
- <span data-ttu-id="d4a04-572">**확대/축소 및 고정:** 메시지를 읽을 때마다 확대/축소를 조정하지 않고, 모든 메시지에 사용할 기본값을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-572">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages.</span></span> [<span data-ttu-id="d4a04-573">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-573">Learn more</span></span>](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- <span data-ttu-id="d4a04-574">**메시지 암호화: 암호화 전용 IRM 정책:** Office 365 메시지 암호화 사용자를 위해 옵션 > 권한 메뉴에 새로운 암호화 전용 옵션이 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-574">**Message Encryption: encrypt-only IRM policy:** New encrypt-only option appears in the Options > Permissions menu for Office 365 Message Encryption users.</span></span> <span data-ttu-id="d4a04-575">이 옵션을 사용하여 메시지를 암호화하고 조직 내부 또는 외부의 원하는 사람에게 메시지를 보낼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-575">This option allows you to encrypt a message and send it to anyone, inside or outside your organization.</span></span>
- <span data-ttu-id="d4a04-576">**숨은 참조에 포함되어 있을 경우 표시되는 경고:** 내가 숨은 참조에 포함되어 있을 때 실수로 메일에 전체 회신하기 전에 숨은 참조 정보 팁이 경고를 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-576">**Warning when you've been BCC'ed:** The BCC infotip will warn you before you accidentally reply all to a mail that you've been blind carbon copied on.</span></span>
- <span data-ttu-id="d4a04-577">**더 스마트해진 받는 사람: 줄:** 받는 사람: 줄을 클릭하여 메시지에 주소를 지정하려고 하면 선택할 수 있는 추천 받는 사람이 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-577">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose.</span></span> <span data-ttu-id="d4a04-578">또한 사진도 확인할 수 있으므로 올바른 사람에게 보내는지도 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-578">Plus, you can see their picture, so you know yo’re sending to the right person.</span></span> [<span data-ttu-id="d4a04-579">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-579">Learn more</span></span>](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- <span data-ttu-id="d4a04-p176">**필터가 적용된 SVG 삽입:** Office 사용자는 이제 필터가 적용된 SVG를 삽입할 수 있습니다. [자세히 알아보기](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p176">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="d4a04-582">**고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-582">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="d4a04-583">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-583">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="d4a04-584">PowerPoint: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-584">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="d4a04-585">**빠른 시작** 새로 디자인 된 시작 페이지는 최근에 열어 본 문서를 앞면과 가운데에 배치합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-585">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="d4a04-586">더 적은 클릭으로 파일로 이동하고 여기에서 계정 설정 또는 옵션을 엽니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-586">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="d4a04-587">**핸즈 프리 입력:** 마이크가 있나요?</span><span class="sxs-lookup"><span data-stu-id="d4a04-587">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="d4a04-588">받아쓰기를 클릭하고 말하는 동안 PowerPoint에 입력되는 내용을 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-588">Click Dictate and watch PowerPoint type while you talk.</span></span> [<span data-ttu-id="d4a04-589">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-589">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="d4a04-590">**새로운 모습의 리본 아이콘:** 모든 기능은 동일하니 걱정하지 마세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-590">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="d4a04-591">새 아이콘은 모든 크기의 화면에서 잘 보입니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-591">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="d4a04-592">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-592">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="d4a04-593">**고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-593">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="d4a04-594">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-594">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="d4a04-595">**생생한 색상의 하이퍼링크:** 이제 파란색 외의 다양한 색상으로 하이퍼링크를 표시할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-595">**Hyperlinks in living color:** Hyperlinks aren't just blue anymore.</span></span> <span data-ttu-id="d4a04-596">원하는 글꼴 색을 적용해 보세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-596">Apply any font color you like.</span></span> [<span data-ttu-id="d4a04-597">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-597">Learn more</span></span>](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- <span data-ttu-id="d4a04-598">**슬라이드에 생동감 주기:** 화면에서 애니메이션 3D 그래픽을 삽입하여 심장 박동, 행성 궤도 및 공룡 난동 모습을 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-598">**Watch your slides come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen.</span></span> [<span data-ttu-id="d4a04-599">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-599">Learn more</span></span>](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- <span data-ttu-id="d4a04-p184">**스케치를 세련되게 변형:** 손으로 그린 텍스트와 도형을 세련된 다이어그램으로 바꾸어 드립니다. 시작하려면 잉크 스트로크만 선택하면 됩니다. [자세히 알아보기](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p184">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="d4a04-p185">**그림 뒤에 있는 내용 표시:** 워크시트에 그림을 넣고, 사전 설정을 선택하고, 투명도 변경을 확인합니다. 바로 이 기능으로요! [자세히 알아보기](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p185">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="d4a04-606">**멋진 슬라이드 만들기:** 잉크를 표준 도형 및 텍스트로 변환한 후, PowerPoint Designer에서 스마트한 슬라이드 디자인 아이디어를 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-606">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="d4a04-607">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-607">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- <span data-ttu-id="d4a04-608">**Microsoft Stream에 게시:** Microsoft Stream을 사용하여 조직 내에서 프레젠테이션을 비디오로 더 안전하게 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-608">**Publish to Microsoft Stream:** Share a presentation as a video more securely within your organization by using Microsoft Stream.</span></span> [<span data-ttu-id="d4a04-609">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-609">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="d4a04-610">**4K 비디오로 내보내기:** 프레젠테이션을 동영상으로 내보낼 때 4K 해상도를 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-610">**Export to 4K video:** When you export a presentation to video, 4K resolution is now an option.</span></span>  [<span data-ttu-id="d4a04-611">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-611">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="d4a04-p189">**필터가 적용된 SVG 삽입:** Office 사용자는 이제 필터가 적용된 SVG를 삽입할 수 있습니다. [자세히 알아보기](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p189">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="d4a04-614">**이제 큰 파일이 열리는 속도 향상:** OneDrive 또는 SharePoint에 저장된 파일을 열 때 이미지, 비디오 및 다른 큰 요소가 백그라운드에서 계속 다운로드됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-614">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="d4a04-615">Word: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-615">Word: Feature updates</span></span>

- <span data-ttu-id="d4a04-616">**빠른 시작** 새로 디자인 된 시작 페이지는 최근에 열어 본 문서를 앞면과 가운데에 배치합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-616">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="d4a04-617">더 적은 클릭으로 파일로 이동하고 여기에서 계정 설정 또는 옵션을 엽니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-617">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="d4a04-618">**핸즈 프리 입력:** 마이크가 있나요?</span><span class="sxs-lookup"><span data-stu-id="d4a04-618">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="d4a04-619">받아쓰기를 클릭하고 말하는 동안 Word에 입력되는 내용을 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-619">Click Dictate and watch Word type while you talk.</span></span> [<span data-ttu-id="d4a04-620">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-620">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="d4a04-p192">**문서에 생동감 주기:** 페이지에서 애니메이션 3D 그래픽을 삽입하여 심장 박동, 행성 궤도 및 공룡 난동 모습을 표시합니다. [자세히 알아보기](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p192">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="d4a04-623">**새로운 모습의 리본 아이콘:** 모든 기능은 동일하니 걱정하지 마세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-623">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="d4a04-624">새 아이콘은 모든 크기의 화면에서 잘 보입니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-624">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="d4a04-625">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-625">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="d4a04-p194">**그림 뒤에 있는 내용 표시:** 워크시트에 그림을 넣고, 사전 설정을 선택하고, 투명도 변경을 확인합니다. 바로 이 기능으로요! [자세히 알아보기](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p194">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="d4a04-p195">**필터가 적용된 SVG 삽입:** Office 사용자는 이제 필터가 적용된 SVG를 삽입할 수 있습니다. [자세히 알아보기](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p195">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="d4a04-631">**고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-631">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="d4a04-632">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-632">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="d4a04-p197">**LinkedIn의 도움을 받아 최상의 이력서 또는 CV를 작성하세요.** 이력서 도우미를 사용하여 지정된 직책에 대한 경력 사항, 추천 기술 등을 확인하세요. [자세한 정보](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span><span class="sxs-lookup"><span data-stu-id="d4a04-p197">**Write your best resume or CV with help from LinkedIn:** With Resume Assistant, see work experiences, suggested skills, and more for a given role. [Learn more](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="d4a04-635">Project: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-635">Project: Feature updates</span></span>

- <span data-ttu-id="d4a04-636">**작업 보드 카드에 자세한 정보 표시:** 제목만으로 이야기를 전달하지 못할 경우 중요한 세부 사항을 표시하도록 작업 보드 카드를 사용자 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-636">**See more info on Task Board cards:** When the title alone doesn’t tell the story, customize your Task Board cards to show all the most important details.</span></span> [<span data-ttu-id="d4a04-637">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-637">Learn more</span></span>](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- <span data-ttu-id="d4a04-638">**새로운 모습의 Office:**  Office 앱의 아이콘이 최신 아이콘으로 업데이트되어 더 간편하고 접근성이 높아졌습니다. 또한 Office 앱에서 사용할 수 있는 풍부한 공동 작업 기능이 두드러지게 표시되도록 리본 디자인이 업데이트되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-638">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="d4a04-639">Publisher: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-639">Publisher: Feature updates</span></span>

- <span data-ttu-id="d4a04-640">**새로운 모습의 Office:**  Office 앱의 아이콘이 최신 아이콘으로 업데이트되어 더 간편하고 접근성이 높아졌습니다. 또한 Office 앱에서 사용할 수 있는 풍부한 공동 작업 기능이 두드러지게 표시되도록 리본 디자인이 업데이트되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-640">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="d4a04-641">Visio: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-641">Visio: Feature updates</span></span>

- <span data-ttu-id="d4a04-642">**다음 다이어그램에서 상징적 순간 즐기기:** 분석, 예술, 경축, 얼굴, 스포츠 등에 대한 아이콘이 있는 새 스텐실 26가지 중에서 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-642">**Enjoy an iconic moment in your next diagram:** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span>
- <span data-ttu-id="d4a04-643">**새로운 모습의 Office:**  Office 앱의 아이콘이 최신 아이콘으로 업데이트되어 더 간편하고 접근성이 높아졌습니다. 또한 Office 앱에서 사용할 수 있는 풍부한 공동 작업 기능이 두드러지게 표시되도록 리본 디자인이 업데이트되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-643">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="d4a04-644">Office 제품군: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-644">Office Suite: Feature updates</span></span>

- <span data-ttu-id="d4a04-p199">**이제 Office 타사 응용 프로그램에서 office.js API를 사용하는 SVG 삽입 지원:** Office에서 추가 기능으로도 알려져 있는 타사 응용 프로그램에 SVG 삽입 기능이 제공되므로 SVG 개인 컬렉션을 Office에 연결할 수 있습니다. 개발자들은 Office.js API를 통해 이 기능을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-p199">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>
- <span data-ttu-id="d4a04-648">**Microsoft Teams 설치:** Microsoft Teams는 기본적으로 Office 365 ProPlus 기존 설치에 설치됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-648">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="d4a04-649">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-649">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a><span data-ttu-id="d4a04-650">비즈니스용 Skype: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-650">Skype for Business: Feature updates</span></span>

- <span data-ttu-id="d4a04-651">**고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-651">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="d4a04-652">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-652">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a><span data-ttu-id="d4a04-653">Teams: 기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-653">Teams: Feature updates</span></span>

- <span data-ttu-id="d4a04-654">**고화질 디스플레이 지원 개선:** 여러 개의 모니터 또는 노트북 도크를 사용하는 경우 각 디스플레이의 배율 설정이 달라도 모든 디스플레이에서 Office 앱이 깔끔하게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-654">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="d4a04-655">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d4a04-655">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a><span data-ttu-id="d4a04-656">버전 1808: 2월 12일</span><span class="sxs-lookup"><span data-stu-id="d4a04-656">Version 1808: February 12</span></span>
<span data-ttu-id="d4a04-657">*버전 1808(빌드 10730.20280)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-657">*Version 1808 (Build 10730.20280)*</span></span> 

### <a name="access-non-security-updates"></a><span data-ttu-id="d4a04-658">Access: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-658">Access: Non-Security updates</span></span> 

- <span data-ttu-id="d4a04-659">이 업데이트는 Access에 대한 새로운 일본 시간대 지원을 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-659">This update adds support for new Japanese eras to Access.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="d4a04-660">Outlook: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-660">Outlook: Non-Security updates</span></span> 

- <span data-ttu-id="d4a04-661">더 이상 존재하지 않는 폴더를 참조하는 규칙이 포함된 사용자로 인해 발생하는 문제를 해결합니다. 규칙을 관리하려 할 때 오류가 표시됩니다. 클라이언트 측 규칙 실행 실패를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="d4a04-661">Addresses an issue that caused users with rules that refer to a folder that no longer exist to see an error when trying to manage rules and to see client-side rules fail to run.</span></span>
- <span data-ttu-id="d4a04-662">캐시된 대리인 사서함을 가진 사용자로 인해 예측할 수 없는 간격마다 주기적인 중단이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-662">Addresses an issue that caused users with cached delegate mailboxes to encounter frequent hangs at unpredictable intervals.</span></span>
- <span data-ttu-id="d4a04-663">회의의 종료 시간이 다음날 자정으로 설정되어 종일 회의가 일부 보기에서 의도한 날보다 하루 더 많이 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-663">Addresses an issue that caused All Day Meetings to appear to span one more day than intended in some views due to the end time of the meeting being set to midnight of the following day.</span></span>
- <span data-ttu-id="d4a04-664">일본 시간대를 참조하는 새 약속 또는 회의를 만들 때 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-664">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="d4a04-665">Office 제품군: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-665">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="d4a04-666">[O365 Office 중앙 집중식 배포](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment)를 사용하여 배포된 추가 기능이 중지되고 사용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-666">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1808-january-8"></a><span data-ttu-id="d4a04-667">버전 1808: 1월 8일</span><span class="sxs-lookup"><span data-stu-id="d4a04-667">Version 1808: January 8</span></span>
<span data-ttu-id="d4a04-668">*버전 1808 (빌드 10730.20264)*</span><span class="sxs-lookup"><span data-stu-id="d4a04-668">*Version 1808 (Build 10730.20264)*</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="d4a04-669">Outlook: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-669">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="d4a04-670">일정 동기화 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-670">Fixed an issue that caused users to experience calendar synchronization errors.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="d4a04-671">Word: 비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="d4a04-671">Word: Non-security updates</span></span>

- <span data-ttu-id="d4a04-672">열기 성능을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-672">Improve open performance.</span></span>


> [!NOTE]
> <span data-ttu-id="d4a04-673">Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d4a04-673">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
