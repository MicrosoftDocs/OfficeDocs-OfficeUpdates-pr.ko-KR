---
title: 2020의 반기 엔터프라이즈 채널(미리 보기) 릴리스의 릴리스 정보
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 2020년 Microsoft 365 앱에 대한 반기 채널(대상 지정) 릴리스의 릴리스 정보를 IT 전문가에게 제공합니다.
ms.openlocfilehash: d6c48db35445d15503c246506bc7d03da3ca0548
ms.sourcegitcommit: 4a2190fd43c552c92d8194ec4520673d75af22f1
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/13/2021
ms.locfileid: "51748966"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="bcb41-103">반기 기업 채널(프리뷰)의 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="bcb41-104">이 릴리스 정보에서는 엔터프라이즈용 Microsoft 365 앱, 비즈니스용 Microsoft 365 앱 및 프로젝트 및 Visio용 데스크톱 앱의 구독 버전에 대한 반기별 엔터프라이즈 채널(미리 보기) 업데이트에 포함된 새로운 기능 및 비보안 업데이트에 대한 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="bcb41-105">당사는 Microsoft 365 앱에 대한 업데이트 채널을 일부 변경하고 있습니다. 여기에는 새 업데이트 채널 추가(월별 엔터프라이즈 채널) 및 기존 업데이트 채널의 이름 변경 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="bcb41-106">자세한 내용은 [이 문서를 검토하세요](/DeployOffice/update-channels-changes).</span><span class="sxs-lookup"><span data-stu-id="bcb41-106">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>


