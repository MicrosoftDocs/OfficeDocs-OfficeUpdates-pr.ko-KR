---
title: 릴리스 정보 현재 채널(미리 보기)
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 이후 참가자 대상 그룹에게 새 기능, 수정 사항 또는 알려진 문제의 최신 목록을 제공합니다.
ms.openlocfilehash: 81b0fd214752a3218809f860db9ad97f34d3ad0c
ms.sourcegitcommit: 6a6a10d50664c552f2aea560d521265d2b0677d2
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/27/2021
ms.locfileid: "52058742"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="946dd-103">Office 현재 채널(미리 보기)에 대한 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="946dd-104">이 문서에는 Windows 데스크톱용 Word, Excel, PowerPoint, Outlook, Access, Project 및 Teams의 현재 채널(미리 보기) 빌드에 대한 릴리스 정보가 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, Project, and Teams for Windows desktop.</span></span> <span data-ttu-id="946dd-105">매주 Microsoft는 흥미로운 새 기능, 중요한 수정 사항, 여러분에게 알아야 할 중요한 문제를 강조합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="946dd-106">일정 기간 동안 기능(때로는 수정)을 현재 채널(미리 보기)에 롤아웃하는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="946dd-107">이로서 더욱 광범위한 사용자들에게 기능을 릴리스하기 전에 원활하게 작동하는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="946dd-108">따라서 아래에 설명된 기능이 보이지 않더라도 곧 제공되게 되므로 걱정할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="946dd-109">당사는 Microsoft 365 앱에 대한 업데이트 채널을 일부 변경하고 있습니다. 여기에는 새 업데이트 채널 추가(월별 엔터프라이즈 채널) 및 기존 업데이트 채널의 이름 변경 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="946dd-110">자세한 내용은 [이 문서를 참조](/DeployOffice/update-channels-changes)하세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-110">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>

> [!NOTE]
> - <span data-ttu-id="946dd-111">릴리스 정보 게시 날짜는 실제 빌드 릴리스 날짜와 일치하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-111">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="946dd-112">Microsoft Teams 기능은 릴리스 주기가 보다 빈번하기 때문에 최근에 릴리스된 현재 채널 미리 보기와 다를 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-112">Microsoft Teams features may differ from the latest Current Channel Preview released as they have a more frequent release cadence.</span></span>

[//]: # (제거하지 마세요)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

## <a name="version-2104-april-26"></a><span data-ttu-id="946dd-115">버전 2104: 4월 26일</span><span class="sxs-lookup"><span data-stu-id="946dd-115">Version 2104: April 26</span></span>
<span data-ttu-id="946dd-116">*버전 2104(빌드 13929.20254)*</span><span class="sxs-lookup"><span data-stu-id="946dd-116">*Version 2104 (Build 13929.20254)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-118">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-118">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-119">Outlook</span></span>

- <span data-ttu-id="946dd-120">**공유 일정 향상 켜기:** Office 365의 공유 일정의 경우 Outlook에서 REST API를 사용하여 해당 일정을 업데이트할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-120">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="946dd-121">미리 보기를 설정하여 공유 일정에 보다 빠르고 신뢰할 수 있는 업데이트를 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-121">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-124">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-124">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-125">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-125">Excel</span></span>

- <span data-ttu-id="946dd-126">일부 파일이 보호된 보기에서 열리지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-126">We fixed an issue where some files would occasionally fail to open in Protected View</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-127">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-127">Outlook</span></span>

- <span data-ttu-id="946dd-128">Outlook이 OWA에 구성된 중요 받은 편지함 기본 설정을 재정의하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-128">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2104-april-19"></a><span data-ttu-id="946dd-130">버전 2104: 4월 19일</span><span class="sxs-lookup"><span data-stu-id="946dd-130">Version 2104: April 19</span></span>
<span data-ttu-id="946dd-131">*버전 2104(빌드 13929.20216)*</span><span class="sxs-lookup"><span data-stu-id="946dd-131">*Version 2104 (Build 13929.20216)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-133">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-133">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-134">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-134">Excel</span></span>

- <span data-ttu-id="946dd-135">**동적 배열에서 데이터 가져오기:** 현재 통합 문서의 동적 배열에서 데이터를 가져오고, 모양을 변경하고, 새로 고칠 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-135">**Import data from dynamic arrays:** You can now import, shape and refresh data from dynamic arrays in the current workbook.</span></span> [<span data-ttu-id="946dd-136">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-136">Learn more</span></span>](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)

### <a name="outlook"></a><span data-ttu-id="946dd-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-137">Outlook</span></span>

- <span data-ttu-id="946dd-138">**향상된 일정 검색:** 일정 검색이 개선되었으며, 그 중 대폭 개선된 사항은 검색 결과에서 시리즈의 다음 항목을 더 쉽게 찾을 수 있는 기능입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-138">**Improved Calendar Search:** Improvements have been made to Calendar search, largest of which is the ability to more easily find the next occurence of a series in search results.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-141">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-141">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-142">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-142">Access</span></span>

- <span data-ttu-id="946dd-143">이 변경은 일부 경우 SQL Server를 실행하면 통과 쿼리로 인해 "커서 상태가 잘못되었습니다"라는 오류 메시지가 표시될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-143">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


- <span data-ttu-id="946dd-144">외부 응용 프로그램이 접근성 인터페이스를 요청하는 경우 참조가 릴리스될 때까지 종료되지 않도록 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-144">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="946dd-145">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-145">Excel</span></span>

- <span data-ttu-id="946dd-146">보호된 시트에 수식으로 붙여넣을 수 있는 기능을 막는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-146">We fixed a problem that was preventing the ability to paste as formulas on a protected sheet.</span></span>


- <span data-ttu-id="946dd-147">파일을 PDF 문서로 저장한 경우 HYPERLINK 함수를 사용하여 만든 하이퍼링크가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-147">We fixed an issue in which hyperlinks created using the HYPERLINK function would not work if the file was saved as a PDF document.</span></span>


- <span data-ttu-id="946dd-148">암시적 연산자(@) 기호가 빈 범위에 대한 참조와 함께 수식에 추가되어 잠재적으로 잘못된 결과를 제공하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-148">We fixed an issue where an implicit operator (@) symbol would be added to the formula with a reference to an empty range and potentially give the incorrect result.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-149">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-149">Outlook</span></span>

- <span data-ttu-id="946dd-150">폴더 계층 구조 변경을 동기화할 때 일부 사용자에게 Outlook이 예기치 않게 닫히는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-150">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="946dd-151">일정을 추가할 때 사용자에게 "시간이 걸릴 수 있습니다"라는 메시지가 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-151">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>


- <span data-ttu-id="946dd-152">대리인이 새로 추가된 일정에 생성된 모임의 이끌이로 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-152">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="946dd-153">이 주의 회의는 교장의 달력에 표시되지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-153">Meetings in this state did not appear on the principal's calendar.</span></span>


- <span data-ttu-id="946dd-154">사용자가 검색할 때 충돌이 발생하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-154">We fixed an issue that caused users to experience a crash when searching.</span></span>


- <span data-ttu-id="946dd-155">검색 관련 충돌이 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-155">We fixed a search related crash.</span></span>


- <span data-ttu-id="946dd-156">사용자의 서명이 예기치 않게 사라지는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-156">We fixed an issue that caused users to see signatures disappear unexpectedly.</span></span>


- <span data-ttu-id="946dd-157">사용자가 메시지를 작성할 때 UI 포커스가 사라질 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-157">We fixed an issue that could cause users to see the message that they are composing losing the UI focus.</span></span>


- <span data-ttu-id="946dd-158">Outlook이 OWA에 구성된 중요 받은 편지함 기본 설정을 재정의하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-158">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="946dd-159">새 장치에서 Outlook을 구성한 후 클라우드 설정 기능 사용자가 기본 설정으로 재정의된 사용자 지정 설정을 볼 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-159">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="946dd-160">일부 사람이 보조 메일 계정과 연결된 서명에 액세스할 수 없는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-160">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="946dd-161">다른 사용자를 대신하여 전체 주소 목록이 아닌 주소록에 대해 확인할 때 이름 확인이 실패하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-161">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="946dd-162">다른 사용자를 대신하여 전체 주소 목록이 아닌 주소록에 대해 확인할 때 이름 확인이 실패하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-162">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-163">프로젝트</span><span class="sxs-lookup"><span data-stu-id="946dd-163">Project</span></span>

- <span data-ttu-id="946dd-164">날짜 형식이 W4/4인 경우 날짜 선택기에 잘못된 날짜와 연도가 표시될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-164">Fixed an issue where if the date format is W4/4, the date picker may show the wrong day and year.</span></span>


### <a name="visio"></a><span data-ttu-id="946dd-165">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-165">Visio</span></span>

- <span data-ttu-id="946dd-166">닫는 동안 Visio 작동이 중지되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-166">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="946dd-167">모든 결과를 표시하는 "셰이프 검색" 기능이 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-167">Fixed "Search Shape" feature to display all the results</span></span>



### <a name="word"></a><span data-ttu-id="946dd-168">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-168">Word</span></span>

- <span data-ttu-id="946dd-169">이 버그에서 Office는 특정 정책을 준수하지 않았습니다 (템플릿 그룹이 비활성화되어야 할 경우 홈페이지에 표시됨).</span><span class="sxs-lookup"><span data-stu-id="946dd-169">In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled).</span></span> <span data-ttu-id="946dd-170">이 픽스를 적용하면 정책이 존중됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-170">With this fix, the policies are being honored.</span></span>


- <span data-ttu-id="946dd-171">문서를 공동 작성하는 경우 설명 순서가 변경되어도 활성 초안이 지워지지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-171">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="946dd-172">일부 국제 언어의 경우 문장 부호와 숫자가 잘못된 측에 표시되는 Modern Commenting의 버그를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-172">Fixed bug in Modern Commenting where punctuation and numbers would show up on the wrong side for some international languages.</span></span>


- <span data-ttu-id="946dd-173">'B'와 ')'의 조합이 자동으로 이모티콘을 착용한 선글라스로 바뀌는 문제를 수정했고 이제 개별 캐릭터로 유지됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-173">Fixed an issue where the combination of 'B' and ')' would automatically turn into the sunglass wearing emoji and now remain as the individual characters</span></span>


- <span data-ttu-id="946dd-174">로컬에 저장된 파일에 대한 자동 저장 설명 텍스트를 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-174">Updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="946dd-175">공동 작성 중 메모 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-175">We fixed an issue with comments during coauthoring.</span></span>


- <span data-ttu-id="946dd-176">메모 아이콘과 관련된 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-176">We fixed an issue relating to comment icon.</span></span>


- <span data-ttu-id="946dd-177">복사 및 붙여넣기 스타일이 붙여 넣은 텍스트와 다를 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-177">We fixed an issue which copy and paste styles may not be same in pasted text.</span></span>


- <span data-ttu-id="946dd-178">제공될 텍스트 예측에 대한 조건을 최적화합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-178">Optimizes conditions for text predictions to be offered.</span></span>


- <span data-ttu-id="946dd-179">하이퍼링크와 관련된 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-179">We fixed an issue relating to hyperlink.</span></span>


- <span data-ttu-id="946dd-180">읽기 모드에서 어두운 모드 테마를 사용할 경우 일부 텍스트는 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-180">Some select text not visible when using darkmode theme in reading mode.</span></span>


- <span data-ttu-id="946dd-181">자동 저장에서 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-181">We fixed an issue in auto save.</span></span>


- <span data-ttu-id="946dd-182">Application.OnTime에서 올바르게 트리거되지 않을 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-182">We made a fix in Application.OnTime where it might not trigger correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-183">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-183">Office Suite</span></span>

- <span data-ttu-id="946dd-184">텍스트의 연산과 관련된 성능 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-184">Fixed a performance issue related to iteration of text.</span></span>


- <span data-ttu-id="946dd-185">Office의 GDI+ LineJoinMiterClipped 지원 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-185">Fixes an issue with support of GDI+ LineJoinMiterClipped in Office.</span></span>


