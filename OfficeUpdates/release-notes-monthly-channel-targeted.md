---
title: 릴리스 정보 월 단위 채널(대상 지정)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 이후 참가자 대상 그룹에게 주요 새 기능, 수정 사항 또는 알려진 문제의 최신 목록을 제공합니다.
ms.openlocfilehash: f0ae7d9c965c4ffea21e31859760ebea550ac3e7
ms.sourcegitcommit: bb2e1868f43693fe085ba9080401e6f8137c8a9e
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/27/2020
ms.locfileid: "43907892"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="ff3a3-103">Office 릴리스 정보 월 단위 채널(대상 지정)</span><span class="sxs-lookup"><span data-stu-id="ff3a3-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="ff3a3-104">이 문서는 Windows 데스크톱용 Word, Excel, PowerPoint, Outlook, Access 및 Project 의 월별 채널(대상 지정) 빌드에 대한 릴리스 정보를 포함합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="ff3a3-105">매주 Microsoft는 흥미로운 새 기능, 중요한 수정 사항, 알리고자 하는 중요한 문제를 강조합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="ff3a3-106">Microsoft는 일정 기간 동안 종종 월별 채널로(대상 지정) 기능(및 경우에 따라 수정 사항)을 출시함을 참고하십시오.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="ff3a3-107">이로서 더욱 광범위한 사용자들에게 기능을 릴리스하기 전에 원활하게 작동하는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="ff3a3-108">따라서 아래에 설명된 기능이 보이지 않더라도 곧 제공되게 되므로 걱정할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="ff3a3-109">릴리스 정보 게시 날짜는 실제 빌드 릴리스 날짜와 일치하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-109">The release notes publication date may not match the actual build release date.</span></span>


