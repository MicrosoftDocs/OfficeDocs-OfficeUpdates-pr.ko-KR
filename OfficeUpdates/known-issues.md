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
ms.openlocfilehash: 7c24098c7a160c3d6391bc8e8e51a73d69c44b0c
ms.sourcegitcommit: a5da36df390868d76bddfc78e9481ed8e9c5b673
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/26/2019
ms.locfileid: "37275499"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="3b955-103">Office 365 ProPlus의 알려진 문제</span><span class="sxs-lookup"><span data-stu-id="3b955-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="3b955-104">이 알려진 문제는 월별 채널, SACT 및 SAC 업데이트를 비롯한 Office 365용 Visio Pro, Project Online 데스크톱 클라이언트 및 Office 365 Business 그리고 2019년 Office 365 ProPlus에 포함된 비보안 업데이트에 관한 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, including Visio Pro for Office 365 and Project Online Desktop Client.</span></span>

<span data-ttu-id="3b955-105">이 표에서는 현재 진행 중인 문제와 해결된 문제에 대한 요약을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="3b955-106">아래의 표에는 조사 중인 중요한 문제를 업데이트할 것입니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-106">We will update the table below with significant issues we are investigating.</span></span>

 > [!NOTE]
 >- <span data-ttu-id="3b955-107">이 목록은 포괄적이지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-107">This list is not comprehensive.</span></span>

<br>

## <a name="september-2019"></a><span data-ttu-id="3b955-108">2019년 9월</span><span class="sxs-lookup"><span data-stu-id="3b955-108">September 10, 2019</span></span>

|<span data-ttu-id="3b955-109">요약</span><span class="sxs-lookup"><span data-stu-id="3b955-109">Summary</span></span>|<span data-ttu-id="3b955-110">조사하는 중</span><span class="sxs-lookup"><span data-stu-id="3b955-110">Investigating</span></span>|<span data-ttu-id="3b955-111">해결됨</span><span class="sxs-lookup"><span data-stu-id="3b955-111">Resolved Property</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="3b955-112">**Excel**</span><span class="sxs-lookup"><span data-stu-id="3b955-112">**Excel**</span></span>
<span data-ttu-id="3b955-113">일부 보호된 시트에서 하이퍼링크를 붙여 넣을 수 없는 문제가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-113">We found an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>|<span data-ttu-id="3b955-114">월별 및 SACT 버전 1908 및 SAC 버전 1902</span><span class="sxs-lookup"><span data-stu-id="3b955-114">Monthly and SACT Version 1908 and SAC Version 1902</span></span>||
<span data-ttu-id="3b955-115">Excel 아이디어 기능에서, Win32 클라이언트에 있는 아이디어 단추를 클릭하여 추가 기능을 로드할 때 오류가 발생했습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-115">We found an issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>|<span data-ttu-id="3b955-116">월 단위 버전 1908</span><span class="sxs-lookup"><span data-stu-id="3b955-116">Monthly Version 1908</span></span>||
<span data-ttu-id="3b955-117">추가 기능 관리자에서 검색할 때 16개의 추가 기능만 표시되는 문제를 발견했습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-117">We found an issue where only 16 add-ins show when browsing in the add-in manager.</span></span>|<span data-ttu-id="3b955-118">월간 및 SACT 버전 1908</span><span class="sxs-lookup"><span data-stu-id="3b955-118">Monthly and SACT Version 1908</span></span>||
|<span data-ttu-id="3b955-119">**Outlook**</span><span class="sxs-lookup"><span data-stu-id="3b955-119">**Outlook**</span></span>
<span data-ttu-id="3b955-120">파일이 WebDAV 위치에 저장되지 않는 문제를 발견하였습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-120">We found an issue which could have prevented files from being saved to a WebDAV location.</span></span>|<span data-ttu-id="3b955-121">월간 버전 1909</span><span class="sxs-lookup"><span data-stu-id="3b955-121">Monthly Version 1909</span></span>||
|<span data-ttu-id="3b955-122">**프로젝트**</span><span class="sxs-lookup"><span data-stu-id="3b955-122">**Project**</span></span>
<span data-ttu-id="3b955-123">파일 메뉴에서 PDF/XPS를 만들 때 파일이 만들어지지 않는 문제가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-123">We found an issue when creating a PDF/XPS from the file menu, the file is not created.</span></span> |<span data-ttu-id="3b955-124">SAC 버전 1902</span><span class="sxs-lookup"><span data-stu-id="3b955-124">SAC Version 1902</span></span>||
|<span data-ttu-id="3b955-125">**Word**</span><span class="sxs-lookup"><span data-stu-id="3b955-125">**Word**</span></span>
<span data-ttu-id="3b955-126">사용자가 파일을 열 때 발생하는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-126">We found an issue users could hit on opening a file.</span></span>|<span data-ttu-id="3b955-127">월 단위 버전 1908</span><span class="sxs-lookup"><span data-stu-id="3b955-127">Monthly Version 1908</span></span>||
<span data-ttu-id="3b955-128">OneDrive 동기화 엔진에서 동기화되는 Office 파일의 경우, 저장 및 다른 이름으로 저장하는 경우에는 필요 속성 및 콘텐츠 형식 요구 사항과 같은 문서 메타데이터가 더 이상 유효성 검사되지 않는 문제가 발견되었습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-128">We found an issue with Office files synced by the OneDrive Sync Engine, document metadata such as Require Properties and Content Type requirements are no longer validated upon Save and Save As.</span></span>|<span data-ttu-id="3b955-129">SAC 버전 1902</span><span class="sxs-lookup"><span data-stu-id="3b955-129">SAC Version 1902</span></span>||