## <a name="version-2102-april-13"></a><span data-ttu-id="bcb41-107">버전 2102: 4월 13일</span><span class="sxs-lookup"><span data-stu-id="bcb41-107">Version 2102: April 13</span></span>
<span data-ttu-id="bcb41-108">*버전2102(빌드 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-108">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="bcb41-109">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-111">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-111">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="bcb41-112">Access</span><span class="sxs-lookup"><span data-stu-id="bcb41-112">Access</span></span>

- <span data-ttu-id="bcb41-113">일부 경우 SQL Server 통과 쿼리를 실행하면 "커서 상태가 잘못되었습니다"라는 오류 메시지가 표시될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-113">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="bcb41-114">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-114">Excel</span></span>

- <span data-ttu-id="bcb41-115">Office 리본에서 비활성화된 명령의 아이콘은 회색으로 표시되지만 어두운 회색 Office 테마의 텍스트는 회색으로 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-115">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="bcb41-116">다른 시트의 표에 행을 추가한 후 예기치 않게 셀에 데이터 유효성 검사를 적용할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-116">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="bcb41-117">32비트 버전의 Excel에 있는 대화 상자 시트에서 함수가 작동하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-117">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="bcb41-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-118">Outlook</span></span>

- <span data-ttu-id="bcb41-119">Outlook이 유휴 시 충돌하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-119">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="bcb41-120">새 장치에서 Outlook을 구성한 후 클라우드 설정 기능 사용자가 기본 설정으로 재정의된 사용자 지정 설정을 볼 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-120">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="bcb41-121">사용자에게 예상보다 더 많은 서명이 표시될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-121">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="bcb41-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-122">PowerPoint</span></span>

- <span data-ttu-id="bcb41-123">Office 리본에서 비활성화된 명령의 아이콘은 회색으로 표시되지만 어두운 회색 Office 테마의 텍스트는 회색으로 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-123">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="bcb41-124">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-124">Word</span></span>

- <span data-ttu-id="bcb41-125">Office 리본에서 비활성화된 명령의 아이콘은 회색으로 표시되지만 어두운 회색 Office 테마의 텍스트는 회색으로 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-125">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="bcb41-126">복사 및 붙여넣기와 관련된 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-126">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="bcb41-127">숨겨진 단락 끝에 입력할 때 응용 프로그램이 중단될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-127">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="bcb41-128">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-128">Office Suite</span></span>

- <span data-ttu-id="bcb41-129">편집 내용을 저장되지 않은 채로 이전에 연 파일을 열 때 사용자가 파일을 저장할 수 없었던 문제를 해결했으며, 이제 파일이 삭제됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-129">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="bcb41-130">수정이 적용된 후 사용자에게 파일 삭제를 알리는 친숙한 메시지가 전송되므로 변경 내용을 취소하거나 다른 이름으로 파일을 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-130">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="bcb41-131">SyncBacked 파일을 오프라인으로 열고 파일을 저장하기 전에 앱의 파일 이름을 바꿀 때 이름 변경 실패 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-131">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="bcb41-132">GCC 사용자가 받아쓰기 기능을 사용할 수 없는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-132">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="bcb41-133">가끔 Outlook의 텍스트가 투명해지고 읽을 수 없게 되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-133">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2102-march-09"></a><span data-ttu-id="bcb41-135">버전 2102: 3월 9일</span><span class="sxs-lookup"><span data-stu-id="bcb41-135">Version 2102: March 09</span></span>
<span data-ttu-id="bcb41-136">*버전 2102(빌드 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-136">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="bcb41-137">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-137">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="bcb41-139">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-139">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-140">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-140">Excel</span></span>

- <span data-ttu-id="bcb41-141">**잉크 도구 상자의 올가미 및 지우개:** 그리기 도구를 사용할 때 잉크 도구 상자에서 올가미와 지우개를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-141">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="bcb41-142">[블로그 게시물](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-142">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="bcb41-143">**PDF 연결 설정:** PDF로 연결하고 PDF에서 데이터를 가져오고 새로 고칩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-143">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="bcb41-144">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-144">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="bcb41-145">**수식에 사용할 변수 만들기:** LET 기능으로 성능, 가독성 및 구성성을 향상시킵니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-145">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="bcb41-146">이 함수를 사용하면 새로운 공식 또는 기존 공식으로 명명된 변수를 작성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-146">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="bcb41-147">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-147">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="bcb41-148">[블로그 게시물](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-148">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="bcb41-149">**고정된 폴더에 저장:** 폴더를 고정하면 Office 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-149">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="bcb41-150">새 파일을 저장할 때 사용할 수 있는 폴더에 대한 추가 제어를 원하다는 사용자 피드백을 받았습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-150">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="bcb41-151">저장 대화 상자에서 폴더를 고정하는 새로운 기능을 제공하게 되어 기쁘게 생각합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-151">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="bcb41-152">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-152">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="bcb41-153">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-153">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="bcb41-154">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-154">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="bcb41-155">**데이터 형식을 사용하여 Power BI에서 조직 데이터를 가져오기:** 이제 Power BI의 Excel 데이터 형식을 Office 365/Microsoft 365를 사용하는 조직의 참가자에게 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-155">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="bcb41-156">필요한 정보를 가져오고 손쉽게 새로 고치는 건 일상적인 여러 워크플로에 매우 중요합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-156">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="bcb41-157">Microsoft는 Power BI를 사용하여 Excel에서 데이터 형식으로 회사나 조직 정보에 액세스할 수 있도록 하여 스프레드시트에 연결된 정보를 제공하는 기능을 확장합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-157">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="bcb41-158">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-158">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="bcb41-159">[블로그 게시물](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-159">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="bcb41-160">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-160">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="bcb41-161">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-161">No conversion required.</span></span><br /><span data-ttu-id="bcb41-162">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-162">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="bcb41-163">**Excel에서 세련된 Visio 다이어그램 만들기:** 워크시트의 데이터를 사용하여 순서도나 조직도와 같은 데이터 기반 다이어그램을 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-163">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="bcb41-164">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-164">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="bcb41-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-165">Outlook</span></span>

- <span data-ttu-id="bcb41-166">**그룹의 데이터 보호 지원:** 그룹을 만들 때 선택한 민감도 레이블이 그룹 전자 메일, 문서, 팀 사이트에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-166">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="bcb41-167">**IT 관리자에 대한 인시던트 알림:** Microsoft 365 테넌트 전역 관리자 및 Office 앱 관리자는 Windows용 Outlook의 새로운 오른쪽 패널 알림을 통해 사용자에게 영향을 주는 Outlook 및 O365 Exchange 인시던트에 대한 알림을 받습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-167">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="bcb41-168">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-168">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="bcb41-169">**문자 서식을 사용해 Outlook 설문 조사 만들기**: 설문 조사를 쉽게 작성하고 투표를 수집하며 전자 메일로 결과를 볼 수 있습니다 [자세한 내용 보기](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="bcb41-169">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="bcb41-170">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-170">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="bcb41-171">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-171">No conversion required.</span></span><br /><span data-ttu-id="bcb41-172">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-172">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="bcb41-173">**새 회의실 찾기:** 다양한 기능으로 회의실을 검색합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-173">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="bcb41-174">**평소 말하는 식으로 검색:** "지난주 동물 병원 진료 예약"과 같은 일상적인 언어를 사용하여 검색을 필터링하고 범위를 좁힙니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-174">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="bcb41-175">**이전 Outlook 세션의 항목을 빠르게 다시 여는 옵션:** 이전 Outlook 세션의 항목을 빠르게 다시 여는 옵션을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-175">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="bcb41-176">[블로그 게시물](https://insider.office.com/ko-KR/blog/automatically-restore-windows-in-outlook)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-176">See details in [blog post](https://insider.office.com/ko-KR/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="bcb41-177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-177">PowerPoint</span></span>

- <span data-ttu-id="bcb41-178">**잉크 도구 상자의 올가미 및 지우개:** 그리기 도구를 사용할 때 잉크 도구 상자에서 올가미와 지우개를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-178">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="bcb41-179">[블로그 게시물](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-179">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="bcb41-180">**고정된 폴더에 저장:** 폴더를 고정하면 Office 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-180">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="bcb41-181">새 파일을 저장할 때 사용할 수 있는 폴더에 대한 추가 제어를 원하다는 사용자 피드백을 받았습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-181">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="bcb41-182">저장 대화 상자에서 폴더를 고정하는 새로운 기능을 제공하게 되어 기쁘게 생각합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-182">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="bcb41-183">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-183">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="bcb41-184">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-184">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="bcb41-185">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-185">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="bcb41-186">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-186">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="bcb41-187">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-187">No conversion required.</span></span><br /><span data-ttu-id="bcb41-188">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-188">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="bcb41-189">Visio</span><span class="sxs-lookup"><span data-stu-id="bcb41-189">Visio</span></span>

- <span data-ttu-id="bcb41-190">**새 Azure 스텐실 및 셰이프:** 최신 Azure 다이어그램을 작성하는 데 도움이 되도록 스텐실을 더 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-190">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="bcb41-191">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-191">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="bcb41-192">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-192">Word</span></span>

- <span data-ttu-id="bcb41-193">**잉크 도구 상자의 올가미 및 지우개:** 그리기 도구를 사용할 때 잉크 도구 상자에서 올가미와 지우개를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-193">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="bcb41-194">[블로그 게시물](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-194">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="bcb41-195">**고정된 폴더에 저장:** 폴더를 고정하면 Office 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-195">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="bcb41-196">새 파일을 저장할 때 사용할 수 있는 폴더에 대한 추가 제어를 원하다는 사용자 피드백을 받았습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-196">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="bcb41-197">저장 대화 상자에서 폴더를 고정하는 새로운 기능을 제공하게 되어 기쁘게 생각합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-197">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="bcb41-198">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-198">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="bcb41-199">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-199">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="bcb41-200">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-200">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="bcb41-201">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-201">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="bcb41-202">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-202">No conversion required.</span></span><br /><span data-ttu-id="bcb41-203">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-203">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="bcb41-204">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-204">Office Suite</span></span>

- <span data-ttu-id="bcb41-205">**탭 창:** 이제 앱의 오른쪽에 있는 탭 UI를 사용하여 여러 창 간에 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-205">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="bcb41-206">UI는 2개 이상의 창이 열려있는 경우에만 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-206">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="bcb41-207">[블로그 게시물](https://blog-insider.office.com/2020/02/20/improved-pane-management/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-207">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-210">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-210">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="bcb41-211">Access</span><span class="sxs-lookup"><span data-stu-id="bcb41-211">Access</span></span>

- <span data-ttu-id="bcb41-212">Office가 아닌 응용 프로그램에서 DAO를 사용할 경우 응용 프로그램이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-212">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="bcb41-213">사용자에게 "잘못된 커서 상태" 오류 대화 상자가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-213">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="bcb41-214">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-214">Excel</span></span>

- <span data-ttu-id="bcb41-215">일부 레거시 Excel 4.0 및 Excel 5.0 매크로와 dialogsheets.show에 대한 일부 VBA 호출이 깨지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-215">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="bcb41-216">피벗 테이블에서 "값 표시 형식" 메뉴를 사용하는 경우 Excel이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-216">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="bcb41-217">사용자가 Excel 통합 문서를 PDF로 내보낼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-217">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="bcb41-218">연결된 그림 붙여넣기 옵션을 사용할 때 이미지가 예상보다 작아지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-218">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="bcb41-219">.xls 또는 .xlt 형식으로 저장할 때 일부 피벗 테이블 형식으로 인해 통합 문서가 손상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-219">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="bcb41-220">Excel 4.0 매크로가 포함된 Excel 추가 기능 파일을 열 때 메시지 표시 없이 매크로가 계속 사용하지 않는 상태로 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-220">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="bcb41-221">Excel이 새 버전의 파일을 사용할 수 있다는 메시지 표시줄을 잘못 표시하여 사용자가 변경 내용을 통합 문서 사본에 저장하거나 변경 내용을 취소하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-221">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="bcb41-222">공동 작성 시 파일의 새 버전을 알려주는 메시지 표시줄이 일부 사용자에게 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-222">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="bcb41-223">특정 Windows 보안 공격 방지 설정(SimExec, 호출자 확인)을 사용 중인 경우 Excel이 예기치 않게 시작되지 않거나 닫히는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-223">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="bcb41-224">차트에서 데이터 계열을 선택한 후 Excel이 응답하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-224">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="bcb41-225">이 변경 사항은 수식 내에서 글꼴을 올바르게 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-225">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="bcb41-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-226">Outlook</span></span>

- <span data-ttu-id="bcb41-227">사용자가 대리인에게 편집자 권한을 부여할 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-227">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="bcb41-228">일부 사용자가 특정 검색 시나리오에서 Outlook이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-228">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="bcb41-229">프로필에 큰 계층이 있는 공유 사서함 또는 위임된 사서함을 가진 사용자가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-229">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="bcb41-230">전자 메일의 제목 줄이 비어있는 경우 일부 자동으로 생성된 전자 메일이 이를 빈 본문으로 보내는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-230">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="bcb41-231">일부 사용자가 예기치 않게 오프라인 상태에서 Outlook이 시작되는 것을 관찰하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-231">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="bcb41-232">대리인이 다른 사서함에서 공유 폴더를 열 때 간헐적으로 오류가 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-232">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="bcb41-233">사용자가 검색 결과를 선택하면 응용 프로그램이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-233">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="bcb41-234">일부 고객이 일정을 로드하는 동안 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-234">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="bcb41-235">일부 모임에서 다른 참석자가 모임을 전달하는 경우 모임의 기존 참석자가 취소 통지를 받는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-235">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="bcb41-236">사용자가 새 그룹을 만들고 나서 중복 일정 그룹이 나타나는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-236">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="bcb41-237">공유 일정의 향상된 기능 사용자가 일정의 색을 노란색 또는 갈색으로 설정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-237">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="bcb41-238">Outlook이 다시 시작될 때까지 탐색 창에 새로 추가된 일정이 나타나지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-238">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="bcb41-239">캐시되지 않은 공유 일정을 검색할 때 검색 결과가 반환되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-239">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="bcb41-240">일부 사용자가 메시지 창을 닫을 때 앱이 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-240">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="bcb41-241">작업에 대해 상황 보고서를 보낼 때 받는 사람 필드가 비어 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-241">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="bcb41-242">MailItem.BeforeAttachmentAdd 이벤트가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-242">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="bcb41-243">일부 사용자가 특정 검색 시나리오에서 Outlook이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-243">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="bcb41-244">사용자가 Outlook에서 검색할 때 앱이 가끔 예기치 않게 닫히는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-244">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="bcb41-245">클라우드 설정 사용자가 설정을 업데이트할 때 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-245">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="bcb41-246">사용자에게 편집된 서명을 저장하라는 메시지가 표시된 후 저장되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-246">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="bcb41-247">하나 이상의 서명이 구성되었음에도 불구하고 일부 사용자에게 서명 드롭다운이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-247">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="bcb41-248">사용자에 대한 클라우드 설정이 기본적으로 설정되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-248">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="bcb41-249">사용자 서명 변경 내용이 저장되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-249">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="bcb41-250">클라우드 설정을 사용하도록 설정한 사용자에 대해 Outlook에서 또 하나의 빈 서명을 만들도록 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-250">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="bcb41-251">OWA에 올바른 기본 서명을 표시하는 것과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-251">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="bcb41-252">유니코드 콘텐츠를 포함하는 서명이 손상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-252">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="bcb41-253">인라인 번역 사용자가 피드백을 제출할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-253">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="bcb41-254">회신하거나 전달할 때 중국어 메시지의 머리글을 읽을 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-254">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="bcb41-255">OFT 파일로 저장하면 중국어 문자가 물음표로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-255">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="bcb41-256">IDataObject 작업(예: 끌어서 놓기, 클립보드)에서 첨부 파일에 대한 filetime 포함을 사용하지 않도록 설정할 수 있는 regkey를 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-256">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="bcb41-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="bcb41-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="bcb41-258">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="bcb41-258">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="bcb41-259">0 = filetimes가 제외됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-259">0 = filetimes are excluded.</span></span>  <span data-ttu-id="bcb41-260">1 = (기본값) filetimes가 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-260">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="bcb41-261">Azure Information Protection의 보호 레이블을 사용하여 메시지에 회신할 때 인라인 이미지를 사라지게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-261">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="bcb41-262">암호화 전용 옵션을 사용하여 보낸 전자 메일에서 암호화 아이콘이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-262">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="bcb41-263">사용자가 해당 옵션을 선택하지 않은 후 메일이 디지털 서명으로 전송될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-263">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="bcb41-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-264">PowerPoint</span></span>

- <span data-ttu-id="bcb41-265">문서 저장에 실패한 경우 응용 프로그램이 예기치 않게 닫히게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-265">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="bcb41-266">Word에서 PowerPoint로 수식 복사/붙여넣기 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-266">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="bcb41-267">이 변경 사항은 특정 지오메트리를 사용하여 형상 병합 작업을 적용할 때 경로 채우기 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-267">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="bcb41-268">이 변경 사항은 수식 내에서 글꼴을 올바르게 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-268">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="bcb41-269">이 변경 사항은 비디오 로드 중에 발생할 수 있는 처리 오류 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-269">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="bcb41-270">Slide.Shapes.AddMediaObject2가 레거시 비디오 형식(MPG-1, Mpeg-2)에 가깝게 되는 VBA 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-270">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="bcb41-271">QAT에서 추가된 글꼴 크기 명령이 업데이트하는 동안 가장 가까운 정의된 글꼴 크기로 자동 완성되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-271">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="bcb41-272">새로 녹음된 오디오가 포함된 슬라이드를 복제한 후 파일을 저장할 때 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-272">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="bcb41-273">삽입 후에 사용자가 다른 슬라이드를 클릭하여 슬라이드가 표시될 때까지 Forms 콘텐츠 추가 기능이 렌더링되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-273">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="bcb41-274">제한된 보기에서 PowerPoint 파일을 열 때 IRM 보호를 사용하지 않도록 설정하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-274">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="bcb41-275">많은 수의 특정 데이터 개체 유형(E2o)이 포함된 파일에서 공동 작성 속도가 느려지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-275">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="bcb41-276">병합 오류 중에 IRM/보호된 문서를 사용할 때 문제를 해결하는 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-276">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="bcb41-277">PresentationBeforeClose 이벤트를 청취하고 프레젠테이션을 확인하는 추가 기능이 있을 때 문서를 닫는 경우 저장 프롬프트가 루프에 표시되는 문제에 대한 수정 사항입니다. 속성을 이벤트 처리기의 일부로 저장했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-277">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="bcb41-278">문서 복구 작업 후에도 손상된 PowerPoint 파일이 올바르게 열리지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-278">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="bcb41-279">때때로 디자인 아이디어를 선택하면 프레젠테이션의 데이터 분류 레이블이 제거되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-279">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="bcb41-280">Project</span><span class="sxs-lookup"><span data-stu-id="bcb41-280">Project</span></span>

- <span data-ttu-id="bcb41-281">PWA에서 로컬 mpp 파일로 프로젝트를 저장하는 경우 ProjectBeforeTaskChangeEvent가 실제로 사용자가 변경하지 않은 데이터에 대해 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-281">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="bcb41-282">작업 양식 유형 보기에서 간격이 변경되는 경우 ProjectBeforeTaskChagne 이벤트의 NewVal에 올바른 값이 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-282">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="bcb41-283">이벤트 코드를 실행 중이고 작업 폼 보기를 통하여 변경을 하려고 하는 경우, 확인 단추를 클릭하면 변경 내용이 커밋되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-283">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="bcb41-284">특정 방식으로 리소스 배분 형식이 지정된 파일을 열 때 Project가 예기치 않게 종료될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-284">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="bcb41-285">로드의 특정 부분에 프로젝트 파일에 문제가 있는 경우 특정 프로젝트를 열 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-285">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="bcb41-286">팀 플래너 보기에 작업에 대한 테두리가 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-286">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="bcb41-287">끌어서 놓기 작업이 팀 플래너에서 작동하지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-287">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="bcb41-288">마일스톤 작업에 비용 자원이 할당되었을 때 기준 비용이 올바르게 롤업되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-288">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="bcb41-289">Visio</span><span class="sxs-lookup"><span data-stu-id="bcb41-289">Visio</span></span>

- <span data-ttu-id="bcb41-290">사용자 지정 Visio 스텐실 및 내장 템플릿 모두에 대해 Office 365용 Visio의 커넥터를 사용하여 직선을 생성할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-290">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="bcb41-291">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-291">Word</span></span>

- <span data-ttu-id="bcb41-292">문서 저장에 실패한 경우 응용 프로그램이 예기치 않게 닫히게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-292">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="bcb41-293">Word에서 PowerPoint로 수식 복사/붙여넣기 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-293">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="bcb41-294">이 변경 사항은 문서 편집 시 커서 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-294">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="bcb41-295">3D 효과가 있는 아이콘 및 SVG 그래픽에 적용된 색과 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-295">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="bcb41-296">내레이터에서 단락을 건너뛰는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-296">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="bcb41-297">서식 있는 텍스트 콘텐츠 컨트롤 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-297">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="bcb41-298">스타일 갤러리 대화 상자와 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-298">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="bcb41-299">공동으로 작성할 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-299">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="bcb41-300">문서 스타일이 서식 파일의 다른 스타일로 바뀌는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-300">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="bcb41-301">최적화된 게이트에 의해 노출된, Word에 영향을 미치는 어설트 버그를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-301">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="bcb41-302">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-302">Office Suite</span></span>

- <span data-ttu-id="bcb41-303">동기화 지원에서 서버 전용으로 전환된 파일을 저장할 때 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-303">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="bcb41-304">특정 시나리오에서 SaveAs를 시도하면 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-304">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="bcb41-305">SaveRequestManagerCam이 오류를 반환하는 대신 응용 프로그램을 종료하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-305">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="bcb41-306">모든 상호 종단 구성 요소가 순차적으로 닫히도록 파일 닫기 순서가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-306">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="bcb41-307">캐시의 URL과 OneDrive의 URL이 일치하지 않을 때 파일이 SyncBacked가 아닌 상태로 열리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-307">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="bcb41-308">비즈니스용 Skype 메시지에서 복사/붙여넣기를 하면 "콘텐츠를 붙여넣는 중에 오류가 발생했습니다"라는 대화 상자가 표시되는 버그를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-308">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="bcb41-309">설명에서 Excel로 텍스트를 복사/붙여넣을 때 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-309">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="bcb41-310">수학 방정식을 포함하는 텍스트에서 내레이터를 사용할 때 발생할 수 있는 충돌을 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-310">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="bcb41-311">Office에서 사용자가 잉크젯 프린터로 문서/파일을 인쇄하고 프린터의 잉크가 부족하면, 잉크젯 프린터에 토너가 없더라도 "토너 부족" 또는 "토너 없음" 메시지가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-311">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="bcb41-312">메시지를 변경하여 "토너/잉크 부족" 및 "토너/잉크 없음"으로 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-312">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="bcb41-313">이전 버전에서 새 Office 버전을 설치하면 레지스트리 항목이 누락되어 전원 쿼리를 사용할 수 없는 등의 기능이 누락될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-313">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="bcb41-314">Microsoft 365 엔드포인트 데이터 손실 방지로 인해 디스크의 Office 문서를 분류하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-314">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="bcb41-315">특정 사용자 설정이 유지되지 않는 그림 압축 대화 상자의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-315">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="bcb41-316">미디어 컨트롤러 이벤트 알림과 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-316">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="bcb41-317">미디어 플레이어 엔진 타이밍과 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-317">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="bcb41-318">최적화된 이진 크기</span><span class="sxs-lookup"><span data-stu-id="bcb41-318">Optimized binary size.</span></span>


- <span data-ttu-id="bcb41-319">Anaheim 웹 보기는 아직 WIP(Windows Information Protection)를 지원 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-319">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="bcb41-320">이 수정 기능은 WIP를 사용하는 환경의 하위 웹에 Office 추가 플랫폼을 다시 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-320">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="bcb41-321">이 기능은 고객의 컴퓨터 환경에 따라 Edge Spartan 웹 보기 또는 Trident 웹 보기가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-321">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="bcb41-322">하위 수준 WebViews 모두 WIP를 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-322">Both down level WebViews support WIP.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-february-09"></a><span data-ttu-id="bcb41-324">버전 2008: 2월 9일</span><span class="sxs-lookup"><span data-stu-id="bcb41-324">Version 2008: February 09</span></span>
<span data-ttu-id="bcb41-325">*버전 2008 (빌드 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-325">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="bcb41-326">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-326">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-328">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-329">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-329">Excel</span></span>

- <span data-ttu-id="bcb41-330">잘못된 파일 특성(만든 시간, 수정된 시간 등)이 있는 UNC 파일을 열 때 Excel이 예기치 않게 닫히는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-330">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="bcb41-331">Excel에서 차트를 복사하여 Word 또는 PowerPoint에 붙여넣을 때 소수점 및 천 단위 구분 기호 설정이 수행되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-331">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="bcb41-332">매크로가 실행될 때마다 피벗 테이블 범위 형식과 관련된 매크로 실행 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-332">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="bcb41-333">시트를 복사하거나 다른 통합 문서로 이동할 때 조건부 서식 규칙이 삭제되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-333">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="bcb41-334">앱 부팅 시 시작 화면이 비활성화되었을 때 사용자가 Excel 파일에 민감도 레이블을 적용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-334">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="bcb41-335">OneDrive 동기화 폴더에서 클라우드 파일을 여는 중 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-335">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="bcb41-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-336">Outlook</span></span>

- <span data-ttu-id="bcb41-337">첨부 파일을 추가하거나 저장할 때 Outlook이 산발적으로 작동을 멈추게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-337">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="bcb41-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-338">PowerPoint</span></span>

- <span data-ttu-id="bcb41-339">QAT에서 추가한 글꼴 크기 명령이 업데이트하는 동안 가장 가까운 정의된 글꼴 크기로 자동 완성되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-339">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="bcb41-340">'원본 서식 유지' 옵션이 때때로 새 슬라이드 마스터에 복사되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-340">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="bcb41-341">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-341">Word</span></span>

- <span data-ttu-id="bcb41-342">변경사항 추적에서 Word 문서를 열면 오류 대화상자가 표시될 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-342">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="bcb41-343">OneDrive 동기화 폴더에서 클라우드 파일을 여는 중 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-343">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="bcb41-344">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-344">Office Suite</span></span>

- <span data-ttu-id="bcb41-345">Office에서 파일을 열 수 없는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-345">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="bcb41-346">서식 복사를 통해 커넥터에 적용된 스케치된 윤곽선이 포함된 문서가 손상될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-346">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-january-12"></a><span data-ttu-id="bcb41-348">버전 2008: 1월 12일</span><span class="sxs-lookup"><span data-stu-id="bcb41-348">Version 2008: January 12</span></span>
<span data-ttu-id="bcb41-349">*버전 2008(빌드 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-349">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="bcb41-350">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-350">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-352">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-352">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-353">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-353">Excel</span></span>

- <span data-ttu-id="bcb41-354">읽기 전용 책을 열면 피벗 테이블 데이터를 더 이상 새로 고칠 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-354">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="bcb41-355">이 변경 사항은 다음 문제에 대한 수정 사항을 제공합니다. OneDrive 로컬 동기화 폴더에서 파일을 삽입하면 Excel "개체 삽입"에 올바른 아이콘이 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-355">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="bcb41-356">공동 작성 시 새 파일 버전에 대한 알림을 고객이 잘못 받는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-356">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="bcb41-357">덮어쓰기 모드에서 IME를 사용하면 추가 문자를 잘못 전달할 수 있는 편집 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-357">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="bcb41-358">다중 스레드 재호출 기능과 함께 실시간 데이터를 사용할 때 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-358">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="bcb41-359">특정 Windows 보안 공격 방지 설정(SimExec, 호출자 확인)을 사용 중인 경우 Excel이 예기치 않게 시작되지 않거나 닫히는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-359">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="bcb41-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-360">Outlook</span></span>

- <span data-ttu-id="bcb41-361">초안에 저장할 때 SmartLinks의 서식이 손실되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-361">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="bcb41-362">정책을 재정의할 때 사유 텍스트를 사용자 지정할 수 있는 방법을 제공하도록 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-362">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="bcb41-363">OFT 파일로 저장하면 중국어 문자가 물음표로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-363">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="bcb41-364">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-364">PowerPoint</span></span>

- <span data-ttu-id="bcb41-365">Slide.Shapes.AddMediaObject2가 레거시 비디오 형식(MPG-1, Mpeg-2)과 충돌하는 VBA 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-365">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="bcb41-366">문서 복구 작업 후에도 손상된 PowerPoint 파일이 올바르게 열리지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-366">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="bcb41-367">Project</span><span class="sxs-lookup"><span data-stu-id="bcb41-367">Project</span></span>

- <span data-ttu-id="bcb41-368">특정 방식으로 리소스 윤곽선이 지정된 파일을 열 때 Project가 예기치 않게 종료될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-368">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="bcb41-369">Skype</span><span class="sxs-lookup"><span data-stu-id="bcb41-369">Skype</span></span>

- <span data-ttu-id="bcb41-370">사용자의 TLS-DSK 인증서가 예상 시간에 갱신되지 않고 유효 기간이 12시간 미만인 경우에만 갱신되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-370">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="bcb41-371">Office에 대한 라이선스가 아직 없을 때 로그인 후 비즈니스용 Skype UI가 공백으로 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-371">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="bcb41-372">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-372">Office Suite</span></span>

- <span data-ttu-id="bcb41-373">이렇게 변경하면 레거시 다이어그램이 포함된 파일 열기 관련 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-373">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="bcb41-374">이렇게 변경하면 액세스 위반을 초래하는 SVG 예비 프록시의 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-374">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2008-december-08"></a><span data-ttu-id="bcb41-376">버전 2008: 12월 8일</span><span class="sxs-lookup"><span data-stu-id="bcb41-376">Version 2008: December 08</span></span>
<span data-ttu-id="bcb41-377">*버전 2008(빌드 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-377">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="bcb41-378">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-378">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-380">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-380">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="bcb41-381">Access</span><span class="sxs-lookup"><span data-stu-id="bcb41-381">Access</span></span>

- <span data-ttu-id="bcb41-382">ODBC DSN 빌더를 사용할 때 발생하는 오류 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-382">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="bcb41-383">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-383">Excel</span></span>

- <span data-ttu-id="bcb41-384">피벗 테이블을 Project 계획에서 내보낸 경우 피벗 테이블을 편집할 수 없고 통합 문서를 저장할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-384">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="bcb41-385">읽기 전용 모드에서 파일을 열 때 여러 개의 메시지 표시줄이 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-385">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="bcb41-386">중복된 열 머리글 값이 많을 때 개요 하위 합계가 작동을 중지할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-386">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="bcb41-387">다중 스레드 재계산 중 그룹 정책 개체 업데이트(예: 원격 그룹 정책 새로 고침)가 있을 때 Excel이 작동을 중지하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-387">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="bcb41-388">사용자가 255개 이상의 열에서 소계 함수를 사용할 때 Excel이 작동을 중지하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-388">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="bcb41-389">콘텐츠를 Excel에서 복사하여 Embed 옵션으로 PowerPoint에 붙여넣을 때 PowerPoint에서 커닝이 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-389">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="bcb41-390">PowerPivot의 테이블 프리뷰 및 쿼리 편집기에서 전환되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-390">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="bcb41-391">사용자가 SharePoint에서 직접 atomsvc(UTF8+BOM) 파일을 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-391">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="bcb41-392">파워 피벗이 탭 구분 기호를 성공적으로 인식하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-392">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="bcb41-393">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-393">Outlook</span></span>

- <span data-ttu-id="bcb41-394">작업에 대해 상황 보고서를 보낼 때 받는 사람 필드가 비어 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-394">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="bcb41-395">MailItem.BeforeAttachmentAdd 이벤트가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-395">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="bcb41-396">Outlook 이외의 응용 프로그램에서 Outlook 메일을 보낼 때 일부 사용자가 예기치 않게 응용 프로그램을 종료하는 문제가 발생했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-396">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="bcb41-397">온라인 모드에서 폴더 간에 여러 메일 항목을 이동할 때 사용자의 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-397">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="bcb41-398">IDataObject 작업(예: 끌어서 놓기, 클립보드)에서 첨부 파일에 대한 filetime 포함을 사용하지 않도록 설정할 수 있는 regkey를 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-398">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="bcb41-399">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes 제외됨  1 = (기본값) filetimes 포함됨</span><span class="sxs-lookup"><span data-stu-id="bcb41-399">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="bcb41-400">Azure Information Protection의 보호 레이블을 사용하여 메시지에 회신할 때 인라인 이미지를 사라지게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-400">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="bcb41-401">Azure Protected Voicemail을 보낼 때 사용자 이름을 전화 번호로 표시하여 Outlook 데스크톱 사용자가 외부 사용자의 음성 메일을 열 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-401">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="bcb41-402">OME 구성을 설정하면 서비스 측에서 DecryptAttachmentsForEncryptOnly 옵션이 설정되어 있는데도 Outlook에서 메시지를 암호화하도록 강제하는 관련 없는 첨부 파일이 메일 항목에 추가되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-402">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="bcb41-403">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-403">PowerPoint</span></span>

- <span data-ttu-id="bcb41-404">사용자가 원본 경로를 로컬 OneDrive 폴더로 변경한 경우 연결된 Excel 차트가 Excel 시트로 잘못 변경되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-404">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="bcb41-405">‘Welcome back! 기능으로 인해 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-405">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="bcb41-406">Office에서 중단한 위치 픽업'이(가) PowerPoint 에서 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-406">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="bcb41-407">Visio</span><span class="sxs-lookup"><span data-stu-id="bcb41-407">Visio</span></span>

- <span data-ttu-id="bcb41-408">사용자 지정 Visio 스텐실 및 내장 템플릿 모두에 대해 Office 365용 Visio의 커넥터를 사용하여 직선을 생성할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-408">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="bcb41-409">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-409">Word</span></span>

- <span data-ttu-id="bcb41-410">문서를 HTML 형식으로 저장할 때 긴 링크가 줄바꿈되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-410">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="bcb41-411">확장 목록에 알 수 없는 확장명을 가진 상위 설명에 회신할 경우 같은 확장명을 받는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-411">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="bcb41-412">메시지가 전달 금지로 설정된 Outlook 에 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-412">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="bcb41-413">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-413">Office Suite</span></span>

- <span data-ttu-id="bcb41-414">ADAL이 비활성화되었을 때 사용자가 SPO 목록을 가져올 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-414">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-november-10"></a><span data-ttu-id="bcb41-416">버전 2008: 11월 10일</span><span class="sxs-lookup"><span data-stu-id="bcb41-416">Version 2008: November 10</span></span>
<span data-ttu-id="bcb41-417">*버전 2008(빌드 13127.20760)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-417">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="bcb41-418">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-418">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-420">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-420">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="bcb41-421">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-421">Excel</span></span>

- <span data-ttu-id="bcb41-422">통합 문서를 로드한 후 특정 함수에 잘못된 결과가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-422">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="bcb41-423">XLAM 추가 기능 참조 및 명명된 범위와 관련된 응용 프로그램이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-423">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="bcb41-424">차트 데이터 시트가 활성 시트면 범위에 FormulaR1C1 속성 설정에 매크로를 사용할 때 셀 참조가 부정확한 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-424">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="bcb41-425">"하나 이상의 수식을 계산하는 동안 Excel 리소스를 모두 사용했습니다" 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-425">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="bcb41-426">Office 언어를 스페인어로 설정했을 때 데이터 유효성 검사 목록에 목록의 모든 항목이 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-426">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="bcb41-427">OLAP 피벗 테이블을 새로 고칠 때 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-427">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="bcb41-428">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-428">Outlook</span></span>

- <span data-ttu-id="bcb41-429">이제 다른 Office 애플리케이션 사용을 비활성화할 필요 없이 Outlook용 IRM(정보 권한 관리)를 사용을 비활성화할 수 있도록 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-429">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="bcb41-430">사용자가 대리인에게 편집자 권한을 부여할 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-430">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="bcb41-431">사용자가 검색 결과를 선택하면 응용 프로그램이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-431">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="bcb41-432">그룹 일정에서 검색이 결과를 반환하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-432">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="bcb41-433">대리인이 다른 사서함에서 공유 폴더를 열 때 간헐적으로 오류가 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-433">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="bcb41-434">전자 메일의 제목 줄이 비어있는 경우 일부 자동으로 생성된 전자 메일이 이를 빈 본문으로 보내는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-434">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="bcb41-435">회신하거나 전달할 때 중국어 메시지의 머리글이 깨져 보이는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-435">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="bcb41-436">선택적으로 연결된 환경이 로딩으로부터 웹 추가 기능을 차단하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-436">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="bcb41-437">
  [블로그 게시물](https://developer.microsoft.com/ko-KR/office/blogs/outlook-add-ins-and-optional-connected-experiences/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="bcb41-437">See details in [blog post](https://developer.microsoft.com/ko-KR/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="bcb41-438">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-438">PowerPoint</span></span>

- <span data-ttu-id="bcb41-439">사용자가 다른 슬라이드를 클릭하여 표시할 때까지 Forms 콘텐츠 추가 기능이 삽입 후에 렌더링되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-439">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="bcb41-440">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-440">Office Suite</span></span>

- <span data-ttu-id="bcb41-441">Microsoft 365 끝점 데이터 손실 방지를 사용하여 System Center Configuration Manager 또는 Office 업데이트용 기타 관리 도구를 사용하는 상용 고객을 대상으로 한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-441">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="bcb41-442">Office 추가 기능에 대한 메시징 API가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-442">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2008-october-13"></a><span data-ttu-id="bcb41-444">버전 2008: 10월 13일</span><span class="sxs-lookup"><span data-stu-id="bcb41-444">Version 2008: October 13</span></span>
<span data-ttu-id="bcb41-445">*버전 2008(빌드 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-445">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="bcb41-446">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-446">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-448">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-448">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-449">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-449">Excel</span></span>

- <span data-ttu-id="bcb41-450">'Before' 및 'After' 필터 조건이 바뀐 PivotDateFilter API로 버그를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-450">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="bcb41-451">사용자가 Analysis Services 데이터베이스에 존재하지 않는 값으로 설정하였기 때문에 피벗 테이블 필터를 수정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-451">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="bcb41-452">시트의 첫 행을 고정한 후 빠른 분석을 사용하는 경우 Excel에서 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-452">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="bcb41-453">IFNA()를 사용하여 수식이 포함된 경우 손상된 통합 문서에 대한 경고를 발생시킬 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-453">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="bcb41-454">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-454">Outlook</span></span>

- <span data-ttu-id="bcb41-455">사용자가 코너에서 "X"를 클릭하여 공유 일정을 닫을 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-455">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="bcb41-456">“공유 일정 개선사항 설정” 설정이 기존 공유 일정관리에 적용되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-456">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="bcb41-457">클라우드 첨부 파일을 열 때 열려고 했던 문서 대신 사용자가 안전 링크 페이지에서 오류를 보는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-457">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="bcb41-458">첨부 파일 업로드에 대한 성능 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-458">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="bcb41-459">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-459">PowerPoint</span></span>

- <span data-ttu-id="bcb41-460">이 변경 사항에서는 내보내기 단추를 클릭해도 내보내지 않는 경우 애니메이션 GIF로 내보내기 하는 기능의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-460">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="bcb41-461">제한된 보기에서 PowerPoint 파일을 열 때 IRM 보호를 사용하지 않도록 설정한 문제를 해결하기 위한 보안 수정입니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-461">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="bcb41-462">PowerPoint 앱에서 충돌이 발생하는 작업 설정 대화 상자에서 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-462">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="bcb41-463">Visio</span><span class="sxs-lookup"><span data-stu-id="bcb41-463">Visio</span></span>

- <span data-ttu-id="bcb41-464">텍스트 맞춤에서 실시간 미리 보기가 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-464">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="bcb41-465">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-465">Word</span></span>

- <span data-ttu-id="bcb41-466">사용자가 크기가 큰 특정 전자 메일을 열 때 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-466">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="bcb41-467">일부 사용자가 문서를 여는 경우, 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-467">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="bcb41-468">Word 부팅 시 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-468">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="bcb41-469">스타일 갤러리 대화 상자와 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-469">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="bcb41-470">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-470">Office Suite</span></span>

- <span data-ttu-id="bcb41-471">Office에서 사용자가 잉크젯 프린터로 문서/파일을 인쇄하고 프린터의 잉크가 부족하면, 잉크젯 프린터에 토너가 없더라도 "토너 부족" 또는 "토너 없음" 메시지가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-471">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="bcb41-472">메시지를 변경하여 "토너/잉크 부족" 및 "토너/잉크 없음"으로 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-472">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="bcb41-473">GIF/애니메이션 모델3D를 사용하여 유휴 상태에서 높은 CPU 사용량 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-473">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="bcb41-474">이 변경 사항은 d2d1.dll 로드 실패로 인한 Office 앱을 시작할 때 발생하는 충돌 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-474">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-september-08"></a><span data-ttu-id="bcb41-476">버전 2008: 9월 8일</span><span class="sxs-lookup"><span data-stu-id="bcb41-476">Version 2008: September 08</span></span>
<span data-ttu-id="bcb41-477">*버전 2008(빌드 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-477">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="bcb41-478">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-478">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="bcb41-480">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-480">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="bcb41-481">Access</span><span class="sxs-lookup"><span data-stu-id="bcb41-481">Access</span></span>

- <span data-ttu-id="bcb41-482">**Query Designer, SQL 보기 및 관계 창에서 생산성을 향상시킬 수 있습니다.** 테이블을 마우스 오른쪽 단추로 클릭하여 열고 디자인하고 크기를 조정하고 숨겨보세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-482">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="bcb41-483">SQL 보기에서 텍스트를 검색하고 바꾸세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-483">Search and replace text in SQL View.</span></span> <span data-ttu-id="bcb41-484">관계 창에서 테이블을 여러 개 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-484">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="bcb41-485">**더 적은 수의 클릭으로 테이블 추가:** 작업하는 동안 열려 있는 테이블 추가 작업창을 사용하여 관계와 쿼리에 테이블을 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-485">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="bcb41-486">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-486">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="bcb41-487">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-487">Excel</span></span>

- <span data-ttu-id="bcb41-488">**향상된 지도 차트:** 매핑된 위치에 대한 풍부한 정보를 볼 수 있는 Excel의 지리적 데이터 유형에 통합하여 지도 차트를 더 효율적으로 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-488">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="bcb41-489">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-489">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="bcb41-490">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-490">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="bcb41-491">[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-491">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="bcb41-492">**Excel 내의 Power BI에 있는 데이터셋에서 PivotTables 생성:** 몇 번의 클릭으로 Power BI에 저장된 데이터셋에 연결된 PivotTables를 Excel에서 생성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-492">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="bcb41-493"> 이렇게 하면 PivotTables와 Power BI를 모두 최대한 활용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-493">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="bcb41-494">보안 Power BI 데이터셋에서 PivotTables를 사용하여 데이터를 계산, 요약 및 분석할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-494">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="bcb41-495">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-495">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="bcb41-496">[블로그 게시물](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-496">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="bcb41-497">**자주 사용하는 Excel 함수가 더욱 빨라졌습니다.** SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS 및 MINIFS 함수가 그 어느 때보다 훨씬 빨라졌습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-497">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="bcb41-498">더 빠르게 결과 값을 얻을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-498">Get to the bottom line more quickly.</span></span> <span data-ttu-id="bcb41-499">지금 바로 시도해 보세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-499">Try one now.</span></span>

- <span data-ttu-id="bcb41-500">**Realtimedata(RTD) 개선 사항:** Office 365 버전 2002 월 단위 채널 이상에서 Excel의 RealTimeData(RTD) 함수는 스프레드시트의 데이터를 계산하는 Excel 2010보다 훨씬 빠릅니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-500">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="bcb41-501">기본 메모리 및 데이터 구조의 병목 현상을 제거했으며 사용 가능한 모든 Multithreaded Recalculation(MTR) 스레드에서 계산할 수 있도록 스레드로부터 안전하게 만들었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-501">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="bcb41-502">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-502">Outlook</span></span>

- <span data-ttu-id="bcb41-503">**공유 일정 업데이트 속도 향상:** Office 365의 공유 일정의 경우 Outlook에서 REST API를 사용하여 해당 일정을 업데이트할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-503">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="bcb41-504">미리 보기를 설정하여 공유 일정에 보다 빠르고 신뢰할 수 있는 업데이트를 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-504">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="bcb41-505">**즉시 더 나은 결과 얻기:** 이전보다 더 스마트하고, 빠르고, 안정적이 되도록 검색 환경을 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-505">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="bcb41-506">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-506">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="bcb41-507">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-507">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="bcb41-508">[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-508">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="bcb41-509">**사용자가 소유한 그룹으로 전자 메일 끌기:** 메시지와 대화를 받은 편지함에서 끌어서 이동하고 복사합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-509">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="bcb41-510">끌어 놓은 메시지는 모든 그룹 구성원과 공유됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-510">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="bcb41-511">[블로그 게시물](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-511">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="bcb41-512">**일정 모양 변경:** 일정을 더욱 쉽게 훑어볼 수 있도록 하는 시각적 업데이트를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-512">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="bcb41-513">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-513">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="bcb41-514">[블로그 게시물](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-514">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="bcb41-515">**받은 편지함을 벗어나지 않고 모임 참가:** 온라인 모임에 참가하기 위해 일정으로 전환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-515">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="bcb41-516">일정을 할 일 창에 고정하고 클릭 한 번만으로 모든 모임에 참여하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-516">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="bcb41-517">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-517">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="bcb41-518">**종속적인 Wi-Fi 네트워크에 대한 새로운 경험:** 로그인하기 위해 웹 페이지가 필요한 Wi-Fi 네트워크에 가입한 적이 있습니까?</span><span class="sxs-lookup"><span data-stu-id="bcb41-518">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="bcb41-519">이제 Outlook이 이를 감지하여 연결하는 데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-519">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="bcb41-520">[블로그 게시물](https://insider.office.com/ko-KR/blog/outlook-on-public-wi-fi-networks-just-got-easier)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-520">See details in [blog post](https://insider.office.com/ko-KR/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="bcb41-521">**사람을 검색할 때 전자 메일 제안 받기:** 검색 상자에 사람의 이름을 입력하면 가장 관련성이 높은 전자 메일 메시지가 검색 제안에 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-521">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="bcb41-522">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-522">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="bcb41-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-523">PowerPoint</span></span>

- <span data-ttu-id="bcb41-524">**\@멘션으로 주의 끌기:** 메모에 @멘션을 사용하여 입력이 필요하다는 사실을 동료들에게 알립니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-524">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="bcb41-525">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-525">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="bcb41-526">**향상된 지도 차트:** 매핑된 위치에 대한 풍부한 정보를 볼 수 있는 Excel의 지리적 데이터 유형에 통합하여 지도 차트를 더 효율적으로 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-526">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="bcb41-527">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-527">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="bcb41-528">**GIF 즉시 만들기:** 하나의 슬라이드, 하나의 프레임.</span><span class="sxs-lookup"><span data-stu-id="bcb41-528">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="bcb41-529">PowerPoint에서 쉽게 루핑 GIF를 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-529">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="bcb41-530">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-530">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="bcb41-531">[블로그 게시물](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)에서 세부 정보를 참조하세요</span><span class="sxs-lookup"><span data-stu-id="bcb41-531">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="bcb41-532">**향상된 다이어그램:** 더욱 향상된 커넥터와 원활한 잉크 변환 프로세스를 통해 아이디어를 더욱 확신을 가지고 잉크로 표현할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-532">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="bcb41-533">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-533">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="bcb41-534">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-534">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="bcb41-535">[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-535">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="bcb41-536">**메모:** PowerPoint에서 새 메모 달기 환경을 사용하여 빠르고 쉽게 메모를 검색하고 문서에 메모를 추가할 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="bcb41-536">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="bcb41-537">메모 고정, 해결, 작업, 개선된 멘션 알림 등과 같은 새로운 기능으로 공동 작업 워크플로를 현대화하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-537">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="bcb41-538">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-538">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="bcb41-539">**발표하는 동안 변경 내용 동기화:** 프레젠테이션이 슬라이드 쇼 모드에 있더라도 내용이 변경될 때마다 동기화됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-539">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="bcb41-540">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-540">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="bcb41-541">[블로그 게시물](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-541">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="bcb41-542">**슬라이드에 연결:** 동료에게 슬라이드 모음에 게시하도록 요청하고 도움이 필요한 슬라이드에서 직접 시작해 보세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-542">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="bcb41-543">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-543">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="bcb41-544">[블로그 게시물](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-544">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="bcb41-545">**PowerPoint의 스트림 비디오 성능 향상:** Microsoft Stream 비디오의 재생 성능을 개선하여 비디오 로드 시간을 최소화하고 원활한 보기 환경을 조성했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-545">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="bcb41-546">Microsoft Stream의 회사 비디오를 사용하여 더 나은 프레젠테이션을 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-546">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="bcb41-547">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-547">Word</span></span>

- <span data-ttu-id="bcb41-548">**향상된 지도 차트:** 매핑된 위치에 대한 풍부한 정보를 볼 수 있는 Excel의 지리적 데이터 유형에 통합하여 지도 차트를 더 효율적으로 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-548">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="bcb41-549">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-549">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="bcb41-550">**잉크 올가미:** 그리기 탭의 올가미 도구를 사용하면 잉크로 그린 개체를 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-550">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="bcb41-551">개별 스트로크를 선택하거나 단어 전체를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-551">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="bcb41-552">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-552">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="bcb41-553">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-553">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="bcb41-554">[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-554">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="bcb41-555">**화면 판독기에서 작업 확인:** 작업 확인은 중요한 접근성 요구 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-555">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="bcb41-556">Windows의 새로운 알림 API가 도입됨에 따라 이제 화면 판독기 사용자에게 작업의 성공에 대해 경고 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-556">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="bcb41-557">이제 잘라내기, 복사, 붙여넣기, 굵게, 기울임꼴, 밑줄, 실행 취소, 다시 실행, 자동 수정 및 자동 자본화가 모두 내레이터 사용자에게 Win32 Word로 공지됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-557">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="bcb41-558">이 기능을 사용하려면 창 + Ctrl + Enter 키를 눌러 내레이터를 켭니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-558">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="bcb41-559">[블로그 게시물](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-559">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="bcb41-560">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-560">Office Suite</span></span>

- <span data-ttu-id="bcb41-561">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-561">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-564">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-564">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="bcb41-565">Access</span><span class="sxs-lookup"><span data-stu-id="bcb41-565">Access</span></span>

- <span data-ttu-id="bcb41-566">ID(예: 일련 번호) 필드를 포함하는 연결된 SQL 테이블을 삽입할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-566">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="bcb41-567">쿼리 실행이 예상했던 시간보다 거의 두 배 이상 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-567">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="bcb41-568">앱에서 충돌 없이 날짜/시간 확장 데이터 형식을 코드로 호출할 수 있도록 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-568">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="bcb41-569">최근에 업데이트된 Access 버전으로 되돌리고 DAO/VBA를 사용하여 10진수 데이터 형식을 관리하고 편집할 수 있도록 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-569">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="bcb41-570">이 수정은 특정 쿼리를 실행하려고 하면 이전에 '쿼리가 너무 복잡합니다'라는 오류 메시지가 발생한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-570">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="bcb41-571">Access에서 이 현재 문제를 해결했지만, 이 문제가 지속되지 않도록 추가 인터페이스를 조사할 것입니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-571">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="bcb41-572">팀에서 향후 업데이트를 알려드리겠습니다. 양해해 주셔서 감사합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-572">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="bcb41-573">이 문제가 해결되었습니다. 이제 Office의 Click-to-Run 응용 프로그램 외부에서 ODBC 드라이버를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-573">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="bcb41-574">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-574">Excel</span></span>

- <span data-ttu-id="bcb41-575">읽기 전용 모드였던 통합 문서에 자동 문서 분류가 발생했을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-575">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="bcb41-576">계정에서 로그아웃한 경우 데이터 연결을 만들 때 발생할 수 있는 충돌을 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-576">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="bcb41-577">도표 시트에 PivotTables를 삽입하려고 할 때 Excel이 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-577">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="bcb41-578">LET() 함수를 사용하여 수식이 들어 있는 파일을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-578">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="bcb41-579">서식 복사를 사용하는 경우 특정 상황에서 Excel이 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-579">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="bcb41-580">SharePoint/OneDrive에 저장하는 경우 사용자 지정 리본 탭이 CustomUI XML을 제거하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-580">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="bcb41-581">팀을 통해 Excel 창을 공유할 때 Ctrl+Shift+화살표 키를 사용하여 스크롤한 후 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-581">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="bcb41-582">경우에 따라 동일한 통합 문서 안의 위치에 대한 하이퍼링크를 클릭하면 통합 문서가 숨겨지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-582">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="bcb41-583">파일 경로가 너무 길면 파일을 다시 연 후 외부 링크가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-583">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="bcb41-584">일부 경우에 Application.Evaluate(VBA)가 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-584">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="bcb41-585">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-585">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="bcb41-586">일부 경우에 피벗 테이블을 포함하는 시트를 복사한 후 Excel 작동이 중단되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-586">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="bcb41-587">이는 이전 버전의 Office에서 SQL 데이터 공급자가 만든 연결이 Office 365와 다르게 내부 테이블 속성을 설정하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-587">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="bcb41-588">이로 인해 Office 365를 사용하여 열 때 이전 버전의 Office에서 만든 연결이 있는 파일에 대해 테이블 미리보기/쿼리 편집기 드롭다운을 사용하지 않도록 설정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-588">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="bcb41-589">원본 통합 문서가 닫힌 경우 외부 링크가 채우기에 업데이트되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-589">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="bcb41-590">수동 입력으로 인해 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-590">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="bcb41-591">OneNote</span><span class="sxs-lookup"><span data-stu-id="bcb41-591">OneNote</span></span>

- <span data-ttu-id="bcb41-592">InfoBar를 통해 사용자에게 Microsoft OneNote의 임시 조정에 대해 알리고 전 세계적으로 사용하는 동안 동기화 및 서비스 가용성을 향상시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-592">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="bcb41-593">OneNote 2016에서 동기화 빈도를 일시적으로 조정하여 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-593">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="bcb41-594">리소스 사용률을 줄이기 위해 공동 작성 상태 감지 기능을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-594">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="bcb41-595">OneNote 2016에서 새로운 내장형 첨부 파일의 최대 허용 크기를 50MB로 일시적으로 줄여 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-595">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="bcb41-596">이 제한을 초과하는 파일의 경우 사용자는 파일을 OneDrive에 업로드하고 OneNote에 링크를 삽입할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-596">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="bcb41-597">OneNote 2016에서 앱 내 비디오 녹화를 일시적으로 사용하지 않도록 설정하여 동기화 및 서비스 안정성을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-597">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="bcb41-598">로컬 노트북은 이 조치의 영향을받지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-598">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="bcb41-599">페이지 버전 기록이 생성되는 빈도를 일시적으로 변경하여 동기화 및 서비스 안정성을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-599">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="bcb41-600">휴지통으로 페이지 이동을 일시적으로 비활성화하여 동기화 및 서버 안정성이 향상을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-600">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="bcb41-601">대신 페이지를 삭제하려는 사용자에게는 페이지를 영구적으로 삭제할 것인지를 묻는 대화 상자가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-601">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="bcb41-602">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-602">Outlook</span></span>

- <span data-ttu-id="bcb41-603">프로필에 추가된 보조 계정에서 모임 요청을 만들려고 시도한 사용자에게 전자 메일 주소 대신 빈 보낸 사람: 필드가 표시되지 않는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-603">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="bcb41-604">사용자가 공유 사서함을 추가한 후 공용 폴더에 연결할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-604">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="bcb41-605">일부 상황에서 대리인이 거절했을 때 관리자의 일정에서 모임이 제거되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-605">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="bcb41-606">공유 일정관리 개선 기능의 일부 사용자가 새로 추가된 공유 일정관리를 볼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-606">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="bcb41-607">사용자가 클라우드 첨부 파일을 사용하여 대화형으로 작업하는 경우 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-607">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="bcb41-608">보호되는 컨텍스트에서 보호되지 않은 컨텍스트로 회신 보낸 사람 주소를 전환할 때 CLP 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-608">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="bcb41-609">Outlook에서 M365 Business Plus 계획에 있는 서비스 비용을 지불한 사용자를 위해 Data Loss Protection 정책을 활성화하지 못한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-609">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="bcb41-610">회신/전송 레이블에 대한 clp 감사 이벤트에서 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-610">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="bcb41-611">폴더 창의 너비가 예기치 않게 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-611">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="bcb41-612">끌어서 놓기를 통해 4501년 1월 1일로 설정하여 파일 시스템에 복사한 첨부 파일의 만든 날짜를 사용자에게 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-612">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="bcb41-613">SharePoint 파일에 스마트 링크를 추가할 때 일부 문자 집합 사용자에게 파일 이름을 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-613">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="bcb41-614">Outlook에서 규칙을 업데이트할 때 ‘이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다’라는 메시지가 사용자에게 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-614">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="bcb41-615">Outlook에서 검색 제안을 검색하지 못한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-615">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="bcb41-616">공유 일정의 개선된 사용자가 일정 오류를 볼 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-616">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="bcb41-617">일부 시나리오에서 사용자가 간헐적 중단과 충돌을 겪는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-617">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="bcb41-618">"머리글만 다운로드" 옵션을 선택한 상태에서 POP 계정에서 네 개 이상의 전자 메일을 삭제하면 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-618">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="bcb41-619">공유 폴더 다운로드를 선택하지 않은 경우에 “전달 허용” 옵션이 공유 일정 모임 "응답 옵션"에서 누락되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-619">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="bcb41-620">관리자의 일정에서 기존 일정 약속을 편집할 때 대리인에게 오류가 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-620">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="bcb41-621">타사의 MAPI 응용 프로그램에서 충돌이 발생하게 하였던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-621">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="bcb41-622">Windows 업데이트 후 로컬로 저장된 .msg 혹은 .oft 파일을 열 때 Outlook의 작동이 중단되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-622">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="bcb41-623">일부 Windows 빌드에서 Outlook이 중단되었던문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-623">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="bcb41-624">Windows 10 서버 버전 사용자에게 “바이러스 백신 상태: 올바르지 않음”이라는 경고 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-624">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="bcb41-625">이 Windows 버전에서는 바이러스 백신 감지를 지원하지만 바이러스 백신 프로그램이 올바르게 설치되었음에도 불구하고 해당 프로그램을 찾을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-625">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="bcb41-626">Windows 업데이트 후 로컬로 저장된 .msg 혹은 .oft 파일을 열 때 Outlook의 작동이 중단되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-626">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="bcb41-627">일부 Windows 빌드에서 Outlook이 중단되었던문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-627">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="bcb41-628">Outlook에서 받은 편지함 복구 도구를 실행하라는 메시지를 계속 표시하도록 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-628">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="bcb41-629">마우스에서 "X" 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-629">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="bcb41-630">보안 대화 상자에서 "저장" 옵션을 선택할 때 사용자가 테넌트 외부에서 로컬 컴퓨터에 OneDrive 첨부 파일을 저장할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-630">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="bcb41-631">일정 정리 페이지가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-631">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="bcb41-632">일부 사용자에게 일정 정리 페이지가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-632">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="bcb41-633">개인 정보 검색 시 사용자가 때때로 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-633">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="bcb41-634">이를 통해 받는 사람을 편집할 때 사용자에게 충돌이 발생하는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-634">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="bcb41-635">압축 보기를 사용할 때 사용자에게 이상 현상이 나타나는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-635">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="bcb41-636">아웃룩 사용자가 컴팩트 뷰에서 탐색 관련 문제를 볼 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-636">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="bcb41-637">오른쪽 클릭 상황에 맞는 메뉴가 검색 컨트롤에 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-637">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="bcb41-638">새 전자 메일에 회신하거나 새 전자 메일을 작성할 때 사용자가 다음 오류를 수신한 문제를 해결합니다. "이 웹 페이지의 일부 파일이 예상 위치에 없습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-638">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="bcb41-639">그래도 다운로드하시겠어요?</span><span class="sxs-lookup"><span data-stu-id="bcb41-639">Do you want to download them anyway?</span></span> <span data-ttu-id="bcb41-640">웹 페이지가 신뢰할 수 있는 원본의 웹 페이지인 경우 예를 클릭합니다."</span><span class="sxs-lookup"><span data-stu-id="bcb41-640">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="bcb41-641">Outlook을 종료하는 동안 사용자 작업이 중지되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-641">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="bcb41-642">기능 제안에서 기능을 검색하여 결과를 반환하지 않고 사용자에게 새 기능 아이디어를 제출할 수 있는 옵션이 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-642">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="bcb41-643">인시던트 알림 경고에서 서식 문제가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-643">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="bcb41-644">관리자 알림에서 피드백을 제출할 때 사용자가 충돌을 경험하게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-644">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="bcb41-645">SVG 이미지 복사하여 붙여넣기 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-645">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="bcb41-646">이를 통해 받는 사람을 편집할 때 사용자에게 충돌이 발생하는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-646">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="bcb41-647">SVG 이미지 복사하여 붙여넣기 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-647">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="bcb41-648">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-648">PowerPoint</span></span>

- <span data-ttu-id="bcb41-649">사용자가 파일에 최신 및 기존 주석을 모두 가지고 있을 때 충돌이 발생하여 주석을 업그레이드하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-649">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="bcb41-650">PowerPoint 앱에서 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-650">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="bcb41-651">제안 창에서 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-651">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="bcb41-652">Project</span><span class="sxs-lookup"><span data-stu-id="bcb41-652">Project</span></span>

- <span data-ttu-id="bcb41-653">양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChange 이벤트가 실행되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-653">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="bcb41-654">이전 버전의 Project에서 만든 프로젝트를 저장하면 Project가 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-654">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="bcb41-655">실제 작업 시간을 보호하는 설정이 설정된 경우 사용자가 기간별 초기 작업 시간을 입력할 수 없는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-655">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="bcb41-656">작업이 완료됨으로 표시된 후 작업 완료율이 100%보다 낮은 값으로 잘못 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-656">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="bcb41-657">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-657">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="bcb41-658">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-658">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="bcb41-659">비활성 단추를 통해 작업이 비활성화/활성화된 때를 ProjectBeforeTaskChange 이벤트에서 감지하지 못하는 문제를 해결했습니다. </span><span class="sxs-lookup"><span data-stu-id="bcb41-659">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="bcb41-660">Project Web App에 연결된 Project를 사용하는 경우 소수 구분 기호가 쉼표이면 TaskDependencies Add 메서드가 종속성에 지연 시간을 추가하려할 때 실패하는 문제를 수정습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-660">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="bcb41-661">Project Web App에서 URL이 .com으로 끝나는 경우 Project 데스크톱 클라이언트에서 프로젝트를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-661">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="bcb41-662">여러 종속성이 있는 작업을 붙여 넣는 경우 일부 종속성이 제대로 복사 되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-662">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="bcb41-663">Project에서 SharePoint 문서 라이브러리에 PDF/XPS를 저장 할 수 없는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-663">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="bcb41-664">100% 완료로 표시된 작업이 100% 미만으로 잘못 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-664">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="bcb41-665">프로젝트 요약 작업(프로젝트 시작/작업 필드)이 변경될 때 ProjectBeforeTaskChange 이벤트가 발생하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-665">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="bcb41-666">리소스에 둘 이상의 비용 비율 테이블이 정의된 경우 나머지 비용이 항상 올바르게 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-666">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="bcb41-667">SharePoint 작업 목록에 연결된 프로젝트에 대해 프로젝트 완료 날짜가 업데이트되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-667">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="bcb41-668">자원 배정 대화 상자에서 선택한 작업이 작업 게시판 보기에서 선택 된 작업과 같지 않은 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-668">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="bcb41-669">상태가 좋지 않은 프로젝트를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-669">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="bcb41-670">Skype</span><span class="sxs-lookup"><span data-stu-id="bcb41-670">Skype</span></span>

- <span data-ttu-id="bcb41-671">사용자에게 Teams 전용으로 이동하는 정책이 지정되어도 Skype for Business Outlook 추가 기능을 사용하여 모임을 예약할 수 있었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-671">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="bcb41-672">이 업데이트 후, 클라이언트가 사용자가 Teams 전용임을 나타내는 정책을 읽고 모임 참가 전용 모드로 들어간 후에는 더 이상 Skype for Business 모임을 예약할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-672">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="bcb41-673">또한 Skype for Business Outlook 추가 기능은 Skype for Business 클라이언트가 미팅 참가 모드인 경우 시작하는 동안 자체적으로 활성화되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-673">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="bcb41-674">춤추는 이모티콘 피부색을 중성 색상으로 변경했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-674">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="bcb41-675">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-675">Word</span></span>

- <span data-ttu-id="bcb41-676">URL에 쿼리 구성 요소가 포함되어 있을 때 사용자 정의 문서 배달(aspx)에서 Word 문서를 여는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-676">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="bcb41-677">이 변경사항은 이전 공동 작성 세션 후 Office 응용 프로그램이 자동 저장 오류 상태로 고정될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-677">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="bcb41-678">사용자가 새 전자 메일에 회신하거나 작성할 때 충돌이 발생한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-678">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="bcb41-679">마우스에서 "X" 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-679">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="bcb41-680">SVG 이미지 복사하여 붙여넣기 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-680">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="bcb41-681">사용자가 셰이프의 크기를 조절할 때 콘텐츠가 손실될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-681">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="bcb41-682">표준 스타일을 사용하여 기본 스타일을 업데이트할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-682">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="bcb41-683">AutoExec에서 매크로 AutoOpen가 실행되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-683">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="bcb41-684">SVG 이미지 복사하여 붙여넣기 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-684">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="bcb41-685">앱의 일부 콘텐츠를 끌 때 충돌이 발생할 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-685">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="bcb41-686">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-686">Office Suite</span></span>

- <span data-ttu-id="bcb41-687">이전 웹 서비스 기반 공유 창의 경우 공유 창이 열려 있는 동안 문서를 닫으면 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-687">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="bcb41-688">이제 이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-688">This is now fixed.</span></span>

- <span data-ttu-id="bcb41-689">시간 문제 때문에 Office 파일을 닫을 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-689">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="bcb41-690">검증을 확인했습니다.기본적으로 Bing Addon 설치 검증을 true로 설정하고 MSI 반환 성공을 설치 성공으로 간주하여 설치 실패율 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-690">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="bcb41-691">이전 AppV51의 회귀 분석을 수정하기 위해 새로운 AppV51 드롭을 다시 보고했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-691">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="bcb41-692">기호 링크를 하드 링크하려고 할 때 업데이트 오류가 발생하는 간편 실행 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-692">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="bcb41-693">전체 제품으로 전환이 완료되었음에도 런타임 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-693">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="bcb41-694">서비스가 올바르게 계산 된 제품이 추가 되었는지 확인하여 수정 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-694">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="bcb41-695">새로 추가한 제품(새 구성에도 존재 하는지 확인)을 필터링하고 기존 제품 출시 ID 끝에 추가 했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-695">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="bcb41-696">사용자가 특정 조건에서 UI 요소 또는 콘텐츠가 표시되지 않는 문제를 해결했습니다. 특히 프리젠터 뷰를 드나드는 경우 또는 여러 모니터를 사용하는 경우 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-696">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="bcb41-697">이 변경 사항은 GIF 또는 3D 모델과 같은 애니메이션 콘텐츠를 로드하고 재생할 때 발생할 수 있는 중단 현상을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-697">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="bcb41-698">이 변경 사항은 특정 사용자 설정을 유지하지 않는 그림 압축 대화 상자의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-698">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="bcb41-699">이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. </span><span class="sxs-lookup"><span data-stu-id="bcb41-699">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="bcb41-700">이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-700">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="bcb41-701">이 수정은 액세스의 제한과 동시에 파일을 암호로 보호하는 작업을 할 수 없게 하는 오류를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-701">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="bcb41-702">레지스트리 TabProcGrowth 값이 REG_SZ 유형이면 추가 기능이 활성화될 때 Office 호스트가 Windows에서 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-702">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="bcb41-703">레지스트리 키 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth가 0으로 설정되어있는 동안 추가 기능이 활성화될 때 사무실 호스트가 Windows에서 충돌했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-703">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="bcb41-704">이렇게 변경하면 이 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-704">This change would fix this issue.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-august-11"></a><span data-ttu-id="bcb41-706">버전 2002: 8월 11일</span><span class="sxs-lookup"><span data-stu-id="bcb41-706">Version 2002: August 11</span></span>
<span data-ttu-id="bcb41-707">*버전 2002(빌드 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-707">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="bcb41-708">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-708">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-710">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-710">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-711">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-711">Excel</span></span>

- <span data-ttu-id="bcb41-712">"읽기 전용 권장 사항"으로 열린 파일에 대해 편집으로 전환할 수 없는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="bcb41-712">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="bcb41-713">OneNote</span><span class="sxs-lookup"><span data-stu-id="bcb41-713">OneNote</span></span>

- <span data-ttu-id="bcb41-714">중복 ID 호출을 제거하여 리소스 활용률 감소</span><span class="sxs-lookup"><span data-stu-id="bcb41-714">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="bcb41-715">공동 Authoring 상태 탐지 개선으로 리소스 활용률 감소</span><span class="sxs-lookup"><span data-stu-id="bcb41-715">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="bcb41-716">오류 감지 기능 및 동기화 경험 품질 향상</span><span class="sxs-lookup"><span data-stu-id="bcb41-716">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="bcb41-717">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-717">Outlook</span></span>

- <span data-ttu-id="bcb41-718">일부 테넌트에 대해 Outlook을 시작할 때 중요한 성능 문제를 일으킨 문제 해결</span><span class="sxs-lookup"><span data-stu-id="bcb41-718">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="bcb41-719">Skype</span><span class="sxs-lookup"><span data-stu-id="bcb41-719">Skype</span></span>

- <span data-ttu-id="bcb41-720">32비트 Skype for Business 클라이언트에서 며칠 동안 실행된 후 화면 공유 시작에 실패할 수 있는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="bcb41-720">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="bcb41-721">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-721">Office Suite</span></span>

- <span data-ttu-id="bcb41-722">그룹 정책을 통해 AutoSave가 해제된 경우 사용자가 '사용 가능한 업데이트'를 클릭할 때까지 일부 문서가 열려 있는 최신 서버 내용을 표시하지 않는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="bcb41-722">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-july-14"></a><span data-ttu-id="bcb41-724">버전 2002: 7월 14일</span><span class="sxs-lookup"><span data-stu-id="bcb41-724">Version 2002: July 14</span></span>
<span data-ttu-id="bcb41-725">*버전 2002(빌드 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-725">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="bcb41-726">[여기](./microsoft365-apps-security-updates.md)에 보안 업데이트가 나열됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-726">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-728">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-728">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-729">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-729">Excel</span></span>

- <span data-ttu-id="bcb41-730">로컬 OneDrive 폴더에서 사용할 수 있는 파일을 빠르게 로드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-730">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="bcb41-731">SharePoint/OneDrive에 저장하는 경우 사용자 지정 리본 탭이 CustomUI XML을 제거하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-731">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="bcb41-732">추가 기능이 사용자 지정 순서가 아니라 알파벳 순서로 로드되었기 때문에 ‘이 통합 문서는 다른 통합 문서에서 현재 참조하고 있으며 닫을 수 없습니다’라는 오류 메시지가 나타나는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-732">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="bcb41-733">이미 열려 있는 통합 문서 내의 위치에 대한 하이퍼링크를 클릭하면 통합 문서가 숨겨질 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-733">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="bcb41-734">일부 복사 및 붙여넣기 차트 링크에서 범용 주소가 아닌 매핑된 드라이브 주소를 사용하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-734">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="bcb41-735">병합된 셀이 있는 열을 삭제하는 경우에 발생하던 성능 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-735">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="bcb41-736">인쇄 대화 상자의 프린터 목록에서 프린터 이름이 반복될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-736">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="bcb41-737">정의된 이름의 수식이 여러 개 포함된 워크시트가 파일을 저장할 때 더 오래 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-737">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="bcb41-738">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-738">Outlook</span></span>

- <span data-ttu-id="bcb41-739">해상도가 다른 여러 모니터를 사용할 때 IME(입력 방법 편집기) 창이 IME를 통해 입력되는 기본 텍스트와 겹치는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-739">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="bcb41-740">시간대 정의 변경에 접근할 때 되풀이되는 약속 또는 모임이 잘못된 시간에 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-740">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="bcb41-741">Outlook에서 규칙을 업데이트할 때 ‘이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다’라는 메시지가 사용자에게 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-741">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="bcb41-742">공유 폴더 다운로드를 선택하지 않은 경우에 “전달 허용” 옵션이 공유 일정 모임 "응답 옵션"에서 누락되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-742">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="bcb41-743">가끔 전자 메일 메시지의 범주가 사라지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-743">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="bcb41-744">대리인이 다른 공유 사서함 컴퓨터의 다른 폴더 계층 구조를 볼 수 있었던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-744">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="bcb41-745">관리자의 일정에서 기존 일정 약속을 편집할 때 대리인에게 오류가 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-745">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="bcb41-746">제목을 편집한 후 NDR 메시지 본문이 유니코드에서 ASCII로 변경되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-746">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="bcb41-747">두 개의 추가 기능에서 같은 리본 그룹에 단추를 추가하면 사용자에게 충돌이 발생하던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-747">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="bcb41-748">사용자가 전자 메일을 개인 메일 그룹으로 전송할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-748">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="bcb41-749">테넌트 기본 권한이 "모든 사용자"로 구성된 경우 올바른 테넌트 기본 권한이 있는 전자 메일에 링크를 추가하지 못하던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-749">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="bcb41-750">보안 대화 상자에서 "저장" 옵션을 선택할 때 사용자가 테넌트 외부에서 로컬 컴퓨터에 OneDrive 첨부 파일을 저장할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-750">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="bcb41-751">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-751">Word</span></span>

- <span data-ttu-id="bcb41-752">정책 FileBlick\Word2007Files를 활성화하는 경우 발생하는 공동 작성 관련 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-752">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="bcb41-753">이름이 바뀐 조회 필드를 추가하는 경우 Word QuickPart가 작동하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-753">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="bcb41-754">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-754">Office Suite</span></span>

- <span data-ttu-id="bcb41-755">대규모 PowerPoint 파일에서 공동 작성하는 동안 사용자가 과도한 네트워크 및 CPU 사용률을 경험할 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-755">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="bcb41-756">이전 AppV51의 회귀 분석을 수정하기 위해 새로운 AppV51 드롭을 다시 보고했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-756">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="bcb41-757">레지스트리 TabProcGrowth 값이 REG_SZ 유형이면 추가 기능이 활성화될 때 Office 호스트가 Windows에서 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-757">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-june-09"></a><span data-ttu-id="bcb41-759">버전 2002: 6월 9일</span><span class="sxs-lookup"><span data-stu-id="bcb41-759">Version 2002: June 09</span></span>
<span data-ttu-id="bcb41-760">*버전 2002(빌드 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-760">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="bcb41-761">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-761">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-763">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-763">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-764">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-764">Excel</span></span>

- <span data-ttu-id="bcb41-765">파일 경로가 너무 길면 파일을 다시 연 후 외부 링크가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-765">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="bcb41-766">팀을 통해 Excel 창을 공유할 때 Ctrl+Shift+화살표 키를 사용하여 스크롤한 후 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-766">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="bcb41-767">인쇄할 때 양식 컨트롤에 있는 확인란 크기 조정 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-767">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="bcb41-768">레거시 "공유 통합 문서" 모드를 사용하여 통합 문서의 새 시트에 변경 내용을 나열할 때 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-768">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="bcb41-769">필터링된 목록에 열을 삽입하면 예상보다 시간이 오래 걸립니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-769">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="bcb41-770">공식을 시작하는 @ 기호가 암시적 교차로 연산자로 간주되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-770">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="bcb41-771">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-771">Outlook</span></span>

- <span data-ttu-id="bcb41-772">기본 팀 클라이언트를 통해 직접 팀 미팅에 참여할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-772">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="bcb41-773">Outlook에서 M365 Business Plus 계획에 있는 서비스 비용을 지불한 사용자를 위해 Data Loss Protection 정책을 활성화하지 못한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-773">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="bcb41-774">Gmail에 대한 인증 프롬프트를 완료할 수 없는 경우 사용자가 잘못된 브라우저 에뮬레이션 설정으로 인해 발생한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-774">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="bcb41-775">서버 운영 체제의 Outlook 사용자에게 "바이러스 백신 상태 : 유효하지 않음" 오류가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-775">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="bcb41-776">이 버전의 Windows에서는 바이러스 백신 탐지를 지원하지만 바이러스 백신을 제대로 구성했음에도 불구하고 바이러스 백신을 찾을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-776">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="bcb41-777">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-777">Word</span></span>

- <span data-ttu-id="bcb41-778">빠른 인쇄를 사용하여 인쇄한 후에 편집하려고 할 때 문서의 단어 맞춤이 스크램블되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-778">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="bcb41-779">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-779">Office Suite</span></span>

- <span data-ttu-id="bcb41-780">우리는 2020년 1월 포크의 새 채널 이름으로 백스테이지의 채널 이름을 업데이트하여 이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-780">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="bcb41-781">이 문제를 해결했으며 앞으로 장치가 정책 관리 대상인 경우 DMS Customer API를 호출하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-781">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="bcb41-782">단일 트랜잭션에서 앱을 추가 및 제거할 때 불완전한 제거가 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-782">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="bcb41-783">레지스트리 키 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth가 0으로 설정되어있는 동안 추가 기능이 활성화될 때 사무실 호스트가 Windows에서 충돌했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-783">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="bcb41-784">이렇게 변경하면 이 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-784">This change would fix this issue.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-may-12"></a><span data-ttu-id="bcb41-786">버전 2002: 5월 12일</span><span class="sxs-lookup"><span data-stu-id="bcb41-786">Version 2002: May 12</span></span>
<span data-ttu-id="bcb41-787">*버전 2002 (빌드 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-787">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="bcb41-788">나열된 보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="bcb41-788">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-790">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-790">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="bcb41-791">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-791">Excel</span></span>

- <span data-ttu-id="bcb41-792">다수의 다양한 통합 문서(특히 숨겨진 창)를 참조하는 통합 문서를 열면 예상보다 느리게 열립니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-792">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="bcb41-793">경우에 따라 CSV 파일을 여는 데 소요되는 시간이 예상보다 더 오래 걸렸습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-793">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="bcb41-794">다른 확대/축소 단계를 사용하는 통합 문서 사이를 전환할 때 일부의 경우에 Excel의 작동이 중단될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-794">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="bcb41-795">범위에 값을 입력하는 것이 예상한 것 보다 느려지는 VBA 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-795">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="bcb41-796">색을 기준으로 필터링 된 열에서 복사한 데이터가 가끔 제대로 붙여 넣어지지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-796">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="bcb41-797">일부 경우에 피벗 테이블을 포함하는 시트를 복사한 후 Excel의 작동이 중단되는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-797">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="bcb41-798">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효화 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-798">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="bcb41-799">파일을 저장하고 다시 열 때 차트 축의 "값 교점" 속성이 예기치 않게 변경되는 문제를 해결 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-799">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="bcb41-800">Range.Value와 Range.Value2 (VBA)를 사용하면 수식이 동적 배열로 입력됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-800">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="bcb41-801">OneNote</span><span class="sxs-lookup"><span data-stu-id="bcb41-801">OneNote</span></span>

- <span data-ttu-id="bcb41-802">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 지역화하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-802">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="bcb41-803">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 표시하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-803">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="bcb41-804">OneNote 2016에서 버전 기록 페이지의 수와 동기화 빈도를 일시적으로 줄임으로써 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-804">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="bcb41-805">OneNote 2016에서 일시적으로 휴지통을 비활성화하여 동기화 및 서비스 안정성을 개선시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-805">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="bcb41-806">사용자가 일반적으로 휴지통으로 전송될 데이터를 삭제하려고 하면, 사용자가 데이터를 유지할지 아니면 영구적으로 삭제할지 묻는 메시지가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-806">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="bcb41-807">OneNote 2016에서 동기화 빈도를 일시적으로 조정하여 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-807">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="bcb41-808">OneNote 2016에서 사용자가 해당 페이지로 이동할 때까지 온라인 전자 필기장에 있는 파일 및 이미지의 다운로드를 일시적으로 지연시켜 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-808">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="bcb41-809">OneNote 2016에서 앱 내 비디오 녹화를 일시적으로 사용하지 않도록 설정하여 동기화 및 서비스 안정성을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-809">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="bcb41-810">로컬 노트북은 이 조치의 영향을받지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-810">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="bcb41-811">OneNote 2016에서 새로운 내장 첨부 파일의 최대 허용 크기를 50MB로 일시적으로 줄여 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-811">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="bcb41-812">이 제한을 초과하는 파일의 경우 사용자는 선택적으로 파일을 OneDrive에 업로드하고 OneNote에 링크를 삽입할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-812">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="bcb41-813">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-813">Outlook</span></span>

- <span data-ttu-id="bcb41-814">폴더 창의 너비가 예기치 않게 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-814">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="bcb41-815">Windows 업데이트 후 .msg와 .oft 파일을 여는 경우 작동이 멈추는 현상이 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-815">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="bcb41-816">대규모 HTML 메시지를 전달할 때 사용자에게 잘린 메시지 본문이 표시되던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-816">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="bcb41-817">이 업데이트는 메시지를 보거나 작성할 때 Microsoft Outlook에서 현재 민감도 레이블을 표시하지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-817">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="bcb41-818">사용자가 전자 메일을 개인 메일 그룹으로 보낼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-818">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="bcb41-819">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-819">PowerPoint</span></span>

- <span data-ttu-id="bcb41-820">개선된 설명이 있는 파일의 복사본을 여는 사용자에게 올바른 메시징을 릴레이하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-820">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="bcb41-821">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-821">Word</span></span>

- <span data-ttu-id="bcb41-822">설치된 언어에 따라 Access 및 Publisher가 제대로 부팅되지 않을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-822">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="bcb41-823">편집에 대해 보호된 문서의 비교 기능 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-823">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="bcb41-824">2개의 문서를 하나로 병합할 때 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-824">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="bcb41-825">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-825">Office Suite</span></span>

- <span data-ttu-id="bcb41-826">파일을 클라이언트에 캐시할 때 Project 앱이 네트워크를 차단하지 않도록 하는 문제를 해결하기 위한 수정입니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-826">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="bcb41-827">내부 작업이 실패 시 로깅을 하고 계속 진행하는 대신 예외를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-827">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="bcb41-828">영향을 받은 사용자는 더 이상 업데이트를 받을 수 없도록 차단되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-828">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="bcb41-829">이렇게 변경하면 스케치된 개요가 리본에서 제대로 작동합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-829">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="bcb41-830">특정 프록시 구성을 사용하여 온-프레미스 위치에서 파일을 여는 동안 발생하는 문제를 수정하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-830">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="bcb41-831">이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-831">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="bcb41-832">이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. </span><span class="sxs-lookup"><span data-stu-id="bcb41-832">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="bcb41-833">이 업데이트는 레이블 정책에서 머리글/바닥글 또는 워터 마크를 적용한 경우 레이블을 변경하거나 제거하여 민감도 레이블을 적용하는 동안 삽입된 255자를 초과하는 텍스트를 차후에 식별하고 제거할 수 없는 Microsoft Word에서의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-833">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="bcb41-834">Office 전달 세션 중에 충돌을 없애고 사용자 환경의 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-834">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="bcb41-835">이 버그는 ECS(향상된 구성 서비스) URL 끝점을 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-835">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="bcb41-836">이 최신 끝점의 호출은 ECS에서 가져오기의 성공률이 높습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-836">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-april-14"></a><span data-ttu-id="bcb41-838">버전 2002: 4월 14일</span><span class="sxs-lookup"><span data-stu-id="bcb41-838">Version 2002: April 14</span></span>
<span data-ttu-id="bcb41-839">*버전 2002 (빌드 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-839">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="bcb41-840">나열된 보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="bcb41-840">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="bcb41-841">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-841">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-842">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-842">Excel</span></span>

- <span data-ttu-id="bcb41-843">**다중값을 반환하는 공식을 입력:** 다중값을 반환하는 공식을 신속히 입력하면 자동으로 인접한 셀들로 입력됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-843">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="bcb41-844">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-844">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="bcb41-845">**유용한 함수 6개:** 스프레드시트를 더욱 유용하게 사용할 수 있는 함수 6개(FILTER, SORT, SORTBY, UNIQUE, SEQUENCE 및 RANDARRAY)가 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-845">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="bcb41-846">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-846">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="bcb41-847">**왼쪽을 보고, 오른쪽을 보십시오… XLOOKUP이 여기 있습니다!** 행별로 XLOOKUP을 사용하여 테이블 또는 범위에서 필요한 것을 모두 찾으십시오.</span><span class="sxs-lookup"><span data-stu-id="bcb41-847">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="bcb41-848">
  [자세한 정보](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="bcb41-848">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-850">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-850">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-851">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-851">Excel</span></span>

- <span data-ttu-id="bcb41-852">특정 경우에 Word나 PowerPoint에서 포함된 통합 문서를 다시 열면 Excel이 중단됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-852">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="bcb41-853">CSV 파일로 저장하면 Excel에서 모든 열이 하나의 열로 병합되는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-853">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="bcb41-854">보호된 시트의 범위에서 Range.ClearContents를 사용하면 예상보다 시간이 오래 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-854">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="bcb41-855">인쇄 미리 보기로 표시되는 경우 양식 컨트롤에서 텍스트의 크기 조정 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-855">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="bcb41-856">리본 메뉴와 상호 작용하는 VBA 매크로는 ScreenUpdating을 예기치 않게 True로 설정한 상태에서 실행될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-856">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="bcb41-857">원본 통합 문서가 닫힌 경우 외부 링크가 채우기(아래로 채우기, 가로 채우기 등)에 업데이트되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-857">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="bcb41-858">경우에 따라 VBA의 Application.Evaluate를 사용해도 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-858">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="bcb41-859">서식 파일에서 차트를 만들 때 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-859">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="bcb41-860">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-860">Outlook</span></span>

- <span data-ttu-id="bcb41-861">일부 시나리오에서 그룹 헤더가 예기치 않게 확장되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-861">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="bcb41-862">특정 검색 결과를 선택할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-862">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="bcb41-863">마우스의 X 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-863">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="bcb41-864">첨부 파일 도구에서 클라우드에 저장 단추가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-864">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="bcb41-865">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-865">PowerPoint</span></span>

- <span data-ttu-id="bcb41-866">복사-붙여넣기 시나리오 개선: 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-866">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="bcb41-867">Project</span><span class="sxs-lookup"><span data-stu-id="bcb41-867">Project</span></span>

- <span data-ttu-id="bcb41-868">이전 버전의 Project에서 만든 프로젝트를 저장하면 Project가 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-868">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="bcb41-869">비활성 단추를 통해 작업이 비활성화/활성화된 때를 ProjectBeforeTaskChange 이벤트에서 감지하지 못하는 문제를 해결했습니다. </span><span class="sxs-lookup"><span data-stu-id="bcb41-869">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="bcb41-870">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-870">Word</span></span>

- <span data-ttu-id="bcb41-871">마우스의 X 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-871">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="bcb41-872">표에 텍스트 맞춤 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-872">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="bcb41-873">삽입 가로선 길이가 더 짧지 않고 가운데 맞춤되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-873">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-march-10"></a><span data-ttu-id="bcb41-875">버전 2002: 3월 10일</span><span class="sxs-lookup"><span data-stu-id="bcb41-875">Version 2002: March 10</span></span>
<span data-ttu-id="bcb41-876">*버전 2002 (빌드 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-876">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="bcb41-877">나열된 보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="bcb41-877">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="bcb41-879">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-879">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="bcb41-880">Access</span><span class="sxs-lookup"><span data-stu-id="bcb41-880">Access</span></span>

- <span data-ttu-id="bcb41-881">**연결된 표 빠르게 찾기:** 새 검색 상자를 사용하여 연결된 표를 간편하게 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-881">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="bcb41-882">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-882">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="bcb41-883">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-883">Excel</span></span>

- <span data-ttu-id="bcb41-884">**\@멘션으로 주의 끌기:** 메모에 @멘션을 사용하여 입력이 필요하다는 사실을 동료들에게 알립니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-884">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="bcb41-885">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-885">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="bcb41-886">**원하는 내용 찾기: 명령, 사용자, 파일, 사진, 웹 문서 등을 검색**</span><span class="sxs-lookup"><span data-stu-id="bcb41-886">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="bcb41-887">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-887">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="bcb41-888">**그림 스케치:** 통합 문서에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-888">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="bcb41-889">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-889">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="bcb41-890">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-890">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="bcb41-891">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-891">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="bcb41-892">**남은 작업에 중점:** 설명을 축소하고 열린 항목을 강조하려면 해결을 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-892">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="bcb41-893">**더 많은 접근 가능한 PDF 만들기:** PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-893">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="bcb41-894">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-894">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="bcb41-895">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-895">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="bcb41-896">**데이터 시각화 도우미 추가 기능:** Excel에서 빠르게 Visio 플로차트를 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-896">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="bcb41-897">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-897">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="bcb41-898">**읽고 즉시 회신:** 통합 문서를 열지 않고 전자 메일에서 바로 메모와 멘션에 회신합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-898">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="bcb41-899">**통합 문서에 대 한 통계를 가져오기:** 통합 문서 통계는 통합 문서의 내용을 간략하게 파악하는 데 도움이 되는 통합 문서의 내용에 대한 개요를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-899">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="bcb41-900">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-900">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="bcb41-901">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-901">Find them at Insert > Icons.</span></span> [<span data-ttu-id="bcb41-902">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-902">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="bcb41-903">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-903">Outlook</span></span>

- <span data-ttu-id="bcb41-904">**LinkedIn 네트워크를 Outlook과 연결하기:** Microsoft 계정을 사용하여 LinkedIn 계정에 안전하게 연결하고 Windows용 Outlook의 명함에 있는 LinkedIn 프로필에서 정보를 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-904">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="bcb41-905">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-905">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="bcb41-p176">**모든 암호화 옵션의 일원화:** 전자 메일 메시지 보호 방법을 선택하려면 옵션 > 암호화로 이동합니다. [자세히 알아보기](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="bcb41-p176">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="bcb41-908">**Outlook의 링크 삽입 메뉴는 테넌트 관리자가 정의한 사용 권한을 포함하는 링크를 삽입합니다:** Outlook의 가장 최근 삽입한 링크에 있는 링크는 이미 사용 권한이 있었던 사용자들에게만 작동했었던 링크를 삽입합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-908">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="bcb41-909">이는 종종 사용자들 간에 문서에 대한 액세스 권한을 요청하는 전자 메일을 주고 받게 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-909">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="bcb41-910">이 환경을 업데이트하여 이제 테넌트 관리자가 설정한 기본 권한으로 링크가 삽입되었습니다. MSIT의 경우 "조직은 편집할 수 있음"이므로 이 방법을 통해 공유된 링크를 받는 모든 내부 사용자가 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-910">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="bcb41-911">**철자 또는 오타로 검색:** Outlook은 철자가 틀린 경우에도 검색 내용을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-911">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="bcb41-912">**피싱 메일을 쉽게 탐지:** 스팸과 피싱 메시지는 형태와 느낌이 다르기 때문에 받은 편지함에서 쉽게 식별하고 제거할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-912">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="bcb41-913">**공격에 대비한 고급 보호:** Office 365 Advanced Threat Protection을 사용하면 전자 메일 제목, 첨부된 메시지, 서명된 메시지, 네트워크 경로 등의 하이퍼 링크를 통해 공격으로부터 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-913">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="bcb41-914">**그리기 기능:** 그림 위쪽에서 낙서를 하거나 그리기 캔버스를 추가하여 잉크로 내 생각을 전달할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-914">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="bcb41-915">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-915">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="bcb41-916">**검색 결과에서 관련 메시지 확인:** Outlook은 검색 용어를 분석하고 검색 결과 상단에 가장 관련성이 높은 전자 메일 메시지를 보여줍니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-916">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="bcb41-917">또한 상위 결과 섹션에 날짜별로 정렬된 모든 결과도 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-917">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="bcb41-918">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-918">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="bcb41-919">**위치 제안 받기:** 약속 및 모임을 예약할 때 위치 필드에 입력을 시작하면 Outlook에 회의실, 주소 및 기타 최근 장소가 제안됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-919">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="bcb41-920">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-920">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="bcb41-921">**화면에 더 많은 메시지 맞춤:** 메시지 사이의 간격을 조정하려면 보기 > 더 좁은 간격 사용을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-921">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="bcb41-922">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-922">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="bcb41-923">**다른 조명에서 메시지 보기:** 태양/달 단추를 사용하여 읽기 창에서 밝은 배경과 어두운 배경 간에 전환을 합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-923">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="bcb41-924">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-924">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="bcb41-925">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-925">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="bcb41-926">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-926">Find them at Insert > Icons.</span></span> [<span data-ttu-id="bcb41-927">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-927">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="bcb41-928">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-928">PowerPoint</span></span>

- <span data-ttu-id="bcb41-929">**PowerPoint에서 빠르게 실시간 공동 작업 수행:** PowerPoint에서 빠르게 실시간 공동 작업 수행</span><span class="sxs-lookup"><span data-stu-id="bcb41-929">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="bcb41-930">**새로운 교정 도구:** 단어를 틀릴까봐 스트레스 받지 마세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-930">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="bcb41-931">이제 PowerPoint는 문법 및 맞춤법 제안 사항을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-931">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="bcb41-932">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-932">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="bcb41-933">**라이브 캡션 및 자막:** 발표자의 단어가 화면에 캡션으로 자동으로 표시되고 원하는 언어로 자막으로 번역됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-933">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="bcb41-934">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-934">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="bcb41-p186">**수식만 쓰세요, 서식은 PowerPoint가 알아서 지정해 드립니다:** 손글씨로 쓴 수학 식을 표준 문자로 변경해 드리겠습니다. 잉크 수식 변환을 선택하고 필기를 선택하기만 하면 됩니다. [자세히 알아보기](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="bcb41-p186">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="bcb41-938">**원하는 내용 찾기:** 검색 창을 사용하여 텍스트, 명령, 도움말 등을 찾으세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-938">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="bcb41-939">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-939">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="bcb41-940">**누락된 슬라이드 제목 찾기 및 수정:** 슬라이드 제목은 발표에 호소력을 더해 다양한 수준의 사용자가 슬라이드를 이해하기 쉽도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-940">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="bcb41-941">접근성 검사를 통해 제목이 누락되는 위치를 표시하여 신속하게 제목을 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-941">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="bcb41-942">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-942">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="bcb41-943">**그림 스케치:** 프레젠테이션에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-943">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="bcb41-944">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-944">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="bcb41-945">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-945">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="bcb41-946">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-946">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="bcb41-947">**그림을 SVG로 저장:** 이미지 품질이 손실되지 않도록 크기를 조정할 수 있는 스케일 가능한 벡터 그래픽으로 차트, 도형 또는 기타 그림을 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-947">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="bcb41-948">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-948">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="bcb41-949">**슬라이드 번호를 유인물에 인쇄:** 슬라이드 번호가 유인물에 자동으로 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-949">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="bcb41-950">계속 사용 및 해제 여부를 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-950">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="bcb41-951">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-951">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="bcb41-952">**잉크 스턴트 재생:** 슬라이드에 잉크를 쓸 때 슬라이드 쇼 중에 잉크의 실제 그리기를 재생하기 위한 재생 애니메이션을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-952">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="bcb41-953">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-953">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="bcb41-954">**더 많은 접근 가능한 PDF 만들기:** PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-954">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="bcb41-955">**모든 사용자를 위한 프레젠테이션 최적화:** 접근성 검사기는 기능은 스크린 리더를 염두에 두고 슬라이드에서 개체를 정렬하는데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-955">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="bcb41-956">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-956">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="bcb41-957">**더욱 안전한 비디오 환경:** 보안 강화는 더욱 안전한 온라인 비디오 환경을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-957">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="bcb41-958">**재개발 대신 재사용:** 사용자가 작성했거나 다른 사용자가 공유하도록 한 슬라이드를 다시 사용하여 시간을 절약하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-958">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="bcb41-959">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-959">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="bcb41-960">**Office 365용 PowerPoint에서 필기 잉크를 도형, 텍스트 또는 수학으로 변경:** 몇 번의 스트로크만으로 자유형 잉크를 Office 도형, 텍스트 또는 수식으로 변경합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-960">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="bcb41-961">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-961">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="bcb41-962">**멋진 슬라이드 만들기:** 잉크를 표준 도형 및 텍스트로 변환한 후, PowerPoint Designer에서 스마트한 슬라이드 디자인 아이디어를 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-962">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="bcb41-963">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-963">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="bcb41-964">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-964">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="bcb41-965">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-965">Find them at Insert > Icons.</span></span> [<span data-ttu-id="bcb41-966">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-966">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="bcb41-967">Visio</span><span class="sxs-lookup"><span data-stu-id="bcb41-967">Visio</span></span>

- <span data-ttu-id="bcb41-968">**범죄 현장 재방문:** 범죄 현장 조사 서식 파일에서 새 증빙, 실내 및 실외 스텐실을 사용하여 범죄 현장에 대한 세부 정보를 다시 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-968">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="bcb41-969">**Excel에서 세련된 Visio 다이어그램 만들기:** 워크시트에 데이터를 입력하여 순서도 또는 조직도를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-969">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="bcb41-970">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-970">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="bcb41-971">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-971">Word</span></span>

- <span data-ttu-id="bcb41-972">**이력서 편집기와 LinkedIn Resume 도우미의 만남:** 이력서 편집기는 이력서에 특별히 맞춤화된 문법 및 스타일 검사를 제공하여 글을 보다 정확하고 전문적으로 만들어 줍니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-972">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="bcb41-973">**3D 개체의 병합으로 발생하는 문서 손상 문제 해결:** 3D 개체의 병합으로 발생하는 문서 손상 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-973">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="bcb41-974">**원하는 내용 찾기:** 검색 창을 사용하여 텍스트, 명령, 도움말 등을 찾으세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-974">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="bcb41-975">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-975">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="bcb41-976">**생생한 색으로 공동 작업:** 메모와 변경 사항은 기여자에 의해 색상으로 구분되므로 공동 작업자 중 개개인을 쉽게 구분할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-976">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="bcb41-977">**공동으로 매크로 사용 문서 편집 공동:** 비즈니스용 OneDrive에서 .docm 파일을 저장하고 공동 작업자와 실시간으로 편집합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-977">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="bcb41-978">**공동 작성 기능 개선**: 문서를 공동 작성 시 변경 내용 추적 기능을 사용하여 Word의 성능을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-978">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="bcb41-979">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-979">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="bcb41-980">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-980">Find them at Insert > Icons.</span></span> [<span data-ttu-id="bcb41-981">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-981">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="bcb41-982">**다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다.** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-982">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="bcb41-983">**그림 스케치:** 문서에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-983">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="bcb41-984">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-984">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="bcb41-985">**정확하게 지우기:** 두 개의 지우개 크기 중에 선택하고 작은 잉킹 결함을 수정하세요.</span><span class="sxs-lookup"><span data-stu-id="bcb41-985">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="bcb41-986">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-986">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="bcb41-987">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-987">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="bcb41-988">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-988">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="bcb41-989">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-989">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="bcb41-990">**공동 작성 향상** : 공동 작성 시 신뢰도가 향상될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-990">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="bcb41-991">**더 많은 접근 가능한 PDF 만들기:** PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-991">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="bcb41-992">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-992">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="bcb41-993">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-993">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="bcb41-994">**더욱 안전한 비디오 환경:** 보안 강화는 더욱 안전한 온라인 비디오 환경을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-994">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="bcb41-995">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="bcb41-995">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-998">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-998">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="bcb41-999">액세스</span><span class="sxs-lookup"><span data-stu-id="bcb41-999">Access</span></span>

- <span data-ttu-id="bcb41-1000">이 업데이트는 업데이트 쿼리가 실행되거나 UPDATE 문이 SQL에 사용될 때 “쿼리가 손상되었습니다” 오류를 일으킬 수 있는 Microsoft Access의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1000">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="bcb41-1001">이 업데이트는 Microsoft Access에서 연결된 SQL Server 테이블의 ID 열이 식별되지 않아서 행이 올바르지 않게 삭제된 것으로 보고되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1001">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="bcb41-1002">이 업데이트는 ADODB 사용시 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1002">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="bcb41-1003">VB 코드의 레코더 개체에서 오류가 잘못 보고될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1003">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="bcb41-1004">데이터베이스 내에서 더 이상 액세스 템플릿으로 인해 첨부 열이 실패하지 않아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1004">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="bcb41-1005">템플릿을 인스턴스화 한 후에는 데이터베이스에 첨부 파일 필드를 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1005">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="bcb41-1006">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-1006">Excel</span></span>

- <span data-ttu-id="bcb41-1007">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1007">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="bcb41-1008">이 변경 사항은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1008">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="bcb41-1009">spilling 배열이 있는 셀이 있는 열로 텍스트를 변환할 때 일부 사용자에게 충돌이 발생하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1009">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="bcb41-1010">이 업데이트는 수식 입력줄에서 예상한 것과 다른 글꼴로 텍스트를 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1010">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="bcb41-1011">일부 현지의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1011">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="bcb41-1012">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1012">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="bcb41-1013">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1013">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="bcb41-1014">스크롤 후 셀을 선택하면 잘못된 셀이 선택되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1014">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="bcb41-1015">신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 오류를 발생시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1015">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="bcb41-1016">일부 현지화의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1016">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="bcb41-1017">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1017">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="bcb41-1018">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1018">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="bcb41-1019">일부 사용자가 경험할 수 있는 OLE (포함 및 연결된 개체) 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1019">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="bcb41-1020">피벗 차트의 오른쪽 클릭 메뉴를 수정하여 세부 정보를 표시하는 옵션을 사용할 수 있도록 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1020">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="bcb41-1021">통합 문서가 열려있지 않은 상태에서 최근 파일을 검색할 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1021">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="bcb41-1022">통합 문서에 외부 링크가 있는 경우 일부 사용자가 여러 개의 팝업 창을 경험하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1022">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="bcb41-1023">상황에 맞는 메뉴에서 주석 명령이 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1023">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="bcb41-1024">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1024">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="bcb41-1025">CUBEVALUE 함수가 때때로 잘못된 결과를 반환하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1025">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="bcb41-1026">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-1026">Outlook</span></span>

- <span data-ttu-id="bcb41-1027">피드백 검색 환경을 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1027">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="bcb41-1028">사용자가 클라우드 설정을 검색할 때 Outlook에서 사용자가 중단되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1028">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="bcb41-1029">검색 상자가 높은 dpi 모드로 잘못 정렬되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1029">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="bcb41-1030">Outlook 프로세스에서 메모리 누수가 사용자에게 관찰되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1030">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="bcb41-1031">사용자가 일부 상황에서 표시된 SMTP 주소와 일치하지 않는 주소로 보낸 전자 메일을 보게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1031">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="bcb41-1032">이 변경으로 메시지 헤더에서 여러 줄 제목을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1032">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="bcb41-1033">파일을 WebDAV 위치에 저장하지 못하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1033">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="bcb41-1034">SMIME 알고리즘 선택 관련 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1034">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="bcb41-1035">타사 응용 프로그램에서 전자 메일을 보낼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1035">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="bcb41-1036">사용자가 계정 만들기 컨텍스트에서 지원 센터에 문의하려고 할 때 사용자에게 "확인" 버튼이 있는 빈 메시지 상자가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1036">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="bcb41-1037">사용자가 프로필을 만드는 동안 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1037">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="bcb41-1038">동기화 슬라이더가 더 작은 설정으로 설정되어 있어도 Outlook이 예기치 않게 모든 메일을 동기화시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1038">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="bcb41-1039">검은색 테마를 가진 사용자가 흰색 배경에 흰색 텍스트를 표시하는 "시작" 드롭다운을 보게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1039">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="bcb41-1040">계정 설정을 취소할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1040">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="bcb41-1041">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1041">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="bcb41-1042">일부 시나리오에서 플래그가 지정된 항목 강조 표시를 사용하지 않도록 설정하는 옵션이 무시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1042">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="bcb41-1043">규칙 대화 상자를 열 때 "이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다." 프롬프트가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1043">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="bcb41-1044">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1044">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="bcb41-1045">매우 긴 Outlook 세션에서 메모리 누수를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1045">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="bcb41-1046">여러 창에서 동일한 항목을 볼 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1046">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="bcb41-1047">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 현저하게 지연이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1047">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="bcb41-1048">사용자가 되풀이되는 일정 항목의 일부 인스턴스를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1048">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="bcb41-1049">Exchange 2010 서버에 사서함이있는 사용자가 일정 항목에 첨부 파일을 추가할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1049">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="bcb41-1050">디지털 서명된 메시지에 회신 할 때 사용자에게 문제가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1050">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="bcb41-1051">모임의 위치 필드가 예상치 않게 업데이트되는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1051">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="bcb41-1052">모임 위치 필드의 쉼표가 세미콜론으로 바뀌는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1052">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="bcb41-1053">모임을 지운 후 예기치 않게 모임의 위치를 모임을 다시 추가하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1053">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="bcb41-1054">브라질 시간대로 설정된 회의 및 약속과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1054">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="bcb41-1055">검은색 테마를 가진 사용자가 흰색 배경에 흰색 텍스트를 표시하는 "시작" 드롭다운을 보게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1055">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="bcb41-1056">이를 통해 첨부 파일 차단 논리를 업데이트하여 Outlook에서 Python 첨부 파일도 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1056">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="bcb41-1057">웹 추가 기능이 디지털 권한 관리 메시지에 액세스하게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1057">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="bcb41-1058">사용자가 프로필을 만드는 동안 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1058">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="bcb41-1059">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1059">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="bcb41-1060">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-1060">PowerPoint</span></span>

- <span data-ttu-id="bcb41-1061">Shape 관련 문제를 해결했습니다. 붙여넣기 방법: 사용자가 Shape를 사용하여 셰이프를 복사하고 붙여 넣는 경우. 붙여넣기 방법. 선택 대상이 붙여넣기한 셰이프로 변경됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1061">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="bcb41-1062">레거시 PPT 주석에서 상황에 맞는 메뉴를 사용할 때 충돌을 일으킬 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1062">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="bcb41-1063">Project</span><span class="sxs-lookup"><span data-stu-id="bcb41-1063">Project</span></span>

- <span data-ttu-id="bcb41-1064">읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1064">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="bcb41-1065">고정된 기간 유형의 100% 작업이 100% 완료 미만으로 잘못 계산할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1065">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="bcb41-1066">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1066">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="bcb41-1067">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1067">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="bcb41-1068">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-1068">Word</span></span>

- <span data-ttu-id="bcb41-1069">일부 경우에 기존 파일을 저장하면 항상 다른 이름으로 저장 대화 상자가 나타나고 파일이 실제로는 저장되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1069">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="bcb41-1070">문서 블록 이끌이가 “사용자가 스타일, 문서 블록을 수정했습니다.”라는 잘못된 알림을 표시할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1070">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="bcb41-1071">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-1071">Office Suite</span></span>

- <span data-ttu-id="bcb41-1072">이 변경 사항은 마커가 포함된 일부 분산형 차트의 느린 렌더링 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1072">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="bcb41-1073">이 변경 사항은 인텔 통합 GPU를 활용하는 그래픽 어댑터에 보고된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1073">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="bcb41-1074">상대적인 마감일이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정 버그를 수정했습니다. 이 픽스는 후속 업데이트에 대한 상대적인 마감일도 사용할 수 있도록 해줍니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1074">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="bcb41-1075">Office 업데이트에서 로컬 또는 네트워크 공유 또는 Configuration Manager에서 제공하는 위치와 같은 의도된 원본 대신 Office CDN에서 파일을 예기치 않게 다운로드했을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1075">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="bcb41-1076">동일한 SharePoint 라이브러리의 Word/Excel/PowerPoint에서 여러 문서를 열 때 첫 번째로 열린 문서만 정책 준수에 대한 검사가 이뤄지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1076">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-february-11"></a><span data-ttu-id="bcb41-1078">버전 1908: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="bcb41-1078">Version 1908: February 11</span></span>
<span data-ttu-id="bcb41-1079">*버전 1908 (빌드 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-1079">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="bcb41-1080">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="bcb41-1080">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-1082">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-1082">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-1083">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-1083">Excel</span></span>

- <span data-ttu-id="bcb41-1084">이 업데이트는 VBA를 사용하여 차트의 머리글/바닥글에 이미지를 추가할 때마다 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1084">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="bcb41-1085">인쇄 미리보기 또는 인쇄 시 그룹 상자 컨트롤의 테두리가 보이지 않던 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1085">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="bcb41-1086">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1086">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="bcb41-1087">차트가 포함된 통합 문서를 저장할 때 차트 머리글의 이미지 파일 크기가 커지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1087">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="bcb41-1088">선택 범위를 상호 참조 도서와 동기화하여 상호 참조 도서에서 DBCS 문자가 손상되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1088">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="bcb41-1089">자동 맞춤을 사용하여 행 높이를 조정할 때 확인란 컨트롤이 축소될 수있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1089">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="bcb41-1090">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-1090">Outlook</span></span>

- <span data-ttu-id="bcb41-1091">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1091">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="bcb41-1092">충돌 메시지를 처리할 때 사용자에게 동기화 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1092">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="bcb41-1093">Outlook을 시작할 때 사용자가 프로필을 로딩할 때 화면이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1093">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="bcb41-1094">보기를 변경할 때 사용자에게 간헐적인 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1094">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="bcb41-1095">Citrix 환경에서 30개 이상의 캘린더를 볼 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1095">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="bcb41-1096">[여기](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)에는 이전 버전에 대해 문서화된 개별 KB가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1096">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="bcb41-1097">사용자가 공유 일정 폴더를 OST와 동기화하는 데 문제가있어 이러한 폴더와 상호 작용할 때 권한 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1097">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="bcb41-1098">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-1098">PowerPoint</span></span>

- <span data-ttu-id="bcb41-1099">복사-붙여넣기 시나리오 개선 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1099">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="bcb41-1100">공동 작업 사용자 간에 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1100">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="bcb41-1101">증분 방식으로 열린 파일에 둘 이상의 포함된 미디어 스트림이 있는 슬라이드가 포함되어 있을 때 발생할 수있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1101">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="bcb41-1102">PowerPoint를 처음 시작할 때 신뢰할 수 없는 추가 기능에 대해 보안 경고 메시지 표시줄이 나타나지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1102">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="bcb41-1103">Project</span><span class="sxs-lookup"><span data-stu-id="bcb41-1103">Project</span></span>

- <span data-ttu-id="bcb41-1104">기본 일정이 변경될 때 리소스 일정이 업데이트되지 않아 작업표와 프로젝트 계획 간에 실제 작업이 다를 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1104">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="bcb41-1105">Word</span><span class="sxs-lookup"><span data-stu-id="bcb41-1105">Word</span></span>

- <span data-ttu-id="bcb41-1106">더 이상 사용되지 않는 API에서 이동하여 Word의 충돌 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1106">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="bcb41-1107">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-1107">Office Suite</span></span>

- <span data-ttu-id="bcb41-1108">이 변경은 손상된 파일을 연 후 이미지를 올바르게 렌더링하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1108">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-january-14"></a><span data-ttu-id="bcb41-1110">버전 1908: 1월 14일</span><span class="sxs-lookup"><span data-stu-id="bcb41-1110">Version 1908: January 14</span></span>
<span data-ttu-id="bcb41-1111">*버전 1908(빌드 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="bcb41-1111">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="bcb41-1112">나열된 보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="bcb41-1112">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="bcb41-1114">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="bcb41-1114">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="bcb41-1115">Excel</span><span class="sxs-lookup"><span data-stu-id="bcb41-1115">Excel</span></span>

- <span data-ttu-id="bcb41-1116">문서 타이틀에 대한 네덜란드어 단축키가 Alt-G로 변경되었습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1116">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="bcb41-1117">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1117">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="bcb41-1118">추가 기능을 통해 연 WPF(Windows Presentation Foundation) 양식의 콤보 상자에서 항목을 선택할 수 없는 문제가 발생했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1118">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="bcb41-1119">Outlook</span><span class="sxs-lookup"><span data-stu-id="bcb41-1119">Outlook</span></span>

- <span data-ttu-id="bcb41-1120">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 현저하게 지연이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1120">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="bcb41-1121">대체 보낸 사람을 사용할 때 정책 팁이 표시되지 않게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1121">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="bcb41-1122">사용자가 현재 상태 정보를 업데이트할 때 일시적으로 작동이 중지되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1122">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="bcb41-1123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="bcb41-1123">PowerPoint</span></span>

- <span data-ttu-id="bcb41-1124">한 프레젠테이션에서 다른 프레젠테이션으로 슬라이드를 복사하여 중복하는 경우 마스터가 복제되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1124">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="bcb41-1125">최신 메모가 포함된 파일에는 지원되지 않는 버전에서 열었을 경우 노란색 경고가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1125">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="bcb41-1126">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="bcb41-1126">Office Suite</span></span>

- <span data-ttu-id="bcb41-1127">Office 업데이트 메시지가 다른 언어로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1127">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="bcb41-1128">앞으로 Office 업데이트 메시지 언어가 Windows 표시 언어와 정확하게 일치할 것입니다.  </span><span class="sxs-lookup"><span data-stu-id="bcb41-1128">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="bcb41-1129">사용자가 관리자가 아니거나 시스템 계정에 네트워크 연결이 없는 경우에 업데이트가 적용되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1129">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

> [!NOTE]
> <span data-ttu-id="bcb41-1131">Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="bcb41-1131">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (관리 센터 메타데이터 콘텐츠를 수정하지 마세요. 시작)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20294|version-2102-march-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|버전 2002년 7월 14일|)
[//]: # (관리 센터 메타데이터 콘텐츠를 수정하지 마세요. 끝)
