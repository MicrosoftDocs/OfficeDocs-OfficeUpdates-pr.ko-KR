---
title: Microsoft Office 보안 업데이트 릴리스 정보
ms.author: andrewmo
author: TimDavenport
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: IT 전문가에게 Microsoft Office 보안 업데이트에 대한 릴리스 정보를 제공합니다.
ms.openlocfilehash: ae1402e77905e221cbcd0a6736ad3fb4ba4d507b
ms.sourcegitcommit: db30154a1be72ca2b3b41f4dcc8ce6986834f6da
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/09/2020
ms.locfileid: "47413086"
---
# <a name="release-notes-for-microsoft-office-security-updates"></a><span data-ttu-id="5803c-103">Microsoft Office 보안 업데이트 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="5803c-103">Release notes for Microsoft Office security updates</span></span>

<span data-ttu-id="5803c-104">이 릴리스 정보에서는 Microsoft Office 업데이트에 포함된 보안 수정에 대한 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="5803c-104">These release notes provide information about security fixes that are included in updates to Microsoft Office.</span></span>

<span data-ttu-id="5803c-105">이 정보는 기업용 Microsoft 365 Apps, Microsoft 365 Apps for Business, Office 2016 Retail(C2R) 및 Office 2019에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="5803c-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, Office 2016 Retail (C2R), and Office 2019.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="5803c-106">당사는 Microsoft 365 앱에 대한 업데이트 채널을 일부 변경하고 있습니다. 여기에는 새 업데이트 채널 추가(월별 엔터프라이즈 채널) 및 기존 업데이트 채널의 이름 변경 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="5803c-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="5803c-107">자세한 내용은 [이 문서를 검토하세요](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="5803c-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="5803c-108">Office 365 ProPlus는 2004 버전부터 엔터프라이즈용 Microsoft 365 앱으로 이름이 변경됩니다.</span><span class="sxs-lookup"><span data-stu-id="5803c-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="5803c-109">자세한 내용은  [이 문서를 검토하세요](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span><span class="sxs-lookup"><span data-stu-id="5803c-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="5803c-110">이 문서에서는 일반적으로 이를 Microsoft 365 앱이라고 지칭합니다.</span><span class="sxs-lookup"><span data-stu-id="5803c-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (공백으로 사용하므로, 위의 선을 삭제하지 마세요.)  

## <a name="september-08-2020"></a><span data-ttu-id="5803c-112">2020년 9월 8일</span><span class="sxs-lookup"><span data-stu-id="5803c-112">September 08, 2020</span></span>
<span data-ttu-id="5803c-113">월 단위 기업 채널: 버전 2007(빌드 13029.20534)</span><span class="sxs-lookup"><span data-stu-id="5803c-113">Monthly Enterprise Channel: Version 2007 (Build 13029.20534)</span></span>  
<span data-ttu-id="5803c-114">월 단위 기업 채널: 버전 2006(빌드 13001.20648)</span><span class="sxs-lookup"><span data-stu-id="5803c-114">Monthly Enterprise Channel: Version 2006 (Build 13001.20648)</span></span>  
<span data-ttu-id="5803c-115">반기 기업 채널(프리뷰): 버전 2008(빌드 13127.20408)</span><span class="sxs-lookup"><span data-stu-id="5803c-115">Semi-Annual Enterprise Channel (Preview): Version 2008 (Build 13127.20408)</span></span>  
<span data-ttu-id="5803c-116">반기 기업 채널: 버전 2002(빌드 12527.21104)</span><span class="sxs-lookup"><span data-stu-id="5803c-116">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.21104)</span></span>  
<span data-ttu-id="5803c-117">반기 기업 채널: 버전 1908(빌드 11929.20946)</span><span class="sxs-lookup"><span data-stu-id="5803c-117">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20946)</span></span>  
<span data-ttu-id="5803c-118">Office 2019 볼륨 라이선스: 버전 1808(빌드 10366.20016)</span><span class="sxs-lookup"><span data-stu-id="5803c-118">Office 2019 Volume Licensed: Version 1808 (Build 10366.20016)</span></span>  