## <a name="may-2019---sample"></a><span data-ttu-id="3b955-130">2019 5월 - 샘플</span><span class="sxs-lookup"><span data-stu-id="3b955-130">May 2019 - SAMPLE</span></span>

|<span data-ttu-id="3b955-131">요약</span><span class="sxs-lookup"><span data-stu-id="3b955-131">Summary</span></span>|<span data-ttu-id="3b955-132">조사하는 중</span><span class="sxs-lookup"><span data-stu-id="3b955-132">Investigating</span></span>|<span data-ttu-id="3b955-133">해결됨</span><span class="sxs-lookup"><span data-stu-id="3b955-133">Resolved Property</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="3b955-134">**Excel**</span><span class="sxs-lookup"><span data-stu-id="3b955-134">**Excel**</span></span>
<span data-ttu-id="3b955-135">샘플을 여러 빌드에서 해결했습니다 -- 셀을 삽입하거나 삭제하는 경우 폭포 차트와 깔때기형 차트가 테이블로 동기화되지 않는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-135">Sample resoved in multiple builds -- We found an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>||<span data-ttu-id="3b955-136">SAC 버전 1902</span><span class="sxs-lookup"><span data-stu-id="3b955-136">SAC Version 1902</span></span> <br> <span data-ttu-id="3b955-137">(16.0.11328.20306)</span><span class="sxs-lookup"><span data-stu-id="3b955-137">(16.0.11328.20306)</span></span> <br> <span data-ttu-id="3b955-138">월간 버전 1905</span><span class="sxs-lookup"><span data-stu-id="3b955-138">Monthly Version 1905</span></span> <br> <span data-ttu-id="3b955-139">(16.0.11629.20210)</span><span class="sxs-lookup"><span data-stu-id="3b955-139">(16.0.11629.20210)</span></span>|
|<span data-ttu-id="3b955-140">**Word**</span><span class="sxs-lookup"><span data-stu-id="3b955-140">**Word**</span></span>
<span data-ttu-id="3b955-141">샘플을 일부 빌드에서 해결했습니다. (전체는 아님) -- 문서 속성 Quick Parts를 활성화하는 경우 성능이 저하되는 문제가 확인되었습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-141">Sample resoved in some builds, not all -- We found an issue with performance when enabling Quick Parts for Document propertiesk.</span></span>|<span data-ttu-id="3b955-142">SAC 버전 1808</span><span class="sxs-lookup"><span data-stu-id="3b955-142">SAC Version 1808</span></span>|<span data-ttu-id="3b955-143">SAC 버전 1902</span><span class="sxs-lookup"><span data-stu-id="3b955-143">SAC Version 1902</span></span> <br> <span data-ttu-id="3b955-144">(16.0.11328.20340)</span><span class="sxs-lookup"><span data-stu-id="3b955-144">(16.0.11328.20340)</span></span>|

<br>
<br>

> [!NOTE]
> <span data-ttu-id="3b955-145">Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="3b955-145">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
