---
title: 2021년 반기 기업 채널(미리 보기) 릴리스의 릴리스 정보
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 2021년 Microsoft 365 앱에 대한 반기 채널(대상 지정) 릴리스의 릴리스 정보를 IT 전문가에게 제공합니다.
ms.openlocfilehash: 3a0307e973092e845ee17c17d22a8b160f9e9ef4
ms.sourcegitcommit: 5f72a0e94cda2cb64636380605806c29bbcdc53f
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/26/2021
ms.locfileid: "52026283"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="978a8-103">반기 기업 채널(프리뷰)의 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="978a8-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="978a8-104">이 릴리스 정보에서는 엔터프라이즈용 Microsoft 365 앱, 비즈니스용 Microsoft 365 앱 및 프로젝트 및 Visio용 데스크톱 앱의 구독 버전에 대한 반기별 엔터프라이즈 채널(미리 보기) 업데이트에 포함된 새로운 기능 및 비보안 업데이트에 대한 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="978a8-105">당사는 Microsoft 365 앱에 대한 업데이트 채널을 일부 변경하고 있습니다. 여기에는 새 업데이트 채널 추가(월별 엔터프라이즈 채널) 및 기존 업데이트 채널의 이름 변경 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="978a8-106">자세한 내용은 [이 문서를 검토하세요](/DeployOffice/update-channels-changes).</span><span class="sxs-lookup"><span data-stu-id="978a8-106">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>


