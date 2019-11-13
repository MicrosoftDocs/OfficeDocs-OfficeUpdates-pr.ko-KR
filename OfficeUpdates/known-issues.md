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
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="a5179-103">Office 365 ProPlus의 알려진 문제</span><span class="sxs-lookup"><span data-stu-id="a5179-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="a5179-104">이 알려진 문제는 월별 채널, SACT 및 SAC 업데이트를 비롯한 Office 365용 Visio Pro, Project Online 데스크톱 클라이언트 및 Office 365 Business 그리고 2019년 Office 365 ProPlus에 포함된 비보안 업데이트에 관한 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-104">These known issues provide information about non-security updates that are included in Monthly Channel, SACT and SAC updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

<span data-ttu-id="a5179-105">이 표에서는 현재 진행 중인 문제와 해결된 문제에 대한 요약을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="a5179-106">아래의 표에는 조사 중인 중요한 문제를 업데이트할 것입니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-106">We will update the table below with significant issues we are investigating.</span></span>

> [!NOTE]
>- <span data-ttu-id="a5179-107">이 목록은 포괄적이지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-107">This list is not comprehensive.</span></span>
>- <span data-ttu-id="a5179-108">해결됨으로 표시된 채널이 아닌 채널에서 문제가 발생하는 경우 곧 해결을 기대할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-108">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="a5179-109">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="a5179-109">Learn more</span></span>](https://docs.microsoft.com/ko-KR/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="a5179-110">해결된 문제는 해당 채널 페이지에도 문서화되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-110">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="a5179-111">마지막 업데이트 날짜: 2019년 11월 12일</span><span class="sxs-lookup"><span data-stu-id="a5179-111">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="a5179-112">Excel</span><span class="sxs-lookup"><span data-stu-id="a5179-112">Excel</span></span>

- <span data-ttu-id="a5179-113">OneDrive에서 파일을 개체로 삽입하는 경우 발생 하는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-113">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="a5179-114">**해결됨**: 월간 버전 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a5179-114">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a5179-115">이전 버전의 Office에서 만든 통합 문서를 현재 버전의 Office에서 열었을 때 Excel이 중단될 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-115">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="a5179-116">**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20436), SAC 버전 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="a5179-116">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="a5179-117">범위를 삭제한 후 입력된 값이 표시되는 데 지연이 되는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-117">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="a5179-118">**해결됨**: SAC 버전 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="a5179-118">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="a5179-119">스크롤 후 셀을 선택하면 잘못된 셀이 선택되었던 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-119">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="a5179-120">**조사 중**: SACT</span><span class="sxs-lookup"><span data-stu-id="a5179-120">**Investigating**: SACT</span></span> <br><span data-ttu-id="a5179-121">**해결됨**: 월간 버전 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a5179-121">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a5179-122">시리즈 컬렉션을 변경할 때 분산형 라인 차트가 제대로 렌더링되지 않을 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-122">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="a5179-123">**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="a5179-123">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="a5179-124">Outlook</span><span class="sxs-lookup"><span data-stu-id="a5179-124">Outlook</span></span>

- <span data-ttu-id="a5179-125">보조 Exchange 계정을 추가할 때 일부 사용자가 만들어진 중복된 특수 폴더를 보게 하였던 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-125">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="a5179-126">**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a5179-126">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388)</span></span>

- <span data-ttu-id="a5179-127">메모리 누수를 발생시킬 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-127">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="a5179-128">**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20388), SAC 버전 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="a5179-128">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388)</span></span>

- <span data-ttu-id="a5179-129">보조 Exchange 계정을 추가할 때 일부 사용자가 만들어진 중복된 특수 폴더를 보게 하였던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-129">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="a5179-130">**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a5179-130">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388)</span></span>

- <span data-ttu-id="a5179-131">사용자가 Skype에서 '부재 중 대화' 메시지를 받을 시 때때로 충돌이 발생할 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-131">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="a5179-132">**해결됨**: 월간 버전 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a5179-132">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a5179-133">DisableBGSave를 사용하도록 설정된 기기에서 첨부 파일을 열 때 일반적인 ""작업을 수행하지 못했습니다" 오류가 발생하는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-133">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="a5179-134">**해결됨**: 월간 버전 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a5179-134">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a5179-135">cid의 링크 관련 문제를 확인했습니다. 이미지 (Outlook 전자 메일 기반 이미지)가 나누어질 수 없음.</span><span class="sxs-lookup"><span data-stu-id="a5179-135">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="a5179-136">**해결됨**: SACT 버전 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a5179-136">**Resolved**: SACT Version 1908 (11929.20396)</span></span>

- <span data-ttu-id="a5179-137">S/MIME 암호화 전자 메일을 보내려고 할 때 잘못된 오류 메시지를 발생시킬 수 있었던 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-137">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="a5179-138">**해결됨**: 월간 버전 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a5179-138">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a5179-139">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a5179-139">PowerPoint</span></span>

- <span data-ttu-id="a5179-140">하이퍼링크를 사용하여 텍스트를 붙여넣을 때 하이퍼링크를 만들지 못하게 하였던 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-140">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="a5179-141">**해결됨**: 월간 버전 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a5179-141">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a5179-142">슬라이드 마스터 및 슬라이드 레이아웃에서 머리글/바닥글/슬라이드 번호의 플레이스홀더에 텍스트를 붙여 넣은 후 TextRanges를 중단시킬 수 있었던 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-142">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="a5179-143">**해결됨**: 월간 버전 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a5179-143">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a5179-144">Win7에서 모든 앱의 리본 메뉴에서 도형 갤러리 삽입을 표시하는 데 약 4초가 걸리는 성능 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-144">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="a5179-145">**해결됨**: 월간 버전 1910 (12130.20272), SACT 버전 1908 (11929.20396), SAC 버전 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="a5179-145">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="a5179-146">Project</span><span class="sxs-lookup"><span data-stu-id="a5179-146">Project</span></span>

- <span data-ttu-id="a5179-147">읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-147">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="a5179-148">**해결됨**: 월간 버전 1910 (12130.20344), SACT 버전 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a5179-148">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388)</span></span>

### <a name="word"></a><span data-ttu-id="a5179-149">Word</span><span class="sxs-lookup"><span data-stu-id="a5179-149">Word</span></span>
- <span data-ttu-id="a5179-150">OneDrive에서 파일을 개체로 삽입하는 경우 발생 하는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-150">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="a5179-151">**해결됨**: 월간 버전 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a5179-151">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="a5179-152">Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="a5179-152">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