[//]: # (보안 세부 정보 컨텐츠 제거 안 함)


### <a name="excel"></a><span data-ttu-id="5803c-120">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-120">Excel</span></span>

-   [<span data-ttu-id="5803c-121">CVE-2020-1594</span><span class="sxs-lookup"><span data-stu-id="5803c-121">CVE-2020-1594</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1594)
-   [<span data-ttu-id="5803c-122">CVE-2020-1335</span><span class="sxs-lookup"><span data-stu-id="5803c-122">CVE-2020-1335</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1335)
-   [<span data-ttu-id="5803c-123">CVE-2020-1224</span><span class="sxs-lookup"><span data-stu-id="5803c-123">CVE-2020-1224</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1224)
-   [<span data-ttu-id="5803c-124">CVE-2020-1332</span><span class="sxs-lookup"><span data-stu-id="5803c-124">CVE-2020-1332</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1332)

### <a name="word"></a><span data-ttu-id="5803c-125">Word</span><span class="sxs-lookup"><span data-stu-id="5803c-125">Word</span></span>

-   [<span data-ttu-id="5803c-126">CVE-2020-1338</span><span class="sxs-lookup"><span data-stu-id="5803c-126">CVE-2020-1338</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1338)
-   [<span data-ttu-id="5803c-127">CVE-2020-1218</span><span class="sxs-lookup"><span data-stu-id="5803c-127">CVE-2020-1218</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1218)
-   [<span data-ttu-id="5803c-128">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="5803c-128">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1445)

### <a name="office-suite"></a><span data-ttu-id="5803c-129">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-129">Office Suite</span></span>

-   [<span data-ttu-id="5803c-130">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="5803c-130">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1458)
-   [<span data-ttu-id="5803c-131">CVE-2020-1193</span><span class="sxs-lookup"><span data-stu-id="5803c-131">CVE-2020-1193</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1193)

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 끝)



