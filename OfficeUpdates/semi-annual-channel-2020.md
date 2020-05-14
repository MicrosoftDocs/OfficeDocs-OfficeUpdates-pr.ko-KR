---
title: 2020년 반기 채널 릴리스에 대한 릴리스 정보
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 2020년 Microsoft 365 앱에 대한 반기 채널 릴리스의 릴리스 정보를 IT 전문가에게 제공합니다.
ms.openlocfilehash: 6619411170491543c4853e6db56fa845a7adc6e3
ms.sourcegitcommit: fb97680a81c7d96b0f0f539dc3e3c8c28ad654e9
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/13/2020
ms.locfileid: "44222081"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a><span data-ttu-id="0d279-103">2020년 반기 채널 릴리스에 대한 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-103">Release notes for Semi-Annual Channel releases in 2020</span></span>

<span data-ttu-id="0d279-104">이러한 릴리스 정보는 엔터프라이즈용 Microsoft 365 앱, 비즈니스용 Microsoft 365 앱, Project와 Visio 데스크톱 앱의 구독 버전에 대한 2020년 반기별 채널 업데이트에 포함된 새로운 기능 및 비보안 업데이트 관련 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="0d279-105">당사는 Microsoft 365 앱에 대한 업데이트 채널을 일부 변경하고 있습니다. 여기에는 새 업데이트 채널 추가(월별 엔터프라이즈 채널) 및 기존 업데이트 채널의 이름 변경 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="0d279-106">자세한 내용은 [이 문서를 검토하세요](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="0d279-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="0d279-107">반기 채널의 사용자가 Office Portal에서 Microsoft 365 앱을 다운로드하여 Windows 10에 설치하는 경우 이제 OneNote 2016이 기본적으로 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-may-12"></a><span data-ttu-id="0d279-109">버전 1908: 5월 12일</span><span class="sxs-lookup"><span data-stu-id="0d279-109">Version 1908: May 12</span></span>
<span data-ttu-id="0d279-110">*버전 1908(빌드 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="0d279-110">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="0d279-111">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="0d279-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="0d279-113">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="0d279-113">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="0d279-114">Excel</span><span class="sxs-lookup"><span data-stu-id="0d279-114">Excel</span></span>

- <span data-ttu-id="0d279-115">색을 기준으로 필터링된 데이터를 다른 너비의 열에 복사하면 값의 붙여넣기가 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-115">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="0d279-116">VBA 매크로를 사용하여 범위의 내용을 지우면 사용자가 경험할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-116">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="0d279-117">범위에 값을 입력하는 것이 예상외로 느려지는 VBA 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-117">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="0d279-118">파일을 저장하고 다시 열 때 차트 축의 "값 교점" 속성이 예기치 않게 변경되는 문제를 해결 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-118">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="0d279-119">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-119">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

### <a name="onenote"></a><span data-ttu-id="0d279-120">OneNote</span><span class="sxs-lookup"><span data-stu-id="0d279-120">OneNote</span></span>

- <span data-ttu-id="0d279-121">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 지역화하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-121">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="0d279-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d279-122">Outlook</span></span>

- <span data-ttu-id="0d279-123">최신 Windows 업데이트 적용 후 .msg와 .oft 파일을 여는 경우 작동이 멈추는 현상이 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-123">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="0d279-124">특정 검색 결과를 선택할 때 작동이 멈추는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-124">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="0d279-125">첨부 파일 도구에서 "클라우드에 저장" 단추가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-125">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="0d279-126">기본적으로 보존 정책 레이블에는 보존 기간이 괄호로 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-126">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="0d279-127">이는 관리자가 정책 이름만 표시하도록 지정할 수 있는 레지스트리 키를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-127">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="0d279-128">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="0d279-128">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="0d279-129">0 = 기본값입니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-129">0 = Default.</span></span>  <span data-ttu-id="0d279-130">1 = 보존 정책 텍스트의 PolicyName만 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-130">1 = we will only show the PolicyName for Retention policy text.</span></span>


### <a name="word"></a><span data-ttu-id="0d279-131">Word</span><span class="sxs-lookup"><span data-stu-id="0d279-131">Word</span></span>

- <span data-ttu-id="0d279-132">2개의 문서를 하나로 병합할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="0d279-133">편집에 대해 보호된 문서의 기능 비교 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1902-may-12"></a><span data-ttu-id="0d279-135">버전 1902: 5월 12일</span><span class="sxs-lookup"><span data-stu-id="0d279-135">Version 1902: May 12</span></span>
<span data-ttu-id="0d279-136">*버전 1902(빌드 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="0d279-136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="0d279-137">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="0d279-137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="0d279-139">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="0d279-139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="0d279-140">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d279-140">Outlook</span></span>

- <span data-ttu-id="0d279-141">최신 Windows 업데이트 적용 후 .msg와 .oft 파일을 여는 경우 작동이 멈추는 현상이 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="0d279-142">기본적으로 보존 정책 레이블에는 보존 기간이 괄호로 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="0d279-143">이는 관리자가 정책 이름만 표시하도록 지정할 수 있는 레지스트리 키를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="0d279-144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="0d279-144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="0d279-145">0 = 기본값입니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-145">0 = Default.</span></span>  <span data-ttu-id="0d279-146">1 = 보존 정책 텍스트의 PolicyName만 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-may-04"></a><span data-ttu-id="0d279-148">버전 1908: 5월 4일</span><span class="sxs-lookup"><span data-stu-id="0d279-148">Version 1908: May 04</span></span>
<span data-ttu-id="0d279-149">*버전 1908(빌드 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="0d279-149">*Version 1908 (Build 11929.20752)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="0d279-150">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="0d279-150">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="0d279-151">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="0d279-151">Office Suite</span></span>

- <span data-ttu-id="0d279-152">라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-152">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="0d279-153">버전 1902: 5월 4일</span><span class="sxs-lookup"><span data-stu-id="0d279-153">Version 1902: May 04</span></span>
<span data-ttu-id="0d279-154">*버전 1902(빌드 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="0d279-154">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="0d279-155">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="0d279-155">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="0d279-156">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="0d279-156">Office Suite</span></span>

- <span data-ttu-id="0d279-157">라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-157">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-14"></a><span data-ttu-id="0d279-158">버전 1908: 4월 14일</span><span class="sxs-lookup"><span data-stu-id="0d279-158">Version 1908: April 14</span></span>
<span data-ttu-id="0d279-159">*버전 1908(빌드 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="0d279-159">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="0d279-160">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="0d279-160">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="0d279-162">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="0d279-162">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="0d279-163">Excel</span><span class="sxs-lookup"><span data-stu-id="0d279-163">Excel</span></span>

- <span data-ttu-id="0d279-164">병합된 셀을 포함하는 열을 삭제할 때 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-164">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="0d279-165">인쇄 미리 보기로 표시되는 경우 양식 컨트롤에서 텍스트의 크기 조정 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-165">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="0d279-166">Skype</span><span class="sxs-lookup"><span data-stu-id="0d279-166">Skype</span></span>

- <span data-ttu-id="0d279-167">두 개 이상의 대화가 진행되는 동안 탭 대화의 제목 이름이 고정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-167">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="0d279-168">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d279-168">Outlook</span></span>

- <span data-ttu-id="0d279-169">Outlook을 종료할 때 사용자가 작동 중단을 경험하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-169">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="0d279-170">일부 시나리오에서 고객에게 빈 회의실 목록이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-170">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d279-171">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d279-171">PowerPoint</span></span>

- <span data-ttu-id="0d279-172">형광펜 관련 문제를 해결했습니다. 어두운 형광펜 색상의 텍스트는 흑백 모드에서 검은 색으로 인쇄됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-172">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="0d279-173">Word</span><span class="sxs-lookup"><span data-stu-id="0d279-173">Word</span></span>

- <span data-ttu-id="0d279-174">표의 텍스트 맞춤 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-174">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="0d279-175">버전 1902: 4월 14일</span><span class="sxs-lookup"><span data-stu-id="0d279-175">Version 1902: April 14</span></span>
<span data-ttu-id="0d279-176">*버전 1902(빌드 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="0d279-176">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="0d279-177">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="0d279-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-march-10"></a><span data-ttu-id="0d279-179">버전 1908: 3월 10일</span><span class="sxs-lookup"><span data-stu-id="0d279-179">Version 1908: March 10</span></span>
<span data-ttu-id="0d279-180">*버전 1908 (빌드 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="0d279-180">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="0d279-181">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="0d279-181">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="0d279-183">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="0d279-183">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="0d279-184">Excel</span><span class="sxs-lookup"><span data-stu-id="0d279-184">Excel</span></span>

- <span data-ttu-id="0d279-185">통합 문서에 외부 링크가 있는 경우 일부 사용자에게 여러 개의 팝업 창이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-185">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="0d279-186">일부 현지의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-186">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="0d279-187">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-187">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="0d279-188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d279-188">PowerPoint</span></span>

- <span data-ttu-id="0d279-189">Shape 관련 문제를 해결했습니다. 붙여넣기 방법: 사용자가 Shape를 사용하여 셰이프를 복사하고 붙여 넣는 경우. 붙여넣기 방법. 선택 대상이 붙여넣기한 셰이프로 변경됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-189">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="0d279-190">Word</span><span class="sxs-lookup"><span data-stu-id="0d279-190">Word</span></span>

- <span data-ttu-id="0d279-191">일부 경우에 기존 파일을 저장하면 항상 다른 이름으로 저장 대화 상자가 나타나고 파일이 실제로는 저장되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-191">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="0d279-192">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="0d279-192">Office Suite</span></span>

- <span data-ttu-id="0d279-193">이 변경 사항은 마커가 포함된 일부 분산형 차트의 느린 렌더링 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-193">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="0d279-194">버전 1902: 3월 10일</span><span class="sxs-lookup"><span data-stu-id="0d279-194">Version 1902: March 10</span></span>
<span data-ttu-id="0d279-195">*버전 1902 (빌드 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="0d279-195">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="0d279-196">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="0d279-196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-february-11"></a><span data-ttu-id="0d279-198">버전 1908: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="0d279-198">Version 1908: February 11</span></span>
<span data-ttu-id="0d279-199">*버전 1908(빌드 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="0d279-199">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="0d279-200">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="0d279-200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="0d279-202">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="0d279-202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="0d279-203">Excel</span><span class="sxs-lookup"><span data-stu-id="0d279-203">Excel</span></span>

- <span data-ttu-id="0d279-204">이 업데이트는 VBA를 사용하여 차트의 머리글/바닥글에 이미지를 추가할 때마다 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-204">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="0d279-205">인쇄 미리보기 또는 인쇄 시 그룹 상자 컨트롤의 테두리가 보이지 않던 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-205">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="0d279-206">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-206">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="0d279-207">차트가 포함된 통합 문서를 저장할 때 차트 머리글의 이미지 파일 크기가 커지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-207">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="0d279-208">선택 범위를 상호 참조 도서와 동기화하여 상호 참조 도서에서 DBCS 문자가 손상되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-208">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="0d279-209">자동 맞춤을 사용하여 행 높이를 조정할 때 확인란 컨트롤이 축소될 수있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-209">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="0d279-210">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d279-210">Outlook</span></span>

- <span data-ttu-id="0d279-211">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-211">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="0d279-212">충돌 메시지를 처리할 때 사용자에게 동기화 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-212">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="0d279-213">Outlook을 시작할 때 사용자가 프로필을 로딩할 때 화면이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-213">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="0d279-214">보기를 변경할 때 사용자에게 간헐적인 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-214">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="0d279-215">Citrix 환경에서 30개 이상의 캘린더를 볼 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-215">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="0d279-216">[여기](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)에는 이전 버전에 대해 문서화된 개별 KB가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-216">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="0d279-217">사용자가 공유 일정 폴더를 OST와 동기화하는 데 문제가있어 이러한 폴더와 상호 작용할 때 권한 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-217">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="0d279-218">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d279-218">PowerPoint</span></span>

- <span data-ttu-id="0d279-219">복사-붙여넣기 시나리오 개선 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-219">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="0d279-220">공동 작업 사용자 간에 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-220">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="0d279-221">증분 방식으로 열린 파일에 둘 이상의 포함된 미디어 스트림이 있는 슬라이드가 포함되어 있을 때 발생할 수있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-221">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="0d279-222">PowerPoint를 처음 시작할 때 신뢰할 수 없는 추가 기능에 대해 보안 경고 메시지 표시줄이 나타나지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-222">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="0d279-223">Project</span><span class="sxs-lookup"><span data-stu-id="0d279-223">Project</span></span>

- <span data-ttu-id="0d279-224">기본 일정이 변경될 때 리소스 일정이 업데이트되지 않아 작업표와 프로젝트 계획 간에 실제 작업이 다를 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-224">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="0d279-225">Word</span><span class="sxs-lookup"><span data-stu-id="0d279-225">Word</span></span>

- <span data-ttu-id="0d279-226">더 이상 사용되지 않는 API에서 이동하여 Word의 충돌 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-226">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="0d279-227">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="0d279-227">Office Suite</span></span>

- <span data-ttu-id="0d279-228">이 변경은 손상된 파일을 연 후 이미지를 올바르게 렌더링하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-228">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1902-february-11"></a><span data-ttu-id="0d279-230">버전 1902: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="0d279-230">Version 1902: February 11</span></span>
<span data-ttu-id="0d279-231">*버전 1902 (빌드 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="0d279-231">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="0d279-232">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="0d279-232">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="0d279-234">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="0d279-234">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="0d279-235">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d279-235">Outlook</span></span>

- <span data-ttu-id="0d279-236">암호화된 전자 메일을 보낼 때 사용자에게 "암호화 알고리즘이 지원되지 않습니다." 오류가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-236">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="0d279-237">Word</span><span class="sxs-lookup"><span data-stu-id="0d279-237">Word</span></span>

- <span data-ttu-id="0d279-238">더 이상 사용되지 않는 API에서 이동하여 Word의 충돌 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-238">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

## <a name="version-1808-february-11"></a><span data-ttu-id="0d279-241">버전 1808: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="0d279-241">Version 1808: February 11</span></span>
<span data-ttu-id="0d279-242">*버전 1808 (빌드 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="0d279-242">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="0d279-243">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="0d279-243">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-january-14"></a><span data-ttu-id="0d279-245">버전 1908: 1월 14일</span><span class="sxs-lookup"><span data-stu-id="0d279-245">Version 1908: January 14</span></span>
<span data-ttu-id="0d279-246">*버전 1908(빌드 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="0d279-246">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="0d279-247">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="0d279-247">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="0d279-249">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="0d279-249">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="0d279-250">Access</span><span class="sxs-lookup"><span data-stu-id="0d279-250">Access</span></span>

- <span data-ttu-id="0d279-251">**데이터베이스 개체에 탭 유지:** 활성 탭이 무엇인지 명확하게 구분할 수 있고, 간편하게 끌어서 순서를 변경할 수 있고, 클릭 한 번으로 데이터베이스 개체를 닫을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-251">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="0d279-252">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-252">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="0d279-253">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-253">Switching between them has never been easier.</span></span> [<span data-ttu-id="0d279-254">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-254">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="0d279-255">**더 많은 공간을 사용하여 확대/축소:** 확대/축소 상자의 크기를 키우고, 글꼴을 변경할 수 있습니다. 확대/축소에 이러한 설정이 모두 저장됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-255">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="0d279-256">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-256">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="0d279-257">Excel</span><span class="sxs-lookup"><span data-stu-id="0d279-257">Excel</span></span>

- <span data-ttu-id="0d279-258">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-258">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="0d279-259">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-259">Switching between them has never been easier.</span></span> [<span data-ttu-id="0d279-260">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-260">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="0d279-261">**콘텐츠 도달 범위 늘리기:** 접근성 높은 프레젠테이션을 만들어야 하나요?</span><span class="sxs-lookup"><span data-stu-id="0d279-261">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="0d279-262">진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-262">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="0d279-263">검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-263">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="0d279-264">**해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="0d279-264">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="0d279-265">파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-265">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="0d279-266">**생동감 있는 워크시트 보기:** 애니메이션 3D 그래픽을 삽입하여 워크북을 통해 심장 박동, 행성 궤도, 공룡 난동 모습 등을 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-266">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="0d279-267">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-267">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="0d279-p111">**자세한 데이터 분석:** 새로운 아이디어 단추는 데이터에서 패턴을 찾아서 인텔리전트 맞춤형 제안을 만듭니다. [자세히 알아보기](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="0d279-p111">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="0d279-270">**공동 작업이 쉬워졌습니다.** 공동 작성 기능이 향상되면 조건부 서식, 셀 스타일 등을 사용하여 작업할 때 변경 내용이 공동 작업자와 원활하게 통합됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-270">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="0d279-271">**유사한 열의 테이블 조인:** 가져오기 및 변환 기능(파워 쿼리)은 테이블 병합을 위해 열을 비교하는 경우 근사 텍스트 매칭 논리(퍼지 매칭)를 특징으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-271">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="0d279-272">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-272">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="0d279-273">**파워 쿼리 기능 향상을 통한 신속한 코드:** 자동 완성 및 구문 색상을 사용하여 신속하게 코드를 완성하세요.</span><span class="sxs-lookup"><span data-stu-id="0d279-273">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="0d279-274">함수, 열, 매개 변수를 쉽게 검색할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-274">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="0d279-275">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-275">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="0d279-276">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-276">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="0d279-277">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-277">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="0d279-278">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d279-278">Outlook</span></span>

- <span data-ttu-id="0d279-279">**Outlook 사용자 환경이 업데이트됨:** 출시 예정을 사용하여 이전에 미리 볼 수 있었던 간소화된 환경은 가장 중요한 작업에 집중할 수 있도록 설계되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-279">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="0d279-280">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-280">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="0d279-281">**사용자 지정이 가능한 간단한 리본:** 가장 많이 사용하는 단추가 한 행에 표시되어 간편합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-281">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="0d279-282">클래식 및 요약 보기 간의 간편한 전화 및 명령 고정/고정 해제</span><span class="sxs-lookup"><span data-stu-id="0d279-282">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="0d279-283">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-283">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="0d279-284">**메시지를 전달하는 동안에도 작업 지속 가능:** Outlook이 이제 백그라운드에서 메시지를 전달합니다. 따라서 폴더 간에 많은 메시지를 주고 받는 동안에도 작업을 계속할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-284">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="0d279-285">\*\*연달아 있는 모임 사이에 시간 넣기: \*\*모임이 기본적으로 5~10분 일찍 끝나도록 설정하여 참석자에게 잠시 숨을 돌리거나 장소를 이동할 시간을 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-285">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="0d279-286">**자주 하는 작업 선택:** 플래그 및 삭제를 사용하지 않나요?</span><span class="sxs-lookup"><span data-stu-id="0d279-286">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="0d279-287">[보관] 또는 [읽은 상태로 표시]는 어떤가요?</span><span class="sxs-lookup"><span data-stu-id="0d279-287">How about Archive or Mark as Read?</span></span> <span data-ttu-id="0d279-288">가장 많이 사용하는 명령으로 빠른 작업 메뉴를 사용자 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-288">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="0d279-p118">**밈하는 항목 표시:** 텍스트 또는 정적 이미지로 가능하지 않은 경우 애니메이션 GIF를 의도하는 바를 나타냅니다. [자세히 알아보기](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="0d279-p118">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="0d279-291">**빠르게 계정 추가:** 계정 설정 기능이 향상되어 Outlook에서 2단계 인증을 사용하여 Outlook.com 및 Gmail 계정을 추가하는 것이 그 어느 때보다 쉬워졌습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-291">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="0d279-292">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-292">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="0d279-293">**동기화 제한 문제 해결:** Outlook의 기능 향상으로 폴더 제한이 사라지고 공유된 편지함을 동기화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-293">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="0d279-294">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="0d279-295">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="0d279-296">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="0d279-297">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d279-297">PowerPoint</span></span>

- <span data-ttu-id="0d279-298">**더 나은 변신:** 셰이프에 이름을 지정하여 셰이프의 모핑 과정을 더 효율적으로 관리하세요.</span><span class="sxs-lookup"><span data-stu-id="0d279-298">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="0d279-299">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-299">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="0d279-300">**해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="0d279-300">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="0d279-301">파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-301">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="0d279-302">**콘텐츠 도달 범위 늘리기:** 접근성 높은 프레젠테이션을 만들어야 하나요?</span><span class="sxs-lookup"><span data-stu-id="0d279-302">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="0d279-303">진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-303">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="0d279-304">검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-304">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="0d279-305">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-305">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="0d279-306">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-306">Switching between them has never been easier.</span></span> [<span data-ttu-id="0d279-307">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-307">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="0d279-308">**온라인 비디오의 새로운 홈:** 조직의 모든 사람이 볼 수 있도록 비디오를 Microsoft Stream에 저장하세요.</span><span class="sxs-lookup"><span data-stu-id="0d279-308">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="0d279-309">비디오 링크를 삽입하고 파일 크기의 일부로 멀티미디어 프레젠테이션을 즐겨보세요.</span><span class="sxs-lookup"><span data-stu-id="0d279-309">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="0d279-310">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-310">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="0d279-311">**변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-311">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="0d279-p126">**대상 그룹에 퀴즈를 내거나 설문 조사하기:** 슬라이드에 퀴즈 또는 설문 조사를 넣습니다. Office가 응답을 수집하고 저장합니다. [자세한 정보](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="0d279-p126">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="0d279-p127">**그 어느 때보다 쉬운 온라인 비디오 삽입:** 슬라이드에 Vimeo 또는 YouTube 비디오를 삽입해야 하나요? 비디오 페이지 링크만 있으면 됩니다. [자세히 알아보기](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="0d279-p127">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="0d279-318">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-318">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="0d279-319">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-319">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="0d279-320">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-320">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="0d279-321">Project</span><span class="sxs-lookup"><span data-stu-id="0d279-321">Project</span></span>

- <span data-ttu-id="0d279-322">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-322">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="0d279-323">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-323">Switching between them has never been easier.</span></span> [<span data-ttu-id="0d279-324">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-324">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="0d279-325">Visio</span><span class="sxs-lookup"><span data-stu-id="0d279-325">Visio</span></span>

- <span data-ttu-id="0d279-326">**프로세스 다이어그램을 Word로 내보내기:** Word 문서에 셰이프 및 메타데이터 등의 다이어그램 콘텐츠를 자동으로 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-326">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="0d279-327">그런 후 문서를 사용자 지정하여 프로세스 지침 및 작업 설명서를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-327">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="0d279-328">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-328">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="0d279-329">**놀랄 만한 수준의 데이터 순서도:** 데이터 시각화 도우미 순서도를 위한 멋진 새 레이아웃은 깔끔하고 정돈되어 있으며 이해하기 쉽습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-329">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="0d279-330">디자인 탭을 클릭하여 옵션을 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="0d279-330">Click the Design tab for options.</span></span>

- <span data-ttu-id="0d279-331">**기본적으로 제공되는 Azure 스텐실:** 수십 개의 Azure 스텐실을 사용하여 클라우드 앱을 디자인하거나 아키텍처를 계획합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-331">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="0d279-332">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-332">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="0d279-p133">**깨진 Excel 링크 해결:** 데이터 시각화 도우미 다이어그램에 연결된 Excel 통합 문서를 찾을 수 없습니까? 링크를 다시 연결하면 정상으로 돌아옵니다. [자세히 알아보기](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="0d279-p133">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="0d279-336">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-336">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="0d279-337">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-337">Switching between them has never been easier.</span></span> [<span data-ttu-id="0d279-338">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-338">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="0d279-339">**Power BI에서 Visio 시각적 개체 내보내기** Power BI 보고서를 PDF, PowerPoint 파일 등으로 내보낼 때 Power BI용 Visio 시각적 개체가 올바르게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-339">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="0d279-340">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-340">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="0d279-341">Word</span><span class="sxs-lookup"><span data-stu-id="0d279-341">Word</span></span>

- <span data-ttu-id="0d279-342">**더 많은 페이지 색상을 사용하도록 학습 도구 모드에 추가 지원 제공:** Word의 학습 도구에 페이지 테마 색상에 대한 지원이 추가되어, 페이지의 배경색을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-342">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="0d279-343">많은 사람들이 흑백 또는 검정색 배경으로 읽는 것에 어려움을 느끼고 있으므로 PC 및 Mac의 Word에서 색상 선택을 확장했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-343">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="0d279-p137">**잉크 편집기로 자연스럽게 편집 가능:** 펜을 사용하여 단일 스트로크로 단어를 분할 또는 조인하거나, 새 줄을 추가하거나, 단어를 삽입할 수 있습니다. [자세한 정보](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="0d279-p137">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="0d279-p138">**평범한 문서를 훌륭한 문서로 개선하기:** 모든 장치에서 문서가 잘 보이도록 공유하기 쉬운 대화형의 웹 페이지로 변환합니다. [자세히 알아보기](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="0d279-p138">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="0d279-348">**콘텐츠 도달 범위 늘리기:** 접근성 높은 문서를 만들어야 하나요?</span><span class="sxs-lookup"><span data-stu-id="0d279-348">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="0d279-349">진행 중인 작업을 중단하지 않고 계속 접근성 검사를 실행하며 상태를 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-349">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="0d279-350">검토 > 접근성 검사를 클릭하여 검사를 시작해 보세요. 확인해야 할 결과를 발견하면 상태 표시줄에 알려드립니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-350">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="0d279-351">**해당 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="0d279-351">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="0d279-352">파일>홈페이지의 검색 상자에 입력하기만 하면 원하는 파일을 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-352">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="0d279-353">**원활하게 전환:** 새 계정 관리자는 모든 Office 365 작업 및 개인 계정을 한 곳에 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-353">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="0d279-354">회사 및 개인 계정 간 전환이 매우 용이합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-354">Switching between them has never been easier.</span></span> [<span data-ttu-id="0d279-355">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-355">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="0d279-p142">**라인 포커스로 가독성 개선:** 부드럽게 줄 단위로 문서를 넘길 수 있습니다. 한 번에 볼 때 1줄, 2줄, 또는 5줄에 포커스를 두도록 조정합니다. [자세히 알아보기](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="0d279-p142">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="0d279-359">**변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-359">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="0d279-360">**\@멘션으로 주의 끌기:** 메모에 @멘션을 사용하여 입력이 필요하다는 사실을 동료들에게 알립니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-360">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="0d279-361">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-361">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="0d279-362">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-362">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="0d279-363">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-363">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="0d279-364">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-364">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="0d279-365">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="0d279-365">Office Suite</span></span>

- <span data-ttu-id="0d279-366">**빠른 파일 찾기:** 최근에 작업한 파일을 찾으십니까?</span><span class="sxs-lookup"><span data-stu-id="0d279-366">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="0d279-367">원하는 파일을 찾으려면 파일 > 열기 탭의 검색 상자에 입력합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-367">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="0d279-368">**변경 내용을 실시간으로 저장:** 파일을 OneDrive에 업로드하여 모든 업데이트를 자동으로 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-368">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="0d279-369">**개인 정보 제어:** 진단 데이터 및 연결된 환경에 대한 업데이트 및 향상된 신규 컨트롤 작업</span><span class="sxs-lookup"><span data-stu-id="0d279-369">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="0d279-370">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-370">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="0d279-371">**Office 아이콘이 새롭게 단장했습니다.** 간단하고 강력하며 지능적인 Office 환경을 반영하여 Office 아이콘이 다시 디자인되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-371">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="0d279-372">**Microsoft Teams 설치:** Microsoft Teams는 기본적으로 Office 365 ProPlus 기존 설치에 설치됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-372">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="0d279-373">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="0d279-373">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="0d279-376">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="0d279-376">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="0d279-377">Access</span><span class="sxs-lookup"><span data-stu-id="0d279-377">Access</span></span>

- <span data-ttu-id="0d279-378">이 업데이트는 합계와 같은 집계가 결과를 정수 값으로 자를 수 있는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-378">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="0d279-379">이 업데이트는 원격 테이블(예: SQL Server 테이블)로의 참조를 포함하는 통합 쿼리가 Access를 닫고 다시 시작하도록 할 수 있는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-379">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="0d279-380">이 업데이트는 업데이트 쿼리가 실행되거나 UPDATE 문이 SQL에 사용될 때 &quot;쿼리가 손상되었습니다&quot; 오류를 일으킬 수있는 Microsoft Access의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-380">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="0d279-381">Excel</span><span class="sxs-lookup"><span data-stu-id="0d279-381">Excel</span></span>

- <span data-ttu-id="0d279-382">문서 타이틀에 대한 네덜란드어 키 설명이 Alt-G로 변경되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-382">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="0d279-383">도형 또는 양식 컨트롤에 할당된 매크로가 잘못된 오류 메시지를 표시하거나 잘못된 대상 범위에서 작동하는 Excel의 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-383">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="0d279-384">첫 번째 항목을 발견한 후 대화 상자에서 포커스가 있는 위치가 찾기 및 바꾸기로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-384">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="0d279-385">이를 통해 다른 사용자와 공동 작성 세션에 있는 동안 피벗 테이블이 정렬되는 방식을 변경하고 새로 고치면 충돌이 트리거될 수 있는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-385">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="0d279-386">OLAP PivotTable의 필터가 큐브에서 제거된 값으로 설정되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-386">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="0d279-387">차트 템플릿을 사용하여 차트를 삽입할 때 미리 보기에 사용되는 색을 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-387">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="0d279-388">시리즈 컬렉션을 변경할 때 분산형 차트가 제대로 렌더링되지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-388">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="0d279-389">셀을 삽입하거나 삭제하는 경우 폭포 차트와 깔때기형 차트가 테이블로 동기화되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-389">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="0d279-390">사용자에게 통합 문서를 다시 열어서 변경 내용을 적용하라는 메시지가 표시되는 Excel의 병합 충돌 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-390">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="0d279-391">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-391">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="0d279-392">최소화된 창을 활성화하는 매크로 런타임 오류를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-392">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="0d279-393">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-393">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="0d279-394">다른 사용자와 공동 작성하는 경우 표의 옆에 잘라내어 붙여 넣는 작업이 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-394">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="0d279-395">매크로가 실행되는 사용자 지정 속성을 변경할 때 공동 작성 작업을 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-395">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="0d279-396">추가 기능을 통해 연 WPF(Windows Presentation Foundation) 양식의 콤보 상자에서 항목을 선택할 수 없는 문제가 발생했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-396">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="0d279-397">통합 문서가 열려있지 않은 상태에서 최근 파일을 검색할 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-397">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="0d279-398">비동기식 사용자 정의 함수의 성능 문제로 인해 함수가 동기식으로 실행되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-398">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="0d279-399">병합된 셀이 있는 열을 삭제하는 성능이 크게 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-399">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="0d279-400">스크롤 후 셀을 선택하면 잘못된 셀이 선택되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-400">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="0d279-401">Lookup 함수에서 오류가 반환될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-401">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="0d279-402">이전 버전의 Office에서 만든 통합 문서를 현재 버전의 Office에서 열었을 때 Excel이 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-402">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="0d279-403">파일에 광범위한 조건부 서식이 있는 경우 글꼴색 단추를 클릭하면 성능이 저하되는 문제.</span><span class="sxs-lookup"><span data-stu-id="0d279-403">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="0d279-404">인쇄 미리 보기의 인쇄 영역이 올바르지 않았던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-404">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="0d279-405">신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 오류를 발생시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-405">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="0d279-406">색 기준 필터링의 성능이 대폭 향상되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-406">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="0d279-407">일부 보호된 시트에서 하이퍼링크를 붙여 넣을 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-407">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="0d279-408">추가 기능 관리자에서 검색할 때 16개 이상의 추가 기능이 표시되도록 활성화했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-408">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="0d279-409">이 변경 내용은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-409">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="0d279-410">cid 링크: 이제 Outlook 메시지의 이미지는 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-410">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="0d279-411">이 업데이트는 Office 문서가 "업로드 실패" 메시지와 함께 비즈니스용 OneDrive에 업로드되지 않을 수 있는 오류를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-411">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="0d279-412">Excel 아이디어 기능에서, Win32 클라이언트에 있는 아이디어 버튼을 클릭하여 추가 기능을 로드할 때 발생하는 오류를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-412">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="0d279-413">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d279-413">Outlook</span></span>

- <span data-ttu-id="0d279-414">cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-414">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="0d279-415">사서함을 기본 인증에서 최신 인증으로 업그레이드한 사용자가 Outlook 프로필에 연결된 잘못된 계정으로 끝나는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-415">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="0d279-416">웹 추가 기능이 디지털 권한 관리 메시지에 액세스하지 않아야 함에도 액세스하게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-416">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="0d279-417">일부 safelinks에서 간단한 호버 URL이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-417">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="0d279-418">이를 통해 첨부 파일 차단 논리를 업데이트하여 Outlook에서 Python 첨부 파일도 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-418">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="0d279-419">POP3 사용자의 하위 집합에서 설정에 관계없이 일반 텍스트로 서식이 지정된 모든 전자 메일을 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-419">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="0d279-420">이 수정은 HTML 서식이 지정된 메시지의 보기를 복원합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-420">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="0d279-421">기본 일정의 항목을 그룹 일정에 복사할 때 사용자에게 사용 권한 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-421">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="0d279-422">사용자가 화면 판독기를 통해 위치 제안에 액세스할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-422">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="0d279-423">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 상당한 지연이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-423">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="0d279-424">매우 긴 Outlook 세션에서 메모리 누수를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-424">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="0d279-425">규칙 대화 상자를 열 때 "이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다." 프롬프트가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-425">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="0d279-426">사용자가 특정 Safelinks와 상호 작용할 때 Outlook에서 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-426">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="0d279-427">대리인이 지정된 모임 요청에 응답했는지 여부와 관련하여 관리자에게 모호성을 유발하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-427">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="0d279-428">일부 AutoDiscover 응답을 처리할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-428">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="0d279-429">사용자가 계정 만들기 컨텍스트에서 지원 센터에 문의하려고 할 때 사용자에게 "확인" 버튼이 있는 빈 메시지 상자가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-429">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="0d279-430">이 변경으로 인해 관리자가 정책을 사용하여 UPN에 대한 자동 검색 인증 프롬프트에서 제공된 계정 전자 메일을 원하는 대로 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-430">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="0d279-431">기본적으로 AutoDiscover는 가능한 경우 계정 UPN을 선호합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-431">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="0d279-432">사용자가 Modern Groups에 대한 검색 실패를 보게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-432">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="0d279-433">특정 시나리오에서 Outlook 사용자가 “비밀번호 필요” 상태에 멈춰있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-433">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="0d279-434">사용자에게 회의실의 가용 시간 이외의 시간에 발생한 모임에 대해 사용자에게 회의실 제안이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-434">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="0d279-435">암호화된 전자 메일을 보낼 때 사용자에게 "암호화 알고리즘이 지원되지 않습니다." 오류가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-435">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="0d279-436">비영어 사용자에게 메일의 제목 줄이 너무 작게 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-436">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="0d279-437">보조 Exchange 계정을 추가할 때 만들어진 중복된 특수 폴더가 일부 사용자에게 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-437">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="0d279-438">사용자가 "부재 중 대화" 메시지에서 규칙을 만들려고 할 때 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-438">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="0d279-439">SMIME 알고리즘 선택 관련 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-439">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="0d279-440">대체 보낸 사람을 사용할 때 정책 팁이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-440">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="0d279-441">Outlook 프로세스에서 메모리 누수가 사용자에게 관찰되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-441">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="0d279-442">현재 상태 정보를 업데이트할 때 간헐적으로 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-442">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="0d279-443">현재 폴더 검색에 간헐적으로 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-443">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="0d279-444">일부 사용자가 Outlook에 대한 클라우드 설정을 검색할 때 사용자에게 인증 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-444">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="0d279-445">피드백 검색 환경을 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-445">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="0d279-446">일부 AutoDiscover 응답을 처리할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-446">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="0d279-447">현재 상태 정보를 업데이트할 때 간헐적으로 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-447">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d279-448">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d279-448">PowerPoint</span></span>

- <span data-ttu-id="0d279-449">일부 추가 기능이 차트의 도형 주변에 예기치 않은 오류를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-449">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="0d279-450">cid 링크: 이제 Outlook 메시지의 이미지는 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-450">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="0d279-451">이 변경으로 인해 PowerPoint 비디오 컨트롤의 액세스 가능한 이름이 복원되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-451">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="0d279-452">일부 애니메이션이 시작되지 않도록 하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-452">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="0d279-453">한 프레젠테이션에서 다른 프레젠테이션으로 슬라이드를 복사하면 마스터가 중복될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-453">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="0d279-454">지원되지 않는 버전에서 열었을 경우 최신 메모가 포함된 파일에 노란색 경고가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-454">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="0d279-455">안정성 수정: 타사 추가 기능이 PowerPoint와 충돌할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-455">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="0d279-456">PowerPoint의 세로 텍스트 상자에서 가타카나 반각글자가 제대로 회전하지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-456">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="0d279-457">Project</span><span class="sxs-lookup"><span data-stu-id="0d279-457">Project</span></span>

- <span data-ttu-id="0d279-458">Windows 7 사용자가 Project Web App 및 SharePoint 사이트에서 프로젝트를 열 수 있도록 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-458">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="0d279-459">읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 식별했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-459">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="0d279-460">모든 명령 수준으로 리소스 초과 할당이 제대로 해결되지는 않습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-460">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="0d279-461">과업에 대한 작업이 0인 과제가 있는 경우 해당 과업이 완성으로 표시되지 않고 항상 99%로 표시되는 문제.</span><span class="sxs-lookup"><span data-stu-id="0d279-461">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="0d279-462">Visio</span><span class="sxs-lookup"><span data-stu-id="0d279-462">Visio</span></span>

- <span data-ttu-id="0d279-463">Visio에서 SVG로 내보내기가 다양한 도형에서 실패했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-463">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="0d279-464">Word</span><span class="sxs-lookup"><span data-stu-id="0d279-464">Word</span></span>

- <span data-ttu-id="0d279-465">Word를 사용하여 문서를 열 경우 이 변경을 통해 성능이 개선됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-465">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="0d279-466">cid 링크: 이제 Outlook 메시지의 이미지는 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-466">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="0d279-467">Deskjet 프린터로 인쇄할 때 배율 문제가 발생할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-467">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="0d279-468">변경 내용 추적 시 때때로 무한 루프로 들어가는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-468">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="0d279-469">종료 시 앱이 중단될 수 있는 여러 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-469">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="0d279-470">또한 특정 추가 기능 관련 충돌도 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-470">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="0d279-471">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="0d279-471">Office Suite</span></span>

- <span data-ttu-id="0d279-472">히라가나와 간지에서 새로운 연호 "레이와"의 철자가 틀리거나 비문법적 표현으로 잘못 식별되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-472">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="0d279-473">SharePoint 2016에 저장된 파일을 공유하려고 할 때 사용자에게 "죄송합니다. 알 수 없는 이유로 이 파일을 공유할 수 없습니다."라는 메시지가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-473">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="0d279-474">PowerPoint에서 공동 작성 및 오프라인 편집이 모두 포함된 세션에서 데이터가 손실될 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-474">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="0d279-475">이를 통해 사용자가 파일을 열 때 발생하는 충돌 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-475">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="0d279-476">PowerPoint 사용자가 온라인으로 프레젠테이션할 때 오류가 발생하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-476">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="0d279-477">일부 인스턴스에서 동기화 엔진 백업 Sharepoint 파일에 '저장됨'이 표시되지만, 실제로 변경 내용이 저장되지 않아 데이터가 손실될 수 있었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-477">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="0d279-478">사용자가 Word, Excel 및 PowerPoint 문서를 저장할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-478">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="0d279-479">이 문제는 새 파일을 만든 후 저장 아이콘을 클릭하거나 Ctrl + S를 눌러 "다른 이름으로 저장 대화 상자" 옵션을 표시하는 사용자에게 영향을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-479">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="0d279-480">Win7에서는 모든 앱의 리본 메뉴에서 도형 갤러리 삽입을 표시하는 데 약 4초가 걸리는 성능 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-480">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="0d279-481">백스테이지의 정보 위치 조각에 접근성 정보가 표시되지 않는 버그를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-481">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="0d279-482">레지스트리 무결성과 관련된 Office 업데이트 프로세스의 안정성이 향상됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-482">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="0d279-483">Office 업데이트에서 로컬 또는 네트워크 공유 또는 Configuration Manager에서 제공하는 위치와 같은 의도된 원본 대신 Office CDN에서 파일을 예기치 않게 다운로드했을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-483">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="0d279-484">Office 업데이트 메시지가 다른 언어로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-484">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="0d279-485">앞으로 Office 업데이트 메시지 언어가 Windows 표시 언어와 정확하게 일치할 것입니다.  </span><span class="sxs-lookup"><span data-stu-id="0d279-485">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="0d279-486">사용자가 관리자가 아니고 시스템 계정에 네트워크 연결이 없는 특정한 경우에 업데이트가 적용되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-486">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="0d279-487">특정 상황에서 Office 바로 가기가 업데이트 후에 사라질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-487">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="0d279-488">이 업데이트는 Office 바로 가기를 게시할 때 안정성을 높입니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-488">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="0d279-489">데이터 통신 네트워크에서 업데이트가 예기치 않게 차단될 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-489">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="0d279-490">상대적인 마감일이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정 버그에 대한 픽스, 이 픽스는 후속 업데이트에 대한 상대적인 마감일도 사용할 수 있도록 해줍니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-490">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="0d279-491">이전에 중단되었을 수 있는 다운로드를 다시 시작하여 Office 업데이트를 다운로드할 경우의 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-491">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="0d279-492">타사의 플러그인에서 Textbox/Shape Autofit 속성과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-492">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="0d279-493">대규모 트리 보기에서 충돌이 발생할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-493">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="0d279-494">Office 고객의 보안을 위해 Microsoft Office 업데이트는 이제 SHA-2 알고리듬 만을 사용하여 서명됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-494">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1902-january-14"></a><span data-ttu-id="0d279-496">버전 1902: 1월 14일</span><span class="sxs-lookup"><span data-stu-id="0d279-496">Version 1902: January 14</span></span>
<span data-ttu-id="0d279-497">*버전 1902(빌드 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="0d279-497">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="0d279-498">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="0d279-498">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="0d279-500">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="0d279-500">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="0d279-501">Excel</span><span class="sxs-lookup"><span data-stu-id="0d279-501">Excel</span></span>

- <span data-ttu-id="0d279-502">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-502">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="0d279-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d279-503">Outlook</span></span>

- <span data-ttu-id="0d279-504">암호화된 전자 메일을 보낼 때 사용자에게 "암호화 알고리즘이 지원되지 않습니다." 오류가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-504">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d279-505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d279-505">PowerPoint</span></span>

- <span data-ttu-id="0d279-506">지원되지 않는 버전에서 열었을 경우 최신 메모가 포함된 파일에 노란색 경고가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-506">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="0d279-507">Word</span><span class="sxs-lookup"><span data-stu-id="0d279-507">Word</span></span>

- <span data-ttu-id="0d279-508">Word를 사용하여 문서를 열 경우 이 변경을 통해 성능이 개선됩니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-508">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1808-january-14"></a><span data-ttu-id="0d279-510">버전 1808: 1월 14일</span><span class="sxs-lookup"><span data-stu-id="0d279-510">Version 1808: January 14</span></span>
<span data-ttu-id="0d279-511">*버전 1808(빌드 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="0d279-511">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="0d279-512">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="0d279-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

> [!NOTE]
> <span data-ttu-id="0d279-514">Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0d279-514">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
