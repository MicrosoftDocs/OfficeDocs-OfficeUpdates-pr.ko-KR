---
title: 2020의 반기 엔터프라이즈 채널 릴리스에 대한 릴리스 정보
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 2020년 Microsoft 365 앱에 대한 반기 채널 릴리스의 릴리스 정보를 IT 전문가에게 제공합니다.
ms.openlocfilehash: 469b87ca79a0f4f091e69cf1239715cee7b9dace
ms.sourcegitcommit: db30154a1be72ca2b3b41f4dcc8ce6986834f6da
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/09/2020
ms.locfileid: "47413076"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-releases-in-2020"></a><span data-ttu-id="2ef93-103">2020의 반기 엔터프라이즈 채널 릴리스에 대한 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-103">Release notes for Semi-Annual Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="2ef93-104">이 릴리스 정보에서는 엔터프라이즈용 Microsoft 365 앱, 비즈니스용 Microsoft 365 앱 및 프로젝트 및 Visio용 데스크톱 앱의 구독 버전에 대한 2020년 반기별 엔터프라이즈 채널 업데이트에 포함된 새로운 기능 및 비보안 업데이트에 대한 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="2ef93-105">당사는 Microsoft 365 앱에 대한 업데이트 채널을 일부 변경하고 있습니다. 여기에는 새 업데이트 채널 추가(월별 엔터프라이즈 채널) 및 기존 업데이트 채널의 이름 변경 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="2ef93-106">자세한 내용은 [이 문서를 참조](https://go.microsoft.com/fwlink/p/?linkid=2127441)하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="2ef93-107">반기 기업 채널의 사용자가 Office Portal에서 Microsoft 365 앱을 다운로드하여 Windows 10에 설치하는 경우 이제 OneNote 2016이 기본적으로 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-september-08"></a><span data-ttu-id="2ef93-109">버전 2002: 9월 8일</span><span class="sxs-lookup"><span data-stu-id="2ef93-109">Version 2002: September 08</span></span>
<span data-ttu-id="2ef93-110">*버전 2002(빌드 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-110">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="2ef93-111">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-113">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ef93-114">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-114">Excel</span></span>

- <span data-ttu-id="2ef93-115">이는 이전 버전의 Office에서 SQL 데이터 공급자가 만든 연결이 Office 365와 다르게 내부 테이블 속성을 설정하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-115">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="2ef93-116">이로 인해 Office 365를 사용하여 열 때 이전 버전의 Office에서 만든 연결이 있는 파일에 대해 테이블 미리보기/쿼리 편집기 드롭다운을 사용하지 않도록 설정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-116">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="2ef93-117">수동 입력으로 인해 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-117">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="2ef93-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-118">Outlook</span></span>

- <span data-ttu-id="2ef93-119">사용자가 공유 사서함을 추가한 후 공용 폴더에 연결할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-119">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2ef93-120">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-120">Office Suite</span></span>

- <span data-ttu-id="2ef93-121">이 변경 사항은 특정 사용자 설정을 유지하지 않는 그림 압축 대화 상자의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-121">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-september-08"></a><span data-ttu-id="2ef93-123">버전 1908: 9월 8일</span><span class="sxs-lookup"><span data-stu-id="2ef93-123">Version 1908: September 08</span></span>
<span data-ttu-id="2ef93-124">*버전 1908(빌드 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-124">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="2ef93-125">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-125">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="2ef93-126">버전 2002: 8월 11일</span><span class="sxs-lookup"><span data-stu-id="2ef93-126">Version 2002: August 11</span></span>
<span data-ttu-id="2ef93-127">*버전 2002(빌드 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-127">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="2ef93-128">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-128">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-130">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-130">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ef93-131">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-131">Excel</span></span>

- <span data-ttu-id="2ef93-132">"읽기 전용 권장 사항"으로 열린 파일에 대해 편집으로 전환할 수 없는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="2ef93-132">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="2ef93-133">원노트</span><span class="sxs-lookup"><span data-stu-id="2ef93-133">OneNote</span></span>

- <span data-ttu-id="2ef93-134">중복 ID 호출을 제거하여 리소스 활용률 감소</span><span class="sxs-lookup"><span data-stu-id="2ef93-134">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="2ef93-135">공동 Authoring 상태 탐지 개선으로 리소스 활용률 감소</span><span class="sxs-lookup"><span data-stu-id="2ef93-135">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="2ef93-136">오류 감지 기능 및 동기화 경험 품질 향상</span><span class="sxs-lookup"><span data-stu-id="2ef93-136">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ef93-137">전망</span><span class="sxs-lookup"><span data-stu-id="2ef93-137">Outlook</span></span>

- <span data-ttu-id="2ef93-138">일부 테넌트에 대해 Outlook을 시작할 때 중요한 성능 문제를 일으킨 문제 해결</span><span class="sxs-lookup"><span data-stu-id="2ef93-138">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="2ef93-139">스카이프</span><span class="sxs-lookup"><span data-stu-id="2ef93-139">Skype</span></span>

- <span data-ttu-id="2ef93-140">32비트 Skype for Business 클라이언트에서 며칠 동안 실행된 후 화면 공유 시작에 실패할 수 있는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="2ef93-140">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ef93-141">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-141">Office Suite</span></span>

- <span data-ttu-id="2ef93-142">그룹 정책을 통해 AutoSave가 해제된 경우 사용자가 '사용 가능한 업데이트'를 클릭할 때까지 일부 문서가 열려 있는 최신 서버 내용을 표시하지 않는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="2ef93-142">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (BUGDETILES 컨텐츠 끝)을(를) 제거하지 마십시오.

## <a name="version-1908-august-11"></a><span data-ttu-id="2ef93-144">버전 1908: 8월 11일</span><span class="sxs-lookup"><span data-stu-id="2ef93-144">Version 1908: August 11</span></span>
<span data-ttu-id="2ef93-145">*버전 1908(빌드 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-145">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="2ef93-146">보안 업데이트가 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)에 나열됨</span><span class="sxs-lookup"><span data-stu-id="2ef93-146">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="2ef93-147">버전 1902: 8월 11일</span><span class="sxs-lookup"><span data-stu-id="2ef93-147">Version 1902: August 11</span></span>
<span data-ttu-id="2ef93-148">*버전 1902(빌드 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-148">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="2ef93-149">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-149">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-july-14"></a><span data-ttu-id="2ef93-152">버전 2002: 7월 14일</span><span class="sxs-lookup"><span data-stu-id="2ef93-152">Version 2002: July 14</span></span>
<span data-ttu-id="2ef93-153">*버전 2002(빌드 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-153">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="2ef93-154">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)에 보안 업데이트가 나열됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-154">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="2ef93-156">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-156">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2ef93-157">Access</span><span class="sxs-lookup"><span data-stu-id="2ef93-157">Access</span></span>

- <span data-ttu-id="2ef93-158">**연결된 표 빠르게 찾기:** 새 검색 상자를 사용하여 연결된 표를 간편하게 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-158">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="2ef93-159">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-159">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="2ef93-160">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-160">Excel</span></span>

- <span data-ttu-id="2ef93-161">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-161">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2ef93-162">**데이터 시각화 도우미 추가 기능:** Excel에서 빠르게 Visio 플로차트를 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-162">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="2ef93-163">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-163">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="2ef93-164">\*\* 더 많은 접근 가능한 PDF 만들기:\*\* PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-164">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="2ef93-165">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-165">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="2ef93-166">[블로그 게시물](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-166">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2ef93-167">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-167">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2ef93-168">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-168">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2ef93-169">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-169">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2ef93-170">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-170">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2ef93-171">[블로그 게시물](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-171">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2ef93-172">**남은 작업에 중점:** 설명을 축소하고 열린 항목을 강조하려면 해결을 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-172">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="2ef93-173">**다중값을 반환하는 공식을 입력:** 다중값을 반환하는 공식을 신속히 입력하면 자동으로 인접한 셀들로 입력됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-173">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="2ef93-174">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-174">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="2ef93-175">[블로그 게시물](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)에서 세부 정보를 참조합니다</span><span class="sxs-lookup"><span data-stu-id="2ef93-175">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="2ef93-176">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-176">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="2ef93-177">**그림 스케치:** 통합 문서에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-177">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="2ef93-178">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-178">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2ef93-179">[블로그 게시물](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-179">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2ef93-180">**원하는 내용 찾기: 명령, 사용자, 파일, 사진, 웹 문서 등을 검색**</span><span class="sxs-lookup"><span data-stu-id="2ef93-180">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="2ef93-181">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-181">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2ef93-182">**유용한 함수 6개:** 스프레드시트를 더욱 유용하게 사용할 수 있는 함수 6개(FILTER, SORT, SORTBY, UNIQUE, SEQUENCE 및 RANDARRAY)가 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-182">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="2ef93-183">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-183">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="2ef93-184">\*\*왼쪽을 보고, 오른쪽을 보십시오… XLOOKUP이 여기 있습니다! \*\* 행별로 XLOOKUP을 사용하여 테이블 또는 범위에서 필요한 것을 모두 찾으십시오.</span><span class="sxs-lookup"><span data-stu-id="2ef93-184">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="2ef93-185">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-185">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="2ef93-186">[블로그 게시물](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-186">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="2ef93-187">**큰 통합 문서 관리:** 셀, 수식, 차트, 표... 통합 문서 통계를 사용하여 통합 문서를 한 눈에 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-187">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="2ef93-188">**읽고 즉시 회신:** 통합 문서를 열지 않고 전자 메일에서 바로 메모와 멘션에 회신합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-188">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="2ef93-189">**\@멘션으로 주의 끌기:** 메모에 @멘션을 사용하여 입력이 필요하다는 사실을 동료들에게 알립니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-189">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="2ef93-190">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-190">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="2ef93-191">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-191">Outlook</span></span>

- <span data-ttu-id="2ef93-192">**화면에 더 많은 메시지 맞춤:** 메시지 사이의 간격을 조정하려면 보기 > 더 좁은 간격 사용을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-192">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="2ef93-193">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-193">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="2ef93-194">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-194">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2ef93-195">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-195">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2ef93-196">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-196">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2ef93-197">**그리기 기능:** 그림 위쪽에서 낙서를 하거나 그리기 캔버스를 추가하여 잉크로 내 생각을 전달할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-197">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="2ef93-198">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-198">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="2ef93-199">**위치 제안 받기:** 약속 및 모임을 예약할 때 위치 필드에 입력을 시작하면 Outlook에 회의실, 주소 및 기타 최근 장소가 제안됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-199">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="2ef93-200">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-200">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="2ef93-201">[블로그 게시물](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-201">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="2ef93-202">**공격에 대비한 고급 보호:** Office 365 Advanced Threat Protection을 사용하면 전자 메일 제목, 첨부된 메시지, 서명된 메시지, 네트워크 경로 등의 하이퍼 링크를 통해 공격으로부터 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-202">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="2ef93-203">**Outlook의 링크 삽입 메뉴는 테넌트 관리자가 정의한 사용 권한을 포함하는 링크를 삽입합니다:** Outlook의 가장 최근 삽입한 링크에 있는 링크는 이미 사용 권한이 있었던 사용자들에게만 작동했었던 링크를 삽입합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-203">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="2ef93-204">이는 종종 사용자들 간에 문서에 대한 액세스 권한을 요청하는 전자 메일을 주고 받게 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-204">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="2ef93-205">이 환경을 업데이트하여 이제 테넌트 관리자가 설정한 기본 권한으로 링크가 삽입되었습니다. MSIT의 경우 "조직은 편집할 수 있음"이므로 이 방법을 통해 공유된 링크를 받는 모든 내부 사용자가 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-205">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="2ef93-206">**다른 조명에서 메시지 보기:** 태양/달 단추를 사용하여 읽기 창에서 밝은 배경과 어두운 배경 간에 전환을 합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-206">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="2ef93-207">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-207">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="2ef93-208">**피싱 메일을 쉽게 탐지:** 스팸과 피싱 메시지는 형태와 느낌이 다르기 때문에 받은 편지함에서 쉽게 식별하고 제거할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-208">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="2ef93-p119">**모든 암호화 옵션의 일원화:** 전자 메일 메시지 보호 방법을 선택하려면 옵션 > 암호화로 이동합니다. [자세히 알아보기](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="2ef93-p119">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="2ef93-211">**맞춤법 문제 또는 오타가 포함된 검색:** Outlook은 철자가 틀린 경우에도 검색 내용을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-211">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="2ef93-212">**LinkedIn 네트워크를 Outlook과 연결하기:** Microsoft 계정을 사용하여 LinkedIn 계정에 안전하게 연결하고 Windows용 Outlook의 명함에 있는 LinkedIn 프로필에서 정보를 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-212">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="2ef93-213">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-213">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="2ef93-214">**검색 결과에서 관련 메시지 확인:** Outlook은 검색 용어를 분석하고 검색 결과 상단에 가장 관련성이 높은 전자 메일 메시지를 보여줍니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-214">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="2ef93-215">또한 상위 결과 섹션에 날짜별로 정렬된 모든 결과도 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-215">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="2ef93-216">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-216">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="2ef93-217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ef93-217">PowerPoint</span></span>

- <span data-ttu-id="2ef93-p122">**수식만 쓰세요, 서식은 PowerPoint가 알아서 지정해 드립니다:** 손글씨로 쓴 수학 식을 표준 문자로 변경해 드리겠습니다. 잉크 수식 변환을 선택하고 필기를 선택하기만 하면 됩니다. [자세히 알아보기](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="2ef93-p122">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="2ef93-221">**원하는 내용 찾기:** 검색 창을 사용하여 텍스트, 명령, 도움말 등을 찾으세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-221">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="2ef93-222">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-222">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2ef93-223">**멋진 슬라이드 만들기:** 잉크를 표준 도형 및 텍스트로 변환한 후, PowerPoint Designer에서 스마트한 슬라이드 디자인 아이디어를 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-223">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="2ef93-224">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-224">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="2ef93-225">**그림 스케치:** 프레젠테이션에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-225">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="2ef93-226">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-226">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2ef93-227">[블로그 게시물](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-227">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2ef93-228">**잉크 스턴트 재생:** 슬라이드에 잉크를 쓸 때 슬라이드 쇼 중에 잉크의 실제 그리기를 재생하기 위한 재생 애니메이션을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-228">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="2ef93-229">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-229">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="2ef93-230">[블로그 게시물](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-230">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="2ef93-231">**더욱 안전한 비디오 환경:** 보안 강화는 더욱 안전한 온라인 비디오 환경을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-231">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="2ef93-232">**그림을 SVG로 저장:** 이미지 품질이 손실되지 않도록 크기를 조정할 수 있는 스케일 가능한 벡터 그래픽으로 차트, 도형 또는 기타 그림을 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-232">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="2ef93-233">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-233">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="2ef93-234">**슬라이드 번호를 유인물에 인쇄:** 슬라이드 번호가 유인물에 자동으로 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-234">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="2ef93-235">계속 사용 및 해제 여부를 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-235">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="2ef93-236">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-236">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="2ef93-237">**누락된 슬라이드 제목 찾기 및 수정:** 슬라이드 제목은 발표에 호소력을 더해 다양한 수준의 사용자가 슬라이드를 이해하기 쉽도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-237">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="2ef93-238">접근성 검사를 통해 제목이 누락되는 위치를 표시하여 신속하게 제목을 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-238">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="2ef93-239">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-239">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="2ef93-240">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-240">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2ef93-241">[블로그 게시물](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-241">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2ef93-242">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-242">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="2ef93-243">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-243">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2ef93-244">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-244">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2ef93-245">\*\* 더 많은 접근 가능한 PDF 만들기:\*\* PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-245">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="2ef93-246">[블로그 게시물](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-246">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2ef93-247">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-247">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2ef93-248">**PowerPoint에서 빠르게 실시간 공동 작업 수행:** PowerPoint에서 빠르게 실시간 공동 작업 수행</span><span class="sxs-lookup"><span data-stu-id="2ef93-248">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="2ef93-249">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-249">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="2ef93-250">**새로운 교정 도구:** 단어를 틀릴까봐 스트레스 받지 마세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-250">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="2ef93-251">이제 PowerPoint는 문법 및 맞춤법 제안 사항을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-251">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="2ef93-252">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-252">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="2ef93-253">**라이브 캡션 및 자막:** 발표자의 단어가 화면에 캡션으로 자동으로 표시되고 원하는 언어로 자막으로 번역됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-253">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="2ef93-254">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-254">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="2ef93-255">\*\*모든 사용자를 위한 프레젠테이션 최적화: \*\* 접근성 검사기는 스크린 리더를 염두에 두고 슬라이드에서 개체를 정렬하는데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-255">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="2ef93-256">[블로그 게시물](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-256">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="2ef93-257">**재개발 대신 재사용:** 사용자가 작성했거나 다른 사용자가 공유하도록 한 슬라이드를 다시 사용하여 시간을 절약하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-257">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="2ef93-258">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-258">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="2ef93-259">Visio</span><span class="sxs-lookup"><span data-stu-id="2ef93-259">Visio</span></span>

- <span data-ttu-id="2ef93-260">**Excel에서 세련된 Visio 다이어그램 만들기:** 워크시트에 데이터를 입력하여 순서도 또는 조직도를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-260">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="2ef93-261">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-261">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="2ef93-262">**범죄 현장 재방문:** 범죄 현장 조사 서식 파일에서 새 증빙, 실내 및 실외 스텐실을 사용하여 범죄 현장에 대한 세부 정보를 다시 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-262">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="2ef93-263">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-263">Word</span></span>

- <span data-ttu-id="2ef93-264">**더욱 안전한 비디오 환경:** 보안 강화는 더욱 안전한 온라인 비디오 환경을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-264">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="2ef93-265">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-265">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="2ef93-266">\*\* 더 많은 접근 가능한 PDF 만들기:\*\* PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-266">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="2ef93-267">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-267">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="2ef93-268">[블로그 게시물](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-268">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2ef93-269">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-269">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2ef93-270">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-270">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2ef93-271">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-271">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2ef93-272">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-272">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="2ef93-273">[블로그 게시물](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-273">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="2ef93-274">**정확하게 지우기:** 두 개의 지우개 크기 중에 선택하고 작은 잉킹 결함을 수정하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-274">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="2ef93-275">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-275">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="2ef93-276">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-276">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2ef93-277">[블로그 게시물](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-277">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2ef93-278">**그림 스케치:** 문서에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-278">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="2ef93-279">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-279">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2ef93-280">[블로그 게시물](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-280">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2ef93-281">**원하는 내용 찾기:** 검색 창을 사용하여 텍스트, 명령, 도움말 등을 찾으세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-281">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="2ef93-282">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-282">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2ef93-283">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-283">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="2ef93-284">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-284">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="2ef93-285">**이력서 편집기와 LinkedIn Resume 도우미의 만남:** 이력서 편집기는 이력서에 특별히 맞춤화된 문법 및 스타일 검사를 제공하여 글을 보다 정확하고 전문적으로 만들어 줍니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-285">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="2ef93-286">**다른 사용자가 변경 내용을 신속하게 확인:** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-286">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="2ef93-287">**3D 개체의 병합으로 발생하는 문서 손상 문제 해결:** 3D 개체의 병합으로 발생하는 문서 손상 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-287">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="2ef93-288">**공동 작성 기능 개선**: 문서 공동 작성 시 변경 내용 추적 기능을 사용하여 Word의 성능을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-288">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="2ef93-289">**공동 작성 향상** : 공동 작성 시 신뢰도가 향상될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-289">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="2ef93-290">**생생한 색으로 공동 작업:** 메모와 변경 사항은 기여자에 의해 색상으로 구분되므로 공동 작업자 중 개개인을 쉽게 구분할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-290">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="2ef93-291">**공동으로 매크로 사용 문서 편집 공동:** 비즈니스용 OneDrive에서 .docm 파일을 저장하고 공동 작업자와 실시간으로 편집합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-291">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ef93-292">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-292">Office Suite</span></span>

- <span data-ttu-id="2ef93-293">**Office 365용 PowerPoint에서 필기 잉크를 도형, 텍스트 또는 수학으로 변경:** 몇 번의 스트로크만으로 자유형 잉크를 Office 도형, 텍스트 또는 수식으로 변경합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-293">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="2ef93-294">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-294">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-297">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-297">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ef93-298">Access</span><span class="sxs-lookup"><span data-stu-id="2ef93-298">Access</span></span>

- <span data-ttu-id="2ef93-299">이 업데이트는 ADODB 사용시 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-299">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="2ef93-300">VB 코드의 레코더 개체에서 오류가 잘못 보고될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-300">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="2ef93-301">데이터베이스 내에서 더 이상 액세스 템플릿으로 인해 첨부 열이 실패하지 않아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-301">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="2ef93-302">템플릿을 인스턴스화 한 후에는 데이터베이스에 첨부 파일 필드를 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-302">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="2ef93-303">이 업데이트는 Microsoft Access에서 연결된 SQL Server 테이블의 ID 열이 식별되지 않아서 행이 올바르지 않게 삭제된 것으로 보고되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-303">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="2ef93-304">이 업데이트는 업데이트 쿼리가 실행되거나 UPDATE 문이 SQL에 사용될 때 “쿼리가 손상되었습니다” 오류를 일으킬 수 있는 Microsoft Access의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-304">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2ef93-305">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-305">Excel</span></span>

- <span data-ttu-id="2ef93-306">로컬 OneDrive 폴더에서 사용할 수 있는 파일을 빠르게 로드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-306">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="2ef93-307">CUBEVALUE 함수가 때때로 잘못된 결과를 반환하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-307">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="2ef93-308">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-308">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2ef93-309">특정 경우에 Word나 PowerPoint에서 포함된 통합 문서를 다시 열면 Excel이 중단됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-309">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="2ef93-310">상황에 맞는 메뉴에서 메모 명령이 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-310">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="2ef93-311">피벗 차트의 오른쪽 클릭 메뉴를 수정하여 세부 정보를 표시하는 옵션을 사용할 수 있도록 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-311">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="2ef93-312">통합 문서가 열려있지 않은 상태에서 최근 파일을 검색할 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-312">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2ef93-313">동일한 통합 문서에서 북마크가 지정된 하이퍼링크를 클릭하면 통합 문서가 숨겨지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-313">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="2ef93-314">CSV 파일로 저장하면 Excel에서 모든 열이 하나의 열로 병합되는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-314">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="2ef93-315">보호된 시트의 범위에서 Range.ClearContents를 사용하면 예상보다 시간이 오래 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-315">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="2ef93-316">인쇄 미리 보기로 표시되는 경우 양식 컨트롤에서 텍스트의 크기 조정 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-316">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="2ef93-317">리본 메뉴와 상호 작용하는 VBA 매크로는 ScreenUpdating을 예기치 않게 True로 설정한 상태에서 실행될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-317">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="2ef93-318">일부 경우에 피벗 테이블을 포함하는 시트를 복사한 후 Excel의 작동이 중단되는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-318">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="2ef93-319">경우에 따라 CSV 파일을 여는 데 소요되는 시간이 예상보다 더 오래 걸렸습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-319">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="2ef93-320">다른 확대/축소 단계를 사용하는 통합 문서 사이를 전환할 때 일부의 경우에 Excel의 작동이 중단될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-320">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="2ef93-321">범위에 값을 입력하는 것이 예상한 것 보다 느려지는 VBA 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-321">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2ef93-322">색을 기준으로 필터링 된 열에서 복사한 데이터가 가끔 제대로 붙여 넣어지지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-322">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="2ef93-323">다수의 다양한 통합 문서(특히 숨겨진 창)를 참조하는 통합 문서를 열면 예상보다 느리게 열립니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-323">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="2ef93-324">원본 통합 문서가 닫힌 경우 외부 링크가 채우기(아래로 채우기, 가로 채우기 등)에 업데이트되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-324">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="2ef93-325">Teams를 통해 Excel 창을 공유할 때 Ctrl+Shift+화살표 키를 사용하여 스크롤한 후 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-325">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2ef93-326">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-326">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2ef93-327">파일을 저장하고 다시 열 때 차트 축의 "값 교점" 속성이 예기치 않게 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-327">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2ef93-328">SharePoint/OneDrive에 저장하는 경우 사용자 지정 리본 탭이 CustomUI XML을 제거하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-328">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="2ef93-329">병합된 셀이 있는 열을 삭제하면 발생하던 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-329">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="2ef93-330">인쇄 대화 상자의 프린터 목록에서 프린터 이름이 반복될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-330">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="2ef93-331">파일 경로가 너무 길면 파일을 다시 연 후 외부 링크가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-331">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="2ef93-332">인쇄할 때 양식 컨트롤에 있는 확인란 크기 조정 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-332">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2ef93-333">레거시 "공유 통합 문서" 모드를 사용하여 통합 문서의 새 시트에 변경 내용을 나열할 때 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-333">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="2ef93-334">필터링된 목록에 열을 삽입하면 예상보다 시간이 오래 걸립니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-334">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="2ef93-335">일부 복사 및 붙여넣기 차트 링크에서 범용 주소가 아닌 매핑된 드라이브 주소를 사용하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-335">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="2ef93-336">추가 기능이 사용자 지정 순서가 아니라 알파벳 순서로 로드되었기 때문에 ‘이 통합 문서는 다른 통합 문서에서 현재 참조하고 있으며 닫을 수 없습니다’라는 오류 메시지가 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-336">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="2ef93-337">이미 열려 있는 통합 문서 내의 위치에 대한 하이퍼링크를 클릭하면 통합 문서가 숨겨질 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-337">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="2ef93-338">다수의 다양한 통합 문서(특히 숨겨진 창)를 참조하는 통합 문서를 열면 예상보다 느리게 열립니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-338">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="2ef93-339">경우에 따라 VBA의 Application.Evaluate를 사용해도 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-339">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2ef93-340">일부 사용자가 경험할 수 있는 OLE(포함 및 연결된 개체) 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-340">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="2ef93-341">사용자가 영문이 아닌 일부 문자의 집합을 사용하여 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-341">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2ef93-342">이 업데이트는 수식 입력줄에서 예상한 것과 다른 글꼴로 텍스트를 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-342">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="2ef93-343">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-343">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2ef93-344">스크롤 후 셀을 선택하면 잘못된 셀이 선택되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-344">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2ef93-345">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-345">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="2ef93-346">신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 오류를 발생시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-346">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2ef93-347">일부 현지화의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-347">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="2ef93-348">서식 파일에서 차트를 만들 때 발생하는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-348">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="2ef93-349">spilling 배열이 있는 셀이 있는 열로 텍스트를 변환할 때 일부 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-349">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="2ef93-350">Range.Value와 Range.Value2(VBA)를 사용하면 수식이 동적 배열로 입력됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-350">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="2ef93-351">공식을 시작하는 @ 기호가 암시적 교차로 연산자로 간주되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-351">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="2ef93-352">정의된 이름의 수식이 여러 개 포함된 워크시트가 파일을 저장할 때 더 오래 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-352">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="2ef93-353">이 변경은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-353">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2ef93-354">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-354">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="2ef93-355">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ef93-355">OneNote</span></span>

- <span data-ttu-id="2ef93-356">OneNote 2016에서 동기화 빈도를 일시적으로 조정하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-356">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="2ef93-357">OneNote 2016에서 사용자가 해당 페이지로 이동할 때까지 온라인 전자 필기장에 있는 파일 및 이미지의 다운로드를 일시적으로 지연시켜 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-357">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="2ef93-358">OneNote 2016에서 일시적으로 휴지통을 비활성화하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-358">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="2ef93-359">사용자가 일반적으로 휴지통으로 전송될 데이터를 삭제하려고 하면, 사용자가 데이터를 유지할지 아니면 영구적으로 삭제할지 묻는 메시지가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-359">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="2ef93-360">OneNote 2016에서 버전 기록 페이지의 수와 동기화 빈도를 일시적으로 줄임으로써 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-360">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="2ef93-361">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 표시하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-361">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="2ef93-362">OneNote 2016에서 새로운 내장 첨부 파일의 최대 허용 크기를 50MB로 일시적으로 줄여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-362">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="2ef93-363">이 제한을 초과하는 파일의 경우 사용자는 선택적으로 파일을 OneDrive에 업로드하고 OneNote에 링크를 삽입할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-363">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="2ef93-364">OneNote 2016에서 앱 내 비디오 녹화를 일시적으로 사용하지 않도록 설정하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-364">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="2ef93-365">로컬 전자 필기장은 이 조치의 영향을 받지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-365">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="2ef93-366">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 지역화하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-366">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ef93-367">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-367">Outlook</span></span>

- <span data-ttu-id="2ef93-368">해상도가 다른 여러 모니터를 사용할 때 IME(입력 방법 편집기) 창이 IME를 통해 입력되는 기본 텍스트와 겹치는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-368">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="2ef93-369">Outlook에서 사용자가 가끔 충돌을 경험하게 한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-369">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="2ef93-370">이를 통해 첨부 파일 차단 논리를 업데이트하여 Outlook에서 Python 첨부 파일도 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-370">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2ef93-371">웹 추가 기능이 디지털 권한 관리 메시지에 액세스하게 만드는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-371">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="2ef93-372">시간대 정의 변경에 접근할 때 되풀이되는 약속 또는 모임이 잘못된 시간에 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-372">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="2ef93-373">2019년 브라질의 시간대를 사용하는 경우 되풀이되는 모임 및 약속은 2020년의 잘못된 타임슬롯에 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-373">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="2ef93-374">이 변경 사항은 브라질 시간대에 설정된 클라이언트나 해당 시간대에 설정된 모임 및 약속과 관련이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-374">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="2ef93-375">이렇게 변경하면 Outlook은 Outlook에서 사용하는 특정 표준 시간대 설정을 재정의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-375">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="2ef93-376">표준 시간대 재정의를 호출하려면 현재 사용자의 레지스트리 키를 설정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-376">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="2ef93-377">레지스트리 키 이름은 해당 표준 시간대의 내부 이름과 일치해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-377">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="2ef93-378">값은 유효 연도 대신 사용되는 표준 시간대 규칙의 연도를 나타냅니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-378">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="2ef93-379">예를 들어, 다음 레지스트리 키 재정의 값은 2020년에 유효 규칙으로 브라질 표준 시간대 규칙을 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-379">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="2ef93-380">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="2ef93-380">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="2ef93-381">South America Standard Time"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="2ef93-381">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="2ef93-382">사용자에게 모임 위치 필드의 예상치 않은 변경이 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-382">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="2ef93-383">모임 위치 필드가 예상치 않게 업데이트되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-383">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="2ef93-384">모임 위치를 지운 후 모임 위치가 예기치 않게 모임에 다시 추가되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-384">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="2ef93-385">모임 위치 필드의 쉼표가 세미콜론으로 바뀌는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-385">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="2ef93-386">기본 Teams 클라이언트를 통해 직접 Teams 모임에 참여할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-386">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="2ef93-387">Exchange 2010 서버에 사서함이 있는 사용자가 일정 항목에 첨부 파일을 추가할 때 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-387">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="2ef93-388">디지털 서명된 메시지에 회신할 때 사용자에게 문제가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-388">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="2ef93-389">사용자가 되풀이되는 일정 항목의 일부 인스턴스를 열 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-389">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="2ef93-390">일부 시나리오에서 그룹 헤더가 예기치 않게 확장되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-390">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="2ef93-391">폴더 창의 너비가 예기치 않게 변경되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-391">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="2ef93-392">Outlook에서 M365 Business Plus 계획에 있는 서비스 비용을 지불한 사용자를 위해 Data Loss Protection 정책을 활성화하지 못하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-392">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="2ef93-393">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 현저하게 지연이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-393">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2ef93-394">여러 창에서 같은 항목을 볼 때 충돌이 발생할 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-394">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="2ef93-395">Outlook에서 규칙을 업데이트할 때 “이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다.” 메시지가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-395">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="2ef93-396">매우 긴 Outlook 세션에서 메모리 누수를 발생시키는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-396">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2ef93-397">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-397">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2ef93-398">규칙 대화 상자를 열 때 “이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다.” 프롬프트가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-398">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2ef93-399">일부 시나리오에서 플래그가 지정된 항목 강조 표시를 사용하지 않도록 설정하는 옵션이 무시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-399">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="2ef93-400">접근성 검사 창을 닫은 후 “S” 키를 누르면 메일이 예기치 않게 전송되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-400">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="2ef93-401">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-401">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="2ef93-402">계정 설정을 취소할 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-402">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="2ef93-403">동기화 슬라이더가 더 작은 설정으로 설정되어 있어도 Outlook이 예기치 않게 모든 메일을 동기화시키는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-403">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="2ef93-404">검은색 테마를 사용한 사용자에게 “보낸 사람” 드롭다운에 흰색 배경에 흰색 텍스트가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-404">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="2ef93-405">사용자가 프로필을 만드는 동안 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-405">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="2ef93-406">사용자가 계정 만들기 컨텍스트에서 지원 센터에 문의하려고 할 때 “확인” 단추가 있는 빈 메시지 상자가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-406">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2ef93-407">사용자가 계정 만들기 컨텍스트에서 지원 센터에 문의하려고 할 때 “확인” 단추가 있는 빈 메시지 상자가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-407">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2ef93-408">타사 응용 프로그램에서 전자 메일을 보낼 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-408">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="2ef93-409">가끔 전자 메일 메시지의 범주가 사라지는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-409">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="2ef93-410">서버 운영 체제의 Outlook 사용자에게 "바이러스 백신 상태 : 유효하지 않음" 오류가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-410">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="2ef93-411">이 버전의 Windows에서는 바이러스 백신 탐지를 지원하지만 바이러스 백신을 제대로 구성했음에도 불구하고 바이러스 백신을 찾을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-411">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="2ef93-412">대리인이 다른 공유 사서함 컴퓨터의 다른 폴더 계층 구조를 볼 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-412">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="2ef93-413">관리자의 일정에서 기존 일정 약속을 편집할 때 대리인에게 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-413">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="2ef93-414">Gmail에 대한 인증 프롬프트를 완료할 수 없는 경우 사용자 브라우저 에뮬레이션 설정이 잘못되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-414">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="2ef93-415">공유 폴더 다운로드를 선택하지 않은 경우에 “전달 허용” 옵션이 공유 일정 모임 "응답 옵션"에 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-415">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="2ef93-416">Windows 업데이트 후 .msg와 .oft 파일을 여는 경우 작동이 멈추는 현상이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-416">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="2ef93-417">마우스의 X 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-417">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="2ef93-418">특정 검색 결과를 선택할 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-418">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2ef93-419">첨부 파일 도구에서 클라우드에 저장 단추가 누락되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-419">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2ef93-420">이 변경으로 메시지 헤더에서 여러 줄 제목을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-420">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="2ef93-421">두 개의 추가 기능에서 같은 리본 그룹에 단추를 추가하면 사용자에게 충돌이 발생하던 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-421">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="2ef93-422">테넌트 기본 권한이 "모든 사용자"로 구성된 경우 올바른 테넌트 기본 권한이 있는 전자 메일에 링크를 추가하지 못하던 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-422">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="2ef93-423">사용자가 전자 메일을 개인 메일 그룹으로 보낼 수 없던 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-423">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="2ef93-424">대규모 HTML 메시지를 전달할 때 사용자에게 잘린 메시지 본문이 표시되던 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-424">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2ef93-425">SMIME 알고리즘 선택 관련 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-425">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2ef93-426">파일을 WebDAV 위치에 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-426">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="2ef93-427">보안 대화 상자에서 "저장" 옵션을 선택할 때 사용자가 테넌트 외부에서 로컬 컴퓨터에 OneDrive 첨부 파일을 저장할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-427">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="2ef93-428">제목을 편집한 후 NDR 메시지 본문이 유니코드에서 ASCII로 변경되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-428">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="2ef93-429">Outlook 프로세스에서 사용자가 메모리 누수를 관찰할 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-429">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2ef93-430">사용자가 일부 상황에서 표시된 SMTP 주소와 일치하지 않는 주소로 보낸 전자 메일을 보게 되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-430">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="2ef93-431">검색 상자가 높은 dpi 모드로 잘못 정렬되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-431">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="2ef93-432">사용자가 클라우드 설정을 검색할 때 Outlook에서 중단을 경험하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-432">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="2ef93-433">피드백 검색 환경을 중단시키는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-433">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2ef93-434">Outlook에서 사용자가 가끔 충돌을 경험하게 한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-434">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="2ef93-435">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-435">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="2ef93-436">사용자가 프로필을 만드는 동안 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-436">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="2ef93-437">Outlook에서 사용자가 가끔 충돌을 경험하게 한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-437">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ef93-438">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ef93-438">PowerPoint</span></span>

- <span data-ttu-id="2ef93-439">레거시 PPT 주석에서 상황에 맞는 메뉴를 사용할 때 충돌을 일으킬 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-439">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="2ef93-440">복사-붙여넣기 시나리오 개선: 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-440">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="2ef93-441">개선된 설명이 있는 파일의 복사본을 여는 사용자에게 올바른 메시징을 릴레이하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-441">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="2ef93-442">Project</span><span class="sxs-lookup"><span data-stu-id="2ef93-442">Project</span></span>

- <span data-ttu-id="2ef93-443">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-443">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="2ef93-444">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-444">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="2ef93-445">비활성 단추를 통해 작업이 비활성화/활성화된 때를 ProjectBeforeTaskChange 이벤트에서 감지하지 못하는 문제를 해결했습니다. </span><span class="sxs-lookup"><span data-stu-id="2ef93-445">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="2ef93-446">이전 버전의 Project에서 만든 프로젝트를 저장하면 Project가 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-446">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="2ef93-447">읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-447">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="2ef93-448">고정된 기간 유형의 100% 작업이 100% 완료 미만으로 잘못 계산할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-448">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="2ef93-449">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-449">Word</span></span>

- <span data-ttu-id="2ef93-450">마우스의 X 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-450">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="2ef93-451">빠른 인쇄를 사용하여 인쇄한 후에 편집하려고 할 때 문서의 단어 맞춤이 뒤섞이는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-451">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="2ef93-452">표에 텍스트 맞춤 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-452">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="2ef93-453">삽입 가로선 길이가 더 짧지 않고 가운데 맞춤되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-453">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="2ef93-454">문서 블록 이끌이가 잘못된 알림을 표시할 수 있습니다. ”사용자가 스타일, 문서 블록을 수정했습니다.”</span><span class="sxs-lookup"><span data-stu-id="2ef93-454">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="2ef93-455">정책 FileBlick\Word2007Files를 활성화하는 경우 발생하는 공동 작성 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-455">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="2ef93-456">이름이 바뀐 조회 필드를 추가하는 경우 Word QuickPart가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-456">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="2ef93-457">2개의 문서를 하나로 병합할 때 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-457">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2ef93-458">편집에 대해 보호된 문서의 비교 기능 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-458">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="2ef93-459">이 업데이트는 레이블 정책에서 머리글/바닥글 또는 워터 마크를 적용한 경우 레이블을 변경하거나 제거하여 민감도 레이블을 적용하는 동안 삽입된 255자를 초과하는 텍스트를 차후에 식별하고 제거할 수 없는 Microsoft Word에서의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-459">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ef93-460">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-460">Office Suite</span></span>

- <span data-ttu-id="2ef93-461">대규모 PowerPoint 파일에서 공동 작성하는 동안 사용자가 과도한 네트워크 및 CPU 사용률을 경험할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-461">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="2ef93-462">파일을 클라이언트에 캐시할 때 Project 앱이 네트워크를 차단하지 않도록 하는 문제를 해결하기 위한 수정입니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-462">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="2ef93-463">우리는 2020년 1월 포크의 새 채널 이름으로 백스테이지의 채널 이름을 업데이트하여 이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-463">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="2ef93-464">이 문제를 해결했으며 앞으로 장치가 정책 관리 대상인 경우 DMS Customer API를 호출하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-464">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="2ef93-465">단일 트랜잭션에서 앱을 추가 및 제거할 때 불완전한 제거가 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-465">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="2ef93-466">상대적인 마감일이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정 버그에 대한 픽스, 이 픽스는 후속 업데이트에 대한 상대적인 마감일도 사용할 수 있도록 해줍니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-466">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2ef93-467">Office 업데이트에서 로컬 또는 네트워크 공유 또는 Configuration Manager에서 제공하는 위치와 같은 의도된 원본 대신 Office CDN에서 파일을 예기치 않게 다운로드했을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-467">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2ef93-468">상대적인 마감일이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정 버그에 대한 픽스, 이 픽스는 후속 업데이트에 대한 상대적인 마감일도 사용할 수 있도록 해줍니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-468">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2ef93-469">이전 AppV51의 회귀 분석을 수정하기 위해 새 AppV51 드롭을 다시 릴리스했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-469">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="2ef93-470">내부 작업이 실패 시 로깅을 하고 계속 진행하는 대신 예외를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-470">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="2ef93-471">영향을 받은 사용자는 더 이상 업데이트를 받을 수 없도록 차단되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-471">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="2ef93-472">당사의 팀에서는 반기 엔터프라이즈 미리 보기에서 Office CDN 도메인의 원격 분석 보고를 위한 클라이언트 지원을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-472">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="2ef93-473">이 변경은 인텔 통합 GPU를 활용하는 그래픽 어댑터에 보고된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-473">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="2ef93-474">이렇게 변경하면 스케치된 개요가 리본에서 제대로 작동합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-474">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="2ef93-475">특정 프록시 구성을 사용하여 온-프레미스 위치에서 파일을 여는 동안 발생하는 문제를 수정하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-475">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="2ef93-476">이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-476">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2ef93-477">Office 전달 세션 중에 충돌을 없애고 사용자 환경의 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-477">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="2ef93-478">이 버그는 ECS(향상된 구성 서비스) URL 끝점을 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-478">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="2ef93-479">이 최신 끝점의 호출은 ECS에서 가져오기의 성공률이 높습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-479">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="2ef93-480">이 업데이트는 메시지를 보거나 작성할 때 Microsoft Outlook에서 현재 민감도 레이블을 표시하지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-480">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="2ef93-481">동일한 SharePoint 라이브러리의 Word/Excel/PowerPoint에서 여러 문서를 열 때 첫 번째로 열린 문서만 정책 준수에 대한 검사가 이뤄지는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-481">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="2ef93-482">Office 고객의 보안을 위해 Microsoft Office 업데이트는 이제 SHA-2 알고리즘만을 사용하여 서명됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-482">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="2ef93-483">레지스트리 키 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth가 0으로 설정되어 있으면 추가 기능이 활성화될 때 Office 호스트가 Windows에서 충돌했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-483">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="2ef93-484">이렇게 변경하면 이 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-484">This change would fix this issue.</span></span>

- <span data-ttu-id="2ef93-485">레지스트리 TabProcGrowth 값이 REG_SZ 유형이면 추가 기능이 활성화될 때 Office 호스트가 Windows에서 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-485">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="2ef93-486">이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. </span><span class="sxs-lookup"><span data-stu-id="2ef93-486">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="2ef93-487">설치된 언어에 따라 Access 및 Publisher가 제대로 부팅되지 않을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-487">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)





[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-july-14"></a><span data-ttu-id="2ef93-490">버전 1908: 7월 14일</span><span class="sxs-lookup"><span data-stu-id="2ef93-490">Version 1908: July 14</span></span>
<span data-ttu-id="2ef93-491">*버전 1908(빌드 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-491">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="2ef93-492">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)에 보안 업데이트가 나열됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-492">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-494">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-494">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ef93-495">Access</span><span class="sxs-lookup"><span data-stu-id="2ef93-495">Access</span></span>

- <span data-ttu-id="2ef93-496">이 업데이트는 합계와 같은 집계가 결과를 정수 값으로 자를 수 있는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-496">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="2ef93-497">이 업데이트는 원격 테이블(예: SQL Server 테이블)로의 참조를 포함하는 통합 쿼리가 Access를 닫고 다시 시작하도록 할 수 있는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-497">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="2ef93-498">이 업데이트는 업데이트 쿼리가 실행되거나 UPDATE 문이 SQL에 사용될 때 “쿼리가 손상되었습니다” 오류를 일으킬 수 있는 Microsoft Access의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-498">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2ef93-499">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-499">Excel</span></span>

- <span data-ttu-id="2ef93-500">문서 타이틀에 대한 네덜란드어 키 설명이 Alt-G로 변경되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-500">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="2ef93-501">도형 또는 양식 컨트롤에 할당된 매크로가 잘못된 오류 메시지를 표시하거나 잘못된 대상 범위에서 작동하는 Excel의 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-501">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="2ef93-502">첫 번째 항목을 발견한 후 대화 상자에서 포커스가 있는 위치가 찾기 및 바꾸기로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-502">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="2ef93-503">이를 통해 다른 사용자와 공동 작성 세션에 있는 동안 피벗 테이블이 정렬되는 방식을 변경하고 새로 고치면 충돌이 트리거될 수 있는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-503">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="2ef93-504">OLAP PivotTable의 필터가 큐브에서 제거된 값으로 설정되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-504">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="2ef93-505">이 업데이트는 VBA를 사용하여 차트의 머리글/바닥글에 이미지를 추가할 때마다 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-505">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="2ef93-506">시리즈 컬렉션을 변경할 때 분산형 차트가 제대로 렌더링되지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-506">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="2ef93-507">차트 템플릿을 사용하여 차트를 삽입할 때 미리 보기에 사용되는 색을 수정하하기 위한 픽스입니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-507">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="2ef93-508">셀을 삽입하거나 삭제하는 경우 폭포 차트와 깔때기형 차트가 테이블로 동기화되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-508">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="2ef93-509">사용자에게 통합 문서를 다시 열어서 변경 내용을 적용하라는 메시지가 표시되는 Excel의 병합 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-509">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="2ef93-510">최소화된 창을 활성화하는 매크로 런타임 오류를 발생시켰던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-510">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="2ef93-511">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-511">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2ef93-512">다른 사용자와 공동 작성하는 경우 표의 옆에 잘라내어 붙여 넣는 작업이 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-512">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="2ef93-513">매크로가 실행되는 사용자 지정 속성을 변경할 때 공동 작성 작업을 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-513">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="2ef93-514">추가 기능을 통해 연 WPF(Windows Presentation Foundation) 양식의 콤보 상자에서 항목을 선택할 수 없는 문제가 발생했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-514">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="2ef93-515">통합 문서가 열려있지 않은 상태에서 최근 파일을 검색할 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-515">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2ef93-516">인쇄 미리보기 또는 인쇄 시 그룹 상자 컨트롤의 테두리가 보이지 않던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-516">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="2ef93-517">통합 문서에 외부 링크가 있는 경우 일부 사용자가 여러 개의 팝업 창을 경험하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-517">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="2ef93-518">VBA 매크로를 사용하여 범위의 내용을 지우면 사용자가 경험할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-518">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2ef93-519">범위에 값을 입력하는 것이 예상한 것 보다 느려지는 VBA 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-519">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2ef93-520">파일을 저장하고 다시 열 때 차트 축의 "값 교점" 속성이 예기치 않게 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-520">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2ef93-521">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-521">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2ef93-522">병합된 셀을 포함하는 열을 삭제할 때 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-522">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="2ef93-523">인쇄 미리 보기로 표시되는 경우 양식 컨트롤에서 텍스트의 크기 조정 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-523">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="2ef93-524">색을 기준으로 필터링된 데이터를 다른 너비의 열에 복사하면 값을 붙여넣을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-524">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="2ef93-525">팀을 통해 Excel 창을 공유할 때 Ctrl+Shift+화살표 키를 사용하여 스크롤한 후 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-525">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2ef93-526">인쇄할 때 양식 컨트롤에 있는 확인란 크기 조정 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-526">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2ef93-527">동일한 통합 문서에서 북마크가 지정된 하이퍼링크를 클릭하면 통합 문서가 숨겨지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-527">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="2ef93-528">레거시 "공유 통합 문서" 모드를 사용하여 통합 문서의 새 시트에 변경 내용을 나열할 때 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-528">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="2ef93-529">일부 현지의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-529">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="2ef93-530">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-530">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="2ef93-531">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-531">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2ef93-532">차트가 포함된 통합 문서를 저장할 때 차트 머리글의 이미지 파일 크기가 커지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-532">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="2ef93-533">비동기식 사용자 정의 함수의 성능 문제로 인해 함수가 동기식으로 실행되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-533">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="2ef93-534">병합된 셀이 있는 열을 삭제하는 성능이 크게 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-534">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="2ef93-535">스크롤 후 셀을 선택하면 잘못된 셀이 선택되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-535">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2ef93-536">Lookup 함수에서 오류가 반환될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-536">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="2ef93-537">선택 범위를 상호 참조 도서와 동기화하여 상호 참조 도서에서 DBCS 문자가 손상되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-537">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="2ef93-538">자동 맞춤을 사용하여 행 높이를 조정할 때 확인란 컨트롤이 축소될 수있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-538">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="2ef93-539">파일에 광범위한 조건부 서식이 있는 경우 글꼴색 단추를 클릭하면 성능이 저하되는 문제.</span><span class="sxs-lookup"><span data-stu-id="2ef93-539">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="2ef93-540">인쇄 미리 보기의 인쇄 영역이 올바르지 않았던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-540">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="2ef93-541">신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 오류를 발생시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-541">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2ef93-542">색 기준 필터링의 성능이 크게 향상되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-542">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="2ef93-543">이전 버전의 Office에서 작성한 통합 문서를 현재 버전의 Office에서 열었을 때 Excel이 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-543">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="2ef93-544">추가 기능 관리자에서 검색할 때 16개 이상의 추가 기능이 표시되도록 활성화했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-544">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="2ef93-545">일부 보호된 시트에서 하이퍼링크를 붙여넣을 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-545">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="2ef93-546">이 변경 사항은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-546">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2ef93-547">cid 링크: 이제 Outlook 메시지의 이미지는 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-547">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ef93-548">이 업데이트는 Office 문서가 "업로드 실패" 메시지와 함께 비즈니스용 OneDrive에 업로드되지 않을 수 있는 오류를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-548">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="2ef93-549">Excel 아이디어 기능에서, Win32 클라이언트에 있는 아이디어 버튼을 클릭하여 추가 기능을 로드할 때 발생하는 오류를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-549">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="2ef93-550">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ef93-550">OneNote</span></span>

- <span data-ttu-id="2ef93-551">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 지역화하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-551">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ef93-552">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-552">Outlook</span></span>

- <span data-ttu-id="2ef93-553">cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-553">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ef93-554">사서함을 기본 인증에서 최신 인증으로 업그레이드한 사용자가 Outlook 프로필에 연결된 잘못된 계정으로 끝나는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-554">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="2ef93-555">웹 추가 기능이 디지털 권한 관리 메시지에 액세스하지 않아야 함에도 액세스하게 만드는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-555">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="2ef93-556">일부 safelinks에서 간단한 호버 URL이 표시되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-556">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="2ef93-557">이를 통해 첨부 파일 차단 논리를 업데이트하여 Outlook에서 Python 첨부 파일도 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-557">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2ef93-558">POP3 사용자의 하위 집합에서 설정에 관계없이 일반 텍스트로 서식이 지정된 모든 전자 메일을 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-558">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="2ef93-559">이 수정은 HTML 서식이 지정된 메시지의 보기를 복원합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-559">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="2ef93-560">기본 일정의 항목을 그룹 일정에 복사할 때 사용 권한 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-560">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="2ef93-561">사용자가 화면 읽기 프로그램을 통해 위치 제안에 액세스할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-561">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="2ef93-562">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 현저하게 지연이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-562">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2ef93-563">매우 긴 Outlook 세션에서 메모리 누수를 발생시키는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-563">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2ef93-564">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-564">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2ef93-565">규칙 대화 상자를 열 때 “이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다.” 프롬프트가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-565">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2ef93-566">사용자가 특정 Safelinks와 상호 작용할 때 Outlook에서 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-566">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="2ef93-567">대리인이 이미 모임 요청에 응답했는지 여부와 관련하여 관리자에게 모호함을 야기하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-567">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="2ef93-568">일부 자동 검색 응답을 처리할 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-568">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2ef93-569">사용자가 계정 만들기 컨텍스트에서 지원 센터에 문의하려고 할 때 “확인” 단추가 있는 빈 메시지 상자가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-569">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2ef93-570">이 변경으로 인해 관리자가 정책을 사용하여 UPN에 대한 자동 검색 인증 프롬프트에서 제공된 계정 전자 메일을 원하는 대로 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-570">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="2ef93-571">기본적으로 AutoDiscover는 가능한 경우 계정 UPN을 선호합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-571">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="2ef93-572">사용자가 Modern Groups에 대한 검색 실패를 보게 되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-572">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="2ef93-573">특정 시나리오에서 Outlook 사용자가 “암호 필요” 상태에 멈춰있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-573">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="2ef93-574">충돌 메시지를 처리할 때 사용자에게 동기화 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-574">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="2ef93-575">최신 Windows 업데이트 적용 후 .msg와 .oft 파일을 여는 경우 작동이 멈추는 현상이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-575">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="2ef93-576">Outlook을 시작할 때 사용자에게 “프로필 로딩 중” 화면에서 중단이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-576">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="2ef93-577">특정 검색 결과를 선택할 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-577">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2ef93-578">첨부 파일 도구에서 "클라우드에 저장" 단추가 누락되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-578">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2ef93-579">기본적으로 보존 정책 레이블에는 보존 기간이 괄호로 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-579">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="2ef93-580">이는 관리자가 정책 이름만 표시하도록 지정할 수 있는 레지스트리 키를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-580">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="2ef93-581">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = 보존 정책 텍스트의 PolicyName만 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-581">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="2ef93-582">Outlook을 종료할 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-582">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="2ef93-583">일부 시나리오에서 고객에게 빈 회의실 목록이 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-583">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="2ef93-584">보기를 변경할 때 사용자에게 간헐적인 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-584">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="2ef93-585">사용자가 공유 일정 폴더를 OST와 동기화하는 데 문제가있어 이러한 폴더와 상호 작용할 때 권한 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-585">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="2ef93-586">Citrix 환경에서 30개 이상의 일정을 볼 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-586">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="2ef93-587">여기에는 [이전 버전에 대해 문서화된 개별 KB](https://support.microsoft.com/ko-KR/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-587">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/ko-KR/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="2ef93-588">SMIME 알고리즘 선택 관련 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-588">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2ef93-589">대체 보낸 사람을 사용할 때 정책 팁이 표시되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-589">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="2ef93-590">회의실의 가용 시간 이외의 시간에 발생한 모임에 대해 사용자에게 회의실 제안이 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-590">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="2ef93-591">비영어 사용자에게 메일의 제목 줄이 너무 작게 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-591">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="2ef93-592">사용자가 “놓친 대화 메시지”에서 규칙을 만들려고 할 때 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-592">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="2ef93-593">보조 Exchange 계정을 추가할 때 일부 사용자에게 만들어진 중복된 특수 폴더를 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-593">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="2ef93-594">대규모 HTML 메시지를 전달할 때 사용자에게 잘린 메시지 본문이 표시되던 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-594">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2ef93-595">Outlook 프로세스에서 사용자가 메모리 누수를 관찰할 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-595">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2ef93-596">사용자가 현재 상태 정보를 업데이트할 때 간헐적인 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-596">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="2ef93-597">현재 폴더 검색에 간헐적으로 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-597">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="2ef93-598">Outlook에 대한 클라우드 설정을 검색할 때 일부 사용자에게 인증 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-598">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="2ef93-599">피드백 검색 환경을 중단시키는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-599">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2ef93-600">일부 자동 검색 응답을 처리할 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-600">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2ef93-601">사용자가 현재 상태 정보를 업데이트할 때 간헐적인 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-601">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ef93-602">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ef93-602">PowerPoint</span></span>

- <span data-ttu-id="2ef93-603">cid 링크: 이제 Outlook 메시지의 이미지는 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-603">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ef93-604">이 변경으로 인해 PowerPoint 비디오 컨트롤의 액세스 가능한 이름이 복원되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-604">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="2ef93-605">일부 애니메이션이 시작되지 않도록 할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-605">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="2ef93-606">한 프레젠테이션에서 다른 프레젠테이션으로 슬라이드를 복사하는 경우 중복되는 마스터를 만들 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-606">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="2ef93-607">복사-붙여넣기 시나리오 개선: 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-607">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="2ef93-608">형광펜 관련 문제 해결: 어두운 형광펜 색상의 텍스트가 흑백 모드에서 검은 색으로 인쇄됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-608">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="2ef93-609">최신 메모가 포함된 파일을 지원되지 않는 버전에서 열었을 경우 노란색 경고가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-609">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="2ef93-610">공동 작업 사용자 간에 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-610">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="2ef93-611">안정성 수정: 타사 추가 기능이 PowerPoint와 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-611">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="2ef93-612">증분 방식으로 열린 파일에 둘 이상의 포함된 미디어 스트림이 있는 슬라이드가 포함되어 있을 때 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-612">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="2ef93-613">Shape 관련 문제를 해결했습니다. 붙여넣기 방법: 사용자가 Shape를 사용하여 셰이프를 복사하고 붙여 넣는 경우. 붙여넣기 방법. 선택 대상이 붙여넣기한 셰이프로 변경됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-613">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="2ef93-614">PowerPoint를 처음 시작할 때 신뢰할 수 없는 추가 기능에 대해 보안 경고 메시지 표시줄이 나타나지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-614">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="2ef93-615">일부 추가 기능이 차트의 도형 주변에 예기치 않은 오류를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-615">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="2ef93-616">PowerPoint 사용자가 온라인으로 프레젠테이션할 때 오류가 발생하지 않도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-616">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="2ef93-617">Project</span><span class="sxs-lookup"><span data-stu-id="2ef93-617">Project</span></span>

- <span data-ttu-id="2ef93-618">Windows 7 사용자가 Project Web App 및 SharePoint 사이트에서 프로젝트를 열 수 있도록 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-618">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="2ef93-619">읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 식별했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-619">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="2ef93-620">모든 명령 수준으로 리소스 초과 할당이 제대로 해결되지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-620">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="2ef93-621">과업에 대한 작업이 0인 과제가 있는 경우 해당 과업이 완성으로 표시되지 않고 항상 99%로 표시되는 문제.</span><span class="sxs-lookup"><span data-stu-id="2ef93-621">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="2ef93-622">기본 일정이 변경될 때 리소스 일정이 업데이트되지 않아 작업표와 프로젝트 계획 간에 실제 작업이 다를 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-622">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="2ef93-623">Skype</span><span class="sxs-lookup"><span data-stu-id="2ef93-623">Skype</span></span>

- <span data-ttu-id="2ef93-624">두 개 이상의 대화가 진행되는 동안 탭 대화의 제목 이름이 고정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-624">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="2ef93-625">Visio</span><span class="sxs-lookup"><span data-stu-id="2ef93-625">Visio</span></span>

- <span data-ttu-id="2ef93-626">Visio에서 SVG로 내보내기가 다양한 도형에서 실패했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-626">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="2ef93-627">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-627">Word</span></span>

- <span data-ttu-id="2ef93-628">cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-628">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ef93-629">Deskjet 프린터로 인쇄할 때 배율 문제가 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-629">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="2ef93-630">표의 텍스트 맞춤 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-630">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="2ef93-631">때때로 무한 루프로 들어가는 변경 내용 추적의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-631">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="2ef93-632">일부 경우에 기존 파일을 저장하면 항상 다른 이름으로 저장 대화 상자가 나타나고 파일이 실제로는 저장되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-632">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="2ef93-633">2개의 문서를 하나로 병합할 때 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-633">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2ef93-634">편집에 대해 보호된 문서의 비교 기능 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-634">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="2ef93-635">종료 시 앱이 중단될 수 있는 다양한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-635">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="2ef93-636">또한 특정 추가 기능 관련 충돌도 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-636">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ef93-637">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-637">Office Suite</span></span>

- <span data-ttu-id="2ef93-638">히라가나와 간지에서 새로운 연호 "레이와"의 철자가 틀리거나 비문법적 표현으로 잘못 식별되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-638">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="2ef93-639">SharePoint 2016에 저장된 파일을 공유하려고 할 때 사용자에게 "죄송합니다. 알 수 없는 이유로 이 파일을 공유할 수 없습니다."라는 메시지가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-639">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="2ef93-640">PowerPoint에서 공동 작성 및 오프라인 편집이 모두 포함된 세션에서 데이터가 손실될 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-640">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="2ef93-641">이를 통해 사용자가 파일을 열 때 발생하는 충돌 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-641">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="2ef93-642">일부 인스턴스에서 동기화 엔진 백업 Sharepoint 파일에 '저장됨'이 표시되지만, 실제로 변경 내용이 저장되지 않아 데이터가 손실될 수 있었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-642">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="2ef93-643">사용자가 Word, Excel 및 PowerPoint 문서를 저장할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-643">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="2ef93-644">이 문제는 새 파일을 만든 후 저장 아이콘을 클릭하거나 Ctrl + S를 눌러 "다른 이름으로 저장 대화 상자" 옵션을 표시하는 사용자에게 영향을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-644">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="2ef93-645">더 이상 사용되지 않는 API에서 벗어나 Word의 충돌 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-645">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="2ef93-646">PowerPoint의 세로 텍스트 상자에서 가타카나 반각글자가 제대로 회전하지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-646">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="2ef93-647">Win7에서는 모든 앱의 리본 메뉴에서 도형 갤러리 삽입을 표시하는 데 약 4초가 걸리는 성능 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-647">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="2ef93-648">백스테이지의 정보 위치 조각에 접근성 정보가 표시되지 않는 버그를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-648">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="2ef93-649">레지스트리 무결성과 관련된 Office 업데이트 프로세스의 안정성이 향상됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-649">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="2ef93-650">2019년 1월 및 7월 분기의 채널 이름을 새 채널 이름으로 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-650">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="2ef93-651">데이터 통신 네트워크에서 업데이트가 예기치 않게 차단되었을 수 있는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-651">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="2ef93-652">상대적인 마감일이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정 버그에 대한 픽스, 이 픽스는 후속 업데이트에 대한 상대적인 마감일도 사용할 수 있도록 해줍니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-652">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2ef93-653">특정 상황에서 Office 바로 가기가 업데이트 후에 사라질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-653">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="2ef93-654">이 업데이트는 Office 바로 가기를 게시할 때 안정성을 높입니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-654">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="2ef93-655">Office 업데이트에서 로컬 또는 네트워크 공유 또는 Configuration Manager에서 제공하는 위치와 같은 의도된 원본 대신 Office CDN에서 파일을 예기치 않게 다운로드했을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-655">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2ef93-656">사용자가 관리자가 아니거나 시스템 계정에 네트워크 연결이 없는 경우에 업데이트가 적용되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-656">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="2ef93-657">Office 업데이트 메시지가 다른 언어로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-657">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="2ef93-658">앞으로 Office 업데이트 메시지 언어가 Windows 표시 언어와 정확하게 일치할 것입니다.  </span><span class="sxs-lookup"><span data-stu-id="2ef93-658">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="2ef93-659">이전에 중단되었을 수 있는 다운로드를 다시 시작하여 Office 업데이트를 다운로드할 때의 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-659">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="2ef93-660">타사의 플러그인에서 Textbox/Shape 자동 맞춤 속성과 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-660">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="2ef93-661">이 변경은 손상된 파일을 연 후 이미지를 올바르게 렌더링하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-661">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="2ef93-662">이 변경은 마커가 포함된 일부 분산형 차트의 느린 렌더링 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-662">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="2ef93-663">대규모 트리 보기에서 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-663">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="2ef93-664">이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-664">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2ef93-665">Office 고객의 보안을 위해 Microsoft Office 업데이트는 이제 SHA-2 알고리즘만을 사용하여 서명됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-665">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="2ef93-666">Office 고객의 보안을 위해 Microsoft Office 업데이트는 이제 SHA-2 알고리듬 만을 사용하여 서명됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-666">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1902-july-14"></a><span data-ttu-id="2ef93-668">버전 1902: 7월 14일</span><span class="sxs-lookup"><span data-stu-id="2ef93-668">Version 1902: July 14</span></span>
<span data-ttu-id="2ef93-669">*버전 1902(빌드 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-669">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="2ef93-670">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)에 보안 업데이트가 나열됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-670">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="2ef93-671">버전 1908: 6월 9일</span><span class="sxs-lookup"><span data-stu-id="2ef93-671">Version 1908: June 09</span></span>
<span data-ttu-id="2ef93-672">*버전 1908(빌드 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-672">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="2ef93-673">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-673">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-675">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-675">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ef93-676">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-676">Excel</span></span>

- <span data-ttu-id="2ef93-677">팀을 통해 Excel 창을 공유할 때 Ctrl+Shift+화살표 키를 사용하여 스크롤한 후 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-677">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2ef93-678">인쇄할 때 양식 컨트롤에 있는 확인란 크기 조정 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-678">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2ef93-679">레거시 "공유 통합 문서" 모드를 사용하여 통합 문서의 새 시트에 변경 내용을 나열할 때 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-679">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ef93-680">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-680">Outlook</span></span>

- <span data-ttu-id="2ef93-681">대규모 HTML 메시지를 전달할 때 사용자에게 잘린 메시지 본문이 표시되던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-681">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ef93-682">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-682">Office Suite</span></span>

- <span data-ttu-id="2ef93-683">2019년 1월 및 7월 분기의 채널 이름을 새 채널 이름으로 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-683">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1902-june-09"></a><span data-ttu-id="2ef93-685">버전 1902: 6월 9일</span><span class="sxs-lookup"><span data-stu-id="2ef93-685">Version 1902: June 09</span></span>
<span data-ttu-id="2ef93-686">*버전 1902(빌드 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-686">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="2ef93-687">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-687">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-689">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-689">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2ef93-690">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-690">Office Suite</span></span>

- <span data-ttu-id="2ef93-691">2019년 1월 및 7월 분기의 채널 이름을 새 채널 이름으로 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-691">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="2ef93-692">C2R 빌드를 나눈 기준 파일에서 더 이상 사용되지 않는 참조를 제거했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-692">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-may-12"></a><span data-ttu-id="2ef93-694">버전 1908: 5월 12일</span><span class="sxs-lookup"><span data-stu-id="2ef93-694">Version 1908: May 12</span></span>
<span data-ttu-id="2ef93-695">*버전 1908(빌드 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-695">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="2ef93-696">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2ef93-696">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-698">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-698">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ef93-699">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-699">Excel</span></span>

- <span data-ttu-id="2ef93-700">색을 기준으로 필터링된 데이터를 다른 너비의 열에 복사하면 값의 붙여넣기가 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-700">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ef93-701">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-701">Outlook</span></span>

- <span data-ttu-id="2ef93-702">최신 Windows 업데이트 적용 후 .msg와 .oft 파일을 여는 경우 작동이 멈추는 현상이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-702">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="2ef93-703">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-703">Word</span></span>

- <span data-ttu-id="2ef93-704">2개의 문서를 하나로 병합할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-704">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2ef93-705">편집에 대해 보호된 문서의 비교 기능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-705">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1902-may-12"></a><span data-ttu-id="2ef93-707">버전 1902: 5월 12일</span><span class="sxs-lookup"><span data-stu-id="2ef93-707">Version 1902: May 12</span></span>
<span data-ttu-id="2ef93-708">*버전 1902(빌드 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-708">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="2ef93-709">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2ef93-709">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-711">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-711">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ef93-712">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-712">Outlook</span></span>

- <span data-ttu-id="2ef93-713">최신 Windows 업데이트 적용 후 .msg와 .oft 파일을 여는 경우 작동이 멈추는 현상이 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-713">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="2ef93-714">기본적으로 보존 정책 레이블에는 보존 기간이 괄호로 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-714">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="2ef93-715">이는 관리자가 정책 이름만 표시하도록 지정할 수 있는 레지스트리 키를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-715">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="2ef93-716">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="2ef93-716">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="2ef93-717">0 = 기본값입니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-717">0 = Default.</span></span>  <span data-ttu-id="2ef93-718">1 = 보존 정책 텍스트의 PolicyName만 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-718">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-may-04"></a><span data-ttu-id="2ef93-720">버전 1908: 5월 4일</span><span class="sxs-lookup"><span data-stu-id="2ef93-720">Version 1908: May 04</span></span>
<span data-ttu-id="2ef93-721">*버전 1908(빌드 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-721">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="2ef93-722">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)에 보안 업데이트가 나열됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-722">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-723">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-723">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ef93-724">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-724">Outlook</span></span>

- <span data-ttu-id="2ef93-725">특정 검색 결과를 선택할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-725">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2ef93-726">첨부 파일 도구에서 “클라우드에 저장” 단추가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-726">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2ef93-727">기본적으로 보존 정책 레이블에는 보존 기간이 괄호로 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-727">By default, retention policy labels display the retention time period in parenthesis.</span></span><span data-ttu-id="2ef93-728">이는 관리자가 정책 이름만 표시하도록 지정할 수 있는 레지스트리 키를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-728"> This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span><span data-ttu-id="2ef93-729"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="2ef93-729"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span><span data-ttu-id="2ef93-730">0 = 기본값 1 = 보존 정책 텍스트의 PolicyName만 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-730"> 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ef93-731">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-731">Office Suite</span></span>

- <span data-ttu-id="2ef93-732">라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-732">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="2ef93-733">버전 1902: 5월 4일</span><span class="sxs-lookup"><span data-stu-id="2ef93-733">Version 1902: May 04</span></span>
<span data-ttu-id="2ef93-734">*버전 1902(빌드 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-734">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-735">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-735">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2ef93-736">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-736">Office Suite</span></span>

- <span data-ttu-id="2ef93-737">라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-737">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version1908april-26"></a><span data-ttu-id="2ef93-738">버전 1908: 4월 26일</span><span class="sxs-lookup"><span data-stu-id="2ef93-738">Version 1908: April 26</span></span>
<span data-ttu-id="2ef93-739">*버전 1908(빌드 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-739">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="2ef93-740"> [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)에 보안 업데이트가 나열됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-740">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-741">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-741">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ef93-742">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-742">Excel</span></span>

- <span data-ttu-id="2ef93-743">VBA 매크로를 사용하여 범위의 내용을 지우면 사용자가 경험할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-743">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2ef93-744">범위에 값을 입력하는 것이 예상한 것 보다 느려지는 VBA 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-744">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2ef93-745">파일을 저장하고 다시 열 때 차트 축의 "값 교점" 속성이 예기치 않게 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-745">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2ef93-746">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-746">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="2ef93-747">OneNote</span><span class="sxs-lookup"><span data-stu-id="2ef93-747">OneNote</span></span>

- <span data-ttu-id="2ef93-748">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 지역화하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-748">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="2ef93-749">버전 1908: 4월 14일</span><span class="sxs-lookup"><span data-stu-id="2ef93-749">Version 1908: April 14</span></span>
<span data-ttu-id="2ef93-750">*버전 1908(빌드 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-750">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="2ef93-751">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2ef93-751">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-753">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-753">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ef93-754">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-754">Excel</span></span>

- <span data-ttu-id="2ef93-755">병합된 셀을 포함하는 열을 삭제할 때 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-755">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="2ef93-756">인쇄 미리 보기로 표시되는 경우 양식 컨트롤에서 텍스트의 크기 조정 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-756">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="2ef93-757">Skype</span><span class="sxs-lookup"><span data-stu-id="2ef93-757">Skype</span></span>

- <span data-ttu-id="2ef93-758">두 개 이상의 대화가 진행되는 동안 탭 대화의 제목 이름이 고정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-758">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ef93-759">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-759">Outlook</span></span>

- <span data-ttu-id="2ef93-760">Outlook을 종료할 때 사용자가 작동 중단을 경험하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-760">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="2ef93-761">일부 시나리오에서 고객에게 빈 회의실 목록이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-761">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ef93-762">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ef93-762">PowerPoint</span></span>

- <span data-ttu-id="2ef93-763">형광펜 관련 문제를 해결했습니다. 어두운 형광펜 색상의 텍스트는 흑백 모드에서 검은 색으로 인쇄됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-763">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="2ef93-764">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-764">Word</span></span>

- <span data-ttu-id="2ef93-765">표의 텍스트 맞춤 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-765">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="2ef93-766">버전 1902: 4월 14일</span><span class="sxs-lookup"><span data-stu-id="2ef93-766">Version 1902: April 14</span></span>
<span data-ttu-id="2ef93-767">*버전 1902(빌드 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-767">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="2ef93-768">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2ef93-768">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-march-10"></a><span data-ttu-id="2ef93-770">버전 1908: 3월 10일</span><span class="sxs-lookup"><span data-stu-id="2ef93-770">Version 1908: March 10</span></span>
<span data-ttu-id="2ef93-771">*버전 1908 (빌드 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-771">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="2ef93-772">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2ef93-772">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-774">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-774">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ef93-775">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-775">Excel</span></span>

- <span data-ttu-id="2ef93-776">통합 문서에 외부 링크가 있는 경우 일부 사용자에게 여러 개의 팝업 창이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-776">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="2ef93-777">일부 현지의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-777">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="2ef93-778">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-778">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2ef93-779">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ef93-779">PowerPoint</span></span>

- <span data-ttu-id="2ef93-780">Shape 관련 문제를 해결했습니다. 붙여넣기 방법: 사용자가 Shape를 사용하여 셰이프를 복사하고 붙여 넣는 경우. 붙여넣기 방법. 선택 대상이 붙여넣기한 셰이프로 변경됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-780">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="2ef93-781">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-781">Word</span></span>

- <span data-ttu-id="2ef93-782">일부 경우에 기존 파일을 저장하면 항상 다른 이름으로 저장 대화 상자가 나타나고 파일이 실제로는 저장되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-782">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2ef93-783">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-783">Office Suite</span></span>

- <span data-ttu-id="2ef93-784">이 변경 사항은 마커가 포함된 일부 분산형 차트의 느린 렌더링 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-784">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="2ef93-785">버전 1902: 3월 10일</span><span class="sxs-lookup"><span data-stu-id="2ef93-785">Version 1902: March 10</span></span>
<span data-ttu-id="2ef93-786">*버전 1902 (빌드 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-786">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="2ef93-787">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2ef93-787">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-february-11"></a><span data-ttu-id="2ef93-789">버전 1908: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="2ef93-789">Version 1908: February 11</span></span>
<span data-ttu-id="2ef93-790">*버전 1908(빌드 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-790">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="2ef93-791">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-791">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-793">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-793">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ef93-794">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-794">Excel</span></span>

- <span data-ttu-id="2ef93-795">이 업데이트는 VBA를 사용하여 차트의 머리글/바닥글에 이미지를 추가할 때마다 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-795">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="2ef93-796">인쇄 미리보기 또는 인쇄 시 그룹 상자 컨트롤의 테두리가 보이지 않던 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-796">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="2ef93-797">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-797">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2ef93-798">차트가 포함된 통합 문서를 저장할 때 차트 머리글의 이미지 파일 크기가 커지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-798">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="2ef93-799">선택 범위를 상호 참조 도서와 동기화하여 상호 참조 도서에서 DBCS 문자가 손상되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-799">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="2ef93-800">자동 맞춤을 사용하여 행 높이를 조정할 때 확인란 컨트롤이 축소될 수있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-800">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="2ef93-801">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-801">Outlook</span></span>

- <span data-ttu-id="2ef93-802">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-802">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2ef93-803">충돌 메시지를 처리할 때 사용자에게 동기화 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-803">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="2ef93-804">Outlook을 시작할 때 사용자가 프로필을 로딩할 때 화면이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-804">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="2ef93-805">보기를 변경할 때 사용자에게 간헐적인 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-805">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="2ef93-806">Citrix 환경에서 30개 이상의 캘린더를 볼 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-806">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="2ef93-807">[여기](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)에는 이전 버전에 대해 문서화된 개별 KB가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-807">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="2ef93-808">사용자가 공유 일정 폴더를 OST와 동기화하는 데 문제가있어 이러한 폴더와 상호 작용할 때 권한 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-808">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2ef93-809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ef93-809">PowerPoint</span></span>

- <span data-ttu-id="2ef93-810">복사-붙여넣기 시나리오 개선 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-810">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="2ef93-811">공동 작업 사용자 간에 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-811">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="2ef93-812">증분 방식으로 열린 파일에 둘 이상의 포함된 미디어 스트림이 있는 슬라이드가 포함되어 있을 때 발생할 수있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-812">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="2ef93-813">PowerPoint를 처음 시작할 때 신뢰할 수 없는 추가 기능에 대해 보안 경고 메시지 표시줄이 나타나지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-813">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="2ef93-814">Project</span><span class="sxs-lookup"><span data-stu-id="2ef93-814">Project</span></span>

- <span data-ttu-id="2ef93-815">기본 일정이 변경될 때 리소스 일정이 업데이트되지 않아 작업표와 프로젝트 계획 간에 실제 작업이 다를 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-815">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="2ef93-816">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-816">Word</span></span>

- <span data-ttu-id="2ef93-817">더 이상 사용되지 않는 API에서 이동하여 Word의 충돌 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-817">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ef93-818">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-818">Office Suite</span></span>

- <span data-ttu-id="2ef93-819">이 변경은 손상된 파일을 연 후 이미지를 올바르게 렌더링하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-819">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1902-february-11"></a><span data-ttu-id="2ef93-821">버전 1902: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="2ef93-821">Version 1902: February 11</span></span>
<span data-ttu-id="2ef93-822">*버전 1902 (빌드 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-822">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="2ef93-823">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-823">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-825">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-825">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2ef93-826">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-826">Outlook</span></span>

- <span data-ttu-id="2ef93-827">암호화된 전자 메일을 보낼 때 사용자에게 "암호화 알고리즘이 지원되지 않습니다." 오류가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-827">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="2ef93-828">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-828">Word</span></span>

- <span data-ttu-id="2ef93-829">더 이상 사용되지 않는 API에서 이동하여 Word의 충돌 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-829">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

## <a name="version-1808-february-11"></a><span data-ttu-id="2ef93-832">버전 1808: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="2ef93-832">Version 1808: February 11</span></span>
<span data-ttu-id="2ef93-833">*버전 1808 (빌드 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-833">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="2ef93-834">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-834">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-january-14"></a><span data-ttu-id="2ef93-836">버전 1908: 1월 14일</span><span class="sxs-lookup"><span data-stu-id="2ef93-836">Version 1908: January 14</span></span>
<span data-ttu-id="2ef93-837">*버전 1908(빌드 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-837">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="2ef93-838">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2ef93-838">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="2ef93-840">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="2ef93-840">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2ef93-841">Access</span><span class="sxs-lookup"><span data-stu-id="2ef93-841">Access</span></span>

- <span data-ttu-id="2ef93-842">**데이터베이스 개체에 탭 유지:** 활성 탭이 무엇인지 명확하게 구분할 수 있고, 간편하게 끌어서 순서를 변경할 수 있고, 클릭 한 번으로 데이터베이스 개체를 닫을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-842">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="2ef93-843">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-843">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ef93-844">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-844">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ef93-845">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-845">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2ef93-846">**더 많은 공간을 사용하여 확대/축소:** 확대/축소 상자의 크기를 키우고, 글꼴을 변경할 수 있습니다. 확대/축소에 이러한 설정이 모두 저장됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-846">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="2ef93-847">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-847">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="2ef93-848">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-848">Excel</span></span>

- <span data-ttu-id="2ef93-849">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-849">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ef93-850">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-850">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ef93-851">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-851">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2ef93-852">**콘텐츠 도달 범위 늘리기:** 접근성 높은 프레젠테이션을 만들어야 하나요?</span><span class="sxs-lookup"><span data-stu-id="2ef93-852">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="2ef93-853">진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-853">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2ef93-854">검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-854">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2ef93-855">**해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="2ef93-855">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2ef93-856">파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-856">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2ef93-857">**생동감 있는 워크시트 보기:** 애니메이션 3D 그래픽을 삽입하여 워크북을 통해 심장 박동, 행성 궤도, 공룡 난동 모습 등을 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-857">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="2ef93-858">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-858">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="2ef93-p171">**자세한 데이터 분석:** 새로운 아이디어 단추는 데이터에서 패턴을 찾아서 인텔리전트 맞춤형 제안을 만듭니다. [자세히 알아보기](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="2ef93-p171">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="2ef93-861">**공동 작업이 쉬워졌습니다.** 공동 작성 기능이 향상되면 조건부 서식, 셀 스타일 등을 사용하여 작업할 때 변경 내용이 공동 작업자와 원활하게 통합됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-861">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="2ef93-862">**유사한 열의 테이블 조인:** 가져오기 및 변환 기능(파워 쿼리)은 테이블 병합을 위해 열을 비교하는 경우 근사 텍스트 매칭 논리(퍼지 매칭)를 특징으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-862">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="2ef93-863">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-863">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="2ef93-864">**파워 쿼리 기능 향상을 통한 신속한 코드:** 자동 완성 및 구문 색상을 사용하여 신속하게 코드를 완성하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-864">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="2ef93-865">함수, 열, 매개 변수를 쉽게 검색할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-865">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="2ef93-866">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-866">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ef93-867">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-867">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2ef93-868">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-868">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="2ef93-869">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-869">Outlook</span></span>

- <span data-ttu-id="2ef93-870">**Outlook 사용자 환경이 업데이트됨:** 출시 예정을 사용하여 이전에 미리 볼 수 있었던 간소화된 환경은 가장 중요한 작업에 집중할 수 있도록 설계되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-870">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="2ef93-871">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-871">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="2ef93-872">**사용자 지정이 가능한 간단한 리본:** 가장 많이 사용하는 단추가 한 행에 표시되어 간편합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-872">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="2ef93-873">클래식 및 요약 보기 간의 간편한 전화 및 명령 고정/고정 해제</span><span class="sxs-lookup"><span data-stu-id="2ef93-873">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="2ef93-874">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-874">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="2ef93-875">**메시지를 전달하는 동안에도 작업 지속 가능:** Outlook이 이제 백그라운드에서 메시지를 전달합니다. 따라서 폴더 간에 많은 메시지를 주고 받는 동안에도 작업을 계속할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-875">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="2ef93-876">\*\*연달아 있는 모임 사이에 시간 넣기: \*\*모임이 기본적으로 5~10분 일찍 끝나도록 설정하여 참석자에게 잠시 숨을 돌리거나 장소를 이동할 시간을 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-876">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="2ef93-877">**자주 하는 작업 선택:** 플래그 및 삭제를 사용하지 않나요?</span><span class="sxs-lookup"><span data-stu-id="2ef93-877">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="2ef93-878">[보관] 또는 [읽은 상태로 표시]는 어떤가요?</span><span class="sxs-lookup"><span data-stu-id="2ef93-878">How about Archive or Mark as Read?</span></span> <span data-ttu-id="2ef93-879">가장 많이 사용하는 명령으로 빠른 작업 메뉴를 사용자 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-879">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="2ef93-p178">**밈하는 항목 표시:** 텍스트 또는 정적 이미지로 가능하지 않은 경우 애니메이션 GIF를 의도하는 바를 나타냅니다. [자세히 알아보기](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="2ef93-p178">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="2ef93-882">**빠르게 계정 추가:** 계정 설정 기능이 향상되어 Outlook에서 2단계 인증을 사용하여 Outlook.com 및 Gmail 계정을 추가하는 것이 그 어느 때보다 쉬워졌습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-882">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="2ef93-883">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-883">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="2ef93-884">**동기화 제한 문제 해결:** Outlook의 기능 향상으로 폴더 제한이 사라지고 공유된 편지함을 동기화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-884">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="2ef93-885">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-885">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ef93-886">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-886">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2ef93-887">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-887">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="2ef93-888">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ef93-888">PowerPoint</span></span>

- <span data-ttu-id="2ef93-889">**더 나은 변신:** 셰이프에 이름을 지정하여 셰이프의 모핑 과정을 더 효율적으로 관리하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-889">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="2ef93-890">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-890">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="2ef93-891">**해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="2ef93-891">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2ef93-892">파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-892">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2ef93-893">**콘텐츠 도달 범위 늘리기:** 접근성 높은 프레젠테이션을 만들어야 하나요?</span><span class="sxs-lookup"><span data-stu-id="2ef93-893">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="2ef93-894">진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-894">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2ef93-895">검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-895">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2ef93-896">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-896">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ef93-897">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-897">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ef93-898">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-898">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2ef93-899">**온라인 비디오의 새로운 홈:** 조직의 모든 사람이 볼 수 있도록 비디오를 Microsoft Stream에 저장하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-899">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="2ef93-900">비디오 링크를 삽입하고 파일 크기의 일부로 멀티미디어 프레젠테이션을 즐겨보세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-900">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="2ef93-901">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-901">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="2ef93-902">**변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-902">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2ef93-p186">**대상 그룹에 퀴즈를 내거나 설문 조사하기:** 슬라이드에 퀴즈 또는 설문 조사를 넣습니다. Office가 응답을 수집하고 저장합니다. [자세한 정보](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="2ef93-p186">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="2ef93-p187">**그 어느 때보다 쉬운 온라인 비디오 삽입:** 슬라이드에 Vimeo 또는 YouTube 비디오를 삽입해야 하나요? 비디오 페이지 링크만 있으면 됩니다. [자세히 알아보기](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="2ef93-p187">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="2ef93-909">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-909">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ef93-910">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-910">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2ef93-911">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-911">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="2ef93-912">Project</span><span class="sxs-lookup"><span data-stu-id="2ef93-912">Project</span></span>

- <span data-ttu-id="2ef93-913">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-913">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ef93-914">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-914">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ef93-915">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-915">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="2ef93-916">Visio</span><span class="sxs-lookup"><span data-stu-id="2ef93-916">Visio</span></span>

- <span data-ttu-id="2ef93-917">**프로세스 다이어그램을 Word로 내보내기:** Word 문서에 셰이프 및 메타데이터 등의 다이어그램 콘텐츠를 자동으로 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-917">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="2ef93-918">그런 후 문서를 사용자 지정하여 프로세스 지침 및 작업 설명서를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-918">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="2ef93-919">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-919">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="2ef93-920">**놀랄 만한 수준의 데이터 순서도:** 데이터 시각화 도우미 순서도를 위한 멋진 새 레이아웃은 깔끔하고 정돈되어 있으며 이해하기 쉽습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-920">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="2ef93-921">디자인 탭을 클릭하여 옵션을 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="2ef93-921">Click the Design tab for options.</span></span>

- <span data-ttu-id="2ef93-922">**기본적으로 제공되는 Azure 스텐실:** 수십 개의 Azure 스텐실을 사용하여 클라우드 앱을 디자인하거나 아키텍처를 계획합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-922">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="2ef93-923">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-923">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="2ef93-p193">**깨진 Excel 링크 해결:** 데이터 시각화 도우미 다이어그램에 연결된 Excel 통합 문서를 찾을 수 없습니까? 링크를 다시 연결하면 정상으로 돌아옵니다. [자세히 알아보기](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="2ef93-p193">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="2ef93-927">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-927">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ef93-928">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-928">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ef93-929">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-929">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2ef93-930">**Power BI에서 Visio 시각적 개체 내보내기** Power BI 보고서를 PDF, PowerPoint 파일 등으로 내보낼 때 Power BI용 Visio 시각적 개체가 올바르게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-930">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="2ef93-931">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-931">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="2ef93-932">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-932">Word</span></span>

- <span data-ttu-id="2ef93-933">**더 많은 페이지 색상을 사용하도록 학습 도구 모드에 추가 지원 제공:** Word의 학습 도구에 페이지 테마 색상에 대한 지원이 추가되어, 페이지의 배경색을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-933">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="2ef93-934">많은 사람들이 흑백 또는 검정색 배경으로 읽는 것에 어려움을 느끼고 있으므로 PC 및 Mac의 Word에서 색상 선택을 확장했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-934">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="2ef93-p197">**잉크 편집기로 자연스럽게 편집 가능:** 펜을 사용하여 단일 스트로크로 단어를 분할 또는 조인하거나, 새 줄을 추가하거나, 단어를 삽입할 수 있습니다. [자세한 정보](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="2ef93-p197">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="2ef93-p198">**평범한 문서를 훌륭한 문서로 개선하기:** 모든 장치에서 문서가 잘 보이도록 공유하기 쉬운 대화형의 웹 페이지로 변환합니다. [자세히 알아보기](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="2ef93-p198">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="2ef93-939">**콘텐츠 도달 범위 늘리기:** 접근성 높은 문서를 만들어야 하나요?</span><span class="sxs-lookup"><span data-stu-id="2ef93-939">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="2ef93-940">진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-940">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2ef93-941">검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-941">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2ef93-942">**해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="2ef93-942">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2ef93-943">파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-943">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2ef93-944">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-944">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2ef93-945">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-945">Switching between them has never been easier.</span></span> [<span data-ttu-id="2ef93-946">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-946">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2ef93-p202">**라인 포커스로 가독성 개선:** 부드럽게 줄 단위로 문서를 넘길 수 있습니다. 한 번에 볼 때 1줄, 2줄, 또는 5줄에 포커스를 두도록 조정합니다. [자세히 알아보기](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="2ef93-p202">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="2ef93-950">**변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-950">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2ef93-951">**\@멘션으로 주의 끌기:** 메모에 @멘션을 사용하여 입력이 필요하다는 사실을 동료들에게 알립니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-951">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="2ef93-952">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-952">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="2ef93-953">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-953">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2ef93-954">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-954">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2ef93-955">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-955">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="2ef93-956">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-956">Office Suite</span></span>

- <span data-ttu-id="2ef93-957">**빠른 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="2ef93-957">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2ef93-958">원하는 파일을 찾으려면 파일 > 열기 탭의 검색 상자에 입력합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-958">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="2ef93-959">**변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-959">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2ef93-960">**개인 정보 제어:** 진단 데이터 및 연결된 환경에 대한 업데이트 및 향상된 신규 컨트롤 작업</span><span class="sxs-lookup"><span data-stu-id="2ef93-960">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="2ef93-961">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-961">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="2ef93-962">**Office 아이콘이 새롭게 단장했습니다.** 간단하고 강력하며 지능적인 Office 환경을 반영하여 Office 아이콘이 다시 디자인되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-962">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="2ef93-963">**Microsoft Teams 설치:** Microsoft Teams는 기본적으로 Office 365 ProPlus 기존 설치에 설치됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-963">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="2ef93-964">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="2ef93-964">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-967">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-967">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2ef93-968">Access</span><span class="sxs-lookup"><span data-stu-id="2ef93-968">Access</span></span>

- <span data-ttu-id="2ef93-969">이 업데이트는 합계와 같은 집계가 결과를 정수 값으로 자를 수 있는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-969">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="2ef93-970">이 업데이트는 원격 테이블(예: SQL Server 테이블)로의 참조를 포함하는 통합 쿼리가 Access를 닫고 다시 시작하도록 할 수 있는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-970">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="2ef93-971">이 업데이트는 업데이트 쿼리가 실행되거나 UPDATE 문이 SQL에 사용될 때 &quot;쿼리가 손상되었습니다&quot; 오류를 일으킬 수있는 Microsoft Access의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-971">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2ef93-972">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-972">Excel</span></span>

- <span data-ttu-id="2ef93-973">문서 타이틀에 대한 네덜란드어 키 설명이 Alt-G로 변경되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-973">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="2ef93-974">도형 또는 양식 컨트롤에 할당된 매크로가 잘못된 오류 메시지를 표시하거나 잘못된 대상 범위에서 작동하는 Excel의 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-974">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="2ef93-975">첫 번째 항목을 발견한 후 대화 상자에서 포커스가 있는 위치가 찾기 및 바꾸기로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-975">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="2ef93-976">이를 통해 다른 사용자와 공동 작성 세션에 있는 동안 피벗 테이블이 정렬되는 방식을 변경하고 새로 고치면 충돌이 트리거될 수 있는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-976">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="2ef93-977">OLAP PivotTable의 필터가 큐브에서 제거된 값으로 설정되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-977">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="2ef93-978">차트 템플릿을 사용하여 차트를 삽입할 때 미리 보기에 사용되는 색을 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-978">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="2ef93-979">시리즈 컬렉션을 변경할 때 분산형 차트가 제대로 렌더링되지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-979">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="2ef93-980">셀을 삽입하거나 삭제하는 경우 폭포 차트와 깔때기형 차트가 테이블로 동기화되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-980">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="2ef93-981">사용자에게 통합 문서를 다시 열어서 변경 내용을 적용하라는 메시지가 표시되는 Excel의 병합 충돌 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-981">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="2ef93-982">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-982">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2ef93-983">최소화된 창을 활성화하는 매크로 런타임 오류를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-983">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="2ef93-984">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-984">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2ef93-985">다른 사용자와 공동 작성하는 경우 표의 옆에 잘라내어 붙여 넣는 작업이 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-985">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="2ef93-986">매크로가 실행되는 사용자 지정 속성을 변경할 때 공동 작성 작업을 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-986">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="2ef93-987">추가 기능을 통해 연 WPF(Windows Presentation Foundation) 양식의 콤보 상자에서 항목을 선택할 수 없는 문제가 발생했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-987">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="2ef93-988">통합 문서가 열려있지 않은 상태에서 최근 파일을 검색할 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-988">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2ef93-989">비동기식 사용자 정의 함수의 성능 문제로 인해 함수가 동기식으로 실행되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-989">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="2ef93-990">병합된 셀이 있는 열을 삭제하는 성능이 크게 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-990">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="2ef93-991">스크롤 후 셀을 선택하면 잘못된 셀이 선택되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-991">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2ef93-992">Lookup 함수에서 오류가 반환될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-992">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="2ef93-993">이전 버전의 Office에서 만든 통합 문서를 현재 버전의 Office에서 열었을 때 Excel이 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-993">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="2ef93-994">파일에 광범위한 조건부 서식이 있는 경우 글꼴색 단추를 클릭하면 성능이 저하되는 문제.</span><span class="sxs-lookup"><span data-stu-id="2ef93-994">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="2ef93-995">인쇄 미리 보기의 인쇄 영역이 올바르지 않았던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-995">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="2ef93-996">신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 오류를 발생시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-996">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2ef93-997">색 기준 필터링의 성능이 대폭 향상되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-997">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="2ef93-998">일부 보호된 시트에서 하이퍼링크를 붙여 넣을 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-998">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="2ef93-999">추가 기능 관리자에서 검색할 때 16개 이상의 추가 기능이 표시되도록 활성화했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-999">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="2ef93-1000">이 변경 내용은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1000">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2ef93-1001">cid 링크: 이제 Outlook 메시지의 이미지는 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1001">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ef93-1002">이 업데이트는 Office 문서가 "업로드 실패" 메시지와 함께 비즈니스용 OneDrive에 업로드되지 않을 수 있는 오류를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1002">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="2ef93-1003">Excel 아이디어 기능에서, Win32 클라이언트에 있는 아이디어 버튼을 클릭하여 추가 기능을 로드할 때 발생하는 오류를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1003">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ef93-1004">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-1004">Outlook</span></span>

- <span data-ttu-id="2ef93-1005">cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1005">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ef93-1006">사서함을 기본 인증에서 최신 인증으로 업그레이드한 사용자가 Outlook 프로필에 연결된 잘못된 계정으로 끝나는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1006">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="2ef93-1007">웹 추가 기능이 디지털 권한 관리 메시지에 액세스하지 않아야 함에도 액세스하게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1007">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="2ef93-1008">일부 safelinks에서 간단한 호버 URL이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1008">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="2ef93-1009">이를 통해 첨부 파일 차단 논리를 업데이트하여 Outlook에서 Python 첨부 파일도 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1009">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2ef93-1010">POP3 사용자의 하위 집합에서 설정에 관계없이 일반 텍스트로 서식이 지정된 모든 전자 메일을 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1010">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="2ef93-1011">이 수정은 HTML 서식이 지정된 메시지의 보기를 복원합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1011">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="2ef93-1012">기본 일정의 항목을 그룹 일정에 복사할 때 사용자에게 사용 권한 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1012">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="2ef93-1013">사용자가 화면 판독기를 통해 위치 제안에 액세스할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1013">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="2ef93-1014">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 상당한 지연이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1014">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2ef93-1015">매우 긴 Outlook 세션에서 메모리 누수를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1015">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2ef93-1016">규칙 대화 상자를 열 때 "이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다." 프롬프트가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1016">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2ef93-1017">사용자가 특정 Safelinks와 상호 작용할 때 Outlook에서 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1017">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="2ef93-1018">대리인이 지정된 모임 요청에 응답했는지 여부와 관련하여 관리자에게 모호성을 유발하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1018">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="2ef93-1019">일부 AutoDiscover 응답을 처리할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1019">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2ef93-1020">사용자가 계정 만들기 컨텍스트에서 지원 센터에 문의하려고 할 때 사용자에게 "확인" 버튼이 있는 빈 메시지 상자가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1020">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2ef93-1021">이 변경으로 인해 관리자가 정책을 사용하여 UPN에 대한 자동 검색 인증 프롬프트에서 제공된 계정 전자 메일을 원하는 대로 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1021">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="2ef93-1022">기본적으로 AutoDiscover는 가능한 경우 계정 UPN을 선호합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1022">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="2ef93-1023">사용자가 Modern Groups에 대한 검색 실패를 보게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1023">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="2ef93-1024">특정 시나리오에서 Outlook 사용자가 “비밀번호 필요” 상태에 멈춰있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1024">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="2ef93-1025">사용자에게 회의실의 가용 시간 이외의 시간에 발생한 모임에 대해 사용자에게 회의실 제안이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1025">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="2ef93-1026">암호화된 전자 메일을 보낼 때 사용자에게 "암호화 알고리즘이 지원되지 않습니다." 오류가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1026">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="2ef93-1027">비영어 사용자에게 메일의 제목 줄이 너무 작게 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1027">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="2ef93-1028">보조 Exchange 계정을 추가할 때 만들어진 중복된 특수 폴더가 일부 사용자에게 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1028">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="2ef93-1029">사용자가 "부재 중 대화" 메시지에서 규칙을 만들려고 할 때 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1029">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="2ef93-1030">SMIME 알고리즘 선택 관련 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1030">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2ef93-1031">대체 보낸 사람을 사용할 때 정책 팁이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1031">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="2ef93-1032">Outlook 프로세스에서 메모리 누수가 사용자에게 관찰되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1032">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2ef93-1033">현재 상태 정보를 업데이트할 때 간헐적으로 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1033">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="2ef93-1034">현재 폴더 검색에 간헐적으로 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1034">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="2ef93-1035">일부 사용자가 Outlook에 대한 클라우드 설정을 검색할 때 사용자에게 인증 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1035">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="2ef93-1036">피드백 검색 환경을 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1036">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2ef93-1037">일부 AutoDiscover 응답을 처리할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1037">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2ef93-1038">현재 상태 정보를 업데이트할 때 간헐적으로 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1038">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ef93-1039">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ef93-1039">PowerPoint</span></span>

- <span data-ttu-id="2ef93-1040">일부 추가 기능이 차트의 도형 주변에 예기치 않은 오류를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1040">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="2ef93-1041">cid 링크: 이제 Outlook 메시지의 이미지는 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1041">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ef93-1042">이 변경으로 인해 PowerPoint 비디오 컨트롤의 액세스 가능한 이름이 복원되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1042">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="2ef93-1043">일부 애니메이션이 시작되지 않도록 하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1043">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="2ef93-1044">한 프레젠테이션에서 다른 프레젠테이션으로 슬라이드를 복사하면 마스터가 중복될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1044">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="2ef93-1045">지원되지 않는 버전에서 열었을 경우 최신 메모가 포함된 파일에 노란색 경고가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1045">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="2ef93-1046">안정성 수정: 타사 추가 기능이 PowerPoint와 충돌할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1046">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="2ef93-1047">PowerPoint의 세로 텍스트 상자에서 가타카나 반각글자가 제대로 회전하지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1047">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="2ef93-1048">Project</span><span class="sxs-lookup"><span data-stu-id="2ef93-1048">Project</span></span>

- <span data-ttu-id="2ef93-1049">Windows 7 사용자가 Project Web App 및 SharePoint 사이트에서 프로젝트를 열 수 있도록 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1049">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="2ef93-1050">읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 식별했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1050">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="2ef93-1051">모든 명령 수준으로 리소스 초과 할당이 제대로 해결되지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1051">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="2ef93-1052">과업에 대한 작업이 0인 과제가 있는 경우 해당 과업이 완성으로 표시되지 않고 항상 99%로 표시되는 문제.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1052">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="2ef93-1053">Visio</span><span class="sxs-lookup"><span data-stu-id="2ef93-1053">Visio</span></span>

- <span data-ttu-id="2ef93-1054">Visio에서 SVG로 내보내기가 다양한 도형에서 실패했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1054">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="2ef93-1055">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-1055">Word</span></span>

- <span data-ttu-id="2ef93-1056">Word를 사용하여 문서를 열 경우 이 변경을 통해 성능이 개선됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1056">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="2ef93-1057">cid 링크: 이제 Outlook 메시지의 이미지는 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1057">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2ef93-1058">Deskjet 프린터로 인쇄할 때 배율 문제가 발생할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1058">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="2ef93-1059">변경 내용 추적 시 때때로 무한 루프로 들어가는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1059">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="2ef93-1060">종료 시 앱이 중단될 수 있는 여러 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1060">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="2ef93-1061">또한 특정 추가 기능 관련 충돌도 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1061">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2ef93-1062">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="2ef93-1062">Office Suite</span></span>

- <span data-ttu-id="2ef93-1063">히라가나와 간지에서 새로운 연호 "레이와"의 철자가 틀리거나 비문법적 표현으로 잘못 식별되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1063">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="2ef93-1064">SharePoint 2016에 저장된 파일을 공유하려고 할 때 사용자에게 "죄송합니다. 알 수 없는 이유로 이 파일을 공유할 수 없습니다."라는 메시지가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1064">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="2ef93-1065">PowerPoint에서 공동 작성 및 오프라인 편집이 모두 포함된 세션에서 데이터가 손실될 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1065">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="2ef93-1066">이를 통해 사용자가 파일을 열 때 발생하는 충돌 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1066">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="2ef93-1067">PowerPoint 사용자가 온라인으로 프레젠테이션할 때 오류가 발생하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1067">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="2ef93-1068">일부 인스턴스에서 동기화 엔진 백업 Sharepoint 파일에 '저장됨'이 표시되지만, 실제로 변경 내용이 저장되지 않아 데이터가 손실될 수 있었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1068">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="2ef93-1069">사용자가 Word, Excel 및 PowerPoint 문서를 저장할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1069">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="2ef93-1070">이 문제는 새 파일을 만든 후 저장 아이콘을 클릭하거나 Ctrl + S를 눌러 "다른 이름으로 저장 대화 상자" 옵션을 표시하는 사용자에게 영향을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1070">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="2ef93-1071">Win7에서는 모든 앱의 리본 메뉴에서 도형 갤러리 삽입을 표시하는 데 약 4초가 걸리는 성능 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1071">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="2ef93-1072">백스테이지의 정보 위치 조각에 접근성 정보가 표시되지 않는 버그를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1072">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="2ef93-1073">레지스트리 무결성과 관련된 Office 업데이트 프로세스의 안정성이 향상됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1073">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="2ef93-1074">Office 업데이트에서 로컬 또는 네트워크 공유 또는 Configuration Manager에서 제공하는 위치와 같은 의도된 원본 대신 Office CDN에서 파일을 예기치 않게 다운로드했을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1074">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2ef93-1075">Office 업데이트 메시지가 다른 언어로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1075">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="2ef93-1076">앞으로 Office 업데이트 메시지 언어가 Windows 표시 언어와 정확하게 일치할 것입니다.  </span><span class="sxs-lookup"><span data-stu-id="2ef93-1076">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="2ef93-1077">사용자가 관리자가 아니고 시스템 계정에 네트워크 연결이 없는 특정한 경우에 업데이트가 적용되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1077">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="2ef93-1078">특정 상황에서 Office 바로 가기가 업데이트 후에 사라질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1078">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="2ef93-1079">이 업데이트는 Office 바로 가기를 게시할 때 안정성을 높입니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1079">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="2ef93-1080">데이터 통신 네트워크에서 업데이트가 예기치 않게 차단될 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1080">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="2ef93-1081">상대적인 마감일이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정 버그에 대한 픽스, 이 픽스는 후속 업데이트에 대한 상대적인 마감일도 사용할 수 있도록 해줍니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1081">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2ef93-1082">이전에 중단되었을 수 있는 다운로드를 다시 시작하여 Office 업데이트를 다운로드할 경우의 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1082">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="2ef93-1083">타사의 플러그인에서 Textbox/Shape Autofit 속성과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1083">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="2ef93-1084">대규모 트리 보기에서 충돌이 발생할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1084">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="2ef93-1085">Office 고객의 보안을 위해 Microsoft Office 업데이트는 이제 SHA-2 알고리듬 만을 사용하여 서명됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1085">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1902-january-14"></a><span data-ttu-id="2ef93-1087">버전 1902: 1월 14일</span><span class="sxs-lookup"><span data-stu-id="2ef93-1087">Version 1902: January 14</span></span>
<span data-ttu-id="2ef93-1088">*버전 1902(빌드 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-1088">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="2ef93-1089">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2ef93-1089">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="2ef93-1091">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="2ef93-1091">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2ef93-1092">Excel</span><span class="sxs-lookup"><span data-stu-id="2ef93-1092">Excel</span></span>

- <span data-ttu-id="2ef93-1093">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1093">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="2ef93-1094">Outlook</span><span class="sxs-lookup"><span data-stu-id="2ef93-1094">Outlook</span></span>

- <span data-ttu-id="2ef93-1095">암호화된 전자 메일을 보낼 때 사용자에게 "암호화 알고리즘이 지원되지 않습니다." 오류가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1095">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2ef93-1096">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2ef93-1096">PowerPoint</span></span>

- <span data-ttu-id="2ef93-1097">지원되지 않는 버전에서 열었을 경우 최신 메모가 포함된 파일에 노란색 경고가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1097">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="2ef93-1098">Word</span><span class="sxs-lookup"><span data-stu-id="2ef93-1098">Word</span></span>

- <span data-ttu-id="2ef93-1099">Word를 사용하여 문서를 열 경우 이 변경을 통해 성능이 개선됩니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1099">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1808-january-14"></a><span data-ttu-id="2ef93-1101">버전 1808: 1월 14일</span><span class="sxs-lookup"><span data-stu-id="2ef93-1101">Version 1808: January 14</span></span>
<span data-ttu-id="2ef93-1102">*버전 1808(빌드 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="2ef93-1102">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="2ef93-1103">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2ef93-1103">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

> [!NOTE]
> <span data-ttu-id="2ef93-1105">Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2ef93-1105">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (관리 센터 메타데이터 콘텐츠를 수정하지 마세요. 시작)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|version-2002-july-14|)
[//]: # (관리 센터 메타데이터 콘텐츠를 수정하지 마세요. 끝)
