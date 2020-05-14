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
description: 2020년 Microsoft 365 앱에 대한 반기 채널(대상 지정) 릴리스의 릴리스 정보를 IT 전문가에게 제공합니다.
ms.openlocfilehash: 8cf9ae0e43417941ec588ff3c45835d7d613488a
ms.sourcegitcommit: 1c78e7def81461cd758dded4b443b5dcffa17461
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/12/2020
ms.locfileid: "44211233"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a><span data-ttu-id="7ad6d-103">2020년 반기 채널(대상 지정) 릴리스에 대한 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-103">Release notes for Semi-Annual Channel (Targeted) releases in 2020</span></span>

<span data-ttu-id="7ad6d-104">이러한 릴리스 정보는 엔터프라이즈용 Microsoft 365 앱, 비즈니스용 Microsoft 365 앱, Project와 Visio 데스크톱 앱의 구독 버전에 대한 2020년 반기별 채널(대상 지정) 업데이트에 포함된 새로운 기능 및 비보안 업데이트 관련 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel (Targeted) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="7ad6d-105">당사는 Microsoft 365 앱에 대한 업데이트 채널을 일부 변경하고 있습니다. 여기에는 새 업데이트 채널 추가(월별 엔터프라이즈 채널) 및 기존 업데이트 채널의 이름 변경 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="7ad6d-106">자세한 내용은 [이 문서를 검토하세요](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="7ad6d-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2002-may-12"></a><span data-ttu-id="7ad6d-107">버전 2002: 5월 12일</span><span class="sxs-lookup"><span data-stu-id="7ad6d-107">Version 2002: May 12</span></span>
<span data-ttu-id="7ad6d-108">*버전 2002 (빌드 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="7ad6d-108">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="7ad6d-109">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7ad6d-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="7ad6d-111">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="7ad6d-111">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="7ad6d-112">Excel</span><span class="sxs-lookup"><span data-stu-id="7ad6d-112">Excel</span></span>

- <span data-ttu-id="7ad6d-113">다수의 다양한 통합 문서(특히 숨겨진 창)를 참조하는 통합 문서를 열면 예상보다 느리게 열립니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-113">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="7ad6d-114">경우에 따라 CSV 파일을 여는 데 소요되는 시간이 예상보다 더 오래 걸렸습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-114">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="7ad6d-115">다른 확대/축소 단계를 사용하는 통합 문서 사이를 전환할 때 일부의 경우에 Excel의 작동이 중단될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-115">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="7ad6d-116">범위에 값을 입력하는 것이 예상한 것 보다 느려지는 VBA 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-116">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="7ad6d-117">색을 기준으로 필터링 된 열에서 복사한 데이터가 가끔 제대로 붙여 넣어지지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-117">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="7ad6d-118">일부 경우에 피벗 테이블을 포함하는 시트를 복사한 후 Excel의 작동이 중단되는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-118">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="7ad6d-119">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효화 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-119">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="7ad6d-120">파일을 저장하고 다시 열 때 차트 축의 "값 교점" 속성이 예기치 않게 변경되는 문제를 해결 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-120">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="7ad6d-121">Range.Value와 Range.Value2 (VBA)를 사용하면 수식이 동적 배열로 입력됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-121">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="7ad6d-122">OneNote</span><span class="sxs-lookup"><span data-stu-id="7ad6d-122">OneNote</span></span>

- <span data-ttu-id="7ad6d-123">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 지역화하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-123">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="7ad6d-124">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 표시하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-124">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="7ad6d-125">OneNote 2016에서 버전 기록 페이지의 수와 동기화 빈도를 일시적으로 줄임으로써 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-125">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="7ad6d-126">OneNote 2016에서 일시적으로 휴지통을 비활성화하여 동기화 및 서비스 안정성을 개선시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-126">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="7ad6d-127">사용자가 일반적으로 휴지통으로 전송될 데이터를 삭제하려고 하면, 사용자가 데이터를 유지할지 아니면 영구적으로 삭제할지 묻는 메시지가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-127">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="7ad6d-128">OneNote 2016에서 동기화 빈도를 일시적으로 조정하여 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-128">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="7ad6d-129">OneNote 2016에서 사용자가 해당 페이지로 이동할 때까지 온라인 전자 필기장에 있는 파일 및 이미지의 다운로드를 일시적으로 지연시켜 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-129">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="7ad6d-130">OneNote 2016에서 앱 내 비디오 녹화를 일시적으로 사용하지 않도록 설정하여 동기화 및 서비스 안정성을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-130">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="7ad6d-131">로컬 노트북은 이 조치의 영향을받지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-131">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="7ad6d-132">OneNote 2016에서 새로운 내장 첨부 파일의 최대 허용 크기를 50MB로 일시적으로 줄여 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-132">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="7ad6d-133">이 제한을 초과하는 파일의 경우 사용자는 선택적으로 파일을 OneDrive에 업로드하고 OneNote에 링크를 삽입할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-133">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="7ad6d-134">Outlook</span><span class="sxs-lookup"><span data-stu-id="7ad6d-134">Outlook</span></span>

- <span data-ttu-id="7ad6d-135">폴더 창의 너비가 예기치 않게 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-135">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="7ad6d-136">Windows 업데이트 후 .msg와 .oft 파일을 여는 경우 작동이 멈추는 현상이 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-136">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="7ad6d-137">대규모 HTML 메시지를 전달할 때 사용자에게 잘린 메시지 본문이 표시되던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-137">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="7ad6d-138">이 업데이트는 메시지를 보거나 작성할 때 Microsoft Outlook에서 현재 민감도 레이블을 표시하지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-138">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7ad6d-139">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7ad6d-139">PowerPoint</span></span>

- <span data-ttu-id="7ad6d-140">개선된 설명이 있는 파일의 복사본을 여는 사용자에게 올바른 메시징을 릴레이하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-140">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="7ad6d-141">Word</span><span class="sxs-lookup"><span data-stu-id="7ad6d-141">Word</span></span>

- <span data-ttu-id="7ad6d-142">설치된 언어에 따라 Access 및 Publisher가 제대로 부팅되지 않을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-142">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="7ad6d-143">편집에 대해 보호된 문서의 비교 기능 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-143">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="7ad6d-144">2개의 문서를 하나로 병합할 때 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-144">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7ad6d-145">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="7ad6d-145">Office Suite</span></span>

- <span data-ttu-id="7ad6d-146">파일을 클라이언트에 캐시할 때 Project 앱이 네트워크를 차단하지 않도록 하는 문제를 해결하기 위한 수정입니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-146">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="7ad6d-147">내부 작업이 실패 시 로깅을 하고 계속 진행하는 대신 예외를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-147">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="7ad6d-148">영향을 받은 사용자는 더 이상 업데이트를 받을 수 없도록 차단되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-148">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="7ad6d-149">이렇게 변경하면 스케치된 개요가 리본에서 제대로 작동합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-149">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="7ad6d-150">특정 프록시 구성을 사용하여 온-프레미스 위치에서 파일을 여는 동안 발생하는 문제를 수정하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-150">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="7ad6d-151">이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-151">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="7ad6d-152">이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. </span><span class="sxs-lookup"><span data-stu-id="7ad6d-152">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="7ad6d-153">이 업데이트는 레이블 정책에서 머리글/바닥글 또는 워터 마크를 적용한 경우 레이블을 변경하거나 제거하여 민감도 레이블을 적용하는 동안 삽입된 255자를 초과하는 텍스트를 차후에 식별하고 제거할 수 없는 Microsoft Word에서의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-153">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="7ad6d-154">Office 전달 세션 중에 충돌을 없애고 사용자 환경의 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-154">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="7ad6d-155">이 버그는 ECS(향상된 구성 서비스) URL 끝점을 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-155">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="7ad6d-156">이 최신 끝점의 호출은 ECS에서 가져오기의 성공률이 높습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-156">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-april-14"></a><span data-ttu-id="7ad6d-158">버전 2002: 4월 14일</span><span class="sxs-lookup"><span data-stu-id="7ad6d-158">Version 2002: April 14</span></span>
<span data-ttu-id="7ad6d-159">*버전 2002 (빌드 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="7ad6d-159">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="7ad6d-160">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7ad6d-160">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="7ad6d-161">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="7ad6d-161">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7ad6d-162">Excel</span><span class="sxs-lookup"><span data-stu-id="7ad6d-162">Excel</span></span>

- <span data-ttu-id="7ad6d-163">**다중값을 반환하는 공식 입력:**  다중값을 반환하는 공식을 신속히 입력하면 자동으로 인접한 셀들로 입력됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-163">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="7ad6d-164">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-164">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="7ad6d-165">**유용한 함수 6개:**  스프레드시트를 더욱 유용하게 사용할 수 있는 새로운 함수 6개(FILTER, SORT, SORTBY, UNIQUE, SEQUENCE 및 RANDARRAY)가 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-165">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="7ad6d-166">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-166">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="7ad6d-167">\*\*왼쪽을 보고, 오른쪽을 보십시오… XLOOKUP이 여기 있습니다! \*\*  행별로 XLOOKUP을 사용하여 테이블 또는 범위에서 필요한 것을 모두 찾으십시오.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-167">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  [<span data-ttu-id="7ad6d-168">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-168">Learn more</span></span>](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="7ad6d-170">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="7ad6d-170">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7ad6d-171">Excel</span><span class="sxs-lookup"><span data-stu-id="7ad6d-171">Excel</span></span>

- <span data-ttu-id="7ad6d-172">특정 경우에 Word나 PowerPoint에서 포함된 통합 문서를 다시 열면 Excel이 중단됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-172">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="7ad6d-173">CSV 파일로 저장하면 Excel에서 모든 열이 하나의 열로 병합되는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-173">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="7ad6d-174">보호된 시트의 범위에서 Range.ClearContents를 사용하면 예상보다 시간이 오래 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-174">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="7ad6d-175">인쇄 미리 보기로 표시되는 경우 양식 컨트롤에서 텍스트의 크기 조정 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-175">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="7ad6d-176">리본 메뉴와 상호 작용하는 VBA 매크로는 ScreenUpdating을 예기치 않게 True로 설정한 상태에서 실행될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-176">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="7ad6d-177">원본 통합 문서가 닫힌 경우 외부 링크가 채우기(아래로 채우기, 가로 채우기 등)에 업데이트되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-177">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="7ad6d-178">경우에 따라 VBA의 Application.Evaluate를 사용해도 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-178">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="7ad6d-179">서식 파일에서 차트를 만들 때 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-179">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="7ad6d-180">Outlook</span><span class="sxs-lookup"><span data-stu-id="7ad6d-180">Outlook</span></span>

- <span data-ttu-id="7ad6d-181">일부 시나리오에서 그룹 헤더가 예기치 않게 확장되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-181">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="7ad6d-182">특정 검색 결과를 선택할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-182">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="7ad6d-183">마우스의 X 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-183">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="7ad6d-184">첨부 파일 도구에서 클라우드에 저장 단추가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-184">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7ad6d-185">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7ad6d-185">PowerPoint</span></span>

- <span data-ttu-id="7ad6d-186">복사-붙여넣기 시나리오 개선: 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-186">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="7ad6d-187">Project</span><span class="sxs-lookup"><span data-stu-id="7ad6d-187">Project</span></span>

- <span data-ttu-id="7ad6d-188">이전 버전의 Project에서 만든 프로젝트를 저장하면 Project가 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-188">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="7ad6d-189">비활성 단추를 통해 작업이 비활성화/활성화된 때를 ProjectBeforeTaskChange 이벤트에서 감지하지 못하는 문제를 해결했습니다. </span><span class="sxs-lookup"><span data-stu-id="7ad6d-189">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="7ad6d-190">Word</span><span class="sxs-lookup"><span data-stu-id="7ad6d-190">Word</span></span>

- <span data-ttu-id="7ad6d-191">마우스의 X 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-191">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="7ad6d-192">표에 텍스트 맞춤 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-192">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="7ad6d-193">삽입 가로선 길이가 더 짧지 않고 가운데 맞춤되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-193">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-march-10"></a><span data-ttu-id="7ad6d-195">버전 2002: 3월 10일</span><span class="sxs-lookup"><span data-stu-id="7ad6d-195">Version 2002: March 10</span></span>
<span data-ttu-id="7ad6d-196">*버전 2002 (빌드 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="7ad6d-196">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="7ad6d-197">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7ad6d-197">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="7ad6d-199">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="7ad6d-199">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7ad6d-200">Access</span><span class="sxs-lookup"><span data-stu-id="7ad6d-200">Access</span></span>

- <span data-ttu-id="7ad6d-201">**연결된 표 빠르게 찾기:** 새 검색 상자를 사용하여 연결된 표를 간편하게 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-201">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="7ad6d-202">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-202">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="7ad6d-203">Excel</span><span class="sxs-lookup"><span data-stu-id="7ad6d-203">Excel</span></span>

- <span data-ttu-id="7ad6d-204">**\@멘션으로 주의 끌기:** 메모에 @멘션을 사용하여 입력이 필요하다는 사실을 동료들에게 알립니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-204">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="7ad6d-205">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-205">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="7ad6d-206">**원하는 내용 찾기: 명령, 사용자, 파일, 사진, 웹 문서 등을 검색**</span><span class="sxs-lookup"><span data-stu-id="7ad6d-206">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="7ad6d-207">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-207">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="7ad6d-208">**그림 스케치:** 통합 문서에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-208">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="7ad6d-209">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-209">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="7ad6d-210">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-210">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="7ad6d-211">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-211">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="7ad6d-212">**남은 작업에 중점:** 설명을 축소하고 열린 항목을 강조하려면 해결을 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-212">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="7ad6d-213">\*\* 더 많은 접근 가능한 PDF 만들기:\*\* PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-213">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="7ad6d-214">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-214">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="7ad6d-215">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-215">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="7ad6d-216">**데이터 시각화 도우미 추가 기능:** Excel에서 빠르게 Visio 플로차트를 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-216">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="7ad6d-217">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-217">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="7ad6d-218">**읽고 즉시 회신:** 통합 문서를 열지 않고 전자 메일에서 바로 메모와 멘션에 회신합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-218">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="7ad6d-219">**통합 문서에 대 한 통계를 가져오기:** 통합 문서 통계는 통합 문서의 내용을 간략하게 파악하는 데 도움이 되는 통합 문서의 내용에 대한 개요를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-219">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="7ad6d-220">**도형을 그림으로 저장:** 몇 번의 클릭만으로 도형, 아이콘 또는 기타 개체를 그림 파일로 저장하여 다른 곳에서 다시 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-220">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="7ad6d-221">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-221">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



### <a name="outlook"></a><span data-ttu-id="7ad6d-222">Outlook</span><span class="sxs-lookup"><span data-stu-id="7ad6d-222">Outlook</span></span>



- <span data-ttu-id="7ad6d-223">**LinkedIn 네트워크를 Outlook과 연결하기:** Microsoft 계정을 사용하여 LinkedIn 계정에 안전하게 연결하고 Windows용 Outlook의 명함에 있는 LinkedIn 프로필에서 정보를 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-223">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="7ad6d-224">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-224">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="7ad6d-p118">**모든 암호화 옵션의 일원화:** 전자 메일 메시지 보호 방법을 선택하려면 옵션 > 암호화로 이동합니다. [자세히 알아보기](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="7ad6d-p118">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="7ad6d-227">**Outlook의 링크 삽입 메뉴는 테넌트 관리자가 정의한 사용 권한을 포함하는 링크를 삽입합니다:** Outlook의 가장 최근 삽입한 링크에 있는 링크는 이미 사용 권한이 있었던 사용자들에게만 작동했었던 링크를 삽입합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-227">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="7ad6d-228">이는 종종 사용자들 간에 문서에 대한 액세스 권한을 요청하는 전자 메일을 주고 받게 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-228">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="7ad6d-229">이 환경을 업데이트하여 이제 테넌트 관리자가 설정한 기본 권한으로 링크가 삽입되었습니다. MSIT의 경우 "조직은 편집할 수 있음"이므로 이 방법을 통해 공유된 링크를 받는 모든 내부 사용자가 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-229">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="7ad6d-230">**철자 또는 오타로 검색:** Outlook은 철자가 틀린 경우에도 검색 내용을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-230">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="7ad6d-231">**피싱 메일을 쉽게 탐지:** 스팸과 피싱 메시지는 형태와 느낌이 다르기 때문에 받은 편지함에서 쉽게 식별하고 제거할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-231">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="7ad6d-232">**공격에 대비한 고급 보호:** Office 365 Advanced Threat Protection을 사용하면 전자 메일 제목, 첨부된 메시지, 서명된 메시지, 네트워크 경로 등의 하이퍼 링크를 통해 공격으로부터 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-232">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="7ad6d-233">**그리기 기능:** 그림 위쪽에서 낙서를 하거나 그리기 캔버스를 추가하여 잉크로 내 생각을 전달할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-233">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="7ad6d-234">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-234">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="7ad6d-235">**검색 결과에서 관련 메시지 확인:** Outlook은 검색 용어를 분석하고 검색 결과 상단에 가장 관련성이 높은 전자 메일 메시지를 보여줍니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-235">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="7ad6d-236">또한 상위 결과 섹션에 날짜별로 정렬된 모든 결과도 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-236">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="7ad6d-237">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-237">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="7ad6d-238">**위치 제안 받기:** 약속 및 모임을 예약할 때 위치 필드에 입력을 시작하면 Outlook에 회의실, 주소 및 기타 최근 장소가 제안됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-238">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="7ad6d-239">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-239">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="7ad6d-240">**화면에 더 많은 메시지 맞춤:** 메시지 사이의 간격을 조정하려면 보기 > 더 좁은 간격 사용을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-240">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="7ad6d-241">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-241">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="7ad6d-242">**다른 조명에서 메시지 보기:** 태양/달 단추를 사용하여 읽기 창에서 밝은 배경과 어두운 배경 간에 전환을 합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-242">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="7ad6d-243">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-243">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)



### <a name="powerpoint"></a><span data-ttu-id="7ad6d-244">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7ad6d-244">PowerPoint</span></span>

- <span data-ttu-id="7ad6d-245">**PowerPoint에서 빠르게 실시간 공동 작업 수행:** PowerPoint에서 빠르게 실시간 공동 작업 수행</span><span class="sxs-lookup"><span data-stu-id="7ad6d-245">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="7ad6d-246">**새로운 교정 도구:** 단어를 틀릴까봐 스트레스 받지 마세요.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-246">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="7ad6d-247">이제 PowerPoint는 문법 및 맞춤법 제안 사항을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-247">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="7ad6d-248">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-248">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)


- <span data-ttu-id="7ad6d-249">**라이브 캡션 및 자막:** 발표자의 단어가 화면에 캡션으로 자동으로 표시되고 원하는 언어로 자막으로 번역됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-249">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="7ad6d-250">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-250">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="7ad6d-p127">**수식만 쓰세요, 서식은 PowerPoint가 알아서 지정해 드립니다:** 손글씨로 쓴 수학 식을 표준 문자로 변경해 드리겠습니다. 잉크 수식 변환을 선택하고 필기를 선택하기만 하면 됩니다. [자세히 알아보기](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="7ad6d-p127">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="7ad6d-254">**원하는 내용 찾기:** 검색 창을 사용하여 텍스트, 명령, 도움말 등을 찾으세요.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-254">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="7ad6d-255">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-255">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="7ad6d-256">**누락된 슬라이드 제목 찾기 및 수정:** 슬라이드 제목은 발표에 호소력을 더해 다양한 수준의 사용자가 슬라이드를 이해하기 쉽도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-256">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="7ad6d-257">접근성 검사를 통해 제목이 누락되는 위치를 표시하여 신속하게 제목을 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-257">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="7ad6d-258">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-258">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="7ad6d-259">**그림 스케치:** 프레젠테이션에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-259">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="7ad6d-260">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-260">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="7ad6d-261">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-261">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="7ad6d-262">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-262">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="7ad6d-263">**그림을 SVG로 저장:** 이미지 품질이 손실되지 않도록 크기를 조정할 수 있는 스케일 가능한 벡터 그래픽으로 차트, 도형 또는 기타 그림을 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-263">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="7ad6d-264">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-264">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="7ad6d-265">**슬라이드 번호를 유인물에 인쇄:** 슬라이드 번호가 유인물에 자동으로 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-265">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="7ad6d-266">계속 사용 및 해제 여부를 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-266">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="7ad6d-267">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-267">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="7ad6d-268">**잉크 스턴트 재생:** 슬라이드에 잉크를 쓸 때 슬라이드 쇼 중에 잉크의 실제 그리기를 재생하기 위한 재생 애니메이션을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-268">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="7ad6d-269">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-269">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="7ad6d-270">\*\* 더 많은 접근 가능한 PDF 만들기:\*\* PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-270">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="7ad6d-271">\*\*모든 사용자를 위한 프레젠테이션 최적화: \*\* 접근성 검사기는 기능은 스크린 리더를 염두에 두고 슬라이드에서 개체를 정렬하는데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-271">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="7ad6d-272">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-272">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="7ad6d-273">**더욱 안전한 비디오 환경:** 보안 강화는 더욱 안전한 온라인 비디오 환경을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-273">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="7ad6d-274">**재개발 대신 재사용:** 사용자가 작성했거나 다른 사용자가 공유하도록 한 슬라이드를 다시 사용하여 시간을 절약하세요.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-274">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="7ad6d-275">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-275">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="7ad6d-276">**Office 365용 PowerPoint에서 필기 잉크를 도형, 텍스트 또는 수학으로 변경:** 몇 번의 스트로크만으로 자유형 잉크를 Office 도형, 텍스트 또는 수식으로 변경합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-276">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="7ad6d-277">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-277">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="7ad6d-278">**멋진 슬라이드 만들기:** 잉크를 표준 도형 및 텍스트로 변환한 후, PowerPoint Designer에서 스마트한 슬라이드 디자인 아이디어를 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-278">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="7ad6d-279">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-279">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

### <a name="visio"></a><span data-ttu-id="7ad6d-280">Visio</span><span class="sxs-lookup"><span data-stu-id="7ad6d-280">Visio</span></span>

- <span data-ttu-id="7ad6d-281">**범죄 현장 재방문:** 범죄 현장 조사 서식 파일에서 새 증빙, 실내 및 실외 스텐실을 사용하여 범죄 현장에 대한 세부 정보를 다시 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-281">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="7ad6d-282">**Excel에서 세련된 Visio 다이어그램 만들기:** 워크시트에 데이터를 입력하여 순서도 또는 조직도를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-282">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="7ad6d-283">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-283">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="7ad6d-284">Word</span><span class="sxs-lookup"><span data-stu-id="7ad6d-284">Word</span></span>

- <span data-ttu-id="7ad6d-285">**이력서 편집기와 LinkedIn Resume 도우미의 만남:** 이력서 편집기는 이력서에 특별히 맞춤화된 문법 및 스타일 검사를 제공하여 글을 보다 정확하고 전문적으로 만들어 줍니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-285">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="7ad6d-286">**3D 개체의 병합으로 발생하는 문서 손상 문제 해결:** 3D 개체의 병합으로 발생하는 문서 손상 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-286">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="7ad6d-287">**원하는 내용 찾기:** 검색 창을 사용하여 텍스트, 명령, 도움말 등을 찾으세요.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-287">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="7ad6d-288">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-288">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="7ad6d-289">**생생한 색으로 공동 작업:** 메모와 변경 사항은 기여자에 의해 색상으로 구분되므로 공동 작업자 중 개개인을 쉽게 구분할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-289">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="7ad6d-290">**공동으로 매크로 사용 문서 편집 공동:** 비즈니스용 OneDrive에서 .docm 파일을 저장하고 공동 작업자와 실시간으로 편집합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-290">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="7ad6d-291">**공동 작성 기능 개선**: 문서를 공동 작성 시 변경 내용 추적 기능을 사용하여 Word의 성능을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-291">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="7ad6d-292">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-292">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="7ad6d-293">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-293">Find them at Insert > Icons.</span></span> [<span data-ttu-id="7ad6d-294">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-294">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="7ad6d-295">**다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다.** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-295">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="7ad6d-296">**그림 스케치:** 문서에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-296">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="7ad6d-297">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-297">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="7ad6d-298">**정확하게 지우기:** 두 개의 지우개 크기 중에 선택하고 작은 잉킹 결함을 수정하세요.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-298">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="7ad6d-299">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-299">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="7ad6d-300">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-300">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="7ad6d-301">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-301">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="7ad6d-302">**다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다.** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-302">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="7ad6d-303">**공동 작성 향상** : 공동 작성 시 신뢰도가 향상될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-303">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="7ad6d-304">\*\* 더 많은 접근 가능한 PDF 만들기:\*\* PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-304">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="7ad6d-305">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-305">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="7ad6d-306">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-306">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="7ad6d-307">**더욱 안전한 비디오 환경:** 보안 강화는 더욱 안전한 온라인 비디오 환경을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-307">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="7ad6d-308">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-308">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="7ad6d-309">**도형을 그림으로 저장:** 몇 번의 클릭만으로 도형, 아이콘 또는 기타 개체를 그림 파일로 저장하여 다른 곳에서 다시 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-309">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="7ad6d-310">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="7ad6d-310">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="7ad6d-313">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="7ad6d-313">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7ad6d-314">Access</span><span class="sxs-lookup"><span data-stu-id="7ad6d-314">Access</span></span>

- <span data-ttu-id="7ad6d-315">이 업데이트는 업데이트 쿼리가 실행되거나 UPDATE 문이 SQL에 사용될 때 &quot;쿼리가 손상되었습니다&quot; 오류를 일으킬 수있는 Microsoft Access의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-315">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="7ad6d-316">이 업데이트는 Microsoft Access에서 연결된 SQL Server 테이블의 ID 열이 식별되지 않아서 행이 올바르지 않게 삭제된 것으로 보고되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-316">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="7ad6d-317">이 업데이트는 ADODB 사용시 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-317">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="7ad6d-318">VB 코드의 레코더 개체에서 오류가 잘못 보고될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-318">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="7ad6d-319">데이터베이스 내에서 더 이상 액세스 템플릿으로 인해 첨부 열이 실패하지 않아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-319">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="7ad6d-320">템플릿을 인스턴스화 한 후에는 데이터베이스에 첨부 파일 필드를 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-320">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="7ad6d-321">Excel</span><span class="sxs-lookup"><span data-stu-id="7ad6d-321">Excel</span></span>

- <span data-ttu-id="7ad6d-322">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-322">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="7ad6d-323">이 변경 사항은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-323">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="7ad6d-324">spilling 배열이 있는 셀이 있는 열로 텍스트를 변환할 때 일부 사용자에게 충돌이 발생하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-324">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="7ad6d-325">이 업데이트는 수식 입력줄에서 예상한 것과 다른 글꼴로 텍스트를 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-325">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="7ad6d-326">일부 현지의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-326">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="7ad6d-327">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-327">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="7ad6d-328">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-328">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="7ad6d-329">스크롤 후 셀을 선택하면 잘못된 셀이 선택되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-329">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="7ad6d-330">신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 오류를 발생시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-330">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="7ad6d-331">일부 현지화의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-331">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="7ad6d-332">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-332">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="7ad6d-333">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-333">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="7ad6d-334">일부 사용자가 경험할 수 있는 OLE (포함 및 연결된 개체) 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-334">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="7ad6d-335">피벗 차트의 오른쪽 클릭 메뉴를 수정하여 세부 정보를 표시하는 옵션을 사용할 수 있도록 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-335">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="7ad6d-336">통합 문서가 열려있지 않은 상태에서 최근 파일을 검색할 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-336">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="7ad6d-337">통합 문서에 외부 링크가 있는 경우 일부 사용자가 여러 개의 팝업 창을 경험하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-337">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="7ad6d-338">상황에 맞는 메뉴에서 주석 명령이 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-338">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="7ad6d-339">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-339">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="7ad6d-340">CUBEVALUE 함수가 때때로 잘못된 결과를 반환하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-340">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="7ad6d-341">Outlook</span><span class="sxs-lookup"><span data-stu-id="7ad6d-341">Outlook</span></span>

- <span data-ttu-id="7ad6d-342">피드백 검색 환경을 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-342">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="7ad6d-343">사용자가 클라우드 설정을 검색할 때 Outlook에서 사용자가 중단되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-343">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="7ad6d-344">검색 상자가 높은 dpi 모드로 잘못 정렬되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-344">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="7ad6d-345">Outlook 프로세스에서 메모리 누수가 사용자에게 관찰되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-345">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="7ad6d-346">사용자가 일부 상황에서 표시된 SMTP 주소와 일치하지 않는 주소로 보낸 전자 메일을 보게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-346">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="7ad6d-347">이 변경으로 메시지 헤더에서 여러 줄 제목을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-347">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="7ad6d-348">파일을 WebDAV 위치에 저장하지 못하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-348">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="7ad6d-349">SMIME 알고리즘 선택 관련 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-349">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="7ad6d-350">타사 응용 프로그램에서 전자 메일을 보낼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-350">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="7ad6d-351">사용자가 계정 만들기 컨텍스트에서 지원 센터에 문의하려고 할 때 &quot;확인&quot; 버튼이 있는 빈 메시지 상자가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-351">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="7ad6d-352">사용자가 프로필을 만드는 동안 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-352">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="7ad6d-353">동기화 슬라이더가 더 작은 설정으로 설정되어 있어도 Outlook이 예기치 않게 모든 메일을 동기화시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-353">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="7ad6d-354">검은색 테마를 사용한 사용자에게 &quot;보낸 사람&quot; 드롭다운에 흰색 배경에 흰색 텍스트가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-354">Addressed an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>

- <span data-ttu-id="7ad6d-355">계정 설정을 취소할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-355">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="7ad6d-356">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-356">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="7ad6d-357">일부 시나리오에서 플래그가 지정된 항목 강조 표시를 사용하지 않도록 설정하는 옵션이 무시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-357">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="7ad6d-358">규칙 대화 상자를 열 때 &quot;이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다&quot; 프롬프트가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-358">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="7ad6d-359">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-359">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="7ad6d-360">매우 긴 Outlook 세션에서 메모리 누수를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-360">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="7ad6d-361">여러 창에서 동일한 항목을 볼 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-361">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="7ad6d-362">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 현저하게 지연이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-362">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="7ad6d-363">사용자가 되풀이되는 일정 항목의 일부 인스턴스를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-363">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="7ad6d-364">Exchange 2010 서버에 사서함이있는 사용자가 일정 항목에 첨부 파일을 추가할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-364">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="7ad6d-365">디지털 서명된 메시지에 회신 할 때 사용자에게 문제가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-365">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="7ad6d-366">모임의 위치 필드가 예상치 않게 업데이트되는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-366">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="7ad6d-367">모임 위치 필드의 쉼표가 세미콜론으로 바뀌는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-367">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="7ad6d-368">모임을 지운 후 예기치 않게 모임의 위치를 모임을 다시 추가하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-368">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="7ad6d-369">브라질 시간대로 설정된 회의 및 약속과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-369">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="7ad6d-370">접근성 검사 창을 닫은 후 &quot;S&quot; 키를 누르면 메일이 예기치 않게 전송되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-370">Addressed an issue that caused users to see mails unexpectedly send when pressing the &quot;S&quot; key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="7ad6d-371">이를 통해 첨부 파일 차단 논리를 업데이트하여 Outlook에서 Python 첨부 파일도 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-371">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="7ad6d-372">웹 추가 기능이 디지털 권한 관리 메시지에 액세스하게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-372">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="7ad6d-373">사용자가 프로필을 만드는 동안 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-373">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="7ad6d-374">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-374">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7ad6d-375">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7ad6d-375">PowerPoint</span></span>

- <span data-ttu-id="7ad6d-376">Shape 관련 문제를 해결했습니다. 붙여넣기 방법: 사용자가 Shape를 사용하여 셰이프를 복사하고 붙여 넣는 경우. 붙여넣기 방법. 선택 대상이 붙여넣기한 셰이프로 변경됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-376">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="7ad6d-377">레거시 PPT 주석에서 상황에 맞는 메뉴를 사용할 때 충돌을 일으킬 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-377">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="7ad6d-378">Project</span><span class="sxs-lookup"><span data-stu-id="7ad6d-378">Project</span></span>

- <span data-ttu-id="7ad6d-379">읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-379">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="7ad6d-380">고정된 기간 유형의 100% 작업이 100% 완료 미만으로 잘못 계산할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-380">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="7ad6d-381">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-381">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="7ad6d-382">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-382">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="7ad6d-383">Word</span><span class="sxs-lookup"><span data-stu-id="7ad6d-383">Word</span></span>

- <span data-ttu-id="7ad6d-384">일부 경우에 기존 파일을 저장하면 항상 다른 이름으로 저장 대화 상자가 나타나고 파일이 실제로는 저장되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-384">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="7ad6d-385">문서 블록 이끌이가 잘못된 알림을 표시할 수 있습니다.&quot;사용자가 스타일, 문서 블록을 수정했습니다&quot;.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-385">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7ad6d-386">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="7ad6d-386">Office Suite</span></span>

- <span data-ttu-id="7ad6d-387">이 변경 사항은 마커가 포함된 일부 분산형 차트의 느린 렌더링 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-387">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="7ad6d-388">이 변경 사항은 인텔 통합 GPU를 활용하는 그래픽 어댑터에 보고된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-388">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="7ad6d-389">상대적인 마감일이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정 버그를 수정했습니다. 이 픽스는 후속 업데이트에 대한 상대적인 마감일도 사용할 수 있도록 해줍니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-389">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="7ad6d-390">Office 업데이트에서 로컬 또는 네트워크 공유 또는 Configuration Manager에서 제공하는 위치와 같은 의도된 원본 대신 Office CDN에서 파일을 예기치 않게 다운로드했을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-390">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="7ad6d-391">동일한 SharePoint 라이브러리의 Word/Excel/PowerPoint에서 여러 문서를 열 때 첫 번째로 열린 문서만 정책 준수에 대한 검사가 이뤄지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-391">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-february-11"></a><span data-ttu-id="7ad6d-393">버전 1908: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="7ad6d-393">Version 1908: February 11</span></span>
<span data-ttu-id="7ad6d-394">*버전 1908(빌드 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="7ad6d-394">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="7ad6d-395">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="7ad6d-395">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="7ad6d-397">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="7ad6d-397">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7ad6d-398">Excel</span><span class="sxs-lookup"><span data-stu-id="7ad6d-398">Excel</span></span>

- <span data-ttu-id="7ad6d-399">이 업데이트는 VBA를 사용하여 차트의 머리글/바닥글에 이미지를 추가할 때마다 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-399">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="7ad6d-400">인쇄 미리보기 또는 인쇄 시 그룹 상자 컨트롤의 테두리가 보이지 않던 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-400">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="7ad6d-401">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-401">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="7ad6d-402">차트가 포함된 통합 문서를 저장할 때 차트 머리글의 이미지 파일 크기가 커지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-402">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="7ad6d-403">선택 범위를 상호 참조 도서와 동기화하여 상호 참조 도서에서 DBCS 문자가 손상되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-403">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="7ad6d-404">자동 맞춤을 사용하여 행 높이를 조정할 때 확인란 컨트롤이 축소될 수있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-404">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="7ad6d-405">Outlook</span><span class="sxs-lookup"><span data-stu-id="7ad6d-405">Outlook</span></span>

- <span data-ttu-id="7ad6d-406">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-406">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="7ad6d-407">충돌 메시지를 처리할 때 사용자에게 동기화 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-407">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="7ad6d-408">Outlook을 시작할 때 사용자가 프로필을 로딩할 때 화면이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-408">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="7ad6d-409">보기를 변경할 때 사용자에게 간헐적인 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-409">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="7ad6d-410">Citrix 환경에서 30개 이상의 캘린더를 볼 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-410">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="7ad6d-411">[여기](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)에는 이전 버전에 대해 문서화된 개별 KB가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-411">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="7ad6d-412">사용자가 공유 일정 폴더를 OST와 동기화하는 데 문제가있어 이러한 폴더와 상호 작용할 때 권한 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-412">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7ad6d-413">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7ad6d-413">PowerPoint</span></span>

- <span data-ttu-id="7ad6d-414">복사-붙여넣기 시나리오 개선 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-414">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="7ad6d-415">공동 작업 사용자 간에 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-415">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="7ad6d-416">증분 방식으로 열린 파일에 둘 이상의 포함된 미디어 스트림이 있는 슬라이드가 포함되어 있을 때 발생할 수있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-416">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="7ad6d-417">PowerPoint를 처음 시작할 때 신뢰할 수 없는 추가 기능에 대해 보안 경고 메시지 표시줄이 나타나지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-417">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="7ad6d-418">Project</span><span class="sxs-lookup"><span data-stu-id="7ad6d-418">Project</span></span>

- <span data-ttu-id="7ad6d-419">기본 일정이 변경될 때 리소스 일정이 업데이트되지 않아 작업표와 프로젝트 계획 간에 실제 작업이 다를 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-419">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="7ad6d-420">Word</span><span class="sxs-lookup"><span data-stu-id="7ad6d-420">Word</span></span>

- <span data-ttu-id="7ad6d-421">더 이상 사용되지 않는 API에서 이동하여 Word의 충돌 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-421">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7ad6d-422">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="7ad6d-422">Office Suite</span></span>

- <span data-ttu-id="7ad6d-423">이 변경은 손상된 파일을 연 후 이미지를 올바르게 렌더링하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-423">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-january-14"></a><span data-ttu-id="7ad6d-425">버전 1908: 1월 14일</span><span class="sxs-lookup"><span data-stu-id="7ad6d-425">Version 1908: January 14</span></span>
<span data-ttu-id="7ad6d-426">*버전 1908(빌드 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="7ad6d-426">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="7ad6d-427">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7ad6d-427">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="7ad6d-429">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="7ad6d-429">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7ad6d-430">Excel</span><span class="sxs-lookup"><span data-stu-id="7ad6d-430">Excel</span></span>

- <span data-ttu-id="7ad6d-431">문서 타이틀에 대한 네덜란드어 단축키가 Alt-G로 변경되었습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-431">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="7ad6d-432">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-432">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="7ad6d-433">추가 기능을 통해 연 WPF(Windows Presentation Foundation) 양식의 콤보 상자에서 항목을 선택할 수 없는 문제가 발생했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-433">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="7ad6d-434">Outlook</span><span class="sxs-lookup"><span data-stu-id="7ad6d-434">Outlook</span></span>

- <span data-ttu-id="7ad6d-435">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 현저하게 지연이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-435">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="7ad6d-436">대체 보낸 사람을 사용할 때 정책 팁이 표시되지 않게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-436">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="7ad6d-437">사용자가 현재 상태 정보를 업데이트할 때 일시적으로 작동이 중지되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-437">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7ad6d-438">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7ad6d-438">PowerPoint</span></span>

- <span data-ttu-id="7ad6d-439">한 프레젠테이션에서 다른 프레젠테이션으로 슬라이드를 복사하여 중복하는 경우 마스터가 복제되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-439">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="7ad6d-440">최신 메모가 포함된 파일에는 지원되지 않는 버전에서 열었을 경우 노란색 경고가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-440">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="7ad6d-441">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="7ad6d-441">Office Suite</span></span>

- <span data-ttu-id="7ad6d-442">Office 업데이트 메시지가 다른 언어로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-442">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="7ad6d-443">앞으로 Office 업데이트 메시지 언어가 Windows 표시 언어와 정확하게 일치할 것입니다.  </span><span class="sxs-lookup"><span data-stu-id="7ad6d-443">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="7ad6d-444">사용자가 관리자가 아니거나 시스템 계정에 네트워크 연결이 없는 경우에 업데이트가 적용되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-444">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

> [!NOTE]
> <span data-ttu-id="7ad6d-446">Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="7ad6d-446">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