- <span data-ttu-id="946dd-186">이 릴리스는 키워드가 문서의 첫 줄에 있는 경우 줄 범위가 중요한 콘텐츠 처리를 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-186">This release improves handling of line-spanning sensitive content when the keyword is on the first line of a document.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2103-april-13"></a><span data-ttu-id="946dd-188">버전 2103: 4월 13일</span><span class="sxs-lookup"><span data-stu-id="946dd-188">Version 2103: April 13</span></span>
<span data-ttu-id="946dd-189">*버전 2103(빌드 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="946dd-189">*Version 2103 (Build 13901.20400)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="946dd-190">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-190">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="946dd-191">Teams</span><span class="sxs-lookup"><span data-stu-id="946dd-191">Teams</span></span>

- <span data-ttu-id="946dd-192">**동적 보기** 동적 보기는 Teams 모임의 공유 콘텐츠 및 비디오 참가자를 자동으로 최적화합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-192">**Dynamic view** Dynamic view automatically optimizes shared content and video participants in Teams meetings.</span></span> <span data-ttu-id="946dd-193">새로운 컨트롤을 사용하면 공유 콘텐츠와 특정 참가자를 나란히 표시하는 기능과 같이 선호도와 요구 사항에 맞게 보기를 개인화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-193">New controls let you personalize the view to suit your preferences and needs, such as the ability to show shared content and specific participants side-by-side.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2103-april-10"></a><span data-ttu-id="946dd-195">버전 2103: 4월 10일</span><span class="sxs-lookup"><span data-stu-id="946dd-195">Version 2103: April 10</span></span>
<span data-ttu-id="946dd-196">*버전 2103(빌드 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="946dd-196">*Version 2103 (Build 13901.20400)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-198">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-198">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-199">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-199">Excel</span></span>

- <span data-ttu-id="946dd-200">이미지를 그릴 때 잠재적인 리소스 경합 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-200">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-201">Outlook</span></span>

- <span data-ttu-id="946dd-202">일정을 추가할 때 사용자에게 "시간이 걸릴 수 있습니다"라는 메시지가 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-202">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>

- <span data-ttu-id="946dd-203">대리인이 새로 추가된 일정에 생성된 모임의 이끌이로 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-203">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="946dd-204">이 주의 회의는 교장의 달력에 표시되지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-204">Meetings in this state did not appear on the principal's calendar.</span></span>

- <span data-ttu-id="946dd-205">이미지를 그릴 때 잠재적인 리소스 경합 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-205">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-206">Powerpoint</span><span class="sxs-lookup"><span data-stu-id="946dd-206">Powerpoint</span></span>

- <span data-ttu-id="946dd-207">이미지를 그릴 때 잠재적인 리소스 경합 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-207">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-208">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-208">Word</span></span>

- <span data-ttu-id="946dd-209">이미지를 그릴 때 잠재적인 리소스 경합 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-209">Fixed a potential resource contention issue in word when drawing an image.</span></span>

- <span data-ttu-id="946dd-210">인쇄 미리 보기에서 응답이 없는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-210">Fixed a non-responsive issue while in Print preview.</span></span>

- <span data-ttu-id="946dd-211">로컬에 저장된 파일에 대한 자동 저장 설명 텍스트를 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-211">Updates text on autosave callout for files saved locally.</span></span>

### <a name="office-suite"></a><span data-ttu-id="946dd-212">Office Suite</span><span class="sxs-lookup"><span data-stu-id="946dd-212">Office Suite</span></span>

- <span data-ttu-id="946dd-213">SyncBacked 파일을 오프라인으로 열고 파일을 저장하기 전에 앱의 파일 이름을 바를 때 이름 변경 실패 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-213">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2103-april-02"></a><span data-ttu-id="946dd-215">버전 2103: 4월 2일</span><span class="sxs-lookup"><span data-stu-id="946dd-215">Version 2103: April 02</span></span>
<span data-ttu-id="946dd-216">*버전 2103(빌드 13901.20336)*</span><span class="sxs-lookup"><span data-stu-id="946dd-216">*Version 2103 (Build 13901.20336)*</span></span>
* <span data-ttu-id="946dd-217">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-217">Various bugs and performance fixes.</span></span>

## <a name="version-2103-april-1"></a><span data-ttu-id="946dd-218">버전 2103: 4월 1일</span><span class="sxs-lookup"><span data-stu-id="946dd-218">Version 2103: April 1</span></span>
<span data-ttu-id="946dd-219">*버전 2103(빌드 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="946dd-219">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="946dd-220">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-220">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="946dd-221">Teams</span><span class="sxs-lookup"><span data-stu-id="946dd-221">Teams</span></span>

- <span data-ttu-id="946dd-222">**날짜/시간 형식** 이 업데이트를 통해 Teams의 날짜/시간 형식이 Mac 및 Windows 운영 체제 국가별 설정과 일치하게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-222">**Date/Time format** With this update, the date/time formats in Teams will match the Mac and Windows operating system regional settings.</span></span> <span data-ttu-id="946dd-223">이전에 Teams는 날짜/시간을 응용 프로그램의 언어에 해당하는 형식으로만 표시했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-223">Previously, Teams would only show date/time in the format corresponding to the application's language.</span></span> <span data-ttu-id="946dd-224">운영 체제의 일정관리 설정에 관계없이 그레고리력만 지원됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-224">It's important to note that only the Gregorian calendar is supported regardless of the operating system's calendar setting.</span></span> 

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2103-march-30"></a><span data-ttu-id="946dd-226">버전 2103: 3월 30일</span><span class="sxs-lookup"><span data-stu-id="946dd-226">Version 2103: March 30</span></span>
<span data-ttu-id="946dd-227">*버전 2103(빌드 13901.20312)*</span><span class="sxs-lookup"><span data-stu-id="946dd-227">*Version 2103 (Build 13901.20312)*</span></span>
* <span data-ttu-id="946dd-228">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-228">Various bugs and performance fixes.</span></span>

## <a name="version-2103-march-28"></a><span data-ttu-id="946dd-229">버전 2103: 3월 28일</span><span class="sxs-lookup"><span data-stu-id="946dd-229">Version 2103: March 28</span></span>
<span data-ttu-id="946dd-230">*버전 2103(빌드 13901.20306)*</span><span class="sxs-lookup"><span data-stu-id="946dd-230">*Version 2103 (Build 13901.20306)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-232">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-232">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-233">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-233">Outlook</span></span>

- <span data-ttu-id="946dd-234">폴더 계층 구조 변경을 동기화할 때 일부 사용자에게 Outlook이 예기치 않게 닫히는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-234">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="946dd-235">일부 사용자가 탐색 창에서 기본 및 보조 일정으로 전환하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-235">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2103-march-22"></a><span data-ttu-id="946dd-237">버전 2103: 3월 22일</span><span class="sxs-lookup"><span data-stu-id="946dd-237">Version 2103: March 22</span></span>
<span data-ttu-id="946dd-238">*버전 2103(빌드 13901.20230)*</span><span class="sxs-lookup"><span data-stu-id="946dd-238">*Version 2103 (Build 13901.20230)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-240">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-240">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-241">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-241">Outlook</span></span>

- <span data-ttu-id="946dd-242">사용자에게 예상보다 더 많은 서명이 표시될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-242">We fixed an issue that caused users to see more signatures than expected.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2103-march-15"></a><span data-ttu-id="946dd-244">버전 2103: 3월 15일</span><span class="sxs-lookup"><span data-stu-id="946dd-244">Version 2103: March 15</span></span>
<span data-ttu-id="946dd-245">*버전 2103(빌드 13901.20170)*</span><span class="sxs-lookup"><span data-stu-id="946dd-245">*Version 2103 (Build 13901.20170)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-247">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-247">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="946dd-248">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-248">Project</span></span>

- <span data-ttu-id="946dd-249">닫는 동안 Visio 작동이 중지되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-249">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="946dd-250">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-250">Visio</span></span>

- <span data-ttu-id="946dd-251">닫는 동안 Visio 작동이 중지되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-251">Fixed an issue where Visio could stop working during close.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)
## <a name="version-2103-march-11"></a><span data-ttu-id="946dd-254">버전 2103: 3월 11일</span><span class="sxs-lookup"><span data-stu-id="946dd-254">Version 2103: March 11</span></span>
<span data-ttu-id="946dd-255">*버전 2103(빌드 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="946dd-255">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="946dd-256">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-256">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-257">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-257">Excel</span></span>

- <span data-ttu-id="946dd-258">**중요한 암호화된 문서에 자동 저장 및 공동 작성**: 생산성과 보안을 바꾸지 마세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-258">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="946dd-259">Microsoft Information Protection을 사용하면 민감도 레이블로 암호화된 문서를 자동 저장하여 암호화되지 않은 문서와 마찬가지로 실시간으로 다른 사용자와 공동 작성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-259">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="946dd-260">테넌트 옵트인(자세한 정보: https://aka.ms/mipcoauth)이 필요합니다</span><span class="sxs-lookup"><span data-stu-id="946dd-260">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-261">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-261">Outlook</span></span>

- <span data-ttu-id="946dd-262">**새 회의실 및 작업 영역 예약 환경:** 회의실 예약 환경이 새로 변경되었으며 개별 작업 영역도 예약할 수 있는 기능이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-262">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-263">PowerPoint</span></span>

- <span data-ttu-id="946dd-264">**중요한 암호화된 문서에 자동 저장 및 공동 작성**: 생산성과 보안을 바꾸지 마세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-264">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="946dd-265">Microsoft Information Protection을 사용하면 민감도 레이블로 암호화된 문서를 자동 저장하여 암호화되지 않은 문서와 마찬가지로 실시간으로 다른 사용자와 공동 작성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-265">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="946dd-266">테넌트 옵트인(자세한 정보: https://aka.ms/mipcoauth)이 필요합니다</span><span class="sxs-lookup"><span data-stu-id="946dd-266">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="teams"></a><span data-ttu-id="946dd-267">Teams</span><span class="sxs-lookup"><span data-stu-id="946dd-267">Teams</span></span>

- <span data-ttu-id="946dd-268">**부재 중 상태** 다른 사용자가 채팅 메시지를 보내면 근무 중이 아니거나 휴가 중이라 답장을 할 수 없다는 것을 알릴 수 있도록 메시지를 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-268">**Out of Office status** Set up a message to let others know you're not working or on vacation so you're not available to reply when they send a chat message to you.</span></span> <span data-ttu-id="946dd-269">부재 중 상태도 Outlook 일정의 자동 응답과 동기화됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-269">Your Out of Office status will also sync with Automatic Replies in your Outlook calendar.</span></span>

### <a name="visio"></a><span data-ttu-id="946dd-270">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-270">Visio</span></span>

- <span data-ttu-id="946dd-271">**Office 아이콘이 새롭게 단장했습니다.** 간단하고 강력하며 지능적인 Office 환경을 반영하여 제품 아이콘이 다시 디자인되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-271">**Office icons have a new look:** The product icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span> [<span data-ttu-id="946dd-272">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-272">Learn more</span></span>](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a><span data-ttu-id="946dd-273">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-273">Word</span></span>

- <span data-ttu-id="946dd-274">**Word 문서용 어두운 모드:** 어두운 모드는 눈의 부담을 줄이고 문서에서 작업하는 동안 밝은 민감도를 수용하는 데 도움이 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-274">**Dark Mode for Word documents:** Dark Mode may help reduce eye strain and accommodate light sensitivity while working on your documents.</span></span>

- <span data-ttu-id="946dd-275">**중요한 암호화된 문서에 자동 저장 및 공동 작성**: 생산성과 보안을 바꾸지 마세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-275">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="946dd-276">Microsoft Information Protection을 사용하면 민감도 레이블로 암호화된 문서를 자동 저장하여 암호화되지 않은 문서와 마찬가지로 실시간으로 다른 사용자와 공동 작성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-276">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="946dd-277">테넌트 옵트인(자세한 정보: https://aka.ms/mipcoauth)이 필요합니다</span><span class="sxs-lookup"><span data-stu-id="946dd-277">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-280">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-280">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-281">액세스</span><span class="sxs-lookup"><span data-stu-id="946dd-281">Access</span></span>

- <span data-ttu-id="946dd-282">외장 드라이브를 제거할 때 예기치 않은 앱이 닫히는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-282">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="946dd-283">외부 응용 프로그램이 접근성 인터페이스를 요청하는 경우 참조가 릴리스될 때까지 종료되지 않도록 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-283">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="946dd-284">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-284">Excel</span></span>

- <span data-ttu-id="946dd-285">외장 드라이브를 제거할 때 예기치 않은 앱이 닫히는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-285">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="946dd-286">이미지를 검색할 수 없는 문제로 인해 데이터 형식 카드를 표시하려고 할 때 Excel이 가끔 예기치 않게 닫히는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-286">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>


- <span data-ttu-id="946dd-287">일본어 글꼴로 곱셈 또는 나눗셈 기호를 사용할 때 글꼴이 예기치 않게 변경되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-287">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="946dd-288">이제 문자를 지원하는 경우 동일한 글꼴을 계속 사용합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-288">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="946dd-289">사용자가 Excel 통합 문서를 PDF로 내보낼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-289">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="946dd-290">연결된 그림 붙여넣기 옵션을 사용할 때 이미지가 예상보다 작아지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-290">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="946dd-291">공동 작업하는 동안 시트를 복사할 때 일부 서식이 손실되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-291">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


- <span data-ttu-id="946dd-292">통합 문서를 열 때 일부 노트가 예기치 않게 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-292">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


- <span data-ttu-id="946dd-293">.xls 또는 .xlt 형식으로 저장할 때 일부 피벗 테이블 형식으로 인해 통합 문서가 손상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-293">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-294">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-294">Outlook</span></span>

- <span data-ttu-id="946dd-295">외장 드라이브를 제거할 때 예기치 않은 앱이 닫히는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-295">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="946dd-296">사용자가 새 그룹을 만들고 나서 중복 일정 그룹이 나타나는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-296">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="946dd-297">공유 일정의 향상된 기능 사용자가 일정의 색을 노란색 또는 갈색으로 설정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-297">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="946dd-298">Outlook이 다시 시작될 때까지 탐색 창에 새로 추가된 일정이 나타나지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-298">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="946dd-299">ASCII가 아닌 문제를 해결했습니다.CSV로 내보낼 때 잘못 내보낼 문자입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-299">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="946dd-300">일부 사람이 보조 메일 계정과 연결된 서명에 액세스할 수 없는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-300">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="946dd-301">새 장치에서 Outlook을 구성한 후 클라우드 설정 기능 사용자가 기본 설정으로 재정의된 사용자 지정 설정을 볼 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-301">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="946dd-302">유니코드 콘텐츠를 포함하는 서명이 손상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-302">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="946dd-303">인라인 번역 사용자가 피드백을 제출할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-303">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="946dd-304">DRM 보호를 제거할 때 첨부 파일이 복제될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-304">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


- <span data-ttu-id="946dd-305">메일을 작성할 때 사용자가 이름 확인을 사용하여 연락처 그룹을 검색할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-305">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-306">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-306">PowerPoint</span></span>

- <span data-ttu-id="946dd-307">외장 드라이브를 제거할 때 예기치 않은 앱이 닫히는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-307">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="946dd-308">PowerPoint 슬라이드쇼 모드에서 라인 차트의 화살표가 예상대로 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-308">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


- <span data-ttu-id="946dd-309">애니메이션 및 오디오 책갈피 루핑 문제를 해결하고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-309">Fixes an issue with looping animations and audio bookmarks.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-310">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-310">Project</span></span>

- <span data-ttu-id="946dd-311">닫는 동안 Visio 작동이 중지되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-311">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="946dd-312">외장 드라이브를 제거할 때 예기치 않은 앱이 닫히는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-312">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="946dd-313">100% 완료된 작업이 99% 완료됨으로 되돌아오는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-313">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>


- <span data-ttu-id="946dd-314">JAWS를 실행하고 작업 정보 대화 상자로 이동하면 Project가 예기치 않게 종료될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-314">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>


- <span data-ttu-id="946dd-315">표시기 열이 첫 번째 열 지점에 없는 경우 요약 작업을 잘라내면 하위 작업도 제거된다는 경고가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-315">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="946dd-316">사용자가 작업표에서 작업 기능에 직접 추가를 선택한 경우 생성된 배정에 올바른 자원 가용성 단위를 사용하지 못할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-316">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


- <span data-ttu-id="946dd-317">Project Web App에서 로컬 파일로 프로젝트를 저장하는 경우 작업 분할이 잘못 생성될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-317">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="946dd-318">이 문제는 표준이 아닌 작업 시간이 있는 작업 달력을 사용하는 경우 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-318">This would happen if a task calendar with non-standard working times was being used.</span></span>


### <a name="publisher"></a><span data-ttu-id="946dd-319">게시자</span><span class="sxs-lookup"><span data-stu-id="946dd-319">Publisher</span></span>

- <span data-ttu-id="946dd-320">외장 드라이브를 제거할 때 예기치 않은 앱이 닫히는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-320">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="visio"></a><span data-ttu-id="946dd-321">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-321">Visio</span></span>

- <span data-ttu-id="946dd-322">닫는 동안 Visio 작동이 중지되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-322">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="946dd-323">외장 드라이브를 제거할 때 예기치 않은 앱이 닫히는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-323">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-324">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-324">Word</span></span>

- <span data-ttu-id="946dd-325">사용자가 MIP 보호 레이블에 액세스할 수 있는 ID에 로그인하지 않은 경우 MIP(Microsoft Information Protection) 레이블로 보호된 파일을 여는 것이 무기한 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-325">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="946dd-326">사용자는 로그인 프롬프트를 표시하기 위해 강제로 열기를 취소해야 하며, 해당 시점 이후에만 열기 작업이 성공합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-326">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="946dd-327">열려 있는/다운로드 중에 로그인 프롬프트가 표시될 수 있도록 허용하여 이 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-327">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="946dd-328">외장 드라이브를 제거할 때 예기치 않은 앱이 닫히는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-328">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="946dd-329">열기/다운로드 중에 로그인 프롬프트를 표시하도록 하여 이 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-329">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="946dd-330">문서를 공동 작성하는 경우 설명 순서가 변경되어도 활성 초안이 지워지지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-330">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="946dd-331">새로운 Word Commenting에서 Diction을 사용할 때 문제가 해결되었습니다. Comment 카드의 Dictation 버튼을 사용하여 올바르게 켜지거나 꺼집니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-331">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="946dd-332">스크롤 또는 확대/축소 애니메이션을 포함하는 스크롤 레이어와 관련된 렌더링 파이프라인의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-332">Fixes an issue in the rendering pipeline related to scrolling layers that contain scroll or zoom animations.</span></span>


- <span data-ttu-id="946dd-333">3D 효과가 있는 아이콘 및 SVG 그래픽에 적용된 색과 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-333">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="946dd-334">자동 저장에서 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-334">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="946dd-335">각주의 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-335">We fixed an issue in footnote.</span></span>


- <span data-ttu-id="946dd-336">RTL에 입력된 다중 회선 코멘트를 게시하여 오른쪽이 아닌 왼쪽에서 두 번째 회선과 이후 회선이 정렬되는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-336">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="946dd-337">여러 개의 메모를 정렬할 때와 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-337">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="946dd-338">소리 내어 읽기 작업 창 바로 가기 키의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-338">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


- <span data-ttu-id="946dd-339">내레이터에서 단락을 건너뛰는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-339">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="946dd-340">맞춤법 검사가 두 개의 다른 맞춤법 수정 컨텍스트 메뉴 사이에서 전환되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-340">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="946dd-341">서식 있는 텍스트 콘텐츠 컨트롤 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-341">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="946dd-342">숨겨진 단락 끝에 입력할 때 응용 프로그램이 중단될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-342">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="946dd-343">열에 텍스트가 겹칠 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-343">We fixed an issue where columns might have overlapping text.</span></span>


- <span data-ttu-id="946dd-344">책갈피와 관련된 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-344">We fixed an issue relating to bookmark.</span></span>


- <span data-ttu-id="946dd-345">공동으로 작성할 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-345">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-346">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-346">Office Suite</span></span>

- <span data-ttu-id="946dd-347">이제 OneDrive 위치는 그룹 정책 설정에 따라 적절하게 필터링됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-347">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="946dd-348">수학 방정식을 포함하는 텍스트에서 내레이터를 사용할 때 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-348">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="946dd-349">세션 0에서 실행되는 Office 앱 지원과 관련된 안정성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-349">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="946dd-350">세션 0에서 실행되는 Office 앱 지원과 관련된 안정성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-350">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="946dd-351">EMF 이미지를 로드할 때 발생할 수 있는 응답 없음과 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-351">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2102-march-03"></a><span data-ttu-id="946dd-353">버전 2102: 3월 3일</span><span class="sxs-lookup"><span data-stu-id="946dd-353">Version 2102: March 03</span></span>
<span data-ttu-id="946dd-354">*버전 2102(빌드 13801.20274)*</span><span class="sxs-lookup"><span data-stu-id="946dd-354">*Version 2102 (Build 13801.20274)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-356">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-356">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="946dd-357">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-357">Word</span></span>

- <span data-ttu-id="946dd-358">아이콘 및 SVG 그래픽에 테마 정보가 적용되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-358">Fixes an issue with theme information applied to icons and SVG graphics.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2102-march-01"></a><span data-ttu-id="946dd-360">버전 2102: 3월 1일</span><span class="sxs-lookup"><span data-stu-id="946dd-360">Version 2102: March 01</span></span>
<span data-ttu-id="946dd-361">*버전 2102(빌드 13801.20266)*</span><span class="sxs-lookup"><span data-stu-id="946dd-361">*Version 2102 (Build 13801.20266)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-363">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-363">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-364">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-364">Outlook</span></span>

- <span data-ttu-id="946dd-365">**Teams에 공유:** Teams 내 개인 또는 채널에 Outlook의 메시지를 공유합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-365">**Share to Teams:** Share messages from Outlook with a person or channel in Teams.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-368">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-368">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-369">Outlook</span></span>

- <span data-ttu-id="946dd-370">사용자가 새 그룹을 만들고 나서 중복 일정 그룹이 나타나는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-370">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="946dd-371">공유 일정의 향상된 기능 사용자가 일정의 색을 노란색 또는 갈색으로 설정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-371">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="946dd-372">일부 사용자가 메시지 창을 닫을 때 앱이 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-372">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="946dd-373">유니코드 콘텐츠를 포함하는 서명이 손상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-373">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="946dd-374">인라인 번역 사용자가 피드백을 제출할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-374">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2102-february-21"></a><span data-ttu-id="946dd-376">버전 2102: 2월 21일</span><span class="sxs-lookup"><span data-stu-id="946dd-376">Version 2102: February 21</span></span>
<span data-ttu-id="946dd-377">*버전 2102(빌드 13801.20182)*</span><span class="sxs-lookup"><span data-stu-id="946dd-377">*Version 2102 (Build 13801.20182)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-379">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-379">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-380">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-380">Outlook</span></span>

- <span data-ttu-id="946dd-381">**음성으로 메시지 초안 작성:** 새 받아쓰기 도구 모음, 음성 명령, 자동 입력 등을 사용하여 메시지를 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-381">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-382">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-382">Word</span></span>

- <span data-ttu-id="946dd-383">**음성으로 문서 초안 작성:** 새 받아쓰기 도구 모음, 음성 명령 및 자동 맞춤법을 사용하여 문서의 초안을 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-383">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-386">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-386">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-387">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-387">Excel</span></span>

- <span data-ttu-id="946dd-388">연결된 그림 붙여넣기 옵션을 사용할 때 이미지가 예상보다 작아지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-388">We fixed an issue which caused images to bee smaller than expected when using the Paste Linked Picture option.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2102-february-16"></a><span data-ttu-id="946dd-390">버전 2102: 2월 16일</span><span class="sxs-lookup"><span data-stu-id="946dd-390">Version 2102: February 16</span></span>
<span data-ttu-id="946dd-391">*버전 2102(빌드 13801.20160)*</span><span class="sxs-lookup"><span data-stu-id="946dd-391">*Version 2102 (Build 13801.20160)*</span></span>
* <span data-ttu-id="946dd-392">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-392">Various bugs and performance fixes.</span></span>

## <a name="version-2102-february-15"></a><span data-ttu-id="946dd-393">버전 2102: 2월 15일</span><span class="sxs-lookup"><span data-stu-id="946dd-393">Version 2102: February 15</span></span>
<span data-ttu-id="946dd-394">*버전 2102(빌드 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="946dd-394">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-396">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-396">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-397">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-397">Outlook</span></span>

- <span data-ttu-id="946dd-398">**받아쓰기 기능을 사용할 수 있는 추가 언어:** 이제 다음 7개 언어에서 받아쓰기 기능을 사용할 수 있습니다. 힌디어, 러시아어, 폴란드어, 포르투갈어(포르투갈), 한국어, 태국어, 중국어(대만)</span><span class="sxs-lookup"><span data-stu-id="946dd-398">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="946dd-399">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-399">Word</span></span>

- <span data-ttu-id="946dd-400">**받아쓰기 기능을 사용할 수 있는 추가 언어:** 이제 다음 7개 언어에서 받아쓰기 기능을 사용할 수 있습니다. 힌디어, 러시아어, 폴란드어, 포르투갈어(포르투갈), 한국어, 태국어, 중국어(대만)</span><span class="sxs-lookup"><span data-stu-id="946dd-400">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-403">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-403">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-404">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-404">Excel</span></span>

- <span data-ttu-id="946dd-405">사용자가 Excel 통합 문서를 PDF로 내보낼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-405">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-406">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-406">Word</span></span>

- <span data-ttu-id="946dd-407">공동으로 작성할 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-407">We fixed an issue in resolving conflicts while in coauthoring.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)


## <a name="version-2102-february-11"></a><span data-ttu-id="946dd-409">버전 2102: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="946dd-409">Version 2102: February 11</span></span>
<span data-ttu-id="946dd-410">*버전 2102(빌드 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="946dd-410">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-412">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-412">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="946dd-413">Teams</span><span class="sxs-lookup"><span data-stu-id="946dd-413">Teams</span></span>

- <span data-ttu-id="946dd-414">**Windows 및 Mac의 Edge 및 Chrome 브라우저에서 2x2 비디오** 사용자는 Windows 및 Mac의 Edge 및 Chrome 브라우저에서 팀 미팅에서 최대 4명의 참가자의 비디오를 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-414">**2x2 video on Edge and Chrome browsers on Windows and Mac** Users can see up to 4 participants' video in Teams meetings in Edge and Chrome browsers on Windows and Mac.</span></span> [<span data-ttu-id="946dd-415">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-415">Learn more</span></span>](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

## <a name="version-2102-february-08"></a><span data-ttu-id="946dd-417">버전 2102: 2월 8일</span><span class="sxs-lookup"><span data-stu-id="946dd-417">Version 2102: February 08</span></span>
<span data-ttu-id="946dd-418">*버전2102(빌드 13801.20084)*</span><span class="sxs-lookup"><span data-stu-id="946dd-418">*Version 2102 (Build 13801.20084)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-420">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-420">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-421">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-421">Outlook</span></span>

- <span data-ttu-id="946dd-422">**Microsoft Search 지원 작성(받는 사람\참조\숨은 참조) 제안:** 이제 Microsoft Search에서 받는 사람\참조 줄에 사용자 추가 기능을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-422">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-425">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-425">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-426">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-426">Access</span></span>

- <span data-ttu-id="946dd-427">이제 선택한 탭이 액세스에서 더 분명하게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-427">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="946dd-428">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-428">Excel</span></span>

- <span data-ttu-id="946dd-429">파일을 다시 열 때 불연속적인 셀 범위를 사용하는 특정 차트가 로드되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-429">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="946dd-430">특정 Windows 보안 공격 방지 설정(SimExec, 호출자 확인)을 사용 중인 경우 Excel이 예기치 않게 시작되지 않거나 닫히는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-430">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="946dd-431">차트에서 데이터 계열을 선택한 후 Excel이 응답하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-431">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="946dd-432">이름 정의 대화 상자에 이름을 추가하면 Excel이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-432">We fixed an issue where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


- <span data-ttu-id="946dd-433">자르기 작업 중에 비율이 유지되는 그림과 관련된 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-433">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-434">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-434">Outlook</span></span>

- <span data-ttu-id="946dd-435">사용자가 해당 옵션을 선택하지 않은 후 메일이 디지털 서명으로 전송될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-435">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="946dd-436">암호화 전용 옵션을 사용하여 보낸 전자 메일에 대해 암호화 아이콘이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-436">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-437">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-437">PowerPoint</span></span>

- <span data-ttu-id="946dd-438">색으로 이모지 표시와 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-438">Fixed an issue related to displaying emojis with color.</span></span>


- <span data-ttu-id="946dd-439">자르기 작업 중에 비율이 유지되는 그림과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-439">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="visio"></a><span data-ttu-id="946dd-440">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-440">Visio</span></span>

- <span data-ttu-id="946dd-441">CAD 스텐실에서 모양 렌더링과 관련된 문제가 이제 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-441">This issue on shape rendering from CAD stencils has now been fixed.</span></span> <span data-ttu-id="946dd-442">사용자는 최신 빌드에서 이 문제가 해결된 것을 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-442">Users will see the issue resolved in the latest build.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-443">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-443">Word</span></span>

- <span data-ttu-id="946dd-444">일정 시간 인터넷 연결이 끊기면 실시간 입력과 현재 상태가 복원되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-444">This fixes an issue that prevented real-time typing and presence from being restored after losing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="946dd-445">사용자가 설명에서 텍스트를 선택하면 Word는 이제 다른 설명에서 선택한 텍스트를 선택 취소합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-445">When a user selects text in a comment, Word now unselects selected text in other comments.</span></span>


- <span data-ttu-id="946dd-446">이제 설명 텍스트를 Word에서 Excel로 복사할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-446">Word now allows copying comment text into Excel.</span></span>


- <span data-ttu-id="946dd-447">VBA 매크로 ExportAsFixedFormat2를 실행할 때 "프레젠테이션(알 수 없는 구성원) 잘못된 값"이라는 오류와 함께 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-447">We fixed an issue when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>


- <span data-ttu-id="946dd-448">자르기 작업 중에 비율이 유지되는 그림과 관련된 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-448">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="946dd-449">링크가 있는 주석이 사용되지 않을 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-449">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="946dd-450">SharePoint Online으로 저장하는 데 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-450">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="946dd-451">Word 문서를 PDF로 내보내는 작업과 관련된 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-451">We fixed an issue in exporting Word document to PDF.</span></span>


- <span data-ttu-id="946dd-452">자동 복구 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-452">We fixed an issue with AutoRecover.</span></span>

- <span data-ttu-id="946dd-453">DRM으로 보호된 파일을 공동으로 작성할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-453">We fixed an issue when coauthoring with DRM protected files</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-454">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-454">Office Suite</span></span>

- <span data-ttu-id="946dd-455">글머리 기호를 이미지로 삽입하면 글머리 기호가 사라지는 PowerPoint에서의 버그를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-455">Fixing a bug in PowerPoint where inserting bullets as images would result in bullets disappearing.</span></span> <span data-ttu-id="946dd-456">이 문제가 해결됨에 따라 더 안정적으로 렌더링됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-456">This fix makes it so they render more reliably.</span></span>

- <span data-ttu-id="946dd-457">다른 로그인 계정에 대한 민감도 레이블을 표시해야 하는 경우에 Office에서 로그인한 계정에 대한 민감도 레이블이 표시되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-457">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2101-february-03"></a><span data-ttu-id="946dd-459">버전 2101: 2월 3일</span><span class="sxs-lookup"><span data-stu-id="946dd-459">Version 2101: February 03</span></span>
<span data-ttu-id="946dd-460">*버전 2101(빌드 13628.20330)*</span><span class="sxs-lookup"><span data-stu-id="946dd-460">*Version 2101 (Build 13628.20330)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-462">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-462">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-463">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-463">Outlook</span></span>

- <span data-ttu-id="946dd-464">OWA에 올바른 기본 서명을 표시하는 것과 관련된 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-464">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="946dd-465">암호화 전용 옵션을 사용하여 보낸 전자 메일에 대해 암호화 아이콘이 표시되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-465">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2101-february-02"></a><span data-ttu-id="946dd-467">버전 2101: 2월 2일</span><span class="sxs-lookup"><span data-stu-id="946dd-467">Version 2101: February 02</span></span>
<span data-ttu-id="946dd-468">*버전 2101(빌드 13628.20320)*</span><span class="sxs-lookup"><span data-stu-id="946dd-468">*Version 2101 (Build 13628.20320)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-470">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-470">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-471">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-471">Outlook</span></span>

- <span data-ttu-id="946dd-472">설정을 업데이트할 때 클라우드 설정 사용자가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-472">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2101-january-25"></a><span data-ttu-id="946dd-474">버전 2101: 1월 25일</span><span class="sxs-lookup"><span data-stu-id="946dd-474">Version 2101: January 25</span></span>
<span data-ttu-id="946dd-475">*버전 2101(빌드 13628.20274)*</span><span class="sxs-lookup"><span data-stu-id="946dd-475">*Version 2101 (Build 13628.20274)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-477">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-477">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-478">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-478">Excel</span></span>

- <span data-ttu-id="946dd-479">**정부 고객: 문서 및 전자 메일에 민감도 레이블 적용:** 이제 GCC 및 GCC-H 환경의 고객이 민감도 레이블 기능을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-479">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="946dd-480">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-480">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="946dd-481">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-481">Outlook</span></span>

- <span data-ttu-id="946dd-482">**정부 고객: 문서 및 전자 메일에 민감도 레이블 적용:** 이제 GCC 및 GCC-H 환경의 고객이 민감도 레이블 기능을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-482">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="946dd-483">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-483">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="946dd-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-484">PowerPoint</span></span>

- <span data-ttu-id="946dd-485">**정부 고객: 문서 및 전자 메일에 민감도 레이블 적용:** 이제 GCC 및 GCC-H 환경의 고객이 민감도 레이블 기능을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-485">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> <span data-ttu-id="946dd-486">[자세히 알아보기](/microsoft-365/compliance/sensitivity-labels).</span><span class="sxs-lookup"><span data-stu-id="946dd-486">[Learn more](/microsoft-365/compliance/sensitivity-labels).</span></span>


### <a name="word"></a><span data-ttu-id="946dd-487">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-487">Word</span></span>

- <span data-ttu-id="946dd-488">**정부 고객: 문서 및 전자 메일에 민감도 레이블 적용:** 이제 GCC 및 GCC-H 환경의 고객이 민감도 레이블 기능을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-488">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="946dd-489">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-489">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a><span data-ttu-id="946dd-490">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-490">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-491">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-491">Outlook</span></span>

- <span data-ttu-id="946dd-492">프로필에 큰 계층이 있는 공유 사서함 또는 위임된 사서함이 중단되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-492">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)



## <a name="version-2101-january-18"></a><span data-ttu-id="946dd-494">버전 2101: 1월 18일</span><span class="sxs-lookup"><span data-stu-id="946dd-494">Version 2101: January 18</span></span>
<span data-ttu-id="946dd-495">*버전 2101 (빌드 13628.20158)*</span><span class="sxs-lookup"><span data-stu-id="946dd-495">*Version 2101 (Build 13628.20158)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)



[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-499">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-499">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="946dd-500">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-500">Project</span></span>

- <span data-ttu-id="946dd-501">팀 플래너 보기에 작업에 대한 테두리가 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-501">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="946dd-502">끌어서 놓기 작업이 팀 플래너에서 작동하지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-502">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2101-january-13"></a><span data-ttu-id="946dd-504">버전 2101: 1월 13일</span><span class="sxs-lookup"><span data-stu-id="946dd-504">Version 2101: January 13</span></span>
<span data-ttu-id="946dd-505">*버전 2101(빌드 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="946dd-505">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)
### <a name="feature-updates"></a><span data-ttu-id="946dd-507">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-507">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="946dd-508">Teams</span><span class="sxs-lookup"><span data-stu-id="946dd-508">Teams</span></span>
- <span data-ttu-id="946dd-509">**추가 테마:** 테마를 데스크톱 및 웹 클라이언트에 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-509">**More themes:** New themes are now available for desktop and web clients.</span></span>

- <span data-ttu-id="946dd-510">**PPT 공유:** 공유 트레이에서 PowerPoint 파일을 선택하면 Teams의 발표자 보기가 자동으로 열립니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-510">**PPT Sharing:** Presenter View in Teams Once you select a PowerPoint file from the Teams Share Tray, Presenter View is opened automatically.</span></span> <span data-ttu-id="946dd-511">현재 슬라이드, 슬라이드 노트 및 간단한 추가 슬라이드 탐색을 위해 데크의 모든 슬라이드의 축소판 그림 스트립을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-511">You can see the current slide, the slide notes, and a thumbnail strip of all the slides in the deck for easy ad-hoc slide navigation.</span></span> <span data-ttu-id="946dd-512">이 보기는 완전히 뒤에 숨겨져 있으며, 발표자가 제어할 수 있는 개인 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-512">This view is completely behind the scenes, and it’s private to the presenter in control.</span></span> <span data-ttu-id="946dd-513">대상 그룹은 현재 슬라이드(큰 빨간색 상자에 강조 표시) 또는 이동하기로 선택한 슬라이드(대상 사용자에 의해 대상 탐색이 잠겨 있지 않은 경우)만 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-513">Your audience can only see your current slide (highlighted in the big red box), or the slide that they choose to navigate to (if audience navigation is not locked by you).</span></span> 

- <span data-ttu-id="946dd-514">**Mac에서 데스크톱 또는 창을 공유할 때 컴퓨터 사운드 포함** Mac에서 Mac용 Teams에서 바탕 화면 또는 창을 공유할 때, 이제 미팅에 참여한 사람들이 컴퓨터에서 오디오 재생을 들을 수 있도록 컴퓨터의 소리를 포함할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-514">**Include computer sound when desktop or window sharing on Mac** When you share a desktop or window from Teams on Mac, you can now include your computer's sound so people that have joined the meeting can hear the audio playing out of your computer.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)
<br/>

## <a name="version-2101-january-09"></a><span data-ttu-id="946dd-516">버전 2101: 1월 9일</span><span class="sxs-lookup"><span data-stu-id="946dd-516">Version 2101: January 09</span></span>
<span data-ttu-id="946dd-517">*버전 2101(빌드 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="946dd-517">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-519">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-519">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-520">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-520">Outlook</span></span>

- <span data-ttu-id="946dd-521">**한 번의 클릭으로 작문 제안:** 한 번의 클릭으로 작문 제안을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-521">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="946dd-522">편집기는 맞춤법과 문법을 수정하며 글을 다듬는 데 필요한 아이디어를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-522">Editor corrects spelling and grammar and gives you ideas for refining your writing.</span></span> [<span data-ttu-id="946dd-523">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-523">Learn more</span></span>](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br /><span data-ttu-id="946dd-524">[블로그 게시물](https://insider.office.com/ko-KR/blog/microsoft-editor-gets-an-upgrade)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-524">See details in [blog post](https://insider.office.com/ko-KR/blog/microsoft-editor-gets-an-upgrade)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-527">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-527">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-528">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-528">Outlook</span></span>

- <span data-ttu-id="946dd-529">일부 사용자가 특정 검색 시나리오에서 Outlook이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-529">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2101-january-07"></a><span data-ttu-id="946dd-531">버전 2101: 1월 7일</span><span class="sxs-lookup"><span data-stu-id="946dd-531">Version 2101: January 07</span></span>
<span data-ttu-id="946dd-532">*버전 2101(빌드 13628.20030)*</span><span class="sxs-lookup"><span data-stu-id="946dd-532">*Version 2101 (Build 13628.20030)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-534">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-534">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-535">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-535">Excel</span></span>

- <span data-ttu-id="946dd-536">**여러 시트를 동시에 숨기기 취소:** 한 번에 여러 시트를 숨길 필요가 없습니다. 한 번에 여러 시트를 숨길 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-536">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="946dd-537">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-537">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- <span data-ttu-id="946dd-538">**향상된 조건부 서식 대화 상자:** 조건부 서식 대화 상자의 크기를 조정할 수 있으며, 이제 한 번의 클릭으로 규칙을 복제할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-538">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="946dd-539">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-539">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-542">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-542">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-543">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-543">Excel</span></span>

- <span data-ttu-id="946dd-544">Excel이 새 버전의 파일을 사용할 수 있다는 메시지 표시줄을 잘못 표시하여 사용자가 변경 내용을 통합 문서 사본에 저장하거나 변경 내용을 취소하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-544">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="946dd-545">Selection.Parent.Copy 요청 후 구분 기호 전환 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-545">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


- <span data-ttu-id="946dd-546">피벗 테이블에서 서식 스타일을 적용할 때 성능이 향상되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-546">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


- <span data-ttu-id="946dd-547">Excel 4.0 매크로가 포함된 Excel 추가 기능 파일을 열 때 메시지 표시 없이 매크로를 사용하지 않는 상태로 둘 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-547">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="946dd-548">Excel에서 차트를 복사하여 Word에 붙여넣을 때 소수점 및 천 단위 구분 기호 설정을 같이 붙여넣도록 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-548">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="946dd-549">잘못된 파일 특성(만든 시간, 수정된 시간 등)이 있는 UNC 파일을 열 때 Excel이 예기치 않게 닫히는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-549">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="946dd-550">STOCKHISTORY 함수를 사용하는 경우 "리소스 부족" 알림을 발생시킬 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-550">Fixed an issue which could cause an "out of resources" alert when using the STOCKHISTORY function.</span></span>


- <span data-ttu-id="946dd-551">FuzzyClustering dll이 PQ dlls 목록에 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-551">Added a FuzzyClustering dll to PQ dlls list.</span></span>


- <span data-ttu-id="946dd-552">이 변경으로 SVG 이미지의 윤곽선 색을 변경하는 것과 관련된 문제를 해결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-552">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="946dd-553">PowerPoint에서 포함된 Excel 범위 미리 보기에 잘못된 크기가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-553">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>


### <a name="onenote"></a><span data-ttu-id="946dd-554">OneNote</span><span class="sxs-lookup"><span data-stu-id="946dd-554">OneNote</span></span>

- <span data-ttu-id="946dd-555">이 변경 사항으로 OneNote에 영향을 미치는 렌더링 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-555">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-556">Outlook</span></span>

- <span data-ttu-id="946dd-557">사용자가 Word에서 메일 병합을 시작할 때 액세스를 허용하는 데 걸리는 시간을 지정할 수 없어 과도한 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-557">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="946dd-558">이렇게 변경하면 Outlook에서 Exchange Online 보관 사서함을 최종 사용자에 표시하지 않는 Exchange 서버 설정을 활용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-558">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


- <span data-ttu-id="946dd-559">사용자가 상환 기반 추가 기능을 사용하는 경우 Outlook이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-559">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


- <span data-ttu-id="946dd-560">사용자가 검색할 범주를 두 개 이상 선택할 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-560">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="946dd-561">다른 약속에서 이벤트를 복사할 때 일부 일정 항목의 시작 시간이 예기치 않게 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-561">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


- <span data-ttu-id="946dd-562">일반 텍스트 S/MIME 메시지가 전송 시 왜곡되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-562">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-563">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-563">PowerPoint</span></span>

- <span data-ttu-id="946dd-564">이 변경 사항으로 텍스트 작업을 수행하는 도형 병합과 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-564">This change addresses an issue with Merge Shapes working with text.</span></span>


- <span data-ttu-id="946dd-565">이 변경으로 SVG 이미지의 윤곽선 색을 변경하는 것과 관련된 문제를 해결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-565">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="946dd-566">슬라이드 쇼에서 배경 비디오 재생을 반복하여 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-566">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="946dd-567">QAT에서 추가한 글꼴 크기 명령에 대한 문제를 해결 했습니다. 이 문제는 업데이트하는 동안 가장 가까운 정의된 글꼴 크기로 자동 완성됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-567">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-568">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-568">Project</span></span>

- <span data-ttu-id="946dd-569">리소스의 최대 단위에서 최대 단위에 대한 최신 업데이트를 항상 반영하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-569">Fixed an issue where a resource's max units would not always reflect the latest update to max units.</span></span>


### <a name="visio"></a><span data-ttu-id="946dd-570">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-570">Visio</span></span>

- <span data-ttu-id="946dd-571">최근 회귀 때문에 발생한 문제입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-571">The issue occurred due to a recent regression.</span></span> <span data-ttu-id="946dd-572">문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-572">We have resolved the issue.</span></span> <span data-ttu-id="946dd-573">이제 "웹 페이지로 저장" 대화 상자는 사용자 입력에 따라 필드가 제대로 채워지고 사용자가 파일을 웹 페이지로 원활하게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-573">"Save as Web Page" dialog will now have the fields correctly populated as per the user inputs and users can seamlessly save their files as web pages.</span></span>


- <span data-ttu-id="946dd-574">이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-574">This issue has been fixed.</span></span> <span data-ttu-id="946dd-575">이제 Visio 파일을 PowerPoint와 Word와 같은 다른 Office 응용 프로그램의 개체로 포함하고 이러한 응용 프로그램 내에서 원활하게 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-575">You can now embed Visio files as objects in other Office applications like PowerPoint and Word and seamlessly access them from within these applications.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-576">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-576">Word</span></span>

- <span data-ttu-id="946dd-577">사용자 지정 해시 설정을 포함하는 컴퓨터에서 sha512 외의 해시 설정을 사용하여 공동 작업 세션에 도달했을 때 문제가 발생하던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-577">Fixed an issue where machines with custom hash settings were running in to issues when they got into a collab session with a hash setting other than sha512.</span></span>


- <span data-ttu-id="946dd-578">이 변경으로 SVG 이미지의 윤곽선 색을 변경하는 것과 관련된 문제를 해결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-578">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="946dd-579">@멘션을 사용하여 댓글 게시물을 편집할 때의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-579">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="946dd-580">최신 메모를 더 강력하게 만들도록 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-580">Fixed an issue to make Modern comments more robust.</span></span>


- <span data-ttu-id="946dd-581">콘텐츠 컨트롤에서 편집할 수 없는 것으로 표시된 최신 메모를 삭제하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-581">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>


- <span data-ttu-id="946dd-582">메모 카드 아래에 입력할 때 애니메이션을 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-582">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="946dd-583">메모 카드의 회신 상자가 화면에 표시되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-583">Fixes an issue where the reply box on a comment card is off the screen.</span></span>


- <span data-ttu-id="946dd-584">페이지 맨 위에 표시된 메모 카드의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-584">Fixes an issue with a comment card displaying at top of page.</span></span>


- <span data-ttu-id="946dd-585">텍스트가 화면 밖으로 스크롤될 수 있는 메모의 버그를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-585">Fixes bug in comments where text can scroll off screen.</span></span>


- <span data-ttu-id="946dd-586">메모 창에서 중첩된 스크롤 막대와 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-586">Fix and issue with nested scrollbars in the comments pane.</span></span>


- <span data-ttu-id="946dd-587">새 Word 인스턴스를 만들 때 메모 초안이 사라집니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-587">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="946dd-588">숨겨진 텍스트가 있는 PDF에 문서를 저장할 때 Word가 걸려 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-588">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2012-january-04"></a><span data-ttu-id="946dd-590">버전 2012: 1월 4일</span><span class="sxs-lookup"><span data-stu-id="946dd-590">Version 2012: January 04</span></span>
<span data-ttu-id="946dd-591">*버전 2012(빌드 13530.20316)*</span><span class="sxs-lookup"><span data-stu-id="946dd-591">*Version 2012 (Build 13530.20316)*</span></span>
* <span data-ttu-id="946dd-592">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-592">Various bugs and performance fixes.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-594">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-594">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-595">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-595">Excel</span></span>

- <span data-ttu-id="946dd-596">**필수 레이블 지정:** 필수 레이블 지정 정책 집합을 사용하는 사용자. 해당 관리자는 문서와 전자 메일에 레이블을 지정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-596">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-597">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-597">PowerPoint</span></span>

- <span data-ttu-id="946dd-598">**필수 레이블 지정:** 필수 레이블 지정 정책 집합을 사용하는 사용자. 해당 관리자는 문서와 전자 메일에 레이블을 지정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-598">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-599">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-599">Word</span></span>

- <span data-ttu-id="946dd-600">**필수 레이블 지정:** 필수 레이블 지정 정책 집합을 사용하는 사용자. 해당 관리자는 문서와 전자 메일에 레이블을 지정해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-600">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2012-december-28"></a><span data-ttu-id="946dd-602">버전 2012: 12월 28일</span><span class="sxs-lookup"><span data-stu-id="946dd-602">Version 2012: December 28</span></span>
<span data-ttu-id="946dd-603">*버전 2012(빌드 13530.20264)*</span><span class="sxs-lookup"><span data-stu-id="946dd-603">*Version 2012 (Build 13530.20264)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-605">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-605">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-606">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-606">Outlook</span></span>

- <span data-ttu-id="946dd-607">일부 고객이 일정을 로드하는 동안 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-607">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2012-december-21"></a><span data-ttu-id="946dd-609">버전 2012: 12월 21일</span><span class="sxs-lookup"><span data-stu-id="946dd-609">Version 2012: December 21</span></span>
<span data-ttu-id="946dd-610">*버전 2012(빌드 13530.20218)*</span><span class="sxs-lookup"><span data-stu-id="946dd-610">*Version 2012 (Build 13530.20218)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-612">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-612">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-613">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-613">Excel</span></span>

- <span data-ttu-id="946dd-614">**M365 관리자에게 민감도 레이블에 대한 감사 데이터를 보냄:** 사용자가 문서 및 이메일에 민감도 레이블을 적용, 변경 또는 제거하면 Office는 관리자가 볼 수 있도록 감사 데이터를 M365 감사 백엔드로 보냅니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-614">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="946dd-615">이는 관리자 혜택을 위한 자동 기능(UI 없음)입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-615">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-616">Outlook</span></span>

- <span data-ttu-id="946dd-617">**연달아 있는 모임 사이에 시간 넣기:** 모임이 기본적으로 5~10분 일찍 끝나도록 설정하여 참석자에게 잠시 숨을 돌리거나 장소를 이동할 시간을 줄 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-617">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="946dd-618">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-618">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="946dd-619">**M365 관리자에게 민감도 레이블에 대한 감사 데이터를 보냄:** 사용자가 문서 및 이메일에 민감도 레이블을 적용, 변경 또는 제거하면 Office는 관리자가 볼 수 있도록 감사 데이터를 M365 감사 백엔드로 보냅니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-619">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="946dd-620">이는 관리자 혜택을 위한 자동 기능(UI 없음)입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-620">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-621">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-621">PowerPoint</span></span>

- <span data-ttu-id="946dd-622">**M365 관리자에게 민감도 레이블에 대한 감사 데이터를 보냄:** 사용자가 문서 및 이메일에 민감도 레이블을 적용, 변경 또는 제거하면 Office는 관리자가 볼 수 있도록 감사 데이터를 M365 감사 백엔드로 보냅니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-622">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="946dd-623">이는 관리자 혜택을 위한 자동 기능(UI 없음)입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-623">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-624">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-624">Word</span></span>

- <span data-ttu-id="946dd-625">**M365 관리자에게 민감도 레이블에 대한 감사 데이터를 보냄:** 사용자가 문서 및 이메일에 민감도 레이블을 적용, 변경 또는 제거하면 Office는 관리자가 볼 수 있도록 감사 데이터를 M365 감사 백엔드로 보냅니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-625">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="946dd-626">이는 관리자 혜택을 위한 자동 기능(UI 없음)입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-626">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-629">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-629">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="946dd-630">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-630">PowerPoint</span></span>

- <span data-ttu-id="946dd-631">QAT에서 추가한 글꼴 크기 명령이 업데이트하는 동안 가장 가까운 정의된 글꼴 크기로 자동 완성되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-631">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2012-december-14"></a><span data-ttu-id="946dd-633">버전 2012: 12월 14일</span><span class="sxs-lookup"><span data-stu-id="946dd-633">Version 2012: December 14</span></span>
<span data-ttu-id="946dd-634">*버전 2012(빌드 13530.20144)*</span><span class="sxs-lookup"><span data-stu-id="946dd-634">*Version 2012 (Build 13530.20144)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-636">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-636">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-637">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-637">Outlook</span></span>

- <span data-ttu-id="946dd-638">**클라우드에서 Outlook 설정: 자동 회신, 중요 받은 편지함, 개인 정보 보호 등과 같이 Windows용 Outlook 설정을 선택하고 모든 PC에서 사용할 수 있습니다** .</span><span class="sxs-lookup"><span data-stu-id="946dd-638">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-641">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-641">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="946dd-642">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-642">Office Suite</span></span>

- <span data-ttu-id="946dd-643">최적화된 이진 크기</span><span class="sxs-lookup"><span data-stu-id="946dd-643">Optimized binary size.</span></span>


- <span data-ttu-id="946dd-644">Anaheim 웹 보기는 아직 WIP(Windows Information Protection)를 지원 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-644">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="946dd-645">이 수정 기능은 WIP를 사용하는 환경의 하위 웹에 Office 추가 플랫폼을 다시 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-645">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="946dd-646">이 기능은 고객의 컴퓨터 환경에 따라 Edge Spartan 웹 보기 또는 Trident 웹 보기가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-646">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="946dd-647">하위 수준 WebViews 모두 WIP를 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-647">Both down level WebViews support WIP.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2012-december-07"></a><span data-ttu-id="946dd-649">버전 2012: 12월 7일</span><span class="sxs-lookup"><span data-stu-id="946dd-649">Version 2012: December 07</span></span>
<span data-ttu-id="946dd-650">*버전 2012(빌드 13530.20064)*</span><span class="sxs-lookup"><span data-stu-id="946dd-650">*Version 2012 (Build 13530.20064)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-652">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-652">Feature updates</span></span>

### <a name="teams"></a><span data-ttu-id="946dd-653">Teams</span><span class="sxs-lookup"><span data-stu-id="946dd-653">Teams</span></span>

- <span data-ttu-id="946dd-654">**이제 Windows 기본 알림이 Teams에서 지원됨:** 이제 사용자는 배너에 구축된 Teams나 Windows 기본 배너를 통해 원하는 알림 전달 방법을 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-654">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through Teams built-in banners or the Windows native banners.</span></span>


- <span data-ttu-id="946dd-655">**Citrix 및 VMWare VDI의 Teams 모임 2x2 갤러리 보기:** VDI 2x2 갤러리 보기 기능을 사용하면 Teams 클라이언트가 VDI 최적화 모드인 경우 Citrix, VMWare에서 VDI 클라이언트의 2x2 갤러리 보기로 최대 4개의 참석자 비디오를 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-655">**Teams Meetings 2x2 Gallery View in Citrix and VMWare VDI:** Teams on VDI 2x2 Gallery View feature will enable to view up to four attendees videos in 2x2 Gallery View on VDI clients from Citrix, VMWare when Teams client in VDI optimized mode.</span></span>


- <span data-ttu-id="946dd-656">**모임 반응:**  모임 반응은 모임에서 상호 작용하는 새로운 방법입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-656">**Meeting Reactions:**  Meeting reactions are a new way to interact in meetings.</span></span> <span data-ttu-id="946dd-657">참가자는 공유 중인 콘텐츠에 스트림으로 표시되는 반응을 보낼 수 있으며, 모임 단계에 표시되는 경우 반응을 보낸 개인에게 보낼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-657">Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage.</span></span> 


- <span data-ttu-id="946dd-658">**웹 모임용 Together 모드 및 대형 갤러리** 대형 갤러리를 사용하면 한 번에 최대 49명의 다른 사람들의 비디오를 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-658">**Together Mode and Large Gallery for Web Meetings** Large Gallery enables you to see the videos of up to 49 other people at once.</span></span> <span data-ttu-id="946dd-659">이 옵션은 10명 이상의 사용자가 카메라를 켰을 때 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-659">This option is available when at least ten people have their cameras turned on.</span></span> <span data-ttu-id="946dd-660">Together 모드를 사용하면 모임의 모든 사용자와 동일한 공유 공간에 있는 것 같은 느낌을 들게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-660">Together mode lets you feel like you're in the same shared space with everyone in the meeting.</span></span> <span data-ttu-id="946dd-661">모임에 5명 이상이 있는 경우 Together 모드를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-661">Together mode is available when there are at least five people in the meeting.</span></span> 


- <span data-ttu-id="946dd-662">**통화 병합** 통화 병합을 사용하면 사용자가 걸고 있는 새 통화나 새 수신 전화를 1-1 또는 그룹 통화에 병합할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-662">**Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call.</span></span> <span data-ttu-id="946dd-663">이는 Teams VOIP 통화 및 PSTN 통화에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-663">This applies to Teams VOIP calls and PSTN calls.</span></span> 


### <a name="visio"></a><span data-ttu-id="946dd-664">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-664">Visio</span></span>

- <span data-ttu-id="946dd-665">**새 Azure 스텐실 및 셰이프:** 최신 Azure 다이어그램을 작성하는 데 도움이 되도록 스텐실을 더 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-665">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="946dd-666">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-666">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-669">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-669">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-670">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-670">Excel</span></span>

- <span data-ttu-id="946dd-671">일부 리본 요소가 중국어 간체로 지역화되지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-671">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="946dd-672">Excel 업데이트 시 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-672">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


- <span data-ttu-id="946dd-673">OneDrive 로컬 동기화 폴더에서 파일을 삽입하는 경우 개체 삽입 명령에 올바른 아이콘이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-673">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="946dd-674">덮어쓰기 모드에서 편집할 때 IME를 사용해야 하는 언어의 편집이 제대로 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-674">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="946dd-675">공동 작성 시 파일의 새 버전을 알리는 메시지 표시줄이 일부 사용자에게 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-675">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="946dd-676">수식 뷰에서 데이터를 복사하고 붙여넣을 때 Excel이 예기치 않게 닫히는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-676">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


- <span data-ttu-id="946dd-677">자동 저장을 사용할 수 없는 경우 경고의 도움말 문서에 대한 하이퍼링크가 손상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-677">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="946dd-678">엑셀이 특정 언어로 실행되는 동안 데이터를 입력할 때 Excel이 중지될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-678">We fixed an issue where when entering data while Excel is running in certain languages could cause Excel to stop working.</span></span>


- <span data-ttu-id="946dd-679">이 변경 사항은 수식 내에서 글꼴을 올바르게 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-679">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="946dd-680">이렇게 하면 Power Pivot가 탭으로 구분된 텍스트 파일을 올바르게 가져올 수 없는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-680">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-681">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-681">Outlook</span></span>

- <span data-ttu-id="946dd-682">작업 상태 보고서에서 수신자 필드를 비어 있게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-682">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


- <span data-ttu-id="946dd-683">MailItem.BeforeAttachmentAdd 이벤트를 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-683">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="946dd-684">Outlook 이외의 응용 프로그램에서 Outlook 메일을 보낼 때 사용자에게 몇 가지 문제가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-684">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="946dd-685">초안에 저장할 때 SmartLinks의 서식이 손실되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-685">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="946dd-686">Zip 파일에서 열린 메시지에 첨부 파일을 추가하면 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-686">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-687">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-687">PowerPoint</span></span>

- <span data-ttu-id="946dd-688">Word에서 Powerpoint로 수식을 복사/붙여넣기를 할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-688">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="946dd-689">이 변경 사항은 잉크 분석 중에 발생한 시간 초과와 관련된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-689">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="946dd-690">이 변경사항은 애니메이션 GIF 사용자 인터페이스의 문법 오류를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-690">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="946dd-691">이 변경 사항은 특정 지오메트리를 사용하여 형상 병합 작업을 적용할 때 경로 채우기 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-691">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="946dd-692">이 변경 사항은 수식 내에서 글꼴을 올바르게 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-692">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="946dd-693">이 변경 사항은 비디오 로드 중에 발생할 수 있는 처리 오류 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-693">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="946dd-694">Slide.Shapes.AddMediaObject2가 레거시 비디오 형식(MPG-1, Mpeg-2)과 충돌하는 VBA 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-694">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="946dd-695">공동 작업자 대한 추가 정보가 있을 때 알 수 없는 공동 작업자의 현재 상태 표시기가 완전히 새로워지지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-695">We fixed an issue where an unknown coauthor's presence indicator does not get completely refreshed when more information about the coauthor is available.</span></span>


- <span data-ttu-id="946dd-696">눈금자가 켜진 상태에서 슬라이드 뷰의 크기를 조정할 때 Null 포인터가 참조 해제되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-696">Fixed a null pointer being dereferenced when slide view is resized with ruler turned on.</span></span>


- <span data-ttu-id="946dd-697">문서 복구 작업 후에도 손상된 PowerPoint 파일이 올바르게 열리지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-697">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-698">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-698">Project</span></span>

- <span data-ttu-id="946dd-699">사용자가 업데이트된 정보를 사용하여 저장된 것으로 고려되는 프로젝트를 여는 경우 업데이트가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-699">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


- <span data-ttu-id="946dd-700">결과물이 연결된 SharePoint 사이트가 더 이상 존재하지 않는 경우, 결과물에 대한 종속성을 삭제할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-700">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="946dd-701">리소스가 많은 프로젝트를 여는 데 시간이 오래 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-701">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="946dd-702">작업에 연결된 할당되지 않은 과제가 여러 개 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-702">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="946dd-703">대규모 프로젝트에서 작업 이름을 입력하는 속도가 매우 느릴 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-703">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>


- <span data-ttu-id="946dd-704">로드의 특정 부분에 프로젝트 파일에 문제가 있는 경우 특정 프로젝트를 열 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-704">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-705">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-705">Word</span></span>

- <span data-ttu-id="946dd-706">서식 있는 텍스트로 붙여넣기보다 일반 텍스트로 붙여넣기를 선호하는 경우가 많습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-706">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="946dd-707">이 상황에 맞는 메뉴 수정사항을 사용하여 일반 텍스트로 붙여넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-707">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="946dd-708">그렇지 않으면 사용자는 메모장과 같은 일반 텍스트 편집기에 복사한 다음 메모장에서 원하는 대상 앱으로 복사해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-708">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>


- <span data-ttu-id="946dd-709">Word에서 Powerpoint로 수식을 복사/붙여넣기를 할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-709">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="946dd-710">이 변경 사항은 문서 편집 시 커서 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-710">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="946dd-711">확대/축소하는 동안 사진이 흐릿해지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-711">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="946dd-712">긴 하이퍼링크가 잘리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-712">We fixed an issue where long hyperlinks were getting truncated.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-713">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-713">Office Suite</span></span>

- <span data-ttu-id="946dd-714">Office 제품군 이전 버전에서 새 Office 버전을 설치하면 레지스트리 항목이 누락되어 전원 쿼리를 사용할 수 없는 등의 기능이 누락될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-714">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2011-december-01"></a><span data-ttu-id="946dd-716">버전 2011: 12월 1일</span><span class="sxs-lookup"><span data-stu-id="946dd-716">Version 2011: December 01</span></span>
<span data-ttu-id="946dd-717">*버전 2011(빌드 13426.20306)*</span><span class="sxs-lookup"><span data-stu-id="946dd-717">*Version 2011 (Build 13426.20306)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-719">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-719">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-720">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-720">Outlook</span></span>

- <span data-ttu-id="946dd-721">**모든 온라인 모임** : 새 설정으로 온라인 모임을 더욱 쉽게 예약하여 모든 모임을 기본적으로 온라인으로 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-721">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-724">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-724">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-725">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-725">Outlook</span></span>

- <span data-ttu-id="946dd-726">일부 모임에서 다른 참석자가 모임을 전달할 때 기존 참석자가 모임이 취소되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-726">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="946dd-727">하나 이상의 서명이 구성되었음에도 불구하고 일부 사용자에게 서명 드롭다운이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-727">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-728">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-728">Project</span></span>

- <span data-ttu-id="946dd-729">로드의 특정 부분에 프로젝트 파일에 문제가 있는 경우 특정 프로젝트를 열 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-729">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2011-november-24"></a><span data-ttu-id="946dd-731">버전 2011: 11월 24일</span><span class="sxs-lookup"><span data-stu-id="946dd-731">Version 2011: November 24</span></span>
<span data-ttu-id="946dd-732">*버전 2011(빌드 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="946dd-732">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-734">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-734">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="946dd-735">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-735">Office Suite</span></span>

- <span data-ttu-id="946dd-736">Word에서 Powerpoint로 수식을 복사/붙여넣기를 할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-736">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2011-november-21"></a><span data-ttu-id="946dd-738">버전 2011: 11월 21일</span><span class="sxs-lookup"><span data-stu-id="946dd-738">Version 2011: November 21</span></span>
<span data-ttu-id="946dd-739">*버전 2011(빌드 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="946dd-739">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-741">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-741">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="946dd-742">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-742">PowerPoint</span></span>

- <span data-ttu-id="946dd-743">**비디오 라이브러리:** 앱에서 사용 가능한 엄선된 로열티 없는 비디오 영상 라이브러리로 문서의 수준을 높이세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-743">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-746">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-746">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-747">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-747">Outlook</span></span>

- <span data-ttu-id="946dd-748">MailItem.BeforeAttachmentAdd 이벤트를 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-748">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="946dd-749">IDataObject 작업(예: 끌어서 놓기, 클립보드)에서 첨부 파일에 대한 filetime 포함을 사용하지 않도록 설정할 수 있는 regkey를 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-749">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="946dd-750">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="946dd-750">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="946dd-751">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="946dd-751">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="946dd-752">0 = filetimes가 제외됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-752">0 = filetimes are excluded.</span></span> <span data-ttu-id="946dd-753">1 = (기본값)filetimes가 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-753">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="946dd-754">Azure Information Protection의 보호 레이블을 사용하여 메시지에 회신할 때 인라인 이미지를 사라지게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-754">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2011-november-18"></a><span data-ttu-id="946dd-756">버전 2011: 11월 18일</span><span class="sxs-lookup"><span data-stu-id="946dd-756">Version 2011: November 18</span></span>
<span data-ttu-id="946dd-757">*버전 2011(빌드 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="946dd-757">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="946dd-758">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-758">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="946dd-759">버전 2011: 11월 16일</span><span class="sxs-lookup"><span data-stu-id="946dd-759">Version 2011: November 16</span></span>
<span data-ttu-id="946dd-760">*버전 2011(빌드 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="946dd-760">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-762">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-762">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-763">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-763">Outlook</span></span>

- <span data-ttu-id="946dd-764">**모든 장치에 같은 서명:** 서명이 클라우드에 저장됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-764">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="946dd-765">서명을 한 번 만들면 모든 장치의 Outlook에서 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-765">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-768">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-768">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-769">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-769">Outlook</span></span>

- <span data-ttu-id="946dd-770">작업에 대해 상황 보고서를 보낼 때 To 필드가 비어 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-770">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-771">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-771">PowerPoint</span></span>

- <span data-ttu-id="946dd-772">Slide.Shapes.AddMediaObject2가 레거시 비디오 형식(MPG-1, Mpeg-2)과 충돌하는 VBA 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-772">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2011-november-09"></a><span data-ttu-id="946dd-774">버전 2011: 11월 9일</span><span class="sxs-lookup"><span data-stu-id="946dd-774">Version 2011: November 09</span></span>
<span data-ttu-id="946dd-775">*버전 2011(빌드 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="946dd-775">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-777">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-777">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-778">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-778">Excel</span></span>

- <span data-ttu-id="946dd-779">**쿼리에서 Power Platform 데이터 흐름 만들기:** 이제 새 Power Platform 데이터 흐름을 만드는 데 사용할 수 있는 파워 쿼리 템플릿으로 쿼리를 내보낼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-779">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-782">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-782">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-783">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-783">Access</span></span>

- <span data-ttu-id="946dd-784">동기화된 OneDrive 폴더에서 쿼리를 내보내려고 할 때 일부 사용자에게 “시스템 리소스가 초과했습니다.”라는 오류가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-784">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="946dd-785">양식 창 간의 '자동' 전환이 다른 양식으로 전환되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-785">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="946dd-786">Office가 아닌 응용 프로그램에서 DAO를 사용할 경우 응용 프로그램이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-786">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="946dd-787">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-787">Excel</span></span>

- <span data-ttu-id="946dd-788">COM 추가 기능을 사용하도록 설정하여 다른 이름으로 저장 작업 후 파일 이름이 변경되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-788">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="946dd-789">Oracle 데이터베이스에 대한 연결을 사용하는 경우의 파워 피벗 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-789">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="946dd-790">Excel 데이터 모델에 잘못된 측정값이 정의된 경우, 잘못된/오해의 소지가 있는 오류 메시지와 함께 자동 저장에 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-790">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="946dd-791">MTR 계산 및 그룹 정책 개체 업데이트(예: 원격 그룹 정책 새로 고침을 통해)가 트리거되는 경우 Excel이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-791">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="946dd-792">사용자가 SharePoint에서 직접 atomsvc(UTF8+BOM) 파일을 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-792">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="946dd-793">프리젠테이션 영역을 확대/축소하여 확대된 선택 영역과 마우스 포인터 사이에 간격이 생긴 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-793">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="946dd-794">Excel 통합 문서를 Word 문서에 삽입하면 Word가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-794">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-795">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-795">Outlook</span></span>

- <span data-ttu-id="946dd-796">첨부 파일을 추가하거나 저장할 때 Outlook이 산발적으로 작동을 멈추게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-796">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="946dd-797">이미지 첨부 파일에 대한 빠른 인쇄에서 다음 오류 메시지가 발생하는 문제를 해결했습니다. “Windows에서 이 그림을 찾을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-797">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="946dd-798">위치를 확인한 후 다시 시도하세요".</span><span class="sxs-lookup"><span data-stu-id="946dd-798">Check the location, and then try again".</span></span>


- <span data-ttu-id="946dd-799">일부 사용자가 온라인으로 작업하기 위해 수동으로 선택할 때까지 Outlook이 오프라인 상태에서 시작하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-799">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="946dd-800">모임 장소에서 다른 위치(예: 브라우저)로 복사한 URL을 붙여넣는 경우 URL 마지막에 세미콜론이 포함되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-800">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="946dd-801">사용자가 기본 인증의 Microsoft 365 그룹 일정에서 약속을 삭제할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-801">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="946dd-802">애칭 캐시를 로드할 때 Outlook을 시작하지 못한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-802">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="946dd-803">옵션이 회색으로 처리되어 사서함 소유자가 자신의 일정에 대한 공유 권한을 관리할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-803">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="946dd-804">Outlook에서 제한된 권한으로 메시지를 작성할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-804">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="946dd-805">전자 메일 서식 파일을 .OFT로 저장하는 경우에 중국어 문자가 물음표로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-805">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-806">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-806">PowerPoint</span></span>

- <span data-ttu-id="946dd-807">프레젠테이션 영역을 확대/축소할 경우 확대된 선택 영역과 마우스 포인터 사이에 간격이 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-807">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="946dd-808">그림 옆에 있는 콘텐츠 개체 틀 아이콘에 도구 설명이 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-808">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="946dd-809">Pptsx 파일에 표시 되는 슬라이드 쇼의 제한된 보기에서 IRM으로 보호된 문서의 화면 캡처를 허용하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-809">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="946dd-810">디자인 창을 닫을 때 눈금선이 슬라이드에서 이동되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-810">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="946dd-811">슬라이드 쇼를 보조 모니터에 복제할 때 슬라이드 쇼가 다른 창 뒤에 숨겨질 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-811">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="946dd-812">선택 창이 열린 상태에서 화면 녹화를 중지한 후 슬라이드의 스크롤 막대가 스스로 조정하기 시작하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-812">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-813">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-813">Project</span></span>

- <span data-ttu-id="946dd-814">작업 양식 유형 보기에서 간격이 변경되는 경우 ProjectBeforeTaskChagne 이벤트의 NewVal에 올바른 값이 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-814">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="946dd-815">특정 방식으로 리소스 윤곽선이 지정된 파일을 열 때 Project가 예기치 않게 종료될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-815">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="946dd-816">PWA에서 로컬 mpp 파일로 프로젝트를 저장하는 경우 ProjectBeforeTaskChangeEvent가 실제로 사용자가 변경하지 않은 데이터에 대해 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-816">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="946dd-817">동일한 이름을 가진 여러 자원이 있을 경우 리소스 계약에서 GUID 대신 이름을 사용하여 리소스를 검색하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-817">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="946dd-818">프로젝트 사이트에 작업 목록이 있고 작업 목록을 그룹화한 경우, 작업 목록을 빠르게 편집할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-818">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="946dd-819">CSOM을 통해 엔터프라이즈 리소스를 업데이트하는 경우, 리소스 최대 단위가 손실될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-819">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-820">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-820">Word</span></span>

- <span data-ttu-id="946dd-821">프리젠테이션 영역을 확대/축소하여 확대된 선택 영역과 마우스 포인터 사이에 간격이 생긴 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-821">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="946dd-822">메모 힌트를 클릭 시 확대하여 보기에 메모 카드를 표시하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-822">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="946dd-823">열 사이 선이 이동할 수 있는 레이아웃 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-823">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="946dd-824">변경사항 추적에서 Word 문서를 열면 오류 대화상자가 표시될 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-824">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="946dd-825">Excel 통합 문서를 Word 문서에 삽입하면 Word가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-825">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="946dd-826">워터마크가 적용된 민감도 레이블 인쇄 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-826">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-827">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-827">Office Suite</span></span>

- <span data-ttu-id="946dd-828">Office 2007 "Microsoft 응용 프로그램 오류 보고"제품과 함께 RemoveMSI 기능을 사용할 때 구성이 실패하는 Office 배포 도구 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-828">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="946dd-829">SSO API 대화형 로그인이 오류 코드를 반환하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-829">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2010-november-06"></a><span data-ttu-id="946dd-831">버전 2010: 11월 6일</span><span class="sxs-lookup"><span data-stu-id="946dd-831">Version 2010: November 06</span></span>
<span data-ttu-id="946dd-832">*버전 2010(빌드 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="946dd-832">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="946dd-833">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-833">Various bugs and performance fixes.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)



[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2010-november-04"></a><span data-ttu-id="946dd-836">버전 2010: 11월 4일</span><span class="sxs-lookup"><span data-stu-id="946dd-836">Version 2010: November 04</span></span>
<span data-ttu-id="946dd-837">*버전 2010(빌드 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="946dd-837">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-839">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-839">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-840">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-840">Excel</span></span>

- <span data-ttu-id="946dd-841">**SVG 클립보드 지원:** 이제 Office의 SVG 콘텐츠를 타사 앱에 붙여 을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-841">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="946dd-842">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-842">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="946dd-843">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-843">Outlook</span></span>

- <span data-ttu-id="946dd-844">**SVG 클립보드 지원:** 이제 Office의 SVG 콘텐츠를 타사 앱에 붙여 을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-844">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="946dd-845">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-845">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="946dd-846">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-846">PowerPoint</span></span>

- <span data-ttu-id="946dd-847">**SVG 클립보드 지원:** 이제 Office의 SVG 콘텐츠를 타사 앱에 붙여 을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-847">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="946dd-848">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-848">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="946dd-849">[블로그 게시물](https://insider.office.com/ko-KR/blog/svg-content-office-third-party-apps)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-849">See details in [blog post](https://insider.office.com/ko-KR/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="946dd-850">**투명한 배경으로 GIF 만들기:** 애니메이션 GIF로 내보낼 때 새 옵션을 사용하여 배경을 투명하게 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-850">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="946dd-851">[블로그 게시물](https://insider.office.com/ko-KR/blog/export-animated-gifs-transparent-backgrounds)에서 세부 정보를 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-851">See details in [blog post](https://insider.office.com/ko-KR/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="946dd-852">**범위 내에서 애니메이션 GIF 내보내기:** 애니메이션 GIF로 내보낼 때 슬라이드 범위 선택</span><span class="sxs-lookup"><span data-stu-id="946dd-852">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="946dd-853">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-853">Word</span></span>

- <span data-ttu-id="946dd-854">**SVG 클립보드 지원:** 이제 Office의 SVG 콘텐츠를 타사 앱에 붙여 을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-854">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="946dd-855">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-855">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-858">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-858">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-859">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-859">Outlook</span></span>

- <span data-ttu-id="946dd-860">사용자가 대리인에게 편집자 권한을 부여할 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-860">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-861">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-861">Office Suite</span></span>

- <span data-ttu-id="946dd-862">동기화 지원에서 서버 전용으로 전환된 파일을 저장할 때 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-862">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2010-october-27"></a><span data-ttu-id="946dd-864">버전 2010: 10월 27일</span><span class="sxs-lookup"><span data-stu-id="946dd-864">Version 2010: October 27</span></span>
<span data-ttu-id="946dd-865">*버전 2010(빌드 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="946dd-865">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-869">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-869">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-870">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-870">Outlook</span></span>

- <span data-ttu-id="946dd-871">사용자에 대한 클라우드 설정이 기본적으로 설정되지 않도록 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-871">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="946dd-872">사용자 서명의 변경을 저장하는 데 실패하게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-872">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (BUGDETILES 컨텐츠 끝)을(를) 제거하지 마세요.

## <a name="version-2010-october-24"></a><span data-ttu-id="946dd-874">버전 2010: 10월 24일</span><span class="sxs-lookup"><span data-stu-id="946dd-874">Version 2010: October 24</span></span>
<span data-ttu-id="946dd-875">*버전 2010(빌드 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="946dd-875">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)



[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-879">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-879">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-880">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-880">Outlook</span></span>

- <span data-ttu-id="946dd-881">회신하거나 전달할 때 중국어 메시지의 머리글을 읽을 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-881">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="946dd-882">OFT 파일로 저장하면 중국어 문자가 물음표로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-882">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-883">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-883">Project</span></span>

- <span data-ttu-id="946dd-884">PWA에서 로컬 mpp 파일로 프로젝트를 저장하는 경우 ProjectBeforeTaskChangeEvent가 실제로 사용자가 변경하지 않은 데이터에 대해 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-884">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="946dd-885">작업 양식 유형 보기에서 간격이 변경되는 경우 ProjectBeforeTaskChagne 이벤트의 NewVal에 올바른 값이 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-885">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (BUGDETILES 컨텐츠 끝)을(를) 제거하지 마세요.

## <a name="version-2010-october-19"></a><span data-ttu-id="946dd-887">버전 2010: 10월 19일</span><span class="sxs-lookup"><span data-stu-id="946dd-887">Version 2010: October 19</span></span>
<span data-ttu-id="946dd-888">‘버전 2010(빌드 13328.20210)’</span><span class="sxs-lookup"><span data-stu-id="946dd-888">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-890">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-890">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-891">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-891">Outlook</span></span>

- <span data-ttu-id="946dd-892">**메시지 작성 시간 절약:** Outlook에서 메시지를 신속하게 작성하는 데 도움이 되는 쓰기 제안을 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-892">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="946dd-893">제안을 수락하려면 탭 키를 사용하면 됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-893">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="946dd-894">[블로그 게시물](https://insider.office.com/ko-KR/blog/text-predictions-in-word-outlook)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-894">See details in [blog post](https://insider.office.com/ko-KR/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="946dd-895">**기본 제공 변환기로 언어 장벽 부수기:** 번역을 위한 추가 기능이 더 이상 필요하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-895">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="946dd-896">메시지에서, 마우스 오른쪽 단추를 클릭하여 특정 단어, 구 또는 전체 메시지를 번역할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-896">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="946dd-897">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-897">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="946dd-898">**작업에 대한 사용자 환경 업데이트**: 작업 항목의 시각적 새로 고침</span><span class="sxs-lookup"><span data-stu-id="946dd-898">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-899">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-899">PowerPoint</span></span>

- <span data-ttu-id="946dd-900">**발표자 코치와 프레젠테이션 연습:** 페이싱, 많이 사용하는 단어, 바디랭귀지 등을 개선하여 청중이 몰입도를 유지할 수 있도록 도와 줍니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-900">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="946dd-901">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-901">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="946dd-902">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-902">Word</span></span>

- <span data-ttu-id="946dd-903">**Microsoft 편집기 창에서 데스크톱용 Word에서 업데이트 받기:** 데스크톱 클라이언트용 Word의 편집기 창에서 현재 환경을 업그레이드했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-903">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="946dd-904">**한 번의 클릭으로 작문 제안:** 한 번의 클릭으로 작문 제안을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-904">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="946dd-905">업데이트된 편집기 창은 제안 사이를 쉽게 탐색할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-905">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-908">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-908">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="946dd-909">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-909">PowerPoint</span></span>

- <span data-ttu-id="946dd-910">PresentationBeforeClose 이벤트를 청취하고 프레젠테이션을 확인하는 추가 기능이 있을 때 문서를 닫는 경우 저장 프롬프트가 루프에 표시되는 문제에 대한 수정 사항입니다. 속성을 이벤트 처리기의 일부로 저장했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-910">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2010-october-11"></a><span data-ttu-id="946dd-912">버전 2010: 10월 11일</span><span class="sxs-lookup"><span data-stu-id="946dd-912">Version 2010: October 11</span></span>
<span data-ttu-id="946dd-913">*버전 2010(빌드 13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="946dd-913">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-915">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-915">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-916">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-916">Excel</span></span>

- <span data-ttu-id="946dd-917">**악의적인 파일로부터 데이터 보호** Application Guard를 사용하여 독립된 컨테이너에서 Office 파일을 읽기, 인쇄 및 저장하여 맬웨어로부터 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-917">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="946dd-918">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-918">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="946dd-919">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-919">PowerPoint</span></span>

- <span data-ttu-id="946dd-920">**악의적인 파일로부터 데이터 보호** Application Guard를 사용하여 독립된 컨테이너에서 Office 파일을 읽기, 인쇄 및 저장하여 맬웨어로부터 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-920">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="946dd-921">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-921">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="946dd-922">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-922">Word</span></span>

- <span data-ttu-id="946dd-923">**악의적인 파일로부터 데이터 보호** Application Guard를 사용하여 독립된 컨테이너에서 Office 파일을 읽기, 인쇄 및 저장하여 맬웨어로부터 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-923">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="946dd-924">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-924">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-927">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-927">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-928">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-928">Access</span></span>

- <span data-ttu-id="946dd-929">스크롤하는 동안 저장된 쿼리/관계 창을 로드하는 경우 스크롤 막대 위치가 제대로 설정되지 않은 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-929">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="946dd-930">테이블 추가 작업창에서 '&'를 포함하는 이름을 제대로 표시하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-930">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="946dd-931">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-931">Excel</span></span>

- <span data-ttu-id="946dd-932">차트에서 다단계 범주 수동 간격이 작동하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-932">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="946dd-933">VBA를 사용하여 계열의 최대값, 중간값 및 최소값에 대한 색을 설정하는 기능이 작동하지 않는 2D 지도 차트의 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-933">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="946dd-934">"하나 이상의 수식을 계산하는 동안 Excel 리소스를 모두 사용했습니다" 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-934">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="946dd-935">Office 언어를 스페인어로 설정했을 때 데이터 유효성 검사 목록에 목록의 모든 항목이 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-935">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="946dd-936">'페이지 나누기 미리 보기'가 활성화되었을 때 대량의 데이터가 있는 워크시트를 전환할 때 현저한 지연이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-936">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="946dd-937">데이터 유효성 검사에 사용되는 테이블을 추가해도 통합 문서에 있는 모든 시트에 대한 옵션이 업데이트되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-937">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="946dd-938">OLAP 피벗 테이블을 새로 고칠 때 중단될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-938">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="946dd-939">수식 입력줄을 통해 수식을 입력할 때 일부의 경우에 차트 시트가 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-939">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="946dd-940">원격 세션 연결/연결 끊기, 모니터 변경 등과 같이 장치 연결이 끊어진 후에 Excel 수식 입력줄이 완전히 렌더링되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-940">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="946dd-941">OneNote</span><span class="sxs-lookup"><span data-stu-id="946dd-941">OneNote</span></span>

- <span data-ttu-id="946dd-942">사용자가 OutSpace 파일 > 정보에 있는 텍스트 상자에서 전자 필기장 URL을 선택하고 복사할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-942">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="946dd-943">사용자가 전자 필기장 색 선택기에서 초록색을 마우스로 가리킨 경우 팝업 창에서 "빨간색 분필"을 읽는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-943">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="946dd-944">OneNote가 사용자 지정 테마에 대한 캔버스에서 고대비 색을 적용하지 못하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-944">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-945">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-945">Outlook</span></span>

- <span data-ttu-id="946dd-946">일부 전자 메일의 제목 줄이 비어있는 경우 자동으로 생성된 전자 메일이 이를 빈 본문과 함께 보내는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-946">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="946dd-947">폴더에 대해 잘못된 폴더 GUID가 캐시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-947">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="946dd-948">사용자가 전자 메일 주소를 표시 이름으로 받는 사람 필드에 복사하여 붙여 넣는 경우, 전자 메일 주소가 정확하게 구문 분석되지 않았고 잘못된 전자 메일 주소에 대한 경고가 표시되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-948">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="946dd-949">이 문제가 해결되었으므로 이름과 전자 메일 주소가 정확하게 구문 분석되고 경고가 더 이상 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-949">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="946dd-950">온라인 공유 폴더가 상위 폴더 이름을 반환하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-950">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="946dd-951">실패하는 대신, 주 계정으로 잘못 이동한 빈 경로가 반환되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-951">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="946dd-952">클래식 첨부 파일에서 다른 이름으로 저장 옵션을 사용할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-952">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="946dd-953">정책을 재정의할 때 사유 텍스트를 사용자 지정할 수 있는 방법을 제공하도록 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-953">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="946dd-954">읽기 전용 미리 보기 창에서 초안을 다시 연 후에 변경 내용 추적이 켜지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-954">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="946dd-955">중요 받은 편지함을 끄고 정렬하면 전자 메일이 숨겨지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-955">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="946dd-956">클라우드 설정을 사용하도록 설정한 사용자에 대해 Outlook에서 두 번째 빈 서명을 만드는 문제를 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-956">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-957">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-957">PowerPoint</span></span>

- <span data-ttu-id="946dd-958">PDF로 내보낼 때 PowerPoint가 직사각형 글머리 기호를 내보내지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-958">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="946dd-959">GIF가 편집기 및 슬라이드 쇼에서 한 번만 활성화되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-959">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="946dd-960">사용자가 원본 경로를 로컬 OneDrive 폴더로 변경한 경우 연결된 Excel 차트가 Excel 시트로 잘못 변경되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-960">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="946dd-961">마지막 슬라이드에 있는 경우와 '세션 종료'를 누른 후와 요약이 표시되기 전에 다음 슬라이드로 살짝 미는 경우, 세션 종료 대화 상자가 요약 페이지에도 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-961">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-962">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-962">Project</span></span>

- <span data-ttu-id="946dd-963">동일한 프로젝트를 여러 번 추가하고 AttachToSources를 false로 설정하는 경우 ConsolidateProjects VBA 메서드가 실패할 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-963">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="946dd-964">이벤트 코드를 실행 중이고 작업 폼 보기를 통하여 변경을 하려고 하는 경우, 확인 단추를 클릭하면 변경 내용이 커밋되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-964">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="946dd-965">동일한 프로젝트를 여러 번 추가하고 AttachToSources를 false로 설정하는 경우 ConsolidateProjects VBA 메서드가 실패할 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-965">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="946dd-966">수식이 포함된 사용자 지정 필드가 있고 획득 가치를 사용하는 경우, 보기를 전환하고 프로젝트/작업 세부 정보를 열 때 성능이 저하될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-966">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="946dd-967">자원 배정 현황 또는 시트 보기에 그룹화 기준을 적용한 후 열을 삽입하는 경우 Project가 중단될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-967">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-968">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-968">Word</span></span>

- <span data-ttu-id="946dd-969">워크플로를 사용하도록 설정한 파일에 대한 링크가 정상적으로 열리지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-969">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="946dd-970">추적된 변경 내용(삽입/삭제)을 탭하면 메모가 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-970">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="946dd-971">Word에서 메모 설명선을 삭제할 때 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-971">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="946dd-972">메시지가 전달 금지로 설정된 Outlook 에 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-972">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="946dd-973">인용문과 수식이 포함된 Word 문서를 저장할 때 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-973">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="946dd-974">스타일 갤러리 대화 상자와 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-974">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-975">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-975">Office Suite</span></span>

- <span data-ttu-id="946dd-976">Office에서 사용자가 잉크젯 프린터로 문서/파일을 인쇄하고 프린터의 잉크가 부족하면, 잉크젯 프린터에 토너가 없더라도 "토너 부족" 또는 "토너 없음" 메시지가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-976">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="946dd-977">메시지를 변경하여 "토너/잉크 부족" 및 "토너/잉크 없음"으로 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-977">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2009-october-07"></a><span data-ttu-id="946dd-979">버전 2009: 10월 7일</span><span class="sxs-lookup"><span data-stu-id="946dd-979">Version 2009: October 07</span></span>
<span data-ttu-id="946dd-980">*버전 2009(빌드 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="946dd-980">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-982">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-982">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-983">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-983">Excel</span></span>

- <span data-ttu-id="946dd-984">**파워 쿼리를 사용하여 데이터 형식 만들기:** 모든 데이터 원본에서 파워 쿼리로 다양한 데이터 형식을 만듭니다</span><span class="sxs-lookup"><span data-stu-id="946dd-984">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-985">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-985">Outlook</span></span>

- <span data-ttu-id="946dd-986">**문법 검사를 도움:** Outlook에서 사용자가 입력할 때 문법 오류를 표시하여 클릭 한 번으로 제안을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-986">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="946dd-987">[블로그 게시물](https://insider.office.com/ko-KR/blog/grammar-and-style-suggestions-available-in-outlook)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-987">See details in [blog post](https://insider.office.com/ko-KR/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-990">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-990">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-991">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-991">Outlook</span></span>

- <span data-ttu-id="946dd-992">캐시되지 않은 공유 일정을 검색할 때 검색에서 결과가 반환되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-992">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="946dd-993">일부 사용자가 예기치 않게 오프라인 상태에서 Outlook이 시작되는 것을 관찰하게 한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-993">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="946dd-994">다른 사서함에서 공유 폴더를 열 때 대리인이 간헐적으로 오류를 발견하게 한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-994">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-995">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-995">PowerPoint</span></span>

- <span data-ttu-id="946dd-996">제한된 보기에서 PowerPoint 파일을 열 때 IRM 보호를 사용하지 않도록 설정한 문제를 해결하기 위한 보안 수정입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-996">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-997">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-997">Office Suite</span></span>

- <span data-ttu-id="946dd-998">Office에서 사용자가 잉크젯 프린터로 문서/파일을 인쇄하고 프린터의 잉크가 부족하면, 잉크젯 프린터에 토너가 없더라도 "토너 부족" 또는 "토너 없음" 메시지가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-998">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="946dd-999">메시지를 변경하여 "토너/잉크 부족" 및 "토너/잉크 없음"으로 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-999">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2009-september-26"></a><span data-ttu-id="946dd-1001">버전 2009: 9월 26일</span><span class="sxs-lookup"><span data-stu-id="946dd-1001">Version 2009: September 26</span></span>
<span data-ttu-id="946dd-1002">*버전 2009(빌드 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1002">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1004">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1004">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1005">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1005">Outlook</span></span>

- <span data-ttu-id="946dd-1006">일부 전자 메일의 제목 줄이 비어있는 경우 일부 자동으로 생성된 전자 메일이 이를 빈 본문과 함께 보내는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1006">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-1007">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1007">Project</span></span>

- <span data-ttu-id="946dd-1008">이벤트 코드를 실행 중이고 작업 폼 보기를 통하여 변경을 하려고 하는 경우, 확인 단추를 클릭하면 변경 내용이 커밋되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1008">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2009-september-21"></a><span data-ttu-id="946dd-1010">버전 2009: 9월 21일</span><span class="sxs-lookup"><span data-stu-id="946dd-1010">Version 2009: September 21</span></span>
<span data-ttu-id="946dd-1011">*버전 2009(빌드 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1011">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1013">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1013">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="946dd-1014">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-1014">Access</span></span>

- <span data-ttu-id="946dd-1015">**Office 테마를 자동으로 전환:** Office는 Windows 10 테마 설정에 맞게 테마를 자동으로 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1015">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="946dd-1016">파일 > 옵션으로 이동한 다음 Office 테마 옆에 있는 "시스템 설정 사용"을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1016">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="946dd-1017">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1017">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="946dd-1018">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1018">Excel</span></span>

- <span data-ttu-id="946dd-1019">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1019">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="946dd-1020">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1020">No conversion required.</span></span><br /><span data-ttu-id="946dd-1021">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-1021">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="946dd-1022">**Office 테마를 자동으로 전환:** Office는 Windows 10 테마 설정에 맞게 테마를 자동으로 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1022">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="946dd-1023">파일 > 옵션으로 이동한 다음 Office 테마 옆에 있는 "시스템 설정 사용"을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1023">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="946dd-1024">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1024">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="946dd-1025">OneNote</span><span class="sxs-lookup"><span data-stu-id="946dd-1025">OneNote</span></span>

- <span data-ttu-id="946dd-1026">**Office 테마를 자동으로 전환:** Office는 Windows 10 테마 설정에 맞게 테마를 자동으로 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1026">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="946dd-1027">파일 > 옵션으로 이동한 다음 Office 테마 옆에 있는 "시스템 설정 사용"을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1027">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="946dd-1028">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1028">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="946dd-1029">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1029">Outlook</span></span>

- <span data-ttu-id="946dd-1030">**메시지 소유자별 대화 삭제:** 소유자별로 메시지를 삭제할 수 있도록 하는 기능입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1030">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="946dd-1031">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1031">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="946dd-1032">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1032">No conversion required.</span></span><br /><span data-ttu-id="946dd-1033">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-1033">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="946dd-1034">**Office 테마를 자동으로 전환:** Office는 Windows 10 테마 설정에 맞게 테마를 자동으로 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1034">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="946dd-1035">파일 > 옵션으로 이동한 다음 Office 테마 옆에 있는 "시스템 설정 사용"을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1035">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="946dd-1036">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1036">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="946dd-1037">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1037">PowerPoint</span></span>

- <span data-ttu-id="946dd-1038">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1038">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="946dd-1039">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1039">No conversion required.</span></span><br /><span data-ttu-id="946dd-1040">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-1040">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="946dd-1041">**Office 테마를 자동으로 전환:** Office는 Windows 10 테마 설정에 맞게 테마를 자동으로 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1041">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="946dd-1042">파일 > 옵션으로 이동한 다음 Office 테마 옆에 있는 "시스템 설정 사용"을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1042">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="946dd-1043">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1043">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="946dd-1044">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1044">Project</span></span>

- <span data-ttu-id="946dd-1045">**Office 테마를 자동으로 전환:** Office는 Windows 10 테마 설정에 맞게 테마를 자동으로 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1045">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="946dd-1046">파일 > 옵션으로 이동한 다음 Office 테마 옆에 있는 "시스템 설정 사용"을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1046">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="946dd-1047">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1047">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="946dd-1048">게시자</span><span class="sxs-lookup"><span data-stu-id="946dd-1048">Publisher</span></span>

- <span data-ttu-id="946dd-1049">**Office 테마를 자동으로 전환:** Office는 Windows 10 테마 설정에 맞게 테마를 자동으로 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1049">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="946dd-1050">파일 > 옵션으로 이동한 다음 Office 테마 옆에 있는 "시스템 설정 사용"을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1050">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="946dd-1051">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1051">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="946dd-1052">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-1052">Visio</span></span>

- <span data-ttu-id="946dd-1053">**Office 테마를 자동으로 전환:** Office는 Windows 10 테마 설정에 맞게 테마를 자동으로 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1053">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="946dd-1054">파일 > 옵션으로 이동한 다음 Office 테마 옆에 있는 "시스템 설정 사용"을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1054">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="946dd-1055">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1055">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="946dd-1056">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1056">Word</span></span>

- <span data-ttu-id="946dd-1057">**Office에 iPhone 사진을 직접 삽입**: 이제 전화기의 HEIC 사진이 Office에 원활하게 삽입됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1057">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="946dd-1058">변환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1058">No conversion required.</span></span><br /><span data-ttu-id="946dd-1059">[블로그 게시물](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-1059">See details in [blog post](https://insider.office.com/ko-KR/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="946dd-1060">**Office 테마를 자동으로 전환:** Office는 Windows 10 테마 설정에 맞게 테마를 자동으로 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1060">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="946dd-1061">파일 > 옵션으로 이동한 다음 Office 테마 옆에 있는 "시스템 설정 사용"을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1061">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="946dd-1062">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1062">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1065">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1065">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="946dd-1066">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1066">PowerPoint</span></span>

- <span data-ttu-id="946dd-1067">많은 수의 특정 데이터 개체 유형(E2o)이 포함된 파일에서 공동 작성 속도가 느려지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1067">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2009-september-14"></a><span data-ttu-id="946dd-1069">버전 2009: 9월 14일</span><span class="sxs-lookup"><span data-stu-id="946dd-1069">Version 2009: September 14</span></span>
<span data-ttu-id="946dd-1070">*버전 2009(빌드 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1070">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="946dd-1071">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-1071">Various bugs and performance fixes.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2009-september-10"></a><span data-ttu-id="946dd-1074">버전 2009: 9월 10일</span><span class="sxs-lookup"><span data-stu-id="946dd-1074">Version 2009: September 10</span></span>
<span data-ttu-id="946dd-1075">*버전 2009(빌드 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1075">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1077">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1077">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-1078">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-1078">Access</span></span>

- <span data-ttu-id="946dd-1079">이제 이 문제는 해결되었으며, 더이상 충돌이 발생하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1079">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="946dd-1080">ODBC 데이터베이스 연결이 타사 응용 프로그램과 작동하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1080">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="946dd-1081">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1081">Excel</span></span>

- <span data-ttu-id="946dd-1082">LET 기능이 포함된 파일을 열면 다음과 같은 경고가 표시되는 문제를 해결: ““your file.xlsx”의 콘텐츠에서 문제를 발견했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1082">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="946dd-1083">가능한 많은 복구를 원하십니까?</span><span class="sxs-lookup"><span data-stu-id="946dd-1083">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="946dd-1084">이 통합 문서의 원본을 신뢰하는 경우 "예"를 클릭하세요”.</span><span class="sxs-lookup"><span data-stu-id="946dd-1084">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="946dd-1085">사용자가 F1을 통해 괄호 및 호출된 도움말을 포함한 수식 이름을 입력하면 해당 수식에 대한 도움말 항목이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1085">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="946dd-1086">차트 데이터 시트가 활성 시트면 범위에 FormulaR1C1 속성 설정에 매크로를 사용할 때 셀 참조가 부정확한 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1086">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="946dd-1087">사용자가 Analysis Services 데이터베이스에 존재하지 않는 값으로 설정하였기 때문에 피벗 테이블 필터를 수정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1087">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="946dd-1088">XLAM 추가 기능 참조 및 명명된 범위와 관련된 충돌을 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1088">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="946dd-1089">사용자가 동적 배열에 사용자 지정 스타일을 적용한 경우 "배열의 일부를 변경할 수 없습니다"라는 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1089">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="946dd-1090">이는 제거된 레거시 제한 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1090">This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="946dd-1091">이전 버전의 파일을 복원한 후 단추에 할당된 매크로가 손상된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1091">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="946dd-1092">잉크 입력으로 인해 Excel이 응답하지 않을 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1092">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-1093">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1093">Outlook</span></span>

- <span data-ttu-id="946dd-1094">그룹 정책을 통해 기본 로깅 옵션을 사용/사용 안 함 설정하는 것에 더 많은 유연성을 제공하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1094">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="946dd-1095">도우미 사용 권한 및 관리자 권한으로 전자 메일 초안이 사서함 간에 이동한 후에 전자 메일 보낸 사람의 레거시 도메인 이름이 유지되고 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1095">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="946dd-1096">일부 사용자가 온라인으로 작업하기 위해 수동으로 선택할 때까지 Outlook이 오프라인 상태에서 시작하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1096">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="946dd-1097">SLR(Single Line Ribbon)을 사용한 후에 VBA 코드 ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage")를 실행할 때 런타임 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1097">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="946dd-1098">고 해상도(예: 1750 x 1920)와 큰 텍스트 크기(예: 175%)가 결합된 시스템에서 자동 회신 대화 상자의 ‘확인’ 및 ‘취소’ 단추가 보이지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1098">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="946dd-1099">빈 연락처 그룹에서 다른 연락처 그룹으로 모임 요청을 보내는 경우 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1099">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="946dd-1100">사용자가 크기가 큰 특정 전자 메일을 열 때 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1100">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="946dd-1101">그룹 정책에서 추가 기능을 항상 사용하도록 설정해야하는 경우, 사용자가 추가 기능을 사용하지 못하는 것을 방지하기 위해 추가 기능을 모니터링 할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1101">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="946dd-1102">사용자가 둘 이상의 메시지를 선택할 때 OneNote에 "전달 금지"정책이 적용된 전자 메일 콘텐츠를 보낼 수 있게 되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1102">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="946dd-1103">이제 다른 Office 애플리케이션 사용을 비활성화할 필요 없이 Outlook용 IRM(정보 권한 관리)를 사용을 비활성화할 수 있도록 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1103">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="946dd-1104">"otherTelephone" 및 "otherHomePhone"에 대한 Active Directory의 사용자 계정 특성이 해당 Outlook LDAP 특성에 매핑되지 않은 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1104">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="946dd-1105">이렇게 변경하면 사용자가 모임 페이지에서 스케줄링 길잡이 페이지로 탭을 전환한 후에도 미팅 페이지가 계속 표시되는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1105">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-1106">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1106">PowerPoint</span></span>

- <span data-ttu-id="946dd-1107">사용자에게 특정 조건에 따라 표시되지 않는 리본/제목 표시줄이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1107">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="946dd-1108">PowerPoint를 부팅한 후 슬라이드를 삽입하고 메모 창을 열고 닫으면 축소판 그림 창의 슬라이드가 겹치는 상태로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1108">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="946dd-1109">비디오 삽입 기능이 사용하지 않도록 설정되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1109">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="946dd-1110">슬라이드 쇼에서 비디오가 자동으로 재생되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1110">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-1111">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1111">Project</span></span>

- <span data-ttu-id="946dd-1112">리소스에 여러 비용 테이블이 있는 경우 남은 비용이 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1112">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="946dd-1113">SharePoint 작업 목록에 연결된 프로젝트에 대해 프로젝트 완료 날짜가 업데이트되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1113">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="946dd-1114">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-1114">Visio</span></span>

- <span data-ttu-id="946dd-1115">실시간 미리 보기가 텍스트 맞춤에서 충돌하여 고객으로부터 보고되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1115">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="946dd-1116">7월 포크에 대한 최고 적중 횟수입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1116">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-1117">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1117">Word</span></span>

- <span data-ttu-id="946dd-1118">사용자가 메모를 클릭한 경우 메모 카드가 메모 텍스트 주위에 테두리를 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1118">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="946dd-1119">글머리 기호 아이콘이 제대로 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1119">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="946dd-1120">사용자가 메모를 선택할 때 머리글/바닥글을 종료할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1120">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="946dd-1121">메모가 삭제된 후 Word에서 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1121">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="946dd-1122">사용자가 이미 커밋된 메모가 포함된 줄에 고정된 메모 초안을 만든 경우, 초안이 SideTrack에서 커밋된 메모를 기준으로 잘못된 순서로 정렬되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1122">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="946dd-1123">문서를 160% 이상으로 확대하고 메모 창이 표시되지 않는 경우 포커스가 메모 창으로 이동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1123">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="946dd-1124">사이드트랙 스크롤이 작동하지 않아 사용자에게 사이드트랙 경계를 초과하는 댓글 스레드가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1124">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="946dd-1125">현재 위치 추적창에서 해결된 메모를 검색하는 것이 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1125">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="946dd-1126">여러 개의 열린 문서 사이를 전환한 후 한 문서의 메모가 다른 열린 문서에 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1126">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="946dd-1127">문서를 HTML 형식으로 저장할 때 긴 링크가 줄바꿈되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1127">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="946dd-1128">경우에 따라 전자 메일에서 글머리 기호가 제대로 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1128">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="946dd-1129">AutoExec 전에 AutoOpen이 실행되는 매크로 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1129">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-1130">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1130">Office Suite</span></span>

- <span data-ttu-id="946dd-1131">Office 2007 "Microsoft 응용 프로그램 오류 보고"제품과 함께 RemoveMSI 기능을 사용할 때 구성이 실패하는 Office 배포 도구 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1131">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="946dd-1132">일부 사용자가 선택한 DPI 설정이 보존되지 않는 그림 압축 대화 상자와 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1132">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="946dd-1133">이 변경 사항은 특정 사용자 설정을 유지하지 않는 그림 압축 대화 상자의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1133">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-september-04"></a><span data-ttu-id="946dd-1135">버전 2008: 9월 4일</span><span class="sxs-lookup"><span data-stu-id="946dd-1135">Version 2008: September 04</span></span>
<span data-ttu-id="946dd-1136">*버전 2008 (빌드 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1136">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1138">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1138">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="946dd-1139">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1139">Office Suite</span></span>

- <span data-ttu-id="946dd-1140">이 변경 사항은 특정 사용자 설정을 유지하지 않는 그림 압축 대화 상자의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1140">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-september-02"></a><span data-ttu-id="946dd-1142">버전 2008: 9월 2일</span><span class="sxs-lookup"><span data-stu-id="946dd-1142">Version 2008: September 02</span></span>
<span data-ttu-id="946dd-1143">*버전 2008(빌드 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1143">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1145">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1145">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1146">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1146">Excel</span></span>

- <span data-ttu-id="946dd-1147">**도형을 그림으로 저장:** 몇 번의 클릭만으로 도형, 아이콘 또는 기타 개체를 그림 파일로 저장하여 다른 곳에서 다시 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1147">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="946dd-1148">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1148">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="946dd-1149">**Excel의 액션 펜을 이용하여 빠르게 편집:** 펜 도구를 사용하여 데이터를 필기하고 빠르게 편집할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1149">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1152">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1152">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1153">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1153">Excel</span></span>

- <span data-ttu-id="946dd-1154">서식 복사를 사용하는 경우 특정 상황에서 Excel이 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1154">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-1155">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1155">Word</span></span>

- <span data-ttu-id="946dd-1156">표준 스타일을 사용하여 기본 스타일을 업데이트할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1156">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (버그 세부 정보 콘텐츠 끝을 제거하지 마세요.)

## <a name="version-2008-august-27"></a><span data-ttu-id="946dd-1158">버전 2008: 8월 27일</span><span class="sxs-lookup"><span data-stu-id="946dd-1158">Version 2008: August 27</span></span>
<span data-ttu-id="946dd-1159">*버전 2008(빌드 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1159">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1163">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1163">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1164">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1164">Outlook</span></span>

- <span data-ttu-id="946dd-1165">프로필에 추가된 보조 계정에서 모임 요청을 만들려고 시도한 사용자에게 전자 메일 주소 대신 빈 보낸 사람: 필드가 표시되지 않는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1165">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="946dd-1166">사용자가 공유 사서함을 추가한 후 공용 폴더에 연결할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1166">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="946dd-1167">사용자가 클라우드 첨부 파일을 사용하여 대화형으로 작업하는 경우 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1167">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="946dd-1168">이를 통해 받는 사람을 편집할 때 사용자에게 충돌이 발생하는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1168">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="946dd-1169">압축 보기를 사용할 때 사용자에게 이상 현상이 나타나는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1169">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1170">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1170">Word</span></span>

- <span data-ttu-id="946dd-1171">이 변경사항은 이전 공동 작성 세션 후 Office 응용 프로그램이 자동 저장 오류 상태로 고정될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1171">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="946dd-1172">AutoExec에서 매크로 AutoOpen가 실행되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1172">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-august-25"></a><span data-ttu-id="946dd-1174">버전 2008: 8월 25일</span><span class="sxs-lookup"><span data-stu-id="946dd-1174">Version 2008: August 25</span></span>
<span data-ttu-id="946dd-1175">*버전 2008(빌드 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1175">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1177">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1177">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1178">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1178">Outlook</span></span>

- <span data-ttu-id="946dd-1179">**사용자별로 검색할 때 전자 메일 제안을 받습니다.:** Outlook에 검색어를 입력하면 제안사항에서 가장 관련성이 높은 전자 메일을 받게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1179">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1182">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1182">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1183">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1183">Outlook</span></span>

- <span data-ttu-id="946dd-1184">새 전자 메일에 회신하거나 새 전자 메일을 작성할 때 사용자가 다음 오류를 수신한 문제를 해결합니다. "이 웹 페이지의 일부 파일이 예상 위치에 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1184">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="946dd-1185">그래도 다운로드하시겠어요?</span><span class="sxs-lookup"><span data-stu-id="946dd-1185">Do you want to download them anyway?</span></span> <span data-ttu-id="946dd-1186">웹 페이지가 신뢰할 수 있는 원본의 웹 페이지인 경우 예를 클릭합니다."</span><span class="sxs-lookup"><span data-stu-id="946dd-1186">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="946dd-1187">프로젝트</span><span class="sxs-lookup"><span data-stu-id="946dd-1187">Project</span></span>

- <span data-ttu-id="946dd-1188">리소스에 둘 이상의 비용 비율 테이블이 정의된 경우 나머지 비용이 항상 올바르게 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1188">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-1189">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1189">Word</span></span>

- <span data-ttu-id="946dd-1190">사용자가 새 전자 메일에 회신하거나 작성할 때 충돌이 발생한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1190">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-august-17"></a><span data-ttu-id="946dd-1192">버전 2008: 8월 17일</span><span class="sxs-lookup"><span data-stu-id="946dd-1192">Version 2008: August 17</span></span>
<span data-ttu-id="946dd-1193">*버전 2008(빌드 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1193">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1195">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1195">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1196">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1196">Outlook</span></span>

- <span data-ttu-id="946dd-1197">일부 상황에서 대리인이 거절했을 때 관리자의 일정에서 모임이 제거되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1197">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="946dd-1198">SharePoint 파일에 스마트 링크를 추가할 때 일부 문자 집합 사용자에게 파일 이름을 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1198">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="946dd-1199">"머리글만 다운로드" 옵션을 선택한 상태에서 POP 계정에서 네 개 이상의 전자 메일을 삭제하면 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1199">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="946dd-1200">오른쪽 클릭 상황에 맞는 메뉴가 검색 컨트롤에 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1200">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (버그 세부 정보를 제거하지 마세요. 끝)

## <a name="version-2008-august-11"></a><span data-ttu-id="946dd-1202">버전 2008: 8월 11일</span><span class="sxs-lookup"><span data-stu-id="946dd-1202">Version 2008: August 11</span></span>
<span data-ttu-id="946dd-1203">*버전 2008 (빌드13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1203">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="946dd-1204">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1204">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1206">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1206">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-1207">액세스</span><span class="sxs-lookup"><span data-stu-id="946dd-1207">Access</span></span>

- <span data-ttu-id="946dd-1208">이 수정은 특정 쿼리를 실행하려고 하면 이전에 '쿼리가 너무 복잡합니다'라는 오류 메시지가 발생한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1208">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="946dd-1209">Office 365를 설치한 경우 ACE를 Office 에코시스템 외부에 노출하기 위해 ACE 재배포 가능 엔진을 더 이상 설치할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1209">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="946dd-1210">따라서 Office 365를 사용하는 사용자는 ACE Redist Engine이 더 이상 필요하지 않으므로 이 문제가 발생하지 않아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1210">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="946dd-1211">이 문제가 해결되었습니다. 이제 Office의 Click-to-Run 응용 프로그램 외부에서 ODBC 드라이버를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1211">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="946dd-1212">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1212">Excel</span></span>

- <span data-ttu-id="946dd-1213">차트 시리즈의 순서가 변경된 경우 시리즈와 함께 정렬된 해당 확인란이 순서와 함께 순서가 변경되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1213">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="946dd-1214">LET() 함수를 사용하여 수식이 들어 있는 파일을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1214">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="946dd-1215">통합 문서에 대한 VBA를 통해 'ForceFullCalculation'아 사용하도록 설정된 경우 차트가 항상 예상한 대로 업데이트되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1215">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="946dd-1216">방사형 그라데이션 채우기가 있는 이미지의 복사본이 원본과 일치하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1216">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="946dd-1217">OneNote</span><span class="sxs-lookup"><span data-stu-id="946dd-1217">OneNote</span></span>

- <span data-ttu-id="946dd-1218">응용 프로그램 창의 크기를 작게 조정한 경우 검색 편집 상자의 개체 틀 텍스트가 오버플로될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1218">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1219">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1219">Outlook</span></span>

- <span data-ttu-id="946dd-1220">Outlook에서 동일한 전자 메일 도메인의 프로필을 여러 개 만드는 것과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1220">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="946dd-1221">공유 일정관리 개선 기능의 일부 사용자가 새로 추가된 공유 일정관리를 볼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1221">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="946dd-1222">S/MIME 암호화된 메시지의 헤더에 잠금 아이콘이 표시되지 않게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1222">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="946dd-1223">공유 폴더 다운로드를 선택하지 않은 경우에 전달 허용 옵션이 공유 일정 모임 "응답 옵션"에 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1223">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="946dd-1224">보안 대화 상자에서 "저장" 옵션을 선택할 때 사용자가 테넌트 외부에서 로컬 컴퓨터에 OneDrive 첨부 파일을 저장할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1224">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="946dd-1225">사용자에 게 적절한 인쇄 권한이 있는 경우에도 인쇄 단추가 사용 안 함 상태로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1225">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="946dd-1226">암호화되지 않은 상태로 전송하는 경우 S/MIME 메시지에서 첨부 파일을 제거하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1226">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="946dd-1227">일반 텍스트 S/MIME 메시지가 전송 시 왜곡되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1227">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="946dd-1228">암호화되지 않은 S/MIME 전자 메일을 전송할 때 첨부 파일이 손상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1228">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="946dd-1229">보낸 사람이 다른 이름으로 저장 권한을 부여한 경우에도 받는 사람이 권한 보호 메시지를 저장할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1229">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="946dd-1230">이 수정은 회신하는 메시지에 대한 소유자 권한이 없는 경우 검사기 창에서 디지털 권한 관리 메시지에 회신할 때 사용자가 서명을 추가할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1230">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="946dd-1231">이 수정은 Outlook이 표시다운 내용에 줄 바꿈을 제대로 표시하지 못하게 하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1231">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="946dd-1232">일부 언어에서 일부 고급 검색 옵션의 레이블이 잘려 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1232">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1233">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1233">PowerPoint</span></span>

- <span data-ttu-id="946dd-1234">방사형 그라데이션 채우기가 있는 이미지의 복사본이 원본과 일치하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1234">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="946dd-1235">Office Store에 대한 액세스가 허용되지 않을 때 PowerPoint의 Forms 버튼이 Forms 생성을 허용하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1235">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="946dd-1236">프로젝트</span><span class="sxs-lookup"><span data-stu-id="946dd-1236">Project</span></span>

- <span data-ttu-id="946dd-1237">작업 보드 보기에 나열된 작업이 자원 배정 대화 상자의 작업과 동기화되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1237">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="946dd-1238">Project에서 SharePoint 문서 라이브러리에 PDF/XPS를 저장하려고 하면 아무 일도 일어나지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1238">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="946dd-1239">여러 종속성이 있는 작업을 복사하고 붙여 넣는 경우 일부 종속성이 제대로 복사되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1239">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="946dd-1240">SharePoint 작업 목록의 경우 두 번째 탭의 리본 버튼을 사용할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1240">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="946dd-1241">Skype</span><span class="sxs-lookup"><span data-stu-id="946dd-1241">Skype</span></span>

- <span data-ttu-id="946dd-1242">춤추는 이모티콘 피부색을 중성 색상으로 변경</span><span class="sxs-lookup"><span data-stu-id="946dd-1242">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="946dd-1243">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-1243">Visio</span></span>

- <span data-ttu-id="946dd-1244">이 문제를 해결한 후에는 사용자가 (이 경우 추가 기능을 통한) 사이의 메커니즘에 의해 삭제 명령 실행을 중지한 경우 메모리가 누출되지 않고 전체 시스템에 영향을 주지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1244">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1245">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1245">Word</span></span>

- <span data-ttu-id="946dd-1246">일부 텍스트와 이미지를 메모 상자에 붙여넣은 후 에 Word가 응답하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1246">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="946dd-1247">방사형 그라데이션 채우기가 있는 이미지의 복사본이 원본과 일치하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1247">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="946dd-1248">응용 프로그램 창의 크기를 작게 조정한 경우 검색 편집 상자의 개체 틀 텍스트가 오버플로될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1248">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="946dd-1249">변경 내용을 추적하기 위해 주석을 추가하면 수정사항 창이 예기치 않게 열리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1249">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="946dd-1250">포커스가 메모 텍스트 상자에 있을 때 '편집기' 명령을 사용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1250">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="946dd-1251">포커스가 메모 텍스트 상자에 있을 때 '변경 내용 표시' 명령을 사용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1251">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="946dd-1252">마지막 메모를 삭제한 후 '새 메모' 단추를 사용하지 않도록 설정되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1252">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="946dd-1253">변경 내용 추적에 대한 '특정 사용자' 옵션이 비활성화되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1253">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="946dd-1254">삽입 > 링크 드롭다운을 통해 문서 링크가 메모 상자에 삽입되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1254">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="946dd-1255">가끔 HTML 파일을 여는 동안 멈추는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1255">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="946dd-1256">사용자 지정 XML에서 문서를 열 때 메모 상태가 손실될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1256">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="946dd-1257">하이퍼링크를 포함 하는 이미지를 추가한 후 VBA hyperlinks 컬렉션의 하이퍼링크 수가 제대로 반복 되지 않는 문제가 해결 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1257">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="946dd-1258">이전 웹 서비스 기반 공유 창의 경우 공유 창이 열려 있는 동안 문서를 닫으면 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1258">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="946dd-1259">이제 이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1259">This is now fixed.</span></span>

- <span data-ttu-id="946dd-1260">사용자가 작업 표시줄에서 새 앱 창을 열고 비어 있는 새 문서를 만든 후에 추가 파일이 생성되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1260">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="946dd-1261">사용자가 문서를 편집하고 있지만 권한을 잃은 경우 사용자에게 재인증을 해야 한다는 알림을 보내지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1261">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2007-august-05"></a><span data-ttu-id="946dd-1263">버전 2007: 8월 5일</span><span class="sxs-lookup"><span data-stu-id="946dd-1263">Version 2007: August 05</span></span>
<span data-ttu-id="946dd-1264">*버전 2007(빌드 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1264">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)



[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1268">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1268">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1269">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1269">Outlook</span></span>

- <span data-ttu-id="946dd-1270">Outlook에서 검색 제안을 검색하지 못한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1270">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="946dd-1271">개인 정보 검색 시 사용자가 때때로 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1271">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-1272">프로젝트</span><span class="sxs-lookup"><span data-stu-id="946dd-1272">Project</span></span>

- <span data-ttu-id="946dd-1273">상태가 좋지 않은 프로젝트를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1273">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2007-july-29"></a><span data-ttu-id="946dd-1275">버전 2007: 7월 29일</span><span class="sxs-lookup"><span data-stu-id="946dd-1275">Version 2007: July 29</span></span>
<span data-ttu-id="946dd-1276">*버전 2007(빌드 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1276">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1278">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1278">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1279">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1279">Excel</span></span>

- <span data-ttu-id="946dd-1280">**데이터 형식을 사용하여 Power BI에서 조직 데이터를 가져오기:** 이제 Power BI의 Excel 데이터 형식을 Office 365 E5/A5 또는 Microsoft 365 E5/A5를 사용하는 조직의 참가자에게 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1280">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="946dd-1281">필요한 정보를 가져오고 손쉽게 새로 고치는 건 일상적인 여러 워크플로에 매우 중요합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1281">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="946dd-1282">Microsoft는 Power BI를 사용하여 Excel에서 데이터 형식으로 회사나 조직 정보에 액세스할 수 있도록 하여 스프레드시트에 연결된 정보를 제공하는 기능을 확장합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1282">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="946dd-1283">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1283">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="946dd-1284">[블로그 게시물](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-1284">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1285">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1285">Outlook</span></span>

- <span data-ttu-id="946dd-1286">**검색할 위치 선택:** 새 검색 범위 드롭다운을 통해 검색을 더 쉽게 수정하고 현재 폴더와 현재 사서함 간 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1286">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="946dd-1287">최상의 환경을 위해 새 검색 기능에 피드백을 보내주신 모든 사용자에게 감사의 말씀을 드립니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1287">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="946dd-1288">피드백을 통해 디자인과 업데이트를 완성했습니다!</span><span class="sxs-lookup"><span data-stu-id="946dd-1288">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1289">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1289">Word</span></span>

- <span data-ttu-id="946dd-1290">**최신 주석을 활용한 더 나은 공동 작업:** 개체에 메모를 추가하고, 동료를 @멘션하고, 메모 스레드를 해결하여 공동 작업 환경을 개선해보세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-1290">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="946dd-1291">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1291">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1294">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1294">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1295">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1295">Outlook</span></span>

- <span data-ttu-id="946dd-1296">보호되는 컨텍스트에서 보호되지 않은 컨텍스트로 회신 보낸 사람 주소를 전환할 때 CLP 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1296">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="946dd-1297">일정 정리 페이지가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1297">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="946dd-1298">인시던트 알림 경고에서 서식 문제가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1298">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2007-july-27"></a><span data-ttu-id="946dd-1300">버전 2007: 7월 27일</span><span class="sxs-lookup"><span data-stu-id="946dd-1300">Version 2007: July 27</span></span>
<span data-ttu-id="946dd-1301">*버전 2007(빌드 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1301">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="946dd-1302">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-1302">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="946dd-1303">버전 2007: 7월 20일</span><span class="sxs-lookup"><span data-stu-id="946dd-1303">Version 2007: July 20</span></span>
<span data-ttu-id="946dd-1304">*버전 2007 (빌드 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1304">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="946dd-1305">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-1305">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="946dd-1306">버전 2007: 7월 15일</span><span class="sxs-lookup"><span data-stu-id="946dd-1306">Version 2007: July 15</span></span>
<span data-ttu-id="946dd-1307">*버전 2007(빌드 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1307">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1309">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1309">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1310">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1310">Excel</span></span>

- <span data-ttu-id="946dd-1311">**Excel에서 세련된 Visio 다이어그램 만들기:** 워크시트에 데이터를 입력하여 순서도 또는 조직도를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1311">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="946dd-1312">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1312">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1315">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1315">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-1316">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-1316">Access</span></span>

- <span data-ttu-id="946dd-1317">연결된 SQL 표를 새로고침할 경우 연결된 표 관리자에서 기본 키에 관한 메시지를 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1317">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="946dd-1318">쿼리 편집기의 쿼리가 스크롤되어 보이지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1318">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="946dd-1319">쿼리 실행이 예상했던 시간보다 거의 두 배 이상 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1319">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="946dd-1320">Microsoft Access에서 연결된 SQL Server 표의 ID 열이 식별되지 않아서 행이 올바르지 않게 삭제된 것으로 보고되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1320">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="946dd-1321">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1321">Excel</span></span>

- <span data-ttu-id="946dd-1322">최근 사용한 목록에 http 또는 https가 아닌 URL이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1322">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="946dd-1323">페이지 나누기 미리 보기에서 여러 시트가 포함 된 통합 문서를 로드할 때 오류 또는 중단이 발생할 수 있는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1323">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="946dd-1324">표와 연결된 쿼리를 편집하지 않은 경우에도 특정 버전의 Excel에서 만든 데이터 모델 표를 '표 미리 보기'에서 볼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1324">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="946dd-1325">이름 정의 \ 이름 적용 대화 상자에서 상대\절대’ 참조 무시를 사용 안 함으로 설정하면 서식이 작동하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1325">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="946dd-1326">SharePoint/OneDrive에 저장 시 사용자 지정 리본 탭의 CustomUI XML이 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1326">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="946dd-1327">파일에 읽기 전용 권장 설정이 되어 있는 경우 통합 문서가 읽기 전용으로 유지 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1327">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="946dd-1328">페이지 나누기 미리 보기에서 여러 시트가 포함 된 통합 문서를 로드할 때 오류 또는 중단이 발생할 수 있는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1328">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="946dd-1329">방사형 차트의 주 눈금선에 제대로 서식을 지정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1329">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="946dd-1330">고급 데이터 필터를 해제하면 표 서식이 손실될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1330">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="946dd-1331">포함된 PDF 문서의 전체 경로가 파일 이름만이 아니라 문서 캡션에 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1331">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="946dd-1332">Wolfram 클라우드 커넥터를 사용하지 않음으로 설정한 다음 Excel 통합 문서를 저장하고 다시 여는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1332">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="946dd-1333">해 찾기 추가 기능을 사용한 상태에서 Excel을 부팅하면 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1333">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-1334">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1334">Outlook</span></span>

- <span data-ttu-id="946dd-1335">‘받는 사람’ 줄에 130명 이상이 있을 경우 Outlook이 중단되는 문제를 해결했으며, 해당 텍스트를 렌더링하는 성능도 향상했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1335">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="946dd-1336">해상도가 다른 여러 모니터를 사용할 때 입력 방법 편집기(IME) 창이 IME를 통해 입력되는 기본 텍스트와 겹치는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1336">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="946dd-1337">이벤트가 2일 이상 경과하고 이후 동일한 종료 시간을 표시하는 '할 일 모음'의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1337">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="946dd-1338">끌어서 놓기를 통해 파일 시스템으로으로 복사한 파일의 첨부 생성 날짜가 4501년 1월 1일로 설정되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1338">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="946dd-1339">사용자가 메일 배포 목록에서 '다른 사람으로 보내기' 혹은 '대신 보내기'를 할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1339">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="946dd-1340">관리자의 일정에서 기존 일정 약속을 편집할 때 대리인에게 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1340">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="946dd-1341">이전에 저장한 약속을 닫을 때 “다른 사용자 또는 다른 창에서 변경했기 때문에 해당 항목을 저장할 수 없음” 오류가 표시되는 문제가 수정 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1341">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="946dd-1342">“항목에 대한 기본 폴더에 복사본을 만드시겠습니까?”</span><span class="sxs-lookup"><span data-stu-id="946dd-1342">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="946dd-1343">공유 폴더 다운로드를 선택하지 않은 경우 공유 일정 모임 “응답 옵션”에 “전달 허용” 옵션이 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1343">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="946dd-1344">보안 대화 상자에서 "저장" 옵션을 선택할 때 사용자가 테넌트 외부에서 로컬 컴퓨터에 OneDrive 첨부 파일을 저장할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1344">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="946dd-1345">공유 일정을 사용한 후 몇 분 동안 Outlook 사용자의 메시지 목록이 업데이트 되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1345">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="946dd-1346">일주일 이내에 진행될 모임의 시간을 일정 미리 알림에서 정확하게 표시하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1346">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="946dd-1347">메시지에 이미지를 인라인으로 삽입한 다음 메시지를 초안으로 저장하면 이미지 크기가 조정되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1347">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="946dd-1348">제목을 편집한 후 NDR 메시지 본문이 유니코드에서 ASCII로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1348">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="946dd-1349">일본에서 미니 캘린더의 날짜가 굵게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1349">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-1350">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1350">PowerPoint</span></span>

- <span data-ttu-id="946dd-1351">실시간 공동 작성 세션이 진행 동안 사용자의 현재 상태 색 표시기가 공동 작성 갤러리에서 새로고침되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1351">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="946dd-1352">슬라이드의 텍스트 영역에 HTML을 붙여넣는 대신 슬라이드 맨 위에 있는 텍스트 상자에 붙여넣는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1352">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="946dd-1353">발표자 보기에서 모든 슬라이드를 선택하고 나서 발표자 보기를 종료하고 Alt+Tab을 사용하여 슬라이드 쇼로 돌아가 '쇼 종료'를 클릭할 때 처리되지 않은 예외가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1353">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-1354">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1354">Project</span></span>

- <span data-ttu-id="946dd-1355">Project에서 SharePoint 문서 라이브러리에 PDF/XPS를 저장 할 수 없는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1355">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="946dd-1356">Project Web App에서 URL이 .com으로 끝나는 경우 Project 데스크톱 클라이언트에서 프로젝트를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1356">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="946dd-1357">특정 XML 파일을 열때 Project가 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1357">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="946dd-1358">Project Web App에서 URL이 '.com'으로 끝나는 경우 Project 데스크톱 클라이언트에서 프로젝트를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1358">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="946dd-1359">여러 종속성이 있는 작업을 붙여 넣는 경우 일부 종속성이 제대로 복사 되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1359">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="946dd-1360">자원 배정 대화 상자에서 선택한 작업이 작업 게시판 보기에서 선택 된 작업과 같지 않은 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1360">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="946dd-1361">프로젝트 요약 작업(프로젝트 시작/작업 필드)을 변경할 때 ProjectBeforeTaskChange 이벤트가 발생하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1361">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="946dd-1362">기간 고정 작업이 100% 완료 상태이지만 실제 완료 날짜가 지정되지 않은 경우 작업 완료율(%)이 100% 미만으로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1362">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="946dd-1363">초기 계획 재설정 또는 업데이트로 기간별 예산 비용/작업 자원이 변경되고 초기 계획에 잘못된 예산 값이 반영 될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1363">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="946dd-1364">정부 커뮤니티 클라우드 환경의 Project Planner 링크가 사용 안 함으로 설정되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1364">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="946dd-1365">라이브러리가 최신 모드인 경우 SharePoint 문서 라이브러리에서 Project 파일을 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1365">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-1366">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1366">Word</span></span>

- <span data-ttu-id="946dd-1367">Office 리본의 서식 지우기 단추를 통해 메모 창에서 서식을 지울 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1367">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="946dd-1368">Word, Excel 또는 PowerPoint 파일에 SVG(확장 가능한 벡터 그래픽)를 삽입한 후 파일을 저장하고 닫은 다음 파일을 다시 열었을 때 읽기 어려워 보이는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1368">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="946dd-1369">눈금자가 표시되지 않을 때 표 크기를 변경 하는 경우 백그라운드에서 실행되는 다른 응용 프로그램에서 번쩍임이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1369">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="946dd-1370">공동 작성 모드에서 가끔 메모 회신이 메모 창에 표시되지는 않지만 수정 창에는 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1370">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="946dd-1371">병합 충돌이 발생하고 사용자가 변경 내용을 삭제하도록 이미 선택했을 때 공동 작성 모드에서 발생하는 문제를 해결했습니다. 더 이상 변경 내용을 저장하거나 삭제하는 옵션이 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1371">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="946dd-1372">HTML 하이퍼링크 색이 제대로 렌더링되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1372">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="946dd-1373">Word에서 자주 여는 문서의 수가 50개를 초과하는 경우 문서를 저장하고 연 후 해당 문서에 대한 수정 내용이 없는 경우에도 수정 기록이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1373">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="946dd-1374">공동 작성 중 자동 저장과 관련 된 문제가 해결 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1374">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="946dd-1375">매크로가 포함된 파일을 새 이름으로 저장하려고 하면 사용자가 입력한 내용에 상관없이 파일이 .docx 확장명과 파일 이름 ‘WRO0004.docx’로 저장되어 문서를 사용할 수 없게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1375">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-1376">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1376">Office Suite</span></span>

- <span data-ttu-id="946dd-1377">시간 문제 때문에 Office 파일을 닫을 때 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1377">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="946dd-1378">서비스가 올바르게 계산 된 제품이 추가 되었는지 확인하여 수정 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1378">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="946dd-1379">새로 추가한 제품(새 구성에도 존재 하는지 확인)을 필터링하고 기존 제품 출시 ID 끝에 추가 했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1379">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2006-july-09"></a><span data-ttu-id="946dd-1381">버전 2006: 7월 9일</span><span class="sxs-lookup"><span data-stu-id="946dd-1381">Version 2006: July 09</span></span>
<span data-ttu-id="946dd-1382">*버전 2006 (빌드 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1382">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1384">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1384">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1385">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1385">Excel</span></span>

- <span data-ttu-id="946dd-1386">**PDF 연결 설정:** PDF로 연결하고 PDF에서 데이터를 가져오고 새로 고칩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1386">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="946dd-1387">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1387">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="946dd-1388">**수식에 사용할 변수 만들기:** LET 기능으로 성능, 가독성 및 구성성을 향상시킵니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1388">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="946dd-1389">이 함수를 사용하면 새로운 공식 또는 기존 공식으로 명명된 변수를 작성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1389">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="946dd-1390">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1390">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="946dd-1391">[블로그 게시물](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-1391">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="946dd-1392">**Excel의 키보드 바로 가기 키:** Excel의 바로 가기 키가 업데이트되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1392">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1393">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1393">Outlook</span></span>

- <span data-ttu-id="946dd-1394">**간단한 설문 조사로 Outlook에 설문 조사 만들기**: 설문 조사를 쉽게 작성하고 투표를 수집하며 전자 메일에서 결과를 볼 수 있습니다 [자세한 내용 보기](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="946dd-1394">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="946dd-1395">**전자 메일로 사진을 보낼 때 선명도를 높게 유지:.** 새 Outlook 설정을 사용하여 사진을 전자 메일 콘텐츠에 첨부해서 보낼 때 압축을 제한할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1395">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1398">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1398">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-1399">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-1399">Access</span></span>

- <span data-ttu-id="946dd-1400">이 문제는 해결되었으며, ID(예: 자동 번호) 필드가 포함된 연결된 SQL 테이블을 Access에 성공적으로 삽입할 수 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1400">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="946dd-1401">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1401">Excel</span></span>

- <span data-ttu-id="946dd-1402">계정에서 로그아웃한 경우 데이터 연결을 만들 때 발생할 수 있는 충돌을 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1402">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1403">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1403">Outlook</span></span>

- <span data-ttu-id="946dd-1404">보안 대화 상자에서 "저장" 옵션을 선택할 때 사용자가 테넌트 외부에서 로컬 컴퓨터에 OneDrive 첨부 파일을 저장할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1404">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="946dd-1405">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1405">Office Suite</span></span>

- <span data-ttu-id="946dd-1406">이전 AppV51의 회귀 분석을 수정하기 위해 새로운 AppV51 드롭을 다시 보고했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1406">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="946dd-1407">레지스트리 TabProcGrowth 값이 REG_SZ 유형이고 값이 "0"인 동안 추가 기능이 활성화되는 동안 office 호스트가 창에서 충돌했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1407">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="946dd-1408">레지스트리 TabProcGrowth 값은 다음 네 가지 경로 중 하나에 속할 수 있습니다. HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main 이렇게 변경하면 이 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1408">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2006-june-25"></a><span data-ttu-id="946dd-1410">버전 2006: 6월 25일</span><span class="sxs-lookup"><span data-stu-id="946dd-1410">Version 2006: June 25</span></span>
<span data-ttu-id="946dd-1411">*버전 2006 (빌드 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1411">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1413">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1413">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="946dd-1414">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-1414">Visio</span></span>

- <span data-ttu-id="946dd-1415">**Excel에서 다듬은 Visio 다이어그램 만들기:** 워크시트의 데이터를 기반으로 흐름도 또는 조직도 생성합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1415">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1418">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1418">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-1419">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-1419">Access</span></span>

- <span data-ttu-id="946dd-1420">이제 이 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1420">This problem is now resolved.</span></span> <span data-ttu-id="946dd-1421">이 과정에서 더 많은 문제가 발생하면 팀원들에게 알려주시기 바랍니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1421">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-1422">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1422">Outlook</span></span>

- <span data-ttu-id="946dd-1423"><span style="display:inline !important;">끌어서 놓기를 통해<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;"> &nbsp;4501년 1월 1일 로 설정하여 파일 시스템에 복사한 첨부 파일의 &nbsp;작성일자 를 사용자에게 표시하는 문제를 해결합니다.</span></span><span class="sxs-lookup"><span data-stu-id="946dd-1423"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="946dd-1424"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">공유 일정관리의 개선된 사용자가 일정관리 오류를 볼 수 있는 문제를 해결합니다.</span></span><span class="sxs-lookup"><span data-stu-id="946dd-1424"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="946dd-1425"><span style="display:inline !important;">Outlook에서 받은 편지함 복구 도구를 실행하라는 메시지를 계속 표시하도록 하는 문제를 해결합니다.</span></span><span class="sxs-lookup"><span data-stu-id="946dd-1425"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="946dd-1426"><span style="display:inline !important;">기능 제안에서 기능을 검색하여 결과를 반환하지 않고 사용자에게 새 기능 아이디어를 제출할 수 있는 옵션이 없는 문제를 해결합니다.</span></span><span class="sxs-lookup"><span data-stu-id="946dd-1426"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2006-june-18"></a><span data-ttu-id="946dd-1428">버전 2006: 6월 18일</span><span class="sxs-lookup"><span data-stu-id="946dd-1428">Version 2006: June 18</span></span>
<span data-ttu-id="946dd-1429">*버전 2006 (빌드 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1429">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1431">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1431">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1432">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1432">Excel</span></span>



- <span data-ttu-id="946dd-1433">**폴더 고정에 저장:** 폴더를 고정하면 Office 파일을 더 쉽게 저장할 수 있습니다. 새 파일이 저장될 때 사용자가 사용 가능한 폴더를 더 많이 관리하기를 원한다는 피드백을 받았습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1433">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="946dd-1434">저장 대화 상자에서 폴더를 고정하는 새로운 기능을 제공하게 되어 기쁘게 생각합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1434">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="946dd-1435">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1435">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="946dd-1436">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-1436">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1437">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1437">PowerPoint</span></span>

- <span data-ttu-id="946dd-1438">**폴더 고정에 저장:** 폴더를 고정하면 Office 파일을 더 쉽게 저장할 수 있습니다. 새 파일이 저장될 때 사용자가 사용 가능한 폴더를 더 많이 관리하기를 원한다는 피드백을 받았습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1438">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="946dd-1439">저장 대화 상자에서 폴더를 고정하는 새로운 기능을 제공하게 되어 기쁘게 생각합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1439">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="946dd-1440">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1440">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="946dd-1441">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-1441">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1442">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1442">Word</span></span>

- <span data-ttu-id="946dd-1443">**폴더 고정에 저장:** 폴더를 고정하면 Office 파일을 더 쉽게 저장할 수 있습니다. 새 파일이 저장될 때 사용자가 사용 가능한 폴더를 더 많이 관리하기를 원한다는 피드백을 받았습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1443">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="946dd-1444">저장 대화 상자에서 폴더를 고정하는 새로운 기능을 제공하게 되어 기쁘게 생각합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1444">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="946dd-1445">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 더 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1445">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="946dd-1446">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-1446">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1449">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1449">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1450">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1450">Excel</span></span>

- <span data-ttu-id="946dd-1451">SharePoint/OneDrive에 저장하는 경우 사용자 지정 리본 탭이 CustomUI XML을 제거하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1451">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1452">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1452">Outlook</span></span>

- <span data-ttu-id="946dd-1453">클라우드 설정을 사용할 때 Ctrl+클릭이 작동을 중지하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1453">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="946dd-1454">프로젝트</span><span class="sxs-lookup"><span data-stu-id="946dd-1454">Project</span></span>

- <span data-ttu-id="946dd-1455">100% 완료로 표시된 작업이 100% 미만으로 잘못 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1455">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2006-june-11"></a><span data-ttu-id="946dd-1457">버전 2006: 6월 11일</span><span class="sxs-lookup"><span data-stu-id="946dd-1457">Version 2006: June 11</span></span>
<span data-ttu-id="946dd-1458">*버전 2006 (빌드 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1458">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1460">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1460">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="946dd-1461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1461">PowerPoint</span></span>

- <span data-ttu-id="946dd-1462">**PowerPoint의 스트림 비디오 성능 향상:** Microsoft Stream 비디오의 재생 성능을 개선하여 비디오 로드 시간을 최소화하고 원활한 보기 환경을 조성했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1462">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="946dd-1463">Microsoft Stream의 회사 비디오를 사용하여 더 나은 프레젠테이션을 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1463">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1464">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1464">Word</span></span>

- <span data-ttu-id="946dd-1465">**벡터의 텍스트 보존:** 이제 Excel, Word 및 PowerPoint에서 이러한 개체를 변환할 때 맵, 차트 및 기타 SVG 벡터의 텍스트를 유지할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1465">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1468">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1468">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1469">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1469">Excel</span></span>

- <span data-ttu-id="946dd-1470">Excel이 OneDrive를 사용할 때 때때로 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1470">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="946dd-1471">차트 축의 사용자 지정 값이 올바르게 적용되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1471">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="946dd-1472">정의된 이름의 수식이 여러 개 포함된 워크시트가 파일을 저장할 때 더 오래 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1472">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="946dd-1473">사용 가능한 프린터 목록에 프린터 이름이 중복되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1473">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="946dd-1474">사용자가 병합된 열을 삭제했을 때 성능시간이 향상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1474">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="946dd-1475">추가 기능이 사용자 지정 순서가 아니라 알파벳 순서로 로드되었기 때문에 "이 통합 문서는 다른 통합 문서에서 현재 참조하고 있으며 닫을 수 없습니다"라는 오류 메시지가 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1475">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="946dd-1476">Excel과 일부 타사 보조 기술 응용 프로그램 간의 글꼴을 관리할 때 메모리가 손상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1476">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="946dd-1477">동일한 통합 문서에서 북마크가 지정된 하이퍼링크를 클릭하면 통합 문서이 숨겨지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1477">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="946dd-1478">일부 복사 및 붙여넣기 차트 링크에서 범용 주소가 아닌 매핑된 드라이브 주소를 사용하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1478">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="946dd-1479">팀을 통해 Excel 창을 공유할 때 Ctrl+Shift+화살표 키를 사용하여 스크롤한 후 Excel이 응답하지 않는문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1479">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="946dd-1480">추가 기능에서 noSelect 잠금 기능이 있는 도형이 포함된 워크시트에서 호스트 항목을 요청할 때 Excel이 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1480">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="946dd-1481">도표 시트에 PivotTables를 삽입하려고 할 때 Excel이 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1481">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1482">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1482">Outlook</span></span>

- <span data-ttu-id="946dd-1483">해상도가 다른 여러 모니터를 사용할 때 IME(입력 방법 편집기) 창이 IME를 통해 입력되는 기본 텍스트와 겹치는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1483">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="946dd-1484">새 전자 메일 메시지를 작성할 때 템플릿을 보면 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1484">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="946dd-1485">Outlook 버전 1911 이후 사용자가 Exchange 2010 공용 폴더를 교환할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1485">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="946dd-1486">Office 리본에서 그룹 일정관리의 분류 단추가 비활성화된 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1486">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="946dd-1487">Outlook에서 M365 Business Plus 계획에 있는 서비스 비용을 지불한 사용자를 위해 Data Loss Protection 정책을 활성화하지 못한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1487">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="946dd-1488">일부 Windows 빌드에서 Outlook이 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1488">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="946dd-1489">사용자가 게스트 사용자와 일정관리를 공유할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1489">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="946dd-1490">사용자가 자정 임계값에 걸쳐 있는 일정관리 항목을 종일 이벤트로 보는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1490">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="946dd-1491">상위 DPI 모니터의 사용자에 대한 폴더 속성의 온라인 보관 드롭다운이 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1491">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="946dd-1492">폴더가 있는 문제를 해결했습니다. 사용자가 폴더 간에 항목을 이동할 때 BeforeItemMove 이벤트가 제대로 실행되지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1492">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="946dd-1493">우리는 두 개의 추가 기능이 리본의 동일한 그룹에 단추를 추가했을 때 Outlook이 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1493">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="946dd-1494">일반 텍스트 전자 메일의 하이퍼링크로 작업할 때 사용자가 아웃룩에서 충돌을 겪게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1494">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="946dd-1495">Outlook에서 RFC2231로 인코딩된 긴 파일 이름을 구문 분석할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1495">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="946dd-1496">Outlook 사용자가 화면 판독기를 사용할 때 간헐적인 중단이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1496">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="946dd-1497">Outlook에서 대화 상대가 충돌하면 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1497">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1498">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1498">PowerPoint</span></span>

- <span data-ttu-id="946dd-1499">양식 기반 인증을 사용하여 서버 구성 파일을 여는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1499">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="946dd-1500">차트/통합 문서가 내장된 PowerPoint 파일에서 파일을 저장할 때 오류가 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1500">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="946dd-1501">프리젠테이션 영역을 확대/축소하여 확대된 선택 영역과 마우스 포인터 사이에 간격이 생긴 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1501">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="946dd-1502">마우스 휠을 사용하여 확대/축소 후 슬라이드의 중심이 맞지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1502">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="946dd-1503">영어 스위스(QWERTZ) 키보드를 사용할 때 키보드 단축키와 철자 검사가 예상대로 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1503">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="946dd-1504">사용자가 닫은 주석 창이 자동으로 다시 열리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1504">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="946dd-1505">한 슬라이드의 편집기가 다음 슬라이드와 겹치는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1505">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="946dd-1506">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1506">Project</span></span>

- <span data-ttu-id="946dd-1507">프로젝트 요약 작업(프로젝트 시작/작업 필드)이 변경될 때 ProjectBeforeTaskChange 이벤트가 발생하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1507">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="946dd-1508">100% 완료로 표시된 작업이 100% 미만으로 잘못 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1508">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="946dd-1509">Options(옵션)을 클릭한 후 Project가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1509">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="946dd-1510">상위 계획이 삭제된 후 연결이 끊어진 작업을 삭제하거나 다시 할당하지 못하도록 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1510">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="946dd-1511">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-1511">Visio</span></span>

- <span data-ttu-id="946dd-1512">고정된 종속 코드에 회귀가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1512">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="946dd-1513">이제 SharePoint Onprem에서 실행되는 Visio 서비스에서 이미지가 렌더링되고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1513">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1514">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1514">Word</span></span>

- <span data-ttu-id="946dd-1515">주석 창의 타임스탬프가 시스템 로캘 시간을 기반으로 하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1515">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="946dd-1516">URL에 쿼리 구성 요소가 포함되어 있을 때 사용자 정의 문서 배달(aspx)에서 Word 문서를 여는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1516">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="946dd-1517">텍스트 복사 및 붙여넣기가 주석 창에 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1517">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="946dd-1518">코멘트의 하이퍼링크가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1518">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="946dd-1519">프리젠테이션 영역을 확대/축소하여 확대된 선택 영역과 마우스 포인터 사이에 간격이 생긴 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1519">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="946dd-1520">웹 앱과 데스크톱 응용 프로그램 간의 동기화가 되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1520">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="946dd-1521">댓글 힌트 거품이 100% 확대/축소 시 흐리게 나타나는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1521">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="946dd-1522">우리는 빈 문서에 새로운 의견을 추가해도 아무런 도움이 되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1522">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="946dd-1523">Outlook 일정을 위한 WordMail에 HTML 붙여넣기가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1523">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="946dd-1524">공동 작성한 세션의 코멘트에 회신하는 것이 때로는 Word의 중단을 야기할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1524">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="946dd-1525">100개 이상의 항목을 포함하는 문서에 색인을 삽입하거나 업데이트하는 경우, 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1525">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="946dd-1526">정책 Word 2007 이상 바이너리 문서와 서식 파일을 사용하는 경우 일부 공동 작성 사례에서 오류가 발생하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1526">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="946dd-1527">사용자 지정 xml 값이 있는 파일이 매우 천천히 열리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1527">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="946dd-1528">경로 이름이 32K보다 큰 파일이 열리지 않고 적절한 오류 메시지가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1528">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="946dd-1529">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1529">Office Suite</span></span>

- <span data-ttu-id="946dd-1530">OS를 종료하면 InTune을 통한 Office 365 ProPlus 배포가 일시 중지되는 문제를 조사하고 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1530">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="946dd-1531">라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1531">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="946dd-1532">이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. </span><span class="sxs-lookup"><span data-stu-id="946dd-1532">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2005-june-08"></a><span data-ttu-id="946dd-1534">버전 2005: 6월 8일</span><span class="sxs-lookup"><span data-stu-id="946dd-1534">Version 2005: June 08</span></span>
<span data-ttu-id="946dd-1535">*버전 2005 (빌드 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1535">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1537">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1537">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="946dd-1538">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1538">PowerPoint</span></span>

- <span data-ttu-id="946dd-1539">글꼴 바꾸기 대화 상자에서 시스템에 설치된 글꼴 대신 글꼴 교체 드롭다운에 프레젠테이션 안의 글꼴만 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1539">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2005-june-04"></a><span data-ttu-id="946dd-1541">버전 2005: 6월 4일</span><span class="sxs-lookup"><span data-stu-id="946dd-1541">Version 2005: June 04</span></span>
<span data-ttu-id="946dd-1542">*버전 2005 (빌드 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1542">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1544">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1544">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="946dd-1545">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-1545">Access</span></span>

- <span data-ttu-id="946dd-1546">**시간을 관리하세요! 날짜/시간 확장 데이터 유형의 정확도가 더 우수해 졌습니다.:** 향상된 새 데이터 유형을 소개합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1546">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="946dd-1547">SQL과의 구문 호환성을 높이고 날짜와 시간을 포함하는 레코드의 정확성과 세부 정보 수준을 높이기 위해 DateTime2 데이터 유형을 Access로 구현하고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1547">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="946dd-1548">이 추가 날짜 및 시간 데이터 유형은 더 큰 날짜 범위(0001-01-01 ~ 9999-12-31)를 포함하며, 더 높은 시간 정밀도(초 대신 나노초)를 제공하여 계산을 수행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1548">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="946dd-1549">사용하도록 설정하려면 새 필드 > 날짜 & 시간 확장을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1549">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="946dd-1550">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1550">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="946dd-1551">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1551">Excel</span></span>

- <span data-ttu-id="946dd-1552">**Excel 내의 Power BI에 있는 데이터셋에서 피벗 테이블 생성:** 몇 번의 클릭으로 Power BI에 저장된 데이터셋에 연결된 피벗 테이블은 Excel에서 생성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1552">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="946dd-1553"> 이렇게 하면 PivotTables와 Power BI를 모두 최대한 활용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1553">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="946dd-1554">보안 Power BI 데이터셋에서 PivotTables를 사용하여 데이터를 계산, 요약 및 분석할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1554">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1555">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1555">Outlook</span></span>

- <span data-ttu-id="946dd-1556">**이전 Outlook 세션에서 항목을 빠르게 다시 여는 옵션:** 이전 Outlook 세션에서 항목을 빠르게 다시 여는 옵션을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1556">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1559">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1559">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="946dd-1560">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1560">PowerPoint</span></span>

- <span data-ttu-id="946dd-1561">이렇게 하면 사용자가 파일에 최신 및 기존 주석을 모두 가지고 있을 때 충돌이 발생하여 주석을 업그레이드하게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1561">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-1562">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1562">Office Suite</span></span>

- <span data-ttu-id="946dd-1563">검증을 확인했습니다.기본적으로 Bing Addon 설치 검증을 true로 설정하고 MSI 반환 성공을 설치 성공으로 간주하여 설치 실패율 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1563">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2005-may-29"></a><span data-ttu-id="946dd-1565">버전 2005: 5월 29일</span><span class="sxs-lookup"><span data-stu-id="946dd-1565">Version 2005: May 29</span></span>
<span data-ttu-id="946dd-1566">*버전 2005(빌드 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1566">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1568">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1568">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="946dd-1569">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1569">Excel</span></span>

- <span data-ttu-id="946dd-1570">**보기 설정:** Excel 데스크톱에서 다른 사용자와 공동 작업하는 동안 정렬/필터합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1570">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1571">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1571">Outlook</span></span>

- <span data-ttu-id="946dd-1572">**Outlook 토스트 알림에 추가 버튼이 추가되었습니다.이제 윈도우즈 10에서 아웃룩을 실행할 때 Outlook 토스트 알림에** 빠른 작업 버튼이 나타납니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1572">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1575">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1575">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="946dd-1576">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1576">Outlook</span></span>

- <span data-ttu-id="946dd-1577">Windows 10 서버 버전 사용자에게 바이러스 백신 상태: 올바르지 않음이라는 경고 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1577">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="946dd-1578">이 Windows 버전에서는 바이러스 백신 탐지를 지원하지만 안티 바이러스가 올바르게 설치되었음에도 불구하고 바이러스 백신 프로그램을 찾을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1578">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="946dd-1579">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1579">Office Suite</span></span>

- <span data-ttu-id="946dd-1580">레지스트리 키 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth가 0으로 설정되어있는 동안 추가 기능이 활성화될 때 사무실 호스트가 Windows에서 충돌했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1580">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="946dd-1581">이렇게 변경하면 이 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1581">This change would fix this issue.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2005-may-21"></a><span data-ttu-id="946dd-1583">버전 2005: 5월 21일</span><span class="sxs-lookup"><span data-stu-id="946dd-1583">Version 2005: May 21</span></span>
<span data-ttu-id="946dd-1584">*버전 2005(빌드 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1584">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)




[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1588">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1588">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1589">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1589">Excel</span></span>

- <span data-ttu-id="946dd-1590">팀을 통해 Excel 창을 공유할 때 Ctrl+Shift+화살표 키를 사용하여 스크롤한 후 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1590">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="946dd-1591">경우에 따라 동일한 통합 문서 안의 위치에 대한 하이퍼링크를 클릭하면 통합 문서이 숨겨집니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1591">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="946dd-1592">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1592">Outlook</span></span>

- <span data-ttu-id="946dd-1593">회신/전송 레이블에 대한 clp 감사 이벤트에서 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1593">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="946dd-1594">관리자 알림에서 피드백을 제출할 때 사용자가 충돌을 겪게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1594">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2005-may-14"></a><span data-ttu-id="946dd-1596">버전 2005: 5월 14일</span><span class="sxs-lookup"><span data-stu-id="946dd-1596">Version 2005: May 14</span></span>
<span data-ttu-id="946dd-1597">*버전 2005(빌드 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1597">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1599">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1599">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1600">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1600">Excel</span></span>

- <span data-ttu-id="946dd-1601">**민감도 레이블 자동 적용 또는 권장:** Office는 감지되는 중요한 콘텐츠에 기반하여 민감도 레이블을 권장하거나 자동으로 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1601">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1602">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1602">PowerPoint</span></span>

- <span data-ttu-id="946dd-1603">**이어폰이 원격 조정 기능을 수행하여 클릭커가 필요하지 않습니다.** Surface Earbuds를 사용하여 PowerPoint 프레젠테이션을 컨트롤합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1603">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="946dd-1604">중요: 제스처를 사용하여 프레젠테이션을 제어하려면 Windows 10용 Surface Audio 앱에서 Surface Earbuds를 페어링해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1604">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="946dd-1605">Windows 10에서 Surface Audio 앱을 시작하는 방법에 대한 지침은 여기에서 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1605">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="946dd-1606">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1606">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="946dd-1607">**민감도 레이블 자동 적용 또는 권장:** Office는 감지되는 중요한 콘텐츠에 기반하여 민감도 레이블을 권장하거나 자동으로 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1607">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1608">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1608">Word</span></span>

- <span data-ttu-id="946dd-1609">**민감도 레이블 자동 적용 또는 권장:** Office는 감지되는 중요한 콘텐츠에 기반하여 민감도 레이블을 권장하거나 자동으로 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1609">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1612">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1612">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="946dd-1613">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1613">Excel</span></span>

- <span data-ttu-id="946dd-1614">차트에 사용되는 사용자 지정 오차 막대 대화 상자에서 셀 참조 편집 컨트롤의 크기를 늘렸습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1614">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="946dd-1615">차트 데이터 표에서 날짜 축에 있는 값을 잘못 렌더링할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1615">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="946dd-1616">페이지 레이아웃이나 페이지 나누기 미리 보기를 실행한 후에 페이지 나누기를 해제하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1616">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="946dd-1617">계열 데이터가 있는 열을 숨기거나 숨기기를 해제한 후에 차트 선 스타일이 손실될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1617">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="946dd-1618">필터링된 목록에 열을 삽입하는 데 예상보다 오래 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1618">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="946dd-1619">인쇄할 때 양식 컨트롤에 있는 확인란 크기 조정 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1619">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="946dd-1620">파일 경로가 너무 길면 파일을 다시 연 후 외부 링크가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1620">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="946dd-1621">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1621">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="946dd-1622">경우에 따라 Application.Evaluate(VBA)가 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1622">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="946dd-1623">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1623">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="946dd-1624">이와 같이 변경하면 CF(조건부 서식) 정보가 제대로 파일에 저장되지 않는 문제를 해결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1624">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="946dd-1625">이 변경 사항은 LINEST 함수가 올바른 값을 반환하는 경우에도 차트 추세선 R 제곱값(강제적인 y 절편)이 올바르지 않은 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1625">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="946dd-1626">이 변경 사항은 사용자 지정된 차트 추세선 서식이 항상 저장되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1626">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="946dd-1627">레거시 "공유 통합 문서" 모드를 사용하여 통합 문서의 새 시트에 변경 내용을 나열할 때 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1627">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="946dd-1628">"음수이면 반전" 옵션을 사용하도록 설정한 경우 피벗 차트에서 사용자 지정 서식이 저장되지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1628">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="946dd-1629">"음수이면 반전" 옵션을 선택한 경우 피벗 차트에서 단일 데이터 요소에 대한 사용자 지정 서식이 저장되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1629">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="946dd-1630">이 변경 사항으로 CSV 파일에 '@' 문자가 업로드되어 '@' 문자 다음 문자열이 수식으로 변환되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1630">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="946dd-1631">SEQUENCE 함수에서 10진수 값이 올바르게 반올림되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1631">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="946dd-1632">OneNote</span><span class="sxs-lookup"><span data-stu-id="946dd-1632">OneNote</span></span>

- <span data-ttu-id="946dd-1633">줄 바꿈이 세로 탭으로 저장되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1633">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1634">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1634">Outlook</span></span>

- <span data-ttu-id="946dd-1635">사용자가 개인 연락처 그룹을 모임 참석자로 추가할 수 없게 하는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1635">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="946dd-1636">Office 리본에서 그룹 일정관리의 분류 단추를 사용할 수 없는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1636">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="946dd-1637">Windows 업데이트 후 로컬로 저장된 .msg 혹은 .oft 파일을 열 때 Outlook의 작동이 중단되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1637">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="946dd-1638">구현되거나 작동하지 않는 그룹 폴더가 있는 엔터프라이즈 고객이 있는 경우 Outlook에 "응답하지 않음" 메시지가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1638">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="946dd-1639">Outlook Desktop 클라이언트에서 사용자가 클릭했던 매우 긴 안전 링크를 잘라서 로드하지 못한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1639">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="946dd-1640">서버와 동기화할 때 DBCS(더블 바이트 문자 집합) 문자를 포함하는 이름의 Outlook 폴더가 간헐적으로 사라지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1640">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="946dd-1641">이 문제를 해결하기 위해서 Outlook을 IMAP 계정으로 구성하고 로캘이 일본어로 설정된 시스템에서 실행해야 했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1641">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="946dd-1642">사용자의 기본 편지함이 아닌 다른 편지함에 대해 만들어진 삭제 규칙이 유효하지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1642">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="946dd-1643">암호화된 메시지를 전달할 때 첨부 파일이 삭제되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1643">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="946dd-1644">2개월 넘게 참석하지 않은 모임의 제목이 일정 정리에 표시되지 않는 문제가 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1644">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="946dd-1645">대규모 HTML 메시지를 전달할 때 사용자에게 잘린 메시지 본문이 표시되던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1645">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="946dd-1646">그룹 정책을 통해 S/MIME 기본 서명 구성을 적용하는 기능이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1646">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1647">PowerPoint</span></span>

- <span data-ttu-id="946dd-1648">사용자가 메모를 게시하지 않고 작성하고 메모 창을 닫은 다음, 새 창을 열어 여러 슬라이드를 탐색한 후 창을 닫고, 마지막으로 원본 프레젠테이션에서 메모 창을 다시 열 때 초안 메모를 사용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1648">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="946dd-1649">별표(\*) 기호 위로 마우스를 가져가면 문서를 업데이트할 마지막 사람의 사용자 이름과 날짜가 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1649">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="946dd-1650">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1650">Project</span></span>

- <span data-ttu-id="946dd-1651">양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChange 이벤트가 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1651">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="946dd-1652">SharePoint 작업 목록에 연결된 프로젝트에서 보드 상태 필드를 변경하면 Project가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1652">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="946dd-1653">이전 버전의 Project에서 만든 프로젝트를 저장하면 Project가 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1653">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="946dd-1654">프로젝트가 프로젝트 웹 앱에 연결되어 있고 소수점 구분 기호가 쉼표인 경우 Lag를 추가할 때 TaskDependency Add 메서드가 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1654">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-1655">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1655">Word</span></span>

- <span data-ttu-id="946dd-1656">공동 작업 모드에서 문서에 메모를 삽입할 때 항상 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1656">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="946dd-1657">이 변경 내용으로 @멘션을 클릭하면 사용자 카드가 깜빡이는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1657">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="946dd-1658">"책갈피 표시" 옵션을 사용하도록 설정하면 책갈피가 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1658">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="946dd-1659">이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1659">This has been fixed.</span></span>

- <span data-ttu-id="946dd-1660">초안 메모가 포함된 문서를 닫을 때 초안 메모를 저장하지 않고 문서를 닫을지 묻는 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1660">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="946dd-1661">이 메시지를 취소하면 문서를 열어두지 않고 닫습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1661">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="946dd-1662">머리글을 복사하여 붙여넣는 것과 관련된 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1662">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="946dd-1663">게시된 메모를 번역하면 '번역된 텍스트를 삽입하지 못했습니다'라는 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1663">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="946dd-1664">이렇게 변경하면 "값 대신 필드 코드 표시" 옵션이 활성화된 경우 하이퍼링크가 있는 텍스트가 표시되지 않을 수 있는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1664">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="946dd-1665">웹 보기/몰입형 리더에서 힌트를 클릭하면 이미 보기에 있더라도 맨 위로 스크롤됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1665">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="946dd-1666">이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1666">This has been fixed.</span></span>

- <span data-ttu-id="946dd-1667">매크로가 포함된 파일을 새 이름으로 저장하려고 하면 사용자가 입력한 내용에 상관없이 파일이 .docx 확장명과 파일 이름 WRO0004.docx로 저장되어 문서를 사용할 수 없게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1667">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="946dd-1668">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1668">Office Suite</span></span>

- <span data-ttu-id="946dd-1669">사용자에게 Teams 전용으로 이동하는 정책이 지정되어도 Skype for Business Outlook 추가 기능을 사용하여 모임을 예약할 수 있었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1669">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="946dd-1670">이 업데이트 후, 클라이언트가 사용자가 Teams 전용임을 나타내는 정책을 읽고 모임 참가 전용 모드로 들어간 후에는 더 이상 Skype for Business 모임을 예약할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1670">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="946dd-1671">또한 Skype for Business Outlook 추가 기능은 Skype for Business 클라이언트가 미팅 참가 모드인 경우 시작하는 동안 자체적으로 활성화되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1671">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="946dd-1672">이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. </span><span class="sxs-lookup"><span data-stu-id="946dd-1672">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="946dd-1673">이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1673">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-may-11"></a><span data-ttu-id="946dd-1675">버전 2004: 5월 11일</span><span class="sxs-lookup"><span data-stu-id="946dd-1675">Version 2004: May 11</span></span>
<span data-ttu-id="946dd-1676">*버전 2004(빌드 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1676">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1678">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1678">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1679">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1679">Excel</span></span>

- <span data-ttu-id="946dd-1680">**대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1680">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1681">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1681">Outlook</span></span>

- <span data-ttu-id="946dd-1682">**전자 메일의 개선된 링크:** 파일에 대한 링크를 포함할 때 파일 이름이 URL로 바뀝니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1682">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="946dd-1683">모든 받는 사람이 액세스 권한을 갖도록 권한을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1683">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="946dd-1684">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1684">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="946dd-1685">[블로그 게시물](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="946dd-1685">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="946dd-1686">**대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1686">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1687">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1687">PowerPoint</span></span>

- <span data-ttu-id="946dd-1688">**대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1688">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="946dd-1689">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1689">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="946dd-1690">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1690">Word</span></span>

- <span data-ttu-id="946dd-1691">**대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1691">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1694">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1694">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1695">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1695">Outlook</span></span>

- <span data-ttu-id="946dd-1696">토스트 알림을 표시할 때 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1696">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-may-04"></a><span data-ttu-id="946dd-1698">버전 2004: 5월 4일</span><span class="sxs-lookup"><span data-stu-id="946dd-1698">Version 2004: May 04</span></span>
<span data-ttu-id="946dd-1699">*버전 2004(빌드 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1699">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1701">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1701">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1702">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1702">Outlook</span></span>

- <span data-ttu-id="946dd-1703">**즉시 더 나은 결과 얻기:** 이전보다 더 스마트하고, 빠르고, 안정적이 되도록 검색 환경을 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1703">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="946dd-1704">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1704">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="946dd-1705">**IT 관리자에 대한 인시던트 알림:** Microsoft 365 테넌트 전역 관리자 및 Office 앱 관리자는 Windows용 Outlook의 새로운 오른쪽 패널 알림을 통해 사용자에게 영향을 주는 Outlook 및 O365 Exchange 인시던트에 대한 알림을 받습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1705">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="946dd-1706">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1706">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1709">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1709">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="946dd-1710">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1710">Office Suite</span></span>

- <span data-ttu-id="946dd-1711">이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1711">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-april-29"></a><span data-ttu-id="946dd-1713">버전 2004: 4월 29일</span><span class="sxs-lookup"><span data-stu-id="946dd-1713">Version 2004: April 29</span></span>
<span data-ttu-id="946dd-1714">*버전 2004 (빌드 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1714">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1716">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1716">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1717">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1717">Outlook</span></span>

- <span data-ttu-id="946dd-1718">**그룹의 데이터 보호 지원:** 그룹을 만들 때 선택한 민감도 레이블이 그룹 전자 메일, 문서, 팀 사이트에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1718">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1721">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1721">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1722">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1722">Outlook</span></span>

- <span data-ttu-id="946dd-1723">일부 Windows 빌드에서 Outlook이 중단되었던 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1723">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-april-25"></a><span data-ttu-id="946dd-1725">버전 2004: 4월 25일</span><span class="sxs-lookup"><span data-stu-id="946dd-1725">Version 2004: April 25</span></span>
<span data-ttu-id="946dd-1726">*버전 2004(빌드 12730.20206)* </span><span class="sxs-lookup"><span data-stu-id="946dd-1726">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1728">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1728">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1729">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1729">Outlook</span></span>

- <span data-ttu-id="946dd-1730">Windows 업데이트 후 로컬로 저장된 .msg 혹은 .oft 파일을 열 때 Outlook의 작동이 중단되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1730">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="946dd-1731">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1731">Project</span></span>

- <span data-ttu-id="946dd-1732">Project Web App에 연결된 Project를 사용하는 경우 소수 구분 기호가 쉼표이면 TaskDependencies Add 메서드가 종속성에 지연 시간을 추가하려할 때 실패하는 문제를 수정습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1732">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-1733">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1733">Office Suite</span></span>

- <span data-ttu-id="946dd-1734">이 수정은 액세스의 제한과 동시에 파일을 암호로 보호하는 작업을 할 수 없게 하는 오류를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1734">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-april-21"></a><span data-ttu-id="946dd-1736">버전 2004: 4월 21일</span><span class="sxs-lookup"><span data-stu-id="946dd-1736">Version 2004: April 21</span></span>
<span data-ttu-id="946dd-1737">*버전 2004(빌드 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1737">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1739">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1739">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1740">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1740">Outlook</span></span>

- <span data-ttu-id="946dd-1741">폴더 창의 너비가 예기치 않게 변경되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1741">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="946dd-1742">Outlook을 종료하는 동안 사용자 작업이 중지되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1742">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-april-15"></a><span data-ttu-id="946dd-1744">버전 2004: 4월 15일</span><span class="sxs-lookup"><span data-stu-id="946dd-1744">Version 2004: April 15</span></span>
<span data-ttu-id="946dd-1745">*버전 2004(빌드 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1745">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1747">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1747">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1748">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1748">Excel</span></span>

- <span data-ttu-id="946dd-1749">**Facebook 커넥터 지원 종료:** 2020년 4월부터는 Excel에서 Facebook 커넥터를 사용하는 외부 데이터 연결을 더 이상 지원하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1749">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1750">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1750">Outlook</span></span>

- <span data-ttu-id="946dd-1751">**Outlook에서 메일 작성 시 @멘션 제안을 사용하지 않는 새 옵션:** @멘션 선택기가 유용하기보다는 불편하게 느껴지나요?</span><span class="sxs-lookup"><span data-stu-id="946dd-1751">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="946dd-1752">원하는 경우 바로 지금 비활성화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1752">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1753">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1753">PowerPoint</span></span>

- <span data-ttu-id="946dd-1754">**발표하는 동안 변경 내용 동기화:** 프레젠테이션이 슬라이드 쇼 모드에 있더라도 내용이 변경될 때마다 동기화됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1754">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1755">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1755">Word</span></span>

- <span data-ttu-id="946dd-1756">**비공개 복사본에 주석 달기:** 공유 문서의 비공개 복사본을 만들어 나만 볼 수 있는 필기 메모를 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1756">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="946dd-1757">시작하려면 보기 > 비공개 복사본 만들기로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1757">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1760">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1760">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-1761">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-1761">Access</span></span>

- <span data-ttu-id="946dd-1762">작업창에서 표 크기 조정 및 새로 고침과 관련된 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1762">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="946dd-1763">Access의 다른 나라 버전이 사용자 인터페이스에서 영어 문자열을 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1763">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="946dd-1764">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1764">Excel</span></span>

- <span data-ttu-id="946dd-1765">시트의 셀 범위를 선택하면 하나의 셀이 선택되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1765">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="946dd-1766">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효로 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1766">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="946dd-1767">일부 경우에 피벗 테이블을 포함하는 시트를 복사한 후 Excel 작동이 중단되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1767">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="946dd-1768">경우에 따라 Application.Evaluate(VBA)가 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1768">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="946dd-1769">다양한 셀을 프로그래밍 방식으로 편집할 때 사용자에게 발생할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1769">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="946dd-1770">일본어 환경으로 csv 파일을 열 때 발생할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1770">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="946dd-1771">사용자 정의 차트 서식 파일을 기본값으로 삽입하면 열 차트로 저장되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1771">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="946dd-1772">원본 데이터 셀에 캡션이 없는 경우 차트의 데이터 레이블이 빈 채로 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1772">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="946dd-1773">일부 x축 범위를 사용하여 차트 크기를 줄일 때 Excel이 응답을 중지하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1773">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="946dd-1774">R1C1 셀 참조를 사용 설정하고 Excel 시트를 공동 작성/공유 중일 때 사용자의 현재 상태 아이콘에 마우스를 올리면 R1C1 모드에서 셀 참조가 활성으로 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1774">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="946dd-1775">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1775">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1776">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1776">Outlook</span></span>

- <span data-ttu-id="946dd-1777">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1777">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="946dd-1778">이 변경 사항은 초안 전자 메일에 대한 최신 변경 내용이 업데이트되지 않은 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1778">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="946dd-1779">파일을 마우스 오른쪽 단추로 클릭 및 '보내기' 사용이 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1779">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="946dd-1780">대리인이 다른 공유 사서함 컴퓨터의 다른 폴더 계층 구조를 볼 수 있었던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1780">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="946dd-1781">가끔 전자 메일 메시지의 범주가 사라지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1781">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="946dd-1782">컴퓨터의 표준 시간대를 변경할 때 일부 미리 알림이 발송되지 않았던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1782">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="946dd-1783">사용자가 조직 양식의 속성을 보려고 할 때 작동 중단이 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1783">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="946dd-1784">사용자가 주소록에 대한 검색 경로를 사용자 지정한 경우 Outlook의 이름 확인 범위가 GAL(전체 주소 목록)을 포함하지 않고 사용자 지정 경로로 제한되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1784">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="946dd-1785">첨부 파일 도구에서 "클라우드에 저장" 단추가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1785">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="946dd-1786">회신하는 메시지에 대한 소유자 권한이 없는 경우 검사기 창에서 디지털 권한 관리 메시지에 회신할 때 사용자가 서명을 추가할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1786">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="946dd-1787">사용자가 웹 위치에서 이전에 만든 모임에 추가 첨부 파일을 추가할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1787">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="946dd-1788">메일에 첨부 파일을 추가하거나 저장할 때 파일을 끌어다 놓는 방법을 사용하는 경우(메뉴를 사용하는 것과 반대로) 파일의 "최종 수정 날짜"가 업데이트되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1788">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="946dd-1789">사용자가 검색 단추를 클릭하는 대신 상세 검색 창에서 Enter 키를 누르면 검색이 시작되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1789">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="946dd-1790">반환된 검색 결과 집합 내에서 범주별로 결과를 정렬하면 범주 색이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1790">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="946dd-1791">"사용 가능한 경우 사용자 사진 표시" 옵션을 사용하지 않도록 설정한 경우 검색에서 사용자에 대한 정보가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1791">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-1792">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1792">PowerPoint</span></span>

- <span data-ttu-id="946dd-1793">이 변경 내용을 적용하면 이모지가 포함된 PowerPoint 파일을 저장할 때 실패할 수 있는 오류가 수정됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1793">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="946dd-1794">이 변경 내용을 적용하면 PowerPoint 또는 Word에 OLE 개체로 포함된 레거시 Excel 차트를 렌더링할 때 가끔 차트 제목이 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1794">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="946dd-1795">Excel에서 PowerPoint로 텍스트를 복사하면 그 서식이 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1795">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="946dd-1796">이 변경 내용을 적용하면 '단어 단위로' 옵션을 사용한 특수 문자 찾기가 가끔 제대로 작동하지 않았던 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1796">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="946dd-1797">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1797">Project</span></span>

- <span data-ttu-id="946dd-1798">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1798">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="946dd-1799">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1799">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="946dd-1800">사용자가 일정 그룹 내의 작업 리본에 있는 “비활성화” 단추를 클릭하면 'ProjectBeforeTaskChange' VBA(Visual Basic Applications) 이벤트가 실행되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1800">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="946dd-1801">양식 유형 보기 내에서 선행 작업이나 후속 작업 세부 정보를 설정한 경우 ProjectBeforeTaskChange VBA(Visual Basic for Applications) 이벤트가 변경 내용을 캡처하지 않는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1801">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="946dd-1802">예를 들어 종속성을 삭제하고 양식에서 확인을 클릭한 경우 이벤트가 실행되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1802">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="946dd-1803">이 동작이 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1803">This behavior has been fixed.</span></span>

- <span data-ttu-id="946dd-1804">날짜 변경과 같이 변경 후에 ACWP (수행된 작업의 실제 비용)의 최신 값이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1804">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="946dd-1805">MRU(최근 사용한 항목) 메뉴를 사용하여 프로젝트를 열면 프로젝트 파일이 읽기/쓰기 권한으로 열리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1805">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="946dd-1806">이 변경 내용은 시작 날짜와 시간을 사용하여 수동 작업을 만들었지만 기간을 지정하지 않은 경우 타임라인에 잘못된 시간이 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1806">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="946dd-1807">회교식 달력을 사용하여 타임라인을 인쇄하면 인쇄 보기에서 한 달을 건너뛰거나 중복되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1807">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="946dd-1808">이 변경 사항은 팀 플래너에서 GDI 개체를 사용하여 작업하면 GDI 개체가 초과 할당되고 메모리가 부족해지는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1808">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="946dd-1809">'CustomFieldValueListGetItem'이 실행되고 사용자 지정 필드에 대한 조회 테이블이 없는 경우 빈 조회 테이블이 없어도 생성되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1809">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="946dd-1810">양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChange 이벤트가 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1810">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="946dd-1811">실제 작업 시간을 보호하는 설정이 설정된 경우 사용자가 기간별 초기 작업 시간을 입력할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1811">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1812">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1812">Word</span></span>

- <span data-ttu-id="946dd-1813">이 변경 내용을 적용하면 힌트 위에 커서를 놓아도 해당 카드가 강조 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1813">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="946dd-1814">이 변경 내용을 적용하면 보기 메뉴에서 여러 페이지를 선택한 경우 메모 창이 공백으로 표시되는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1814">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="946dd-1815">댓글 달기 기능을 사용할 수 없었던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1815">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="946dd-1816">이 변경 내용을 적용하면 올가미 선택 도구를 사용할 때 그룹 지정된 도형 안의 텍스트가 일시적으로 사라지는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1816">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="946dd-1817">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1817">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="946dd-1818">이 변경 내용을 적용하면 PowerPoint 또는 Word에 OLE 개체로 포함된 레거시 Excel 차트를 렌더링할 때 가끔 차트 제목이 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1818">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="946dd-1819">이 변경 사항은 계정 관리자가 메시지를 발송하지 않아 타사 애플리케이션이 중단되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1819">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="946dd-1820">두 페이지 보기에서 댓글을 작성할 때 댓글 앵커가 가끔 보이지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1820">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="946dd-1821">메모를 입력하거나 편집하고 Ctrl+A를 사용할 때 메모 카드 내에서 텍스트를 선택하는 대신 캔버스에서 텍스트를 선택하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1821">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="946dd-1822">단락의 스타일이 목록에 연결된 스타일의 상위 항목인 경우 해당 목록의 번호 매기기가 분실되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1822">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="946dd-1823">문서에 없는 제목 스타일을 사용하여 목차를 업데이트할 때 발생하는 문제도 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1823">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="946dd-1824">빠른 인쇄를 사용하여 인쇄한 후에 편집하려고 할 때 문서의 단어 맞춤이 스크램블되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1824">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="946dd-1825">두 개의 문서를 하나로 병합할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1825">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="946dd-1826">문서를 보낼 때 Word 문서에 저장된 디지털 서명이 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1826">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="946dd-1827">수식 관련 수정을 표시할 때 파일을 저장하면 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1827">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-april-14"></a><span data-ttu-id="946dd-1829">버전 2003: 4월 14일</span><span class="sxs-lookup"><span data-stu-id="946dd-1829">Version 2003: April 14</span></span>
<span data-ttu-id="946dd-1830">*버전 2003(빌드 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1830">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="946dd-1831">나열된 보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="946dd-1831">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

- <span data-ttu-id="946dd-1833">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-1833">Various bugs and performance fixes.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-april-09"></a><span data-ttu-id="946dd-1835">버전 2003: 4월 9일</span><span class="sxs-lookup"><span data-stu-id="946dd-1835">Version 2003: April 09</span></span>
<span data-ttu-id="946dd-1836">*버전 2003(빌드 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1836">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1838">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1838">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1839">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1839">Excel</span></span>

- <span data-ttu-id="946dd-1840">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="946dd-1840">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="946dd-1841">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="946dd-1841">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1842">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1842">Outlook</span></span>

- <span data-ttu-id="946dd-1843">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="946dd-1843">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="946dd-1844">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="946dd-1844">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1845">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1845">PowerPoint</span></span>

- <span data-ttu-id="946dd-1846">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="946dd-1846">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="946dd-1847">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="946dd-1847">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1848">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1848">Word</span></span>

- <span data-ttu-id="946dd-1849">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="946dd-1849">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="946dd-1850">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="946dd-1850">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)




[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-april-03"></a><span data-ttu-id="946dd-1854">버전 2003: 4월 3일</span><span class="sxs-lookup"><span data-stu-id="946dd-1854">Version 2003: April 03</span></span>
<span data-ttu-id="946dd-1855">*버전 2003(빌드 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1855">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1857">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1857">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1858">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1858">Excel</span></span>

- <span data-ttu-id="946dd-1859">VBA의 Application.Evaluate 사용이 경우에 따라 사용자 정의 함수에서 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1859">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1860">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1860">Outlook</span></span>

- <span data-ttu-id="946dd-1861">마우스에서 "X" 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1861">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="946dd-1862">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1862">Project</span></span>

- <span data-ttu-id="946dd-1863">양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChangeevent가 발생합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1863">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1864">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1864">Word</span></span>

- <span data-ttu-id="946dd-1865">마우스에서 "X" 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1865">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-march-31"></a><span data-ttu-id="946dd-1867">버전 2003: 3월 31일</span><span class="sxs-lookup"><span data-stu-id="946dd-1867">Version 2003: March 31</span></span>
<span data-ttu-id="946dd-1868">*버전 2003 (빌드 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1868">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1870">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1870">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="946dd-1871">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-1871">Access</span></span>

- <span data-ttu-id="946dd-1872">**"테이블 추가" 작업 창:** Access의 새로운 "테이블 추가" 작업 창이 마침내 나왔습니다!</span><span class="sxs-lookup"><span data-stu-id="946dd-1872">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="946dd-1873">이 기능을 사용하면 쿼리 및 관계 보기에 대한 "테이블 표시" 대화 상자를 탐색하지 않고도 쿼리 창에 추가하거나 제거할 테이블을 손쉽게 선택/여러 개 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1873">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="946dd-1874">여기에는 연결된 테이블을 표시하는 새로운 "링크" 탭, 현재 목록을 필터링하는 검색 상자, "끌어다 놓기" 동작 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1874">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1877">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1877">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="946dd-1878">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1878">Project</span></span>

- <span data-ttu-id="946dd-1879"><span style="display:inline !important;">실제 작업 시간을 보호하는 설정이 설정된 경우 사용자가 기간별 초기 작업 시간을 입력할 수 없는 문제가 수정되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="946dd-1879"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-march-25"></a><span data-ttu-id="946dd-1881">버전 2003: 3월 25일</span><span class="sxs-lookup"><span data-stu-id="946dd-1881">Version 2003: March 25</span></span>
<span data-ttu-id="946dd-1882">*버전 2003 (빌드 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1882">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="946dd-1883">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-1883">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="946dd-1884">버전 2003: 3월 23일</span><span class="sxs-lookup"><span data-stu-id="946dd-1884">Version 2003: March 23</span></span>
<span data-ttu-id="946dd-1885">*버전 2003 (빌드 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1885">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="946dd-1886">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-1886">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="946dd-1887">버전 2003: 3월 21일</span><span class="sxs-lookup"><span data-stu-id="946dd-1887">Version 2003: March 21</span></span>
<span data-ttu-id="946dd-1888">*버전 2003 (빌드 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1888">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1890">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1890">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-1891">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1891">Outlook</span></span>

- <span data-ttu-id="946dd-1892">**받은 편지함을 벗어나지 않고 모임 참가:** 온라인 모임에 참가하기 위해 일정으로 전환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1892">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="946dd-1893">일정을 할 일 창에 고정하고 클릭 한 번만으로 모든 모임에 참여하세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-1893">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="946dd-1894">**완전히 새로워진 일정:** 지난 해, Microsoft는 새로워진 메일 환경을 제공했으며, 올해에는 일정이 새롭게 바뀌었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1894">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="946dd-1895">업데이트가 새로 제공되지만 노련한 Outlook 사용자에게는 익숙하므로 바로 시작하여 생산성을 높일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1895">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1896">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1896">PowerPoint</span></span>

- <span data-ttu-id="946dd-1897">**슬라이드 쇼 중에 슬라이드 업데이트:** 프레젠테이션을 진행하는 동안 다른 작성자가 변경한 슬라이드를 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1897">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-march-16"></a><span data-ttu-id="946dd-1899">버전 2003: 3월 16일</span><span class="sxs-lookup"><span data-stu-id="946dd-1899">Version 2003: March 16</span></span>
<span data-ttu-id="946dd-1900">*버전 2003 (빌드 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1900">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-1902">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1902">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1903">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1903">Excel</span></span>

- <span data-ttu-id="946dd-1904">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-1904">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1905">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1905">Outlook</span></span>

- <span data-ttu-id="946dd-1906">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-1906">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1907">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1907">PowerPoint</span></span>

- <span data-ttu-id="946dd-1908">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-1908">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1909">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1909">Word</span></span>

- <span data-ttu-id="946dd-1910">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-1910">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="946dd-1911">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1911">Office Suite</span></span>

- <span data-ttu-id="946dd-1912">**탭 창:** 이제 앱의 오른쪽에 있는 탭 UI를 사용하여 여러 창 간에 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1912">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="946dd-1913">UI는 2개 이상의 창이 열려있는 경우에만 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1913">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1916">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1916">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1917">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1917">Excel</span></span>

- <span data-ttu-id="946dd-1918">원본 주소록이 닫힌 경우 외부 링크가 채우기에 업데이트되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1918">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-1919">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1919">Outlook</span></span>

- <span data-ttu-id="946dd-1920">사용자가 종료 후 작업 관리자에 남아 있는 Outlook 프로세스를 보게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1920">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-march-10"></a><span data-ttu-id="946dd-1922">버전 2003: 3월 10일</span><span class="sxs-lookup"><span data-stu-id="946dd-1922">Version 2003: March 10</span></span>
<span data-ttu-id="946dd-1923">*버전 2003(빌드 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1923">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="946dd-1924">나열된 보안 업데이트는 [여기](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="946dd-1924">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)
### <a name="feature-updates"></a><span data-ttu-id="946dd-1926">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-1926">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1927">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1927">Excel</span></span>
- <span data-ttu-id="946dd-1928">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1928">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="946dd-1929">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1929">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="946dd-1930">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1930">PowerPoint</span></span>
- <span data-ttu-id="946dd-1931">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1931">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="946dd-1932">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1932">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="946dd-1933">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1933">Word</span></span>
- <span data-ttu-id="946dd-1934">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1934">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="946dd-1935">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="946dd-1935">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1936">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1936">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-1937">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-1937">Excel</span></span>

- <span data-ttu-id="946dd-1938">File \ Options 대화 상자의 '확인' 단추가 회색으로 표시되고 기능에는 영향을 미치지 않는 외관상의 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1938">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="946dd-1939">피벗 테이블 측정의 이름을 바꿀 때 사용자가 겪을 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1939">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="946dd-1940">인쇄 미리 보기에서 슬라이서의 텍스트 크기가 제대로 조정되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1940">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="946dd-1941">VBA 매크로를 사용하여 범위의 내용을 지우면 사용자가 경험할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1941">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="946dd-1942">사용자가 리본과 상호 작용하는 매크로를 실행할 때 UI가 깜박이는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1942">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="946dd-1943">파일의 첫 단어가 TABLE 인 경우 CSV 파일이 잘못 로드되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1943">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="946dd-1944">확대/축소 수준이 다른 두 통합 문서 간에 전환할 때 사용자가 충돌을 경험할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1944">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="946dd-1945">CUBEVALUE 함수가 때때로 잘못된 결과를 반환하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1945">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="946dd-1946">이번 변경으로 추가 기능에서 noSelect 잠금을 사용하는 도형이 포함된 문서/통합 문서의 호스트 항목을 요청하는 경우 발생하는 앱(Excel, Word)의 잠재적인 충돌 및 개체 모델의 런타임 오류가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1946">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="946dd-1947">설정을 동기화하는 경우 Outlook 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1947">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="946dd-1948">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-1948">Outlook</span></span>

- <span data-ttu-id="946dd-1949">Outlook Web Access로 규칙을 만들 때 Exchange 서버에 유지되지 않아 충돌이 발생하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1949">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="946dd-1950">설정을 동기화하는 경우 Outlook 사용자에게 충돌이 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1950">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="946dd-1951">어두운 모드의 Outlook에서 '보낸 사람:' 입력란에 드롭다운 목록이 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1951">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="946dd-1952">로깅이 꺼져 있어도 일부 시나리오에서 Outlook이 예기치 않게 로깅 출력을 생성하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1952">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="946dd-1953">Outlook이 밤새 실행 중인 상태에서 사용자가 공용 폴더 메시지를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1953">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="946dd-1954">Gmail 계정 추가의 인증 작업 과정에서 권한 페이지의 '허용' 및 '거부' 버튼이 비활성화되는 경합 상태를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1954">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="946dd-1955">사용자가 &quot;약속 있음/없음 옵션&quot; 일정 권한 대화 상자에 액세스하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1955">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="946dd-1956">다른 시간대에서 보낸 되풀이 모임 인스턴스를 열 때 &quot;죄송합니다. 이 항목을 여는 데 문제가 있습니다&quot;라는 경고가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1956">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="946dd-1957">해당 메시지에서 첨부 파일을 끌어서 놓은 후 사용자가 .msg 파일을 다시 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1957">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="946dd-1958">첨부 파일 이름에 괄호가 포함된 경우 Outlook에서 OneDrive로 파일 첨부 파일을 업로드한 후 파일 이름이 변경될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1958">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="946dd-1959">사용자가 다른 응용 프로그램에서 파일을 열 때 파일 탐색기를 통해 파일을 전자 메일 메시지에 첨부할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1959">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="946dd-1960">설정을 동기화하는 경우 Outlook 사용자에게 충돌이 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1960">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="946dd-1961">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-1961">PowerPoint</span></span>

- <span data-ttu-id="946dd-1962">축소판 그림 위로 마우스를 가져가면 권장 축소판 그림이 깜박이는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1962">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="946dd-1963">경우에 따라 PowerPoint가 중단될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1963">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="946dd-1964">File \ Options 대화 상자의 '확인' 단추가 회색으로 표시되고 기능에는 영향을 미치지 않는 외관상의 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1964">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="946dd-1965">Excel 차트가 포함된 PowerPoint 또는 Word에서 문서를 저장하지 못하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1965">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="946dd-1966">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1966">Project</span></span>

- <span data-ttu-id="946dd-1967">작업이 완료됨으로 표시된 후 작업 완료율이 100%보다 낮은 값으로 잘못 변경되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1967">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="946dd-1968">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1968">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="946dd-1969">요약 작업 날짜가 가끔 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1969">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="946dd-1970">Visio</span><span class="sxs-lookup"><span data-stu-id="946dd-1970">Visio</span></span>

- <span data-ttu-id="946dd-1971">Visio 데스크톱에서 연 파일의 경우, 셰이프 정보 창에서 셰이프 데이터 구역에 일관성이 없는 세부 정보가 표시되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1971">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="946dd-1972">이제 이 문제가 해결었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1972">It has now been fixed.</span></span>

- <span data-ttu-id="946dd-1973">몇 가지 보안 검사로 인해 2016 이전 버전에서 가져온 비트맵이 렌더링되지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1973">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="946dd-1974">Visio 구독에서 이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1974">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-1975">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-1975">Word</span></span>

- <span data-ttu-id="946dd-1976">마우스 포인터가 주석 카드 위로 마우스를 가져갈 때 주석 카드가 항상 강조 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1976">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="946dd-1977">메모 카드를 탭할 때 메모 편집 상자에 포커스가 표시되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1977">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="946dd-1978">File \ Options 대화 상자의 '확인' 단추가 회색으로 표시되고 기능에는 영향을 미치지 않는 외관상의 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1978">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="946dd-1979">문서 공동 작성 세션 중에 주석 카드에 직접 이미지를 추가하면 태그가 추가될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1979">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="946dd-1980">이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1980">This issue has been fixed.</span></span>

- <span data-ttu-id="946dd-1981">수식에 텍스트 콘텐츠 컨트롤과 같은 컨트롤을 삽입한 다음 파일을 저장하고 열면 읽을 수 없는 콘텐츠 오류가 발생합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1981">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="946dd-1982">이전에 암호로 보호된 파일을 클라우드 저장소에 저장하지 못하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1982">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="946dd-1983">편집에 대해 보호된 문서의 비교 기능 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1983">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="946dd-1984">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-1984">Office Suite</span></span>

- <span data-ttu-id="946dd-1985">Word/Excel/PowerPoint 문서와 함께 Multichoice/ Lookup/Managed-metadata 속성을 사용하고 SharePoint 문서 라이브러리에 저장할 때, 이러한 속성은 이전에 255 자로 제한되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1985">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="946dd-1986">이러한 속성이 255자를 초과하면 해당 문서를 저장할 수 없었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1986">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="946dd-1987">이 변경으로 이 제한이 2048자로 늘었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1987">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="946dd-1988">Word/Excel/PowerPoint에서 UPN(사용자 계정 이름)이 더 이상 대소문자를 구분하지 않아 SharePoint에서 파일 작업시 오류가 줄어듭니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1988">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="946dd-1989">동일한 SharePoint 라이브러리의 Word/Excel/PowerPoint에서 여러 문서를 열 때 첫 번째로 열린 문서만 정책 준수에 대한 검사가 이뤄지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1989">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-march-05"></a><span data-ttu-id="946dd-1991">버전 2002: 3월 5일</span><span class="sxs-lookup"><span data-stu-id="946dd-1991">Version 2002: March 05</span></span>
<span data-ttu-id="946dd-1992">*버전 2002 (빌드 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1992">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="946dd-1993">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-1993">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="946dd-1994">버전 2002: 3월 4일</span><span class="sxs-lookup"><span data-stu-id="946dd-1994">Version 2002: March 04</span></span>
<span data-ttu-id="946dd-1995">*버전 2002 (빌드 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="946dd-1995">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-1997">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-1997">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="946dd-1998">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-1998">Project</span></span>
- <span data-ttu-id="946dd-1999">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-1999">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-2000">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-2000">Office Suite</span></span>
- <span data-ttu-id="946dd-2001">동일한 SharePoint 라이브러리의 Word/Excel/PowerPoint에서 여러 문서를 열 때 첫 번째로 열린 문서만 정책 준수에 대한 검사가 이뤄지는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2001">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-march-01"></a><span data-ttu-id="946dd-2003">버전 2002: 3월 1일</span><span class="sxs-lookup"><span data-stu-id="946dd-2003">Version 2002: March 01</span></span>
<span data-ttu-id="946dd-2004">*버전 2002 (빌드 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="946dd-2004">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="946dd-2005">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-2005">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-2006">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-2006">Outlook</span></span>

- <span data-ttu-id="946dd-2007">타사 응용 프로그램에서 전자 메일을 보낼 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2007">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-february-24"></a><span data-ttu-id="946dd-2009">버전 2002: 2월 24일</span><span class="sxs-lookup"><span data-stu-id="946dd-2009">Version 2002: February 24</span></span>
<span data-ttu-id="946dd-2010">*버전 2002 (빌드 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="946dd-2010">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="946dd-2011">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-2011">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="946dd-2012">버전 2002: 2월 22일</span><span class="sxs-lookup"><span data-stu-id="946dd-2012">Version 2002: February 22</span></span>
<span data-ttu-id="946dd-2013">*버전 2002 (빌드 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="946dd-2013">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="946dd-2014">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="946dd-2014">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="946dd-2015">버전 2002: 2월 21일</span><span class="sxs-lookup"><span data-stu-id="946dd-2015">Version 2002: February 21</span></span>
<span data-ttu-id="946dd-2016">*버전 2002(빌드 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="946dd-2016">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-2018">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-2018">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="946dd-2019">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-2019">Access</span></span>

- <span data-ttu-id="946dd-2020">**Query Designer, SQL 보기 및 관계 창에서 생산성을 향상시킬 수 있습니다.** 테이블을 마우스 오른쪽 단추로 클릭하여 열고 디자인하고 크기를 조정하고 숨겨보세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-2020">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="946dd-2021">SQL 보기에서 텍스트를 검색하고 바꾸세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-2021">Search and replace text in SQL View.</span></span> <span data-ttu-id="946dd-2022">관계 창에서 테이블을 여러 개 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="946dd-2022">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-2023">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-2023">Outlook</span></span>

- <span data-ttu-id="946dd-2024">**종속적인 Wi-Fi 네트워크에 대한 새로운 경험:** 로그인하기 위해 웹 페이지가 필요한 Wi-Fi 네트워크에 가입한 적이 있습니까?</span><span class="sxs-lookup"><span data-stu-id="946dd-2024">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="946dd-2025">이제 Outlook이 이를 감지하여 연결하는 데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2025">Outlook now detects this and helps you get connected.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-2028">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-2028">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="946dd-2029">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-2029">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="946dd-2030">CUBEVALUE 함수가 때때로 잘못된 결과를 반환하는 문제가 해결되었습니다.&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="946dd-2030">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="946dd-2031">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-2031">Outlook</span></span>

- <span data-ttu-id="946dd-2032">모임 위치 필드의 쉼표가 세미콜론으로 바뀌는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2032">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="946dd-2033">여러 창에서 동일한 항목을 볼 때 충돌이 발생할 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2033">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="946dd-2034">동기화 슬라이더가 더 작은 설정으로 설정되어 있어도 Outlook이 예기치 않게 모든 메일을 동기화시키는 문제를 해결했습니다. &nbsp;</span><span class="sxs-lookup"><span data-stu-id="946dd-2034">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="946dd-2035">검은색 테마를 사용한 사용자에게 &quot;보낸 사람&quot; 드롭다운에 흰색 배경에 흰색 텍스트가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2035">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="946dd-2036"><span style="display:inline !important;">이 변경으로 메시지 헤더에서 여러 줄 제목을 볼 수 있습니다.</span></span><span class="sxs-lookup"><span data-stu-id="946dd-2036"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-february-18"></a><span data-ttu-id="946dd-2038">버전 2002: 2월 18일</span><span class="sxs-lookup"><span data-stu-id="946dd-2038">Version 2002: February 18</span></span>
<span data-ttu-id="946dd-2039">*버전 2002(빌드 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="946dd-2039">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="946dd-2040">버전 2002: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="946dd-2040">Version 2002: February 11</span></span>
<span data-ttu-id="946dd-2041">*버전 2002 (빌드 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="946dd-2041">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="946dd-2042">[여기](./microsoft365-apps-security-updates.md) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-2042">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="946dd-2044">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="946dd-2044">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="946dd-2045">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-2045">Outlook</span></span>

- <span data-ttu-id="946dd-2046">**사용자가 소유한 그룹으로 전자 메일 끌기:** 메시지와 대화를 받은 편지함에서 끌어서 이동하고 복사합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2046">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="946dd-2047">끌어 놓은 메시지는 모든 그룹 구성원과 공유됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2047">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="946dd-2048">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-2048">Word</span></span>

- <span data-ttu-id="946dd-2049">**다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다.** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2049">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="946dd-2050">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-2050">Office Suite</span></span>

- <span data-ttu-id="946dd-2051">**더 명확한 상태 표시줄 아이콘:** 상태 표시줄 아이콘을 쉽게 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2051">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="946dd-2054">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="946dd-2054">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="946dd-2055">Access</span><span class="sxs-lookup"><span data-stu-id="946dd-2055">Access</span></span>

- <span data-ttu-id="946dd-2056">데이터베이스 내에서 더 이상 액세스 템플릿으로 인해 첨부 열이 실패하지 않아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2056">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="946dd-2057">템플릿을 인스턴스화 한 후에는 데이터베이스에 첨부 파일 필드를 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2057">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="946dd-2058">이 업데이트는 ADODB 사용시 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2058">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="946dd-2059">VB 코드의 레코더 개체에서 오류가 잘못 보고될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2059">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="946dd-2060">이 업데이트는 Microsoft Access에서 연결된 SQL Server 테이블의 ID 열이 식별되지 않아서 행이 올바르지 않게 삭제된 것으로 보고되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2060">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="946dd-2061">Excel</span><span class="sxs-lookup"><span data-stu-id="946dd-2061">Excel</span></span>

- <span data-ttu-id="946dd-2062">상황에 맞는 메뉴에서 주석 명령이 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2062">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="946dd-2063">spilling 배열이 있는 셀이 있는 열로 텍스트를 변환할 때 일부 사용자에게 충돌이 발생하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2063">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="946dd-2064">동적 배열에서 Text To Columns를 사용할 때 Excel이 중단되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2064">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="946dd-2065">Outlook</span><span class="sxs-lookup"><span data-stu-id="946dd-2065">Outlook</span></span>

- <span data-ttu-id="946dd-2066">월 보기를 사용하여 일정을 스크롤할 때 이전 일정 이벤트가 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2066">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="946dd-2067">왼쪽 탐색 창의 '즐겨찾는 사람’에 저장된 폴더가 간헐적으로 사라질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2067">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="946dd-2068">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2068">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="946dd-2069">일부 시나리오에서 플래그가 지정된 항목 강조 표시를 사용하지 않도록 설정하는 옵션이 무시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2069">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="946dd-2070">계정 설정을 취소할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2070">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="946dd-2071">보존 정책에 따라 만료되는 전자 메일에 두 개의 레이블이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2071">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="946dd-2072">하나는 메일이 하루 내에 만료되고 다른 하나는 2일 후에 만료된다는 것을 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2072">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="946dd-2073">Citrix 환경에서 30개 이상의 캘린더를 볼 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2073">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="946dd-2074">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="946dd-2074">PowerPoint</span></span>

- <span data-ttu-id="946dd-2075">PowerPoint 잉크 애니메이션에서 잉크가 완전히 렌더링되지 않거나 건너뛰기될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2075">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="946dd-2076">이벤트 처리기가 실행 중인 경우, 파일을 닫은 후 PowerPoint에서 프레젠테이션 모음의 해당 파일을 즉시 제거하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2076">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="946dd-2077">따라서 개체 모델에서 보고한 열려 있는 프레젠테이션 수가 올바르지 않아 PowerPoint가 종료되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2077">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="946dd-2078">형광펜 관련 문제를 해결했습니다. 어두운 형광펜 색상의 텍스트는 흑백 모드에서 검은 색으로 인쇄됩니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2078">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="946dd-2079">Project</span><span class="sxs-lookup"><span data-stu-id="946dd-2079">Project</span></span>

- <span data-ttu-id="946dd-2080">고정된 기간 유형의 100% 작업이 100% 완료 미만으로 잘못 계산할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2080">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="946dd-2081">Word</span><span class="sxs-lookup"><span data-stu-id="946dd-2081">Word</span></span>

- <span data-ttu-id="946dd-2082">목차를 업데이트하고 스크롤하면 때때로 문서 위에 회색 영역이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2082">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="946dd-2083">메모가 작성되었지만 게시되지 않고 사용자가 파일을 저장하려고 하는 경우 '찾아보기'를 사용하여 파일을 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2083">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="946dd-2084">메모 카드 간에 앞뒤로 이동할 때 때때로 선택 강조 표시로 처음 선택한 메모가 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2084">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="946dd-2085">메모를 편집하고 텍스트를 기울임꼴로 표시하고 게시하면 기울임꼴 서식이 손실되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2085">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="946dd-2086">반전 페이지 색이 있는 읽기 모드에서 메모 힌트가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2086">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="946dd-2087">문서를 공동 작성하는 경우 루트 메모의 초안 버전이 유지되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2087">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="946dd-2088">SlideTrack을 활성화하고 메모 창을 닫으면 Ctrl+Alt+M을 눌러 메모 창을 열지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2088">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="946dd-2089">테이블에 @mention을 추가할 때 '이 문서의 테이블이 손상되었습니다'라는 오류 메시지가 생성될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2089">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="946dd-2090">메모 상황에 맞는 메뉴에서 메모 명령(메모 편집, 메모에 대한 회신, 메모 삭제, 메모 확인)이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2090">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="946dd-2091">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="946dd-2091">Office Suite</span></span>

- <span data-ttu-id="946dd-2092">노르웨이 니노르스크(nn-no) 교정 도구 패키지가 잘못 설치될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2092">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="946dd-2093">이 변경 사항은 인텔 통합 GPU를 활용하는 그래픽 어댑터에 보고된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="946dd-2093">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)
