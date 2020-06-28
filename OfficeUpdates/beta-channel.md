---
title: 베타 채널에 대 한 릴리스 정보
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 초기 참가자 대상 그룹에게 주요 새 기능, 수정 사항 또는 알려진 문제의 최신 목록을 제공합니다.
ms.openlocfilehash: 55d62bf10375c72a09f93369c20f7f5b6d1b963f
ms.sourcegitcommit: f9bf47d0d27e084205311ab6e844d044da83f252
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/26/2020
ms.locfileid: "44906913"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="d79fe-103">베타 채널에 대 한 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="d79fe-104">이 문서에는 Word, Excel, PowerPoint, Outlook, Access 및 Windows 데스크톱 프로젝트의 베타 채널 빌드를 위한 릴리스 정보가 포함 되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="d79fe-105">매주 Microsoft는 흥미로운 새 기능, 중요한 수정 사항, 알리고자 하는 중요한 문제를 강조합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="d79fe-106">일정 기간에 걸쳐 기능 (및 수정 사항)을 베타 채널에 배포 하는 경우가 많습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="d79fe-107">이로서 더욱 광범위한 사용자들에게 기능을 릴리스하기 전에 원활하게 작동하는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="d79fe-108">따라서 아래에 설명된 기능이 보이지 않더라도 곧 제공되게 되므로 걱정할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="d79fe-109">당사는 Microsoft 365 앱에 대한 업데이트 채널을 일부 변경하고 있습니다. 여기에는 새 업데이트 채널 추가(월별 엔터프라이즈 채널) 및 기존 업데이트 채널의 이름 변경 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="d79fe-110">자세한 내용은 [이 문서를 검토하세요](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="d79fe-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="d79fe-111">릴리스 정보는 매주 포스팅되며 여러 빌드의 편집일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="d79fe-112">릴리스 정보 게시 날짜는 실제 빌드 릴리스 날짜와 일치하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (제거하지 마세요)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

## <a name="version-2007-june-26"></a><span data-ttu-id="d79fe-115">버전 2007:6 월 26 일</span><span class="sxs-lookup"><span data-stu-id="d79fe-115">Version 2007: June 26</span></span>
<span data-ttu-id="d79fe-116">*버전 2007 (빌드 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-116">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-118">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-118">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d79fe-119">Access</span><span class="sxs-lookup"><span data-stu-id="d79fe-119">Access</span></span>

- <span data-ttu-id="d79fe-120">연결 된 SQL 테이블을 새로 고치면 연결 된 테이블 관리자가 기본 키를 입력 하 라는 메시지가 표시 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-120">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="d79fe-121">쿼리 편집기의 쿼리가 스크롤되어 보이지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-121">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="d79fe-122">쿼리 실행이 예상 보다 두 배의 시간을 차지 하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-122">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-123">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-123">Outlook</span></span>

- <span data-ttu-id="d79fe-124">사용자가 메일 그룹의 ' 다른 사람 이름으로 보내기 ' 또는 ' 대신 보내기 '를 할 수 없는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-124">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="d79fe-125">메시지에 이미지를 인라인으로 삽입 한 후 메시지를 드래프트로 저장 하면 이미지 크기가 조정 되는 문제가 해결 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-125">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="d79fe-126">주제를 편집한 후 NDR 메시지 본문을 유니코드에서 ASCII로 변경 하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-126">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-127">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-127">Project</span></span>

- <span data-ttu-id="d79fe-128">정부 커뮤니티 클라우드 환경의 Project Planner 링크가 사용 하지 않도록 설정 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-128">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d79fe-129">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d79fe-129">Office Suite</span></span>

- <span data-ttu-id="d79fe-130">Word, Excel 또는 PowerPoint 파일에 SVG (확장 가능한 벡터 그래픽)에 삽입 된 텍스트를 삽입 한 후 파일을 저장 하 고 닫은 후 파일을 다시 여는 문제를 illegible.</span><span class="sxs-lookup"><span data-stu-id="d79fe-130">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2007-june-19"></a><span data-ttu-id="d79fe-132">버전 2007:6 월 19 일</span><span class="sxs-lookup"><span data-stu-id="d79fe-132">Version 2007: June 19</span></span>
<span data-ttu-id="d79fe-133">*버전 2007 (빌드 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-133">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-135">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-136">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-136">Excel</span></span>

- <span data-ttu-id="d79fe-137">통합 문서를 SharePoint/OneDrive에 저장할 때 사용자 지정 리본 메뉴 탭의 CustomUI XML이 제거 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-137">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="d79fe-138">파일에 읽기 전용 권장 사항이 있을 때 통합 문서가 읽기 전용으로 설정 된 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-138">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-139">Outlook</span></span>

- <span data-ttu-id="d79fe-140">Ime (입력기) 창이 다른 해상도로 여러 모니터를 사용할 때 IME를 통해 입력 중인 기본 텍스트와 겹치게 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-140">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="d79fe-141">이전에 저장 한 약속을 닫을 때 사용자가 다음 오류를 표시 하는 문제를 해결 했습니다: "다른 사용자가 변경 했거나 다른 창에서 항목을 저장할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-141">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="d79fe-142">항목의 기본 폴더에 복사본을 만드시겠습니까? "</span><span class="sxs-lookup"><span data-stu-id="d79fe-142">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="d79fe-143">일본 사용자의 경우 미니 일정의 날짜가 굵게 표시 되지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-143">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="d79fe-144">일정 미리 알림이 매주 한 주 이내에 진행 되는 모임의 시간을 정확히 표시 하지 못하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-144">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-145">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-145">PowerPoint</span></span>

- <span data-ttu-id="d79fe-146">라이브 공동 작성 세션 중에 사용자의 현재 상태 색 표시기가 공동 작성 갤러리에서 새로 고쳐지지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-146">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-147">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-147">Project</span></span>

- <span data-ttu-id="d79fe-148">고정 기간 작업이 100% 완료 되었지만 실제 완료 날짜를 지정 하지 않은 경우 작업 완료율이 100% 미만으로 표시 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-148">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-149">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-149">Word</span></span>

- <span data-ttu-id="d79fe-150">HTML 하이퍼링크 색이 올바르게 렌더링 되지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-150">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d79fe-151">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d79fe-151">Office Suite</span></span>

- <span data-ttu-id="d79fe-152">Http 또는 https 기반이 아닌 Url이 가장 최근에 사용 된 목록에 표시 되지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-152">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2007-june-12"></a><span data-ttu-id="d79fe-154">버전 2007:6 월 12 일</span><span class="sxs-lookup"><span data-stu-id="d79fe-154">Version 2007: June 12</span></span>
<span data-ttu-id="d79fe-155">*버전 2007 (빌드 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-155">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-157">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-157">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-158">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-158">Excel</span></span>

- <span data-ttu-id="d79fe-159">**데이터 형식을 사용 하 여 POWER BI에서 조직 데이터 가져오기:** Power BI의 Excel 데이터 형식은 이제 Office 365 E5/A5 또는 Microsoft 365 E5/A5가 있는 조직의 참가자에 게 배포 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-159">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="d79fe-160">필요한 정보를 가져오고 쉽게 새로 고쳐야 하는 것은 일상적인 많은 워크플로에 중요 한 요소입니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-160">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="d79fe-161">Microsoft는 Power BI에서 Excel의 데이터 형식으로 회사 또는 조직 정보에 액세스할 수 있도록 하 여 스프레드시트에 연결 된 정보를 가져올 수 있는 기능을 확장 하 고 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-161">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="d79fe-162">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-162">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="d79fe-163">[블로그 게시물](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="d79fe-163">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-166">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-166">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d79fe-167">Access</span><span class="sxs-lookup"><span data-stu-id="d79fe-167">Access</span></span>

- <span data-ttu-id="d79fe-168">Microsoft Access에서 연결 된 SQL Server 테이블의 Id 열을 식별 하지 못하여 행이 잘못 삭제 된 것으로 보고 될 수 있는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-168">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="d79fe-169">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-169">Excel</span></span>

- <span data-ttu-id="d79fe-170">방사형 차트의 주 눈금선을 제대로 서식 지정할 수 없는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-170">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-171">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-171">Project</span></span>

- <span data-ttu-id="d79fe-172">프로젝트 요약 작업 (프로젝트 시작/작업 필드)이 변경 될 때 ProjectBeforeTaskChange 이벤트가 발생 하지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-172">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="d79fe-173">초기 설정 또는 업데이트 시 시간대 별 예산 비용/작업 자원이 변경 될 수 있으며 초기 계획에 잘못 된 예산 값이 적용 될 수 있는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-173">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-174">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-174">Word</span></span>

- <span data-ttu-id="d79fe-175">Office 리본 메뉴의 서식 지우기 단추를 통해 메모 창에서 서식을 지우는 기능이 작동 하지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-175">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="d79fe-176">눈금자가 표시 되지 않을 때 테이블의 크기를 변경 하면 백그라운드로 실행 되는 다른 응용 프로그램이 깜박임을 시작할 수 있는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-176">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="d79fe-177">공동 작성 모드에서는 메모 회신이 메모 창에 표시 되지 않지만 수정 창에 표시 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-177">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="d79fe-178">Word에서 문서를 저장 하 고 연 후에도 50 개 보다 많은 수의 문서가 있는 경우 해당 문서가 변경 되지 않았더라도 수정 내용이 표시 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-178">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2006-june-05"></a><span data-ttu-id="d79fe-180">버전 2006:6 월 05 일</span><span class="sxs-lookup"><span data-stu-id="d79fe-180">Version 2006: June 05</span></span>
<span data-ttu-id="d79fe-181">*버전 2006 (빌드 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-181">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-183">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-183">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-184">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-184">Excel</span></span>

- <span data-ttu-id="d79fe-185">**Excel에서 공동 작업을 수행 하는 동안 정렬/필터링:** 이제 다른 사람과 공동 작업 하면서 Excel 파일을 정렬 및 필터링 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-185">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="d79fe-186">이 새로운 기능을 사용 하면 문서를 공동으로 사용 하는 동안 다른 사용자의 정렬 및 필터를 통해 영향을 받지 않게 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-186">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="d79fe-187">**Excel 내에서 POWER BI의 데이터 집합에서 피벗 테이블을 만듭니다.** Excel에서 몇 번의 클릭 만으로 Power BI에 저장 된 데이터 집합에 연결 된 피벗 테이블을 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-187">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="d79fe-188">이렇게 하면 피벗 테이블 및 Power BI 중에서 최상의 성능을 얻을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-188"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="d79fe-189">보안 Power BI 데이터 집합의 피벗 테이블을 사용 하 여 데이터를 계산, 요약 및 분석 합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-189">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="d79fe-190">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-190">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="d79fe-191">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-191">Outlook</span></span>

- <span data-ttu-id="d79fe-192">**이전 세션에서 항목을 빠르게 다시 엽니다.** 이전 Outlook 세션에서 항목을 빠르게 다시 열 수 있는 옵션이 추가 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-192">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="d79fe-193">Outlook이 충돌 하는 것이 든, 아니면 사용자가 해당 앱을 다시 열 때 빠르게 항목을 시작할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-193">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="d79fe-194">이 기능은 기본적으로 설정 되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-194">This feature is on by default.</span></span> <span data-ttu-id="d79fe-195">해제 하려면 옵션 > 일반 > 시작 옵션으로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-195">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-198">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-198">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-199">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-199">Excel</span></span>

- <span data-ttu-id="d79fe-200">차트 축의 사용자 지정 값이 제대로 적용 되지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-200">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="d79fe-201">파일을 저장할 때 이름이 정의 된 여러 수식이 포함 된 워크시트의 시간이 더 오래 걸리는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-201">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-202">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-202">Outlook</span></span>

- <span data-ttu-id="d79fe-203">Ime (입력 방법 편집기) 창이 다른 해상도로 여러 모니터를 사용할 때 IME를 통해 입력 중인 기본 텍스트와 겹치는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-203">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="d79fe-204">새 전자 메일 메시지를 작성할 때 서식 파일을 볼 때 충돌이 발생 하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-204">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="d79fe-205">Outlook 버전 1911 후 사용자가 2010 공용 폴더를 교환할 수 없는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-205">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="d79fe-206">Office 리본의 그룹 일정에 대 한 범주 단추를 사용할 수 없는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-206">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="d79fe-207">Outlook에서 충돌 하는 대화 상대가 있는 사용자가 충돌을 경험 하 게 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-207">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="d79fe-208">높은 DPI 모니터에서 사용자가 폴더 속성의 온라인 보관 드롭다운을 누락 하 게 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-208">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="d79fe-209">일반 텍스트 전자 메일의 하이퍼링크 작업을 수행할 때 Outlook에서 충돌이 발생 하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-209">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="d79fe-210">Outlook에서 RFC2231로 인코드된 긴 파일 이름을 구문 분석할 수 없는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-210">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="d79fe-211">화면 읽기 프로그램을 사용할 때 Outlook 사용자에 게 간헐적으로 응답이 발생 하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-211">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-212">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-212">PowerPoint</span></span>

- <span data-ttu-id="d79fe-213">폼 기반 인증을 사용 하 여 서버 구성 파일을 여는 것과 관련 한 문제가 해결 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-213">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="d79fe-214">포함 된 차트/통합 문서가 있는 PowerPoint 파일을 저장 하면 오류가 발생 하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-214">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="d79fe-215">사용자가 닫은 메모 창이 자동으로 다시 열리도록 하는 문제가 해결 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-215">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="d79fe-216">한 슬라이드의 슬라이드 편집기가 다음 슬라이드로 겹치는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-216">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-217">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-217">Project</span></span>

- <span data-ttu-id="d79fe-218">부모 계획이 삭제 된 후 고아 작업을 삭제 하거나 다시 할당할 수 없도록 하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-218">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-219">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-219">Word</span></span>

- <span data-ttu-id="d79fe-220">설명 창의 타임 스탬프가 시스템 로캘 시간을 기반으로 하지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-220">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="d79fe-221">웹 앱과 데스크톱 응용 프로그램 간의 설명이 동기화 되지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-221">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)


## <a name="version2006may29"></a><span data-ttu-id="d79fe-223">버전 2006:5 월 29 일</span><span class="sxs-lookup"><span data-stu-id="d79fe-223">Version 2006: May 29</span></span>
<span data-ttu-id="d79fe-224">*버전 2006 (빌드 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-224">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="featureupdates"></a><span data-ttu-id="d79fe-225">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-225">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d79fe-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-226">Outlook</span></span>

- <span data-ttu-id="d79fe-227">**Outlook toast 알림에 추가 된 추가 단추:** 이제 Windows 10에서 Outlook을 실행할 때 빠른 실행 단추가 Outlook toast 알림에 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-227">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-228">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-228">PowerPoint</span></span>

- <span data-ttu-id="d79fe-229">**PowerPoint에서 스트림 비디오 성능이 향상 되었습니다.** 비디오 로드 시간을 최소화 하 고 매끄러운 보기 환경을 만들기 위해 Microsoft Stream 비디오의 재생 성능을 개선 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-229">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="d79fe-230">Microsoft Stream의 회사 동영상을 사용 하 여 더 나은 프레젠테이션을 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-230">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolvedissues"></a><span data-ttu-id="d79fe-233">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-233">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="d79fe-234">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-234">Excel</span></span>

- <span data-ttu-id="d79fe-235">OneDrive를 사용할 때 Excel이 때때로 종료 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-235">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="d79fe-236">같은 통합 문서 내에서 책갈피로 표시 된 하이퍼링크를 클릭 하면 통합 문서를 숨기는 문제가 해결 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-236">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="d79fe-237">일부 복사 및 붙여 넣은 차트 링크는 범용 주소가 아닌 매핑된 드라이브 주소를 사용 하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-237">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="d79fe-238">Excel 창이 팀을 통해 공유 될 때 Ctrl + Shift + 화살표 키를 사용 하 여 스크롤하면 Excel이 응답 하지 않게 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-238">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-239">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-239">PowerPoint</span></span>

- <span data-ttu-id="d79fe-240">마우스 휠을 사용 하 여 확대 한 후 슬라이드가 가운데에 나타나지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-240">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-241">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-241">Word</span></span>

- <span data-ttu-id="d79fe-242">메모 창에 텍스트를 복사 하 여 붙여 넣는 것이 표시 되지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-242">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="d79fe-243">주석 힌트 거품이 100% zoom에서 희미 한 것 처럼 보이는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-243">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="d79fe-244">정책 단어 2007 이상 이진 문서와 서식 파일을 사용 하면 일부 공동 작성 사례가 실패할 수 있는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-244">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="d79fe-245">긴 경로 이름의 파일 (32K 초과)이 열리지 않고 해당 오류 메시지가 표시 되지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-245">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a><span data-ttu-id="d79fe-246">버전 2006:5 월 22 일</span><span class="sxs-lookup"><span data-stu-id="d79fe-246">Version 2006: May 22</span></span>
<span data-ttu-id="d79fe-247">*버전 2006 (빌드 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-247">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-249">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-249">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-250">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-250">Excel</span></span>

- <span data-ttu-id="d79fe-251">**고정 된 폴더에 저장:** 폴더를 고정 하면 Office 파일을 보다 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-251">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="d79fe-252">사용자가 새 파일을 저장할 때 사용할 수 있는 폴더를 보다 강력 하 게 제어 하려는 의견이 수신 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-252">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="d79fe-253">새 기능을 제공 하는 경우: 저장 대화 상자에 폴더를 고정 합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-253">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="d79fe-254">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 보다 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-254">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="d79fe-255">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="d79fe-255">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-256">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-256">PowerPoint</span></span>

- <span data-ttu-id="d79fe-257">**고정 된 폴더에 저장:** 폴더를 고정 하면 Office 파일을 보다 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-257">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="d79fe-258">사용자가 새 파일을 저장할 때 사용할 수 있는 폴더를 보다 강력 하 게 제어 하려는 의견이 수신 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-258">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="d79fe-259">새 기능을 제공 하는 경우: 저장 대화 상자에 폴더를 고정 합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-259">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="d79fe-260">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 보다 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-260">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="d79fe-261">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보를 참조하세요</span><span class="sxs-lookup"><span data-stu-id="d79fe-261">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-262">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-262">Word</span></span>

- <span data-ttu-id="d79fe-263">**고정 된 폴더에 저장:** 폴더를 고정 하면 Office 파일을 보다 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-263">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="d79fe-264">사용자가 새 파일을 저장할 때 사용할 수 있는 폴더를 보다 강력 하 게 제어 하려는 의견이 수신 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-264">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="d79fe-265">새 기능을 제공 하는 경우: 저장 대화 상자에 폴더를 고정 합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-265">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="d79fe-266">이 새로운 기능을 통해 Word, Excel 및 PowerPoint 파일을 보다 쉽게 저장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-266">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="d79fe-267">[블로그 게시물](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="d79fe-267">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-270">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-270">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-271">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-271">Excel</span></span>

- <span data-ttu-id="d79fe-272">추가 기능이 사용자 지정 순서가 아닌 알파벳 순서로 로드 되었기 때문에 "이 통합 문서가 현재 다른 사용자가 이미 참조 하 고 있으므로 닫을 수 없습니다." 라는 오류 메시지가 표시 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-272">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="d79fe-273">Excel과 일부 타사 보조 기술 응용 프로그램 간에 글꼴을 관리할 때 메모리가 손상 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-273">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="d79fe-274">추가 기능에서 noSelect 잠금과 함께 셰이프를 포함 하는 워크시트의 호스트 항목을 요청 하면 Excel이 중단 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-274">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-275">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-275">Outlook</span></span>

- <span data-ttu-id="d79fe-276">사용자가 폴더 간에 항목을 이동 했을 때 BeforeItemMove 이벤트가 올바르게 발생 하지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-276">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="d79fe-277">사용자가 자정 임계값을 하루 종일 이벤트로 분할 하는 일정 항목을 보았을 때의 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-277">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="d79fe-278">두 개의 추가 기능에서 리본의 같은 그룹에 단추를 추가 하면 Outlook이 충돌 하는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-278">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="d79fe-279">사용자가 게스트 사용자와 일정을 공유할 수 없는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-279">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-280">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-280">PowerPoint</span></span>

- <span data-ttu-id="d79fe-281">프레젠테이션 영역에서 확대 및 축소 된 선택 윤곽 및 마우스 포인터 사이에 간격이 있는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-281">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-282">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-282">Project</span></span>

- <span data-ttu-id="d79fe-283">옵션을 클릭 하면 Project가 중단 되는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-283">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-284">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-284">Word</span></span>

- <span data-ttu-id="d79fe-285">주석의 하이퍼링크가 작동 하지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-285">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="d79fe-286">프레젠테이션 영역에서 확대 및 축소 된 선택 윤곽 및 마우스 포인터 사이에 간격이 있는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-286">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="d79fe-287">일정에 대해 HTML을 WordMail에 붙여 넣는 것이 작동 하지 않는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-287">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="d79fe-288">공동 작성 된 세션의 의견에 회신할 경우 Word가 중지 될 수 있는 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-288">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2006-may-15"></a><span data-ttu-id="d79fe-290">버전 2006: 5월 15일</span><span class="sxs-lookup"><span data-stu-id="d79fe-290">Version 2006: May 15</span></span>
<span data-ttu-id="d79fe-291">*버전 2006(빌드 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-291">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-293">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-293">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-294">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-294">Excel</span></span>

- <span data-ttu-id="d79fe-295">**PDF 연결 설정:** PDF로 연결하고 PDF에서 데이터를 가져오고 새로 고칩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-295">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="d79fe-296">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-296">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a><span data-ttu-id="d79fe-297">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-297">Outlook</span></span>

- <span data-ttu-id="d79fe-298">**원하는 항목만 찾기:** 폴더, 보낸 사람, 날짜, 첨부 정보 등의 옵션을 사용하여 검색 범위를 좁힙니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-298">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-299">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-299">PowerPoint</span></span>

- <span data-ttu-id="d79fe-300">**이어폰이 원격 조정 기능을 수행하여 클릭커가 필요하지 않습니다.** Surface Earbuds를 사용하여 PowerPoint 프레젠테이션을 컨트롤합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-300">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="d79fe-301">중요: 제스처를 사용하여 프레젠테이션을 제어하려면 Windows 10용 Surface Audio 앱에서 Surface Earbuds를 페어링해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-301">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="d79fe-302">Windows 10에서 Surface Audio 앱을 시작하는 방법에 대한 지침은 여기에서 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-302">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="d79fe-303">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-303">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a><span data-ttu-id="d79fe-304">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-304">Word</span></span>

- <span data-ttu-id="d79fe-305">**민감도 레이블 자동 적용 또는 권장:** Office는 감지되는 중요한 콘텐츠에 기반하여 민감도 레이블을 권장하거나 자동으로 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-305">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-308">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-308">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="d79fe-309">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-309">Excel</span></span>
- <span data-ttu-id="d79fe-310">사용자가 병합된 열을 삭제했을 때 성능시간이 향상되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-310">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="d79fe-311">사용 가능한 프린터 목록에 프린터 이름이 중복되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-311">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-312">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-312">PowerPoint</span></span>
- <span data-ttu-id="d79fe-313">영어 스위스(QWERTZ) 키보드를 사용하는 경우, 바로 가기 키와 맞춤법 검사가 제대로 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-313">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-314">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-314">Word</span></span>
- <span data-ttu-id="d79fe-315">빈 문서에 새 메모를 추가해도 아무 작업도 수행하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-315">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="d79fe-316">100개 이상의 항목을 포함하는 문서에 색인을 삽입하거나 업데이트하는 경우, 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-316">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="d79fe-317">사용자 지정 xml 값이 있는 파일이 매우 천천히 열리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-317">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d79fe-318">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d79fe-318">Office Suite</span></span>
- <span data-ttu-id="d79fe-319">라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-319">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2006-may-08"></a><span data-ttu-id="d79fe-322">버전 2006: 5월 8일</span><span class="sxs-lookup"><span data-stu-id="d79fe-322">Version 2006: May 08</span></span>
<span data-ttu-id="d79fe-323">*버전 2006(빌드 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-323">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-325">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-325">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-326">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-326">Excel</span></span>

- <span data-ttu-id="d79fe-327">**대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-327">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-328">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-328">Outlook</span></span>

- <span data-ttu-id="d79fe-329">**즉시 더 나은 결과 얻기:** 이전보다 더 스마트하고, 빠르고, 안정적이 되도록 검색 환경을 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-329">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="d79fe-330">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-330">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="d79fe-331">**대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-331">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-332">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-332">PowerPoint</span></span>

- <span data-ttu-id="d79fe-333">**대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-333">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="d79fe-334">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-334">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="d79fe-335">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-335">Word</span></span>

- <span data-ttu-id="d79fe-336">**대화에서 애니메이션 GIF 사용:** 애니메이션 GIF가 이제 Office 편집기에서 지원됩니다. 이제 문서가 더욱 돋보입니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-336">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-339">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-339">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="d79fe-340">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d79fe-340">Office Suite</span></span>

- <span data-ttu-id="d79fe-341">OS를 종료하면 InTune을 통한 Office 365 ProPlus 배포가 일시 중지되는 문제를 조사하고 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-341">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2005-may-01"></a><span data-ttu-id="d79fe-343">버전 2005: 5월 1일</span><span class="sxs-lookup"><span data-stu-id="d79fe-343">Version 2005: May 01</span></span>
<span data-ttu-id="d79fe-344">*버전 2005 (빌드 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-344">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-346">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-346">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d79fe-347">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-347">Outlook</span></span>

- <span data-ttu-id="d79fe-348">**전자 메일의 개선된 링크:** 파일에 대한 링크를 포함할 때 파일 이름이 URL로 바뀝니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-348">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="d79fe-349">모든 받는 사람이 액세스 권한을 갖도록 권한을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-349">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="d79fe-350">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-350">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-353">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-353">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-354">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-354">Excel</span></span>

- <span data-ttu-id="d79fe-355">차트 데이터 표에서 날짜 축에 있는 값을 잘못 렌더링할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-355">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="d79fe-356">페이지 레이아웃이나 페이지 나누기 미리 보기를 실행한 후에 페이지 나누기를 해제하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-356">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="d79fe-357">계열 데이터가 있는 열을 숨기거나 숨기기를 해제한 후에 차트 선 스타일이 손실될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-357">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="d79fe-358">필터링된 목록에 열을 삽입하면 예상보다 시간이 오래 걸립니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-358">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="d79fe-359">레거시 "공유 통합 문서" 모드를 사용하여 통합 문서의 새 시트에 변경 내용을 나열할 때 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-359">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="d79fe-360">"음수이면 반전" 옵션을 사용하도록 설정한 경우 피벗 차트에서 사용자 지정 서식이 저장되지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-360">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="d79fe-361">"음수이면 반전" 옵션을 선택한 경우 피벗 차트에서 단일 데이터 요소에 대한 사용자 지정 서식이 저장되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-361">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="d79fe-362">이 변경 사항으로 CSV 파일에 '@' 문자가 업로드되어 '@' 문자 다음 문자열이 수식으로 변환되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-362">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="d79fe-363">SEQUENCE 함수에서 10진수 값이 올바르게 반올림되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-363">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-364">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-364">Outlook</span></span>

- <span data-ttu-id="d79fe-365">사용자가 Outlook 데스크톱 클라이언트에서 클릭한 매우 긴 안전 링크가 잘려서 로드되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-365">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="d79fe-366">서버와 동기화할 때 DBCS(더블 바이트 문자 집합) 문자를 포함하는 이름의 Outlook 폴더가 간헐적으로 사라지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-366">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="d79fe-367">이 문제를 해결하기 위해서 Outlook을 IMAP 계정으로 구성하고 로캘이 일본어로 설정된 시스템에서 실행해야 했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-367">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-368">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-368">PowerPoint</span></span>

- <span data-ttu-id="d79fe-369">사용자가 메모를 게시하지 않고 작성하고 메모 창을 닫은 다음, 새 창을 열어 여러 슬라이드를 탐색한 후 창을 닫고, 마지막으로 원본 프레젠테이션에서 메모 창을 다시 열 때 초안 메모를 사용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-369">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-370">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-370">Project</span></span>

- <span data-ttu-id="d79fe-371">Project가 Project Web App에 연결되어 있고 소수 구분 기호가 쉼표인 경우, 지연 시간이 추가되면 TaskDependencies Add 메서드가 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-371">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-372">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-372">Word</span></span>

- <span data-ttu-id="d79fe-373">공동 작업 모드에서 문서에 메모를 삽입할 때 항상 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-373">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="d79fe-374">이 변경 내용으로 @멘션을 클릭하면 사용자 카드가 깜빡이는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-374">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="d79fe-375">초안 메모가 포함된 문서를 닫을 때 초안 메모를 저장하지 않고 문서를 닫을지 묻는 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-375">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="d79fe-376">이 메시지를 취소하면 문서를 열어두지 않고 닫습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-376">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="d79fe-377">게시된 메모를 번역하면 "번역된 텍스트 삽입 실패"라는 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-377">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="d79fe-378">웹 보기/몰입형 리더에서 힌트를 클릭하면 이미 보기에 있더라도 맨 위로 스크롤됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-378">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="d79fe-379">이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-379">This has been fixed.</span></span>
- <span data-ttu-id="d79fe-380">매크로가 포함된 파일을 새 이름으로 저장하려고 하면 사용자가 입력한 내용에 상관없이 파일이 .docx 확장명과 파일 이름 WRO0004.docx로 저장되어 문서를 사용할 수 없게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-380">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)


## <a name="version-2005-april-24"></a><span data-ttu-id="d79fe-382">버전 2005: 4월 24일</span><span class="sxs-lookup"><span data-stu-id="d79fe-382">Version 2005: April 24</span></span>
<span data-ttu-id="d79fe-383">*버전 2005(빌드 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-383">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-385">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-385">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-386">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-386">Excel</span></span>
- <span data-ttu-id="d79fe-387">이 변경 사항은 LINEST 함수가 올바른 값을 반환하는 경우에도 차트 추세선 R 제곱값(강제적인 y 절편)이 올바르지 않은 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-387">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="d79fe-388">이 변경 사항은 사용자 지정된 차트 추세선 서식이 항상 저장되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-388">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-389">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-389">Outlook</span></span>
- <span data-ttu-id="d79fe-390">Office 리본에서 그룹 일정의 분류 버튼이 비활성화되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-390">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="d79fe-391">구현되거나 작동하지 않는 그룹 폴더가 있는 엔터프라이즈 고객이 있는 경우 Outlook에 "응답하지 않음" 메시지가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-391">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-392">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-392">PowerPoint</span></span>
- <span data-ttu-id="d79fe-393">별표(\*) 기호 위로 마우스를 가져가면 문서를 업데이트할 마지막 사람의 사용자 이름과 날짜가 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-393">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-394">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-394">Word</span></span>
- <span data-ttu-id="d79fe-395">"책갈피 표시" 옵션을 사용하도록 설정하면 책갈피가 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-395">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="d79fe-396">이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-396">This has been fixed.</span></span>
- <span data-ttu-id="d79fe-397">이 변경 사항은 "값 대신 필드 코드 표시" 옵션을 사용하도록 설정한 경우 하이퍼링크가 포함된 텍스트를 표시할 수 없는 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-397">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)


## <a name="version-2005-april-17"></a><span data-ttu-id="d79fe-399">버전 2005: 4월 17일</span><span class="sxs-lookup"><span data-stu-id="d79fe-399">Version 2005: April 17</span></span>
<span data-ttu-id="d79fe-400">*버전 2005(빌드 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-400">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-402">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-402">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-403">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-403">Excel</span></span>
- <span data-ttu-id="d79fe-404">차트에 사용되는 사용자 지정 오차 막대 대화 상자에서 셀 참조 편집 컨트롤의 크기를 늘렸습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-404">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="d79fe-405">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-405">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="d79fe-406">인쇄할 때 양식 컨트롤의 확인란 크기 조정에 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-406">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="d79fe-407">경우에 따라 Application.Evaluate(VBA)가 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-407">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="d79fe-408">이와 같이 변경하면 CF(조건부 서식) 정보가 제대로 파일에 저장되지 않는 문제를 해결할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-408">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="d79fe-409">OneNote</span><span class="sxs-lookup"><span data-stu-id="d79fe-409">OneNote</span></span>
- <span data-ttu-id="d79fe-410">줄 바꿈이 세로 탭으로 저장되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-410">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-411">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-411">Outlook</span></span>
- <span data-ttu-id="d79fe-412">사용자가 개인 연락처 그룹을 모임 참석자로 추가할 수 없게 하는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-412">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="d79fe-413">2개월 넘게 참석하지 않은 모임의 제목이 일정 정리에 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-413">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="d79fe-414">대규모 HTML 메시지를 전달할 때 사용자에게 잘린 메시지 본문이 표시되던 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-414">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="d79fe-415">그룹 정책을 통해 S/MIME 기본 서명 구성을 적용하는 기능이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-415">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="d79fe-416">사용자의 기본 사서함 이외의 사서함을 위해 만든 삭제 규칙이 유효하지 않게 되는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-416">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="d79fe-417">암호화된 메시지를 전달할 때 첨부 파일이 삭제되는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-417">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-418">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-418">Project</span></span>
- <span data-ttu-id="d79fe-419">양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChange 이벤트가 실행됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-419">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="d79fe-420">SharePoint 작업 목록에 연결된 프로젝트에서 보드 상태 필드를 변경하면 Project가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-420">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="d79fe-421">이전 버전의 Project에서 만든 프로젝트를 저장하면 Project가 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-421">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)


## <a name="version-2004-april-10"></a><span data-ttu-id="d79fe-423">버전 2004: 4월 10일</span><span class="sxs-lookup"><span data-stu-id="d79fe-423">Version 2004: April 10</span></span>
<span data-ttu-id="d79fe-424">*버전 2004(빌드 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-424">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-426">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-426">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="d79fe-427">Access</span><span class="sxs-lookup"><span data-stu-id="d79fe-427">Access</span></span>

- <span data-ttu-id="d79fe-428">**테이블 표시 대화 상자를 사용하지 않고 작업 창으로 바로 이동한 후 관계 및 쿼리에 테이블을 간단하게 추가:** 네 개의 탭을 클릭하고, 여러 이름을 한번에 선택하고, 텍스트를 검색하고, 작업 중에 열어 놓은 작업 창에서 끌어와 테이블 및 쿼리를 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-428">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="d79fe-429">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-429">Excel</span></span>

- <span data-ttu-id="d79fe-430">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="d79fe-430">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="d79fe-431">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="d79fe-431">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-432">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-432">Outlook</span></span>

- <span data-ttu-id="d79fe-433">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="d79fe-433">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="d79fe-434">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="d79fe-434">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="d79fe-435">**전자 메일로 사진을 보낼 때 선명도를 높게 유지:.** 새 Outlook 설정을 사용하여 사진을 전자 메일 콘텐츠에 첨부해서 보낼 때 압축을 제한할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-435">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-436">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-436">PowerPoint</span></span>

- <span data-ttu-id="d79fe-437">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="d79fe-437">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="d79fe-438">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="d79fe-438">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="d79fe-439">**발표하는 동안 변경 내용 동기화:** 프레젠테이션이 슬라이드 쇼 모드에 있더라도 내용이 변경될 때마다 동기화됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-439">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-440">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-440">Word</span></span>

- <span data-ttu-id="d79fe-441">**M365 Premium 콘텐츠 선택기:** 문서에 생기를 불어넣어 보세요!</span><span class="sxs-lookup"><span data-stu-id="d79fe-441">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="d79fe-442">로열티가 없는 수천 개의 이미지, 아이콘, 스티커를 탐색하세요. [자세한 정보](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="d79fe-442">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="d79fe-443">**비공개 복사본에 주석 달기:** 공유 문서의 비공개 복사본을 만들어 나만 볼 수 있는 필기 메모를 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-443">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="d79fe-444">시작하려면 보기 > 비공개 복사본 만들기로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-444">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-447">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-447">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d79fe-448">Access</span><span class="sxs-lookup"><span data-stu-id="d79fe-448">Access</span></span>

- <span data-ttu-id="d79fe-449">작업창에서 표 크기 조정 및 새로 고침과 관련된 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-449">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="d79fe-450">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-450">Excel</span></span>

- <span data-ttu-id="d79fe-451">시트의 셀 범위를 선택하면 하나의 셀이 선택되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-451">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="d79fe-452">일부 x축 범위를 사용하여 차트 크기를 줄일 때 Excel이 응답을 중지하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-452">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="d79fe-453">사용자 정의 차트 서식 파일을 기본값으로 삽입하면 열 차트로 저장되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-453">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="d79fe-454">원본 데이터 셀에 캡션이 없는 경우 차트의 데이터 레이블이 빈 채로 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-454">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="d79fe-455">R1C1 셀 참조를 사용 설정하고 Excel 시트를 공동 작성/공유 중일 때 사용자의 현재 상태 아이콘에 마우스를 올리면 R1C1 모드에서 셀 참조가 활성으로 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-455">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-456">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-456">Outlook</span></span>

- <span data-ttu-id="d79fe-457">가끔 전자 메일 메시지의 범주가 사라지는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-457">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="d79fe-458">대리인이 다른 공유 사서함 컴퓨터의 다른 폴더 계층 구조를 볼 수 있었던 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-458">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="d79fe-459">사용자가 조직 양식의 속성을 보려고 할 때 작동 중단이 발생하는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-459">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="d79fe-460">컴퓨터의 표준 시간대를 변경할 때 일부 미리 알림이 발송되지 않았던 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-460">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-461">PowerPoint</span></span>

- <span data-ttu-id="d79fe-462">이 변경 내용을 적용하면 PowerPoint 또는 Word에 OLE 개체로 포함된 레거시 Excel 차트를 렌더링할 때 가끔 차트 제목이 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-462">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="d79fe-463">Excel에서 PowerPoint로 텍스트를 복사하면 그 서식이 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-463">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="d79fe-464">이 변경 내용을 적용하면 '단어 단위로' 옵션을 사용한 특수 문자 찾기가 가끔 제대로 작동하지 않았던 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-464">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-465">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-465">Project</span></span>

- <span data-ttu-id="d79fe-466">실제 작업 시간을 보호하는 설정이 설정된 경우 사용자가 기간별 초기 작업 시간을 입력할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-466">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-467">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-467">Word</span></span>

- <span data-ttu-id="d79fe-468">이 변경 내용을 적용하면 힌트 위에 커서를 놓아도 해당 카드가 강조 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-468">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="d79fe-469">이 변경 내용을 적용하면 올가미 선택 도구를 사용할 때 그룹 지정된 도형 안의 텍스트가 일시적으로 사라지는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-469">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="d79fe-470">이 변경 내용을 적용하면 PowerPoint 또는 Word에 OLE 개체로 포함된 레거시 Excel 차트를 렌더링할 때 가끔 차트 제목이 표시되지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-470">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="d79fe-471">두 페이지 보기에서 댓글을 작성할 때 댓글 앵커가 가끔 보이지 않는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-471">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="d79fe-472">단락의 스타일이 목록에 연결된 스타일의 상위 항목인 경우 해당 목록의 번호 매기기가 분실되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-472">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-march-27"></a><span data-ttu-id="d79fe-474">버전 2004: 3월 27일</span><span class="sxs-lookup"><span data-stu-id="d79fe-474">Version 2004: March 27</span></span>
<span data-ttu-id="d79fe-475">*버전 2004(빌드 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-475">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-477">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-477">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d79fe-478">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-478">Outlook</span></span>

- <span data-ttu-id="d79fe-479">**메일 작성 시 @멘션 제안을 사용하지 않는 새 옵션:** @멘션 선택기가 유용하기보다는 불편하게 느껴지나요?</span><span class="sxs-lookup"><span data-stu-id="d79fe-479">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="d79fe-480">원하는 경우 바로 지금 비활성화할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-480">Now you can turn it off if you prefer.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-483">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-483">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d79fe-484">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-484">Outlook</span></span>
- <span data-ttu-id="d79fe-485">첨부 파일 도구에서 "클라우드에 저장" 단추가 누락되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-485">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="d79fe-486">회신하는 메시지에 대한 소유자 권한이 없는 경우 검사기 창에서 디지털 권한 관리 메시지에 회신할 때 사용자가 서명을 추가할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-486">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="d79fe-487">사용자가 웹 위치에서 이전에 만든 모임에 추가 첨부 파일을 추가할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-487">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-488">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-488">PowerPoint</span></span>
- <span data-ttu-id="d79fe-489">이 변경 내용을 적용하면 이모지가 포함된 PowerPoint 파일을 저장할 때 실패할 수 있는 오류가 수정됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-489">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-490">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-490">Project</span></span>
- <span data-ttu-id="d79fe-491">'CustomFieldValueListGetItem'이 실행되고 사용자 지정 필드에 대한 조회 테이블이 없는 경우 빈 조회 테이블이 없어도 생성되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-491">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-492">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-492">Word</span></span>
- <span data-ttu-id="d79fe-493">이 변경 내용은 보기 메뉴에서 여러 페이지를 선택한 경우 메모 창이 공백으로 표시될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-493">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-march-20"></a><span data-ttu-id="d79fe-495">버전 2004: 2020년 3월</span><span class="sxs-lookup"><span data-stu-id="d79fe-495">Version 2004: March 20</span></span>
<span data-ttu-id="d79fe-496">*버전 2004(빌드 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-496">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-498">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-498">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d79fe-499">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-499">Outlook</span></span>

- <span data-ttu-id="d79fe-500">**완전히 새로워진 일정:** 지난 해, 당사는 새로워진 메일 환경을 제공했으며, 올해에는 일정이 새롭게 바뀌었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-500">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="d79fe-501">업데이트가 새로 제공되지만 노련한 Outlook 사용자에게는 익숙하므로 바로 시작하여 생산성을 높일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-501">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="d79fe-502">**그룹의 데이터 보호 지원:** 그룹을 만들 때 선택한 민감도 레이블이 그룹 전자 메일, 문서, 팀 사이트에 적용됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-502">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-503">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-503">PowerPoint</span></span>

- <span data-ttu-id="d79fe-504">**슬라이드 쇼 중에 슬라이드 업데이트:** 프레젠테이션을 진행하는 동안 다른 작성자가 변경한 슬라이드를 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-504">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-507">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-507">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-508">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-508">Excel</span></span>

- <span data-ttu-id="d79fe-509">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-509">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-510">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-510">Outlook</span></span>

- <span data-ttu-id="d79fe-511">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-511">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="d79fe-512">이 변경 사항은 초안 전자 메일에 대한 최신 변경 내용이 업데이트되지 않은 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-512">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="d79fe-513">파일을 마우스 오른쪽 단추로 클릭 및 '보내기' 사용이 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-513">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="d79fe-514">사용자가 주소록에 대한 검색 경로를 사용자 지정한 경우 Outlook의 이름 확인 범위가 GAL(전체 주소 목록)을 포함하지 않고 사용자 지정 경로로 제한되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-514">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="d79fe-515">반환된 검색 결과 집합 내에서 범주별로 결과를 정렬하면 범주 색이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-515">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-516">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-516">Project</span></span>

- <span data-ttu-id="d79fe-517">사용자가 일정 그룹 내의 작업 리본에서 찾은 "비활성화" 단추를 클릭하면 'ProjectBeforeTaskChange' VBA(Visual Basic for Applications) 이벤트가 실행되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-517">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="d79fe-518">양식 유형 보기 내에서 선행 작업이나 후속 작업 세부 정보를 설정한 경우 ProjectBeforeTaskChange VBA(Visual Basic for Applications) 이벤트가 변경 내용을 캡처하지 않는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-518">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="d79fe-519">예를 들어 종속성을 삭제하고 양식에서 확인을 클릭한 경우 이벤트가 실행되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-519">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="d79fe-520">이 동작이 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-520">This behavior has been fixed.</span></span>

- <span data-ttu-id="d79fe-521">날짜 변경과 같이 변경 후에 ACWP (수행된 작업의 실제 비용)의 최신 값이 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-521">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="d79fe-522">MRU(최근 사용한 항목) 메뉴를 사용하여 프로젝트를 열면 프로젝트 파일이 읽기/쓰기 권한으로 열리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-522">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="d79fe-523">이 변경 내용은 시작 날짜와 시간을 사용하여 수동 작업을 만들었지만 기간을 지정하지 않은 경우 타임라인에 잘못된 시간이 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-523">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="d79fe-524">회교식 달력을 사용하여 타임라인을 인쇄하면 인쇄 보기에서 한 달을 건너뛰거나 중복되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-524">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="d79fe-525">이 변경 사항은 팀 플래너에서 GDI 개체를 사용하여 작업하면 GDI 개체가 초과 할당되고 메모리가 부족해지는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-525">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-526">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-526">Word</span></span>

- <span data-ttu-id="d79fe-527">댓글에 대한 게시 기능이 사용하지 않도록 설정되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-527">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="d79fe-528">이 변경 사항은 잘못된 프로토콜 정보를 사용하여 이미지를 처리할 때 발생하는 지연을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-528">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="d79fe-529">또한 계정 관리자가 메시지를 발송하지 않아 타사 애플리케이션이 중단되는 문제를 해결하며,</span><span class="sxs-lookup"><span data-stu-id="d79fe-529">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="d79fe-530">문서에 없는 제목 스타일을 사용하여 목차를 업데이트할 때 발생하는 문제도 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-530">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="d79fe-531">문서를 보낼 때 Word 문서에 저장된 디지털 서명이 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-531">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2004-march-13"></a><span data-ttu-id="d79fe-533">버전 2004: 3월 13일</span><span class="sxs-lookup"><span data-stu-id="d79fe-533">Version 2004: March 13</span></span>
<span data-ttu-id="d79fe-534">*버전 2004 (빌드 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-534">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-536">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-536">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="d79fe-537">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-537">Excel</span></span>
- <span data-ttu-id="d79fe-538">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-538">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="d79fe-539">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-539">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="d79fe-540">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-540">PowerPoint</span></span>
- <span data-ttu-id="d79fe-541">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-541">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="d79fe-542">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-542">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="d79fe-543">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-543">Word</span></span>
- <span data-ttu-id="d79fe-544">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-544">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="d79fe-545">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-545">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-548">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-548">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="d79fe-549">Access</span><span class="sxs-lookup"><span data-stu-id="d79fe-549">Access</span></span>
- <span data-ttu-id="d79fe-550">Access의 다른 나라 버전이 사용자 인터페이스에서 영어 문자열을 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-550">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="d79fe-551">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-551">Excel</span></span>
- <span data-ttu-id="d79fe-552">다양한 셀을 프로그래밍 방식으로 편집할 때 사용자에게 발생할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-552">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="d79fe-553">일본어 환경으로 csv 파일을 열 때 발생할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-553">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-554">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-554">Outlook</span></span>
- <span data-ttu-id="d79fe-555">메일에 첨부 파일을 추가하거나 저장할 때 파일을 끌어다 놓는 방법을 사용하는 경우(메뉴를 사용하는 것과 반대로) 파일의 "최종 수정 날짜"가 업데이트되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-555">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="d79fe-556">사용자가 검색 단추를 클릭하는 대신 상세 검색 창에서 Enter 키를 누르면 검색이 시작되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-556">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="d79fe-557">"사용 가능한 경우 사용자 사진 표시" 옵션을 사용하지 않도록 설정한 경우 검색에서 사용자에 대한 정보가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-557">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="d79fe-558">Project</span><span class="sxs-lookup"><span data-stu-id="d79fe-558">Project</span></span>
- <span data-ttu-id="d79fe-559">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-559">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="d79fe-560">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-560">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-561">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-561">Word</span></span>
- <span data-ttu-id="d79fe-562">메모를 입력하거나 편집하고 Ctrl+A를 사용할 때 메모 카드 내에서 텍스트를 선택하는 대신 캔버스에서 텍스트를 선택하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-562">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="d79fe-563">빠른 인쇄를 사용하여 인쇄한 후에 편집하려고 할 때 문서의 단어 맞춤이 스크램블되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-563">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="d79fe-564">두 문서를 하나의 문서로 병합할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-564">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="d79fe-565">수식 관련 수정을 표시할 때 파일을 저장하면 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-565">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-march-06"></a><span data-ttu-id="d79fe-567">버전 2003: 3월 6일</span><span class="sxs-lookup"><span data-stu-id="d79fe-567">Version 2003: March 06</span></span>
<span data-ttu-id="d79fe-568">*버전 2003(빌드 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-568">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-570">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-570">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d79fe-571">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-571">Outlook</span></span>

- <span data-ttu-id="d79fe-572">Outlook Web Access로 규칙을 만들 때 Exchange 서버에 유지되지 않아 충돌이 발생하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-572">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="d79fe-573">어두운 모드의 Outlook에서 '보낸 사람:' 입력란에 드롭다운 목록이 표시되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-573">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="d79fe-574">사용자가 다른 응용 프로그램에서 파일을 열 때 파일 탐색기를 통해 파일을 전자 메일 메시지에 첨부할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-574">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-575">PowerPoint</span></span>

- <span data-ttu-id="d79fe-576">축소판 그림 위로 마우스를 가져가면 권장 축소판 그림이 깜박이는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-576">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="d79fe-577">경우에 따라 PowerPoint가 중단될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-577">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-578">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-578">Word</span></span>

- <span data-ttu-id="d79fe-579">편집에 대해 보호된 문서의 비교 기능 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-579">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d79fe-580">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d79fe-580">Office Suite</span></span>

- <span data-ttu-id="d79fe-581">Word/Excel/PowerPoint에서 UPN(사용자 계정 이름)이 더 이상 대소문자를 구분하지 않아 SharePoint에서 파일 작업시 오류가 줄어듭니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-581">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="d79fe-582">File \ Options 대화 상자의 '확인'단추가 회색으로 표시되고 기능에는 영향을 미치지 않는 외관상의 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-582">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

## <a name="version-2003-february-28"></a><span data-ttu-id="d79fe-585">버전 2003: 2월 28일</span><span class="sxs-lookup"><span data-stu-id="d79fe-585">Version 2003: February 28</span></span>
<span data-ttu-id="d79fe-586">*버전 2003 (빌드 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-586">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-588">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-588">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d79fe-589">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-589">Outlook</span></span>

- <span data-ttu-id="d79fe-590">**IT 관리자에 대한 인시던트 알림:** Microsoft 365 테넌트 전역 관리자 및 Office 앱 관리자는 Windows용 Outlook의 새로운 오른쪽 패널 알림을 통해 사용자에게 영향을 주는 Outlook 및 O365 Exchange 인시던트에 대한 알림을 받습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-590">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="d79fe-591">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-591">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="d79fe-592">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-592">PowerPoint</span></span>

- <span data-ttu-id="d79fe-593">**개선된 잉크를 통한 도형 다이어그램 작성 경험:** 더 나은 다이어그램을 그리고 Office 개체를 조작할 수 있도록 변환합니다. [자세히 알아보기](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="d79fe-593">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-596">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-596">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d79fe-597">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-597">Excel</span></span>

- <span data-ttu-id="d79fe-598">인쇄 미리 보기에서 슬라이서의 텍스트 크기가 제대로 조정되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-598">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-599">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-599">Outlook</span></span>

- <span data-ttu-id="d79fe-600">메일에 첨부 파일을 추가하거나 저장할 때 파일을 끌어다 놓는 방법을 사용하는 경우(메뉴를 사용하는 것과 반대로) 파일의 "최종 수정 날짜"가 업데이트되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-600">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-601">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-601">Word</span></span>

- <span data-ttu-id="d79fe-602">메모 카드를 탭할 때 메모 편집 상자에 포커스가 표시되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-602">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="d79fe-603">수식에 텍스트 콘텐츠 컨트롤과 같은 컨트롤을 삽입한 다음 파일을 저장하고 열면 읽을 수 없는 콘텐츠 오류가 발생합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-603">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="d79fe-604">이전에 암호로 보호된 파일을 클라우드 저장소에 저장하지 못하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-604">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d79fe-605">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d79fe-605">Office Suite</span></span>

- <span data-ttu-id="d79fe-606">동일한 SharePoint 라이브러리의 Word/Excel/PowerPoint에서 여러 문서를 열 때 첫 번째로 열린 문서만 정책 준수에 대한 검사가 이뤄지는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-606">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-february-21"></a><span data-ttu-id="d79fe-608">버전 2003: 2월 21일</span><span class="sxs-lookup"><span data-stu-id="d79fe-608">Version 2003: February 21</span></span>
<span data-ttu-id="d79fe-609">*버전 2003 (빌드 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-609">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-611">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-611">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="d79fe-612">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d79fe-612">Office Suite</span></span>

- <span data-ttu-id="d79fe-613">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="d79fe-613">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-616">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-616">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="d79fe-617">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-617">Excel</span></span>
- <span data-ttu-id="d79fe-618">피벗 테이블 측정의 이름을 바꿀 때 사용자가 겪을 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-618">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="d79fe-619">VBA 매크로를 사용하여 범위의 내용을 지우면 사용자가 경험할 수 있는 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-619">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="d79fe-620">사용자가 리본과 상호 작용하는 매크로를 실행할 때 UI가 깜박이는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-620">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="d79fe-621">파일의 첫 단어가 TABLE 인 경우 CSV 파일이 잘못 로드되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-621">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="d79fe-622">확대/축소 수준이 다른 두 통합 문서 간에 전환할 때 사용자가 충돌을 경험할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-622">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-623">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-623">Outlook</span></span>
- <span data-ttu-id="d79fe-624">Outlook이 밤새 실행 중인 상태에서 사용자가 공용 폴더 메시지를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-624">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="d79fe-625">Gmail 계정 추가의 인증 작업 과정에서 권한 페이지의 '허용' 및 '거부' 버튼이 비활성화되는 경합 상태를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-625">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="d79fe-626">로깅이 꺼져 있어도 일부 시나리오에서 Outlook이 예기치 않게 로깅 출력을 생성하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-626">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-627">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-627">Word</span></span>
- <span data-ttu-id="d79fe-628">마우스 포인터가 주석 카드 위로 마우스를 가져갈 때 주석 카드가 항상 강조 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-628">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="d79fe-629">문서 공동 작성 세션 중에 주석 카드에 직접 이미지를 추가하면 태그가 추가될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-629">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="d79fe-630">이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-630">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d79fe-631">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d79fe-631">Office Suite</span></span>
- <span data-ttu-id="d79fe-632">Word/Excel/PowerPoint 문서와 함께 Multichoice/ Lookup/Managed-metadata 속성을 사용하고 SharePoint 문서 라이브러리에 저장할 때, 이러한 속성은 이전에 255 자로 제한되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-632">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="d79fe-633">이러한 속성이 255자를 초과하면 해당 문서를 저장할 수 없었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-633">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="d79fe-634">이 변경으로 이 제한이 2048자로 늘었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-634">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2003-february-14"></a><span data-ttu-id="d79fe-636">버전 2003: 2월 14일</span><span class="sxs-lookup"><span data-stu-id="d79fe-636">Version 2003: February 14</span></span>
<span data-ttu-id="d79fe-637">*버전 2003 (빌드 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-637">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-639">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-639">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d79fe-640">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-640">Outlook</span></span>

- <span data-ttu-id="d79fe-641">\*\*종속적인 Wi-Fi 네트워크에 대한 새로운 경험: \*\* 로그인하기 위해 웹 페이지가 필요한 Wi-Fi 네트워크에 가입한 적이 있습니까?</span><span class="sxs-lookup"><span data-stu-id="d79fe-641">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="d79fe-642">이제 Outlook이 이를 감지하여 연결하는 데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-642">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-643">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-643">Word</span></span>

- <span data-ttu-id="d79fe-644">\*\*그리기 도구 상자에서 잉크 편집기 찾기: \*\* 그리기를 선택한 다음 잉크 편집기 펜을 선택하여 손가락이나 디지털 펜으로 문서를 편집하십시오.</span><span class="sxs-lookup"><span data-stu-id="d79fe-644">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="d79fe-645">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="d79fe-645">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="d79fe-646">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d79fe-646">Office Suite</span></span>

- <span data-ttu-id="d79fe-647">**더 명확한 상태 표시줄 아이콘:** 상태 표시줄 아이콘을 쉽게 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-647">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-650">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-650">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d79fe-651">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-651">Outlook</span></span>

- <span data-ttu-id="d79fe-652">사용자가 "약속 있음/없음 옵션" 일정 권한 대화 상자에 액세스하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-652">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="d79fe-653">다른 시간대에서 보낸 되풀이 모임 인스턴스를 열 때 "죄송합니다. 이 항목을 여는 데 문제가 있습니다"라는 경고가 표시되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-653">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="d79fe-654">해당 메시지에서 첨부 파일을 끌어서 놓은 후 사용자가 .msg 파일을 다시 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-654">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="d79fe-655">첨부 파일 이름에 괄호가 포함된 경우 Outlook에서 OneDrive로 파일 첨부 파일을 업로드한 후 파일 이름이 변경될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-655">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-656">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-656">PowerPoint</span></span>

- <span data-ttu-id="d79fe-657">Excel 차트가 포함된 PowerPoint 또는 Word에서 문서를 저장하지 못하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-657">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-658">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-658">Word</span></span>

- <span data-ttu-id="d79fe-659">PDF로 내보낼 때 문서의 그림이 투명성을 잃는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-659">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-february-07"></a><span data-ttu-id="d79fe-661">버전 2002: 2월 7일</span><span class="sxs-lookup"><span data-stu-id="d79fe-661">Version 2002: February 07</span></span>
<span data-ttu-id="d79fe-662">*버전 2002 (빌드 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="d79fe-662">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="d79fe-664">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="d79fe-664">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="d79fe-665">Access</span><span class="sxs-lookup"><span data-stu-id="d79fe-665">Access</span></span>

- <span data-ttu-id="d79fe-666">**Query Designer, SQL 보기 및 관계 창에서 생산성을 향상시킬 수 있습니다.** 테이블을 마우스 오른쪽 단추로 클릭하여 열고 디자인하고 크기를 조정하고 숨겨보세요.</span><span class="sxs-lookup"><span data-stu-id="d79fe-666">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="d79fe-667">SQL 보기에서 텍스트를 검색하고 바꾸세요.</span><span class="sxs-lookup"><span data-stu-id="d79fe-667">Search and replace text in SQL View.</span></span> <span data-ttu-id="d79fe-668">관계 창에서 테이블을 여러 개 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="d79fe-668">Select multiple tables in the Relationships window.</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="d79fe-671">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="d79fe-671">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d79fe-672">Access</span><span class="sxs-lookup"><span data-stu-id="d79fe-672">Access</span></span>

- <span data-ttu-id="d79fe-673">이 업데이트는 ADODB 사용시 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-673">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="d79fe-674">VB 코드의 레코더 개체에서 오류가 잘못 보고될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-674">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="d79fe-675">이 업데이트는 Microsoft Access에서 연결된 SQL Server 테이블의 ID 열이 식별되지 않아서 행이 올바르지 않게 삭제된 것으로 보고되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-675">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="d79fe-676">Excel</span><span class="sxs-lookup"><span data-stu-id="d79fe-676">Excel</span></span>

- <span data-ttu-id="d79fe-677">동적 배열에서 Text To Columns를 사용할 때 Excel이 중단되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-677">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="d79fe-678">Outlook</span><span class="sxs-lookup"><span data-stu-id="d79fe-678">Outlook</span></span>

- <span data-ttu-id="d79fe-679">월 보기를 사용하여 일정을 스크롤할 때 이전 일정 이벤트가 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-679">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="d79fe-680">Citrix 환경에서 30개 이상의 캘린더를 볼 때 사용자에게 충돌이 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-680">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d79fe-681">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d79fe-681">PowerPoint</span></span>

- <span data-ttu-id="d79fe-682">이벤트 처리기가 실행 중인 경우, 파일을 닫은 후 PowerPoint에서 프레젠테이션 모음의 해당 파일을 즉시 제거하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-682">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="d79fe-683">따라서 개체 모델에서 보고한 열려 있는 프레젠테이션 수가 올바르지 않아 PowerPoint가 종료되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-683">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="d79fe-684">형광펜 관련 문제를 해결했습니다. 어두운 형광펜 색상의 텍스트는 흑백 모드에서 검은 색으로 인쇄됩니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-684">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="d79fe-685">Word</span><span class="sxs-lookup"><span data-stu-id="d79fe-685">Word</span></span>

- <span data-ttu-id="d79fe-686">목차를 업데이트하고 스크롤하면 때때로 문서 위에 회색 영역이 표시될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-686">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="d79fe-687">문서를 공동 작성하는 경우 루트 메모의 초안 버전이 유지되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-687">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="d79fe-688">메모 카드 간에 앞뒤로 이동할 때 때때로 선택 강조 표시로 처음 선택한 메모가 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-688">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="d79fe-689">메모가 작성되었지만 게시되지 않고 사용자가 파일을 저장하려고 하는 경우 '찾아보기'를 사용하여 파일을 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-689">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="d79fe-690">SlideTrack을 활성화하고 메모 창을 닫으면 Ctrl+Alt+M을 눌러 메모 창을 열지 못할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-690">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="d79fe-691">테이블에 @mention을 추가할 때 '이 문서의 테이블이 손상되었습니다'라는 오류 메시지가 생성될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-691">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d79fe-692">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="d79fe-692">Office Suite</span></span>

- <span data-ttu-id="d79fe-693">노르웨이 니노르스크(nn-no) 교정 도구 패키지가 잘못 설치될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="d79fe-693">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)
