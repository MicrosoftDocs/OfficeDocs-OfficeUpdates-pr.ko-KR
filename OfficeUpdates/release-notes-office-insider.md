---
title: Office 참가자에 대한 릴리스 정보
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 초기 참가자 대상 그룹에게 주요 새 기능, 수정 사항 또는 알려진 문제의 최신 목록을 제공합니다.
ms.openlocfilehash: 38f26f551be55a7817a993108f598c6a6a9ecdb5
ms.sourcegitcommit: fdc89a96b2ab35af2f08654ef28117dec7657443
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/24/2020
ms.locfileid: "43804901"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="439b4-103">Office 참가자에 대한 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="439b4-104">이 문서에는 Windows 데스크톱용 Word, Excel, PowerPoint, Outlook, Access 및 Project 의 참가자 빌드에 대한 릴리스 정보가 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="439b4-105">매주 Microsoft는 흥미로운 새 기능, 중요한 수정 사항, 알리고자 하는 중요한 문제를 강조합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="439b4-106">Microsoft는 일정 기간 동안 자주 참가자들에게 기능을 배포하며 때로는 수정 사항도 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="439b4-107">이로서 더욱 광범위한 사용자들에게 기능을 릴리스하기 전에 원활하게 작동하는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="439b4-108">따라서 아래에 설명된 기능이 보이지 않더라도 곧 제공되게 되므로 걱정할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="439b4-109">릴리스 정보는 매주 포스팅되며 여러 빌드의 편집일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="439b4-110">릴리스 정보 게시 날짜는 실제 빌드 릴리스 날짜와 일치하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-110">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (제거하지 마세요)

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2005-april-24"></a><span data-ttu-id="439b4-113">버전 2005: 4월 24일</span><span class="sxs-lookup"><span data-stu-id="439b4-113">Version 2005: April 24</span></span>
<span data-ttu-id="439b4-114">*버전 2005(빌드 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="439b4-114">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-118">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-119">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-119">Excel</span></span>
- <span data-ttu-id="439b4-120">이 변경 사항은 LINEST 함수가 올바른 값을 반환하는 경우에도 차트 추세선 R 제곱값(강제적인 y 절편)이 올바르지 않은 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-120">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="439b4-121">이 변경 사항은 사용자 지정된 차트 추세선 서식이 항상 저장되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-121">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-122">Outlook</span></span>
- <span data-ttu-id="439b4-123">Office 리본에서 그룹 일정의 분류 버튼이 비활성화되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-123">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="439b4-124">구현되거나 작동하지 않는 그룹 폴더가 있는 엔터프라이즈 고객이 있는 경우 Outlook에 "응답하지 않음" 메시지가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-124">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-125">PowerPoint</span></span>
- <span data-ttu-id="439b4-126">별표(\*) 기호 위로 마우스를 가져가면 문서를 업데이트할 마지막 사람의 사용자 이름과 날짜가 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-126">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-127">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-127">Word</span></span>
- <span data-ttu-id="439b4-128">"책갈피 표시" 옵션을 사용하도록 설정하면 책갈피가 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-128">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="439b4-129">이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-129">This has been fixed.</span></span>
- <span data-ttu-id="439b4-130">이 변경 사항은 "값 대신 필드 코드 표시" 옵션을 사용하도록 설정한 경우 하이퍼링크가 포함된 텍스트를 표시할 수 없는 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-130">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2005-april-17"></a><span data-ttu-id="439b4-132">버전 2005: 4월 17일</span><span class="sxs-lookup"><span data-stu-id="439b4-132">Version 2005: April 17</span></span>
<span data-ttu-id="439b4-133">*버전 2005(빌드 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="439b4-133">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-135">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-136">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-136">Excel</span></span>
- <span data-ttu-id="439b4-137">차트에 사용되는 사용자 지정 오차 막대 대화 상자에서 셀 참조 편집 컨트롤의 크기를 늘렸습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-137">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="439b4-138">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-138">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="439b4-139">인쇄할 때 양식 컨트롤의 확인란 크기 조정에 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-139">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="439b4-140">경우에 따라 Application.Evaluate(VBA)가 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-140">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="439b4-141">이와 같이 변경하면 CF(조건부 서식) 정보가 제대로 파일에 저장되지 않는 문제를 해결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-141">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="439b4-142">OneNote</span><span class="sxs-lookup"><span data-stu-id="439b4-142">OneNote</span></span>
- <span data-ttu-id="439b4-143">줄 바꿈이 세로 탭으로 저장되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-143">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-144">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-144">Outlook</span></span>
- <span data-ttu-id="439b4-145">사용자가 개인 연락처 그룹을 모임 참석자로 추가할 수 없게 하는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-145">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="439b4-146">2개월 넘게 참석하지 않은 모임의 제목이 일정 정리에 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-146">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="439b4-147">대규모 HTML 메시지를 전달할 때 사용자에게 잘린 메시지 본문이 표시되던 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-147">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="439b4-148">그룹 정책을 통해 S/MIME 기본 서명 구성을 적용하는 기능이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-148">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="439b4-149">사용자의 기본 사서함 이외의 사서함을 위해 만든 삭제 규칙이 유효하지 않게 되는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-149">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="439b4-150">암호화된 메시지를 전달할 때 첨부 파일이 삭제되는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-150">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="439b4-151">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-151">Project</span></span>
- <span data-ttu-id="439b4-152">양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChange 이벤트가 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-152">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="439b4-153">SharePoint 작업 목록에 연결된 프로젝트에서 보드 상태 필드를 변경하면 Project가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-153">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="439b4-154">이전 버전의 Project에서 만든 프로젝트를 저장하면 Project가 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-154">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-april-10"></a><span data-ttu-id="439b4-156">버전 2004: 4월 10일</span><span class="sxs-lookup"><span data-stu-id="439b4-156">Version 2004: April 10</span></span>
<span data-ttu-id="439b4-157">*버전 2004(빌드 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="439b4-157">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-159">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-159">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="439b4-160">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-160">Access</span></span>

- <span data-ttu-id="439b4-161">**테이블 표시 대화 상자를 사용하지 않고 작업 창으로 바로 이동한 후 관계 및 쿼리에 테이블을 간단하게 추가:** 네 개의 탭을 클릭하고, 여러 이름을 한번에 선택하고, 텍스트를 검색하고, 작업 중에 열어 놓은 작업 창에서 끌어와 테이블 및 쿼리를 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-161">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-162">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-162">Excel</span></span>

- <span data-ttu-id="439b4-163">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="439b4-163">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="439b4-164">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="439b4-164">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-165">Outlook</span></span>

- <span data-ttu-id="439b4-166">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="439b4-166">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="439b4-167">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="439b4-167">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="439b4-168">**전자 메일로 사진을 보낼 때 선명도를 높게 유지:.** 새 Outlook 설정을 사용하여 사진을 전자 메일 콘텐츠에 첨부해서 보낼 때 압축을 제한할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-168">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-169">PowerPoint</span></span>

- <span data-ttu-id="439b4-170">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="439b4-170">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="439b4-171">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="439b4-171">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="439b4-172">**발표하는 동안 변경 내용 동기화:** 프레젠테이션이 슬라이드 쇼 모드에 있더라도 내용이 변경될 때마다 동기화됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-172">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-173">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-173">Word</span></span>

- <span data-ttu-id="439b4-174">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="439b4-174">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="439b4-175">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="439b4-175">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="439b4-176">**비공개 복사본에 주석 달기:** 공유 문서의 비공개 복사본을 만들어 나만 볼 수 있는 필기 메모를 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-176">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="439b4-177">시작하려면 보기 > 비공개 복사본 만들기로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-177">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-180">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-180">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="439b4-181">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-181">Access</span></span>

- <span data-ttu-id="439b4-182">작업창에서 표 크기 조정 및 새로 고침과 관련된 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-182">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-183">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-183">Excel</span></span>

- <span data-ttu-id="439b4-184">시트의 셀 범위를 선택하면 하나의 셀이 선택되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-184">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="439b4-185">일부 x축 범위를 사용하여 차트 크기를 줄일 때 Excel이 응답을 중지하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-185">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="439b4-186">사용자 정의 차트 서식 파일을 기본값으로 삽입하면 열 차트로 저장되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-186">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="439b4-187">원본 데이터 셀에 캡션이 없는 경우 차트의 데이터 레이블이 빈 채로 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-187">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="439b4-188">R1C1 셀 참조를 사용 설정하고 Excel 시트를 공동 작성/공유 중일 때 사용자의 현재 상태 아이콘에 마우스를 올리면 R1C1 모드에서 셀 참조가 활성으로 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-188">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-189">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-189">Outlook</span></span>

- <span data-ttu-id="439b4-190">가끔 전자 메일 메시지의 범주가 사라지는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-190">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="439b4-191">대리인이 다른 공유 사서함 컴퓨터의 다른 폴더 계층 구조를 볼 수 있었던 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-191">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="439b4-192">사용자가 조직 양식의 속성을 보려고 할 때 작동 중단이 발생하는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-192">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="439b4-193">컴퓨터의 표준 시간대를 변경할 때 일부 미리 알림이 발송되지 않았던 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-193">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-194">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-194">PowerPoint</span></span>

- <span data-ttu-id="439b4-195">이 변경 내용을 적용하면 PowerPoint 또는 Word에 OLE 개체로 포함된 레거시 Excel 차트를 렌더링할 때 가끔 차트 제목이 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-195">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="439b4-196">Excel에서 PowerPoint로 텍스트를 복사하면 그 서식이 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-196">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="439b4-197">이 변경 내용을 적용하면 '단어 단위로' 옵션을 사용한 특수 문자 찾기가 가끔 제대로 작동하지 않았던 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-197">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="439b4-198">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-198">Project</span></span>

- <span data-ttu-id="439b4-199">실제 작업 시간을 보호하는 설정이 설정된 경우 사용자가 기간별 초기 작업 시간을 입력할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-199">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-200">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-200">Word</span></span>

- <span data-ttu-id="439b4-201">이 변경 내용을 적용하면 힌트 위에 커서를 놓아도 해당 카드가 강조 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-201">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="439b4-202">이 변경 내용을 적용하면 올가미 선택 도구를 사용할 때 그룹 지정된 도형 안의 텍스트가 일시적으로 사라지는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-202">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="439b4-203">이 변경 내용을 적용하면 PowerPoint 또는 Word에 OLE 개체로 포함된 레거시 Excel 차트를 렌더링할 때 가끔 차트 제목이 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-203">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="439b4-204">두 페이지 보기에서 댓글을 작성할 때 댓글 앵커가 가끔 보이지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-204">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="439b4-205">단락의 스타일이 목록에 연결된 스타일의 상위 항목인 경우 해당 목록의 번호 매기기가 분실되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-205">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-march-27"></a><span data-ttu-id="439b4-207">버전 2004: 3월 27일</span><span class="sxs-lookup"><span data-stu-id="439b4-207">Version 2004: March 27</span></span>
<span data-ttu-id="439b4-208">*버전 2004(빌드 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="439b4-208">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-210">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-210">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-211">Outlook</span></span>

- <span data-ttu-id="439b4-212">**메일 작성 시 @멘션 제안을 사용하지 않는 새 옵션:** @멘션 선택기가 유용하기보다는 불편하게 느껴지나요?</span><span class="sxs-lookup"><span data-stu-id="439b4-212">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="439b4-213">원하는 경우 바로 지금 비활성화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-213">Now you can turn it off if you prefer.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-216">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-216">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-217">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-217">Outlook</span></span>
- <span data-ttu-id="439b4-218">첨부 파일 도구에서 "클라우드에 저장" 단추가 누락되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-218">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="439b4-219">회신하는 메시지에 대한 소유자 권한이 없는 경우 검사기 창에서 디지털 권한 관리 메시지에 회신할 때 사용자가 서명을 추가할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-219">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="439b4-220">사용자가 웹 위치에서 이전에 만든 모임에 추가 첨부 파일을 추가할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-220">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-221">PowerPoint</span></span>
- <span data-ttu-id="439b4-222">이 변경 내용을 적용하면 이모지가 포함된 PowerPoint 파일을 저장할 때 실패할 수 있는 오류가 수정됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-222">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="439b4-223">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-223">Project</span></span>
- <span data-ttu-id="439b4-224">'CustomFieldValueListGetItem'이 실행되고 사용자 지정 필드에 대한 조회 테이블이 없는 경우 빈 조회 테이블이 없어도 생성되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-224">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-225">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-225">Word</span></span>
- <span data-ttu-id="439b4-226">이 변경 내용은 보기 메뉴에서 여러 페이지를 선택한 경우 메모 창이 공백으로 표시될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-226">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-march-20"></a><span data-ttu-id="439b4-228">버전 2004: 2020년 3월</span><span class="sxs-lookup"><span data-stu-id="439b4-228">Version 2004: March 20</span></span>
<span data-ttu-id="439b4-229">*버전 2004(빌드 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-229">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-231">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-231">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-232">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-232">Outlook</span></span>

- <span data-ttu-id="439b4-233">**완전히 새로워진 일정:** 지난 해, 당사는 새로워진 메일 환경을 제공했으며, 올해에는 일정이 새롭게 바뀌었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-233">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="439b4-234">업데이트가 새로 제공되지만 노련한 Outlook 사용자에게는 익숙하므로 바로 시작하여 생산성을 높일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-234">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="439b4-235">**그룹의 데이터 보호 지원:** 그룹을 만들 때 선택한 민감도 레이블이 그룹 전자 메일, 문서, 팀 사이트에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-235">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-236">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-236">PowerPoint</span></span>

- <span data-ttu-id="439b4-237">**슬라이드 쇼 중에 슬라이드 업데이트:** 프레젠테이션을 진행하는 동안 다른 작성자가 변경한 슬라이드를 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-237">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-240">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-240">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-241">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-241">Excel</span></span>

- <span data-ttu-id="439b4-242">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-242">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-243">Outlook</span></span>

- <span data-ttu-id="439b4-244">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-244">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="439b4-245">이 변경 사항은 초안 전자 메일에 대한 최신 변경 내용이 업데이트되지 않은 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-245">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="439b4-246">파일을 마우스 오른쪽 단추로 클릭 및 '보내기' 사용이 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-246">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="439b4-247">사용자가 주소록에 대한 검색 경로를 사용자 지정한 경우 Outlook의 이름 확인 범위가 GAL(전체 주소 목록)을 포함하지 않고 사용자 지정 경로로 제한되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-247">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="439b4-248">반환된 검색 결과 집합 내에서 범주별로 결과를 정렬하면 범주 색이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-248">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="439b4-249">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-249">Project</span></span>

- <span data-ttu-id="439b4-250">사용자가 일정 그룹 내의 작업 리본에서 찾은 "비활성화" 단추를 클릭하면 'ProjectBeforeTaskChange' VBA(Visual Basic for Applications) 이벤트가 실행되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-250">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="439b4-251">양식 유형 보기 내에서 선행 작업이나 후속 작업 세부 정보를 설정한 경우 ProjectBeforeTaskChange VBA(Visual Basic for Applications) 이벤트가 변경 내용을 캡처하지 않는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-251">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="439b4-252">예를 들어 종속성을 삭제하고 양식에서 확인을 클릭한 경우 이벤트가 실행되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-252">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="439b4-253">이 동작이 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-253">This behavior has been fixed.</span></span>

- <span data-ttu-id="439b4-254">날짜 변경과 같이 변경 후에 ACWP (수행된 작업의 실제 비용)의 최신 값이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-254">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="439b4-255">MRU(최근 사용한 항목) 메뉴를 사용하여 프로젝트를 열면 프로젝트 파일이 읽기/쓰기 권한으로 열리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-255">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="439b4-256">이 변경 내용은 시작 날짜와 시간을 사용하여 수동 작업을 만들었지만 기간을 지정하지 않은 경우 타임라인에 잘못된 시간이 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-256">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="439b4-257">회교식 달력을 사용하여 타임라인을 인쇄하면 인쇄 보기에서 한 달을 건너뛰거나 중복되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-257">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="439b4-258">이 변경 사항은 팀 플래너에서 GDI 개체를 사용하여 작업하면 GDI 개체가 초과 할당되고 메모리가 부족해지는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-258">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-259">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-259">Word</span></span>

- <span data-ttu-id="439b4-260">댓글에 대한 게시 기능이 사용하지 않도록 설정되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-260">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="439b4-261">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-261">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="439b4-262">또한 계정 관리자가 메시지를 발송하지 않아 타사 애플리케이션이 중단되는 문제를 해결하며,</span><span class="sxs-lookup"><span data-stu-id="439b4-262">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="439b4-263">문서에 없는 제목 스타일을 사용하여 목차를 업데이트할 때 발생하는 문제도 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-263">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="439b4-264">문서를 보낼 때 Word 문서에 저장된 디지털 서명이 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-264">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-march-13"></a><span data-ttu-id="439b4-266">버전 2004: 3월 13일</span><span class="sxs-lookup"><span data-stu-id="439b4-266">Version 2004: March 13</span></span>
<span data-ttu-id="439b4-267">*버전 2004 (빌드 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="439b4-267">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-269">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-269">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-270">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-270">Excel</span></span>
- <span data-ttu-id="439b4-271">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-271">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="439b4-272">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-272">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="439b4-273">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-273">PowerPoint</span></span>
- <span data-ttu-id="439b4-274">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-274">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="439b4-275">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-275">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="439b4-276">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-276">Word</span></span>
- <span data-ttu-id="439b4-277">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-277">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="439b4-278">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-278">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-281">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-281">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="439b4-282">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-282">Access</span></span>
- <span data-ttu-id="439b4-283">Access의 다른 나라 버전이 사용자 인터페이스에서 영어 문자열을 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-283">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-284">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-284">Excel</span></span>
- <span data-ttu-id="439b4-285">다양한 셀을 프로그래밍 방식으로 편집할 때 사용자에게 발생할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-285">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="439b4-286">일본어 환경으로 csv 파일을 열 때 발생할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-286">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-287">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-287">Outlook</span></span>
- <span data-ttu-id="439b4-288">메일에 첨부 파일을 추가하거나 저장할 때 파일을 끌어다 놓는 방법을 사용하는 경우(메뉴를 사용하는 것과 반대로) 파일의 "최종 수정 날짜"가 업데이트되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-288">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="439b4-289">사용자가 검색 단추를 클릭하는 대신 상세 검색 창에서 Enter 키를 누르면 검색이 시작되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-289">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="439b4-290">"사용 가능한 경우 사용자 사진 표시" 옵션을 사용하지 않도록 설정한 경우 검색에서 사용자에 대한 정보가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-290">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="439b4-291">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-291">Project</span></span>
- <span data-ttu-id="439b4-292">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-292">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="439b4-293">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-293">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-294">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-294">Word</span></span>
- <span data-ttu-id="439b4-295">메모를 입력하거나 편집하고 Ctrl+A를 사용할 때 메모 카드 내에서 텍스트를 선택하는 대신 캔버스에서 텍스트를 선택하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-295">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="439b4-296">빠른 인쇄를 사용하여 인쇄한 후에 편집하려고 할 때 문서의 단어 맞춤이 스크램블되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-296">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="439b4-297">두 문서를 하나의 문서로 병합할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-297">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="439b4-298">수식 관련 수정을 표시할 때 파일을 저장하면 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-298">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-march-06"></a><span data-ttu-id="439b4-300">버전 2003: 3월 6일</span><span class="sxs-lookup"><span data-stu-id="439b4-300">Version 2003: March 06</span></span>
<span data-ttu-id="439b4-301">*버전 2003(빌드 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="439b4-301">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-303">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-303">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-304">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-304">Outlook</span></span>

- <span data-ttu-id="439b4-305">Outlook Web Access로 규칙을 만들 때 Exchange 서버에 유지되지 않아 충돌이 발생하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-305">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="439b4-306">어두운 모드의 Outlook에서 '보낸 사람:' 입력란에 드롭다운 목록이 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-306">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="439b4-307">사용자가 다른 응용 프로그램에서 파일을 열 때 파일 탐색기를 통해 파일을 전자 메일 메시지에 첨부할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-307">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-308">PowerPoint</span></span>

- <span data-ttu-id="439b4-309">축소판 그림 위로 마우스를 가져가면 권장 축소판 그림이 깜박이는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-309">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="439b4-310">경우에 따라 PowerPoint가 중단될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-310">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-311">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-311">Word</span></span>

- <span data-ttu-id="439b4-312">편집에 대해 보호된 문서의 비교 기능 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-312">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-313">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-313">Office Suite</span></span>

- <span data-ttu-id="439b4-314">Word/Excel/PowerPoint에서 UPN(사용자 계정 이름)이 더 이상 대소문자를 구분하지 않아 SharePoint에서 파일 작업시 오류가 줄어듭니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-314">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="439b4-315">File \ Options 대화 상자의 '확인'단추가 회색으로 표시되고 기능에는 영향을 미치지 않는 외관상의 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-315">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

## <a name="version-2003-february-28"></a><span data-ttu-id="439b4-318">버전 2003: 2월 28일</span><span class="sxs-lookup"><span data-stu-id="439b4-318">Version 2003: February 28</span></span>
<span data-ttu-id="439b4-319">*버전 2003 (빌드 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="439b4-319">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-321">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-321">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-322">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-322">Outlook</span></span>

- <span data-ttu-id="439b4-323">**IT 관리자에 대한 인시던트 알림:** Microsoft 365 테넌트 전역 관리자 및 Office 앱 관리자는 Windows용 Outlook의 새로운 오른쪽 패널 알림을 통해 사용자에게 영향을 주는 Outlook 및 O365 Exchange 인시던트에 대한 알림을 받습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-323">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-324">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-324">PowerPoint</span></span>

- <span data-ttu-id="439b4-325">**개선된 잉크를 통한 도형 다이어그램 작성 경험:** 더 나은 다이어그램을 그리고 Office 개체를 조작할 수 있도록 변환합니다. [자세히 알아보기](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="439b4-325">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-328">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-329">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-329">Excel</span></span>

- <span data-ttu-id="439b4-330">인쇄 미리 보기에서 슬라이서의 텍스트 크기가 제대로 조정되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-330">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-331">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-331">Outlook</span></span>

- <span data-ttu-id="439b4-332">메일에 첨부 파일을 추가하거나 저장할 때 파일을 끌어다 놓는 방법을 사용하는 경우(메뉴를 사용하는 것과 반대로) 파일의 "최종 수정 날짜"가 업데이트되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-332">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="439b4-333">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-333">Word</span></span>

- <span data-ttu-id="439b4-334">메모 카드를 탭할 때 메모 편집 상자에 포커스가 표시되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-334">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="439b4-335">수식에 텍스트 콘텐츠 컨트롤과 같은 컨트롤을 삽입한 다음 파일을 저장하고 열면 읽을 수 없는 콘텐츠 오류가 발생합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-335">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="439b4-336">이전에 암호로 보호된 파일을 클라우드 저장소에 저장하지 못하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-336">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-337">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-337">Office Suite</span></span>

- <span data-ttu-id="439b4-338">동일한 SharePoint 라이브러리의 Word/Excel/PowerPoint에서 여러 문서를 열 때 첫 번째로 열린 문서만 정책 준수에 대한 검사가 이뤄지는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-338">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-february-21"></a><span data-ttu-id="439b4-340">버전 2003: 2월 21일</span><span class="sxs-lookup"><span data-stu-id="439b4-340">Version 2003: February 21</span></span>
<span data-ttu-id="439b4-341">*버전 2003 (빌드 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-341">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-343">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-343">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="439b4-344">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-344">Office Suite</span></span>

- <span data-ttu-id="439b4-345">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="439b4-345">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-348">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-348">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-349">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-349">Excel</span></span>
- <span data-ttu-id="439b4-350">피벗 테이블 측정의 이름을 바꿀 때 사용자가 겪을 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-350">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="439b4-351">VBA 매크로를 사용하여 범위의 내용을 지우면 사용자가 경험할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-351">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="439b4-352">사용자가 리본과 상호 작용하는 매크로를 실행할 때 UI가 깜박이는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-352">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="439b4-353">파일의 첫 단어가 TABLE 인 경우 CSV 파일이 잘못 로드되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-353">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="439b4-354">확대/축소 수준이 다른 두 통합 문서 간에 전환할 때 사용자가 충돌을 경험할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-354">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-355">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-355">Outlook</span></span>
- <span data-ttu-id="439b4-356">Outlook이 밤새 실행 중인 상태에서 사용자가 공용 폴더 메시지를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-356">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="439b4-357">Gmail 계정 추가의 인증 작업 과정에서 권한 페이지의 '허용' 및 '거부' 버튼이 비활성화되는 경합 상태를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-357">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="439b4-358">로깅이 꺼져 있어도 일부 시나리오에서 Outlook이 예기치 않게 로깅 출력을 생성하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-358">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-359">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-359">Word</span></span>
- <span data-ttu-id="439b4-360">마우스 포인터가 주석 카드 위로 마우스를 가져갈 때 주석 카드가 항상 강조 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-360">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="439b4-361">문서 공동 작성 세션 중에 주석 카드에 직접 이미지를 추가하면 태그가 추가될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-361">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="439b4-362">이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-362">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-363">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-363">Office Suite</span></span>
- <span data-ttu-id="439b4-364">Word/Excel/PowerPoint 문서와 함께 Multichoice/ Lookup/Managed-metadata 속성을 사용하고 SharePoint 문서 라이브러리에 저장할 때, 이러한 속성은 이전에 255 자로 제한되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-364">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="439b4-365">이러한 속성이 255자를 초과하면 해당 문서를 저장할 수 없었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-365">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="439b4-366">이 변경으로 이 제한이 2048자로 늘었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-366">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-february-14"></a><span data-ttu-id="439b4-368">버전 2003: 2월 14일</span><span class="sxs-lookup"><span data-stu-id="439b4-368">Version 2003: February 14</span></span>
<span data-ttu-id="439b4-369">*버전 2003 (빌드 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-369">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-371">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-371">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-372">Outlook</span></span>

- <span data-ttu-id="439b4-373">\*\*종속적인 Wi-Fi 네트워크에 대한 새로운 경험: \*\* 로그인하기 위해 웹 페이지가 필요한 Wi-Fi 네트워크에 가입한 적이 있습니까?</span><span class="sxs-lookup"><span data-stu-id="439b4-373">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="439b4-374">이제 Outlook이 이를 감지하여 연결하는 데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-374">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-375">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-375">Word</span></span>

- <span data-ttu-id="439b4-376">\*\*그리기 도구 상자에서 잉크 편집기 찾기: \*\* 그리기를 선택한 다음 잉크 편집기 펜을 선택하여 손가락이나 디지털 펜으로 문서를 편집하십시오.</span><span class="sxs-lookup"><span data-stu-id="439b4-376">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="439b4-377">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-377">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="439b4-378">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-378">Office Suite</span></span>

- <span data-ttu-id="439b4-379">**더 명확한 상태 표시줄 아이콘:** 상태 표시줄 아이콘을 쉽게 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-379">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-382">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-382">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-383">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-383">Outlook</span></span>

- <span data-ttu-id="439b4-384">사용자가 "약속 있음/없음 옵션" 일정 권한 대화 상자에 액세스하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-384">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="439b4-385">다른 시간대에서 보낸 되풀이 모임 인스턴스를 열 때 "죄송합니다. 이 항목을 여는 데 문제가 있습니다"라는 경고가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-385">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="439b4-386">해당 메시지에서 첨부 파일을 끌어서 놓은 후 사용자가 .msg 파일을 다시 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-386">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="439b4-387">첨부 파일 이름에 괄호가 포함된 경우 Outlook에서 OneDrive로 파일 첨부 파일을 업로드한 후 파일 이름이 변경될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-387">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-388">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-388">PowerPoint</span></span>

- <span data-ttu-id="439b4-389">Excel 차트가 포함된 PowerPoint 또는 Word에서 문서를 저장하지 못하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-389">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-390">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-390">Word</span></span>

- <span data-ttu-id="439b4-391">PDF로 내보낼 때 문서의 그림이 투명성을 잃는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-391">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-february-07"></a><span data-ttu-id="439b4-393">버전 2002: 2월 7일</span><span class="sxs-lookup"><span data-stu-id="439b4-393">Version 2002: February 07</span></span>
<span data-ttu-id="439b4-394">*버전 2002 (빌드 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="439b4-394">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-396">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-396">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="439b4-397">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-397">Access</span></span>

- <span data-ttu-id="439b4-398">**Query Designer, SQL 보기 및 관계 창에서 생산성을 향상시킬 수 있습니다.** 테이블을 마우스 오른쪽 단추로 클릭하여 열고 디자인하고 크기를 조정하고 숨겨보세요.</span><span class="sxs-lookup"><span data-stu-id="439b4-398">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="439b4-399">SQL 보기에서 텍스트를 검색하고 바꾸세요.</span><span class="sxs-lookup"><span data-stu-id="439b4-399">Search and replace text in SQL View.</span></span> <span data-ttu-id="439b4-400">관계 창에서 테이블을 여러 개 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="439b4-400">Select multiple tables in the Relationships window.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-403">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-403">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="439b4-404">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-404">Access</span></span>

- <span data-ttu-id="439b4-405">이 업데이트는 ADODB 사용시 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-405">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="439b4-406">VB 코드의 레코더 개체에서 오류가 잘못 보고될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-406">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="439b4-407">이 업데이트는 Microsoft Access에서 연결된 SQL Server 테이블의 ID 열이 식별되지 않아서 행이 올바르지 않게 삭제된 것으로 보고되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-407">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-408">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-408">Excel</span></span>

- <span data-ttu-id="439b4-409">동적 배열에서 Text To Columns를 사용할 때 Excel이 중단되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-409">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-410">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-410">Outlook</span></span>

- <span data-ttu-id="439b4-411">월 보기를 사용하여 일정을 스크롤할 때 이전 일정 이벤트가 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-411">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="439b4-412">Citrix 환경에서 30개 이상의 캘린더를 볼 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-412">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-413">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-413">PowerPoint</span></span>

- <span data-ttu-id="439b4-414">이벤트 처리기가 실행 중인 경우, 파일을 닫은 후 PowerPoint에서 프레젠테이션 모음의 해당 파일을 즉시 제거하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-414">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="439b4-415">따라서 개체 모델에서 보고한 열려 있는 프레젠테이션 수가 올바르지 않아 PowerPoint가 종료되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-415">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="439b4-416">형광펜 관련 문제를 해결했습니다. 어두운 형광펜 색상의 텍스트는 흑백 모드에서 검은 색으로 인쇄됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-416">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-417">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-417">Word</span></span>

- <span data-ttu-id="439b4-418">목차를 업데이트하고 스크롤하면 때때로 문서 위에 회색 영역이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-418">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="439b4-419">문서를 공동 작성하는 경우 루트 메모의 초안 버전이 유지되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-419">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="439b4-420">메모 카드 간에 앞뒤로 이동할 때 때때로 선택 강조 표시로 처음 선택한 메모가 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-420">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="439b4-421">메모가 작성되었지만 게시되지 않고 사용자가 파일을 저장하려고 하는 경우 '찾아보기'를 사용하여 파일을 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-421">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="439b4-422">SlideTrack을 활성화하고 메모 창을 닫으면 Ctrl+Alt+M을 눌러 메모 창을 열지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-422">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="439b4-423">테이블에 @mention을 추가할 때 '이 문서의 테이블이 손상되었습니다'라는 오류 메시지가 생성될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-423">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-424">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-424">Office Suite</span></span>

- <span data-ttu-id="439b4-425">노르웨이 니노르스크(nn-no) 교정 도구 패키지가 잘못 설치될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-425">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-january-31"></a><span data-ttu-id="439b4-427">버전 2002: 1월 31일</span><span class="sxs-lookup"><span data-stu-id="439b4-427">Version 2002: January 31</span></span>
<span data-ttu-id="439b4-428">*버전 2002(빌드 12513.20010)*</span><span class="sxs-lookup"><span data-stu-id="439b4-428">*Version 2002 (Build 12513.20010)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-430">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-430">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-431">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-431">Excel</span></span>

- <span data-ttu-id="439b4-432">**읽고 즉시 회신:** 통합 문서를 열지 않고 전자 메일에서 바로 메모와 멘션에 회신합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-432">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="439b4-433">**쿼리 편집기의 데이터 프로파일링:** 열에서 데이터를 한눈에 분석하고 오류와 비어 있는 값을 식별하며 배포 히스토그램을 표시하는 기능 등을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-433">**Data Profiling in Query Editor:** Get-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-436">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-436">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-437">Outlook</span></span>

- <span data-ttu-id="439b4-438">보존 정책에 따라 만료되는 전자 메일에 두 개의 레이블이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-438">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="439b4-439">하나는 메일이 하루 내에 만료되고 다른 하나는 2일 후에 만료된다는 것을 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-439">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-440">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-440">Word</span></span>

- <span data-ttu-id="439b4-441">&quot;반전&quot; 페이지 색이 있는 읽기 모드에서 메모 힌트가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-441">Fixed an issue where comment hint was not visible in read mode with &quot;Inverse&quot; page color.</span></span>

- <span data-ttu-id="439b4-442">메모를 편집하고 텍스트를 기울임꼴로 표시하고 게시하면 기울임꼴 서식이 손실되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-442">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>

- <span data-ttu-id="439b4-443">메모 상황에 맞는 메뉴에서 메모 명령(메모 편집, 메모에 대한 회신, 메모 삭제, 메모 확인)이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-443">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-january-17"></a><span data-ttu-id="439b4-445">버전 2002: 1월 17일</span><span class="sxs-lookup"><span data-stu-id="439b4-445">Version 2002: January 17</span></span>
<span data-ttu-id="439b4-446">*버전 2002(빌드 12508.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-446">*Version 2002 (Build 12508.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-448">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-448">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="439b4-449">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-449">Word</span></span>

- <span data-ttu-id="439b4-450">**멘션 및 댓글 알림 전자 메일에 이제 미리 보기가 포함됩니다**: 이제 멘션 및 댓글에 대한 전자 메일 알림에 댓글 텍스트와 참조 항목에 대한 컨텍스트의 미리 보기가 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-450">**Mention & comment notification emails now contain previews:** Email notifications for mentions & comments will now include previews of the comment text and context for what it is referring to.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-453">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-453">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-454">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-454">Excel</span></span>

- <span data-ttu-id="439b4-455">일부 경우에 접근성 검사에 도형에 대한 추천 항목이 나타나지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-455">In some cases, the Accessibility checker would not show the recommendations for shapes.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-456">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-456">Outlook</span></span>

- <span data-ttu-id="439b4-457">왼쪽 탐색 창의 '즐겨찾는 사람’에 저장된 폴더는 간헐적으로 사라질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-457">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-458">PowerPoint</span></span>

- <span data-ttu-id="439b4-459">PowerPoint 잉크 애니메이션에서 잉크가 완전히 렌더링되지 않거나 건너뛰기될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-459">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2001-january-10"></a><span data-ttu-id="439b4-461">버전 2001: 1월 10일</span><span class="sxs-lookup"><span data-stu-id="439b4-461">Version 2001: January 10</span></span>
<span data-ttu-id="439b4-462">*버전 2001(빌드 12430.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-462">*Version 2001 (Build 12430.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-464">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-464">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-465">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-465">Excel</span></span>
- <span data-ttu-id="439b4-466">**도형을 그림으로 저장:** 몇 번의 클릭만으로 도형, 아이콘 또는 기타 개체를 그림 파일로 저장하여 다른 곳에서 다시 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-466">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="439b4-467">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-467">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a><span data-ttu-id="439b4-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-468">Outlook</span></span>
- <span data-ttu-id="439b4-469">**이제 사용자는 Word/Excel/Outlook에서 개체를 Windows용 그림으로 저장할 수 있습니다.:** PowerPoint에서 이미 표시되는 기능을 사용하여 사용자는 이제 Word, Excel 및 Outlook에서 개체를 그림으로 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-469">**User can now save objects in Word/Excel/Outlook as a picture for Windows.:** With the ability already seen in PowerPoint, users can now save objects in Word, Excel and Outlook as a picture.</span></span> <span data-ttu-id="439b4-470">개체에는 도형, 아이콘, 그림 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-470">Objects include shapes, icons, pictures, and more!</span></span> <span data-ttu-id="439b4-471">이는 마우스 오른쪽 단추를 클릭하여 메뉴를 통해 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-471">This can be accessed through the right-click menu.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-472">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-472">Word</span></span>
- <span data-ttu-id="439b4-473">**주변에 도형을 그려 Word에서 잉크를 쉽게 선택할 수 있습니다.:** 그리기 탭의 올가미 도구를 사용하면 잉크로 그린 개체를 선택하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-473">**Easily select ink in Word by drawing a shape around it.:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="439b4-474">개별 스트로크를 선택하거나 단어 전체를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-474">Select individual strokes, or whole words.</span></span> <span data-ttu-id="439b4-475">잉크 수가 많고 일부 잉크만을 사용하려는 경우 유용합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-475">It's handy when you have lots of ink and you only want to work with some of it.</span></span> [<span data-ttu-id="439b4-476">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-476">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="439b4-477">**도형을 그림으로 저장:** 몇 번의 클릭만으로 도형, 아이콘 또는 기타 개체를 그림 파일로 저장하여 다른 곳에서 다시 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-477">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="439b4-478">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-478">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-481">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-481">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="439b4-482">OneNote</span><span class="sxs-lookup"><span data-stu-id="439b4-482">OneNote</span></span>
- <span data-ttu-id="439b4-483">100% 해상도에서는 페이지 탭이 너무 작게 표시되고 함께 닫힐 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-483">Page tabs may appear too small and close together at 100% resolution.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-484">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-484">Word</span></span>
- <span data-ttu-id="439b4-485">다수의 메모 집합에서 메모 목록 끝에 있는 메모를 삭제하면 창이 맨 위로 스크롤될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-485">In a large set of comments, deleting a comment near the end of the list of comments may result in the pane scrolling all the way to the top.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2001-january-03"></a><span data-ttu-id="439b4-487">버전 2001: 1월 3일</span><span class="sxs-lookup"><span data-stu-id="439b4-487">Version 2001: January 03</span></span>
<span data-ttu-id="439b4-488">*버전 2001(빌드 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-488">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-490">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-490">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-491">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-491">Excel</span></span>
- <span data-ttu-id="439b4-492">일부 테두리 선이 A4 크기 용지에서 예상한 대로 인쇄되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-492">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="439b4-493">VBA를 사용하여 시트에서 차트 개체의 머리글/바닥글에 이미지를 추가하면 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-493">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="439b4-494">차트 축의 서식을 지정할 때 레이블 간격이 255로 제한되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-494">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="439b4-495">데이터 원본의 URL이 잘린 XML 쿼리를 새로 고치는 동안 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-495">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="439b4-496">통합 문서 통계는 개인용 매크로 통합 문서를 포함하여 열려 있는 모든 통합 문서에서 매크로 개수를 보고합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-496">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-497">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-497">Outlook</span></span>
- <span data-ttu-id="439b4-498">폴더를 전환하면 메일 목록/메일 미리 보기가 잠시 동안 흰색으로 깜박일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-498">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="439b4-499">이 동작은 어둡게 모드에서 더 뚜렷했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-499">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-500">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-500">PowerPoint</span></span>
- <span data-ttu-id="439b4-501">Shape.Paste 메서드를 호출하면 붙여 넣은 도형에 포커스가 생기는 개체 모델 문제를 해결했습니다.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="439b4-501">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="439b4-502">복사/붙여넣기 시나리오 개선: &nbsp;프로그래밍 방법으로 PowerPoint 슬라이드에서 도형을 복사하여 루프의 다른 슬라이드에 붙여 넣으면 예외 오류가 발생할 수 있습니다.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="439b4-502">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="439b4-503">구역 머리글을 축소하고 확장한 후에는 슬라이드의 구역 머리글에 있는 애니메이션이 올바르게 렌더링되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-503">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="439b4-504">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-504">Project</span></span>
- <span data-ttu-id="439b4-505">작업 및 자원 활용 현황 보기에서 텍스트 래핑이 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-505">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="439b4-506">자원에 둘 이상의 비용 종류가 있는 경우 과제의 비용 금액이 정확하지 않을 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-506">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-507">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-507">Word</span></span>
- <span data-ttu-id="439b4-508">수식에 텍스트 콘텐츠 컨트롤과 같은 컨트롤을 삽입한 다음 파일을 저장하고 열면 읽을 수 없는 콘텐츠 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-508">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="439b4-509">공동 작성시 Word 온라인을 사용하여 메모를 추가하는 경우 Word 데스크톱에 표시되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-509">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-510">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-510">Office Suite</span></span>
- <span data-ttu-id="439b4-511">라이선스가 하나만 있는 라이선스를 변경할 때 유효한 라이선스에 잘못된 만료 날짜가 표시되는 문제를 제거했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-511">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2001-december-13"></a><span data-ttu-id="439b4-513">버전 2001: 12월 13일</span><span class="sxs-lookup"><span data-stu-id="439b4-513">Version 2001: December 13</span></span>
<span data-ttu-id="439b4-514">*버전 2001 (빌드 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-514">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-516">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-516">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-517">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-517">Outlook</span></span>

- <span data-ttu-id="439b4-518">**사용자가 소유한 그룹으로 전자 메일 끌기:** 메시지와 대화를 받은 편지함에서 끌어서 이동하고 복사합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-518">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="439b4-519">끌어 놓은 메시지는 모든 그룹 구성원과 공유됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-519">Messages you drag will be shared with all group members.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-522">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-522">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="439b4-523">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-523">Access</span></span>
- <span data-ttu-id="439b4-524">연결된 ODBC 테이블을 참조하고 정렬 기준 절을 포함하는 통합 쿼리를 실행할 때 64비트 버전의 Access에서 충돌 문제가 발생합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-524">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="439b4-525">Access의 통합 쿼리에서(O365) 데이터 합계를 구할 때 소수점 데이터가 잘릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-525">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="439b4-526">ACE용 COM 인터페이스가 Office 응용 프로그램 외부에서 사용할 수 있도록 노출되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-526">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-527">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-527">Excel</span></span>
- <span data-ttu-id="439b4-528">3D 모델(애니메이션 또는 정적)을 삽입하고 ‘다른 그림으로 저장' 작업이 작동하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-528">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="439b4-529">백스테이지에서 피드백을 시작하는 단축키(Alt+Ctrl + 7/8)이 AZERTY 키보드와 충돌합니다(Alt-Gr + 7/8).</span><span class="sxs-lookup"><span data-stu-id="439b4-529">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="439b4-530">영향: 사용자가 '\'와 같은 일부 문자를 사용 하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-530">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-531">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-531">Outlook</span></span>
- <span data-ttu-id="439b4-532">받는 사람의 잘못된 주소로 전자 메일을 전송하는 문제를 해결 합니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-532">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="439b4-533">Outlook에서 사서함에 대한 &quot;읽기&quot; 액세스 권한만 있는 사용자가 메시지의 읽음/읽지 않음 상태를 변경할 수 있도록 허용한 한 문제를 해결 합니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-533">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="439b4-534">웹 사이트의 보안 인증서 해지는 제품 지원에 의해 재생산 될 수 없습니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-534">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="439b4-535">근본적인 원인을 파악 하기 위해 로깅을 추가 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-535">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="439b4-536">사용자에게 동기화 실패를 표시하는 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-536">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-537">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-537">PowerPoint</span></span>
- <span data-ttu-id="439b4-538">3D 모델(애니메이션 또는 정적)을 삽입하고 ‘다른 그림으로 저장' 작업이 작동하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-538">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="439b4-539">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-539">Project</span></span>
- <span data-ttu-id="439b4-540">수동 일정 예약 하위 작업의 요약 롤업에서는 작업이 계산 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-540">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="439b4-541">서버 기반 프로젝트를 저장 하려고 하면 리본 단추에서 호출한 Project VBA 코드가 작동 하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-541">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="439b4-542">Project가 실행 되고 있지 않은 경우, SharePoint 문서 라이브러리에서 프로젝트 파일을 열면 오류가 표시 되고 파일이 열리지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-542">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-543">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-543">Word</span></span>
- <span data-ttu-id="439b4-544">기존 파일 저장이 작동 하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-544">Saving existing files may not work.</span></span>
- <span data-ttu-id="439b4-545">맞춤법 및 문법 검사 편집기 창에서 화살표 키를 사용 하면 깜빡임 현상이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-545">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="439b4-546">추가 작업 해결 시 연결된 설명이 포인트 메모로 변환되지 않을 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-546">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="439b4-547">3D 모델(애니메이션 또는 정적)을 삽입하고 ‘다른 그림으로 저장' 작업이 작동하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-547">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-548">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-548">Office Suite</span></span>
- <span data-ttu-id="439b4-549">Office 업데이트 메시지가 다른 언어로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-549">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="439b4-550">앞으로 Office 업데이트 메시지 언어가 Windows 표시 언어와 정확하게 일치할 것입니다.  </span><span class="sxs-lookup"><span data-stu-id="439b4-550">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1912-december-06"></a><span data-ttu-id="439b4-552">버전 1912: 12월 06</span><span class="sxs-lookup"><span data-stu-id="439b4-552">Version 1912: December 06</span></span>
<span data-ttu-id="439b4-553">*버전 1912(빌드 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="439b4-553">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-555">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-555">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-556">Outlook</span></span>

- <span data-ttu-id="439b4-557">**고급 그룹 전자 메일 설정:** 이 기능을 사용하면 그룹 사용자가 전자 메일이나 이벤트를 받은 편지함에서 받거나 팔로우하도록 사용자 지정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-557">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="439b4-558">**그룹 명명 정책:** 그룹 명명 정책을 사용하면 IT 관리자가 조직의 사용자가 만든 그룹의 이름을 표준화하고 관리할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-558">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="439b4-559">관리자는 그룹 이름을 만들 때 특정 접두사와 접미사를 추가하도록 요구할 수 있으며, 특정 단어를 사용할 수 없도록 차단할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-559">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="439b4-560">이는 그룹 이름에 부적절한 단어의 사용을 최소화하는데 도움을 줄뿐만 아니라 IT가 해당 디렉터리의 그룹의 표현을 관리하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-560">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="439b4-561">명명 정책은 또한 팀 사이트를 배포하는 조직이 부서를 기준으로 분류하는데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-561">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-562">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-562">Office Suite</span></span>

- <span data-ttu-id="439b4-563">**탭 창:** 이제 앱의 오른쪽에 있는 탭 UI를 사용하여 여러 창 간에 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-563">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="439b4-564">UI는 2개 이상의 창이 열려있는 경우에만 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-564">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-567">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-567">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-568">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-568">Excel</span></span>
- <span data-ttu-id="439b4-569">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-569">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="439b4-570">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-570">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="439b4-571">4K 해상도의 하드웨어 그래픽 가속을 사용하지 않도록 설정하는 경우 스크롤링할 때 셀 렌더링이 지연될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-571">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="439b4-572">셀 경계와 겹치는 긴 수식을 지우더라도 여전히 셀 경계가 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-572">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="439b4-573">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-573">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="439b4-574">여백 드롭다운 메뉴가 제대로 렌더링되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-574">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="439b4-575">OneNote</span><span class="sxs-lookup"><span data-stu-id="439b4-575">OneNote</span></span>
- <span data-ttu-id="439b4-576">OneNote는 '모임 노트' Outlook 추가 기능을 통해 열리지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-576">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-577">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-577">Outlook</span></span>
- <span data-ttu-id="439b4-578">보존 정책 레이블에는 보존 기간이 괄호로 표시 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-578">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="439b4-579">일본어 언어 팩이 있는 연락처 카드에 공백이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-579">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="439b4-580">Outlook 전자 메일 메시지에 인라인으로 삽입된 이미지의 크기가 간혹 변경되는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-580">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-581">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-581">PowerPoint</span></span>
- <span data-ttu-id="439b4-582">한 개의 클라우드 파일의 한 슬라이드에 있는 두 개(혹은 이상)의 비디오가 있는 경우 비디오 이미지는 올바르게 렌더링되지만 사용자가 재생을 하기 위해 각각을 클릭 시 비디오 내용이 동일합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-582">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="439b4-583">일부의 경우에는 터치 장치를 사용한 스크롤이 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-583">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="439b4-584">여백 드롭다운 메뉴가 제대로 렌더링되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-584">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="439b4-585">한 Office 응용 프로그램에서 다른 응용 프로그램으로의 Safelinks가 연결된 응용 프로그램을 시작 하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-585">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="439b4-586">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-586">Project</span></span>
- <span data-ttu-id="439b4-587">프로젝트 비교 기능을 사용하는 경우 프로젝트가 충돌할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-587">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="439b4-588">사용자가 어두운 모드인 경우에 과도하게 할당된 리소스를 가지고 작업 검사자 패널로 이동하는 경우 테이블을 읽을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-588">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="439b4-589">배정이 없는 작업에 대한 노력의 설정은 1일로 반올림됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-589">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-590">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-590">Word</span></span>
- <span data-ttu-id="439b4-591">특정 조건에서는 메일 병합 후의 저장이 작동하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-591">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="439b4-592">문서 블록 이끌이가 잘못된 알림을 표시할 수 있습니다.&quot;사용자가 스타일, 문서 블록을 수정했습니다&quot;.</span><span class="sxs-lookup"><span data-stu-id="439b4-592">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="439b4-593">복사/붙여넣기를 사용하는 경우 메모 창이 다시 로드되는 경우가 간혹 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-593">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="439b4-594">메모가 올바른 순서로 붙여넣기가 되지 않는 경우가 가끔 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-594">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="439b4-595">기존 문서에 사용자 지정 스타일을 사용한 다단 목록으로 구성된 서식 파일을 적용 시 특정 조건에서는 스타일이 유지되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-595">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="439b4-596">나눠진 화면 테두리의 크기를 조정하면 화면이 추가로 분할될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-596">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="439b4-597">여백 드롭다운 메뉴가 정확히 렌더링되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-597">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="439b4-598">댓글 카드에 있는 사용자에 멘션을 사용 시 JSON이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-598">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="439b4-599">한 Office 응용 프로그램에서 다른 응용 프로그램으로의 Safelinks가 연결된 응용 프로그램을 시작 하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-599">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-600">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-600">Office Suite</span></span>
- <span data-ttu-id="439b4-601">일본어 기반 제품의 경우 계정 사용자의 이름과 성이 잘못된 순서로 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-601">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="439b4-602">메모 위에 마우스 포인터를 올리면 메모 주변에 텍스트 상자의 윤곽이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-602">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1912-november-15"></a><span data-ttu-id="439b4-604">버전 1912: 11월 15일</span><span class="sxs-lookup"><span data-stu-id="439b4-604">Version 1912: November 15</span></span>
<span data-ttu-id="439b4-605">*버전 1912 (빌드 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-605">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-607">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-607">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="439b4-608">Insights Services</span><span class="sxs-lookup"><span data-stu-id="439b4-608">Insights Services</span></span>
- <span data-ttu-id="439b4-609">**Excel 아이디어의 자연 언어 쿼리:** 데이터에 대한 자연 언어 질문을 하는 Excel 아이디어의 새로운 기능</span><span class="sxs-lookup"><span data-stu-id="439b4-609">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-612">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-612">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-613">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-613">Excel</span></span>
- <span data-ttu-id="439b4-614">일부 현지화 과정에서 텍스트를 열로 기능이 작동하지 않을 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-614">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="439b4-615">셀 내에서 동적 배열 수식을 편집할 때 텍스트가 셀 경계선 외부에 정렬될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-615">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-616">Outlook</span></span>
- <span data-ttu-id="439b4-617">그룹 정책을 통해 S/MIME 구성을 적용하는 기능이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-617">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="439b4-618">포함된 이미지가 생각보다 작게 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-618">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-619">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-619">PowerPoint</span></span>
- <span data-ttu-id="439b4-620">텍스트에서 포커스를 이동한 후 커서가 사라질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-620">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="439b4-621">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-621">Project</span></span>
- <span data-ttu-id="439b4-622">사용자가 라이선스 관련 에러를 경험할 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-622">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="439b4-623">날짜 선택기에서 오늘 버튼이 올바르지 않은 날짜를 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-623">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-624">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-624">Word</span></span>
- <span data-ttu-id="439b4-625">마우스 오른쪽 단추를 클릭하면 전체 단어가 선택되지 않을 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-625">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="439b4-626">제안된 형식으로 변환한 후에는 커서가 개체 내에서 계속 활성 상태로 유지될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-626">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="439b4-627">특정 시나리오에서 메시지 내 이미지 스케일링이 올바르지 않을 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-627">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="439b4-628">일부 테마에서는 선택된 메모를 확인하기가 어렵습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-628">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="439b4-629">숨겨진 판 스위치에서 메모 힌트를 선택하면 이제 모던 메모 판이 보여집니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-629">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-630">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-630">Office Suite</span></span>
- <span data-ttu-id="439b4-631">메모를 회신하면 텍스트 상자가 창 가장자리를 벗어나 세로로 확장될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-631">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1912-november-08"></a><span data-ttu-id="439b4-633">버전 1912: 11월 8일</span><span class="sxs-lookup"><span data-stu-id="439b4-633">Version 1912: November 08</span></span>
<span data-ttu-id="439b4-634">*버전 1912 (빌드 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-634">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-636">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-636">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="439b4-637">사용자 수명 주기</span><span class="sxs-lookup"><span data-stu-id="439b4-637">User Lifecycle</span></span>
- <span data-ttu-id="439b4-638">**AFO 활성화 경험 개선:** 고객이 새 PC와 함께 제공되는 Office를 활성화할 때 표시되는 화면 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-638">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-639">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-639">Word</span></span>
- <span data-ttu-id="439b4-640">**Word가 제공하는 새롭고 개선된 온라인 비디오 경험:** 새로운 비디오를 추가하거나 기존의 비디오 편집할 때 도움을 주는 새롭고 더 안전한 온라인 비디오 경험</span><span class="sxs-lookup"><span data-stu-id="439b4-640">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-643">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-643">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-644">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-644">Outlook</span></span>
- <span data-ttu-id="439b4-645">교차 폴더 콘텐츠를 수반하는 간헐적인 충돌</span><span class="sxs-lookup"><span data-stu-id="439b4-645">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-646">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-646">Office Suite</span></span>
- <span data-ttu-id="439b4-647">Excel에서 PowerPoint로 차트를 붙여넣으면 차트 크기가 줄어들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-647">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1911-november-01"></a><span data-ttu-id="439b4-649">버전 1911: 11월 1일</span><span class="sxs-lookup"><span data-stu-id="439b4-649">Version 1911: November 01</span></span>
<span data-ttu-id="439b4-650">*버전 1911 (빌드 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="439b4-650">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-652">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-652">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-653">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-653">Excel</span></span>
- <span data-ttu-id="439b4-654">**SVG 개체와 함께 컨텍스트를 가져오세요!:** 이제 Office에서 이러한 개체를 변환할 때 지도, 차트 및 기타 SVG 벡터 텍스트를 유지할 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-654">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="439b4-655">**Surface 펜을 집어들 때 펜 옵션보기:** Word, Excel 또는 PowerPoint에서 Surface 펜을 처음 집어들면 그리기 탭이 활성화되어 펜 색상을 쉽게 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-655">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-656">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-656">PowerPoint</span></span>
- <span data-ttu-id="439b4-657">**SVG 개체와 함께 컨텍스트를 가져오세요!:** 이제 Office에서 이러한 개체를 변환할 때 지도, 차트 및 기타 SVG 벡터 텍스트를 유지할 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-657">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="439b4-658">**Surface 펜을 집어들 때 펜 옵션보기:** Word, Excel 또는 PowerPoint에서 Surface 펜을 처음 집어들면 그리기 탭이 활성화되어 펜 색상을 쉽게 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-658">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="439b4-659">Visio</span><span class="sxs-lookup"><span data-stu-id="439b4-659">Visio</span></span>
- <span data-ttu-id="439b4-660">**Excel에서 세련된 Visio 다이어그램 만들기** Excel 내에서 데이터를 세련된 Visio 다이어그램으로 쉽고 빠르게 시각화합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-660">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="439b4-661">[자세히 알아보기](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span><span class="sxs-lookup"><span data-stu-id="439b4-661">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="439b4-662">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-662">Word</span></span>
- <span data-ttu-id="439b4-663">**Surface 펜을 집어들 때 펜 옵션보기:** Word, Excel 또는 PowerPoint에서 Surface 펜을 처음 집어들면 그리기 탭이 활성화되어 펜 색상을 쉽게 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-663">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="439b4-664">**공동 작성 개선:** 실시간으로 다른 사용자가 콘텐츠 변경 내용을 받을 수 있도록 하여 더 높은 공동 작성 환경을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-664">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="439b4-665">**다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다:** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-665">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-668">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-668">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-669">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-669">Excel</span></span>
- <span data-ttu-id="439b4-670">신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-670">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="439b4-671">다른 시트의 데이터를 참조하는 스파크 라인이 포함된 시트를 삭제하면 파일을 다시 열 때 손상된 것으로 식별될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-671">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="439b4-672">보고서 필터를 SQL 태뷸러 서버에 대한 쿼리의 나머지 피벗 테이블과 함께 변환할 때 잘못된 결과가 발생할 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-672">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="439b4-673">내레이터와 돋보기를 동시에 사용하면 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-673">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="439b4-674">내레이터와 돋보기를 동시에 사용하면 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-674">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-675">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-675">Outlook</span></span>
- <span data-ttu-id="439b4-676">전달된 전자 메일에 포함된 이미지가 누락될 수 있음</span><span class="sxs-lookup"><span data-stu-id="439b4-676">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="439b4-677">회의실 찾기 도구가 사용 가능한 회의실을 &quot;없음&quot;으로 표시할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-677">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="439b4-678">사용자가 엄격한 테넌트 제한이 있는 Outlook 프로필을 만들지 못할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-678">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-679">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-679">PowerPoint</span></span>
- <span data-ttu-id="439b4-680">내레이터와 돋보기를 동시에 사용하면 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-680">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="439b4-681">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-681">Project</span></span>
- <span data-ttu-id="439b4-682">사용자가 작업을 완료로 표시할 수 없으며, 이는 99%로 설정됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-682">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="439b4-683">평준화로 초과 할당을 해결할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-683">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-684">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-684">Word</span></span>
- <span data-ttu-id="439b4-685">내레이터와 돋보기를 동시에 사용하면 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-685">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="439b4-686">레거시 문서를 연 다음 정보 탭으로 이동하면 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-686">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="439b4-687">컨텍스트 메뉴에 교정 제안이 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-687">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="439b4-688">콘텐츠 정책이 메모에 제대로 적용되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-688">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="439b4-689">어두운 텍스트를 사용하여 쓰여진 레거시 메모가 어두운 모드에서 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-689">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="439b4-690">한국어/영어 자동 고침을 사용하는 경우 잘못된 문자가 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-690">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="439b4-691">상위 정책 레이블이 우선 순위를 가져야할 때 하위 정책 레이블이 적용될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-691">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="439b4-692">cid 링크: 요청 시 Outlook 메시지의 이미지&nbsp;가 이제 성공적으로 깨질 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="439b4-692">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="439b4-693">내레이터와 돋보기를 동시에 사용하면 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-693">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="439b4-694">탐색 창에서 검색이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-694">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-695">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-695">Office Suite</span></span>
- <span data-ttu-id="439b4-696">일부 드로잉이 미리보기 또는 슬라이드 쇼에서 표시되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-696">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="439b4-697">세로 텍스트 상자에서 일부 가타카나 문자가 잘못 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-697">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="439b4-698">연결되지 않은 네트워크 공유에 파일을 저장하면 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-698">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1911-october-25"></a><span data-ttu-id="439b4-700">버전 1911: 10월 25일</span><span class="sxs-lookup"><span data-stu-id="439b4-700">Version 1911: October 25</span></span>
<span data-ttu-id="439b4-701">*버전 1911(빌드 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="439b4-701">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-703">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-703">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="439b4-704">Visio</span><span class="sxs-lookup"><span data-stu-id="439b4-704">Visio</span></span>

- <span data-ttu-id="439b4-705">**Excel에서 세련된 Visio  다이어그램 만들기** Excel 내에서 데이터를 세련된 Visio 다이어그램으로 쉽고 빠르게 시각화합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-705">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="439b4-706">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-706">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="439b4-707">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-707">Word</span></span>

- <span data-ttu-id="439b4-708">**공동 작성 개선:** 실시간으로 다른 사용자가 콘텐츠 변경 내용을 받을 수 있도록 하여 더 높은 공동 작성 환경을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-708">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="439b4-709">**다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다:** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-709">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="439b4-712">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="439b4-712">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="439b4-713">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-713">Access</span></span>

- <div><span data-ttu-id="439b4-714"><span>레코드 수가 올바르지 않을 수 있습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-714"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="439b4-715">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-715">Excel</span></span>

- <div><span data-ttu-id="439b4-716"><span>병합된 셀이 있는 열을 삭제하는 성능이 크게 개선되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-716"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="439b4-717"><span>사용자가 Office 365 Excel 통합 문서 형식으로 저장하지 못할 수 있습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-717"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="439b4-718"><span>확인란을 제대로 렌더링할 수 없습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-718"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="439b4-719"><span>차트 크기에 대한 변경 내용을 저장할 수 없습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-719"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="439b4-720"><span>일부 VBA 함수는 새 차트 종류에서 오류를 반환합니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-720"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="439b4-721"><span>데이터 원본 대화 상자 선택에서 일부 필드의 대/소문자를 구분 하지 않습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-721"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="439b4-722">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-722">PowerPoint</span></span>

- <div><span data-ttu-id="439b4-723"><span>차트 크기에 대한 변경 내용을 저장할 수 없습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-723"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="439b4-724">Publisher</span><span class="sxs-lookup"><span data-stu-id="439b4-724">Publisher</span></span>

- <div><span data-ttu-id="439b4-725"><span>도형이 그래픽 테두리 외부에 표시될 수 있습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-725"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="439b4-726">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-726">Word</span></span>

- <div><span data-ttu-id="439b4-727"><span>도형이 그래픽 테두리 외부에 표시될 수 있습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-727"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="439b4-728"><span>텍스트를 강조 표시하는 것이 어려울 수 있습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-728"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="439b4-729"><span>사용자가 편집기의 개별 항목으로 이동하지 못하게 할 수 있습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-729"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="439b4-730"><span>문법 또는 맞춤법 오류가 강조 표시되지 않을 수 있습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-730"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="439b4-731"><span>차트 크기에 대한 변경 내용을 저장할 수 없습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-731"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="439b4-732"><span>@멘션에 서식 적용 후 연락처 카드를 열지 못할 수 있습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-732"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="439b4-733"><span>사용자가 Word, Excel 및 PowerPoint 문서를 저장할 수 없는 문제가 해결되었습니다.&nbsp; 이 문제는 새 파일을 만든 후 저장 아이콘을 클릭하거나 Ctrl + S를 눌러 &quot;다른 이름으로 저장 모델 대화 상자&quot; 옵션을 표시하는 사용자에게 영향을 줍니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-733"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="439b4-734">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-734">Office Suite</span></span>

- <div><span data-ttu-id="439b4-735"><span>Windows 7에서 도형을 사용하는 경우의 성능 문제</span></span><span class="sxs-lookup"><span data-stu-id="439b4-735"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1911-october-18"></a><span data-ttu-id="439b4-737">버전 1911: 10월 18일</span><span class="sxs-lookup"><span data-stu-id="439b4-737">Version 1911: October 18</span></span>
<span data-ttu-id="439b4-738">*버전 1911(빌드 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="439b4-738">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-740">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-740">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="439b4-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-741">Outlook</span></span>

- <span data-ttu-id="439b4-742">**가장 필요로 하는 사용자에게 접속할 수 있는 메일 보내기:** Outlook에서 접속할 수 있는 콘텐츠를 선호하는 사용자에게 전자 메일을 보낼 때 콘텐츠에 액세스가 가능한 지 확인하는 데 도움이 되는 메일 팁을 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-742">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-743">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-743">PowerPoint</span></span>

- <span data-ttu-id="439b4-744">\*\*모든 사용자를 위한 프레젠테이션 최적화: \*\* 접근성 검사기는 기능은 스크린 리더를 염두에 두고 슬라이드에서 개체를 정렬하는데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-744">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="439b4-745">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-745">Office Suite</span></span>

- <span data-ttu-id="439b4-746">\*\*업로드 센터가 주의를 요하는 파일들로 대체됩니다: \*\* 업로드 센터가 파일 > 열기 아래의 Office 응용 프로그램 내에 표시되는 주의를 요하는 파일들로 대체됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-746">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="439b4-747">이 새로운 환경은 업로드 센터와 비교 시 더욱 최신이고, 통합적이며 개입성이 낮습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-747">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="439b4-750">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-750">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-751">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-751">Excel</span></span>

- <div><span data-ttu-id="439b4-752"><span>자동 맞춤을 사용하여 행 높이를 조정할 때 확인란 컨트롤이 축소되었던 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-752"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="439b4-753"><span>스크롤 후 셀을 선택하면 잘못된 셀이 선택되었던 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-753"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="439b4-754">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-754">Outlook</span></span>

- <div><span data-ttu-id="439b4-755"><span>디지털로 서명된 첨부 파일을 사용하여 전자 메일에 서명할 때 디지털 서명이 훼손되는 문제를 확인했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-755"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="439b4-756"><span>메시지 본문에 끌어넣기를 한 후 긴 파일 이름이 잘리는 문제를 확인했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-756"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="439b4-757">리본이 자동으로 숨기기로 설정된 경우 검색 상자가 사라지는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-757">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="439b4-758">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-758">PowerPoint</span></span>

- <div><span data-ttu-id="439b4-759"><span>슬라이드 미리 보기의 가로 세로 비율이 제대로 잠기거나 해제되지 않는 문제를 확인했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-759"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="439b4-760">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-760">Project</span></span>

- <div><span data-ttu-id="439b4-761">업데이트 작업을 수행하는 동안 입력한 메모가 보존되지 않는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-761">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="439b4-762">사용자가 파일을 잠글 수 있지만 오류 메시지에 사용자 이름이 표시되지 않는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-762">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="439b4-763"><span>읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 확인했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-763"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="439b4-764">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-764">Word</span></span>

- <div><span data-ttu-id="439b4-765"><span>스크린 리더를 사용하는 동안 의견을 볼 때 발생하는 문제를 확인했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-765"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="439b4-766"><span>일부 비평이 맞춤법이나 문법의 비평으로 오인되는 문제를 확인했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-766"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="439b4-767"><span>새 의견 대화 상자에서 간혹 포커스가 맞지 않는 문제를 확인했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-767"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="439b4-768">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-768">Office Suite</span></span>

- <div><span data-ttu-id="439b4-769"><span>&quot;진행 중인 다른 설치&quot;의 잘못된 오류 메시지로 인해 업그레이드를 하지 못했던 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-769"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="439b4-770"><span>로컬 리소스에서 클라우드 리소스로의 동기화에 영향을 줄 수 있는 문제를 확인했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-770"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="439b4-771"><span>환영 메시지에 유효하지 않은 링크가 포함되는 문제를 확인했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-771"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1910-october-11"></a><span data-ttu-id="439b4-773">버전 1910: 10월 11일</span><span class="sxs-lookup"><span data-stu-id="439b4-773">Version 1910: October 11</span></span>
<span data-ttu-id="439b4-774">*버전 1910 (빌드 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="439b4-774">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)
[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)
[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="439b4-778">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-778">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-779">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-779">Excel</span></span>

- <div><span data-ttu-id="439b4-780">OneDrive에서 파일을 개체로 삽입하는 경우 발생 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-780">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="439b4-781">일부 콘텐츠에 하이퍼링크 서식이 제대로 적용 되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-781">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="439b4-782">구조적 절대 참조를 포함하는 수식이 잘못 조정 될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-782">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="439b4-783">이전 버전의 Office에서 작성한 통합 문서를 현재 버전의 Office에서 열었을 때 Excel이 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-783">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="439b4-784">Excel에서 복사한 콘텐츠를 다른 Office 응용 프로그램에 붙여 넣을 시 정확히 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-784">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="439b4-785">차트 템플릿을 사용하여 차트를 삽입할 때 미리 보기에 사용되는 색 수정</span><span class="sxs-lookup"><span data-stu-id="439b4-785">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="439b4-786">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-786">PowerPoint</span></span>

- <div><span data-ttu-id="439b4-787">AirSpace WinComp에서 실행 시 ARC 장치의 연결이 끊어질 수 있는 문제를 확인 했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-787">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="439b4-788">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-788">Word</span></span>

- <div><span data-ttu-id="439b4-789">OneDrive에서 파일을 개체로 삽입하는 경우 발생 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-789">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="439b4-790">그래픽 콘텐츠가 전자 메일 스레드에서 삭제되 게 하는 문제를 수정하기 위해 복구 단계를 개선했습니다.<span>&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="439b4-790">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (버그의 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1910-october-04"></a><span data-ttu-id="439b4-792">버전 1910: 10월 4일</span><span class="sxs-lookup"><span data-stu-id="439b4-792">Version 1910: October 04</span></span>
<span data-ttu-id="439b4-793">*버전 1910 (빌드 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-793">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-795">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-795">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-796">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-796">Excel</span></span>

- <span data-ttu-id="439b4-797">**데이터 시각화 도우미 추가 기능:** Excel에서 빠르게 Visio 플로차트를 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-797">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="439b4-798">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-798">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="439b4-801">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-801">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-802">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-802">Excel</span></span>

- <div><span data-ttu-id="439b4-803"><span>인쇄 미리 보기의 인쇄 영역이 올바르지 않았던 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-803"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="439b4-804"><span>공동 작성 세션이 진행되는 동안 피벗 테이블을 새로 고칠 수 없었던 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-804"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="439b4-805">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-805">Access</span></span>

- <div><span data-ttu-id="439b4-806">사용자가 공유 데이터베이스를 사용하는 경우 &quot;일관성이 없는 상태&quot; 오류가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-806">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="439b4-807">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-807">Outlook</span></span>

- <div><span data-ttu-id="439b4-808"><span>메일 폴더의 복제를 발생시킬 수 있었던 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-808"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="439b4-809"><span>S/MIME 암호화 전자 메일을 보내려고 할 때 잘못된 오류 메시지를 발생시킬 수 있었던 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-809"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="439b4-810"><span>사용자가 Skype에서 '부재 중 대화' 메시지를 받을 시 때때로 충돌이 발생할 수 있는 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-810"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="439b4-811"><span>메모리 누수를 발생시킬 수 있는 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-811"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="439b4-812"><span>초안으로 저장할 때 보낸 사람 이름을 변경할 수 있었던 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-812"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="439b4-813">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-813">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="439b4-814">슬라이드 마스터 및 슬라이드 레이아웃에서 머리글/바닥글/슬라이드 번호 플레이스홀더에 텍스트를 붙여 넣은 후 TextRanges를 중단시킬 수 있었던 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-814">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="439b4-815">하이퍼링크를 사용하여 텍스트를 붙여넣을 때 하이퍼링크를 만들지 못하게 하였던 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-815">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="439b4-816">통계가 제대로 작동하지 않도록 하였던 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-816">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="439b4-817">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-817">Word</span></span>

- <div><span data-ttu-id="439b4-818"><span>글꼴 색이 적용되지 않았던 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-818"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="439b4-819">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-819">Office Suite</span></span>

- <div><span data-ttu-id="439b4-820">해당 기능을 사용하지 않도록 설정한 경우 버전 기록을 제공할 수 있었던 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-820">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1910-september-27"></a><span data-ttu-id="439b4-822">버전 1910: 9월 27일</span><span class="sxs-lookup"><span data-stu-id="439b4-822">Version 1910: September 27</span></span>
<span data-ttu-id="439b4-823">*버전 1910 (빌드 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-823">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)
[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)
[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="439b4-827">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-827">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-828">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-828">Excel</span></span>

- <div><span data-ttu-id="439b4-829"><span>시리즈 컬렉션을 변경할 때 분산형 차트가 제대로 렌더링되지 않을 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-829"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="439b4-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-830">Outlook</span></span>

- <div><span data-ttu-id="439b4-831"><span>공유 일정 폴더와 상호 작용하는 경우에 사용 권한 오류가 보고될 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-831"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="439b4-832"><span>사용자가 일정에 첨부 파일을 추가하지 못하도록 하는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-832"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="439b4-833"><span>디지털 서명된 메시지에 회신할 때 오류 메시지가 표시되는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-833"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="439b4-834">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-834">Word</span></span>

- <div><span data-ttu-id="439b4-835"><span>Deskjet 프린터로 인쇄할 때 배율 문제가 발생할 수 있는 문제를 해결 했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-835"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="439b4-836">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-836">Office Suite</span></span>

- <div><span data-ttu-id="439b4-837"><span>보통 굵기의 텍스트에 잘못된 스타일이 적용되는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-837"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="439b4-838"><span>보류 중인 업로드가 있는 파일을 닫으면 사용자에게 잘못된 오류 메시지가 나타날 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-838"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1910-september-20"></a><span data-ttu-id="439b4-840">버전 1910: 9월 20일</span><span class="sxs-lookup"><span data-stu-id="439b4-840">Version 1910: September 20</span></span>
<span data-ttu-id="439b4-841">*버전 1910 (빌드 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-841">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="439b4-845">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-845">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-846">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-846">Excel</span></span>

- <div><span data-ttu-id="439b4-847"><span>Excel을 시작 시 가끔 중단이 되는 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-847"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="439b4-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-848">Outlook</span></span>

- <div><span data-ttu-id="439b4-849"><span>사용할 수 있는 회의실 수가 많은 경우 회의실 선택 성능을 크게 개선하였습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-849"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="439b4-850"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Office 365에서 최신 인증으로 마이그레이션할 때 Outlook에 여러 메일함이 있는 고객의 메일함 동기화를 방지할 수 있는 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-850"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="439b4-851"><span>드롭다운 메뉴에 서명 레이블의 일부 문자가 표시되지 않는 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-851"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="439b4-852">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-852">Project</span></span>

- <div><span data-ttu-id="439b4-853"><span>엔터프라이즈 리소스를 로컬 리소스로 바꿀 때 충돌이 발생하는 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-853"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="439b4-854">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-854">Word</span></span>

- <div><span data-ttu-id="439b4-855"><span>초안 보기에서 동기식 스크롤링이 제대로 작동하지 않는 문제를 수정했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-855"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="439b4-856">처음으로 문서를 저장한 후 도구 조언이 제대로 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-856">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1910-september-13"></a><span data-ttu-id="439b4-858">버전 1910: 9월 13일</span><span class="sxs-lookup"><span data-stu-id="439b4-858">Version 1910: September 13</span></span>
<span data-ttu-id="439b4-859">*버전 1910 (빌드 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-859">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="439b4-861">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-861">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-862">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-862">Excel</span></span>

- <div><span data-ttu-id="439b4-863"><span>사용자가 일부 보호 시트에 하이퍼링크를 붙여넣지 못하는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-863"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="439b4-864">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-864">Outlook</span></span>

- <div><span data-ttu-id="439b4-865"><span>간단한 보기에서 UI가 정지되는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-865"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="439b4-866">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-866">PowerPoint</span></span>

- <div><span data-ttu-id="439b4-867"><span>사용자가 PDF로 인쇄할 때 오류가 발생하는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-867"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="439b4-868">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-868">Project</span></span>

- <div><span data-ttu-id="439b4-869"><span>보호된 작업을 사용하도록 설정한 경우 요약 작업의 작업 값을 변경하면 충돌이 발생하는 <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">문제가 해결되었습니다.</span></span></span><span class="sxs-lookup"><span data-stu-id="439b4-869"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="439b4-870"><font size=2 style="background-color:rgb(255, 255, 255);">이벤트를 엔터프라이즈 일정과 동기화할 수 없는 문제가 해결되었습니다.</font></span><span class="sxs-lookup"><span data-stu-id="439b4-870"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="439b4-871">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-871">Office Suite</span></span>

- <div><span data-ttu-id="439b4-872"><span>파일의 로컬 버전을 삭제하라는 경고가 반복되는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-872"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1910-september-06"></a><span data-ttu-id="439b4-874">버전 1910: 9월 6일</span><span class="sxs-lookup"><span data-stu-id="439b4-874">Version 1910: September 06</span></span>
<span data-ttu-id="439b4-875">*버전 1910(빌드 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="439b4-875">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-877">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-877">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-878">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-878">Excel</span></span>

- <span data-ttu-id="439b4-879">**준비, 설정, 그리기:** Surface 펜을 들어 그리기를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-879">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="439b4-880">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-880">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="439b4-881">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-881">PowerPoint</span></span>

- <span data-ttu-id="439b4-882">**준비, 설정, 그리기:** Surface 펜을 들어 그리기를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-882">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="439b4-883">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-883">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="439b4-884">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-884">Word</span></span>

- <span data-ttu-id="439b4-885">**준비, 설정, 그리기:** Surface 펜을 들어 그리기를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-885">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="439b4-886">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-886">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="439b4-889">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-889">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-890">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-890">Excel</span></span>

- <div><span data-ttu-id="439b4-891"><span>리본에 있는 글꼴 이름이 사용중인 글꼴과 다를 수 있는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-891"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="439b4-892">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-892">Outlook</span></span>

- <div><span data-ttu-id="439b4-893"><span>Internet Explorer에서 제한된 사이트에 대해 보호 모드가 해제된 경우 Outlook에서 부적절한 리소스 소비가 발생할 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-893"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="439b4-894"><span>ANSI 원본의 텍스트를 붙여넣을 때 유니코드 문자가 표시될 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-894"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="439b4-895"><span>일부 사용자가 그룹 일정 보기에서 오프라인으로 잘못 표시되는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-895"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="439b4-896">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-896">Word</span></span>

- <div><span data-ttu-id="439b4-897"><span>표 서식이 손실될 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-897"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="439b4-898"><span>Ctrl + v 단축키가 손상될 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-898"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1909-august-30"></a><span data-ttu-id="439b4-900">버전 1909: 8월 30일</span><span class="sxs-lookup"><span data-stu-id="439b4-900">Version 1909: August 30</span></span>
<span data-ttu-id="439b4-901">*버전 1909 (빌드 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="439b4-901">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="439b4-903">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-903">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="439b4-904">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-904">Access</span></span>

- <span data-ttu-id="439b4-905">**연결된 표 빠르게 찾기:** 새 검색 상자를 사용하여 연결된 표를 간편하게 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-905">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-906">PowerPoint</span></span>

- <span data-ttu-id="439b4-907">**그림을 SVG로 저장:** 이미지 품질이 손실되지 않도록 크기를 조정할 수 있는 스케일 가능한 벡터 그래픽으로 차트, 도형 또는 기타 그림을 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-907">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="439b4-908">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-908">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="non-security-updates"></a><span data-ttu-id="439b4-911">비보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-911">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="439b4-912">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-912">Excel</span></span>

- <div><span data-ttu-id="439b4-913"><span>민감도&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">에 대한 키 설명이</span> &nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">다른 키 설명과 충돌하는 문제를 해결했습니다.</span></span></span><span class="sxs-lookup"><span data-stu-id="439b4-913"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="439b4-914"><span>저장을 시도할 때 공유 통합 문서를 작업하는 동안 발생한 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-914"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="439b4-915"><span>Excel에 '\Excel\Add-in Manager' 레지스트리 값에 있는 처음 16개의 추가 기능만 나열되는 문제를 해결했습니다.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="439b4-915"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="439b4-916"><span>Frequency() 함수가 잘못된 결과를 반환하는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-916"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="439b4-917"><span>색 기준 필터링의 성능이 크게 향상되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-917"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="439b4-918"><span>마우스를 움직일 때 마우스 클릭 이벤트로 해석될 수 있는 Surface 사용자의 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-918"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="439b4-919"><span>찾기/바꾸기 대화 상자에서 키보드 탐색을 방해하는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-919"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="439b4-920"><span>일부 글꼴 이름이 제대로 표시되지 않는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-920"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="439b4-921"><span>CSV가 지원되는 파일 형식으로 표시되지 않는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-921"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="439b4-922">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-922">Access</span></span>

- <div><span data-ttu-id="439b4-923">사용자가 공유 데이터베이스를 사용하는 경우 &quot;일관성이 없는 상태&quot; 오류가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-923">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="439b4-924"><span>날짜 선택기가 표시되지 않아야 할 때 나타나는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-924"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="439b4-925">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-925">Outlook</span></span>

- <div><span data-ttu-id="439b4-926"><span>일부 POP3 사용자에게 HTML 콘텐츠가 표시되지 않는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-926"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="439b4-927"><span>기능을 사용할 수 없는 환경에서 작업할 때 연락처 카드의 오버플로 메뉴에서 기능이 없는 'Planner' 링크를 제거하는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-927"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="439b4-928">OneNote</span><span class="sxs-lookup"><span data-stu-id="439b4-928">OneNote</span></span>

- <div><span data-ttu-id="439b4-929"><span>&nbsp;OneNote 백그라운드 동기화가 때때로 포커스를 가로채는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-929"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="439b4-930">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-930">PowerPoint</span></span>

- <div><span data-ttu-id="439b4-931"><span>3D 턴테이블의 회전 방향에 영향을 주는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-931"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="439b4-932"><span>특수 문자가 포함된 경우 일부 하이퍼링크가 작동하지 않는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-932"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="439b4-933"><span>한 번에 여러 메모 창이 열리는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-933"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="439b4-934">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-934">Project</span></span>

- <div><span data-ttu-id="439b4-935"><span>Team Planner 보기를 인쇄한 후에 종종 충돌이 발생할 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-935"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="439b4-936">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-936">Word</span></span>

- <div><span data-ttu-id="439b4-937"><span>세로 텍스트 상자의 멀티 바이트 문자가 읽기용 보기에 겹쳐서 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-937">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="439b4-938"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">추가 기능 마법사에서 사용자가 작업을 수행하는 경우 일본어 우편 엽서와 인사말 카드 관련 추가 리소스를 찾지 못하는 문제를 해결했습니다.</span></span></span><span class="sxs-lookup"><span data-stu-id="439b4-938"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="439b4-939"><span>제한된 보기에서 제목 표시줄 사용자 인터페이스에 문제를 일으킬 수있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-939"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="439b4-940">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-940">Office Suite</span></span>

- <div><span data-ttu-id="439b4-941"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">일반 셰이프와 연결선 셰이프를 모두 포함하는 선택 영역에서 셰이프를 변경하면 파일 문제가 손상되는 문제를 해결했습니다.</span></span></span><span class="sxs-lookup"><span data-stu-id="439b4-941"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="439b4-942"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">여러 외부 디스플레이에서 Dock/Dock 해제를 사용할 때 문제가 발생하는 문제를 해결했습니다.</span></span></span><span class="sxs-lookup"><span data-stu-id="439b4-942"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="august-23-2019br"></a><span data-ttu-id="439b4-944">**2019년 8월 23일**</span><span class="sxs-lookup"><span data-stu-id="439b4-944">**August 23, 2019**</span></span><br/>
<span data-ttu-id="439b4-945">버전 1909 (빌드 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="439b4-945">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="439b4-946">비보안 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-946">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-947">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-947">Excel</span></span>

- <div><span data-ttu-id="439b4-948"><span>병합된 셀이 있는 열을 삭제하는 성능이 크게 개선되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-948"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="439b4-949">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-949">Office Suite</span></span>

- <div><span data-ttu-id="439b4-950"><span>브라우저에서 볼 때 일부 유니 코드 문자가 표시되지 않는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-950"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="439b4-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-951">Outlook</span></span>

- <div><span data-ttu-id="439b4-952"><span>파일을 WebDAV 위치에 저장하지 못하는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-952"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="439b4-953">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-953">PowerPoint</span></span>

- <div><span data-ttu-id="439b4-954"><span>사용자가 한 메모를 클릭하면 다른 메모가 선택되는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-954"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="439b4-955">**2019년 8월 16일**</span><span class="sxs-lookup"><span data-stu-id="439b4-955">**August 16, 2019**</span></span><br/>
<span data-ttu-id="439b4-956">버전 1909 (빌드 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="439b4-956">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="439b4-957">PowerPoint 기능 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-957">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="439b4-958">**슬라이드 번호를 유인물에 인쇄:** 슬라이드 번호가 유인물에 자동으로 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-958">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="439b4-959">계속 사용 및 해제 여부를 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-959">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="439b4-960">비보안 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-960">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-961">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-961">Excel</span></span>

- <div><span data-ttu-id="439b4-962"><span>자동 저장이 활성화 될 수 있는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-962"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="439b4-963">셀 높이가 부정확하게 측정될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-963">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="439b4-964">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-964">Office Suite</span></span>

- <div><span data-ttu-id="439b4-965"><span>댓글 기능의 성능을 크게 향상시키는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-965"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="439b4-966"><span>검색 중에 화살표 키를 사용하면 충돌이 발생하는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-966"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="439b4-967"><span>@ 기호가 특정 문자 뒤에 있으면 @멘션을 방해할 수 있는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-967"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="439b4-968"><span>@멘션을 삭제할 때 때때로 충돌이 발생할 수 있는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-968"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="439b4-969"><span>메모 카드에서 이모지가 제대로 표시되지 않도록 하는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-969"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="439b4-970"><span>때때로 충돌을 일으킬 수 있는 활성 클립보드 관련 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-970"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="439b4-971"><span>빠른 실행 도구 모음 단추가 제대로 작동하지 않을 수 있는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-971"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="439b4-972"><span>문서 서식 미리 보기가 배경으로 전환되지 않도록 하는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-972"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="439b4-973">OneNote</span><span class="sxs-lookup"><span data-stu-id="439b4-973">OneNote</span></span>

- <span data-ttu-id="439b4-974">Office 테마가 검은색으로 설정된 경우 섹션 드롭다운 목록에서 섹션 이름이 공백으로 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-974">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-975">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-975">Outlook</span></span>

- <div><span data-ttu-id="439b4-976"><span>Outlook이 반복적으로 포커스를 얻거나 저하시킬 수 있는 이벤트 보내기 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-976"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="439b4-977"><span>폴더에 회신 게시 바로 가기가 작동하지 않는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-977"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="439b4-978">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-978">PowerPoint</span></span>

- <div><span data-ttu-id="439b4-979"><span>공동 작업 시 때때로 문제를 일으킬 수 있는 제한된 보기 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-979"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="439b4-980"><span>메모 창의 작업이 제대로 표시되지 않도록 하는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-980"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="439b4-981"><span>새 슬라이드를 삽입할 때 충돌이 발생하는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-981"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="439b4-982">사용자 수명 주기</span><span class="sxs-lookup"><span data-stu-id="439b4-982">User Lifecycle</span></span>

- <div><span data-ttu-id="439b4-983"><span>때때로 구독 기능이 사라지는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-983"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="439b4-984">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-984">Word</span></span>

- <div><span data-ttu-id="439b4-985"><span>하이퍼링크에 특정 문자가 포함된 경우 하이퍼링크가 손상되는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-985"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="439b4-986"><span>해당 이미지의 설명을 볼 때 이미지 크기가 잘못될 수 있는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-986"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="439b4-987"><span>글머리 기호 목록 드롭다운 메뉴에서 때때로 충돌이 발생할 수 있는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-987"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="439b4-988">**2019년 8월 9일**</span><span class="sxs-lookup"><span data-stu-id="439b4-988">**August 09, 2019**</span></span><br/>
<span data-ttu-id="439b4-989">버전 1909 (빌드 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="439b4-989">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="439b4-990">Excel 기능 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-990">Excel Feature updates:</span></span>

- <span data-ttu-id="439b4-991">**공동 작업이 쉬워졌습니다.** 공동 작성 기능이 향상되면 조건부 서식, 셀 스타일 등을 사용하여 작업할 때 변경 내용이 공동 작업자와 원활하게 통합됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-991">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="439b4-992">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-992">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="439b4-993">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-993">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="439b4-994">Office 제품군 기능 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-994">Office Suite Feature updates:</span></span>

- <span data-ttu-id="439b4-995">**새 Office 앱 아이콘:** Office의 간단하고 강력하며 지능적인 경험을 반영하여 다시 디자인된 응용 프로그램 아이콘.</span><span class="sxs-lookup"><span data-stu-id="439b4-995">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="439b4-996">Outlook 기능 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-996">Outlook Feature updates:</span></span>

- <span data-ttu-id="439b4-997">**공격에 대비한 고급 보호:** Office 365 Advanced Threat Protection을 사용하면 전자 메일 제목, 첨부된 메시지, 서명된 메시지, 네트워크 경로 등의 하이퍼 링크를 통해 공격으로부터 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-997">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="439b4-998">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-998">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="439b4-999">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-999">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="439b4-1000">PowerPoint 기능 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-1000">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="439b4-1001">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1001">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="439b4-1002">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1002">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="439b4-1003">Word 기능 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-1003">Word Feature updates:</span></span>

- <span data-ttu-id="439b4-1004">**다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다.** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1004">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="439b4-1005">**검색하여 즐겁게 사용해 보세요.** 원하는 아이콘을 쉽게 찾을 수 있도록 검색하여 아이콘 삽입을 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1005">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="439b4-1006">그리고 선택할 때, 삽입 단추를 클릭하여 선택한 수를 알 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1006">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="439b4-1007">비보안 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-1007">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1008">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1008">Outlook</span></span>

- <div><span data-ttu-id="439b4-1009"><span>모임이 취소된 후 모임 받는 사람이 두 가지 알림을 받던 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1009"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="439b4-1010">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1010">PowerPoint</span></span>

- <div><span data-ttu-id="439b4-1011"><span>사용자가 도형 및 아이콘에 윤곽선 없음 또는 채우기 없음을 선택할 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1011"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="439b4-1012">**2019년 8월 2일**</span><span class="sxs-lookup"><span data-stu-id="439b4-1012">**August 02, 2019**</span></span><br/>
<span data-ttu-id="439b4-1013">버전 1908 (빌드 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="439b4-1013">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="439b4-1014">Excel 기능 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-1014">Excel Feature updates:</span></span>

- <span data-ttu-id="439b4-1015">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1015">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="439b4-1016">**문서에 민감도 레이블 적용:** 조직의 정보 보호 정책을 항상 준수하기 위해 파일과 전자 메일에 민감도 레이블을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1016">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="439b4-1017">Outlook 기능 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-1017">Outlook Feature updates:</span></span>

- <span data-ttu-id="439b4-1018">**문서에 민감도 레이블 적용:** 조직의 정보 보호 정책을 항상 준수하기 위해 파일과 전자 메일에 민감도 레이블을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1018">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="439b4-1019">PowerPoint 기능 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-1019">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="439b4-1020">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1020">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="439b4-1021">**문서에 민감도 레이블 적용:** 조직의 정보 보호 정책을 항상 준수하기 위해 파일과 전자 메일에 민감도 레이블을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1021">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="439b4-1022">Word 기능 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-1022">Word Feature updates:</span></span>

- <span data-ttu-id="439b4-1023">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1023">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="439b4-1024">**다른 방식으로 말하기:** 다르게 표현하는 경우 재작성은 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1024">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="439b4-1025">재작성은 표현을 기교있게 만들어주는 대안을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1025">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="439b4-1026">**문서에 민감도 레이블 적용:** 조직의 정보 보호 정책을 항상 준수하기 위해 파일과 전자 메일에 민감도 레이블을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1026">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="439b4-1027">비보안 업데이트:</span><span class="sxs-lookup"><span data-stu-id="439b4-1027">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1028">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1028">Access</span></span>
- <span data-ttu-id="439b4-1029">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1029">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1030">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1030">Excel</span></span>

- <div><span data-ttu-id="439b4-1031"><span>PDF로 인쇄할 때 &quot;모든 레이블이 반복&quot; 적용된 것으로 표시되는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1031"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="439b4-1032">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="439b4-1032">Office Suite</span></span>

- <div><span data-ttu-id="439b4-1033"><span>사용자가 데스크톱에서 문서를 열지 못하도록 하는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1033"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="439b4-1034"><span>&quot;진행 중인 다른 설치&quot;의 잘못된 오류 메시지로 인해 업그레이드가 방지 될 수 있는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1034"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="439b4-1035"><span>보안 업데이트를 설치하면 사용자에게 오류 메시지가 표시되는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1035"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="439b4-1036"><span>커서가 사라질 수 있는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1036"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="439b4-1037"><span>홈 탭이 아니라 그리기 탭으로 사용자가 기본값을 가질 수 있는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1037"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="439b4-1038"><span>대규모 트리 보기에서 충돌이 발생할 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1038"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="439b4-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1039">Outlook</span></span>

- <div></div><span data-ttu-id="439b4-1040"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">반복되는 암호 프롬프트를 야기할 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1040"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="439b4-1041"><span>전자 메일 주소를 올바르게 쿼리하지 못하는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1041"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="439b4-1042"><span>사용자가 레거시 버전의 Outlook에서 만든 일정 항목을 열지 못하도록 하는 문제가 해결되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1042"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1043">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1043">PowerPoint</span></span>

- <div><span data-ttu-id="439b4-1044"><span>일부 애니메이션이 시작되지 않도록 할 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1044"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="439b4-1045">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1045">Project</span></span>
- <span data-ttu-id="439b4-1046">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1046">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1047">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1047">Word</span></span>

- <div><span data-ttu-id="439b4-1048"><span>댓글에 대한 회신이 순서에 맞지 않게 표시될 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1048"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="439b4-1049"><span>일부 경우에 메모가 아니라 힌트가 표시되는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1049"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="439b4-1050"><span>사용자가 새 메모를 추가하려고 할 때 수정 창이 표시될 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1050"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="439b4-1051"><span>실행 취소 드롭 다운 목록이 표시되지 않을 수 있는 문제를 해결했습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1051"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="439b4-1052"><span>메모가 추가되지 않을 수 있는 문제가 수정되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="439b4-1052"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="439b4-1053">2019년 7월 26일</span><span class="sxs-lookup"><span data-stu-id="439b4-1053">July 26, 2019</span></span>
<span data-ttu-id="439b4-1054">버전 1908 (빌드 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="439b4-1054">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1055">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1055">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="439b4-1056">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1056">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="439b4-1057">접근성 높은 PDF 만들기</span><span class="sxs-lookup"><span data-stu-id="439b4-1057">Create more accessible PDFs</span></span>

<span data-ttu-id="439b4-1058">PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1058">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1059">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1059">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="439b4-1060">모두</span><span class="sxs-lookup"><span data-stu-id="439b4-1060">All</span></span>

- <span data-ttu-id="439b4-1061">Office 업데이트 후 Office의 파일 형식 연결과 아이콘이 깨질 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1061">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1062">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1062">Word</span></span> 
- <span data-ttu-id="439b4-1063">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1063">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1064">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1064">Excel</span></span>
- <span data-ttu-id="439b4-1065">차트를 이동하면 때때로 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1065">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="439b4-1066">차트 유형을 변경한 후 차트 개체에서 통합 문서 개체를 가져오는 경우 오류가 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1066">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1067">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1067">PowerPoint</span></span>
- <span data-ttu-id="439b4-1068">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1068">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1069">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1069">Outlook</span></span>
- <span data-ttu-id="439b4-1070">간략한 리본의 비활성 컨트롤이 때때로 리본에서 회색으로 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1070">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1071">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1071">Access</span></span>
- <span data-ttu-id="439b4-1072">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1072">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1073">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1073">Project</span></span>
- <span data-ttu-id="439b4-1074">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1074">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="439b4-1075">2019년 7월 19일</span><span class="sxs-lookup"><span data-stu-id="439b4-1075">July 19, 2019</span></span>
<span data-ttu-id="439b4-1076">버전 1908 (빌드 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="439b4-1076">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1077">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1077">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1078">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1078">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="439b4-1079">Word Online에서 읽을 때 머리글자어를 의미하는 바를 알아보기</span><span class="sxs-lookup"><span data-stu-id="439b4-1079">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="439b4-1080">머리글자어를 마주치면 조직 내에서 데이터를 사용하여 정의하려고 시도합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1080">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="439b4-1081">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1081">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1082">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1082">Word</span></span> 
- <span data-ttu-id="439b4-1083">BookMarkEnd 태그가 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1083">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="439b4-1084">사용자가 특수 문자를 입력하는 동안 글꼴 선택 영역이 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1084">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="439b4-1085">새 메모 카드에 빈 회신을 유발할 수도 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1085">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="439b4-1086">전자 메일을 공유할 때 서식이 손실될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1086">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1087">Excel</span></span>
- <span data-ttu-id="439b4-1088">넓은 범위의 배열에서 종종 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1088">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="439b4-1089">필터링된 범위에서 데이터를 복사하는 성능이 크게 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1089">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="439b4-1090">파일 이름에 특수 문자가 포함된 경우 일부 파일을 열지 못하도록 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1090">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1091">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1091">PowerPoint</span></span>
- <span data-ttu-id="439b4-1092">PowerPoint에서 새로 만든 섹션에 섹션 이름이 기본적으로 선택되지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1092">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="439b4-1093">4:3 디스플레이를 사용할 때 UI를 사용하기 어려워 질 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1093">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1094">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1094">Outlook</span></span>
- <span data-ttu-id="439b4-1095">사용할 수 있는 회의실이 나열되지 않도록 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1095">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="439b4-1096">일부 POP3 사용자가 HTML 서식을 사용하지 못하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1096">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1097">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1097">Access</span></span>
- <span data-ttu-id="439b4-1098">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1098">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1099">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1099">Project</span></span>
- <span data-ttu-id="439b4-1100">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1100">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="439b4-1101">2019년 7월 12일</span><span class="sxs-lookup"><span data-stu-id="439b4-1101">July 12, 2019</span></span>
<span data-ttu-id="439b4-1102">버전 1907(빌드 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="439b4-1102">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1103">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1103">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1104">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1104">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="439b4-1105">프레젠테이션에서 잉크 리플레이 사용하기</span><span class="sxs-lookup"><span data-stu-id="439b4-1105">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="439b4-1106">PowerPoint에 잉크 리플레이 애니메이션을 적용하면 프레젠테이션을 더욱 잘 표현할 수 있고 보다 많은 정보를 전달할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1106">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1107">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1107">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1108">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1108">Word</span></span> 
- <span data-ttu-id="439b4-1109">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1109">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1110">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1110">Excel</span></span>
- <span data-ttu-id="439b4-1111">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1111">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1112">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1112">PowerPoint</span></span>
- <span data-ttu-id="439b4-1113">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1113">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1114">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1114">Outlook</span></span>
- <span data-ttu-id="439b4-1115">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1115">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1116">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1116">Access</span></span>
- <span data-ttu-id="439b4-1117">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1117">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1118">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1118">Project</span></span>
- <span data-ttu-id="439b4-1119">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1119">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="439b4-1120">2019년 7월 5일</span><span class="sxs-lookup"><span data-stu-id="439b4-1120">July 5, 2019</span></span>
<span data-ttu-id="439b4-1121">버전 1907 (빌드 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="439b4-1121">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1122">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1122">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="439b4-1123">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1123">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="439b4-1124">도형 스케치!</span><span class="sxs-lookup"><span data-stu-id="439b4-1124">Sketchy Shapes!</span></span>

<span data-ttu-id="439b4-1125">프레젠테이션 초안을 작성 중인가요?</span><span class="sxs-lookup"><span data-stu-id="439b4-1125">In the middle of drafting a presentation?</span></span> <span data-ttu-id="439b4-1126">스케치 스타일을 적용하여 아직 작업 중임을 보여줍니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1126">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="439b4-1127">이 기능을 사용하면 개체를 자유형 도형, 손으로 그린 도형으로 변환하지 않고 개인적인 손길을 담을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1127">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1128">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1128">Excel</span></span>

- <span data-ttu-id="439b4-1129">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1129">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="439b4-1130">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1130">PowerPoint</span></span>

- <span data-ttu-id="439b4-1131">**유인물의 슬라이드 번호 인쇄 설정은 보다 쉬운 액세스를 위해 인쇄 메뉴로 이동했습니다:** 유인물 레이아웃을 선택할 때 인쇄 > 인쇄 레이아웃 드롭다운에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1131">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="439b4-1132">또한 프레젠테이션마다 손쉽게 설정을 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1132">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="439b4-1133">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="439b4-1133">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="439b4-1134">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1134">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1135">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1135">Word</span></span>

- <span data-ttu-id="439b4-1136">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1136">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1137">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1137">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="439b4-1138">모두</span><span class="sxs-lookup"><span data-stu-id="439b4-1138">All</span></span>
- <span data-ttu-id="439b4-1139">리본 키 팁의 성능이 크게 향상되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1139">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="439b4-1140">'준비 중인 서비스 보기' 대화 상자가 제대로 표시되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1140">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="439b4-1141">공동인증 갤러리 팝업에서 사진이 잘못 정렬될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1141">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1142">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1142">Word</span></span> 
- <span data-ttu-id="439b4-1143">새로운 의견이 추가되지 않을 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1143">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="439b4-1144">테이블이 가끔 충돌을 일으킬 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1144">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="439b4-1145">유효하지 않은 데이터가 메일 병합 끝에 추가될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1145">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="439b4-1146">일부 LaTeX 수식이 올바르게 렌더링되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1146">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1147">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1147">Excel</span></span>
- <span data-ttu-id="439b4-1148">차트 유형을 변경하는 경우 런타임 예외가 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1148">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="439b4-1149">여러 창이 열려 있을 때 잘못된 리본이 표시될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1149">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="439b4-1150">매크로가 통합 문서의 두 번째 인스턴스를 열었을 때 오류가 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1150">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="439b4-1151">통합 문서를 열거나 만들 때 또는 통합 문서 사이를 전환할 때 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1151">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="439b4-1152">사용자가 Teams에서 Word로 작성한 PDF를 열지 못하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1152">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1153">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1153">PowerPoint</span></span>
- <span data-ttu-id="439b4-1154">PDF로 내보낼 때 차트 품질을 저하시키는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1154">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="439b4-1155">툴팁이 센터까지의 거리를 표시하지 못하게 하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1155">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1156">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1156">Outlook</span></span>
- <span data-ttu-id="439b4-1157">디스크 가득 참 오류가 표시되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1157">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="439b4-1158">모임 요청을 업데이트 할 때 첨부 파일이 중복 될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1158">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1159">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1159">Access</span></span>
- <span data-ttu-id="439b4-1160">일부 쿼리의 경우 큰 정수 값을 반환하지 못하게 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1160">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="439b4-1161">Sql textbox를 편집할 수 없게 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1161">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="439b4-1162">일부 DPI 디스플레이에서 도구 설명을 표시 하는 데 어려움이 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1162">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1163">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1163">Project</span></span>
- <span data-ttu-id="439b4-1164">새 작업에서 플래그 값을 편집할 수 없게 하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1164">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="439b4-1165">상태 업데이트로 인해 할당 및 작업에 대한 실제 시작 날짜가 잘못 설정될 수있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1165">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="439b4-1166">일부 리소스가 초과 할당되었다고 잘못 표시될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1166">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="439b4-1167">서버에 연결된 상태에 Lag이 추가되고 소수점 구분 기호가 쉼표인 경우 TaskDependencies Add 메서드가 실패할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1167">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="439b4-1168">CSOM을 통해 로컬 사용자 정의 필드 조회 테이블 값을 업데이트 하는 경우 PCS가 충돌할 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1168">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="439b4-1169">소수를 포함하는 경우 전체 작업 시간값이 잘못된 것으로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1169">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="439b4-1170">2019년 6월 28일</span><span class="sxs-lookup"><span data-stu-id="439b4-1170">June 28, 2019</span></span>
<span data-ttu-id="439b4-1171">버전 1907 (빌드 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="439b4-1171">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1172">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1172">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1173">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1173">Excel</span></span>

- <span data-ttu-id="439b4-1174">**파워 쿼리 기능 향상을 통한 신속한 코드:** 자동 완성 및 구문 색상을 사용하 여 신속하게 코드를 완성하세요.</span><span class="sxs-lookup"><span data-stu-id="439b4-1174">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="439b4-1175">함수, 열, 매개 변수를 쉽게 검색할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1175">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="439b4-1176">**유사한 열의 테이블 조인:** 가져오기 및 변환 기능(파워 쿼리)은 테이블 병합을 위해 열을 비교하는 경우 근사 텍스트 매칭 논리(퍼지 매칭)를 특징으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1176">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1177">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1177">Word</span></span>

- <span data-ttu-id="439b4-1178">**공동 작성 향상** : 공동 작성 시 신뢰도가 향상될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1178">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="439b4-1179">Word, Excel, PowerPoint 및 Visio</span><span class="sxs-lookup"><span data-stu-id="439b4-1179">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="439b4-1180">권장 문서</span><span class="sxs-lookup"><span data-stu-id="439b4-1180">Recommended Documents</span></span>

<span data-ttu-id="439b4-1181">관련 활동이 권장되는 문서를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1181">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1182">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1182">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1183">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1183">Word</span></span> 
- <span data-ttu-id="439b4-1184">일부 사용자가 .DOC 파일을 열지 못할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1184">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="439b4-1185">설명이 제대로 로드되지 않도록 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1185">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1186">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1186">Excel</span></span>
- <span data-ttu-id="439b4-1187">파워 쿼리의 성능이 향상되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1187">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1188">PowerPoint</span></span>
- <span data-ttu-id="439b4-1189">화면을 깜박이게 할 수 있는 Surface 장치에 펜을 사용하는 것과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1189">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1190">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1190">Outlook</span></span>
- <span data-ttu-id="439b4-1191">모임으로 변환할 때 약속 있음/없음 상태를 변경할 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1191">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="439b4-1192">애드혹 서식 파일을 사용하여 전자 메일을 보호하는 경우 잘못된 서식 파일 및 설명이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1192">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1193">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1193">Access</span></span>
- <span data-ttu-id="439b4-1194">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1194">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1195">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1195">Project</span></span>
- <span data-ttu-id="439b4-1196">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1196">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="439b4-1197">2019년 6월 21일</span><span class="sxs-lookup"><span data-stu-id="439b4-1197">June 21, 2019</span></span>
<span data-ttu-id="439b4-1198">버전 1907(빌드 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="439b4-1198">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1199">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1199">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1200">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1200">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="439b4-1201">Outlook 데스크톱의 검은색 테마의 어두운 모드</span><span class="sxs-lookup"><span data-stu-id="439b4-1201">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="439b4-1202">어두운 모드에서는 검은색 테마의 사용자가 전자 메일을 읽을 때 배경이 어두운 읽기 창과 전자 메일을 쓸 때 어두운 배경의 작성 경험을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1202">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="439b4-1203">읽기 창과 리본에 태양/달 토글이 있습니다. 사용자가 밝은 배경으로 메시지가 어떻게 표시되는지 미리 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1203">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1204">시작하기:</span><span class="sxs-lookup"><span data-stu-id="439b4-1204">Getting Started:</span></span>

1. <span data-ttu-id="439b4-1205">검은색 테마를 설정하면 어두운 모드가 기본적으로 켜집니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1205">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="439b4-1206">달/태양 토글(읽기 창 및 리본에서)을 사용하여 어두운 모드에서 메시지가 어떻게 보이는지 사용자가 미리 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1206">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1207">시도해 볼 시나리오</span><span class="sxs-lookup"><span data-stu-id="439b4-1207">Scenarios to Try</span></span>

1. <span data-ttu-id="439b4-1208">전자 메일을 어두운 모드로 읽습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1208">Read emails in dark mode.</span></span> <span data-ttu-id="439b4-1209">내용을 읽을 수 없는 경우 읽기 창에서 태양 토글을 사용하여 밝은 배경으로 전환합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1209">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="439b4-1210">전자 메일을 어두운 모드로 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1210">Compose emails in dark mode.</span></span> <span data-ttu-id="439b4-1211">리본에서 태양 토글을 사용하여 밝은 배경에서 메시지가 어떻게 보이는지 미리 봅니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1211">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="439b4-1212">제대로 렌더링되지 않는 전자 메일을 발견하면 OutlookDarkModeFail@service.microsoft.com에 첨부 파일로 보냅니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1212">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="439b4-1213">위치 제안 받기</span><span class="sxs-lookup"><span data-stu-id="439b4-1213">Get location suggestions</span></span>

<span data-ttu-id="439b4-1214">입력을 시작하면 Outlook이 일치하는 위치를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1214">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="439b4-1215">이는 약속과 모임을 만들 때 위치 필드에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1215">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1216">시작하기:</span><span class="sxs-lookup"><span data-stu-id="439b4-1216">Getting Started:</span></span>

- <span data-ttu-id="439b4-1217">Outlook의 O365 또는 Outlook.com 일정에서 약속 또는 모임 만들기</span><span class="sxs-lookup"><span data-stu-id="439b4-1217">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="439b4-1218">위치 필드를 클릭하고 입력을 시작합니다...</span><span class="sxs-lookup"><span data-stu-id="439b4-1218">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1219">시도해 볼 시나리오</span><span class="sxs-lookup"><span data-stu-id="439b4-1219">Scenarios to Try</span></span>

<span data-ttu-id="439b4-1220">모임에 회의실을 추가할 때 회의실 찾기 추가 기능이나 주소록을 사용하는 대신 위치 필드를 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1220">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="439b4-1221">식당, 커피숍 또는 치과의사의 사무실과 같은 공공 장소에서 물리적 위치에 있는 약속의 경우 새 선택기를 사용하여 정확한 위치를 검색해보세요.</span><span class="sxs-lookup"><span data-stu-id="439b4-1221">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="439b4-1222">이렇게 하면 Outlook Mobile에서 나갈 시간이 되면 알림을 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1222">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1223">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1223">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="439b4-1224">모두</span><span class="sxs-lookup"><span data-stu-id="439b4-1224">All</span></span>
- <span data-ttu-id="439b4-1225">오프라인에서 검색 상자를 사용할 수 있도록 유지하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1225">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1226">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1226">Word</span></span> 
- <span data-ttu-id="439b4-1227">때때로 키보드 포커스를 보기 어려운 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1227">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="439b4-1228">새 문서에 붙여 넣은 텍스트의 텍스트 정렬이 잘못될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1228">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="439b4-1229">컴퓨터가 일시 중지된 후 일부 사용자가 변경 사항을 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1229">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="439b4-1230">경우에 따라 선택한 범위가 아니라 전체 문서를 인쇄하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1230">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="439b4-1231">더 작은 디스플레이에서 메모를 읽기 어려울 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1231">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="439b4-1232">장치를 캡처할 때 충돌을 일으킬 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1232">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1233">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1233">Excel</span></span>
- <span data-ttu-id="439b4-1234">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1234">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1235">PowerPoint</span></span>
- <span data-ttu-id="439b4-1236">때때로 키보드 포커스를 보기 어려운 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1236">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1237">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1237">Outlook</span></span>
- <span data-ttu-id="439b4-1238">추가 기능을 사용하도록 설정 되어 있지 않은 상태에서 잘못 표시될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1238">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="439b4-1239">고객이 많은 경우 보유 정책을 모두 볼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1239">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1240">액세스</span><span class="sxs-lookup"><span data-stu-id="439b4-1240">Access</span></span>
- <span data-ttu-id="439b4-1241">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1241">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1242">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1242">Project</span></span>
- <span data-ttu-id="439b4-1243">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1243">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="439b4-1244">2019년 6월 14일</span><span class="sxs-lookup"><span data-stu-id="439b4-1244">June 14, 2019</span></span>
<span data-ttu-id="439b4-1245">버전 1907 (빌드 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="439b4-1245">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1246">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1246">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1247">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1247">Word</span></span> 
- <span data-ttu-id="439b4-1248">OneDrive에 저장 시 사용자가 로그인할 수 없게되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1248">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="439b4-1249">제한된 액세스 모드에서 사용자가 SharePoint 속성을 변경할 수 없게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1249">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="439b4-1250">여백을 조정할 때 머리글 및 바닥글 내용이 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1250">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="439b4-1251">웹 보기로 전환할 때 서식이 손상될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1251">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="439b4-1252">SharePoint에서 열 때 사용자 정의 필드를 사용 하지 못하게 되는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1252">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1253">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1253">Excel</span></span>
- <span data-ttu-id="439b4-1254">필터링된 세트의 행을 삭제 시 발생하는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1254">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="439b4-1255">제한된 보기에서 마우스가 간혹 깜박이는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1255">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="439b4-1256">시리즈를 삭제 시 충돌이 발생할 수 있었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1256">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="439b4-1257">일부 사용자에게는 가용하지 않은 버전 기록을 추가하기 위한 옵션이 주어지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1257">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="439b4-1258">스프레드시트 비교 도구를 사용 시 예외가 발생할 수 있던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1258">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1259">PowerPoint</span></span>
- <span data-ttu-id="439b4-1260">SharePoint로의 링크를 클릭 시 충돌이 발생할 수 있었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1260">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="439b4-1261">Surface 펜을 사용하여 입력 시 사용자를 다음 페이지로 전환할 수 있던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1261">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1262">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1262">Outlook</span></span>
- <span data-ttu-id="439b4-1263">경우에 따라 받는 이의 필드가 보통 보다 크게 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1263">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1264">액세스</span><span class="sxs-lookup"><span data-stu-id="439b4-1264">Access</span></span>
- <span data-ttu-id="439b4-1265">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1265">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1266">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1266">Project</span></span>
- <span data-ttu-id="439b4-1267">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1267">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="439b4-1268">2019년 6월 7일</span><span class="sxs-lookup"><span data-stu-id="439b4-1268">June 7, 2019</span></span>
<span data-ttu-id="439b4-1269">버전 1907 (빌드 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="439b4-1269">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1270">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1270">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1271">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1271">Word</span></span> 
- <span data-ttu-id="439b4-1272">문장의 첫 글자를 대문자로 자동 고침을 설정했을 때 Word에서 종종 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1272">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="439b4-1273">SharePoint에서 문서를 편집할 때의 성능이 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1273">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="439b4-1274">Adobe Illustrator에서 만든 벡터 기반 이미지가 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1274">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1275">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1275">Excel</span></span>
- <span data-ttu-id="439b4-1276">매크로가 기록될 때 정렬 필드가 제대로 설정 되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1276">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="439b4-1277">배열 수식을 다시 계산하는 동안 멈춤 또는 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1277">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1278">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1278">PowerPoint</span></span>
- <span data-ttu-id="439b4-1279">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1279">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1280">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1280">Outlook</span></span>
- <span data-ttu-id="439b4-1281">인라인 첨부 파일의 크기가 잘못 조정되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1281">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1282">액세스</span><span class="sxs-lookup"><span data-stu-id="439b4-1282">Access</span></span>
- <span data-ttu-id="439b4-1283">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1283">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1284">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1284">Project</span></span>
- <span data-ttu-id="439b4-1285">일정 기간의 작업표에서 과제 완료 날짜가 간혹 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1285">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="439b4-1286">이전 버전에서 프로젝트를 열 때 완료율 값이 잘못될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1286">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="439b4-1287">2019년 5월 31일</span><span class="sxs-lookup"><span data-stu-id="439b4-1287">May 31, 2019</span></span>
<span data-ttu-id="439b4-1288">버전 1906 (빌드 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="439b4-1288">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1289">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1289">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1290">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1290">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="439b4-1291">현재 고객 지원팀에 문의하기 위한 대화 상자는 도킹할 수 있으며 오른쪽에 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1291">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="439b4-1292">고객 지원팀에 문의하는데 사용되는 대화 상자가 이제 오른쪽 창에 표시되고 도킹된 창으로 시작 됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1292">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="439b4-1293">이메일에서 잉크로 표시하세요!</span><span class="sxs-lookup"><span data-stu-id="439b4-1293">Ink in Your Email!</span></span>

<span data-ttu-id="439b4-1294">이제 Outlook 전자 메일에 그림을 그리고 주석을 달 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1294">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1295">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1295">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="439b4-1296">Word로 문서 링크 열기</span><span class="sxs-lookup"><span data-stu-id="439b4-1296">Open document links in Word</span></span>

<span data-ttu-id="439b4-1297">Office에서 문서 링크를 클릭 시 기본 설정을 업데이트하여 Word 앱에서 기본적으로 열리도록 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1297">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="439b4-1298">기본 설정을 업데이트하려면 파일 ->옵션->고급->링크 처리로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1298">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="439b4-1299">자세한 정보: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="439b4-1299">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1300">시작하기:</span><span class="sxs-lookup"><span data-stu-id="439b4-1300">Getting Started:</span></span>

<span data-ttu-id="439b4-1301">기능은 기본적으로 해제됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1301">Feature will default to off.</span></span> <span data-ttu-id="439b4-1302">사용자는 옵션->고급->링크 처리 설정으로 이동하거나 Win32 WXP 앱이 옵트인 경험을 가능하게할 시 옵트인하여 기능을 켤 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1302">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="439b4-1303">사용자가 Outlook/Word/PowerPoint/Excel에서 비즈니스/Sharepoint용 OneDrive/OneDrive에저장된 Word/PowerPoint/Excel 파일로의 링크를 클릭하는 경우 기본적으로 브라우저가 아닌 해당 Office 응용 프로그램에서 링크가 열립니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1303">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="439b4-1304">이 기본 설정을 변경하려면 사용자는 Outlook/Word/Excel/PowerPoint에서 다음의 설정을 업데이트하면 됩니다:</span><span class="sxs-lookup"><span data-stu-id="439b4-1304">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="439b4-1305">파일->옵션->고급->링크 처리</span><span class="sxs-lookup"><span data-stu-id="439b4-1305">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="439b4-1306">이 설정은 Outlook/Word/PowerPoint/Excel에서 공유되며 이들 앱에서 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1306">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1307">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1307">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1308">옵트인 (opt in) 경험을 사용하려면 - Outlook/Word/PowerPoint/Excel에서 OneDrive/SharePoint에 저장된 Word 문서로의 링크를 엽니다 - 30일 창에서 이 과정을 두 번 시행합니다..</span><span class="sxs-lookup"><span data-stu-id="439b4-1308">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="439b4-1309">옵트인(opt-in) 한 후에는 기본적으로 Win32 앱에서 링크를 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1309">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1310">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1310">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="439b4-1311">PowerPoint에서 프레젠테이션을 링크를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1311">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="439b4-1312">Office에서 프레젠테이션 링크를 클릭 시 기본 설정을 업데이트하여 PowerPoint 앱에서 기본적으로 열리도록 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1312">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="439b4-1313">기본 설정을 업데이트하려면 파일 ->옵션->고급->링크 처리로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1313">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="439b4-1314">자세한 정보: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="439b4-1314">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1315">시작하기:</span><span class="sxs-lookup"><span data-stu-id="439b4-1315">Getting Started:</span></span>

<span data-ttu-id="439b4-1316">기능은 기본적으로 해제됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1316">Feature will default to off.</span></span> <span data-ttu-id="439b4-1317">사용자는 옵션->고급->링크 처리 설정으로 이동하거나 Win32 WXP 앱이 옵트인 경험을 가능하게할 시 옵트인하여 기능을 켤 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1317">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="439b4-1318">사용자가 Outlook/Word/PowerPoint/Excel에서 비즈니스/Sharepoint용 OneDrive/OneDrive에저장된 Word/PowerPoint/Excel 파일로의 링크를 클릭하는 경우 기본적으로 브라우저가 아닌 해당 Office 응용 프로그램에서 링크가 열립니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1318">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="439b4-1319">이 기본 설정을 변경하려면 사용자는 Outlook/Word/Excel/PowerPoint에서 다음의 설정을 업데이트하면 됩니다:</span><span class="sxs-lookup"><span data-stu-id="439b4-1319">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="439b4-1320">파일->옵션->고급->링크 처리</span><span class="sxs-lookup"><span data-stu-id="439b4-1320">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="439b4-1321">이 설정은 Outlook/Word/PowerPoint/Excel에서 공유되며 이들 앱에서 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1321">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1322">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1322">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1323">옵트인 (opt in) 경험을 사용하려면 - Outlook/Word/PowerPoint/Excel에서 OneDrive/SharePoint에 저장된 PowerPoint 프레젠테이션으로의 링크를 엽니다 - 30일 창에서 이 과정을 두 번 시행합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1323">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="439b4-1324">옵트인(opt-in) 한 후에는 기본적으로 Win32 앱에서 링크를 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1324">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1325">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1325">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="439b4-1326">Excel에서 워크북 링크 열기</span><span class="sxs-lookup"><span data-stu-id="439b4-1326">Open workbook links in Excel</span></span>

<span data-ttu-id="439b4-1327">Office에서 워크북 링크를 클릭 시 기본 설정을 업데이트하여 Excel 앱에서 기본적으로 열리도록 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1327">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="439b4-1328">기본 설정을 업데이트하려면 파일->옵션->고급->링크 처리로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1328">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="439b4-1329">자세한 정보: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="439b4-1329">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1330">시작하기:</span><span class="sxs-lookup"><span data-stu-id="439b4-1330">Getting Started:</span></span>

<span data-ttu-id="439b4-1331">기능은 기본적으로 해제됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1331">Feature will default to off.</span></span> <span data-ttu-id="439b4-1332">사용자는 옵션->고급->링크 처리 설정으로 이동하거나 Win32 WXP 앱이 옵트인 경험을 가능하게할 시 옵트인하여 기능을 켤 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1332">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="439b4-1333">사용자가 Outlook/Word/PowerPoint/Excel에서 비즈니스/Sharepoint용 OneDrive/OneDrive에저장된 Word/PowerPoint/Excel 파일로의 링크를 클릭하는 경우 기본적으로 브라우저가 아닌 해당 Office 응용 프로그램에서 링크가 열립니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1333">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="439b4-1334">이 기본 설정을 변경하려면 사용자는 Outlook/Word/Excel/PowerPoint에서 다음의 설정을 업데이트하면 됩니다:</span><span class="sxs-lookup"><span data-stu-id="439b4-1334">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="439b4-1335">파일->옵션->고급->링크 처리</span><span class="sxs-lookup"><span data-stu-id="439b4-1335">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="439b4-1336">이 설정은 Outlook/Word/PowerPoint/Excel에서 공유되며 이들 앱에서 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1336">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1337">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1337">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1338">옵트인 (opt in) 경험을 사용하려면 - Outlook/Word/PowerPoint/Excel에서 OneDrive/SharePoint에 저장된 Excel 워크북으로의 링크를 엽니다 - 30일 창에서 이 과정을 두 번 시행합니다..</span><span class="sxs-lookup"><span data-stu-id="439b4-1338">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="439b4-1339">옵트인(opt-in) 한 후에는 기본적으로 Win32 앱에서 링크를 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1339">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1340">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1340">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="439b4-1341">모두</span><span class="sxs-lookup"><span data-stu-id="439b4-1341">All</span></span>
- <span data-ttu-id="439b4-1342">자동 저장이 비활성화된 상태에서도 파일이 간혹 자동으로 저장되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1342">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1343">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1343">Word</span></span> 
- <span data-ttu-id="439b4-1344">일부 사용자가 SharePoint에 저장하지 못하게 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1344">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1345">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1345">Excel</span></span>
- <span data-ttu-id="439b4-1346">비활성 필터에 대해 올바르지 않은 아이콘이 표시될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1346">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1347">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1347">PowerPoint</span></span>
- <span data-ttu-id="439b4-1348">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1348">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1349">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1349">Outlook</span></span>
- <span data-ttu-id="439b4-1350">일부 사용자가 그룹 일정 보기에서 오프라인으로 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1350">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="439b4-1351">SafeLink가 후행 공백이 있는 URL을 분석하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1351">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="439b4-1352">방이 비 작업시간 외에 사용가능 하도록 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1352">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1353">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1353">Access</span></span>
- <span data-ttu-id="439b4-1354">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1354">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1355">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1355">Project</span></span>
- <span data-ttu-id="439b4-1356">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1356">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="439b4-1357">2019년 5월 24일</span><span class="sxs-lookup"><span data-stu-id="439b4-1357">May 24, 2019</span></span>
<span data-ttu-id="439b4-1358">버전 1906(빌드 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="439b4-1358">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1359">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1359">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="439b4-1360">사용자 환경 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-1360">User Experience Updates</span></span>

<span data-ttu-id="439b4-1361">출시 예정이었던 업데이트가 이제 시행되었으며, 이는 간소화된 리본과 폴더 창, 메시지 목록 및 읽기 창의 시각적 새로 고침 기능을 특징으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1361">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1362">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1362">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="439b4-1363">모두</span><span class="sxs-lookup"><span data-stu-id="439b4-1363">All</span></span>

- <span data-ttu-id="439b4-1364">채팅 창이 표시되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1364">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1365">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1365">Word</span></span> 
- <span data-ttu-id="439b4-1366">경우에 따라 Word에서 문법적 오류로 인해 텍스트가 잘못 강조될 수있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1366">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1367">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1367">Excel</span></span>
- <span data-ttu-id="439b4-1368">차트 요소에 올바르지 않은 아이콘이 사용되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1368">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="439b4-1369">동일한 통합 문서가 이미 열려 있는 경우 VBA 스크립트에서 잘못 된 통합 문서를 활성화할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1369">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1370">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1370">PowerPoint</span></span>
- <span data-ttu-id="439b4-1371">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1371">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1372">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1372">Outlook</span></span>
- <span data-ttu-id="439b4-1373">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1373">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1374">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1374">Access</span></span>
- <span data-ttu-id="439b4-1375">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1375">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1376">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1376">Project</span></span>
- <span data-ttu-id="439b4-1377">작업 표시줄로 전환한 후 프로젝트가 중단될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1377">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="439b4-1378">2019년 5월 17일</span><span class="sxs-lookup"><span data-stu-id="439b4-1378">May 17, 2019</span></span>
<span data-ttu-id="439b4-1379">버전 1906(빌드 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="439b4-1379">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1380">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1380">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1381">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1381">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="439b4-1382">사용자 환경 업데이트</span><span class="sxs-lookup"><span data-stu-id="439b4-1382">User Experience Updates</span></span>

<span data-ttu-id="439b4-1383">출시 예정이었던 업데이트가 이제 시행되었으며, 이는 간소화된 리본과 폴더 창, 메시지 목록 및 읽기 창의 시각적 새로 고침 기능을 특징으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1383">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1384">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1384">Getting Started:</span></span>

<span data-ttu-id="439b4-1385">이러한 변경 사항은 새로운 기본 UI의 일부가됩니다. 12월 중순 이래로 출시 예정 스위치 뒤에 숨겨진 상태였지만 100% prod가 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1385">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="439b4-1386">사용자 지정이 가능한 간소화된 리본</span><span class="sxs-lookup"><span data-stu-id="439b4-1386">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="439b4-1387">클래식 및 요약 보기 간의 간편한 전환 및 명령 고정/고정 해제가 쉽도록 사용자 지정 가능</span><span class="sxs-lookup"><span data-stu-id="439b4-1387">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1388">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1388">Getting Started:</span></span>

<span data-ttu-id="439b4-1389">사용자는 출시 예정(초기 설정)을 켜고 리본의 갈매기 모양을 클릭해 클래식 멀티 라인 리본과 새로운 단순 싱글 라인 리본 사이를 전환하여 간소화된 리본을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1389">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1390">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1390">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1391">클래식 리본에서 간단한 리본으로 전환</span><span class="sxs-lookup"><span data-stu-id="439b4-1391">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="439b4-1392">즐겨찾기 선택 작업</span><span class="sxs-lookup"><span data-stu-id="439b4-1392">Pick your favorite action</span></span>

<span data-ttu-id="439b4-1393">플래그를 사용하지 않고 삭제?</span><span class="sxs-lookup"><span data-stu-id="439b4-1393">Don't use Flag and Delete?</span></span> <span data-ttu-id="439b4-1394">[보관] 또는 [읽은 상태로 표시]는 어떤가요?</span><span class="sxs-lookup"><span data-stu-id="439b4-1394">How about Archive or Mark as Read?</span></span> <span data-ttu-id="439b4-1395">가장 많이 사용하는 명령으로 빠른 작업 메뉴를 사용자 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1395">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1396">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1396">Getting Started:</span></span>

<span data-ttu-id="439b4-1397">빠른 작업을 선택하려면 메시지 목록의 이메일을 마우스 오른쪽 버튼으로 클릭하여 상황에 맞는 메뉴를 불러 오십시오.</span><span class="sxs-lookup"><span data-stu-id="439b4-1397">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="439b4-1398">그런 다음 "빠른 작업 설정..."을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1398">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1399">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1399">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1400">기본값을 플래그에서 변경하고 보관으로 삭제, 이동, 읽은 상태로 표시하거나 메시지 목록을 더 깔끔하게 하기 위해 모두 없앱니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1400">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="439b4-1401">넓은 레이아웃 아니면 더 좁은 레이아웃?</span><span class="sxs-lookup"><span data-stu-id="439b4-1401">Relaxed or tighter layout?</span></span> <span data-ttu-id="439b4-1402">선택</span><span class="sxs-lookup"><span data-stu-id="439b4-1402">You choose</span></span>

<span data-ttu-id="439b4-1403">더 좁은 간격을 사용하면 항목 간에 더 넓은 공백을 할지 또는 더 좁은 레이아웃을 사용하여 더 많은 항목을 표시할지를 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1403">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1404">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1404">Getting Started:</span></span>

<span data-ttu-id="439b4-1405">보기 탭, 촘촘한 간격 사용 확인란 - 기본 리본의 메시지 그룹, 단순 리본의 현재보기 설정</span><span class="sxs-lookup"><span data-stu-id="439b4-1405">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1406">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1406">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1407">Outlook을 사용하여 설정을 사용하거나 사용하지 않고 전자 메일을 분류하고 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1407">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="439b4-1408">간격을 좁게 사용하면 페이지당 메시지가 더 많이 표시되고 작성 양식의 컨트롤이 보다 간소화됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1408">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="439b4-1409">Onedrive 동기화 클라이언트를 사용할 때 MRU 항목 중복 제거</span><span class="sxs-lookup"><span data-stu-id="439b4-1409">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="439b4-1410">mru 항목을 제거하고 동기화된 데이터에 대한 복사 동작으로 보다 신속하게 연결할 수 있도록 하여 클라우드 첨부가 포함된 onedrive 동기화 클라이언트와보다 잘 통합됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1410">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1411">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1411">Getting Started:</span></span>

<span data-ttu-id="439b4-1412">OneDrive 동기화 클라이언트를 사용하면 첨부 파일 MRU에서 중복 된 파일이 더 이상 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1412">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1413">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1413">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1414">OneDrive 동기화 클라이언트 사용 및 Outlook 데스크톱의 파일 첨부 메뉴 사용</span><span class="sxs-lookup"><span data-stu-id="439b4-1414">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="439b4-1415">여러 폴더가 있는 사서함에 대한 공유 폴더 동기화 기능 향상</span><span class="sxs-lookup"><span data-stu-id="439b4-1415">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="439b4-1416">수년 동안 Outlook은 공유 사서함을 동기화할 때 폴더 수를 최대 500개로 제한해 왔습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1416">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="439b4-1417">이 변경을 통해 Outlook은 이 500개 폴더 제한이 더 이상 적용되지 않도록 동기화 방식을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1417">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1418">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1418">Getting Started:</span></span>

<span data-ttu-id="439b4-1419">사서함에 1000 폴더를 만들고, 다른 사용자에 게 사서함에 대 한 액세스 권한을 부여 하 고, "다른 사용자"를 위한 Outlook 프로필을 만들고, 동기화가 작동 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1419">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1420">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1420">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="439b4-1421">조금만 지우기</span><span class="sxs-lookup"><span data-stu-id="439b4-1421">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1422">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1422">Getting Started:</span></span>

<span data-ttu-id="439b4-1423">그리기 탭으로 이동하십시오. 지우개 드롭 다운을 선택하십시오.</span><span class="sxs-lookup"><span data-stu-id="439b4-1423">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="439b4-1424">작은 지우개 또는 중간 지우개를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1424">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1425">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1425">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1426">그리기 탭으로 이동하 고 펜을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1426">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="439b4-1427">잉크 스트로크를 그립니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1427">Draw an ink stroke.</span></span> <span data-ttu-id="439b4-1428">지우개 드롭다운을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1428">Select the Eraser dropdown.</span></span> <span data-ttu-id="439b4-1429">작은 지우개 또는 중간 지우개를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1429">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="439b4-1430">잉크 스트로크를 조금만 지웁니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1430">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1431">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1431">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="439b4-1432">모두</span><span class="sxs-lookup"><span data-stu-id="439b4-1432">All</span></span> 
- <span data-ttu-id="439b4-1433">일부 사용자가 PDF를 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1433">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="439b4-1434">사용자가 32 비트 시스템에서 대용량 파일을 저장하는 데 영향을 줄 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1434">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1435">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1435">Word</span></span> 
- <span data-ttu-id="439b4-1436">받아쓰기 기능의 응답성을 크게 향상 시켰습니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1436">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1437">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1437">Excel</span></span>
- <span data-ttu-id="439b4-1438">터치 스크린 장치에서 두 번 클릭 이벤트가 실패 할 수 있는 문제가 수정되었습니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1438">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="439b4-1439">일부 사용자가 VBA 매크로를 편집하지 못할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1439">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="439b4-1440">슬라이스를 사용할 때 성능에 영향을 줄 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1440">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1441">PowerPoint</span></span>
- <span data-ttu-id="439b4-1442">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1442">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1443">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1443">Outlook</span></span>
- <span data-ttu-id="439b4-1444">선택한 항목에서 잘못된 서식 파일을 표시할 수 있는 문제가 수정되었습니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1444">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1445">액세스</span><span class="sxs-lookup"><span data-stu-id="439b4-1445">Access</span></span>
- <span data-ttu-id="439b4-1446">확대/축소 빌더를 사용하여 긴 서식 있는 텍스트를 표시하면 읽기가 어려워지는 문제를 해결했습니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1446">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1447">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1447">Project</span></span>
- <span data-ttu-id="439b4-1448">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1448">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="439b4-1449">2019년 5월 10일</span><span class="sxs-lookup"><span data-stu-id="439b4-1449">May 10, 2019</span></span>
<span data-ttu-id="439b4-1450">버전 1906(빌드 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="439b4-1450">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1451">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1451">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1452">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1452">Outlook</span></span>

<span data-ttu-id="439b4-1453">**화면에 더 많은 메시지 맞춤:** 메시지 사이의 간격을 조정하려면 보기 > 더 좁은 간격 사용을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1453">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1454">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1454">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="439b4-1455">모두</span><span class="sxs-lookup"><span data-stu-id="439b4-1455">All</span></span>
- <span data-ttu-id="439b4-1456">다른 이름으로 저장 대화 상자에서 잘못된 경로를 표시할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1456">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1457">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1457">Word</span></span> 
- <span data-ttu-id="439b4-1458">텍스트를 입력하세요의 일부 선택 항목이 삽입되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1458">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1459">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1459">Excel</span></span>
- <span data-ttu-id="439b4-1460">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1460">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1461">PowerPoint</span></span>
- <span data-ttu-id="439b4-1462">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1462">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1463">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1463">Outlook</span></span>
- <span data-ttu-id="439b4-1464">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1464">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1465">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1465">Access</span></span>
- <span data-ttu-id="439b4-1466">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1466">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1467">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1467">Project</span></span>
- <span data-ttu-id="439b4-1468">작업 ID에서 강조 표시가 필요할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1468">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="439b4-1469">2019년 5월 3일</span><span class="sxs-lookup"><span data-stu-id="439b4-1469">May 3, 2019</span></span>
<span data-ttu-id="439b4-1470">버전 1906(빌드 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="439b4-1470">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1471">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1471">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1472">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1472">Outlook</span></span>

<span data-ttu-id="439b4-1473">**모든 암호화 옵션을 한 곳에서 확인:** 전자 메일 메시지 보호 방법을 선택하려면 옵션 > 암호화로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1473">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1474">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1474">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="439b4-1475">모두</span><span class="sxs-lookup"><span data-stu-id="439b4-1475">All</span></span>
- <span data-ttu-id="439b4-1476">일부 사용자를 대상으로 비즈니스용 OneDrive 동기화 중에 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1476">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1477">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1477">Word</span></span> 
- <span data-ttu-id="439b4-1478">특정한 경우 Word를 시작하는 데 오랜 시간이 걸리는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1478">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1479">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1479">Excel</span></span>
- <span data-ttu-id="439b4-1480">최신 버전 Excel로 업그레이드한 후 통합 문서에서 가끔 외부 링크가 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1480">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="439b4-1481">일부 사용자를 대상으로 새 통합 문서에서 셀을 선택할 때 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1481">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1482">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1482">PowerPoint</span></span>
- <span data-ttu-id="439b4-1483">드로잉을 텍스트로 변환할 때 글꼴 크기가 일정하지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1483">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1484">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1484">Outlook</span></span>
- <span data-ttu-id="439b4-1485">.VCF 파일에서 연락처를 저장하면 빈 필드가 생길 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1485">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="439b4-1486">전송되었음에도 불구하고 메시지가 보낼 편지함 폴더에 쌓일 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1486">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="439b4-1487">DRM 메시지를 볼 때 Outlook이 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1487">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1488">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1488">Access</span></span>
- <span data-ttu-id="439b4-1489">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1489">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1490">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1490">Project</span></span>
- <span data-ttu-id="439b4-1491">편집기가 중국어에서 영어로 전환되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1491">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="439b4-1492">게시되지 않은 작업이 게시된 마스터 프로젝트 사본에 표시될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1492">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="439b4-1493">2019년 4월 26일</span><span class="sxs-lookup"><span data-stu-id="439b4-1493">April 26, 2019</span></span>
<span data-ttu-id="439b4-1494">버전 1905(빌드 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="439b4-1494">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="439b4-1495">새로운 기능</span><span class="sxs-lookup"><span data-stu-id="439b4-1495">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1496">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1496">Outlook</span></span>

<span data-ttu-id="439b4-1497">**공유 일정 업데이트 속도 향상:** Office 365의 공유 일정의 경우 Outlook에서 REST API를 사용하여 해당 일정을 업데이트할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1497">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="439b4-1498">미리 보기를 설정하여 공유 일정에 보다 빠르고 신뢰할 수 있는 업데이트를 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1498">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1499">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1499">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="439b4-1500">공동 작성 개선</span><span class="sxs-lookup"><span data-stu-id="439b4-1500">Coauthoring improvements</span></span>

<span data-ttu-id="439b4-1501">실시간으로 다른 사용자가 콘텐츠 변경 내용을 받을 수 있도록 하여 더 높은 공동 작성 환경을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1501">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="439b4-1502">Visio</span><span class="sxs-lookup"><span data-stu-id="439b4-1502">Visio</span></span>

- <span data-ttu-id="439b4-1503">**Power BI에서 Visio 시각적 개체 내보내기** Power BI 보고서를 PDF, PowerPoint 파일 등으로 내보낼 때 Power BI용 Visio 시각적 개체가 올바르게 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1503">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1504">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1504">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1505">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1505">Word</span></span> 
- <span data-ttu-id="439b4-1506">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1506">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1507">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1507">Excel</span></span>
- <span data-ttu-id="439b4-1508">해 찾기 매크로가 실행에 실패하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1508">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="439b4-1509">Excel 파일를 SharePoint로 가져오지 못하게 하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1509">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1510">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1510">PowerPoint</span></span>
- <span data-ttu-id="439b4-1511">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1511">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1512">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1512">Outlook</span></span>
- <span data-ttu-id="439b4-1513">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1513">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1514">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1514">Access</span></span>
- <span data-ttu-id="439b4-1515">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1515">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1516">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1516">Project</span></span>
- <span data-ttu-id="439b4-1517">다양한 성능 및 안정성 수정 사항</span><span class="sxs-lookup"><span data-stu-id="439b4-1517">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="439b4-1518">2019년 4월 19일</span><span class="sxs-lookup"><span data-stu-id="439b4-1518">April 19, 2019</span></span>
<span data-ttu-id="439b4-1519">버전 1905 (빌드 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="439b4-1519">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1520">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1520">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1521">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1521">Outlook</span></span>

<span data-ttu-id="439b4-1522">**사람을 검색할 때 전자 메일 제안 받기:** 검색 상자에 사람의 이름을 입력하면 가장 관련성이 높은 전자 메일 메시지가 검색 제안에 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1522">**Get email suggestions when you search for a person:** When you type a person's name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1523">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1523">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="439b4-1524">데이터 형식을 사용하여 등치 지역도 개선</span><span class="sxs-lookup"><span data-stu-id="439b4-1524">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="439b4-1525">이 기능은 Excel의 지리 데이터 형식을 사용하여 등치 지역도 차트를 그리는 사용자에게 유용한 개선 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1525">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="439b4-1526">기능과 최종 사용자가 매핑하고자 하는 지역의 정확성의 통합성을 향상하는 이점을 최종 사용자에게 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1526">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="439b4-1527">추가적인 이점은 도시 폴리곤을 매핑할 수 있다는 점입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1527">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="439b4-1528">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1528">Getting Started:</span></span>

- <span data-ttu-id="439b4-1529">이 기능은 Excel의 기존 기능을 개선한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1529">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="439b4-1530">개선 사항을 사용하려면 위치를 서식이 있는 엔티티로 변환하고 등치 지역도를 사용해 그립니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1530">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1531">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1531">Scenarios to Try:</span></span>

- <span data-ttu-id="439b4-1532">사용자는 국가, 시/도, 시/군/구 및 우편 번호를 매핑할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1532">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="439b4-1533">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1533">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="439b4-1534">모든 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="439b4-1534">All Applications</span></span>
- <span data-ttu-id="439b4-1535">응용 프로그램을 시작할 때마다 첫 번째 실행 대화 상자가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1535">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="439b4-1536">"다른 이름으로 저장" 대화 상자에서 SharePoint 링크가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1536">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="439b4-1537">사용자에게 "지금 복구" 대화 상자가 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1537">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1538">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1538">Word</span></span> 
- <span data-ttu-id="439b4-1539">일부 사용자가 글꼴을 요청할 때 메모리 또는 디스크 공간 부족에 대한 오류가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1539">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="439b4-1540">메모 창에서 전환할 때 창 포커스를 잃는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1540">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1541">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1541">Excel</span></span>
- <span data-ttu-id="439b4-1542">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1542">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1543">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1543">PowerPoint</span></span>
- <span data-ttu-id="439b4-1544">브랜드 셰이프 크기를 조정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1544">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="439b4-1545">제한된 보기 모드에서 파일을 열 때 PowerPoint에서 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1545">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1546">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1546">Outlook</span></span>
- <span data-ttu-id="439b4-1547">일부 사용자가 중국어 단어를 선택하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1547">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="439b4-1548">만료 날짜가 올바르게 계산되지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1548">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1549">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1549">Access</span></span>
- <span data-ttu-id="439b4-1550">일부 사용자가 매크로 작성기를 사용하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1550">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="439b4-1551">보고서를 인쇄할 때 첫 페이지만 인쇄하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1551">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="439b4-1552">하이퍼 링크를 마우스로 가리킬 때 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1552">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="439b4-1553">관계 보기를 사용하는 경우 일부 항목이 화면에 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1553">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1554">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1554">Project</span></span>
- <span data-ttu-id="439b4-1555">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1555">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="439b4-1556">2019년 4월 12일</span><span class="sxs-lookup"><span data-stu-id="439b4-1556">April 12, 2019</span></span>
<span data-ttu-id="439b4-1557">버전 1905 (빌드 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="439b4-1557">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1558">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1558">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1559">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1559">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="439b4-1560">Microsoft Graph를 활용하여 스마트해지기</span><span class="sxs-lookup"><span data-stu-id="439b4-1560">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="439b4-1561">지능형 데이터를 가져오거나 링크하고, 지능형 기술을 이용하여 데스크톱 데이터베이스를 다시 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1561">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1562">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1562">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="439b4-1563">모든 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="439b4-1563">All Applications</span></span>
 - <span data-ttu-id="439b4-1564">일부 사용자가 클라우드 위치에 파일을 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1564">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="439b4-1565">잘못된 창이 리본에서 열릴 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1565">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1566">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1566">Word</span></span> 
- <span data-ttu-id="439b4-1567">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1567">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1568">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1568">Excel</span></span>
- <span data-ttu-id="439b4-1569">통합 문서에 연결된 데이터 유형이 없을 때 연결된 데이터 유형에 대한 오류 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1569">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="439b4-1570">로컬에서 또는 온라인에서 볼 때 Word 문서 내 URL 링크가 변경될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1570">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1571">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1571">PowerPoint</span></span>
- <span data-ttu-id="439b4-1572">애니메이션 탭에서 변경 사항을 취소한 후 응용 프로그램이 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1572">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1573">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1573">Outlook</span></span>
- <span data-ttu-id="439b4-1574">일부 사용자가 공용 폴더에서 연락처에 대한 메모 필드를 수정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1574">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="439b4-1575">만료 날짜와 삭제 날짜 간에 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1575">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1576">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1576">Access</span></span>
- <span data-ttu-id="439b4-1577">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1577">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1578">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1578">Project</span></span>
- <span data-ttu-id="439b4-1579">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1579">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="439b4-1580">2019년 4월 5일</span><span class="sxs-lookup"><span data-stu-id="439b4-1580">April 5, 2019</span></span>
<span data-ttu-id="439b4-1581">버전 1904(빌드 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="439b4-1581">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1582">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1582">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1583">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1583">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="439b4-1584">Windows 용 Outlook: 중요 받은 편지함 설정 지정 및 공유</span><span class="sxs-lookup"><span data-stu-id="439b4-1584">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="439b4-1585">중요 받은 편지함 기본 설정은 클라우드에 저장되므로, 임의 컴퓨터에서 Windows용 Outlook 및 웹용 Outlook을 사용할 때 일관된 경험을 즐길 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1585">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1586">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1586">Getting Started:</span></span>

<span data-ttu-id="439b4-1587">파일 > 옵션 > 일반 탭에 새로운 ‘클라우드에 내 Outlook 설정 저장’ 기본 설정이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1587">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="439b4-1588">다른 Desktop Outlook 설치 및 OWA로 로밍하려면 사용자가 중요 받은 편지함 설정을 사용으로 지정하는 상자를 선택해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1588">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1589">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1589">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1590">클라우드 설정 기본 설정이 켜져 있는 컴퓨터에서 중요 받은 편지함을 변경하십시오.</span><span class="sxs-lookup"><span data-stu-id="439b4-1590">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="439b4-1591">OWA로 이동하여 거기에 적용된 환경 설정을 확인하십시오.</span><span class="sxs-lookup"><span data-stu-id="439b4-1591">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="439b4-1592">OWA에서 중요 받은 편지함을 변경하고 데스크톱 Outlook을 시작하여 환경 설정이 반영되었는지 확인하십시오.</span><span class="sxs-lookup"><span data-stu-id="439b4-1592">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1593">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1593">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="439b4-1594">학습 도구 모드는 더 많은 페이지 색상을 지원합니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1594">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="439b4-1595">Word 학습 도구는 페이지 테마 색을 추가로 지원하므로 페이지의 배경색을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1595">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="439b4-1596">많은 사람들이 흑백 또는 검정색 배경으로 읽는 것에 어려움을 느끼고 있으므로 PC 및 Mac의 Word에서 색상 선택을 확장했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1596">Many people have challenges reading with an all-white or all-black background, so we've expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1597">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1597">Getting Started:</span></span>

<span data-ttu-id="439b4-1598">이 기능을 사용하려면보기 탭으로 이동하여 학습 도구와 페이지 색상을 차례로 선택하십시오.</span><span class="sxs-lookup"><span data-stu-id="439b4-1598">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1599">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1599">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1600">이 기능을 사용하려면보기 탭으로 이동하여 학습 도구와 페이지 색상을 차례로 선택하십시오.</span><span class="sxs-lookup"><span data-stu-id="439b4-1600">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1601">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1601">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="439b4-1602">애니메이션 3D 모델로 독창성 높이기</span><span class="sxs-lookup"><span data-stu-id="439b4-1602">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="439b4-1603">이제 Office에서 애니메이션 모델을 지원하므로 편집기에서 재생되므로 시트를 실제로 사용할 수 있습니다!</span><span class="sxs-lookup"><span data-stu-id="439b4-1603">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1604">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1604">Getting Started:</span></span>

1. <span data-ttu-id="439b4-1605">Excel을 엽니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1605">Open Excel</span></span>
2. <span data-ttu-id="439b4-1606">애니메이션 모델을 삽입하십시오(곧 Remix로 변경되지만, 현재는 여기에서 애니메이션 모델에 액세스하십시오.\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="439b4-1606">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="439b4-1607">애니메이션 모델이 편집기에서 재생됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1607">The animated model will play in the editor!</span></span> <span data-ttu-id="439b4-1608">슬라이드 쇼 모드를 확인하십시오 - 거기에서도 재생됩니다!</span><span class="sxs-lookup"><span data-stu-id="439b4-1608">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="439b4-1609">3D 형식 리본에서 모델의 더 많은 애니메이션 장면 탐색</span><span class="sxs-lookup"><span data-stu-id="439b4-1609">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1610">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1610">Scenarios to Try:</span></span>

1. <span data-ttu-id="439b4-1611">애니메이션 모델을 삽입하고 편집기에서 재생되는 것을 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1611">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="439b4-1612">장면 갤러리(3차원 서식 리본에서 사용 가능)를 통해 애니메이션 모델에서 사용할 수 있는 애니메이션 장면을 탐색합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1612">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="439b4-1613">리본, floatie 또는 스페이스 바를 사용하여 애니메이션을 간편하게 재생하고 일시 중지합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1613">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1614">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1614">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="439b4-1615">모든 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="439b4-1615">All Applications</span></span>
- <span data-ttu-id="439b4-1616">상황에 맞는 메뉴에서 Excel에 대해 잘못된 앱 아이콘이 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1616">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="439b4-1617">업데이트를 설치한 후 파일 메뉴 단추가 사라지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1617">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="439b4-1618">사용자 라이선스를 변경할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1618">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1619">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1619">Word</span></span> 
- <span data-ttu-id="439b4-1620">특정 줌 레벨에서 텍스트가 올바르게 렌더링되지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1620">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1621">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1621">Excel</span></span>
- <span data-ttu-id="439b4-1622">편집한 후 통합 문서 저장 메시지가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1622">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="439b4-1623">사용자가 통합 문서를 공유한 경우 BeforeSave 이벤트가 트리거되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1623">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="439b4-1624">열 크기를 6픽셀 미만으로 조정하면 잘못된 오류 메시지가 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1624">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="439b4-1625">Excel에서 Application.Visible 플래그를 무시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1625">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="439b4-1626">비활성 상태의 고정된 창에 추적 화살표가 남아 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1626">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="439b4-1627">통합 문서를 열 때 날짜 및 통화에 대한 셀 서식이 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1627">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="439b4-1628">도구 설명이 예기치 않게 이동되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1628">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="439b4-1629">파워 쿼리 편집기의 지역화 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1629">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="439b4-1630">통합 문서를 전자 메일을 통해 첨부 파일로 보낼 때 통합 문서가 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1630">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1631">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1631">PowerPoint</span></span>
- <span data-ttu-id="439b4-1632">도형 복사에 예상보다 시간이 오래 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1632">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1633">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1633">Outlook</span></span>
- <span data-ttu-id="439b4-1634">그리기 도구를 사용하는 동안 Outlook이 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1634">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="439b4-1635">html 전자 메일을 작성할 때 지역화 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1635">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="439b4-1636">사용자가 아래쪽 창을 선택하기 힘든 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1636">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1637">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1637">Access</span></span>
- <span data-ttu-id="439b4-1638">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1638">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1639">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1639">Project</span></span>
- <span data-ttu-id="439b4-1640">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1640">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="439b4-1641">2019년 3월 22일</span><span class="sxs-lookup"><span data-stu-id="439b4-1641">March 22, 2019</span></span>
<span data-ttu-id="439b4-1642">버전 1904(빌드 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="439b4-1642">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="439b4-1643">새로운 기능</span><span class="sxs-lookup"><span data-stu-id="439b4-1643">New Features</span></span>

- <span data-ttu-id="439b4-1644">**개인 정보 제어:** 진단 데이터 및 연결된 환경에 대한 업데이트 및 향상된 신규 컨트롤 작업</span><span class="sxs-lookup"><span data-stu-id="439b4-1644">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="439b4-1645">자세한 정보<https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="439b4-1645">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="439b4-1646">**Office 아이콘이 새롭게 단장했습니다.** 간단하고 강력하며 지능적인 Office 환경을 반영하여 Office 아이콘이 다시 디자인되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1646">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1647">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1647">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1648">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1648">Word</span></span> 
- <span data-ttu-id="439b4-1649">UI에 지속적으로 “변경 내용을 확인하는 중”이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1649">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1650">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1650">Excel</span></span>
- <span data-ttu-id="439b4-1651">워크시트 이동 후 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1651">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="439b4-1652">PDF로 저장한 후 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1652">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="439b4-1653">저장 대화 상자에서 일부 한국어 문자를 허용하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1653">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1654">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1654">PowerPoint</span></span>
- <span data-ttu-id="439b4-1655">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1655">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1656">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1656">Outlook</span></span>
- <span data-ttu-id="439b4-1657">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1657">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1658">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1658">Access</span></span>
- <span data-ttu-id="439b4-1659">Access에서 Access로 추가 바로 가기가 만들어졌다는 오류 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1659">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="439b4-1660">연결된 SharePoint의 데이터가 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1660">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1661">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1661">Project</span></span>
- <span data-ttu-id="439b4-1662">언어 설정이 중국어에서 영어로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1662">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="439b4-1663">SharePoint와 동기화할 때 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1663">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="439b4-1664">2019년 3월 15일</span><span class="sxs-lookup"><span data-stu-id="439b4-1664">March 15, 2019</span></span>
<span data-ttu-id="439b4-1665">버전 1904(빌드 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="439b4-1665">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1666">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1666">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1667">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1667">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="439b4-1668">포커스 모드</span><span class="sxs-lookup"><span data-stu-id="439b4-1668">Focus Mode</span></span>

<span data-ttu-id="439b4-1669">보기 메뉴에서 포커스로 전환하면 주의를 산만하게 하는 요인들을 제거하고 작업에 집중할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1669">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="439b4-1670">Office 365 구독자만 해당합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1670">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1671">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1671">Getting Started:</span></span>

<span data-ttu-id="439b4-1672">보기 탭 리본 상태 막대 "포커스" 버튼의 "포커스 "버튼 </span><span class="sxs-lookup"><span data-stu-id="439b4-1672">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1673">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1673">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1674">포커스 모드를 시작하 고 주요 환경을 경험해 보세요.</span><span class="sxs-lookup"><span data-stu-id="439b4-1674">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1675">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1675">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1676">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1676">Word</span></span> 
- <span data-ttu-id="439b4-1677">PDF로 저장된 문서의 이미지에 잘못된 DPI가 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1677">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1678">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1678">Excel</span></span>
- <span data-ttu-id="439b4-1679">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1679">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1680">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1680">PowerPoint</span></span>
- <span data-ttu-id="439b4-1681">메모 창이 적절하게 열리거나 닫히지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1681">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="439b4-1682">비디오를 삭제할 때 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1682">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="439b4-1683">경우에 따라 응용 프로그램을 시작할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1683">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1684">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1684">Outlook</span></span>
- <span data-ttu-id="439b4-1685">일본어로 표시할 때 읽음 확인이 올바르지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1685">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1686">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1686">Access</span></span>
- <span data-ttu-id="439b4-1687">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1687">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1688">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1688">Project</span></span>
- <span data-ttu-id="439b4-1689">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1689">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="439b4-1690">2019년 3월 8일</span><span class="sxs-lookup"><span data-stu-id="439b4-1690">March 8, 2019</span></span> 
<span data-ttu-id="439b4-1691">버전 1903(빌드 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="439b4-1691">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1692">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1692">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1693">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1693">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="439b4-1694">Microsoft Search를 통해 원하는 것을 찾으십시오.</span><span class="sxs-lookup"><span data-stu-id="439b4-1694">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="439b4-1695">Microsoft Search를 사용하면 모든 파일, 작업, 사람을 찾고 작업을 수행하는 데 필요한 도움을 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1695">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1696">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1696">Getting Started:</span></span>

- <span data-ttu-id="439b4-1697">이 기능은 머리글의 UI 위에 눈에 띄도록 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1697">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1698">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1698">Scenarios to Try:</span></span>

- <span data-ttu-id="439b4-1699">대학이나 최근 문서를 검색하거나 가장 자주 사용하는 리본 명령을 검색해 보세요.</span><span class="sxs-lookup"><span data-stu-id="439b4-1699">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="439b4-1700">화제나 주제를 검색하여 더 많은 정보를 얻으세요.</span><span class="sxs-lookup"><span data-stu-id="439b4-1700">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="439b4-1701">공동 작성</span><span class="sxs-lookup"><span data-stu-id="439b4-1701">CoAuthoring</span></span>

<span data-ttu-id="439b4-1702">매크로 포함하는 문서가 잠기는게 번거롭습니까?</span><span class="sxs-lookup"><span data-stu-id="439b4-1702">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="439b4-1703">이제 비즈니스용 OneDrive의 .docm 파일을 사용하여 여러 작성자가 동시에 편집할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1703">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1704">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1704">Getting Started:</span></span>

<span data-ttu-id="439b4-1705">사용자가 이 기능에 액세스 하기 위해 UI에서 버튼을 누를 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1705">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="439b4-1706">OneDrive for Business docm 파일에서는 기본적으로 활성화되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1706">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="439b4-1707">따라서 사용자는 OneDrive for Business에 docm 파일을 저장하여 사용해 봐야 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1707">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1708">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1708">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1709">OneDrive for Business에 docm 파일을 만들고 동료와 공유하고 공동 작업해 보십시오!</span><span class="sxs-lookup"><span data-stu-id="439b4-1709">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1710">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1710">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1711">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1711">Word</span></span> 
- <span data-ttu-id="439b4-1712">Options에서 ‘ESC’를 누를 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1712">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="439b4-1713">메모에 회신할 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1713">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="439b4-1714">Word에서 PowerPoint Online으로 복사 및 붙여넣기를 할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1714">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1715">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1715">Excel</span></span>
- <span data-ttu-id="439b4-1716">보호되고 편집 가능한 문서를 열었을 때 Excel에서 셀을 복사하는 경우 높은 CPU 사용량을 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1716">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1717">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1717">PowerPoint</span></span>
- <span data-ttu-id="439b4-1718">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1718">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1719">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1719">Outlook</span></span>
- <span data-ttu-id="439b4-1720">Outlook Search가 선택한 연대순 정렬을 반영하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1720">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="439b4-1721">"이 작업 열기" 워크플로우 리본 버튼이 특정 이메일에 응답하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1721">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="439b4-1722">사용자가 회의실 찾기를 통해 사용 가능한 회의실을 선택한 후 Outlook이 사내 회의실을 지우지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1722">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1723">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1723">Access</span></span>
- <span data-ttu-id="439b4-1724">어두운 테마에서 흰색 배경에 흰색 텍스트가 있던 저장된 가져오기/내보내기 대화 상자의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1724">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="439b4-1725">테이블 디자인에서 사용자가 표시 컨트롤 속성의 Yes/No 필드를 Textbox로 설정하지 못했던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1725">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1726">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1726">Project</span></span>
- <span data-ttu-id="439b4-1727">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1727">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="439b4-1728">2019년 3월 1일</span><span class="sxs-lookup"><span data-stu-id="439b4-1728">March 1, 2019</span></span> 
<span data-ttu-id="439b4-1729">버전 1903(빌드 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="439b4-1729">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1730">새로운 기능</span><span class="sxs-lookup"><span data-stu-id="439b4-1730">What's New</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1731">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1731">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="439b4-1732">동기화 중 변경 내용 추적, 메모, 실시간 공동 작업을 표시하는 색상</span><span class="sxs-lookup"><span data-stu-id="439b4-1732">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="439b4-1733">이제 제품의 개선을 통해 공동 작업자의 메모, 변경 내용 추적 및 커서를 동일한 색상으로 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1733">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1734">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1734">Getting Started:</span></span>

<span data-ttu-id="439b4-1735">다른 사용자가 연 SharePoint 또는 OneDrive문서를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1735">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="439b4-1736">사용자의 변경 내용 추적과 해당 사용자 커서의 색이 일치 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1736">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1737">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1737">Scenarios to Try:</span></span>

<span data-ttu-id="439b4-1738">다른 사용자가 연 SharePoint 또는 OneDrive문서를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1738">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="439b4-1739">사용자의 변경 내용 추적과 해당 사용자 커서의 색이 일치 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1739">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1740">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1740">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1741">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1741">Word</span></span> 
- <span data-ttu-id="439b4-1742">Options에서 ‘ESC’를 누를 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1742">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="439b4-1743">Word에서 PowerPoint Online으로 복사 및 붙여넣기를 할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1743">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1744">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1744">Excel</span></span>
- <span data-ttu-id="439b4-1745">보호되고 편집 가능한 문서를 열었을 때 Excel에서 셀을 복사하는 경우 높은 CPU 사용량을 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1745">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1746">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1746">PowerPoint</span></span>
- <span data-ttu-id="439b4-1747">PowerPoint에서 @Mentions를 사용 시의 슬라이드 이미지 크기 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1747">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1748">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1748">Outlook</span></span>
- <span data-ttu-id="439b4-1749">Outlook Search가 선택한 연대순 정렬을 반영하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1749">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="439b4-1750">"이 작업 열기" 워크플로우 리본 버튼이 특정 이메일에 응답하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1750">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="439b4-1751">사용자가 회의실 찾기를 통해 사용 가능한 회의실을 선택한 후 Outlook이 사내 회의실을 지우지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1751">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1752">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1752">Access</span></span>
- <span data-ttu-id="439b4-1753">데이터 전송 발신기와 테이블의 재연결을 확인 시 표시되는 프롬프트 텍스트를 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1753">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="439b4-1754">어두운 테마에서 흰색 배경에 흰색 텍스트가 있던 저장된 가져오기/내보내기 대화 상자의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1754">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="439b4-1755">테이블 디자인에서 사용자가 표시 컨트롤 속성의 Yes/No 필드를 Textbox로 설정하지 못했던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1755">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1756">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1756">Project</span></span>
- <span data-ttu-id="439b4-1757">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1757">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="439b4-1758">2019년 2월 15일</span><span class="sxs-lookup"><span data-stu-id="439b4-1758">February 15, 2019</span></span> 
<span data-ttu-id="439b4-1759">버전 1903(빌드 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="439b4-1759">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="439b4-1760">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="439b4-1760">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1761">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1761">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="439b4-1762">모핑 전환 개선 사항 - 이름으로 모핑</span><span class="sxs-lookup"><span data-stu-id="439b4-1762">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="439b4-1763">모핑하려는 도형 지정</span><span class="sxs-lookup"><span data-stu-id="439b4-1763">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1764">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1764">Getting Started:</span></span>

- <span data-ttu-id="439b4-1765">두 개체를 같은 개체로 처리하도록 모핑을 사용하기 위해 사용자는 선택 창을 사용하여 도형 이름을 바꿀 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1765">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="439b4-1766">이름은 “!!”로 시작해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1766">The name must be prefaced with "!!"</span></span> <span data-ttu-id="439b4-1767">모핑에서 이름을 사용하여 기본 일치 동작을 무시하도록 하려면, 예를 들어 “!!이름”</span><span class="sxs-lookup"><span data-stu-id="439b4-1767">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. "!!Name"</span></span>
- <span data-ttu-id="439b4-1768">사용자는 계속 “!!”로 시작하지 않는 셰이프 이름을 바꿀 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1768">Users can continue to rename shapes with any name that doesn't start with "!!"</span></span> <span data-ttu-id="439b4-1769">모핑 작동 방식의 변경에 대해 우려할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1769">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1770">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1770">Scenarios to Try:</span></span>

- <span data-ttu-id="439b4-1771">슬라이드에 도형을 삽입합니다. 직사각형을 가정해 보겠습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1771">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="439b4-1772">새 슬라이드를 만듭니다 
</span><span class="sxs-lookup"><span data-stu-id="439b4-1772">Create a new slide</span></span>
- <span data-ttu-id="439b4-1773">두 번째 슬라이드에 다른 도형을 삽입합니다. 삼각형을 가정해 보겠습니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1773">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="439b4-1774">SelectionPane을 열고, 슬라이드 1에서 직사각형을 "!!도형"으로 이름을 바꾸고, 슬라이드 2에서 삼각형을 “!!도형”으로 이름을 바꿉니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1774">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="439b4-1775">두 번째 슬라이드에 모핑 적용</span><span class="sxs-lookup"><span data-stu-id="439b4-1775">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="439b4-1776">모핑 전환 개선 사항 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="439b4-1776">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="439b4-1777">더 원활한 전환으로 SmartArt 모핑</span><span class="sxs-lookup"><span data-stu-id="439b4-1777">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1778">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1778">Getting Started:</span></span>

<span data-ttu-id="439b4-1779">SmartArt를 사용하는 것과 같은 방법으로 모핑 사용</span><span class="sxs-lookup"><span data-stu-id="439b4-1779">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1780">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1780">Scenarios to Try:</span></span>

- <span data-ttu-id="439b4-1781">슬라이드에 SmartArt 삽입</span><span class="sxs-lookup"><span data-stu-id="439b4-1781">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="439b4-1782">슬라이드를 복제합니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1782">Duplicate the Slide</span></span>
- <span data-ttu-id="439b4-1783">복제된 슬라이드에서 SmartArt를 크기 조정/변경/이동합니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1783">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="439b4-1784">복제된 슬라이드에서 모핑 적용</span><span class="sxs-lookup"><span data-stu-id="439b4-1784">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="439b4-1785">모핑 전환 개선 사항 - 표</span><span class="sxs-lookup"><span data-stu-id="439b4-1785">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="439b4-1786">더 원활한 전환으로 표 모핑</span><span class="sxs-lookup"><span data-stu-id="439b4-1786">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="439b4-1787">시작:</span><span class="sxs-lookup"><span data-stu-id="439b4-1787">Getting Started:</span></span>
<span data-ttu-id="439b4-1788">표를 사용하는 것과 같은 방법으로 모핑 사용</span><span class="sxs-lookup"><span data-stu-id="439b4-1788">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1789">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1789">Scenarios to Try:</span></span>

- <span data-ttu-id="439b4-1790">슬라이드에서 표 추가</span><span class="sxs-lookup"><span data-stu-id="439b4-1790">Insert a Table in a slide</span></span>
- <span data-ttu-id="439b4-1791">슬라이드를 복제합니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1791">Duplicate the slide</span></span>
- <span data-ttu-id="439b4-1792">복제된 슬라이드에서 Table을 크기 조정/변경/이동합니다</span><span class="sxs-lookup"><span data-stu-id="439b4-1792">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="439b4-1793">복제된 슬라이드에서 모핑 적용</span><span class="sxs-lookup"><span data-stu-id="439b4-1793">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="439b4-1794">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher 및 Visio</span><span class="sxs-lookup"><span data-stu-id="439b4-1794">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="439b4-1795">원활한 계정 전환</span><span class="sxs-lookup"><span data-stu-id="439b4-1795">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="439b4-1796">새 계정 관리자를 통해 사용자의 모든 회사 및 개인 계정을 한곳에서 볼 수 있으며, 사용자가 직접 여러 계정 간에 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1796">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="439b4-1797">업데이트된 환경에서는 사용자의 로그인 방법이 명확해지며, 이제 먼저 로그아웃하거나 복잡한 대화 상자를 거치지 않고 회사 및 개인 계정 사이를 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1797">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="439b4-1799">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="439b4-1799">Scenarios to Try:</span></span>
- <span data-ttu-id="439b4-1800">계정 간 전환</span><span class="sxs-lookup"><span data-stu-id="439b4-1800">Switch between accounts</span></span>
- <span data-ttu-id="439b4-1801">새 계정 추가 [참고: 먼저 파일 | 계정 | 연결된 서비스에 가서 회사 계정에 연결된 개인 서비스를 제거 또는 그 반대로 하고자 할 수 있습니다]</span><span class="sxs-lookup"><span data-stu-id="439b4-1801">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="439b4-1802">계정에서 로그아웃</span><span class="sxs-lookup"><span data-stu-id="439b4-1802">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="439b4-1803">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1803">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1804">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1804">Word</span></span> 
- <span data-ttu-id="439b4-1805">표 및 이미지에 대한 상황에 맞는 미리 보기 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1805">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1806">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1806">Excel</span></span>
- <span data-ttu-id="439b4-1807">자동 필터 검색 필드의 텍스트는 검은색 테마에서 흰색인 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1807">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="439b4-1808">새 Office 추가 기능에 있는 동의 UI 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1808">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1809">PowerPoint</span></span>
- <span data-ttu-id="439b4-1810">노트북 또는 태블릿에 슬라이드 쇼를 표시할 때 자동으로 확장하는 디스플레이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1810">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1811">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1811">Outlook</span></span>
- <span data-ttu-id="439b4-1812">OneNote로 보내기 버튼 디스플레이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1812">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1813">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1813">Access</span></span>
- <span data-ttu-id="439b4-1814">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1814">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1815">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1815">Project</span></span>
- <span data-ttu-id="439b4-1816">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1816">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="439b4-1817">2019년 2월 11일</span><span class="sxs-lookup"><span data-stu-id="439b4-1817">February 11, 2019</span></span>
<span data-ttu-id="439b4-1818">버전 1903(빌드 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="439b4-1818">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="439b4-1819">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="439b4-1819">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1820">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1820">Word</span></span> 
- <span data-ttu-id="439b4-1821">일부 사용자 지정된 스타일을 Word Online에 적용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1821">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="439b4-1822">Word에서 서식 있는 개체의 컨텍스트 미리 보기 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1822">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="439b4-1823">Word에서 목록을 붙여넣으면 작동이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1823">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1824">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1824">Excel</span></span>
- <span data-ttu-id="439b4-1825">통화 기호가 없을 때 숫자 서식 뒤에 추가된 공백이 더 이상 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1825">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="439b4-1826">주식 자동 검색 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1826">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1827">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1827">PowerPoint</span></span>
- <span data-ttu-id="439b4-1828">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1828">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1829">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1829">Outlook</span></span>
- <span data-ttu-id="439b4-1830">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1830">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1831">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1831">Access</span></span>
- <span data-ttu-id="439b4-1832">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1832">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1833">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1833">Project</span></span>
- <span data-ttu-id="439b4-1834">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1834">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="439b4-1835">2019년 2월 1일</span><span class="sxs-lookup"><span data-stu-id="439b4-1835">February 1, 2019</span></span> 
<span data-ttu-id="439b4-1836">버전 1902(빌드 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="439b4-1836">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="439b4-1837">중요 수정 사항</span><span class="sxs-lookup"><span data-stu-id="439b4-1837">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="439b4-1838">Word</span><span class="sxs-lookup"><span data-stu-id="439b4-1838">Word</span></span> 
- <span data-ttu-id="439b4-1839">임베디드 Excel 테이블에서 셀 크기를 조정하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1839">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="439b4-1840">그리기 캔버스에서 도형 복사 / 붙여 넣기 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1840">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="439b4-1841">Excel</span><span class="sxs-lookup"><span data-stu-id="439b4-1841">Excel</span></span>
- <span data-ttu-id="439b4-1842">Excel 웹 응용 프로그램에서 파일을 열 때 발생하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1842">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="439b4-1843">파일 이름 크기로 인해 .XLSX가 실패하여 CSV 파일을 저장하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1843">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="439b4-1844">컨텍스트 메뉴를 수정하여 컨텍스트 메뉴 옵션을 표시했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1844">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="439b4-1845">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="439b4-1845">PowerPoint</span></span>
- <span data-ttu-id="439b4-1846">사용자가 키보드 단축키 ctrl + alt + 7 / ctrl + alt + 8을 사용하여 대괄호를 입력할 수 없는 부분을 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1846">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="439b4-1847">PPT에 로컬 비디오를 삽입하면 'C'드라이브의 디스크 공간이 줄어드는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1847">We fixed an issue where inserting a local video into the PPT would reduce the 'C' drive disk space</span></span>
- <span data-ttu-id="439b4-1848">일부 사용자에게 표시되지 않는 Microsoft Stream에 게시 버튼이 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1848">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="439b4-1849">Outlook</span><span class="sxs-lookup"><span data-stu-id="439b4-1849">Outlook</span></span>
- <span data-ttu-id="439b4-1850">일정의 작업 보기에 작업 제목이 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1850">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="439b4-1851">Access</span><span class="sxs-lookup"><span data-stu-id="439b4-1851">Access</span></span>
- <span data-ttu-id="439b4-1852">차트 관련 배율 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1852">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="439b4-1853">Project</span><span class="sxs-lookup"><span data-stu-id="439b4-1853">Project</span></span>
- <span data-ttu-id="439b4-1854">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="439b4-1854">Various performance and stability fixes</span></span>