## <a name="august-11-2020"></a><span data-ttu-id="5803c-133">2020년 8월 11일</span><span class="sxs-lookup"><span data-stu-id="5803c-133">August 11, 2020</span></span>
<span data-ttu-id="5803c-134">현재 채널: 버전 2007(빌드 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="5803c-134">Current Channel: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="5803c-135">월별 엔터프라이즈 채널: 버전 2006(빌드 13001.20520)</span><span class="sxs-lookup"><span data-stu-id="5803c-135">Monthly Enterprise Channel: Version 2006 (Build 13001.20520)</span></span>  
<span data-ttu-id="5803c-136">월별 엔터프라이즈 채널: 버전 2005(빌드 12827.20656)</span><span class="sxs-lookup"><span data-stu-id="5803c-136">Monthly Enterprise Channel: Version 2005 (Build 12827.20656)</span></span>  
<span data-ttu-id="5803c-137">반기별 엔터프라이즈 채널(Preview): 버전 2002(빌드 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="5803c-137">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="5803c-138">반기별 엔터프라이즈 채널: 버전 2002(빌드 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="5803c-138">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="5803c-139">반기별 엔터프라이즈 채널: 버전 1908(빌드 11929.20934)</span><span class="sxs-lookup"><span data-stu-id="5803c-139">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20934)</span></span>  
<span data-ttu-id="5803c-140">반기별 엔터프라이즈 채널: 버전 1902(빌드 11328.20644)</span><span class="sxs-lookup"><span data-stu-id="5803c-140">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20644)</span></span>  
<span data-ttu-id="5803c-141">Windows 7의 Microsoft 365 애플리케이션: 버전 2002(빌드 12527.20988)</span><span class="sxs-lookup"><span data-stu-id="5803c-141">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20988)</span></span>  
<span data-ttu-id="5803c-142">Office 2019 소매: 버전 2007(빌드 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="5803c-142">Office 2019 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="5803c-143">Office 2016 소매: 버전 2007(빌드 13029.20344)</span><span class="sxs-lookup"><span data-stu-id="5803c-143">Office 2016 Retail: Version 2007 (Build 13029.20344)</span></span>  
<span data-ttu-id="5803c-144">Office 2019 볼륨 라이선스: 버전 1808(빌드 10364.20059)</span><span class="sxs-lookup"><span data-stu-id="5803c-144">Office 2019 Volume Licensed: Version 1808 (Build 10364.20059)</span></span>  

[//]: # (보안 세부 정보 컨텐츠 제거 안 함)


### <a name="access"></a><span data-ttu-id="5803c-146">접근</span><span class="sxs-lookup"><span data-stu-id="5803c-146">Access</span></span>

-   [<span data-ttu-id="5803c-147">CVE-2020-1582</span><span class="sxs-lookup"><span data-stu-id="5803c-147">CVE-2020-1582</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1582)

### <a name="excel"></a><span data-ttu-id="5803c-148">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-148">Excel</span></span>

-   [<span data-ttu-id="5803c-149">CVE-2020-1495</span><span class="sxs-lookup"><span data-stu-id="5803c-149">CVE-2020-1495</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1495)
-   [<span data-ttu-id="5803c-150">CVE-2020-1498</span><span class="sxs-lookup"><span data-stu-id="5803c-150">CVE-2020-1498</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1498)
-   [<span data-ttu-id="5803c-151">CVE-2020-1496</span><span class="sxs-lookup"><span data-stu-id="5803c-151">CVE-2020-1496</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1496)
-   [<span data-ttu-id="5803c-152">CVE-2020-1497</span><span class="sxs-lookup"><span data-stu-id="5803c-152">CVE-2020-1497</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1497)
-   [<span data-ttu-id="5803c-153">CVE-2020-1494</span><span class="sxs-lookup"><span data-stu-id="5803c-153">CVE-2020-1494</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1494)

### <a name="outlook"></a><span data-ttu-id="5803c-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="5803c-154">Outlook</span></span>

-   [<span data-ttu-id="5803c-155">CVE-2020-1493</span><span class="sxs-lookup"><span data-stu-id="5803c-155">CVE-2020-1493</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1493)
-   [<span data-ttu-id="5803c-156">CVE-2020-1483</span><span class="sxs-lookup"><span data-stu-id="5803c-156">CVE-2020-1483</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1483)

### <a name="word"></a><span data-ttu-id="5803c-157">Word</span><span class="sxs-lookup"><span data-stu-id="5803c-157">Word</span></span>

-   [<span data-ttu-id="5803c-158">CVE-2020-1583</span><span class="sxs-lookup"><span data-stu-id="5803c-158">CVE-2020-1583</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1583)
-   [<span data-ttu-id="5803c-159">CVE-2020-1502</span><span class="sxs-lookup"><span data-stu-id="5803c-159">CVE-2020-1502</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1502)
-   [<span data-ttu-id="5803c-160">CVE-2020-1503</span><span class="sxs-lookup"><span data-stu-id="5803c-160">CVE-2020-1503</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1503)

### <a name="office-suite"></a><span data-ttu-id="5803c-161">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-161">Office Suite</span></span>

-   [<span data-ttu-id="5803c-162">CVE-2020-1581</span><span class="sxs-lookup"><span data-stu-id="5803c-162">CVE-2020-1581</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1581)
-   [<span data-ttu-id="5803c-163">CVE-2020-1563</span><span class="sxs-lookup"><span data-stu-id="5803c-163">CVE-2020-1563</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1563)

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 끝)



## <a name="july-14-2020"></a><span data-ttu-id="5803c-165">2020년 7월 14일</span><span class="sxs-lookup"><span data-stu-id="5803c-165">July 14, 2020</span></span>
<span data-ttu-id="5803c-166">현재 채널: 버전 2006(빌드 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="5803c-166">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="5803c-167">월 단위 기업 채널: 버전 2005(빌드 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="5803c-167">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="5803c-168">월 단위 기업 채널: 버전 2004(빌드 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="5803c-168">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="5803c-169">반기 기업 채널(미리 보기): 버전 2002(빌드 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="5803c-169">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="5803c-170">반기 기업 채널: 버전 2002(빌드 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="5803c-170">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="5803c-171">반기 기업 채널: 버전 1908(빌드 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="5803c-171">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="5803c-172">반기 기업 채널: 버전 1902(빌드 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="5803c-172">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="5803c-173">Windows 7 기반 Microsoft 365 앱: 버전 2002(빌드 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="5803c-173">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 시작)


### <a name="excel"></a><span data-ttu-id="5803c-175">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-175">Excel</span></span>

-   [<span data-ttu-id="5803c-176">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="5803c-176">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="5803c-177">Outlook</span><span class="sxs-lookup"><span data-stu-id="5803c-177">Outlook</span></span>

-   [<span data-ttu-id="5803c-178">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="5803c-178">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="5803c-179">Project</span><span class="sxs-lookup"><span data-stu-id="5803c-179">Project</span></span>

-   [<span data-ttu-id="5803c-180">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="5803c-180">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="5803c-181">Word</span><span class="sxs-lookup"><span data-stu-id="5803c-181">Word</span></span>

-   [<span data-ttu-id="5803c-182">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="5803c-182">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="5803c-183">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="5803c-183">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="5803c-184">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="5803c-184">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="5803c-185">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="5803c-185">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="5803c-186">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-186">Office Suite</span></span>

-   [<span data-ttu-id="5803c-187">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="5803c-187">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1458)

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 끝)



## <a name="june-09-2020"></a><span data-ttu-id="5803c-189">2020년 6월 9일</span><span class="sxs-lookup"><span data-stu-id="5803c-189">June 09, 2020</span></span>
<span data-ttu-id="5803c-190">현재 채널: 버전 2005(빌드 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="5803c-190">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="5803c-191">월 단위 기업 채널: 버전 2004(빌드 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="5803c-191">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="5803c-192">월 단위 기업 채널: 버전 2003(빌드 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="5803c-192">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="5803c-193">반기 기업 채널(미리 보기): 버전 2002(빌드 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="5803c-193">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="5803c-194">반기 기업 채널: 버전 1908(빌드 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="5803c-194">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="5803c-195">반기 기업 채널: 버전 1902(빌드 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="5803c-195">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="5803c-196">Windows 7 기반 Microsoft 365 앱: 버전 2002(빌드 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="5803c-196">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 시작)


### <a name="excel"></a><span data-ttu-id="5803c-198">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-198">Excel</span></span>

-   [<span data-ttu-id="5803c-199">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="5803c-199">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="5803c-200">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="5803c-200">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="5803c-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="5803c-201">Outlook</span></span>

-   [<span data-ttu-id="5803c-202">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="5803c-202">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="5803c-203">Project</span><span class="sxs-lookup"><span data-stu-id="5803c-203">Project</span></span>

-   [<span data-ttu-id="5803c-204">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="5803c-204">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="5803c-205">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-205">Office Suite</span></span>

-   [<span data-ttu-id="5803c-206">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="5803c-206">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-1321)

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 끝)



## <a name="may-12-2020"></a><span data-ttu-id="5803c-208">2020년 5월 12일</span><span class="sxs-lookup"><span data-stu-id="5803c-208">May 12, 2020</span></span>
<span data-ttu-id="5803c-209">월별 채널: 버전 2004(빌드 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="5803c-209">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="5803c-210">월별 엔터프라이즈 채널: 버전 2003(빌드 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="5803c-210">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="5803c-211">반기 채널(대상 지정): 버전 2002(빌드 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="5803c-211">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="5803c-212">반기 채널: 버전 1908(빌드 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="5803c-212">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="5803c-213">반기 채널: 버전 1902(빌드 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="5803c-213">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="5803c-214">Windows 7 기반 Microsoft 365 앱: 버전 2002 (빌드 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="5803c-214">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 시작)


### <a name="excel"></a><span data-ttu-id="5803c-216">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-216">Excel</span></span>

-   [<span data-ttu-id="5803c-217">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="5803c-217">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0901)

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 끝)



## <a name="april-14-2020"></a><span data-ttu-id="5803c-219">2020년 4월 14일</span><span class="sxs-lookup"><span data-stu-id="5803c-219">April 14, 2020</span></span>
<span data-ttu-id="5803c-220">월별 채널: 버전 2003(빌드 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="5803c-220">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="5803c-221">반기 채널(대상 지정): 버전 2002 (빌드 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="5803c-221">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="5803c-222">반기 채널: 버전 1908 (빌드 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="5803c-222">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="5803c-223">반기 채널: 버전 1902 (빌드 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="5803c-223">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="5803c-224">Windows 7 기반 Microsoft 365 앱: 버전 2002 (빌드 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="5803c-224">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 시작)


### <a name="excel"></a><span data-ttu-id="5803c-226">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-226">Excel</span></span>

-   [<span data-ttu-id="5803c-227">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="5803c-227">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="5803c-228">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="5803c-228">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="5803c-229">Word</span><span class="sxs-lookup"><span data-stu-id="5803c-229">Word</span></span>

-   [<span data-ttu-id="5803c-230">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="5803c-230">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="5803c-231">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-231">Office Suite</span></span>

-   [<span data-ttu-id="5803c-232">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="5803c-232">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="5803c-233">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="5803c-233">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="5803c-234">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="5803c-234">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0961)

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 끝)



## <a name="march-10-2020"></a><span data-ttu-id="5803c-236">2020년 3월 10일</span><span class="sxs-lookup"><span data-stu-id="5803c-236">March 10, 2020</span></span>
<span data-ttu-id="5803c-237">월별 채널: 버전 2002 (빌드 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="5803c-237">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="5803c-238">반기 채널(대상 지정): 버전 2002 (빌드 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="5803c-238">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="5803c-239">반기 채널(대상 지정): 버전 1908 (빌드 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="5803c-239">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="5803c-240">반기 채널(대상 지정): 버전 1902 (빌드 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="5803c-240">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="5803c-241">Windows 7 기반 Microsoft 365 앱: 버전 2002 (빌드 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="5803c-241">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 시작)



### <a name="word"></a><span data-ttu-id="5803c-243">Word</span><span class="sxs-lookup"><span data-stu-id="5803c-243">Word</span></span>

-   [<span data-ttu-id="5803c-244">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="5803c-244">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="5803c-245">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="5803c-245">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="5803c-246">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="5803c-246">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="5803c-247">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="5803c-247">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0851)

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 끝)



## <a name="february-11-2020"></a><span data-ttu-id="5803c-249">2020년 2월 11일</span><span class="sxs-lookup"><span data-stu-id="5803c-249">February 11, 2020</span></span>
<span data-ttu-id="5803c-250">월별 채널: 버전 2001(빌드 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="5803c-250">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="5803c-251">반기 채널(대상 지정): 버전 1908(빌드 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="5803c-251">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="5803c-252">반기 채널: 버전 1908(빌드 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="5803c-252">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="5803c-253">반기 채널: 버전 1902(빌드 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="5803c-253">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="5803c-254">반기 채널: 버전 1808(빌드 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="5803c-254">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 시작)


### <a name="excel"></a><span data-ttu-id="5803c-256">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-256">Excel</span></span>

-   [<span data-ttu-id="5803c-257">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="5803c-257">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="5803c-258">Outlook</span><span class="sxs-lookup"><span data-stu-id="5803c-258">Outlook</span></span>

-   [<span data-ttu-id="5803c-259">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="5803c-259">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="5803c-260">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-260">Office Suite</span></span>

-   [<span data-ttu-id="5803c-261">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="5803c-261">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0697)

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 끝)



## <a name="january-14-2020"></a><span data-ttu-id="5803c-263">2020년 1월 14일</span><span class="sxs-lookup"><span data-stu-id="5803c-263">January 14, 2020</span></span>
<span data-ttu-id="5803c-264">월별 채널: 버전 1912(빌드 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="5803c-264">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="5803c-265">반기 채널(대상 지정): 버전 1908(빌드 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="5803c-265">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="5803c-266">반기 채널: 버전 1908(빌드 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="5803c-266">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="5803c-267">반기 채널: 버전 1902(빌드 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="5803c-267">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="5803c-268">반기 채널: 버전 1808 (빌드 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="5803c-268">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 시작)


### <a name="excel"></a><span data-ttu-id="5803c-270">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-270">Excel</span></span>

-   [<span data-ttu-id="5803c-271">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="5803c-271">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="5803c-272">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="5803c-272">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="5803c-273">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="5803c-273">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="5803c-274">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-274">Office Suite</span></span>

-   [<span data-ttu-id="5803c-275">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="5803c-275">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2020-0652)

[//]: # (보안 세부 정보 콘텐츠를 제거하지 마세요. 끝)



## <a name="december-10-2019"></a><span data-ttu-id="5803c-277">2019년 12월 10일</span><span class="sxs-lookup"><span data-stu-id="5803c-277">December 10, 2019</span></span>
<span data-ttu-id="5803c-278">월별 채널: 버전 1911 (빌드 12228.20364) 이상</span><span class="sxs-lookup"><span data-stu-id="5803c-278">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="5803c-279">반기 채널(대상 지정): 버전 1908 (빌드 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="5803c-279">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="5803c-280">반기 채널: 버전 1902 (빌드 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="5803c-280">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="5803c-281">반기 채널: 버전 1808 (빌드 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="5803c-281">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="5803c-282">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-282">Excel</span></span>

-   [<span data-ttu-id="5803c-283">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="5803c-283">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="5803c-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5803c-284">PowerPoint</span></span>

-   [<span data-ttu-id="5803c-285">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="5803c-285">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="5803c-286">Word</span><span class="sxs-lookup"><span data-stu-id="5803c-286">Word</span></span>

-   [<span data-ttu-id="5803c-287">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="5803c-287">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="5803c-288">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-288">Office Suite</span></span>

-   [<span data-ttu-id="5803c-289">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="5803c-289">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="5803c-290">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="5803c-290">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="5803c-291">2019년 11월 12일</span><span class="sxs-lookup"><span data-stu-id="5803c-291">November 12, 2019</span></span>
<span data-ttu-id="5803c-292">월별 채널: 버전 1910 (빌드 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="5803c-292">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="5803c-293">반기 채널(대상 지정): 버전 1908 (빌드 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="5803c-293">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="5803c-294">반기 채널: 버전 1902 (빌드 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="5803c-294">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="5803c-295">반기 채널: 버전 1808 (빌드 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="5803c-295">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="5803c-296">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-296">Excel</span></span>

-   [<span data-ttu-id="5803c-297">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="5803c-297">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="5803c-298">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="5803c-298">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="5803c-299">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-299">Office Suite</span></span>

-   [<span data-ttu-id="5803c-300">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="5803c-300">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="5803c-301">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="5803c-301">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="5803c-302">2019년 10월 8일</span><span class="sxs-lookup"><span data-stu-id="5803c-302">October 08, 2019</span></span>
<span data-ttu-id="5803c-303">월별 채널: 버전 1909 (빌드 12026.20320) 이상</span><span class="sxs-lookup"><span data-stu-id="5803c-303">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="5803c-304">반기 채널(대상 지정): 버전 1908 (빌드 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="5803c-304">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="5803c-305">반기 채널: 버전 1902 (빌드 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="5803c-305">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="5803c-306">반기 채널: 버전 1808 (빌드 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="5803c-306">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="5803c-307">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-307">Excel</span></span>

-   [<span data-ttu-id="5803c-308">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="5803c-308">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="5803c-309">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="5803c-309">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="5803c-310">2019년 9월 10일</span><span class="sxs-lookup"><span data-stu-id="5803c-310">September 10, 2019</span></span>
<span data-ttu-id="5803c-311">월별 채널: 버전 1908 (빌드 11929.20300) 이상</span><span class="sxs-lookup"><span data-stu-id="5803c-311">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="5803c-312">반기 채널(대상 지정): 버전 1908 (빌드 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="5803c-312">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="5803c-313">반기 채널: 버전 1902 (빌드 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="5803c-313">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="5803c-314">반기 채널: 버전 1808 (빌드 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="5803c-314">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="5803c-315">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-315">Excel</span></span>

-   [<span data-ttu-id="5803c-316">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="5803c-316">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="5803c-317">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="5803c-317">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="5803c-318">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-318">Office Suite</span></span>

-   [<span data-ttu-id="5803c-319">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="5803c-319">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="5803c-320">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="5803c-320">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="5803c-321">2019년 8월 13일</span><span class="sxs-lookup"><span data-stu-id="5803c-321">August 13, 2019</span></span>
<span data-ttu-id="5803c-322">월별 채널: 버전 1907 (빌드 11901.20218) 이상</span><span class="sxs-lookup"><span data-stu-id="5803c-322">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="5803c-323">반기 채널(대상 지정): 버전 1902 (빌드 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="5803c-323">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="5803c-324">반기 채널: 버전 1902 (빌드 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="5803c-324">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="5803c-325">반기 채널: 버전 1808 (빌드 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="5803c-325">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="5803c-326">반기 채널: 버전 1803 (빌드 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="5803c-326">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="5803c-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="5803c-327">Outlook</span></span>

-   [<span data-ttu-id="5803c-328">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="5803c-328">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="5803c-329">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="5803c-329">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="5803c-330">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="5803c-330">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="5803c-331">Word</span><span class="sxs-lookup"><span data-stu-id="5803c-331">Word</span></span>

-   [<span data-ttu-id="5803c-332">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="5803c-332">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="5803c-333">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="5803c-333">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="5803c-334">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-334">Office Suite</span></span>

-   [<span data-ttu-id="5803c-335">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="5803c-335">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="5803c-336">2019년 7월 9일</span><span class="sxs-lookup"><span data-stu-id="5803c-336">July 09, 2019</span></span>
<span data-ttu-id="5803c-337">월간 채널: 버전 1906 (빌드 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="5803c-337">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="5803c-338">반기 채널(대상 지정): 버전 1902(빌드 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="5803c-338">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="5803c-339">반기 채널: 버전 1902 (빌드 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="5803c-339">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="5803c-340">반기 채널: 버전 1808 (빌드 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="5803c-340">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="5803c-341">반기 채널: 버전 1803 (빌드 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="5803c-341">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="5803c-342">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-342">Excel</span></span>

-   [<span data-ttu-id="5803c-343">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="5803c-343">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="5803c-344">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="5803c-344">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="5803c-345">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="5803c-345">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="5803c-346">Outlook</span><span class="sxs-lookup"><span data-stu-id="5803c-346">Outlook</span></span>

-   [<span data-ttu-id="5803c-347">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="5803c-347">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="5803c-348">비즈니스용 Skype</span><span class="sxs-lookup"><span data-stu-id="5803c-348">Skype for Business</span></span>

-   [<span data-ttu-id="5803c-349">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="5803c-349">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="5803c-350">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-350">Office Suite</span></span>

-   [<span data-ttu-id="5803c-351">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="5803c-351">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="5803c-352">2019년 6월 11일</span><span class="sxs-lookup"><span data-stu-id="5803c-352">June 11, 2019</span></span>
<span data-ttu-id="5803c-353">월별 채널: 버전 1905(빌드 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="5803c-353">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="5803c-354">반기 채널(대상 지정): 버전 1902(빌드 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="5803c-354">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="5803c-355">반기 채널: 버전 1808(빌드 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="5803c-355">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="5803c-356">반기 채널: 버전 1803(빌드 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="5803c-356">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="5803c-357">Word</span><span class="sxs-lookup"><span data-stu-id="5803c-357">Word</span></span>

-   [<span data-ttu-id="5803c-358">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="5803c-358">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="5803c-359">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="5803c-359">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="5803c-360">2019년 5월 14일</span><span class="sxs-lookup"><span data-stu-id="5803c-360">May 14, 2019</span></span>
<span data-ttu-id="5803c-361">월별 채널: 버전 1904(빌드 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="5803c-361">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="5803c-362">반기 채널(대상 지정): 버전 1902(빌드 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="5803c-362">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="5803c-363">반기 채널: 버전 1808(빌드 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="5803c-363">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="5803c-364">반기 채널: 버전 1803(Build 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="5803c-364">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="5803c-365">Word</span><span class="sxs-lookup"><span data-stu-id="5803c-365">Word</span></span>

-   [<span data-ttu-id="5803c-366">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="5803c-366">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="5803c-367">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-367">Office Suite</span></span>

-   [<span data-ttu-id="5803c-368">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="5803c-368">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="5803c-369">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="5803c-369">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="5803c-370">2019년 4월 9일</span><span class="sxs-lookup"><span data-stu-id="5803c-370">April 09, 2019</span></span>
<span data-ttu-id="5803c-371">월별 채널: 버전 1903(빌드 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="5803c-371">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="5803c-372">반기 채널(대상 지정): 버전 1902(빌드 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="5803c-372">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="5803c-373">반기 채널: 버전 1808(빌드 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="5803c-373">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="5803c-374">반기 채널: 버전 1803(빌드 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="5803c-374">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="5803c-375">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-375">Excel</span></span>

-   [<span data-ttu-id="5803c-376">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="5803c-376">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="5803c-377">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-377">Office Suite</span></span>

-   [<span data-ttu-id="5803c-378">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="5803c-378">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="5803c-379">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="5803c-379">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="5803c-380">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="5803c-380">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="5803c-381">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="5803c-381">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="5803c-382">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="5803c-382">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="5803c-383">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="5803c-383">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="5803c-384">2019년 3월 12일</span><span class="sxs-lookup"><span data-stu-id="5803c-384">March 12, 2019</span></span>
<span data-ttu-id="5803c-385">이번 달에는 채널 보안 업데이트가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="5803c-385">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="5803c-386">2019년 2월 12일</span><span class="sxs-lookup"><span data-stu-id="5803c-386">February 12, 2019</span></span>
<span data-ttu-id="5803c-387">월간 채널: 버전 1901(빌드 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="5803c-387">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="5803c-388">반기 채널(대상 지정): 버전 1808(빌드 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="5803c-388">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="5803c-389">반기 채널: 버전 1808(빌드 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="5803c-389">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="5803c-390">반기 채널: 버전 1803(빌드 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="5803c-390">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="5803c-391">반기 채널: 버전 1708(빌드 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="5803c-391">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="5803c-392">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-392">Excel</span></span>

-   [<span data-ttu-id="5803c-393">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="5803c-393">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="5803c-394">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="5803c-394">Office suite</span></span>

-   [<span data-ttu-id="5803c-395">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="5803c-395">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="5803c-396">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="5803c-396">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="5803c-397">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="5803c-397">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="5803c-398">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="5803c-398">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="5803c-399">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="5803c-399">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="5803c-400">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="5803c-400">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="5803c-401">2019년 1월 8일</span><span class="sxs-lookup"><span data-stu-id="5803c-401">January 8, 2019</span></span>

<span data-ttu-id="5803c-402">월간 채널: 버전 1812 (빌드 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="5803c-402">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="5803c-403">반기 대상 지정 채널: 버전 1808 (빌드 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="5803c-403">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="5803c-404">반기 채널: 버전 1808 (빌드 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="5803c-404">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="5803c-405">반기 채널: 버전 1803 (빌드 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="5803c-405">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="5803c-406">반기 채널: 버전 1708 (빌드 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="5803c-406">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="5803c-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="5803c-407">Outlook</span></span>
-   [<span data-ttu-id="5803c-408">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="5803c-408">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="5803c-409">Word: 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="5803c-409">Word: Security updates</span></span> 
-   [<span data-ttu-id="5803c-410">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="5803c-410">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="5803c-411">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="5803c-411">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="5803c-412">Office 제품군: 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="5803c-412">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="5803c-413">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="5803c-413">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="5803c-414">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="5803c-414">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="5803c-415">2018년 12월 11일</span><span class="sxs-lookup"><span data-stu-id="5803c-415">December 11, 2018</span></span>
<span data-ttu-id="5803c-416">월간 채널: 버전 1811 (빌드 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="5803c-416">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="5803c-417">반기 채널: 버전 1803 (빌드 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="5803c-417">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="5803c-418">반기 채널 (대상 지정): 버전 1808 (빌드 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="5803c-418">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="5803c-419">Excel</span><span class="sxs-lookup"><span data-stu-id="5803c-419">Excel</span></span>

-   [<span data-ttu-id="5803c-420">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="5803c-420">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="5803c-421">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="5803c-421">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="5803c-422">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="5803c-422">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="5803c-423">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="5803c-423">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="5803c-424">Outlook</span><span class="sxs-lookup"><span data-stu-id="5803c-424">Outlook</span></span>

-   [<span data-ttu-id="5803c-425">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="5803c-425">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="5803c-426">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5803c-426">PowerPoint</span></span>

-   [<span data-ttu-id="5803c-427">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="5803c-427">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="5803c-428">2018년 11월 13일</span><span class="sxs-lookup"><span data-stu-id="5803c-428">November 13, 2018</span></span>
<span data-ttu-id="5803c-429">월별 채널: 버전 1810(빌드 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="5803c-429">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="5803c-430">반기 채널: 버전 1803(빌드 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="5803c-430">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="5803c-431">반기 채널(대상 지정): 버전 1808(빌드 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="5803c-431">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="5803c-432">Excel:</span><span class="sxs-lookup"><span data-stu-id="5803c-432">Excel:</span></span>

-   [<span data-ttu-id="5803c-433">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="5803c-433">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="5803c-434">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="5803c-434">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="5803c-435">Outlook:</span><span class="sxs-lookup"><span data-stu-id="5803c-435">Outlook:</span></span>

-   [<span data-ttu-id="5803c-436">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="5803c-436">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="5803c-437">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="5803c-437">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="5803c-438">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="5803c-438">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="5803c-439">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="5803c-439">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="5803c-440">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="5803c-440">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="5803c-441">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="5803c-441">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="5803c-442">Project:</span><span class="sxs-lookup"><span data-stu-id="5803c-442">Project:</span></span>

-   [<span data-ttu-id="5803c-443">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="5803c-443">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="5803c-444">비즈니스용 Skype:</span><span class="sxs-lookup"><span data-stu-id="5803c-444">Skype for Business:</span></span>

-   [<span data-ttu-id="5803c-445">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="5803c-445">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="5803c-446">Word:</span><span class="sxs-lookup"><span data-stu-id="5803c-446">Word:</span></span>

-   [<span data-ttu-id="5803c-447">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="5803c-447">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/ko-KR/security-guidance/advisory/CVE-2018-8573)