## <a name="version-2102-april-13"></a><span data-ttu-id="978a8-107">버전 2102: 4월 13일</span><span class="sxs-lookup"><span data-stu-id="978a8-107">Version 2102: April 13</span></span>
<span data-ttu-id="978a8-108">*버전2102(빌드 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="978a8-108">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="978a8-109">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="978a8-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="978a8-111">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="978a8-111">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="978a8-112">Access</span><span class="sxs-lookup"><span data-stu-id="978a8-112">Access</span></span>

- <span data-ttu-id="978a8-113">일부 경우 SQL Server 통과 쿼리를 실행하면 "커서 상태가 잘못되었습니다"라는 오류 메시지가 표시될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-113">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="978a8-114">Excel</span><span class="sxs-lookup"><span data-stu-id="978a8-114">Excel</span></span>

- <span data-ttu-id="978a8-115">Office 리본에서 비활성화된 명령의 아이콘은 회색으로 표시되지만 어두운 회색 Office 테마의 텍스트는 회색으로 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-115">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="978a8-116">다른 시트의 표에 행을 추가한 후 예기치 않게 셀에 데이터 유효성 검사를 적용할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-116">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="978a8-117">32비트 버전의 Excel에 있는 대화 상자 시트에서 함수가 작동하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-117">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="978a8-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="978a8-118">Outlook</span></span>

- <span data-ttu-id="978a8-119">Outlook이 유휴 시 충돌하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-119">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="978a8-120">새 장치에서 Outlook을 구성한 후 클라우드 설정 기능 사용자가 기본 설정으로 재정의된 사용자 지정 설정을 볼 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-120">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="978a8-121">사용자에게 예상보다 더 많은 서명이 표시될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-121">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="978a8-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="978a8-122">PowerPoint</span></span>

- <span data-ttu-id="978a8-123">Office 리본에서 비활성화된 명령의 아이콘은 회색으로 표시되지만 어두운 회색 Office 테마의 텍스트는 회색으로 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-123">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="978a8-124">Word</span><span class="sxs-lookup"><span data-stu-id="978a8-124">Word</span></span>

- <span data-ttu-id="978a8-125">Office 리본에서 비활성화된 명령의 아이콘은 회색으로 표시되지만 어두운 회색 Office 테마의 텍스트는 회색으로 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-125">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="978a8-126">복사 및 붙여넣기와 관련된 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-126">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="978a8-127">숨겨진 단락 끝에 입력할 때 응용 프로그램이 중단될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-127">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="978a8-128">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="978a8-128">Office Suite</span></span>

- <span data-ttu-id="978a8-129">편집 내용을 저장되지 않은 채로 이전에 연 파일을 열 때 사용자가 파일을 저장할 수 없었던 문제를 해결했으며, 이제 파일이 삭제됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-129">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="978a8-130">수정이 적용된 후 사용자에게 파일 삭제를 알리는 친숙한 메시지가 전송되므로 변경 내용을 취소하거나 다른 이름으로 파일을 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-130">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="978a8-131">SyncBacked 파일을 오프라인으로 열고 파일을 저장하기 전에 앱의 파일 이름을 바꿀 때 이름 변경 실패 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-131">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="978a8-132">GCC 사용자가 받아쓰기 기능을 사용할 수 없는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-132">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="978a8-133">가끔 Outlook의 텍스트가 투명해지고 읽을 수 없게 되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-133">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2102-march-09"></a><span data-ttu-id="978a8-135">버전 2102: 3월 9일</span><span class="sxs-lookup"><span data-stu-id="978a8-135">Version 2102: March 09</span></span>
<span data-ttu-id="978a8-136">*버전 2102(빌드 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="978a8-136">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="978a8-137">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="978a8-137">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="978a8-139">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="978a8-139">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="978a8-140">Excel</span><span class="sxs-lookup"><span data-stu-id="978a8-140">Excel</span></span>

- <span data-ttu-id="978a8-141">**잉크 도구 상자의 올가미 및 지우개:** 그리기 도구를 사용할 때 잉크 도구 상자에서 올가미와 지우개를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-141">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="978a8-142">[블로그 게시물](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-142">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="978a8-143">**PDF 연결 설정:** PDF로 연결하고 PDF에서 데이터를 가져오고 새로 고칩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-143">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="978a8-144">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="978a8-144">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="978a8-145">**수식에 사용할 변수 만들기:** LET 기능으로 성능, 가독성 및 구성성을 향상시킵니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-145">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="978a8-146">이 함수를 사용하면 새로운 공식 또는 기존 공식으로 명명된 변수를 작성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-146">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="978a8-147">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="978a8-147">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="978a8-148">[블로그 게시물](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-148">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="978a8-149">**고정된 폴더에 저장:** 폴더를 고정하면 Office 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-149">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="978a8-150">새 파일을 저장할 때 사용할 수 있는 폴더에 대한 추가 제어를 원하다는 사용자 피드백을 받았습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-150">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="978a8-151">저장 대화 상자에서 폴더를 고정하는 새로운 기능을 제공하게 되어 기쁘게 생각합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-151">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="978a8-152">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-152">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="978a8-153">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="978a8-153">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="978a8-154">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-154">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="978a8-155">**데이터 형식을 사용하여 Power BI에서 조직 데이터를 가져오기:** 이제 Power BI의 Excel 데이터 형식을 Office 365/Microsoft 365를 사용하는 조직의 참가자에게 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-155">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="978a8-156">필요한 정보를 가져오고 손쉽게 새로 고치는 건 일상적인 여러 워크플로에 매우 중요합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-156">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="978a8-157">Microsoft는 Power BI를 사용하여 Excel에서 데이터 형식으로 회사나 조직 정보에 액세스할 수 있도록 하여 스프레드시트에 연결된 정보를 제공하는 기능을 확장합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-157">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="978a8-158">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="978a8-158">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="978a8-159">[블로그 게시물](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-159">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="978a8-160">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-160">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="978a8-161">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-161">No conversion required.</span></span><br /><span data-ttu-id="978a8-162">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-162">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="978a8-163">**Excel에서 세련된 Visio 다이어그램 만들기:** 워크시트의 데이터를 사용하여 순서도나 조직도와 같은 데이터 기반 다이어그램을 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-163">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="978a8-164">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="978a8-164">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="978a8-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="978a8-165">Outlook</span></span>

- <span data-ttu-id="978a8-166">**그룹의 데이터 보호 지원:** 그룹을 만들 때 선택한 민감도 레이블이 그룹 전자 메일, 문서, 팀 사이트에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-166">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="978a8-167">**IT 관리자에 대한 인시던트 알림:** Microsoft 365 테넌트 전역 관리자 및 Office 앱 관리자는 Windows용 Outlook의 새로운 오른쪽 패널 알림을 통해 사용자에게 영향을 주는 Outlook 및 O365 Exchange 인시던트에 대한 알림을 받습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-167">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="978a8-168">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="978a8-168">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="978a8-169">**문자 서식을 사용해 Outlook 설문 조사 만들기**: 설문 조사를 쉽게 작성하고 투표를 수집하며 전자 메일로 결과를 볼 수 있습니다 [자세한 내용 보기](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="978a8-169">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="978a8-170">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-170">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="978a8-171">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-171">No conversion required.</span></span><br /><span data-ttu-id="978a8-172">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-172">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="978a8-173">**새 회의실 찾기:** 다양한 기능으로 회의실을 검색합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-173">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="978a8-174">**평소 말하는 식으로 검색:** "지난주 동물 병원 진료 예약"과 같은 일상적인 언어를 사용하여 검색을 필터링하고 범위를 좁힙니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-174">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="978a8-175">**이전 Outlook 세션의 항목을 빠르게 다시 여는 옵션:** 이전 Outlook 세션의 항목을 빠르게 다시 여는 옵션을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-175">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="978a8-176">[블로그 게시물](https://insider.office.com/ko-KR/blog/automatically-restore-windows-in-outlook)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-176">See details in [blog post](https://insider.office.com/ko-KR/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="978a8-177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="978a8-177">PowerPoint</span></span>

- <span data-ttu-id="978a8-178">**잉크 도구 상자의 올가미 및 지우개:** 그리기 도구를 사용할 때 잉크 도구 상자에서 올가미와 지우개를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-178">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="978a8-179">[블로그 게시물](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-179">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="978a8-180">**고정된 폴더에 저장:** 폴더를 고정하면 Office 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-180">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="978a8-181">새 파일을 저장할 때 사용할 수 있는 폴더에 대한 추가 제어를 원하다는 사용자 피드백을 받았습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-181">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="978a8-182">저장 대화 상자에서 폴더를 고정하는 새로운 기능을 제공하게 되어 기쁘게 생각합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-182">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="978a8-183">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-183">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="978a8-184">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="978a8-184">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="978a8-185">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-185">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="978a8-186">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-186">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="978a8-187">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-187">No conversion required.</span></span><br /><span data-ttu-id="978a8-188">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-188">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="978a8-189">Visio</span><span class="sxs-lookup"><span data-stu-id="978a8-189">Visio</span></span>

- <span data-ttu-id="978a8-190">**새 Azure 스텐실 및 셰이프:** 최신 Azure 다이어그램을 작성하는 데 도움이 되도록 스텐실을 더 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-190">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="978a8-191">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="978a8-191">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="978a8-192">Word</span><span class="sxs-lookup"><span data-stu-id="978a8-192">Word</span></span>

- <span data-ttu-id="978a8-193">**잉크 도구 상자의 올가미 및 지우개:** 그리기 도구를 사용할 때 잉크 도구 상자에서 올가미와 지우개를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-193">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="978a8-194">[블로그 게시물](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-194">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="978a8-195">**고정된 폴더에 저장:** 폴더를 고정하면 Office 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-195">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="978a8-196">새 파일을 저장할 때 사용할 수 있는 폴더에 대한 추가 제어를 원하다는 사용자 피드백을 받았습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-196">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="978a8-197">저장 대화 상자에서 폴더를 고정하는 새로운 기능을 제공하게 되어 기쁘게 생각합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-197">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="978a8-198">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-198">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="978a8-199">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="978a8-199">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="978a8-200">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-200">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="978a8-201">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-201">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="978a8-202">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-202">No conversion required.</span></span><br /><span data-ttu-id="978a8-203">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-203">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="978a8-204">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="978a8-204">Office Suite</span></span>

- <span data-ttu-id="978a8-205">**탭 창:** 이제 앱의 오른쪽에 있는 탭 UI를 사용하여 여러 창 간에 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-205">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="978a8-206">UI는 2개 이상의 창이 열려있는 경우에만 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-206">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="978a8-207">[블로그 게시물](https://blog-insider.office.com/2020/02/20/improved-pane-management/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="978a8-207">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="978a8-210">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="978a8-210">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="978a8-211">Access</span><span class="sxs-lookup"><span data-stu-id="978a8-211">Access</span></span>

- <span data-ttu-id="978a8-212">Office가 아닌 응용 프로그램에서 DAO를 사용할 경우 응용 프로그램이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-212">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="978a8-213">사용자에게 "잘못된 커서 상태" 오류 대화 상자가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-213">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="978a8-214">Excel</span><span class="sxs-lookup"><span data-stu-id="978a8-214">Excel</span></span>

- <span data-ttu-id="978a8-215">일부 레거시 Excel 4.0 및 Excel 5.0 매크로와 dialogsheets.show에 대한 일부 VBA 호출이 깨지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-215">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="978a8-216">피벗 테이블에서 "값 표시 형식" 메뉴를 사용하는 경우 Excel이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-216">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="978a8-217">사용자가 Excel 통합 문서를 PDF로 내보낼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-217">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="978a8-218">연결된 그림 붙여넣기 옵션을 사용할 때 이미지가 예상보다 작아지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-218">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="978a8-219">.xls 또는 .xlt 형식으로 저장할 때 일부 피벗 테이블 형식으로 인해 통합 문서가 손상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-219">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="978a8-220">Excel 4.0 매크로가 포함된 Excel 추가 기능 파일을 열 때 메시지 표시 없이 매크로가 계속 사용하지 않는 상태로 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-220">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="978a8-221">Excel이 새 버전의 파일을 사용할 수 있다는 메시지 표시줄을 잘못 표시하여 사용자가 변경 내용을 통합 문서 사본에 저장하거나 변경 내용을 취소하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-221">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="978a8-222">공동 작성 시 파일의 새 버전을 알려주는 메시지 표시줄이 일부 사용자에게 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-222">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="978a8-223">특정 Windows 보안 공격 방지 설정(SimExec, 호출자 확인)을 사용 중인 경우 Excel이 예기치 않게 시작되지 않거나 닫히는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-223">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="978a8-224">차트에서 데이터 계열을 선택한 후 Excel이 응답하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-224">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="978a8-225">이 변경 사항은 수식 내에서 글꼴을 올바르게 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-225">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="978a8-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="978a8-226">Outlook</span></span>

- <span data-ttu-id="978a8-227">사용자가 대리인에게 편집자 권한을 부여할 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-227">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="978a8-228">일부 사용자가 특정 검색 시나리오에서 Outlook이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-228">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="978a8-229">프로필에 큰 계층이 있는 공유 사서함 또는 위임된 사서함을 가진 사용자가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-229">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="978a8-230">전자 메일의 제목 줄이 비어있는 경우 일부 자동으로 생성된 전자 메일이 이를 빈 본문으로 보내는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-230">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="978a8-231">일부 사용자가 예기치 않게 오프라인 상태에서 Outlook이 시작되는 것을 관찰하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-231">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="978a8-232">대리인이 다른 사서함에서 공유 폴더를 열 때 간헐적으로 오류가 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-232">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="978a8-233">사용자가 검색 결과를 선택하면 응용 프로그램이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-233">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="978a8-234">일부 고객이 일정을 로드하는 동안 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-234">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="978a8-235">일부 모임에서 다른 참석자가 모임을 전달하는 경우 모임의 기존 참석자가 취소 통지를 받는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-235">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="978a8-236">사용자가 새 그룹을 만들고 나서 중복 일정 그룹이 나타나는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-236">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="978a8-237">공유 일정의 향상된 기능 사용자가 일정의 색을 노란색 또는 갈색으로 설정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-237">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="978a8-238">Outlook이 다시 시작될 때까지 탐색 창에 새로 추가된 일정이 나타나지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-238">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="978a8-239">캐시되지 않은 공유 일정을 검색할 때 검색 결과가 반환되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-239">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="978a8-240">일부 사용자가 메시지 창을 닫을 때 앱이 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-240">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="978a8-241">작업에 대해 상황 보고서를 보낼 때 받는 사람 필드가 비어 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-241">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="978a8-242">MailItem.BeforeAttachmentAdd 이벤트가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-242">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="978a8-243">일부 사용자가 특정 검색 시나리오에서 Outlook이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-243">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="978a8-244">사용자가 Outlook에서 검색할 때 앱이 가끔 예기치 않게 닫히는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-244">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="978a8-245">클라우드 설정 사용자가 설정을 업데이트할 때 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-245">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="978a8-246">사용자에게 편집된 서명을 저장하라는 메시지가 표시된 후 저장되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-246">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="978a8-247">하나 이상의 서명이 구성되었음에도 불구하고 일부 사용자에게 서명 드롭다운이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-247">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="978a8-248">사용자에 대한 클라우드 설정이 기본적으로 설정되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-248">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="978a8-249">사용자 서명 변경 내용이 저장되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-249">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="978a8-250">클라우드 설정을 사용하도록 설정한 사용자에 대해 Outlook에서 또 하나의 빈 서명을 만들도록 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-250">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="978a8-251">OWA에 올바른 기본 서명을 표시하는 것과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-251">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="978a8-252">유니코드 콘텐츠를 포함하는 서명이 손상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-252">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="978a8-253">인라인 번역 사용자가 피드백을 제출할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-253">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="978a8-254">회신하거나 전달할 때 중국어 메시지의 머리글을 읽을 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-254">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="978a8-255">OFT 파일로 저장하면 중국어 문자가 물음표로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-255">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="978a8-256">IDataObject 작업(예: 끌어서 놓기, 클립보드)에서 첨부 파일에 대한 filetime 포함을 사용하지 않도록 설정할 수 있는 regkey를 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-256">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="978a8-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="978a8-257">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="978a8-258">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="978a8-258">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="978a8-259">0 = filetimes가 제외됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-259">0 = filetimes are excluded.</span></span>  <span data-ttu-id="978a8-260">1 = (기본값) filetimes가 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-260">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="978a8-261">Azure Information Protection의 보호 레이블을 사용하여 메시지에 회신할 때 인라인 이미지를 사라지게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-261">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="978a8-262">암호화 전용 옵션을 사용하여 보낸 전자 메일에서 암호화 아이콘이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-262">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="978a8-263">사용자가 해당 옵션을 선택하지 않은 후 메일이 디지털 서명으로 전송될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-263">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="978a8-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="978a8-264">PowerPoint</span></span>

- <span data-ttu-id="978a8-265">문서 저장에 실패한 경우 응용 프로그램이 예기치 않게 닫히게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-265">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="978a8-266">Word에서 PowerPoint로 수식 복사/붙여넣기 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-266">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="978a8-267">이 변경 사항은 특정 지오메트리를 사용하여 형상 병합 작업을 적용할 때 경로 채우기 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-267">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="978a8-268">이 변경 사항은 수식 내에서 글꼴을 올바르게 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-268">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="978a8-269">이 변경 사항은 비디오 로드 중에 발생할 수 있는 처리 오류 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-269">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="978a8-270">Slide.Shapes.AddMediaObject2가 레거시 비디오 형식(MPG-1, Mpeg-2)에 가깝게 되는 VBA 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-270">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="978a8-271">QAT에서 추가된 글꼴 크기 명령이 업데이트하는 동안 가장 가까운 정의된 글꼴 크기로 자동 완성되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-271">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="978a8-272">새로 녹음된 오디오가 포함된 슬라이드를 복제한 후 파일을 저장할 때 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-272">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="978a8-273">삽입 후에 사용자가 다른 슬라이드를 클릭하여 슬라이드가 표시될 때까지 Forms 콘텐츠 추가 기능이 렌더링되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-273">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="978a8-274">제한된 보기에서 PowerPoint 파일을 열 때 IRM 보호를 사용하지 않도록 설정하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-274">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="978a8-275">많은 수의 특정 데이터 개체 유형(E2o)이 포함된 파일에서 공동 작성 속도가 느려지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-275">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="978a8-276">병합 오류 중에 IRM/보호된 문서를 사용할 때 문제를 해결하는 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-276">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="978a8-277">PresentationBeforeClose 이벤트를 청취하고 프레젠테이션을 확인하는 추가 기능이 있을 때 문서를 닫는 경우 저장 프롬프트가 루프에 표시되는 문제에 대한 수정 사항입니다. 속성을 이벤트 처리기의 일부로 저장했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-277">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="978a8-278">문서 복구 작업 후에도 손상된 PowerPoint 파일이 올바르게 열리지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-278">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="978a8-279">때때로 디자인 아이디어를 선택하면 프레젠테이션의 데이터 분류 레이블이 제거되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-279">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="978a8-280">Project</span><span class="sxs-lookup"><span data-stu-id="978a8-280">Project</span></span>

- <span data-ttu-id="978a8-281">PWA에서 로컬 mpp 파일로 프로젝트를 저장하는 경우 ProjectBeforeTaskChangeEvent가 실제로 사용자가 변경하지 않은 데이터에 대해 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-281">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="978a8-282">작업 양식 유형 보기에서 간격이 변경되는 경우 ProjectBeforeTaskChagne 이벤트의 NewVal에 올바른 값이 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-282">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="978a8-283">이벤트 코드를 실행 중이고 작업 폼 보기를 통하여 변경을 하려고 하는 경우, 확인 단추를 클릭하면 변경 내용이 커밋되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-283">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="978a8-284">특정 방식으로 리소스 배분 형식이 지정된 파일을 열 때 Project가 예기치 않게 종료될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-284">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="978a8-285">로드의 특정 부분에 프로젝트 파일에 문제가 있는 경우 특정 프로젝트를 열 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-285">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="978a8-286">팀 플래너 보기에 작업에 대한 테두리가 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-286">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="978a8-287">끌어서 놓기 작업이 팀 플래너에서 작동하지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-287">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="978a8-288">마일스톤 작업에 비용 자원이 할당되었을 때 기준 비용이 올바르게 롤업되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-288">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="978a8-289">Visio</span><span class="sxs-lookup"><span data-stu-id="978a8-289">Visio</span></span>

- <span data-ttu-id="978a8-290">사용자 지정 Visio 스텐실 및 내장 템플릿 모두에 대해 Office 365용 Visio의 커넥터를 사용하여 직선을 생성할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-290">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="978a8-291">Word</span><span class="sxs-lookup"><span data-stu-id="978a8-291">Word</span></span>

- <span data-ttu-id="978a8-292">문서 저장에 실패한 경우 응용 프로그램이 예기치 않게 닫히게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-292">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="978a8-293">Word에서 PowerPoint로 수식 복사/붙여넣기 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-293">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="978a8-294">이 변경 사항은 문서 편집 시 커서 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-294">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="978a8-295">3D 효과가 있는 아이콘 및 SVG 그래픽에 적용된 색과 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-295">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="978a8-296">내레이터에서 단락을 건너뛰는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-296">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="978a8-297">서식 있는 텍스트 콘텐츠 컨트롤 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-297">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="978a8-298">스타일 갤러리 대화 상자와 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-298">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="978a8-299">공동으로 작성할 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-299">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="978a8-300">문서 스타일이 서식 파일의 다른 스타일로 바뀌는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-300">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="978a8-301">최적화된 게이트에 의해 노출된, Word에 영향을 미치는 어설트 버그를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-301">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="978a8-302">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="978a8-302">Office Suite</span></span>

- <span data-ttu-id="978a8-303">동기화 지원에서 서버 전용으로 전환된 파일을 저장할 때 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-303">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="978a8-304">특정 시나리오에서 SaveAs를 시도하면 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-304">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="978a8-305">SaveRequestManagerCam이 오류를 반환하는 대신 응용 프로그램을 종료하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-305">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="978a8-306">모든 상호 종단 구성 요소가 순차적으로 닫히도록 파일 닫기 순서가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-306">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="978a8-307">캐시의 URL과 OneDrive의 URL이 일치하지 않을 때 파일이 SyncBacked가 아닌 상태로 열리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-307">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="978a8-308">비즈니스용 Skype 메시지에서 복사/붙여넣기를 하면 "콘텐츠를 붙여넣는 중에 오류가 발생했습니다"라는 대화 상자가 표시되는 버그를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-308">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="978a8-309">설명에서 Excel로 텍스트를 복사/붙여넣을 때 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-309">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="978a8-310">수학 방정식을 포함하는 텍스트에서 내레이터를 사용할 때 발생할 수 있는 충돌을 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-310">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="978a8-311">Office에서 사용자가 잉크젯 프린터로 문서/파일을 인쇄하고 프린터의 잉크가 부족하면, 잉크젯 프린터에 토너가 없더라도 "토너 부족" 또는 "토너 없음" 메시지가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-311">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="978a8-312">메시지를 변경하여 "토너/잉크 부족" 및 "토너/잉크 없음"으로 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-312">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="978a8-313">이전 버전에서 새 Office 버전을 설치하면 레지스트리 항목이 누락되어 전원 쿼리를 사용할 수 없는 등의 기능이 누락될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-313">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="978a8-314">Microsoft 365 엔드포인트 데이터 손실 방지로 인해 디스크의 Office 문서를 분류하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-314">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="978a8-315">특정 사용자 설정이 유지되지 않는 그림 압축 대화 상자의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-315">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="978a8-316">미디어 컨트롤러 이벤트 알림과 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-316">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="978a8-317">미디어 플레이어 엔진 타이밍과 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-317">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="978a8-318">최적화된 이진 크기</span><span class="sxs-lookup"><span data-stu-id="978a8-318">Optimized binary size.</span></span>


- <span data-ttu-id="978a8-319">Anaheim 웹 보기는 아직 WIP(Windows Information Protection)를 지원 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-319">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="978a8-320">이 수정 기능은 WIP를 사용하는 환경의 하위 웹에 Office 추가 플랫폼을 다시 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-320">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="978a8-321">이 기능은 고객의 컴퓨터 환경에 따라 Edge Spartan 웹 보기 또는 Trident 웹 보기가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-321">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="978a8-322">하위 수준 WebViews 모두 WIP를 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-322">Both down level WebViews support WIP.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-february-09"></a><span data-ttu-id="978a8-324">버전 2008: 2월 9일</span><span class="sxs-lookup"><span data-stu-id="978a8-324">Version 2008: February 09</span></span>
<span data-ttu-id="978a8-325">*버전 2008 (빌드 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="978a8-325">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="978a8-326">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="978a8-326">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="978a8-328">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="978a8-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="978a8-329">Excel</span><span class="sxs-lookup"><span data-stu-id="978a8-329">Excel</span></span>

- <span data-ttu-id="978a8-330">잘못된 파일 특성(만든 시간, 수정된 시간 등)이 있는 UNC 파일을 열 때 Excel이 예기치 않게 닫히는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-330">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="978a8-331">Excel에서 차트를 복사하여 Word 또는 PowerPoint에 붙여넣을 때 소수점 및 천 단위 구분 기호 설정이 수행되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-331">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="978a8-332">매크로가 실행될 때마다 피벗 테이블 범위 형식과 관련된 매크로 실행 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-332">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="978a8-333">시트를 복사하거나 다른 통합 문서로 이동할 때 조건부 서식 규칙이 삭제되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-333">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="978a8-334">앱 부팅 시 시작 화면이 비활성화되었을 때 사용자가 Excel 파일에 민감도 레이블을 적용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-334">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="978a8-335">OneDrive 동기화 폴더에서 클라우드 파일을 여는 중 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-335">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="978a8-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="978a8-336">Outlook</span></span>

- <span data-ttu-id="978a8-337">첨부 파일을 추가하거나 저장할 때 Outlook이 산발적으로 작동을 멈추게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-337">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="978a8-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="978a8-338">PowerPoint</span></span>

- <span data-ttu-id="978a8-339">QAT에서 추가한 글꼴 크기 명령이 업데이트하는 동안 가장 가까운 정의된 글꼴 크기로 자동 완성되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-339">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="978a8-340">'원본 서식 유지' 옵션이 때때로 새 슬라이드 마스터에 복사되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-340">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="978a8-341">Word</span><span class="sxs-lookup"><span data-stu-id="978a8-341">Word</span></span>

- <span data-ttu-id="978a8-342">변경사항 추적에서 Word 문서를 열면 오류 대화상자가 표시될 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-342">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="978a8-343">OneDrive 동기화 폴더에서 클라우드 파일을 여는 중 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-343">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="978a8-344">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="978a8-344">Office Suite</span></span>

- <span data-ttu-id="978a8-345">Office에서 파일을 열 수 없는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-345">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="978a8-346">서식 복사를 통해 커넥터에 적용된 스케치된 윤곽선이 포함된 문서가 손상될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-346">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-january-12"></a><span data-ttu-id="978a8-348">버전 2008: 1월 12일</span><span class="sxs-lookup"><span data-stu-id="978a8-348">Version 2008: January 12</span></span>
<span data-ttu-id="978a8-349">*버전 2008(빌드 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="978a8-349">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="978a8-350">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="978a8-350">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="978a8-352">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="978a8-352">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="978a8-353">Excel</span><span class="sxs-lookup"><span data-stu-id="978a8-353">Excel</span></span>

- <span data-ttu-id="978a8-354">읽기 전용 책을 열면 피벗 테이블 데이터를 더 이상 새로 고칠 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-354">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="978a8-355">이 변경 사항은 다음 문제에 대한 수정 사항을 제공합니다. OneDrive 로컬 동기화 폴더에서 파일을 삽입하면 Excel "개체 삽입"에 올바른 아이콘이 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-355">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="978a8-356">공동 작성 시 새 파일 버전에 대한 알림을 고객이 잘못 받는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-356">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="978a8-357">덮어쓰기 모드에서 IME를 사용하면 추가 문자를 잘못 전달할 수 있는 편집 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-357">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="978a8-358">다중 스레드 재호출 기능과 함께 실시간 데이터를 사용할 때 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-358">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="978a8-359">특정 Windows 보안 공격 방지 설정(SimExec, 호출자 확인)을 사용 중인 경우 Excel이 예기치 않게 시작되지 않거나 닫히는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-359">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="978a8-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="978a8-360">Outlook</span></span>

- <span data-ttu-id="978a8-361">초안에 저장할 때 SmartLinks의 서식이 손실되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-361">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="978a8-362">정책을 재정의할 때 사유 텍스트를 사용자 지정할 수 있는 방법을 제공하도록 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-362">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="978a8-363">OFT 파일로 저장하면 중국어 문자가 물음표로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-363">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="978a8-364">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="978a8-364">PowerPoint</span></span>

- <span data-ttu-id="978a8-365">Slide.Shapes.AddMediaObject2가 레거시 비디오 형식(MPG-1, Mpeg-2)과 충돌하는 VBA 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-365">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="978a8-366">문서 복구 작업 후에도 손상된 PowerPoint 파일이 올바르게 열리지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-366">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="978a8-367">Project</span><span class="sxs-lookup"><span data-stu-id="978a8-367">Project</span></span>

- <span data-ttu-id="978a8-368">특정 방식으로 리소스 윤곽선이 지정된 파일을 열 때 Project가 예기치 않게 종료될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-368">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="978a8-369">Skype</span><span class="sxs-lookup"><span data-stu-id="978a8-369">Skype</span></span>

- <span data-ttu-id="978a8-370">사용자의 TLS-DSK 인증서가 예상 시간에 갱신되지 않고 유효 기간이 12시간 미만인 경우에만 갱신되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-370">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="978a8-371">Office에 대한 라이선스가 아직 없을 때 로그인 후 비즈니스용 Skype UI가 공백으로 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-371">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="978a8-372">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="978a8-372">Office Suite</span></span>

- <span data-ttu-id="978a8-373">이렇게 변경하면 레거시 다이어그램이 포함된 파일 열기 관련 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-373">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="978a8-374">이렇게 변경하면 액세스 위반을 초래하는 SVG 예비 프록시의 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-374">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

> [!NOTE]
> <span data-ttu-id="978a8-377">Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="978a8-377">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


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