[//]: # (제거하지 마세요)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-april-25"></a><span data-ttu-id="ff3a3-113">버전 2004: 4월 25일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-113">Version 2004: April 25</span></span>
<span data-ttu-id="ff3a3-114">*버전 2004(빌드 12730.20206)* </span><span class="sxs-lookup"><span data-stu-id="ff3a3-114">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-116">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-116">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ff3a3-117">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-117">Outlook</span></span>

- <span data-ttu-id="ff3a3-118">Windows 업데이트 후 로컬로 저장된 .msg 혹은 .oft 파일을 열 때 Outlook의 작동이 중단되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-118">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="ff3a3-119">Project</span><span class="sxs-lookup"><span data-stu-id="ff3a3-119">Project</span></span>

- <span data-ttu-id="ff3a3-120">Project Web App에 연결된 Project를 사용하는 경우 소수 구분 기호가 쉼표이면 TaskDependencies Add 메서드가 종속성에 지연 시간을 추가하려할 때 실패하는 문제를 수정습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-120">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ff3a3-121">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="ff3a3-121">Office Suite</span></span>

- <span data-ttu-id="ff3a3-122">이 수정은 액세스의 제한과 동시에 파일을 암호로 보호하는 작업을 할 수 없게 하는 오류를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-122">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-april-21"></a><span data-ttu-id="ff3a3-124">버전 2004: 4월 21일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-124">Version 2004: April 21</span></span>
<span data-ttu-id="ff3a3-125">*버전 2004(빌드 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-125">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-127">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-127">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ff3a3-128">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-128">Outlook</span></span>

- <span data-ttu-id="ff3a3-129">폴더 창의 너비가 예기치 않게 변경되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-129">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="ff3a3-130">Outlook을 종료하는 동안 사용자 작업이 중지되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-130">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-april-15"></a><span data-ttu-id="ff3a3-132">버전 2004: 4월 15일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-132">Version 2004: April 15</span></span>
<span data-ttu-id="ff3a3-133">*버전 2004(빌드 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-133">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-135">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-135">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-136">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-136">Excel</span></span>

- <span data-ttu-id="ff3a3-137">**Facebook 커넥터 지원 종료:** 2020년 4월부터는 Excel에서 Facebook 커넥터를 사용하는 외부 데이터 연결을 더 이상 지원하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-137">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-138">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-138">Outlook</span></span>

- <span data-ttu-id="ff3a3-139">**Outlook에서 메일 작성 시 @멘션 제안을 사용하지 않는 새 옵션:** @멘션 선택기가 유용하기보다는 불편하게 느껴지나요?</span><span class="sxs-lookup"><span data-stu-id="ff3a3-139">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="ff3a3-140">원하는 경우 바로 지금 비활성화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-140">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-141">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-141">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-142">**발표하는 동안 변경 내용 동기화:** 프레젠테이션이 슬라이드 쇼 모드에 있더라도 내용이 변경될 때마다 동기화됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-142">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="ff3a3-143">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-143">Word</span></span>

- <span data-ttu-id="ff3a3-144">**비공개 복사본에 주석 달기:** 공유 문서의 비공개 복사본을 만들어 나만 볼 수 있는 필기 메모를 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-144">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="ff3a3-145">시작하려면 보기 > 비공개 복사본 만들기로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-145">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-148">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-148">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ff3a3-149">Access</span><span class="sxs-lookup"><span data-stu-id="ff3a3-149">Access</span></span>

- <span data-ttu-id="ff3a3-150">작업창에서 표 크기 조정 및 새로 고침과 관련된 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-150">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="ff3a3-151">Access의 다른 나라 버전이 사용자 인터페이스에서 영어 문자열을 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-151">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="ff3a3-152">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-152">Excel</span></span>

- <span data-ttu-id="ff3a3-153">시트의 셀 범위를 선택하면 하나의 셀이 선택되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-153">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="ff3a3-154">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효로 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-154">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="ff3a3-155">일부 경우에 피벗 테이블을 포함하는 시트를 복사한 후 Excel 작동이 중단되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-155">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="ff3a3-156">경우에 따라 Application.Evaluate(VBA)가 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-156">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="ff3a3-157">다양한 셀을 프로그래밍 방식으로 편집할 때 사용자에게 발생할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-157">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="ff3a3-158">일본어 환경으로 csv 파일을 열 때 발생할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-158">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="ff3a3-159">사용자 정의 차트 서식 파일을 기본값으로 삽입하면 열 차트로 저장되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-159">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="ff3a3-160">원본 데이터 셀에 캡션이 없는 경우 차트의 데이터 레이블이 빈 채로 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-160">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="ff3a3-161">일부 x축 범위를 사용하여 차트 크기를 줄일 때 Excel이 응답을 중지하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-161">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="ff3a3-162">R1C1 셀 참조를 사용 설정하고 Excel 시트를 공동 작성/공유 중일 때 사용자의 현재 상태 아이콘에 마우스를 올리면 R1C1 모드에서 셀 참조가 활성으로 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-162">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="ff3a3-163">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-163">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-164">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-164">Outlook</span></span>

- <span data-ttu-id="ff3a3-165">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-165">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="ff3a3-166">이 변경 사항은 초안 전자 메일에 대한 최신 변경 내용이 업데이트되지 않은 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-166">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="ff3a3-167">파일을 마우스 오른쪽 단추로 클릭 및 '보내기' 사용이 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-167">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="ff3a3-168">대리인이 다른 공유 사서함 컴퓨터의 다른 폴더 계층 구조를 볼 수 있었던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-168">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="ff3a3-169">가끔 전자 메일 메시지의 범주가 사라지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-169">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="ff3a3-170">컴퓨터의 표준 시간대를 변경할 때 일부 미리 알림이 발송되지 않았던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-170">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="ff3a3-171">사용자가 조직 양식의 속성을 보려고 할 때 작동 중단이 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-171">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="ff3a3-172">사용자가 주소록에 대한 검색 경로를 사용자 지정한 경우 Outlook의 이름 확인 범위가 GAL(전체 주소 목록)을 포함하지 않고 사용자 지정 경로로 제한되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-172">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="ff3a3-173">첨부 파일 도구에서 "클라우드에 저장" 단추가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-173">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="ff3a3-174">회신하는 메시지에 대한 소유자 권한이 없는 경우 검사기 창에서 디지털 권한 관리 메시지에 회신할 때 사용자가 서명을 추가할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-174">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="ff3a3-175">사용자가 웹 위치에서 이전에 만든 모임에 추가 첨부 파일을 추가할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-175">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="ff3a3-176">메일에 첨부 파일을 추가하거나 저장할 때 파일을 끌어다 놓는 방법을 사용하는 경우(메뉴를 사용하는 것과 반대로) 파일의 "최종 수정 날짜"가 업데이트되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-176">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="ff3a3-177">사용자가 검색 단추를 클릭하는 대신 상세 검색 창에서 Enter 키를 누르면 검색이 시작되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-177">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="ff3a3-178">반환된 검색 결과 집합 내에서 범주별로 결과를 정렬하면 범주 색이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-178">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="ff3a3-179">"사용 가능한 경우 사용자 사진 표시" 옵션을 사용하지 않도록 설정한 경우 검색에서 사용자에 대한 정보가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-179">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ff3a3-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-180">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-181">이 변경 내용을 적용하면 이모지가 포함된 PowerPoint 파일을 저장할 때 실패할 수 있는 오류가 수정됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-181">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="ff3a3-182">이 변경 내용을 적용하면 PowerPoint 또는 Word에 OLE 개체로 포함된 레거시 Excel 차트를 렌더링할 때 가끔 차트 제목이 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-182">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="ff3a3-183">Excel에서 PowerPoint로 텍스트를 복사하면 그 서식이 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-183">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="ff3a3-184">이 변경 내용을 적용하면 '단어 단위로' 옵션을 사용한 특수 문자 찾기가 가끔 제대로 작동하지 않았던 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-184">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="ff3a3-185">Project</span><span class="sxs-lookup"><span data-stu-id="ff3a3-185">Project</span></span>

- <span data-ttu-id="ff3a3-186">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-186">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="ff3a3-187">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-187">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="ff3a3-188">사용자가 일정 그룹 내의 작업 리본에 있는 “비활성화” 단추를 클릭하면 'ProjectBeforeTaskChange' VBA(Visual Basic Applications) 이벤트가 실행되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-188">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="ff3a3-189">양식 유형 보기 내에서 선행 작업이나 후속 작업 세부 정보를 설정한 경우 ProjectBeforeTaskChange VBA(Visual Basic for Applications) 이벤트가 변경 내용을 캡처하지 않는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-189">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="ff3a3-190">예를 들어 종속성을 삭제하고 양식에서 확인을 클릭한 경우 이벤트가 실행되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-190">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="ff3a3-191">이 동작이 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-191">This behavior has been fixed.</span></span>

- <span data-ttu-id="ff3a3-192">날짜 변경과 같이 변경 후에 ACWP (수행된 작업의 실제 비용)의 최신 값이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-192">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="ff3a3-193">MRU(최근 사용한 항목) 메뉴를 사용하여 프로젝트를 열면 프로젝트 파일이 읽기/쓰기 권한으로 열리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-193">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="ff3a3-194">이 변경 내용은 시작 날짜와 시간을 사용하여 수동 작업을 만들었지만 기간을 지정하지 않은 경우 타임라인에 잘못된 시간이 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-194">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="ff3a3-195">회교식 달력을 사용하여 타임라인을 인쇄하면 인쇄 보기에서 한 달을 건너뛰거나 중복되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-195">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="ff3a3-196">이 변경 사항은 팀 플래너에서 GDI 개체를 사용하여 작업하면 GDI 개체가 초과 할당되고 메모리가 부족해지는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-196">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="ff3a3-197">'CustomFieldValueListGetItem'이 실행되고 사용자 지정 필드에 대한 조회 테이블이 없는 경우 빈 조회 테이블이 없어도 생성되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-197">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="ff3a3-198">양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChange 이벤트가 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-198">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="ff3a3-199">실제 작업 시간을 보호하는 설정이 설정된 경우 사용자가 기간별 초기 작업 시간을 입력할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-199">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="ff3a3-200">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-200">Word</span></span>

- <span data-ttu-id="ff3a3-201">이 변경 내용을 적용하면 힌트 위에 커서를 놓아도 해당 카드가 강조 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-201">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="ff3a3-202">이 변경 내용을 적용하면 보기 메뉴에서 여러 페이지를 선택한 경우 메모 창이 공백으로 표시되는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-202">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="ff3a3-203">댓글 달기 기능을 사용할 수 없었던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-203">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="ff3a3-204">이 변경 내용을 적용하면 올가미 선택 도구를 사용할 때 그룹 지정된 도형 안의 텍스트가 일시적으로 사라지는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-204">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="ff3a3-205">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-205">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="ff3a3-206">이 변경 내용을 적용하면 PowerPoint 또는 Word에 OLE 개체로 포함된 레거시 Excel 차트를 렌더링할 때 가끔 차트 제목이 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-206">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="ff3a3-207">이 변경 사항은 계정 관리자가 메시지를 발송하지 않아 타사 애플리케이션이 중단되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-207">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="ff3a3-208">두 페이지 보기에서 댓글을 작성할 때 댓글 앵커가 가끔 보이지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-208">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="ff3a3-209">메모를 입력하거나 편집하고 Ctrl+A를 사용할 때 메모 카드 내에서 텍스트를 선택하는 대신 캔버스에서 텍스트를 선택하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-209">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="ff3a3-210">단락의 스타일이 목록에 연결된 스타일의 상위 항목인 경우 해당 목록의 번호 매기기가 분실되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-210">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="ff3a3-211">문서에 없는 제목 스타일을 사용하여 목차를 업데이트할 때 발생하는 문제도 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-211">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="ff3a3-212">빠른 인쇄를 사용하여 인쇄한 후에 편집하려고 할 때 문서의 단어 맞춤이 스크램블되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-212">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="ff3a3-213">두 개의 문서를 하나로 병합할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-213">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="ff3a3-214">문서를 보낼 때 Word 문서에 저장된 디지털 서명이 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-214">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="ff3a3-215">수식 관련 수정을 표시할 때 파일을 저장하면 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-215">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-april-14"></a><span data-ttu-id="ff3a3-217">버전 2003: 4월 14일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-217">Version 2003: April 14</span></span>
<span data-ttu-id="ff3a3-218">*버전 2003(빌드 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-218">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="ff3a3-219">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ff3a3-219">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

- <span data-ttu-id="ff3a3-221">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-221">Various bugs and performance fixes.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-april-09"></a><span data-ttu-id="ff3a3-223">버전 2003: 4월 9일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-223">Version 2003: April 09</span></span>
<span data-ttu-id="ff3a3-224">*버전 2003(빌드 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-224">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-226">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-226">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-227">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-227">Excel</span></span>

- <span data-ttu-id="ff3a3-228">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="ff3a3-228">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ff3a3-229">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ff3a3-229">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-230">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-230">Outlook</span></span>

- <span data-ttu-id="ff3a3-231">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="ff3a3-231">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ff3a3-232">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ff3a3-232">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-233">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-233">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-234">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="ff3a3-234">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ff3a3-235">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ff3a3-235">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="ff3a3-236">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-236">Word</span></span>

- <span data-ttu-id="ff3a3-237">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="ff3a3-237">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="ff3a3-238">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="ff3a3-238">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)




[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-april-03"></a><span data-ttu-id="ff3a3-242">버전 2003: 4월 3일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-242">Version 2003: April 03</span></span>
<span data-ttu-id="ff3a3-243">*버전 2003(빌드 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-243">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-245">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-245">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-246">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-246">Excel</span></span>

- <span data-ttu-id="ff3a3-247">VBA의 Application.Evaluate 사용이 경우에 따라 사용자 정의 함수에서 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-247">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-248">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-248">Outlook</span></span>

- <span data-ttu-id="ff3a3-249">마우스에서 "X" 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-249">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="ff3a3-250">Project</span><span class="sxs-lookup"><span data-stu-id="ff3a3-250">Project</span></span>

- <span data-ttu-id="ff3a3-251">양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChangeevent가 발생합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-251">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="ff3a3-252">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-252">Word</span></span>

- <span data-ttu-id="ff3a3-253">마우스에서 "X" 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-253">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-march-31"></a><span data-ttu-id="ff3a3-255">버전 2003: 3월 31일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-255">Version 2003: March 31</span></span>
<span data-ttu-id="ff3a3-256">*버전 2003 (빌드 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-256">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-258">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-258">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ff3a3-259">Access</span><span class="sxs-lookup"><span data-stu-id="ff3a3-259">Access</span></span>

- <span data-ttu-id="ff3a3-260">**"테이블 추가" 작업 창:** Access의 새로운 "테이블 추가" 작업 창이 마침내 나왔습니다!</span><span class="sxs-lookup"><span data-stu-id="ff3a3-260">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="ff3a3-261">이 기능을 사용하면 쿼리 및 관계 보기에 대한 "테이블 표시" 대화 상자를 탐색하지 않고도 쿼리 창에 추가하거나 제거할 테이블을 손쉽게 선택/여러 개 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-261">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="ff3a3-262">여기에는 연결된 테이블을 표시하는 새로운 "링크" 탭, 현재 목록을 필터링하는 검색 상자, "끌어다 놓기" 동작 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-262">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-265">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-265">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="ff3a3-266">Project</span><span class="sxs-lookup"><span data-stu-id="ff3a3-266">Project</span></span>

- <div><span data-ttu-id="ff3a3-267"><span style="display:inline !important;">실제 작업 시간을 보호하는 설정이 설정된 경우 사용자가 기간별 초기 작업 시간을 입력할 수 없는 문제가 수정되었습니다.</span></span><span class="sxs-lookup"><span data-stu-id="ff3a3-267"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-march-25"></a><span data-ttu-id="ff3a3-269">버전 2003: 3월 25일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-269">Version 2003: March 25</span></span>
<span data-ttu-id="ff3a3-270">*버전 2003 (빌드 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-270">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="ff3a3-271">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-271">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="ff3a3-272">버전 2003: 3월 23일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-272">Version 2003: March 23</span></span>
<span data-ttu-id="ff3a3-273">*버전 2003 (빌드 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-273">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="ff3a3-274">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-274">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="ff3a3-275">버전 2003: 3월 21일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-275">Version 2003: March 21</span></span>
<span data-ttu-id="ff3a3-276">*버전 2003 (빌드 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-276">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-278">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-278">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ff3a3-279">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-279">Outlook</span></span>

- <span data-ttu-id="ff3a3-280">**받은 편지함을 벗어나지 않고 모임 참가:** 온라인 모임에 참가하기 위해 일정으로 전환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-280">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="ff3a3-281">일정을 할 일 창에 고정하고 클릭 한 번만으로 모든 모임에 참여하세요.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-281">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="ff3a3-282">**완전히 새로워진 일정:** 지난 해, Microsoft는 새로워진 메일 환경을 제공했으며, 올해에는 일정이 새롭게 바뀌었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-282">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="ff3a3-283">업데이트가 새로 제공되지만 노련한 Outlook 사용자에게는 익숙하므로 바로 시작하여 생산성을 높일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-283">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-284">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-285">**슬라이드 쇼 중에 슬라이드 업데이트:** 프레젠테이션을 진행하는 동안 다른 작성자가 변경한 슬라이드를 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-285">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-march-16"></a><span data-ttu-id="ff3a3-287">버전 2003: 3월 16일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-287">Version 2003: March 16</span></span>
<span data-ttu-id="ff3a3-288">*버전 2003 (빌드 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-288">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-290">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-290">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-291">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-291">Excel</span></span>

- <span data-ttu-id="ff3a3-292">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-292">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-293">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-293">Outlook</span></span>

- <span data-ttu-id="ff3a3-294">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-294">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-295">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-295">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-296">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-296">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="ff3a3-297">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-297">Word</span></span>

- <span data-ttu-id="ff3a3-298">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-298">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ff3a3-299">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="ff3a3-299">Office Suite</span></span>

- <span data-ttu-id="ff3a3-300">**탭 창:** 이제 앱의 오른쪽에 있는 탭 UI를 사용하여 여러 창 간에 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-300">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="ff3a3-301">UI는 2개 이상의 창이 열려있는 경우에만 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-301">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-304">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-304">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-305">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-305">Excel</span></span>

- <span data-ttu-id="ff3a3-306">원본 주소록이 닫힌 경우 외부 링크가 채우기에 업데이트되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-306">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-307">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-307">Outlook</span></span>

- <span data-ttu-id="ff3a3-308">사용자가 종료 후 작업 관리자에 남아 있는 Outlook 프로세스를 보게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-308">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-march-10"></a><span data-ttu-id="ff3a3-310">버전 2003: 3월 10일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-310">Version 2003: March 10</span></span>
<span data-ttu-id="ff3a3-311">*버전 2003(빌드 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-311">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="ff3a3-312">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ff3a3-312">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)
### <a name="feature-updates"></a><span data-ttu-id="ff3a3-314">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-314">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-315">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-315">Excel</span></span>
- <span data-ttu-id="ff3a3-316">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-316">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="ff3a3-317">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-317">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-318">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-318">PowerPoint</span></span>
- <span data-ttu-id="ff3a3-319">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-319">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="ff3a3-320">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-320">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="ff3a3-321">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-321">Word</span></span>
- <span data-ttu-id="ff3a3-322">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-322">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="ff3a3-323">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-323">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-324">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-324">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-325">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-325">Excel</span></span>

- <span data-ttu-id="ff3a3-326">File \ Options 대화 상자의 '확인' 단추가 회색으로 표시되고 기능에는 영향을 미치지 않는 외관상의 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-326">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="ff3a3-327">피벗 테이블 측정의 이름을 바꿀 때 사용자가 겪을 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-327">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="ff3a3-328">인쇄 미리 보기에서 슬라이서의 텍스트 크기가 제대로 조정되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-328">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="ff3a3-329">VBA 매크로를 사용하여 범위의 내용을 지우면 사용자가 경험할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-329">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="ff3a3-330">사용자가 리본과 상호 작용하는 매크로를 실행할 때 UI가 깜박이는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-330">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="ff3a3-331">파일의 첫 단어가 TABLE 인 경우 CSV 파일이 잘못 로드되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-331">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="ff3a3-332">확대/축소 수준이 다른 두 통합 문서 간에 전환할 때 사용자가 충돌을 경험할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-332">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="ff3a3-333">CUBEVALUE 함수가 때때로 잘못된 결과를 반환하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-333">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="ff3a3-334">이번 변경으로 추가 기능에서 noSelect 잠금을 사용하는 도형이 포함된 문서/통합 문서의 호스트 항목을 요청하는 경우 발생하는 앱(Excel, Word)의 잠재적인 충돌 및 개체 모델의 런타임 오류가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-334">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="ff3a3-335">설정을 동기화하는 경우 Outlook 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-335">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="ff3a3-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-336">Outlook</span></span>

- <span data-ttu-id="ff3a3-337">Outlook Web Access로 규칙을 만들 때 Exchange 서버에 유지되지 않아 충돌이 발생하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-337">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="ff3a3-338">설정을 동기화하는 경우 Outlook 사용자에게 충돌이 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-338">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="ff3a3-339">어두운 모드의 Outlook에서 '보낸 사람:' 입력란에 드롭다운 목록이 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-339">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="ff3a3-340">로깅이 꺼져 있어도 일부 시나리오에서 Outlook이 예기치 않게 로깅 출력을 생성하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-340">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="ff3a3-341">Outlook이 밤새 실행 중인 상태에서 사용자가 공용 폴더 메시지를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-341">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="ff3a3-342">Gmail 계정 추가의 인증 작업 과정에서 권한 페이지의 '허용' 및 '거부' 버튼이 비활성화되는 경합 상태를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-342">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="ff3a3-343">사용자가 &quot;약속 있음/없음 옵션&quot; 일정 권한 대화 상자에 액세스하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-343">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="ff3a3-344">다른 시간대에서 보낸 되풀이 모임 인스턴스를 열 때 &quot;죄송합니다. 이 항목을 여는 데 문제가 있습니다&quot;라는 경고가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-344">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="ff3a3-345">해당 메시지에서 첨부 파일을 끌어서 놓은 후 사용자가 .msg 파일을 다시 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-345">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="ff3a3-346">첨부 파일 이름에 괄호가 포함된 경우 Outlook에서 OneDrive로 파일 첨부 파일을 업로드한 후 파일 이름이 변경될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-346">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="ff3a3-347">사용자가 다른 응용 프로그램에서 파일을 열 때 파일 탐색기를 통해 파일을 전자 메일 메시지에 첨부할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-347">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="ff3a3-348">설정을 동기화하는 경우 Outlook 사용자에게 충돌이 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-348">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-349">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-349">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-350">축소판 그림 위로 마우스를 가져가면 권장 축소판 그림이 깜박이는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-350">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="ff3a3-351">경우에 따라 PowerPoint가 중단될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-351">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="ff3a3-352">File \ Options 대화 상자의 '확인' 단추가 회색으로 표시되고 기능에는 영향을 미치지 않는 외관상의 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-352">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="ff3a3-353">Excel 차트가 포함된 PowerPoint 또는 Word에서 문서를 저장하지 못하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-353">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="ff3a3-354">Project</span><span class="sxs-lookup"><span data-stu-id="ff3a3-354">Project</span></span>

- <span data-ttu-id="ff3a3-355">작업이 완료됨으로 표시된 후 작업 완료율이 100%보다 낮은 값으로 잘못 변경되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-355">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="ff3a3-356">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-356">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="ff3a3-357">요약 작업 날짜가 가끔 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-357">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="ff3a3-358">Visio</span><span class="sxs-lookup"><span data-stu-id="ff3a3-358">Visio</span></span>

- <span data-ttu-id="ff3a3-359">Visio 데스크톱에서 연 파일의 경우, 셰이프 정보 창에서 셰이프 데이터 구역에 일관성이 없는 세부 정보가 표시되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-359">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="ff3a3-360">이제 이 문제가 해결었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-360">It has now been fixed.</span></span>

- <span data-ttu-id="ff3a3-361">몇 가지 보안 검사로 인해 2016 이전 버전에서 가져온 비트맵이 렌더링되지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-361">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="ff3a3-362">Visio 구독에서 이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-362">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="ff3a3-363">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-363">Word</span></span>

- <span data-ttu-id="ff3a3-364">마우스 포인터가 주석 카드 위로 마우스를 가져갈 때 주석 카드가 항상 강조 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-364">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="ff3a3-365">메모 카드를 탭할 때 메모 편집 상자에 포커스가 표시되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-365">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="ff3a3-366">File \ Options 대화 상자의 '확인' 단추가 회색으로 표시되고 기능에는 영향을 미치지 않는 외관상의 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-366">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="ff3a3-367">문서 공동 작성 세션 중에 주석 카드에 직접 이미지를 추가하면 태그가 추가될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-367">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="ff3a3-368">이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-368">This issue has been fixed.</span></span>

- <span data-ttu-id="ff3a3-369">수식에 텍스트 콘텐츠 컨트롤과 같은 컨트롤을 삽입한 다음 파일을 저장하고 열면 읽을 수 없는 콘텐츠 오류가 발생합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-369">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="ff3a3-370">이전에 암호로 보호된 파일을 클라우드 저장소에 저장하지 못하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-370">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="ff3a3-371">편집에 대해 보호된 문서의 비교 기능 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-371">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="ff3a3-372">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="ff3a3-372">Office Suite</span></span>

- <span data-ttu-id="ff3a3-373">Word/Excel/PowerPoint 문서와 함께 Multichoice/ Lookup/Managed-metadata 속성을 사용하고 SharePoint 문서 라이브러리에 저장할 때, 이러한 속성은 이전에 255 자로 제한되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-373">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="ff3a3-374">이러한 속성이 255자를 초과하면 해당 문서를 저장할 수 없었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-374">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="ff3a3-375">이 변경으로 이 제한이 2048자로 늘었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-375">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="ff3a3-376">Word/Excel/PowerPoint에서 UPN(사용자 계정 이름)이 더 이상 대소문자를 구분하지 않아 SharePoint에서 파일 작업시 오류가 줄어듭니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-376">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="ff3a3-377">동일한 SharePoint 라이브러리의 Word/Excel/PowerPoint에서 여러 문서를 열 때 첫 번째로 열린 문서만 정책 준수에 대한 검사가 이뤄지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-377">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-march-05"></a><span data-ttu-id="ff3a3-379">버전 2002: 3월 5일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-379">Version 2002: March 05</span></span>
<span data-ttu-id="ff3a3-380">*버전 2002 (빌드 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-380">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="ff3a3-381">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-381">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="ff3a3-382">버전 2002: 3월 4일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-382">Version 2002: March 04</span></span>
<span data-ttu-id="ff3a3-383">*버전 2002 (빌드 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-383">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-385">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-385">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="ff3a3-386">Project</span><span class="sxs-lookup"><span data-stu-id="ff3a3-386">Project</span></span>
- <div><span data-ttu-id="ff3a3-387">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-387">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="ff3a3-388">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="ff3a3-388">Office Suite</span></span>
- <div><span data-ttu-id="ff3a3-389">동일한 SharePoint 라이브러리의 Word/Excel/PowerPoint에서 여러 문서를 열 때 첫 번째로 열린 문서만 정책 준수에 대한 검사가 이뤄지는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-389">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-march-01"></a><span data-ttu-id="ff3a3-391">버전 2002: 3월 1일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-391">Version 2002: March 01</span></span>
<span data-ttu-id="ff3a3-392">*버전 2002 (빌드 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-392">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-393">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-393">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ff3a3-394">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-394">Outlook</span></span>

- <div><span data-ttu-id="ff3a3-395">타사 응용 프로그램에서 전자 메일을 보낼 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-395">Addresses an issue that caused third party applications to be unable to send email.</span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-february-24"></a><span data-ttu-id="ff3a3-397">버전 2002: 2월 24일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-397">Version 2002: February 24</span></span>
<span data-ttu-id="ff3a3-398">*버전 2002 (빌드 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-398">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="ff3a3-399">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-399">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="ff3a3-400">버전 2002: 2월 22일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-400">Version 2002: February 22</span></span>
<span data-ttu-id="ff3a3-401">*버전 2002 (빌드 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-401">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="ff3a3-402">다양한 버그 및 성능 수정 사항.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-402">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="ff3a3-403">버전 2002: 2월 21일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-403">Version 2002: February 21</span></span>
<span data-ttu-id="ff3a3-404">*버전 2002(빌드 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-404">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-406">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-406">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ff3a3-407">Access</span><span class="sxs-lookup"><span data-stu-id="ff3a3-407">Access</span></span>

- <span data-ttu-id="ff3a3-408">**Query Designer, SQL 보기 및 관계 창에서 생산성을 향상시킬 수 있습니다.** 테이블을 마우스 오른쪽 단추로 클릭하여 열고 디자인하고 크기를 조정하고 숨겨보세요.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-408">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="ff3a3-409">SQL 보기에서 텍스트를 검색하고 바꾸세요.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-409">Search and replace text in SQL View.</span></span> <span data-ttu-id="ff3a3-410">관계 창에서 테이블을 여러 개 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-410">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-411">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-411">Outlook</span></span>

- <span data-ttu-id="ff3a3-412">\*\*종속적인 Wi-Fi 네트워크에 대한 새로운 경험: \*\* 로그인하기 위해 웹 페이지가 필요한 Wi-Fi 네트워크에 가입한 적이 있습니까?</span><span class="sxs-lookup"><span data-stu-id="ff3a3-412">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="ff3a3-413">이제 Outlook이 이를 감지하여 연결하는 데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-413">Outlook now detects this and helps you get connected.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-416">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-416">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-417">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-417">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="ff3a3-418">CUBEVALUE 함수가 때때로 잘못된 결과를 반환하는 문제가 해결되었습니다.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="ff3a3-418">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;</span></span></div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a><span data-ttu-id="ff3a3-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-419">Outlook</span></span>

- <div><span data-ttu-id="ff3a3-420">모임 위치 필드의 쉼표가 세미콜론으로 바뀌는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-420">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span></div>


- <div><span data-ttu-id="ff3a3-421">여러 창에서 동일한 항목을 볼 때 충돌이 발생할 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-421">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span></div>


- <div><span data-ttu-id="ff3a3-422">동기화 슬라이더가 더 작은 설정으로 설정되어 있어도 Outlook이 예기치 않게 모든 메일을 동기화시키는 문제를 해결했습니다. &nbsp;</span><span class="sxs-lookup"><span data-stu-id="ff3a3-422">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span></div>


- <div><span data-ttu-id="ff3a3-423">검은색 테마를 사용한 사용자에게 &quot;보낸 사람&quot; 드롭다운에 흰색 배경에 흰색 텍스트가 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-423">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span></div>


- <div><span data-ttu-id="ff3a3-424"><span style="display:inline !important;">이 변경으로 메시지 헤더에서 여러 줄 제목을 볼 수 있습니다.</span></span><span class="sxs-lookup"><span data-stu-id="ff3a3-424"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-february-18"></a><span data-ttu-id="ff3a3-426">버전 2002: 2월 18일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-426">Version 2002: February 18</span></span>
<span data-ttu-id="ff3a3-427">*버전 2002(빌드 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-427">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="ff3a3-428">버전 2002: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-428">Version 2002: February 11</span></span>
<span data-ttu-id="ff3a3-429">*버전 2002 (빌드 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-429">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="ff3a3-430">[여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-430">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-432">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-432">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ff3a3-433">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-433">Outlook</span></span>

- <span data-ttu-id="ff3a3-434">**사용자가 소유한 그룹으로 전자 메일 끌기:** 메시지와 대화를 받은 편지함에서 끌어서 이동하고 복사합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-434">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="ff3a3-435">끌어 놓은 메시지는 모든 그룹 구성원과 공유됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-435">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="ff3a3-436">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-436">Word</span></span>

- <span data-ttu-id="ff3a3-437">**다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다.** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-437">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ff3a3-438">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="ff3a3-438">Office Suite</span></span>

- <span data-ttu-id="ff3a3-439">**더 명확한 상태 표시줄 아이콘:** 상태 표시줄 아이콘을 쉽게 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-439">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-442">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-442">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ff3a3-443">Access</span><span class="sxs-lookup"><span data-stu-id="ff3a3-443">Access</span></span>

- <span data-ttu-id="ff3a3-444">데이터베이스 내에서 더 이상 액세스 템플릿으로 인해 첨부 열이 실패하지 않아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-444">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="ff3a3-445">템플릿을 인스턴스화 한 후에는 데이터베이스에 첨부 파일 필드를 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-445">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="ff3a3-446">이 업데이트는 ADODB 사용시 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-446">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="ff3a3-447">VB 코드의 레코더 개체에서 오류가 잘못 보고될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-447">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="ff3a3-448">이 업데이트는 Microsoft Access에서 연결된 SQL Server 테이블의 ID 열이 식별되지 않아서 행이 올바르지 않게 삭제된 것으로 보고되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-448">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="ff3a3-449">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-449">Excel</span></span>

- <span data-ttu-id="ff3a3-450">상황에 맞는 메뉴에서 주석 명령이 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-450">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="ff3a3-451">spilling 배열이 있는 셀이 있는 열로 텍스트를 변환할 때 일부 사용자에게 충돌이 발생하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-451">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="ff3a3-452">동적 배열에서 Text To Columns를 사용할 때 Excel이 중단되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-452">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-453">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-453">Outlook</span></span>

- <span data-ttu-id="ff3a3-454">월 보기를 사용하여 일정을 스크롤할 때 이전 일정 이벤트가 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-454">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="ff3a3-455">왼쪽 탐색 창의 '즐겨찾는 사람’에 저장된 폴더가 간헐적으로 사라질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-455">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="ff3a3-456">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-456">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="ff3a3-457">일부 시나리오에서 플래그가 지정된 항목 강조 표시를 사용하지 않도록 설정하는 옵션이 무시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-457">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="ff3a3-458">계정 설정을 취소할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-458">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="ff3a3-459">보존 정책에 따라 만료되는 전자 메일에 두 개의 레이블이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-459">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="ff3a3-460">하나는 메일이 하루 내에 만료되고 다른 하나는 2일 후에 만료된다는 것을 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-460">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="ff3a3-461">Citrix 환경에서 30개 이상의 캘린더를 볼 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-461">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ff3a3-462">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-462">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-463">PowerPoint 잉크 애니메이션에서 잉크가 완전히 렌더링되지 않거나 건너뛰기될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-463">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="ff3a3-464">이벤트 처리기가 실행 중인 경우, 파일을 닫은 후 PowerPoint에서 프레젠테이션 모음의 해당 파일을 즉시 제거하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-464">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="ff3a3-465">따라서 개체 모델에서 보고한 열려 있는 프레젠테이션 수가 올바르지 않아 PowerPoint가 종료되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-465">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="ff3a3-466">형광펜 관련 문제를 해결했습니다. 어두운 형광펜 색상의 텍스트는 흑백 모드에서 검은 색으로 인쇄됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-466">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="ff3a3-467">Project</span><span class="sxs-lookup"><span data-stu-id="ff3a3-467">Project</span></span>

- <span data-ttu-id="ff3a3-468">고정된 기간 유형의 100% 작업이 100% 완료 미만으로 잘못 계산할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-468">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="ff3a3-469">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-469">Word</span></span>

- <span data-ttu-id="ff3a3-470">목차를 업데이트하고 스크롤하면 때때로 문서 위에 회색 영역이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-470">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="ff3a3-471">메모가 작성되었지만 게시되지 않고 사용자가 파일을 저장하려고 하는 경우 '찾아보기'를 사용하여 파일을 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-471">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="ff3a3-472">메모 카드 간에 앞뒤로 이동할 때 때때로 선택 강조 표시로 처음 선택한 메모가 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-472">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="ff3a3-473">메모를 편집하고 텍스트를 기울임꼴로 표시하고 게시하면 기울임꼴 서식이 손실되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-473">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="ff3a3-474">반전 페이지 색이 있는 읽기 모드에서 메모 힌트가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-474">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="ff3a3-475">문서를 공동 작성하는 경우 루트 메모의 초안 버전이 유지되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-475">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="ff3a3-476">SlideTrack을 활성화하고 메모 창을 닫으면 Ctrl+Alt+M을 눌러 메모 창을 열지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-476">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="ff3a3-477">테이블에 @mention을 추가할 때 '이 문서의 테이블이 손상되었습니다'라는 오류 메시지가 생성될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-477">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="ff3a3-478">메모 상황에 맞는 메뉴에서 메모 명령(메모 편집, 메모에 대한 회신, 메모 삭제, 메모 확인)이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-478">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ff3a3-479">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="ff3a3-479">Office Suite</span></span>

- <span data-ttu-id="ff3a3-480">노르웨이 니노르스크(nn-no) 교정 도구 패키지가 잘못 설치될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-480">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="ff3a3-481">이 변경 사항은 인텔 통합 GPU를 활용하는 그래픽 어댑터에 보고된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-481">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2001-january-29"></a><span data-ttu-id="ff3a3-483">버전 2001: 1월 29일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-483">Version 2001: January 29</span></span>
<span data-ttu-id="ff3a3-484">*버전 2001 (빌드 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-484">*Version 2001 (Build 12430.20184)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-486">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-486">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="ff3a3-487">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-487">Word</span></span>

- <span data-ttu-id="ff3a3-488">**도형을 그림으로 저장:** 몇 번의 클릭만으로 도형, 아이콘 또는 기타 개체를 그림 파일로 저장하여 다른 곳에서 다시 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-488">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="ff3a3-489">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-489">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-492">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-492">Resolved issues</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-493">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-493">Outlook</span></span>

- <span data-ttu-id="ff3a3-494">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-494">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2001-january-27"></a><span data-ttu-id="ff3a3-496">버전 2001: 1월 27일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-496">Version 2001: January 27</span></span>
<span data-ttu-id="ff3a3-497">*버전 2001(빌드 12430.20170)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-497">*Version 2001 (Build 12430.20170)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-499">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-499">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-500">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-500">Excel</span></span>

- <span data-ttu-id="ff3a3-501">**읽고 즉시 회신:** 통합 문서를 열지 않고 전자 메일에서 바로 메모와 멘션에 회신합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-501">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="ff3a3-502">**준비, 설정, 그리기:** Surface 펜을 들어 그리기를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-502">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="ff3a3-503">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-503">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="ff3a3-504">**쿼리 편집기의 데이터 프로파일링:** 열에서 데이터를 한눈에 분석하고 오류와 비어 있는 값을 식별하며 배포 히스토그램을 표시하는 기능 등을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-504">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-505">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-506">**준비, 설정, 그리기:** Surface 펜을 들어 그리기를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-506">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="ff3a3-507">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-507">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="ff3a3-508">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-508">Word</span></span>

- <span data-ttu-id="ff3a3-509">**준비, 설정, 그리기:** Surface 펜을 들어 그리기를 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-509">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="ff3a3-510">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-510">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-513">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-513">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ff3a3-514">Access</span><span class="sxs-lookup"><span data-stu-id="ff3a3-514">Access</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="ff3a3-515"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">이 업데이트는 Microsoft Access에서 연결된 SQL Server 테이블의 ID 열이 식별되지 않아서 행이 올바르지 않게 삭제된 것으로 보고되는 문제를 해결합니다.</span></span></span><span class="sxs-lookup"><span data-stu-id="ff3a3-515"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly</span></span></span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2001-january-17"></a><span data-ttu-id="ff3a3-517">버전 2001: 1월 17일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-517">Version 2001: January 17</span></span>
<span data-ttu-id="ff3a3-518">*버전 2001(빌드 12430.20120)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-518">*Version 2001 (Build 12430.20120)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-520">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-520">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="ff3a3-521">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-521">Word</span></span>

- <span data-ttu-id="ff3a3-522">**주변에 도형을 그려 Word에서 잉크를 쉽게 선택할 수 있습니다.:** 그리기 탭의 올가미 도구를 사용하면 잉크로 그린 개체를 선택하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-522">**Easily select ink in Word by drawing a shape around it.:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="ff3a3-523">개별 스트로크를 선택하거나 단어 전체를 선택 합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-523">Select individual strokes, or whole words.</span></span> <span data-ttu-id="ff3a3-524">잉크 수가 많고 일부 잉크만을 사용하려는 경우 유용합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-524">It's handy when you have lots of ink and you only want to work with some of it.</span></span> [<span data-ttu-id="ff3a3-525">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-525">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-527">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-527">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-528">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-528">Excel</span></span>

- <span data-ttu-id="ff3a3-529">Excel 클라이언트로 인해 빌드 12430.20050를 사용하고 32비트 버전의 Excel을 실행하는 사용자를 위한 영어 외 언어 버전 2001에서 인쇄, 매크로 실행, 확대/축소,... 등의 여러 시나리오에서 문제가 발생합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-529">Excel client is causing issues in several scenarios (such as print, macro execution, zoom,…) on a non-English language Version 2001 for users with build 12430.20050 and running the 32-bit version of Excel.</span></span> 

## <a name="version-2001-january-14"></a><span data-ttu-id="ff3a3-530">버전 2001: 1월 14일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-530">Version 2001: January 14</span></span>
<span data-ttu-id="ff3a3-531">*버전 2001(빌드 12430.20050)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-531">*Version 2001 (Build 12430.20050)*</span></span>

<span data-ttu-id="ff3a3-532">[여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-532">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="ff3a3-533">버전 1912: 1월 8일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-533">Version 1912: January 08</span></span>
<span data-ttu-id="ff3a3-534">*버전 1912(빌드 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-534">*Version 1912 (Build 12325.20288)*</span></span>

## <a name="version-1912-january-07"></a><span data-ttu-id="ff3a3-535">버전 1912: 1월 7일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-535">Version 1912: January 07</span></span>
<span data-ttu-id="ff3a3-536">*버전 1912(빌드 12325.20280)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-536">*Version 1912 (Build 12325.20280)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-538">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-538">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ff3a3-539">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-539">Outlook</span></span>

- <span data-ttu-id="ff3a3-540">사용자가 일부 상황에서 표시된 SMTP 주소와 일치하지 않는 주소로 보낸 전자 메일을 보게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-540">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span></div>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1912-january-06"></a><span data-ttu-id="ff3a3-542">버전 1912: 1월 6일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-542">Version 1912: January 06</span></span>
<span data-ttu-id="ff3a3-543">*버전 1912 (빌드 12325.20264)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-543">*Version 1912 (Build 12325.20264)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-545">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-545">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="ff3a3-546">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-546">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-547">**GIF 즉시 만들기:** 하나의 슬라이드, 하나의 프레임.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-547">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="ff3a3-548">PowerPoint에서 쉽게 루핑 GIF를 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-548">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="ff3a3-549">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-549">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1912-december-30"></a><span data-ttu-id="ff3a3-551">버전 1912: 12월 30일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-551">Version 1912: December 30</span></span>
<span data-ttu-id="ff3a3-552">*버전 1912 (빌드 12325.20240)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-552">*Version 1912 (Build 12325.20240)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-554">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-554">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-555">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-555">Excel</span></span>

- <span data-ttu-id="ff3a3-556">**SVG 개체와 함께 컨텍스트를 가져오세요!:** 이제 Office에서 이러한 개체를 변환할 때 지도, 차트 및 기타 SVG 벡터 텍스트를 유지할 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="ff3a3-556">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-557">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-557">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-558">**SVG 개체와 함께 컨텍스트를 가져오세요!:** 이제 Office에서 이러한 개체를 변환할 때 지도, 차트 및 기타 SVG 벡터 텍스트를 유지할 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="ff3a3-558">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-561">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-561">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ff3a3-562">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-562">Outlook</span></span>

- <div><span data-ttu-id="ff3a3-563">사용자가 클라우드 설정을 검색할 때 Outlook에서 사용자가 중단되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-563">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span></div>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1912-december-19"></a><span data-ttu-id="ff3a3-565">버전 1912: 12월 19일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-565">Version 1912: December 19</span></span>
<span data-ttu-id="ff3a3-566">*버전 1912(빌드 12325.20214)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-566">*Version 1912 (Build 12325.20214)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-568">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-568">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="ff3a3-569">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-569">Word</span></span>

- <span data-ttu-id="ff3a3-570">**더욱 안전한 비디오 환경:** 보안 강화는 더욱 안전한 온라인 비디오 환경을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-570">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="ff3a3-571">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-571">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-574">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-574">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ff3a3-575">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-575">Outlook</span></span>

- <span data-ttu-id="ff3a3-576">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 현저하게 지연이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-576">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1912-december-12"></a><span data-ttu-id="ff3a3-578">버전 1912: 12월 12일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-578">Version 1912: December 12</span></span>
<span data-ttu-id="ff3a3-579">*버전 1912(빌드 12325.20172)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-579">*Version 1912 (Build 12325.20172)*</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-581">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-581">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-582">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-582">Excel</span></span>

- <span data-ttu-id="ff3a3-583">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-583">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="ff3a3-584">셀 내에서 동적 배열 수식을 편집할 때 텍스트가 셀 경계선 외부에 정렬될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-584">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

- <span data-ttu-id="ff3a3-585">일부 현지화의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-585">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="ff3a3-586">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-586">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="ff3a3-587">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-587">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="ff3a3-588">여백 드롭다운 메뉴가 제대로 렌더링되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-588">Margin dropdown menu may not render correctly.</span></span>

- <span data-ttu-id="ff3a3-589">4K 해상도의 하드웨어 그래픽 가속을 사용하지 않도록 설정하는 경우 스크롤링할 때 셀 렌더링이 지연될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-589">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>

- <span data-ttu-id="ff3a3-590">이 변경 사항은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-590">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="onenote"></a><span data-ttu-id="ff3a3-591">OneNote</span><span class="sxs-lookup"><span data-stu-id="ff3a3-591">OneNote</span></span>

- <span data-ttu-id="ff3a3-592">OneNote는 '모임 노트' Outlook 추가 기능을 통해 열리지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-592">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-593">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-593">Outlook</span></span>

- <span data-ttu-id="ff3a3-594">교차 폴더 콘텐츠를 수반하는 간헐적인 충돌</span><span class="sxs-lookup"><span data-stu-id="ff3a3-594">Intermittent crash involving cross folder content.</span></span>

- <span data-ttu-id="ff3a3-595">Outlook 전자 메일 메시지에 인라인으로 삽입된 이미지의 크기가 간혹 변경되는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-595">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

- <span data-ttu-id="ff3a3-596">그룹 정책을 통해 S/MIME 기본 서명 구성을 적용하는 기능이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-596">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

- <span data-ttu-id="ff3a3-597">포함된 이미지가 예상보다 작게 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-597">Embedded images may appear smaller than expected.</span></span>

- <span data-ttu-id="ff3a3-598">보존 정책 레이블에는 보존 기간이 괄호로 표시 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-598">Retention policy labels may display the retention time period in parenthesis.</span></span>

- <span data-ttu-id="ff3a3-599">대체 보낸 사람을 사용할 때 정책 팁이 표시되지 않게 하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-599">Addresses an issue that caused Policy tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="ff3a3-600">일본어 언어 팩이 있는 연락처 카드에 공백이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-600">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>

- <span data-ttu-id="ff3a3-601">모임을 지운 후 예기치 않게 모임의 위치를 모임을 다시 추가하게 하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-601">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-602">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-602">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-603">텍스트에서 포커스를 이동한 후 커서가 사라질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-603">Cursor may disappear after moving focus from text.</span></span>

- <span data-ttu-id="ff3a3-604">한 Office 응용 프로그램에서 다른 응용 프로그램으로의 세이프 링크가 연결된 응용 프로그램을 시작하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-604">Safelinks from one Office application to another may not launch the linked application.</span></span>

- <span data-ttu-id="ff3a3-605">일부의 경우에는 터치 장치를 사용한 스크롤이 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-605">In some cases, scrolling with touch devices will not work.</span></span>

- <span data-ttu-id="ff3a3-606">한 개의 클라우드 파일의 한 슬라이드에 있는 두 개(혹은 이상)의 비디오가 있는 경우 비디오 이미지는 올바르게 렌더링되지만 사용자가 재생을 하기 위해 각각을 클릭 시 비디오 내용이 동일합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-606">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>

- <span data-ttu-id="ff3a3-607">여백 드롭다운 메뉴가 제대로 렌더링되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-607">Margin dropdown menu may not render correctly.</span></span>

### <a name="project"></a><span data-ttu-id="ff3a3-608">Project</span><span class="sxs-lookup"><span data-stu-id="ff3a3-608">Project</span></span>

- <span data-ttu-id="ff3a3-609">사용자가 어두운 모드인 경우에 과도하게 할당된 리소스를 가지고 작업 검사자 패널로 이동하는 경우 테이블을 읽을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-609">If you are in Dark mode, when you go to the task inspector panel on a task with an overallocated resource, you are unable to read the table.</span></span>

- <span data-ttu-id="ff3a3-610">사용자에게 라이선싱과 관련된 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-610">Users may experience an error regarding licensing.</span></span>

- <span data-ttu-id="ff3a3-611">날짜 선택기에서 때때로 오늘 단추가 올바르지 않은 날짜를 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-611">The Today button in the date picker may sometimes set the incorrect date.</span></span>

- <span data-ttu-id="ff3a3-612">프로젝트 비교 기능을 사용하는 경우 프로젝트가 충돌할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-612">Project may crash when you use the Compare Projects feature.</span></span>

- <span data-ttu-id="ff3a3-613">배정이 없는 작업에 대한 노력의 설정은 1일로 반올림됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-613">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="ff3a3-614">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-614">Word</span></span>

- <span data-ttu-id="ff3a3-615">이제 창 전환기에서 숨겨진 경우 메모 힌트를 선택하면 최신 메모 창이 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-615">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

- <span data-ttu-id="ff3a3-616">마우스 오른쪽 단추를 클릭하면 전체 단어가 선택되지 않는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-616">Right-clicking can sometimes not result in selecting the whole word.</span></span>

- <span data-ttu-id="ff3a3-617">한 Office 응용 프로그램에서 다른 응용 프로그램으로의 세이프 링크가 연결된 응용 프로그램을 시작하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-617">Safelinks from one Office application to another may not launch the linked application.</span></span>

- <span data-ttu-id="ff3a3-618">문서 블록 이끌이가 잘못된 알림을 표시할 수 있습니다.&quot;사용자가 스타일, 문서 블록을 수정했습니다&quot;.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-618">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

- <span data-ttu-id="ff3a3-619">일부 테마에서는 선택된 메모를 확인하기가 어렵습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-619">Some themes may make it difficult to determine which comment is selected.</span></span>

- <span data-ttu-id="ff3a3-620">제안된 형식으로 변환한 후에는 커서가 개체 내에서 계속 활성 상태로 유지될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-620">The cursor may remain active within an object after converting to a suggested format.</span></span>

- <span data-ttu-id="ff3a3-621">일부 시나리오에서 메시지의 이미지가 제대로 크기가 조절되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-621">Images in messages may be incorrectly scaled in some scenarios.</span></span>

- <span data-ttu-id="ff3a3-622">복사/붙여넣기를 사용하는 경우 메모 창이 다시 로드되는 경우가 간혹 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-622">Comment pane sometimes gets reloaded when using copy/paste.</span></span>

- <span data-ttu-id="ff3a3-623">메모가 올바른 순서로 붙여넣기가 되지 않는 경우가 가끔 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-623">Comments are sometimes not pasted in the correct order.</span></span>

- <span data-ttu-id="ff3a3-624">댓글 카드에 있는 사용자에 멘션을 사용 시 JSON이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-624">At-mentioning a user in a comment card may show JSON.</span></span>

- <span data-ttu-id="ff3a3-625">여백 드롭다운 메뉴가 제대로 렌더링되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-625">Margin dropdown menu may not render correctly.</span></span>

- <span data-ttu-id="ff3a3-626">나눠진 화면 테두리의 크기를 조정하면 화면이 추가로 분할될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-626">Resizing a split screen border may introduce an additional split screen.</span></span>

- <span data-ttu-id="ff3a3-627">기존 문서에 사용자 지정 스타일을 사용한 다단 목록으로 구성된 서식 파일을 적용 시 특정 조건에서는 스타일이 유지되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-627">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>

- <span data-ttu-id="ff3a3-628">특정 조건에서는 메일 병합 후의 저장이 작동하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-628">Saving a file after doing a mail merge may not work under certain conditions.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ff3a3-629">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="ff3a3-629">Office Suite</span></span>

- <span data-ttu-id="ff3a3-630">Excel에서 PowerPoint로 차트를 붙여넣으면 차트 크기가 줄어들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-630">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

- <span data-ttu-id="ff3a3-631">메모를 회신하면 텍스트 상자가 창 가장자리를 벗어나 세로로 확장될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-631">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

- <span data-ttu-id="ff3a3-632">일본어 기반 제품의 경우 계정 사용자의 이름과 성이 잘못된 순서로 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-632">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>

- <span data-ttu-id="ff3a3-633">상대적인 마감일이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정 버그에 대한 픽스, 이 픽스는 후속 업데이트에 대한 상대적인 마감일도 사용할 수 있도록 해줍니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-633">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="ff3a3-634">메모 위에 마우스 포인터를 올리면 메모 주변에 텍스트 상자의 윤곽이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-634">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

- <span data-ttu-id="ff3a3-635">Office 업데이트에서 로컬 또는 네트워크 공유 또는 Configuration Manager에서 제공하는 위치와 같은 의도된 원본 대신 Office CDN에서 파일을 예기치 않게 다운로드했을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-635">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1911-december-10"></a><span data-ttu-id="ff3a3-637">버전 1911: 12월 10일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-637">Version 1911: December 10</span></span>
<span data-ttu-id="ff3a3-638">*버전 1911 (빌드 12228.20364)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-638">*Version 1911 (Build 12228.20364)*</span></span>

<span data-ttu-id="ff3a3-639">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ff3a3-639">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-641">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-641">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-642">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-642">Excel</span></span>

- <span data-ttu-id="ff3a3-643">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-643">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="ff3a3-644">\*\* 더 많은 접근 가능한 PDF 만들기:\*\* PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-644">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="ff3a3-645">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-645">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

### <a name="outlook"></a><span data-ttu-id="ff3a3-646">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-646">Outlook</span></span>

- <span data-ttu-id="ff3a3-647">**그룹 명명 정책:** 그룹 명명 정책을 사용하면 IT 관리자가 조직의 사용자가 만든 그룹의 이름을 표준화하고 관리할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-647">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="ff3a3-648">관리자는 그룹 이름을 만들 때 특정 접두사와 접미사를 추가하도록 요구할 수 있으며, 특정 단어를 사용할 수 없도록 차단할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-648">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="ff3a3-649">이는 그룹 이름에 부적절한 단어의 사용을 최소화하는데 도움을 줄뿐만 아니라 IT가 해당 디렉터리의 그룹의 표현을 관리하는 데 도움이 됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-649">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="ff3a3-650">명명 정책은 또한 팀 사이트를 배포하는 조직이 부서를 기준으로 분류하는데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-650">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-651">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-651">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-652">**잉크 스턴트 재생:** 슬라이드에 잉크를 쓸 때 슬라이드 쇼 중에 잉크의 실제 그리기를 재생하기 위한 재생 애니메이션을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-652">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="ff3a3-653">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-653">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="ff3a3-654">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-654">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="ff3a3-655">\*\* 더 많은 접근 가능한 PDF 만들기:\*\* PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-655">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

### <a name="word"></a><span data-ttu-id="ff3a3-656">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-656">Word</span></span>

- <span data-ttu-id="ff3a3-657">**다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다.** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-657">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="ff3a3-658">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-658">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="ff3a3-659">\*\* 더 많은 접근 가능한 PDF 만들기:\*\* PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-659">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="ff3a3-660">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-660">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

## <a name="resolved-issues"></a><span data-ttu-id="ff3a3-661">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-661">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-662">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-662">Excel</span></span>

- <span data-ttu-id="ff3a3-663">이 변경 사항은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-663">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="ff3a3-664">피벗 차트의 오른쪽 클릭 메뉴를 수정하여 세부 정보를 표시하는 옵션을 사용할 수 있도록 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-664">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-665">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-665">Outlook</span></span>

- <span data-ttu-id="ff3a3-666">웹 추가 기능이 디지털 권한 관리 메시지에 액세스하게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-666">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1911-november-20"></a><span data-ttu-id="ff3a3-668">버전 1911: 11월 20일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-668">Version 1911: November 20</span></span>
<span data-ttu-id="ff3a3-669">*버전 1911 (빌드 12228.20250)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-669">*Version 1911 (Build 12228.20250)*</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-671">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-671">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="ff3a3-672">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-672">Outlook</span></span>

- <span data-ttu-id="ff3a3-673">**고급 그룹 전자 메일 설정:** 이 기능을 사용하면 그룹 사용자가 전자 메일이나 이벤트를 받은 편지함에서 받거나 팔로우하도록 사용자 지정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-673">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1911-november-15"></a><span data-ttu-id="ff3a3-675">버전 1911: 11월 15일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-675">Version 1911: November 15</span></span>
<span data-ttu-id="ff3a3-676">*버전 1911 (빌드 12228.20206)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-676">*Version 1911 (Build 12228.20206)*</span></span>

## <a name="version-1911-november-12"></a><span data-ttu-id="ff3a3-677">버전 1911: 11월 12일</span><span class="sxs-lookup"><span data-stu-id="ff3a3-677">Version 1911: November 12</span></span>
<span data-ttu-id="ff3a3-678">*버전 1911 (빌드 12228.20120)*</span><span class="sxs-lookup"><span data-stu-id="ff3a3-678">*Version 1911 (Build 12228.20120)*</span></span>

<span data-ttu-id="ff3a3-679">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ff3a3-679">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="ff3a3-681">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="ff3a3-681">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="ff3a3-682">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-682">Excel</span></span>

- <span data-ttu-id="ff3a3-683">**데이터 시각화 도우미 추가 기능:** Excel에서 빠르게 Visio 플로차트를 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-683">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="ff3a3-684">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-684">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="ff3a3-685">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-685">Outlook</span></span>

- <span data-ttu-id="ff3a3-686">**가장 필요로 하는 사용자에게 접속할 수 있는 메일 보내기:** Outlook에서 접속할 수 있는 콘텐츠를 선호하는 사용자에게 전자 메일을 보낼 때 콘텐츠에 액세스가 가능한 지 확인하는 데 도움이 되는 메일 팁을 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-686">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-687">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-687">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-688">\*\*모든 사용자를 위한 프레젠테이션 최적화: \*\* 접근성 검사기는 기능은 스크린 리더를 염두에 두고 슬라이드에서 개체를 정렬하는데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-688">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="visio"></a><span data-ttu-id="ff3a3-689">Visio</span><span class="sxs-lookup"><span data-stu-id="ff3a3-689">Visio</span></span>

- <span data-ttu-id="ff3a3-690">**Excel에서 세련된 Visio  다이어그램 만들기** Excel 내에서 데이터를 세련된 Visio 다이어그램으로 쉽고 빠르게 시각화합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-690">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="ff3a3-691">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="ff3a3-691">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="ff3a3-692">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-692">Word</span></span>

- <span data-ttu-id="ff3a3-693">**공동 작성 개선:** 실시간으로 다른 사용자가 콘텐츠 변경 내용을 받을 수 있도록 하여 더 높은 공동 작성 환경을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-693">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ff3a3-694">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="ff3a3-694">Office Suite</span></span>

- <span data-ttu-id="ff3a3-695">\*\*업로드 센터가 주의를 요하는 파일들로 대체됩니다: \*\* 업로드 센터가 파일 > 열기 아래의 Office 응용 프로그램 내에 표시되는 주의를 요하는 파일들로 대체됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-695">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="ff3a3-696">이 새로운 환경은 업로드 센터와 비교 시 더욱 최신이고, 통합적이며 개입성이 낮습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-696">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="ff3a3-699">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="ff3a3-699">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ff3a3-700">Access</span><span class="sxs-lookup"><span data-stu-id="ff3a3-700">Access</span></span>

- <span data-ttu-id="ff3a3-701">레코드 수가 올바르지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-701">The record count could be incorrect.</span></span>

### <a name="excel"></a><span data-ttu-id="ff3a3-702">Excel</span><span class="sxs-lookup"><span data-stu-id="ff3a3-702">Excel</span></span>

- <span data-ttu-id="ff3a3-703">다른 시트의 데이터를 참조하는 스파크 라인이 포함된 시트를 삭제하면 파일을 다시 열 때 손상된 것으로 식별될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-703">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="ff3a3-704">차트 크기에 대한 변경 내용을 저장할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-704">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="ff3a3-705">확인란을 제대로 렌더링할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-705">Checkboxes could not render correctly.</span></span>
- <span data-ttu-id="ff3a3-706">일부 필드에서는 데이터 원본 선택 대화 상자의 대/소문자가 구분되지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-706">Select Data Source dialogs were not case sensitive for some fields.</span></span>
- <span data-ttu-id="ff3a3-707">일부 VBA 함수는 새로운 차트에서 오류를 반환합니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-707">Some VBA functions would return an error on new chart.</span></span>
- <span data-ttu-id="ff3a3-708">사용자가 Office 365 Excel 통합 문서 형식으로 저장을 하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-708">Users could be prevented from saving in Office 365 Excel Workbook format.</span></span>
- <span data-ttu-id="ff3a3-709">자동 맞춤을 사용하여 행 높이를 조정할 때 확인란 컨트롤이 축소되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-709">Resolved an issue where check box controls could shrink when using autofit to adjust row height.</span></span>
- <span data-ttu-id="ff3a3-710">보고서 필터를 SQL 태뷸러 서버에 대한 쿼리의 나머지 피벗 테이블과 함께 변환할 때 잘못된 결과가 발생할 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-710">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="ff3a3-711">신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 오류를 발생시킬 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-711">Resolved an issue where Excel may fail when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="ff3a3-712">내레이터와 돋보기를 동시에 사용하면 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-712">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="ff3a3-713">스크롤 후 셀을 선택하면 잘못된 셀이 선택되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-713">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>
- <span data-ttu-id="ff3a3-714">병합된 셀이 있는 열을 삭제하는 성능이 크게 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-714">We significantly improved the performance of deleting columns with merged cells.</span></span>

### <a name="onenote"></a><span data-ttu-id="ff3a3-715">OneNote</span><span class="sxs-lookup"><span data-stu-id="ff3a3-715">OneNote</span></span>

- <span data-ttu-id="ff3a3-716">로컬 리소스에서 클라우드 리소스로의 동기화에 영향을 줄 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-716">Identified an issue which could affect syncing from a local resource to a cloud resource.</span></span>

### <a name="outlook"></a><span data-ttu-id="ff3a3-717">Outlook</span><span class="sxs-lookup"><span data-stu-id="ff3a3-717">Outlook</span></span>

- <span data-ttu-id="ff3a3-718">회의실 찾기 도구가 사용 가능한 회의실을 &quot;없음&quot;으로 표시할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-718">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="ff3a3-719">리본이 자동으로 숨기기로 설정된 경우 검색 상자가 사라지는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-719">Identified an issue where the search box could disappear when the ribbon is set to hide automatically.</span></span>
- <span data-ttu-id="ff3a3-720">디지털로 서명된 첨부 파일을 사용하여 전자 메일에 서명할 때 디지털 서명이 훼손되는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-720">Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment.</span></span>
- <span data-ttu-id="ff3a3-721">전달된 전자 메일에 포함된 이미지가 누락될 수 있음</span><span class="sxs-lookup"><span data-stu-id="ff3a3-721">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="ff3a3-722">사용자가 엄격한 테넌트 제한이 있는 Outlook 프로필을 만들지 못할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-722">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>
- <span data-ttu-id="ff3a3-723">메시지 본문에 끌어넣기를 한 후 긴 파일 이름이 잘리는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-723">Identified an issue where long filenames were truncated after draging and droping to the message body.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ff3a3-724">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ff3a3-724">PowerPoint</span></span>

- <span data-ttu-id="ff3a3-725">차트 크기에 대한 변경 내용을 저장할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-725">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="ff3a3-726">내레이터와 돋보기를 동시에 사용하면 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-726">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="ff3a3-727">슬라이드 미리 보기의 가로 세로 비율이 제대로 잠기거나 해제되지 않는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-727">Identified an issue where aspect ratio for the slide preview was not being properly locked/unlocked.</span></span>

### <a name="project"></a><span data-ttu-id="ff3a3-728">Project</span><span class="sxs-lookup"><span data-stu-id="ff3a3-728">Project</span></span>

- <span data-ttu-id="ff3a3-729">업데이트 작업을 수행하는 동안 입력한 메모가 보존되지 않는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-729">Identified an issue where notes might not persist if entered while doing update tasks.</span></span>
- <span data-ttu-id="ff3a3-730">사용자가 작업을 완료로 표시할 수 없으며, 이는 99%로 설정됩니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-730">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="ff3a3-731">평준화로 초과 할당을 해결할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-731">Overallocations are not resolved by leveling.</span></span>
- <span data-ttu-id="ff3a3-732">읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-732">Identified an issue where users could get several messages when opening a read-only project.</span></span>
- <span data-ttu-id="ff3a3-733">사용자가 파일을 잠글 수 있지만 오류 메시지에 사용자 이름이 표시되지 않는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-733">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message.</span></span>

### <a name="publisher"></a><span data-ttu-id="ff3a3-734">게시자</span><span class="sxs-lookup"><span data-stu-id="ff3a3-734">Publisher</span></span>

- <span data-ttu-id="ff3a3-735">도형이 그래픽 테두리 외부에 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-735">Shapes could appear outside of the graphics border.</span></span>

### <a name="word"></a><span data-ttu-id="ff3a3-736">Word</span><span class="sxs-lookup"><span data-stu-id="ff3a3-736">Word</span></span>

- <span data-ttu-id="ff3a3-737">컨텍스트 메뉴에 교정 제안이 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-737">Proofing suggestions are not displaying in contextual menus.</span></span>
- <span data-ttu-id="ff3a3-738">차트 크기에 대한 변경 내용을 저장할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-738">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="ff3a3-739">도형이 그래픽 테두리 외부에 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-739">Shapes could appear outside of the graphics border.</span></span>
- <span data-ttu-id="ff3a3-740">스크린 리더를 사용하는 동안 의견을 볼 때 발생하는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-740">Identified an issue when viewing comments while using a screen reader.</span></span>
- <span data-ttu-id="ff3a3-741">일부 비평이 맞춤법이나 문법의 비평으로 오인되는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-741">Identified an issue where some critiques were misidentified as being spelling or grammar critiques.</span></span>
- <span data-ttu-id="ff3a3-742">cid 링크: Outlook 메시지의 이미지는 이제 요청 시 성공적으로 나누어질 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-742">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="ff3a3-743">한국어/영어 자동 고침을 사용하는 경우 잘못된 문자가 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-743">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="ff3a3-744">탐색 창에서 검색이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-744">Searching from the Navigation pane may fail.</span></span>
- <span data-ttu-id="ff3a3-745">내레이터와 돋보기를 동시에 사용하면 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-745">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="ff3a3-746">콘텐츠 정책이 메모에 제대로 적용되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-746">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="ff3a3-747">상위 정책 레이블이 우선 순위를 가져야할 때 하위 정책 레이블이 적용될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-747">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="ff3a3-748">레거시 문서를 연 다음 정보 탭으로 이동하면 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-748">Opening legacy documents and then going to the Info tab can cause a failure.</span></span>
- <span data-ttu-id="ff3a3-749">새 의견 대화 상자에서 간혹 포커스가 맞지 않는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-749">Identified an issue where a new comment dialog could sometimes not obtain focus.</span></span>
- <span data-ttu-id="ff3a3-750">@멘션에 서식 적용 후 연락처 카드를 열지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-750">A contact card could be prevented from opening after apply formatting to an @ mention.</span></span>
- <span data-ttu-id="ff3a3-751">텍스트를 강조 표시하는 것이 어려울 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-751">Highlighting text could be challenging.</span></span>
- <span data-ttu-id="ff3a3-752">사용자가 Word, Excel 및 PowerPoint 문서를 저장할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-752">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="ff3a3-753">이 문제는 새 파일을 만든 후 저장 아이콘을 클릭하거나 Ctrl + S를 눌러 "다른 이름으로 저장" 옵션을 가져오는 사용자에게 영향을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-753">This issue affects users that create a new file and bring up the "Save as" option after clicking on the Save icon or pressing Ctrl + S.</span></span>
- <span data-ttu-id="ff3a3-754">어두운 텍스트를 사용하여 쓰여진 레거시 메모가 어두운 모드에서 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-754">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="ff3a3-755">사용자가 편집기의 개별 항목으로 이동하지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-755">A user could be prevented from navigating to an individual item in the editor.</span></span>
- <span data-ttu-id="ff3a3-756">문법 또는 맞춤법 오류가 강조 표시되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-756">Grammar or spelling errors might not be highlighted.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ff3a3-757">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="ff3a3-757">Office Suite</span></span>

- <span data-ttu-id="ff3a3-758">일부 드로잉이 미리보기 또는 슬라이드 쇼에서 표시되지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-758">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="ff3a3-759">“진행 중인 다른 설치”의 잘못된 오류 메시지로 인해 업그레이드를 하지 못했던 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-759">We fixed an issue where an upgrade could be prevented by a incorrect error message of "Another install in progress".</span></span>
- <span data-ttu-id="ff3a3-760">세로 텍스트 상자에서 일부 가타카나 문자가 잘못 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-760">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="ff3a3-761">연결되지 않은 네트워크 공유에 파일을 저장하면 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-761">Attempting to save a file to a disconnected network share may result in a filure.</span></span>
- <span data-ttu-id="ff3a3-762">Windows 7에서 도형을 사용하는 경우의 성능 문제.</span><span class="sxs-lookup"><span data-stu-id="ff3a3-762">Performance issue when using Shapes on Windows 7.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

