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
ms.openlocfilehash: bc3878099fa34b75437ce800250d711cb0f5bd0c
ms.sourcegitcommit: 568fdf9ae96367ef3a4f601128df80944dd265a7
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 02/10/2021
ms.locfileid: "50173837"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="012bd-103">반기 기업 채널(프리뷰)의 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="012bd-104">이 릴리스 정보에서는 엔터프라이즈용 Microsoft 365 앱, 비즈니스용 Microsoft 365 앱 및 프로젝트 및 Visio용 데스크톱 앱의 구독 버전에 대한 반기별 엔터프라이즈 채널(미리 보기) 업데이트에 포함된 새로운 기능 및 비보안 업데이트에 대한 정보를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="012bd-105">당사는 Microsoft 365 앱에 대한 업데이트 채널을 일부 변경하고 있습니다. 여기에는 새 업데이트 채널 추가(월별 엔터프라이즈 채널) 및 기존 업데이트 채널의 이름 변경 등이 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="012bd-106">자세한 내용은 [이 문서를 참조](https://go.microsoft.com/fwlink/p/?linkid=2127441)하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2008-february-09"></a><span data-ttu-id="012bd-107">버전 2008: 2월 9일</span><span class="sxs-lookup"><span data-stu-id="012bd-107">Version 2008: February 09</span></span>
<span data-ttu-id="012bd-108">*버전 2008 (빌드 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="012bd-108">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="012bd-109">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-111">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="012bd-112">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-112">Excel</span></span>

- <span data-ttu-id="012bd-113">잘못된 파일 특성(만든 시간, 수정된 시간 등)이 있는 UNC 파일을 열 때 Excel이 예기치 않게 닫히는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-113">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="012bd-114">Excel에서 차트를 복사하여 Word 또는 PowerPoint에 붙여넣을 때 소수점 및 천 단위 구분 기호 설정이 수행되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-114">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="012bd-115">매크로가 실행될 때마다 피벗 테이블 범위 형식과 관련된 매크로 실행 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-115">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="012bd-116">시트를 복사하거나 다른 통합 문서로 이동할 때 조건부 서식 규칙이 삭제되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-116">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="012bd-117">앱 부팅 시 시작 화면이 비활성화되었을 때 사용자가 Excel 파일에 민감도 레이블을 적용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-117">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="012bd-118">OneDrive 동기화 폴더에서 클라우드 파일을 여는 중 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-118">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="012bd-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-119">Outlook</span></span>

- <span data-ttu-id="012bd-120">첨부 파일을 추가하거나 저장할 때 Outlook이 산발적으로 작동을 멈추게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-120">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="012bd-121">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-121">PowerPoint</span></span>

- <span data-ttu-id="012bd-122">QAT에서 추가한 글꼴 크기 명령이 업데이트하는 동안 가장 가까운 정의된 글꼴 크기로 자동 완성되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-122">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="012bd-123">'원본 서식 유지' 옵션이 때때로 새 슬라이드 마스터에 복사되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-123">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="012bd-124">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-124">Word</span></span>

- <span data-ttu-id="012bd-125">변경사항 추적에서 Word 문서를 열면 오류 대화상자가 표시될 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-125">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="012bd-126">OneDrive 동기화 폴더에서 클라우드 파일을 여는 중 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-126">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="012bd-127">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-127">Office Suite</span></span>

- <span data-ttu-id="012bd-128">Office에서 파일을 열 수 없는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-128">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="012bd-129">서식 복사를 통해 커넥터에 적용된 스케치된 윤곽선이 포함된 문서가 손상될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-129">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-january-12"></a><span data-ttu-id="012bd-131">버전 2008: 1월 12일</span><span class="sxs-lookup"><span data-stu-id="012bd-131">Version 2008: January 12</span></span>
<span data-ttu-id="012bd-132">*버전 2008(빌드 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="012bd-132">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="012bd-133">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-133">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-135">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="012bd-136">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-136">Excel</span></span>

- <span data-ttu-id="012bd-137">읽기 전용 책을 열면 피벗 테이블 데이터를 더 이상 새로 고칠 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-137">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="012bd-138">이 변경 사항은 다음 문제에 대한 수정 사항을 제공합니다. OneDrive 로컬 동기화 폴더에서 파일을 삽입하면 Excel "개체 삽입"에 올바른 아이콘이 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-138">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="012bd-139">공동 작성 시 새 파일 버전에 대한 알림을 고객이 잘못 받는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-139">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="012bd-140">덮어쓰기 모드에서 IME를 사용하면 추가 문자를 잘못 전달할 수 있는 편집 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-140">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="012bd-141">다중 스레드 재호출 기능과 함께 실시간 데이터를 사용할 때 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-141">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="012bd-142">특정 Windows 보안 공격 방지 설정(SimExec, 호출자 확인)을 사용 중인 경우 Excel이 예기치 않게 시작되지 않거나 닫히는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-142">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="012bd-143">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-143">Outlook</span></span>

- <span data-ttu-id="012bd-144">초안에 저장할 때 SmartLinks의 서식이 손실되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-144">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="012bd-145">정책을 재정의할 때 사유 텍스트를 사용자 지정할 수 있는 방법을 제공하도록 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-145">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="012bd-146">OFT 파일로 저장하면 중국어 문자가 물음표로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-146">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="012bd-147">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-147">PowerPoint</span></span>

- <span data-ttu-id="012bd-148">Slide.Shapes.AddMediaObject2가 레거시 비디오 형식(MPG-1, Mpeg-2)과 충돌하는 VBA 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-148">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="012bd-149">문서 복구 작업 후에도 손상된 PowerPoint 파일이 올바르게 열리지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-149">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="012bd-150">Project</span><span class="sxs-lookup"><span data-stu-id="012bd-150">Project</span></span>

- <span data-ttu-id="012bd-151">특정 방식으로 리소스 윤곽선이 지정된 파일을 열 때 Project가 예기치 않게 종료될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-151">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="012bd-152">Skype</span><span class="sxs-lookup"><span data-stu-id="012bd-152">Skype</span></span>

- <span data-ttu-id="012bd-153">사용자의 TLS-DSK 인증서가 예상 시간에 갱신되지 않고 유효 기간이 12시간 미만인 경우에만 갱신되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-153">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="012bd-154">Office에 대한 라이선스가 아직 없을 때 로그인 후 비즈니스용 Skype UI가 공백으로 표시되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-154">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="012bd-155">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-155">Office Suite</span></span>

- <span data-ttu-id="012bd-156">이렇게 변경하면 레거시 다이어그램이 포함된 파일 열기 관련 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-156">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="012bd-157">이렇게 변경하면 액세스 위반을 초래하는 SVG 예비 프록시의 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-157">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2008-december-08"></a><span data-ttu-id="012bd-159">버전 2008: 12월 8일</span><span class="sxs-lookup"><span data-stu-id="012bd-159">Version 2008: December 08</span></span>
<span data-ttu-id="012bd-160">*버전 2008(빌드 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="012bd-160">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="012bd-161">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-161">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-163">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-163">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="012bd-164">Access</span><span class="sxs-lookup"><span data-stu-id="012bd-164">Access</span></span>

- <span data-ttu-id="012bd-165">ODBC DSN 빌더를 사용할 때 발생하는 오류 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-165">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="012bd-166">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-166">Excel</span></span>

- <span data-ttu-id="012bd-167">피벗 테이블을 Project 계획에서 내보낸 경우 피벗 테이블을 편집할 수 없고 통합 문서를 저장할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-167">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="012bd-168">읽기 전용 모드에서 파일을 열 때 여러 개의 메시지 표시줄이 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-168">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="012bd-169">중복된 열 머리글 값이 많을 때 개요 하위 합계가 작동을 중지할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-169">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="012bd-170">다중 스레드 재계산 중 그룹 정책 개체 업데이트(예: 원격 그룹 정책 새로 고침)가 있을 때 Excel이 작동을 중지하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-170">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="012bd-171">사용자가 255개 이상의 열에서 소계 함수를 사용할 때 Excel이 작동을 중지하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-171">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="012bd-172">콘텐츠를 Excel에서 복사하여 Embed 옵션으로 PowerPoint에 붙여넣을 때 PowerPoint에서 커닝이 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-172">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="012bd-173">PowerPivot의 테이블 프리뷰 및 쿼리 편집기에서 전환되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-173">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="012bd-174">사용자가 SharePoint에서 직접 atomsvc(UTF8+BOM) 파일을 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-174">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="012bd-175">파워 피벗이 탭 구분 기호를 성공적으로 인식하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-175">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="012bd-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-176">Outlook</span></span>

- <span data-ttu-id="012bd-177">작업에 대해 상황 보고서를 보낼 때 받는 사람 필드가 비어 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-177">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="012bd-178">MailItem.BeforeAttachmentAdd 이벤트가 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-178">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="012bd-179">Outlook 이외의 응용 프로그램에서 Outlook 메일을 보낼 때 일부 사용자가 예기치 않게 응용 프로그램을 종료하는 문제가 발생했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-179">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="012bd-180">온라인 모드에서 폴더 간에 여러 메일 항목을 이동할 때 사용자의 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-180">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="012bd-181">IDataObject 작업(예: 끌어서 놓기, 클립보드)에서 첨부 파일에 대한 filetime 포함을 사용하지 않도록 설정할 수 있는 regkey를 추가했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-181">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="012bd-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes 제외됨  1 = (기본값) filetimes 포함됨</span><span class="sxs-lookup"><span data-stu-id="012bd-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="012bd-183">Azure Information Protection의 보호 레이블을 사용하여 메시지에 회신할 때 인라인 이미지를 사라지게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-183">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="012bd-184">Azure Protected Voicemail을 보낼 때 사용자 이름을 전화 번호로 표시하여 Outlook 데스크톱 사용자가 외부 사용자의 음성 메일을 열 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-184">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="012bd-185">OME 구성을 설정하면 서비스 측에서 DecryptAttachmentsForEncryptOnly 옵션이 설정되어 있는데도 Outlook에서 메시지를 암호화하도록 강제하는 관련 없는 첨부 파일이 메일 항목에 추가되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-185">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="012bd-186">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-186">PowerPoint</span></span>

- <span data-ttu-id="012bd-187">사용자가 원본 경로를 로컬 OneDrive 폴더로 변경한 경우 연결된 Excel 차트가 Excel 시트로 잘못 변경되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-187">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="012bd-188">‘Welcome back! 기능으로 인해 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-188">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="012bd-189">Office에서 중단한 위치 픽업'이(가) PowerPoint 에서 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-189">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="012bd-190">Visio</span><span class="sxs-lookup"><span data-stu-id="012bd-190">Visio</span></span>

- <span data-ttu-id="012bd-191">사용자 지정 Visio 스텐실 및 내장 템플릿 모두에 대해 Office 365용 Visio의 커넥터를 사용하여 직선을 생성할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-191">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="012bd-192">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-192">Word</span></span>

- <span data-ttu-id="012bd-193">문서를 HTML 형식으로 저장할 때 긴 링크가 줄바꿈되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-193">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="012bd-194">확장 목록에 알 수 없는 확장명을 가진 상위 설명에 회신할 경우 같은 확장명을 받는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-194">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="012bd-195">메시지가 전달 금지로 설정된 Outlook 에 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-195">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="012bd-196">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-196">Office Suite</span></span>

- <span data-ttu-id="012bd-197">ADAL이 비활성화되었을 때 사용자가 SPO 목록을 가져올 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-197">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-november-10"></a><span data-ttu-id="012bd-199">버전 2008: 11월 10일</span><span class="sxs-lookup"><span data-stu-id="012bd-199">Version 2008: November 10</span></span>
<span data-ttu-id="012bd-200">*버전 2008(빌드 13127.20760)*</span><span class="sxs-lookup"><span data-stu-id="012bd-200">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="012bd-201">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-201">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-203">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-203">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="012bd-204">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-204">Excel</span></span>

- <span data-ttu-id="012bd-205">통합 문서를 로드한 후 특정 함수에 잘못된 결과가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-205">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="012bd-206">XLAM 추가 기능 참조 및 명명된 범위와 관련된 응용 프로그램이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-206">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="012bd-207">차트 데이터 시트가 활성 시트면 범위에 FormulaR1C1 속성 설정에 매크로를 사용할 때 셀 참조가 부정확한 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-207">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="012bd-208">"하나 이상의 수식을 계산하는 동안 Excel 리소스를 모두 사용했습니다" 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-208">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="012bd-209">Office 언어를 스페인어로 설정했을 때 데이터 유효성 검사 목록에 목록의 모든 항목이 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-209">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="012bd-210">OLAP 피벗 테이블을 새로 고칠 때 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-210">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="012bd-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-211">Outlook</span></span>

- <span data-ttu-id="012bd-212">이제 다른 Office 애플리케이션 사용을 비활성화할 필요 없이 Outlook용 IRM(정보 권한 관리)를 사용을 비활성화할 수 있도록 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-212">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="012bd-213">사용자가 대리인에게 편집자 권한을 부여할 수 없게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-213">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="012bd-214">사용자가 검색 결과를 선택하면 응용 프로그램이 예기치 않게 종료되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-214">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="012bd-215">그룹 일정에서 검색이 결과를 반환하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-215">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="012bd-216">대리인이 다른 사서함에서 공유 폴더를 열 때 간헐적으로 오류가 생기는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-216">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="012bd-217">전자 메일의 제목 줄이 비어있는 경우 일부 자동으로 생성된 전자 메일이 이를 빈 본문으로 보내는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-217">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="012bd-218">회신하거나 전달할 때 중국어 메시지의 머리글이 깨져 보이는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-218">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="012bd-219">선택적으로 연결된 환경이 로딩으로부터 웹 추가 기능을 차단하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-219">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="012bd-220">
  [블로그 게시물](https://developer.microsoft.com/ko-KR/office/blogs/outlook-add-ins-and-optional-connected-experiences/)에서 세부 정보 보기</span><span class="sxs-lookup"><span data-stu-id="012bd-220">See details in [blog post](https://developer.microsoft.com/ko-KR/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="012bd-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-221">PowerPoint</span></span>

- <span data-ttu-id="012bd-222">사용자가 다른 슬라이드를 클릭하여 표시할 때까지 Forms 콘텐츠 추가 기능이 삽입 후에 렌더링되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-222">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="012bd-223">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-223">Office Suite</span></span>

- <span data-ttu-id="012bd-224">Microsoft 365 끝점 데이터 손실 방지를 사용하여 System Center Configuration Manager 또는 Office 업데이트용 기타 관리 도구를 사용하는 상용 고객을 대상으로 한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-224">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="012bd-225">Office 추가 기능에 대한 메시징 API가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-225">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요 끝)

## <a name="version-2008-october-13"></a><span data-ttu-id="012bd-227">버전 2008: 10월 13일</span><span class="sxs-lookup"><span data-stu-id="012bd-227">Version 2008: October 13</span></span>
<span data-ttu-id="012bd-228">*버전 2008(빌드 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="012bd-228">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="012bd-229">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-229">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-231">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-231">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="012bd-232">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-232">Excel</span></span>

- <span data-ttu-id="012bd-233">'Before' 및 'After' 필터 조건이 바뀐 PivotDateFilter API로 버그를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-233">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="012bd-234">사용자가 Analysis Services 데이터베이스에 존재하지 않는 값으로 설정하였기 때문에 피벗 테이블 필터를 수정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-234">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="012bd-235">시트의 첫 행을 고정한 후 빠른 분석을 사용하는 경우 Excel에서 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-235">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="012bd-236">IFNA()를 사용하여 수식이 포함된 경우 손상된 통합 문서에 대한 경고를 발생시킬 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-236">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="012bd-237">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-237">Outlook</span></span>

- <span data-ttu-id="012bd-238">사용자가 코너에서 "X"를 클릭하여 공유 일정을 닫을 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-238">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="012bd-239">“공유 일정 개선사항 설정” 설정이 기존 공유 일정관리에 적용되지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-239">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="012bd-240">클라우드 첨부 파일을 열 때 열려고 했던 문서 대신 사용자가 안전 링크 페이지에서 오류를 보는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-240">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="012bd-241">첨부 파일 업로드에 대한 성능 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-241">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="012bd-242">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-242">PowerPoint</span></span>

- <span data-ttu-id="012bd-243">이 변경 사항에서는 내보내기 단추를 클릭해도 내보내지 않는 경우 애니메이션 GIF로 내보내기 하는 기능의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-243">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="012bd-244">제한된 보기에서 PowerPoint 파일을 열 때 IRM 보호를 사용하지 않도록 설정한 문제를 해결하기 위한 보안 수정입니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-244">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="012bd-245">PowerPoint 앱에서 충돌이 발생하는 작업 설정 대화 상자에서 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-245">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="012bd-246">Visio</span><span class="sxs-lookup"><span data-stu-id="012bd-246">Visio</span></span>

- <span data-ttu-id="012bd-247">텍스트 맞춤에서 실시간 미리 보기가 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-247">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="012bd-248">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-248">Word</span></span>

- <span data-ttu-id="012bd-249">사용자가 크기가 큰 특정 전자 메일을 열 때 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-249">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="012bd-250">일부 사용자가 문서를 여는 경우, 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-250">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="012bd-251">Word 부팅 시 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-251">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="012bd-252">스타일 갤러리 대화 상자와 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-252">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="012bd-253">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-253">Office Suite</span></span>

- <span data-ttu-id="012bd-254">Office에서 사용자가 잉크젯 프린터로 문서/파일을 인쇄하고 프린터의 잉크가 부족하면, 잉크젯 프린터에 토너가 없더라도 "토너 부족" 또는 "토너 없음" 메시지가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-254">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="012bd-255">메시지를 변경하여 "토너/잉크 부족" 및 "토너/잉크 없음"으로 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-255">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="012bd-256">GIF/애니메이션 모델3D를 사용하여 유휴 상태에서 높은 CPU 사용량 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-256">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="012bd-257">이 변경 사항은 d2d1.dll 로드 실패로 인한 Office 앱을 시작할 때 발생하는 충돌 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-257">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2008-september-08"></a><span data-ttu-id="012bd-259">버전 2008: 9월 8일</span><span class="sxs-lookup"><span data-stu-id="012bd-259">Version 2008: September 08</span></span>
<span data-ttu-id="012bd-260">*버전 2008(빌드 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="012bd-260">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="012bd-261">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-261">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="012bd-263">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-263">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="012bd-264">Access</span><span class="sxs-lookup"><span data-stu-id="012bd-264">Access</span></span>

- <span data-ttu-id="012bd-265">**Query Designer, SQL 보기 및 관계 창에서 생산성을 향상시킬 수 있습니다.** 테이블을 마우스 오른쪽 단추로 클릭하여 열고 디자인하고 크기를 조정하고 숨겨보세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-265">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="012bd-266">SQL 보기에서 텍스트를 검색하고 바꾸세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-266">Search and replace text in SQL View.</span></span> <span data-ttu-id="012bd-267">관계 창에서 테이블을 여러 개 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-267">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="012bd-268">**더 적은 수의 클릭으로 테이블 추가:** 작업하는 동안 열려 있는 테이블 추가 작업창을 사용하여 관계와 쿼리에 테이블을 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-268">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="012bd-269">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-269">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="012bd-270">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-270">Excel</span></span>

- <span data-ttu-id="012bd-271">**향상된 지도 차트:** 매핑된 위치에 대한 풍부한 정보를 볼 수 있는 Excel의 지리적 데이터 유형에 통합하여 지도 차트를 더 효율적으로 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-271">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="012bd-272">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-272">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="012bd-273">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-273">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="012bd-274">[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-274">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="012bd-275">**Excel 내의 Power BI에 있는 데이터셋에서 PivotTables 생성:** 몇 번의 클릭으로 Power BI에 저장된 데이터셋에 연결된 PivotTables를 Excel에서 생성할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-275">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="012bd-276"> 이렇게 하면 PivotTables와 Power BI를 모두 최대한 활용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-276">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="012bd-277">보안 Power BI 데이터셋에서 PivotTables를 사용하여 데이터를 계산, 요약 및 분석할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-277">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="012bd-278">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-278">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="012bd-279">[블로그 게시물](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-279">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="012bd-280">**자주 사용하는 Excel 함수가 더욱 빨라졌습니다.** SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS 및 MINIFS 함수가 그 어느 때보다 훨씬 빨라졌습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-280">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="012bd-281">더 빠르게 결과 값을 얻을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-281">Get to the bottom line more quickly.</span></span> <span data-ttu-id="012bd-282">지금 바로 시도해 보세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-282">Try one now.</span></span>

- <span data-ttu-id="012bd-283">**Realtimedata(RTD) 개선 사항:** Office 365 버전 2002 월 단위 채널 이상에서 Excel의 RealTimeData(RTD) 함수는 스프레드시트의 데이터를 계산하는 Excel 2010보다 훨씬 빠릅니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-283">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="012bd-284">기본 메모리 및 데이터 구조의 병목 현상을 제거했으며 사용 가능한 모든 Multithreaded Recalculation(MTR) 스레드에서 계산할 수 있도록 스레드로부터 안전하게 만들었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-284">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="012bd-285">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-285">Outlook</span></span>

- <span data-ttu-id="012bd-286">**공유 일정 업데이트 속도 향상:** Office 365의 공유 일정의 경우 Outlook에서 REST API를 사용하여 해당 일정을 업데이트할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-286">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="012bd-287">미리 보기를 설정하여 공유 일정에 보다 빠르고 신뢰할 수 있는 업데이트를 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-287">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="012bd-288">**즉시 더 나은 결과 얻기:** 이전보다 더 스마트하고, 빠르고, 안정적이 되도록 검색 환경을 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-288">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="012bd-289">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-289">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="012bd-290">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-290">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="012bd-291">[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-291">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="012bd-292">**사용자가 소유한 그룹으로 전자 메일 끌기:** 메시지와 대화를 받은 편지함에서 끌어서 이동하고 복사합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-292">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="012bd-293">끌어 놓은 메시지는 모든 그룹 구성원과 공유됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-293">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="012bd-294">[블로그 게시물](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-294">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="012bd-295">**일정 모양 변경:** 일정을 더욱 쉽게 훑어볼 수 있도록 하는 시각적 업데이트를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-295">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="012bd-296">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-296">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="012bd-297">[블로그 게시물](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-297">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="012bd-298">**받은 편지함을 벗어나지 않고 모임 참가:** 온라인 모임에 참가하기 위해 일정으로 전환할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-298">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="012bd-299">일정을 할 일 창에 고정하고 클릭 한 번만으로 모든 모임에 참여하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-299">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="012bd-300">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-300">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="012bd-301">**종속적인 Wi-Fi 네트워크에 대한 새로운 경험:** 로그인하기 위해 웹 페이지가 필요한 Wi-Fi 네트워크에 가입한 적이 있습니까?</span><span class="sxs-lookup"><span data-stu-id="012bd-301">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="012bd-302">이제 Outlook이 이를 감지하여 연결하는 데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-302">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="012bd-303">[블로그 게시물](https://insider.office.com/ko-KR/blog/outlook-on-public-wi-fi-networks-just-got-easier)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-303">See details in [blog post](https://insider.office.com/ko-KR/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="012bd-304">**사람을 검색할 때 전자 메일 제안 받기:** 검색 상자에 사람의 이름을 입력하면 가장 관련성이 높은 전자 메일 메시지가 검색 제안에 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-304">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="012bd-305">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-305">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="012bd-306">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-306">PowerPoint</span></span>

- <span data-ttu-id="012bd-307">**\@멘션으로 주의 끌기:** 메모에 @멘션을 사용하여 입력이 필요하다는 사실을 동료들에게 알립니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-307">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="012bd-308">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-308">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="012bd-309">**향상된 지도 차트:** 매핑된 위치에 대한 풍부한 정보를 볼 수 있는 Excel의 지리적 데이터 유형에 통합하여 지도 차트를 더 효율적으로 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-309">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="012bd-310">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-310">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="012bd-311">**GIF 즉시 만들기:** 하나의 슬라이드, 하나의 프레임.</span><span class="sxs-lookup"><span data-stu-id="012bd-311">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="012bd-312">PowerPoint에서 쉽게 루핑 GIF를 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-312">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="012bd-313">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-313">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="012bd-314">[블로그 게시물](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)에서 세부 정보를 참조하세요</span><span class="sxs-lookup"><span data-stu-id="012bd-314">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="012bd-315">**향상된 다이어그램:** 더욱 향상된 커넥터와 원활한 잉크 변환 프로세스를 통해 아이디어를 더욱 확신을 가지고 잉크로 표현할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-315">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="012bd-316">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-316">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="012bd-317">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-317">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="012bd-318">[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-318">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="012bd-319">**메모:** PowerPoint에서 새 메모 달기 환경을 사용하여 빠르고 쉽게 메모를 검색하고 문서에 메모를 추가할 수 있습니다. </span><span class="sxs-lookup"><span data-stu-id="012bd-319">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="012bd-320">메모 고정, 해결, 작업, 개선된 멘션 알림 등과 같은 새로운 기능으로 공동 작업 워크플로를 현대화하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-320">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="012bd-321">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-321">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="012bd-322">**발표하는 동안 변경 내용 동기화:** 프레젠테이션이 슬라이드 쇼 모드에 있더라도 내용이 변경될 때마다 동기화됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-322">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="012bd-323">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-323">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="012bd-324">[블로그 게시물](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-324">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="012bd-325">**슬라이드에 연결:** 동료에게 슬라이드 모음에 게시하도록 요청하고 도움이 필요한 슬라이드에서 직접 시작해 보세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-325">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="012bd-326">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-326">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="012bd-327">[블로그 게시물](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-327">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="012bd-328">**PowerPoint의 스트림 비디오 성능 향상:** Microsoft Stream 비디오의 재생 성능을 개선하여 비디오 로드 시간을 최소화하고 원활한 보기 환경을 조성했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-328">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="012bd-329">Microsoft Stream의 회사 비디오를 사용하여 더 나은 프레젠테이션을 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-329">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="012bd-330">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-330">Word</span></span>

- <span data-ttu-id="012bd-331">**향상된 지도 차트:** 매핑된 위치에 대한 풍부한 정보를 볼 수 있는 Excel의 지리적 데이터 유형에 통합하여 지도 차트를 더 효율적으로 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-331">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="012bd-332">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-332">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="012bd-333">**잉크 올가미:** 그리기 탭의 올가미 도구를 사용하면 잉크로 그린 개체를 선택할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-333">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="012bd-334">개별 스트로크를 선택하거나 단어 전체를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-334">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="012bd-335">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-335">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="012bd-336">**완벽한 색상 선택:** 16진 색상 코드를 사용하여 글꼴, 텍스트 강조 등 원하는 색상을 정확하게 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-336">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="012bd-337">[블로그 게시물](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-337">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="012bd-338">**화면 판독기에서 작업 확인:** 작업 확인은 중요한 접근성 요구 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-338">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="012bd-339">Windows의 새로운 알림 API가 도입됨에 따라 이제 화면 판독기 사용자에게 작업의 성공에 대해 경고 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-339">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="012bd-340">이제 잘라내기, 복사, 붙여넣기, 굵게, 기울임꼴, 밑줄, 실행 취소, 다시 실행, 자동 수정 및 자동 자본화가 모두 내레이터 사용자에게 Win32 Word로 공지됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-340">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="012bd-341">이 기능을 사용하려면 창 + Ctrl + Enter 키를 눌러 내레이터를 켭니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-341">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="012bd-342">[블로그 게시물](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)에서 세부 정보를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-342">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="012bd-343">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-343">Office Suite</span></span>

- <span data-ttu-id="012bd-344">**민감도 레이블**: 조직에서 사용자 지정 권한에 대한 메시지를 표시하도록 구성한 민감도 레이블을 적용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-344">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-347">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-347">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="012bd-348">Access</span><span class="sxs-lookup"><span data-stu-id="012bd-348">Access</span></span>

- <span data-ttu-id="012bd-349">ID(예: 일련 번호) 필드를 포함하는 연결된 SQL 테이블을 삽입할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-349">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="012bd-350">쿼리 실행이 예상했던 시간보다 거의 두 배 이상 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-350">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="012bd-351">앱에서 충돌 없이 날짜/시간 확장 데이터 형식을 코드로 호출할 수 있도록 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-351">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="012bd-352">최근에 업데이트된 Access 버전으로 되돌리고 DAO/VBA를 사용하여 10진수 데이터 형식을 관리하고 편집할 수 있도록 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-352">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="012bd-353">이 수정은 특정 쿼리를 실행하려고 하면 이전에 '쿼리가 너무 복잡합니다'라는 오류 메시지가 발생한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-353">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="012bd-354">Access에서 이 현재 문제를 해결했지만, 이 문제가 지속되지 않도록 추가 인터페이스를 조사할 것입니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-354">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="012bd-355">팀에서 향후 업데이트를 알려드리겠습니다. 양해해 주셔서 감사합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-355">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="012bd-356">이 문제가 해결되었습니다. 이제 Office의 Click-to-Run 응용 프로그램 외부에서 ODBC 드라이버를 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-356">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="012bd-357">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-357">Excel</span></span>

- <span data-ttu-id="012bd-358">읽기 전용 모드였던 통합 문서에 자동 문서 분류가 발생했을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-358">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="012bd-359">계정에서 로그아웃한 경우 데이터 연결을 만들 때 발생할 수 있는 충돌을 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-359">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="012bd-360">도표 시트에 PivotTables를 삽입하려고 할 때 Excel이 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-360">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="012bd-361">LET() 함수를 사용하여 수식이 들어 있는 파일을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-361">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="012bd-362">서식 복사를 사용하는 경우 특정 상황에서 Excel이 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-362">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="012bd-363">SharePoint/OneDrive에 저장하는 경우 사용자 지정 리본 탭이 CustomUI XML을 제거하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-363">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="012bd-364">팀을 통해 Excel 창을 공유할 때 Ctrl+Shift+화살표 키를 사용하여 스크롤한 후 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-364">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="012bd-365">경우에 따라 동일한 통합 문서 안의 위치에 대한 하이퍼링크를 클릭하면 통합 문서가 숨겨지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-365">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="012bd-366">파일 경로가 너무 길면 파일을 다시 연 후 외부 링크가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-366">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="012bd-367">일부 경우에 Application.Evaluate(VBA)가 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-367">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="012bd-368">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효가 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-368">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="012bd-369">일부 경우에 피벗 테이블을 포함하는 시트를 복사한 후 Excel 작동이 중단되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-369">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="012bd-370">이는 이전 버전의 Office에서 SQL 데이터 공급자가 만든 연결이 Office 365와 다르게 내부 테이블 속성을 설정하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-370">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="012bd-371">이로 인해 Office 365를 사용하여 열 때 이전 버전의 Office에서 만든 연결이 있는 파일에 대해 테이블 미리보기/쿼리 편집기 드롭다운을 사용하지 않도록 설정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-371">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="012bd-372">원본 통합 문서가 닫힌 경우 외부 링크가 채우기에 업데이트되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-372">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="012bd-373">수동 입력으로 인해 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-373">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="012bd-374">OneNote</span><span class="sxs-lookup"><span data-stu-id="012bd-374">OneNote</span></span>

- <span data-ttu-id="012bd-375">InfoBar를 통해 사용자에게 Microsoft OneNote의 임시 조정에 대해 알리고 전 세계적으로 사용하는 동안 동기화 및 서비스 가용성을 향상시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-375">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="012bd-376">OneNote 2016에서 동기화 빈도를 일시적으로 조정하여 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-376">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="012bd-377">리소스 사용률을 줄이기 위해 공동 작성 상태 감지 기능을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-377">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="012bd-378">OneNote 2016에서 새로운 내장형 첨부 파일의 최대 허용 크기를 50MB로 일시적으로 줄여 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-378">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="012bd-379">이 제한을 초과하는 파일의 경우 사용자는 파일을 OneDrive에 업로드하고 OneNote에 링크를 삽입할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-379">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="012bd-380">OneNote 2016에서 앱 내 비디오 녹화를 일시적으로 사용하지 않도록 설정하여 동기화 및 서비스 안정성을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-380">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="012bd-381">로컬 노트북은 이 조치의 영향을받지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-381">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="012bd-382">페이지 버전 기록이 생성되는 빈도를 일시적으로 변경하여 동기화 및 서비스 안정성을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-382">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="012bd-383">휴지통으로 페이지 이동을 일시적으로 비활성화하여 동기화 및 서버 안정성이 향상을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-383">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="012bd-384">대신 페이지를 삭제하려는 사용자에게는 페이지를 영구적으로 삭제할 것인지를 묻는 대화 상자가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-384">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="012bd-385">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-385">Outlook</span></span>

- <span data-ttu-id="012bd-386">프로필에 추가된 보조 계정에서 모임 요청을 만들려고 시도한 사용자에게 전자 메일 주소 대신 빈 보낸 사람: 필드가 표시되지 않는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-386">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="012bd-387">사용자가 공유 사서함을 추가한 후 공용 폴더에 연결할 수 없는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-387">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="012bd-388">일부 상황에서 대리인이 거절했을 때 관리자의 일정에서 모임이 제거되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-388">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="012bd-389">공유 일정관리 개선 기능의 일부 사용자가 새로 추가된 공유 일정관리를 볼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-389">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="012bd-390">사용자가 클라우드 첨부 파일을 사용하여 대화형으로 작업하는 경우 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-390">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="012bd-391">보호되는 컨텍스트에서 보호되지 않은 컨텍스트로 회신 보낸 사람 주소를 전환할 때 CLP 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-391">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="012bd-392">Outlook에서 M365 Business Plus 계획에 있는 서비스 비용을 지불한 사용자를 위해 Data Loss Protection 정책을 활성화하지 못한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-392">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="012bd-393">회신/전송 레이블에 대한 clp 감사 이벤트에서 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-393">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="012bd-394">폴더 창의 너비가 예기치 않게 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-394">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="012bd-395">끌어서 놓기를 통해 4501년 1월 1일로 설정하여 파일 시스템에 복사한 첨부 파일의 만든 날짜를 사용자에게 표시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-395">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="012bd-396">SharePoint 파일에 스마트 링크를 추가할 때 일부 문자 집합 사용자에게 파일 이름을 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-396">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="012bd-397">Outlook에서 규칙을 업데이트할 때 ‘이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다’라는 메시지가 사용자에게 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-397">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="012bd-398">Outlook에서 검색 제안을 검색하지 못한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-398">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="012bd-399">공유 일정의 개선된 사용자가 일정 오류를 볼 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-399">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="012bd-400">일부 시나리오에서 사용자가 간헐적 중단과 충돌을 겪는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-400">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="012bd-401">"머리글만 다운로드" 옵션을 선택한 상태에서 POP 계정에서 네 개 이상의 전자 메일을 삭제하면 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-401">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="012bd-402">공유 폴더 다운로드를 선택하지 않은 경우에 “전달 허용” 옵션이 공유 일정 모임 "응답 옵션"에서 누락되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-402">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="012bd-403">관리자의 일정에서 기존 일정 약속을 편집할 때 대리인에게 오류가 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-403">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="012bd-404">타사의 MAPI 응용 프로그램에서 충돌이 발생하게 하였던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-404">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="012bd-405">Windows 업데이트 후 로컬로 저장된 .msg 혹은 .oft 파일을 열 때 Outlook의 작동이 중단되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-405">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="012bd-406">일부 Windows 빌드에서 Outlook이 중단되었던문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-406">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="012bd-407">Windows 10 서버 버전 사용자에게 “바이러스 백신 상태: 올바르지 않음”이라는 경고 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-407">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="012bd-408">이 Windows 버전에서는 바이러스 백신 감지를 지원하지만 바이러스 백신 프로그램이 올바르게 설치되었음에도 불구하고 해당 프로그램을 찾을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-408">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="012bd-409">Windows 업데이트 후 로컬로 저장된 .msg 혹은 .oft 파일을 열 때 Outlook의 작동이 중단되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-409">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="012bd-410">일부 Windows 빌드에서 Outlook이 중단되었던문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-410">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="012bd-411">Outlook에서 받은 편지함 복구 도구를 실행하라는 메시지를 계속 표시하도록 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-411">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="012bd-412">마우스에서 "X" 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-412">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="012bd-413">보안 대화 상자에서 "저장" 옵션을 선택할 때 사용자가 테넌트 외부에서 로컬 컴퓨터에 OneDrive 첨부 파일을 저장할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-413">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="012bd-414">일정 정리 페이지가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-414">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="012bd-415">일부 사용자에게 일정 정리 페이지가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-415">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="012bd-416">개인 정보 검색 시 사용자가 때때로 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-416">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="012bd-417">이를 통해 받는 사람을 편집할 때 사용자에게 충돌이 발생하는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-417">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="012bd-418">압축 보기를 사용할 때 사용자에게 이상 현상이 나타나는 문제를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-418">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="012bd-419">아웃룩 사용자가 컴팩트 뷰에서 탐색 관련 문제를 볼 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-419">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="012bd-420">오른쪽 클릭 상황에 맞는 메뉴가 검색 컨트롤에 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-420">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="012bd-421">새 전자 메일에 회신하거나 새 전자 메일을 작성할 때 사용자가 다음 오류를 수신한 문제를 해결합니다. "이 웹 페이지의 일부 파일이 예상 위치에 없습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-421">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="012bd-422">그래도 다운로드하시겠어요?</span><span class="sxs-lookup"><span data-stu-id="012bd-422">Do you want to download them anyway?</span></span> <span data-ttu-id="012bd-423">웹 페이지가 신뢰할 수 있는 원본의 웹 페이지인 경우 예를 클릭합니다."</span><span class="sxs-lookup"><span data-stu-id="012bd-423">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="012bd-424">Outlook을 종료하는 동안 사용자 작업이 중지되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-424">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="012bd-425">기능 제안에서 기능을 검색하여 결과를 반환하지 않고 사용자에게 새 기능 아이디어를 제출할 수 있는 옵션이 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-425">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="012bd-426">인시던트 알림 경고에서 서식 문제가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-426">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="012bd-427">관리자 알림에서 피드백을 제출할 때 사용자가 충돌을 경험하게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-427">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="012bd-428">SVG 이미지 복사하여 붙여넣기 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-428">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="012bd-429">이를 통해 받는 사람을 편집할 때 사용자에게 충돌이 발생하는 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-429">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="012bd-430">SVG 이미지 복사하여 붙여넣기 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-430">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="012bd-431">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-431">PowerPoint</span></span>

- <span data-ttu-id="012bd-432">사용자가 파일에 최신 및 기존 주석을 모두 가지고 있을 때 충돌이 발생하여 주석을 업그레이드하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-432">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="012bd-433">PowerPoint 앱에서 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-433">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="012bd-434">제안 창에서 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-434">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="012bd-435">Project</span><span class="sxs-lookup"><span data-stu-id="012bd-435">Project</span></span>

- <span data-ttu-id="012bd-436">양식보기에서 선행 작업/후속자 데이터를 편집하면 추가 ProjectBeforeTaskChange 이벤트가 실행되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-436">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="012bd-437">이전 버전의 Project에서 만든 프로젝트를 저장하면 Project가 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-437">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="012bd-438">실제 작업 시간을 보호하는 설정이 설정된 경우 사용자가 기간별 초기 작업 시간을 입력할 수 없는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-438">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="012bd-439">작업이 완료됨으로 표시된 후 작업 완료율이 100%보다 낮은 값으로 잘못 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-439">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="012bd-440">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-440">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="012bd-441">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-441">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="012bd-442">비활성 단추를 통해 작업이 비활성화/활성화된 때를 ProjectBeforeTaskChange 이벤트에서 감지하지 못하는 문제를 해결했습니다. </span><span class="sxs-lookup"><span data-stu-id="012bd-442">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="012bd-443">Project Web App에 연결된 Project를 사용하는 경우 소수 구분 기호가 쉼표이면 TaskDependencies Add 메서드가 종속성에 지연 시간을 추가하려할 때 실패하는 문제를 수정습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-443">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="012bd-444">Project Web App에서 URL이 .com으로 끝나는 경우 Project 데스크톱 클라이언트에서 프로젝트를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-444">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="012bd-445">여러 종속성이 있는 작업을 붙여 넣는 경우 일부 종속성이 제대로 복사 되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-445">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="012bd-446">Project에서 SharePoint 문서 라이브러리에 PDF/XPS를 저장 할 수 없는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-446">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="012bd-447">100% 완료로 표시된 작업이 100% 미만으로 잘못 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-447">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="012bd-448">프로젝트 요약 작업(프로젝트 시작/작업 필드)이 변경될 때 ProjectBeforeTaskChange 이벤트가 발생하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-448">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="012bd-449">리소스에 둘 이상의 비용 비율 테이블이 정의된 경우 나머지 비용이 항상 올바르게 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-449">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="012bd-450">SharePoint 작업 목록에 연결된 프로젝트에 대해 프로젝트 완료 날짜가 업데이트되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-450">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="012bd-451">자원 배정 대화 상자에서 선택한 작업이 작업 게시판 보기에서 선택 된 작업과 같지 않은 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-451">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="012bd-452">상태가 좋지 않은 프로젝트를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-452">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="012bd-453">Skype</span><span class="sxs-lookup"><span data-stu-id="012bd-453">Skype</span></span>

- <span data-ttu-id="012bd-454">사용자에게 Teams 전용으로 이동하는 정책이 지정되어도 Skype for Business Outlook 추가 기능을 사용하여 모임을 예약할 수 있었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-454">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="012bd-455">이 업데이트 후, 클라이언트가 사용자가 Teams 전용임을 나타내는 정책을 읽고 모임 참가 전용 모드로 들어간 후에는 더 이상 Skype for Business 모임을 예약할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-455">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="012bd-456">또한 Skype for Business Outlook 추가 기능은 Skype for Business 클라이언트가 미팅 참가 모드인 경우 시작하는 동안 자체적으로 활성화되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-456">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="012bd-457">춤추는 이모티콘 피부색을 중성 색상으로 변경했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-457">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="012bd-458">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-458">Word</span></span>

- <span data-ttu-id="012bd-459">URL에 쿼리 구성 요소가 포함되어 있을 때 사용자 정의 문서 배달(aspx)에서 Word 문서를 여는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-459">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="012bd-460">이 변경사항은 이전 공동 작성 세션 후 Office 응용 프로그램이 자동 저장 오류 상태로 고정될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-460">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="012bd-461">사용자가 새 전자 메일에 회신하거나 작성할 때 충돌이 발생한 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-461">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="012bd-462">마우스에서 "X" 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-462">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="012bd-463">SVG 이미지 복사하여 붙여넣기 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-463">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="012bd-464">사용자가 셰이프의 크기를 조절할 때 콘텐츠가 손실될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-464">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="012bd-465">표준 스타일을 사용하여 기본 스타일을 업데이트할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-465">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="012bd-466">AutoExec에서 매크로 AutoOpen가 실행되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-466">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="012bd-467">SVG 이미지 복사하여 붙여넣기 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-467">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="012bd-468">앱의 일부 콘텐츠를 끌 때 충돌이 발생할 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-468">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="012bd-469">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-469">Office Suite</span></span>

- <span data-ttu-id="012bd-470">이전 웹 서비스 기반 공유 창의 경우 공유 창이 열려 있는 동안 문서를 닫으면 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-470">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="012bd-471">이제 이 문제는 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-471">This is now fixed.</span></span>

- <span data-ttu-id="012bd-472">시간 문제 때문에 Office 파일을 닫을 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-472">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="012bd-473">검증을 확인했습니다.기본적으로 Bing Addon 설치 검증을 true로 설정하고 MSI 반환 성공을 설치 성공으로 간주하여 설치 실패율 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-473">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="012bd-474">이전 AppV51의 회귀 분석을 수정하기 위해 새로운 AppV51 드롭을 다시 보고했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-474">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="012bd-475">기호 링크를 하드 링크하려고 할 때 업데이트 오류가 발생하는 간편 실행 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-475">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="012bd-476">전체 제품으로 전환이 완료되었음에도 런타임 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-476">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="012bd-477">서비스가 올바르게 계산 된 제품이 추가 되었는지 확인하여 수정 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-477">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="012bd-478">새로 추가한 제품(새 구성에도 존재 하는지 확인)을 필터링하고 기존 제품 출시 ID 끝에 추가 했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-478">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="012bd-479">사용자가 특정 조건에서 UI 요소 또는 콘텐츠가 표시되지 않는 문제를 해결했습니다. 특히 프리젠터 뷰를 드나드는 경우 또는 여러 모니터를 사용하는 경우 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-479">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="012bd-480">이 변경 사항은 GIF 또는 3D 모델과 같은 애니메이션 콘텐츠를 로드하고 재생할 때 발생할 수 있는 중단 현상을 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-480">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="012bd-481">이 변경 사항은 특정 사용자 설정을 유지하지 않는 그림 압축 대화 상자의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-481">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="012bd-482">이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. </span><span class="sxs-lookup"><span data-stu-id="012bd-482">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="012bd-483">이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-483">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="012bd-484">이 수정은 액세스의 제한과 동시에 파일을 암호로 보호하는 작업을 할 수 없게 하는 오류를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-484">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="012bd-485">레지스트리 TabProcGrowth 값이 REG_SZ 유형이면 추가 기능이 활성화될 때 Office 호스트가 Windows에서 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-485">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="012bd-486">레지스트리 키 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth가 0으로 설정되어있는 동안 추가 기능이 활성화될 때 사무실 호스트가 Windows에서 충돌했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-486">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="012bd-487">이렇게 변경하면 이 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-487">This change would fix this issue.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-august-11"></a><span data-ttu-id="012bd-489">버전 2002: 8월 11일</span><span class="sxs-lookup"><span data-stu-id="012bd-489">Version 2002: August 11</span></span>
<span data-ttu-id="012bd-490">*버전 2002(빌드 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="012bd-490">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="012bd-491">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-491">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-493">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-493">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="012bd-494">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-494">Excel</span></span>

- <span data-ttu-id="012bd-495">"읽기 전용 권장 사항"으로 열린 파일에 대해 편집으로 전환할 수 없는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="012bd-495">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="012bd-496">OneNote</span><span class="sxs-lookup"><span data-stu-id="012bd-496">OneNote</span></span>

- <span data-ttu-id="012bd-497">중복 ID 호출을 제거하여 리소스 활용률 감소</span><span class="sxs-lookup"><span data-stu-id="012bd-497">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="012bd-498">공동 Authoring 상태 탐지 개선으로 리소스 활용률 감소</span><span class="sxs-lookup"><span data-stu-id="012bd-498">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="012bd-499">오류 감지 기능 및 동기화 경험 품질 향상</span><span class="sxs-lookup"><span data-stu-id="012bd-499">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="012bd-500">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-500">Outlook</span></span>

- <span data-ttu-id="012bd-501">일부 테넌트에 대해 Outlook을 시작할 때 중요한 성능 문제를 일으킨 문제 해결</span><span class="sxs-lookup"><span data-stu-id="012bd-501">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="012bd-502">Skype</span><span class="sxs-lookup"><span data-stu-id="012bd-502">Skype</span></span>

- <span data-ttu-id="012bd-503">32비트 Skype for Business 클라이언트에서 며칠 동안 실행된 후 화면 공유 시작에 실패할 수 있는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="012bd-503">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="012bd-504">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-504">Office Suite</span></span>

- <span data-ttu-id="012bd-505">그룹 정책을 통해 AutoSave가 해제된 경우 사용자가 '사용 가능한 업데이트'를 클릭할 때까지 일부 문서가 열려 있는 최신 서버 내용을 표시하지 않는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="012bd-505">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-july-14"></a><span data-ttu-id="012bd-507">버전 2002: 7월 14일</span><span class="sxs-lookup"><span data-stu-id="012bd-507">Version 2002: July 14</span></span>
<span data-ttu-id="012bd-508">*버전 2002(빌드 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="012bd-508">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="012bd-509">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)에 보안 업데이트가 나열됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-509">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-511">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-511">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="012bd-512">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-512">Excel</span></span>

- <span data-ttu-id="012bd-513">로컬 OneDrive 폴더에서 사용할 수 있는 파일을 빠르게 로드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-513">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="012bd-514">SharePoint/OneDrive에 저장하는 경우 사용자 지정 리본 탭이 CustomUI XML을 제거하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-514">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="012bd-515">추가 기능이 사용자 지정 순서가 아니라 알파벳 순서로 로드되었기 때문에 ‘이 통합 문서는 다른 통합 문서에서 현재 참조하고 있으며 닫을 수 없습니다’라는 오류 메시지가 나타나는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-515">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="012bd-516">이미 열려 있는 통합 문서 내의 위치에 대한 하이퍼링크를 클릭하면 통합 문서가 숨겨질 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-516">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="012bd-517">일부 복사 및 붙여넣기 차트 링크에서 범용 주소가 아닌 매핑된 드라이브 주소를 사용하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-517">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="012bd-518">병합된 셀이 있는 열을 삭제하는 경우에 발생하던 성능 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-518">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="012bd-519">인쇄 대화 상자의 프린터 목록에서 프린터 이름이 반복될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-519">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="012bd-520">정의된 이름의 수식이 여러 개 포함된 워크시트가 파일을 저장할 때 더 오래 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-520">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="012bd-521">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-521">Outlook</span></span>

- <span data-ttu-id="012bd-522">해상도가 다른 여러 모니터를 사용할 때 IME(입력 방법 편집기) 창이 IME를 통해 입력되는 기본 텍스트와 겹치는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-522">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="012bd-523">시간대 정의 변경에 접근할 때 되풀이되는 약속 또는 모임이 잘못된 시간에 표시되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-523">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="012bd-524">Outlook에서 규칙을 업데이트할 때 ‘이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다’라는 메시지가 사용자에게 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-524">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="012bd-525">공유 폴더 다운로드를 선택하지 않은 경우에 “전달 허용” 옵션이 공유 일정 모임 "응답 옵션"에서 누락되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-525">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="012bd-526">가끔 전자 메일 메시지의 범주가 사라지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-526">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="012bd-527">대리인이 다른 공유 사서함 컴퓨터의 다른 폴더 계층 구조를 볼 수 있었던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-527">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="012bd-528">관리자의 일정에서 기존 일정 약속을 편집할 때 대리인에게 오류가 발생하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-528">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="012bd-529">제목을 편집한 후 NDR 메시지 본문이 유니코드에서 ASCII로 변경되는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-529">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="012bd-530">두 개의 추가 기능에서 같은 리본 그룹에 단추를 추가하면 사용자에게 충돌이 발생하던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-530">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="012bd-531">사용자가 전자 메일을 개인 메일 그룹으로 전송할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-531">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="012bd-532">테넌트 기본 권한이 "모든 사용자"로 구성된 경우 올바른 테넌트 기본 권한이 있는 전자 메일에 링크를 추가하지 못하던 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-532">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="012bd-533">보안 대화 상자에서 "저장" 옵션을 선택할 때 사용자가 테넌트 외부에서 로컬 컴퓨터에 OneDrive 첨부 파일을 저장할 수 없는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-533">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="012bd-534">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-534">Word</span></span>

- <span data-ttu-id="012bd-535">정책 FileBlick\Word2007Files를 활성화하는 경우 발생하는 공동 작성 관련 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-535">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="012bd-536">이름이 바뀐 조회 필드를 추가하는 경우 Word QuickPart가 작동하지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-536">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="012bd-537">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-537">Office Suite</span></span>

- <span data-ttu-id="012bd-538">대규모 PowerPoint 파일에서 공동 작성하는 동안 사용자가 과도한 네트워크 및 CPU 사용률을 경험할 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-538">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="012bd-539">이전 AppV51의 회귀 분석을 수정하기 위해 새로운 AppV51 드롭을 다시 보고했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-539">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="012bd-540">레지스트리 TabProcGrowth 값이 REG_SZ 유형이면 추가 기능이 활성화될 때 Office 호스트가 Windows에서 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-540">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-june-09"></a><span data-ttu-id="012bd-542">버전 2002: 6월 9일</span><span class="sxs-lookup"><span data-stu-id="012bd-542">Version 2002: June 09</span></span>
<span data-ttu-id="012bd-543">*버전 2002(빌드 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="012bd-543">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="012bd-544">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-544">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-546">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-546">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="012bd-547">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-547">Excel</span></span>

- <span data-ttu-id="012bd-548">파일 경로가 너무 길면 파일을 다시 연 후 외부 링크가 작동하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-548">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="012bd-549">팀을 통해 Excel 창을 공유할 때 Ctrl+Shift+화살표 키를 사용하여 스크롤한 후 Excel이 응답하지 않을 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-549">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="012bd-550">인쇄할 때 양식 컨트롤에 있는 확인란 크기 조정 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-550">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="012bd-551">레거시 "공유 통합 문서" 모드를 사용하여 통합 문서의 새 시트에 변경 내용을 나열할 때 충돌이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-551">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="012bd-552">필터링된 목록에 열을 삽입하면 예상보다 시간이 오래 걸립니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-552">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="012bd-553">공식을 시작하는 @ 기호가 암시적 교차로 연산자로 간주되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-553">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="012bd-554">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-554">Outlook</span></span>

- <span data-ttu-id="012bd-555">기본 팀 클라이언트를 통해 직접 팀 미팅에 참여할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-555">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="012bd-556">Outlook에서 M365 Business Plus 계획에 있는 서비스 비용을 지불한 사용자를 위해 Data Loss Protection 정책을 활성화하지 못한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-556">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="012bd-557">Gmail에 대한 인증 프롬프트를 완료할 수 없는 경우 사용자가 잘못된 브라우저 에뮬레이션 설정으로 인해 발생한 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-557">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="012bd-558">서버 운영 체제의 Outlook 사용자에게 "바이러스 백신 상태 : 유효하지 않음" 오류가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-558">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="012bd-559">이 버전의 Windows에서는 바이러스 백신 탐지를 지원하지만 바이러스 백신을 제대로 구성했음에도 불구하고 바이러스 백신을 찾을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-559">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="012bd-560">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-560">Word</span></span>

- <span data-ttu-id="012bd-561">빠른 인쇄를 사용하여 인쇄한 후에 편집하려고 할 때 문서의 단어 맞춤이 스크램블되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-561">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="012bd-562">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-562">Office Suite</span></span>

- <span data-ttu-id="012bd-563">우리는 2020년 1월 포크의 새 채널 이름으로 백스테이지의 채널 이름을 업데이트하여 이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-563">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="012bd-564">이 문제를 해결했으며 앞으로 장치가 정책 관리 대상인 경우 DMS Customer API를 호출하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-564">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="012bd-565">단일 트랜잭션에서 앱을 추가 및 제거할 때 불완전한 제거가 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-565">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="012bd-566">레지스트리 키 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth가 0으로 설정되어있는 동안 추가 기능이 활성화될 때 사무실 호스트가 Windows에서 충돌했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-566">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="012bd-567">이렇게 변경하면 이 문제가 해결됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-567">This change would fix this issue.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-may-12"></a><span data-ttu-id="012bd-569">버전 2002: 5월 12일</span><span class="sxs-lookup"><span data-stu-id="012bd-569">Version 2002: May 12</span></span>
<span data-ttu-id="012bd-570">*버전 2002 (빌드 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="012bd-570">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="012bd-571">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="012bd-571">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-573">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-573">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="012bd-574">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-574">Excel</span></span>

- <span data-ttu-id="012bd-575">다수의 다양한 통합 문서(특히 숨겨진 창)를 참조하는 통합 문서를 열면 예상보다 느리게 열립니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-575">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="012bd-576">경우에 따라 CSV 파일을 여는 데 소요되는 시간이 예상보다 더 오래 걸렸습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-576">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="012bd-577">다른 확대/축소 단계를 사용하는 통합 문서 사이를 전환할 때 일부의 경우에 Excel의 작동이 중단될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-577">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="012bd-578">범위에 값을 입력하는 것이 예상한 것 보다 느려지는 VBA 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-578">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="012bd-579">색을 기준으로 필터링 된 열에서 복사한 데이터가 가끔 제대로 붙여 넣어지지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-579">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="012bd-580">일부 경우에 피벗 테이블을 포함하는 시트를 복사한 후 Excel의 작동이 중단되는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-580">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="012bd-581">Excel 2016에서 디지털 서명을 사용하여 저장한 통합 문서를 최신 버전의 Excel에서 열면 서명이 무효화 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-581">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="012bd-582">파일을 저장하고 다시 열 때 차트 축의 "값 교점" 속성이 예기치 않게 변경되는 문제를 해결 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-582">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="012bd-583">Range.Value와 Range.Value2 (VBA)를 사용하면 수식이 동적 배열로 입력됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-583">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="012bd-584">OneNote</span><span class="sxs-lookup"><span data-stu-id="012bd-584">OneNote</span></span>

- <span data-ttu-id="012bd-585">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 지역화하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-585">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="012bd-586">사용자가 OneNote 사용자 환경에서 시행되는 임시 조치에 대해 자세히 알아볼 수 있는 알림을 표시하여 동기화 및 서비스 안정성을 개선합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-586">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="012bd-587">OneNote 2016에서 버전 기록 페이지의 수와 동기화 빈도를 일시적으로 줄임으로써 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-587">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="012bd-588">OneNote 2016에서 일시적으로 휴지통을 비활성화하여 동기화 및 서비스 안정성을 개선시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-588">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="012bd-589">사용자가 일반적으로 휴지통으로 전송될 데이터를 삭제하려고 하면, 사용자가 데이터를 유지할지 아니면 영구적으로 삭제할지 묻는 메시지가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-589">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="012bd-590">OneNote 2016에서 동기화 빈도를 일시적으로 조정하여 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-590">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="012bd-591">OneNote 2016에서 사용자가 해당 페이지로 이동할 때까지 온라인 전자 필기장에 있는 파일 및 이미지의 다운로드를 일시적으로 지연시켜 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-591">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="012bd-592">OneNote 2016에서 앱 내 비디오 녹화를 일시적으로 사용하지 않도록 설정하여 동기화 및 서비스 안정성을 향상시켰습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-592">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="012bd-593">로컬 노트북은 이 조치의 영향을받지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-593">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="012bd-594">OneNote 2016에서 새로운 내장 첨부 파일의 최대 허용 크기를 50MB로 일시적으로 줄여 동기화 및 서비스 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-594">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="012bd-595">이 제한을 초과하는 파일의 경우 사용자는 선택적으로 파일을 OneDrive에 업로드하고 OneNote에 링크를 삽입할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-595">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="012bd-596">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-596">Outlook</span></span>

- <span data-ttu-id="012bd-597">폴더 창의 너비가 예기치 않게 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-597">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="012bd-598">Windows 업데이트 후 .msg와 .oft 파일을 여는 경우 작동이 멈추는 현상이 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-598">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="012bd-599">대규모 HTML 메시지를 전달할 때 사용자에게 잘린 메시지 본문이 표시되던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-599">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="012bd-600">이 업데이트는 메시지를 보거나 작성할 때 Microsoft Outlook에서 현재 민감도 레이블을 표시하지 않는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-600">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="012bd-601">사용자가 전자 메일을 개인 메일 그룹으로 보낼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-601">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="012bd-602">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-602">PowerPoint</span></span>

- <span data-ttu-id="012bd-603">개선된 설명이 있는 파일의 복사본을 여는 사용자에게 올바른 메시징을 릴레이하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-603">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="012bd-604">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-604">Word</span></span>

- <span data-ttu-id="012bd-605">설치된 언어에 따라 Access 및 Publisher가 제대로 부팅되지 않을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-605">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="012bd-606">편집에 대해 보호된 문서의 비교 기능 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-606">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="012bd-607">2개의 문서를 하나로 병합할 때 발생하는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-607">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="012bd-608">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-608">Office Suite</span></span>

- <span data-ttu-id="012bd-609">파일을 클라이언트에 캐시할 때 Project 앱이 네트워크를 차단하지 않도록 하는 문제를 해결하기 위한 수정입니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-609">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="012bd-610">내부 작업이 실패 시 로깅을 하고 계속 진행하는 대신 예외를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-610">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="012bd-611">영향을 받은 사용자는 더 이상 업데이트를 받을 수 없도록 차단되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-611">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="012bd-612">이렇게 변경하면 스케치된 개요가 리본에서 제대로 작동합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-612">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="012bd-613">특정 프록시 구성을 사용하여 온-프레미스 위치에서 파일을 여는 동안 발생하는 문제를 수정하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-613">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="012bd-614">이 업데이트는 라이브러리 이름 또는 라이브러리 경로에 DBCS 문자가 있는 코드 라이브러리에 대한 참조를 포함하는 특정 VBA 프로젝트를 로드할 때 Office 응용 프로그램에서 손상된 것으로 보이는 Microsoft Office의 VBA(Visual Basic for Applications) 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-614">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="012bd-615">이 업데이트는 PATH 환경 변수에서 지정된 위치를 검색하여 찾을 수 있는 사항을 참고로 하는 Visual Basic for Applications 프로젝트가 런타임에 제대로 발견되지 않아 VBA 런타임 오류로 이어질 수 있는 Microsoft Office에서의 문제를 해결합니다. </span><span class="sxs-lookup"><span data-stu-id="012bd-615">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="012bd-616">이 업데이트는 레이블 정책에서 머리글/바닥글 또는 워터 마크를 적용한 경우 레이블을 변경하거나 제거하여 민감도 레이블을 적용하는 동안 삽입된 255자를 초과하는 텍스트를 차후에 식별하고 제거할 수 없는 Microsoft Word에서의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-616">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="012bd-617">Office 전달 세션 중에 충돌을 없애고 사용자 환경의 안정성을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-617">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="012bd-618">이 버그는 ECS(향상된 구성 서비스) URL 끝점을 업데이트합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-618">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="012bd-619">이 최신 끝점의 호출은 ECS에서 가져오기의 성공률이 높습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-619">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-april-14"></a><span data-ttu-id="012bd-621">버전 2002: 4월 14일</span><span class="sxs-lookup"><span data-stu-id="012bd-621">Version 2002: April 14</span></span>
<span data-ttu-id="012bd-622">*버전 2002 (빌드 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="012bd-622">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="012bd-623">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="012bd-623">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="012bd-624">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-624">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="012bd-625">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-625">Excel</span></span>

- <span data-ttu-id="012bd-626">**다중값을 반환하는 공식을 입력:** 다중값을 반환하는 공식을 신속히 입력하면 자동으로 인접한 셀들로 입력됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-626">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="012bd-627">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-627">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="012bd-628">**유용한 함수 6개:** 스프레드시트를 더욱 유용하게 사용할 수 있는 함수 6개(FILTER, SORT, SORTBY, UNIQUE, SEQUENCE 및 RANDARRAY)가 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-628">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="012bd-629">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-629">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="012bd-630">**왼쪽을 보고, 오른쪽을 보십시오… XLOOKUP이 여기 있습니다!** 행별로 XLOOKUP을 사용하여 테이블 또는 범위에서 필요한 것을 모두 찾으십시오.</span><span class="sxs-lookup"><span data-stu-id="012bd-630">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="012bd-631">
  [자세한 정보](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="012bd-631">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-633">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-633">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="012bd-634">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-634">Excel</span></span>

- <span data-ttu-id="012bd-635">특정 경우에 Word나 PowerPoint에서 포함된 통합 문서를 다시 열면 Excel이 중단됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-635">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="012bd-636">CSV 파일로 저장하면 Excel에서 모든 열이 하나의 열로 병합되는 경우가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-636">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="012bd-637">보호된 시트의 범위에서 Range.ClearContents를 사용하면 예상보다 시간이 오래 걸릴 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-637">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="012bd-638">인쇄 미리 보기로 표시되는 경우 양식 컨트롤에서 텍스트의 크기 조정 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-638">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="012bd-639">리본 메뉴와 상호 작용하는 VBA 매크로는 ScreenUpdating을 예기치 않게 True로 설정한 상태에서 실행될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-639">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="012bd-640">원본 통합 문서가 닫힌 경우 외부 링크가 채우기(아래로 채우기, 가로 채우기 등)에 업데이트되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-640">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="012bd-641">경우에 따라 VBA의 Application.Evaluate를 사용해도 사용자 정의 함수에서 제대로 작동하지 않았습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-641">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="012bd-642">서식 파일에서 차트를 만들 때 성능 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-642">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="012bd-643">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-643">Outlook</span></span>

- <span data-ttu-id="012bd-644">일부 시나리오에서 그룹 헤더가 예기치 않게 확장되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-644">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="012bd-645">특정 검색 결과를 선택할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-645">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="012bd-646">마우스의 X 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-646">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="012bd-647">첨부 파일 도구에서 클라우드에 저장 단추가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-647">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="012bd-648">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-648">PowerPoint</span></span>

- <span data-ttu-id="012bd-649">복사-붙여넣기 시나리오 개선: 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-649">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="012bd-650">Project</span><span class="sxs-lookup"><span data-stu-id="012bd-650">Project</span></span>

- <span data-ttu-id="012bd-651">이전 버전의 Project에서 만든 프로젝트를 저장하면 Project가 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-651">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="012bd-652">비활성 단추를 통해 작업이 비활성화/활성화된 때를 ProjectBeforeTaskChange 이벤트에서 감지하지 못하는 문제를 해결했습니다. </span><span class="sxs-lookup"><span data-stu-id="012bd-652">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="012bd-653">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-653">Word</span></span>

- <span data-ttu-id="012bd-654">마우스의 X 단추를 사용할 때 가끔 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-654">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="012bd-655">표에 텍스트 맞춤 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-655">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="012bd-656">삽입 가로선 길이가 더 짧지 않고 가운데 맞춤되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-656">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-2002-march-10"></a><span data-ttu-id="012bd-658">버전 2002: 3월 10일</span><span class="sxs-lookup"><span data-stu-id="012bd-658">Version 2002: March 10</span></span>
<span data-ttu-id="012bd-659">*버전 2002 (빌드 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="012bd-659">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="012bd-660">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="012bd-660">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="feature-updates"></a><span data-ttu-id="012bd-662">기능 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-662">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="012bd-663">Access</span><span class="sxs-lookup"><span data-stu-id="012bd-663">Access</span></span>

- <span data-ttu-id="012bd-664">**연결된 표 빠르게 찾기:** 새 검색 상자를 사용하여 연결된 표를 간편하게 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-664">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="012bd-665">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-665">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="012bd-666">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-666">Excel</span></span>

- <span data-ttu-id="012bd-667">**\@멘션으로 주의 끌기:** 메모에 @멘션을 사용하여 입력이 필요하다는 사실을 동료들에게 알립니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-667">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="012bd-668">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-668">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="012bd-669">**원하는 내용 찾기: 명령, 사용자, 파일, 사진, 웹 문서 등을 검색**</span><span class="sxs-lookup"><span data-stu-id="012bd-669">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="012bd-670">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-670">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="012bd-671">**그림 스케치:** 통합 문서에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-671">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="012bd-672">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-672">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="012bd-673">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-673">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="012bd-674">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-674">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="012bd-675">**남은 작업에 중점:** 설명을 축소하고 열린 항목을 강조하려면 해결을 선택하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-675">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="012bd-676">**더 많은 접근 가능한 PDF 만들기:** PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-676">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="012bd-677">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-677">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="012bd-678">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-678">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="012bd-679">**데이터 시각화 도우미 추가 기능:** Excel에서 빠르게 Visio 플로차트를 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-679">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="012bd-680">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-680">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="012bd-681">**읽고 즉시 회신:** 통합 문서를 열지 않고 전자 메일에서 바로 메모와 멘션에 회신합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-681">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="012bd-682">**통합 문서에 대 한 통계를 가져오기:** 통합 문서 통계는 통합 문서의 내용을 간략하게 파악하는 데 도움이 되는 통합 문서의 내용에 대한 개요를 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-682">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="012bd-683">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-683">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="012bd-684">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-684">Find them at Insert > Icons.</span></span> [<span data-ttu-id="012bd-685">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-685">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="012bd-686">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-686">Outlook</span></span>

- <span data-ttu-id="012bd-687">**LinkedIn 네트워크를 Outlook과 연결하기:** Microsoft 계정을 사용하여 LinkedIn 계정에 안전하게 연결하고 Windows용 Outlook의 명함에 있는 LinkedIn 프로필에서 정보를 확인하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-687">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="012bd-688">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-688">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="012bd-p158">**모든 암호화 옵션의 일원화:** 전자 메일 메시지 보호 방법을 선택하려면 옵션 > 암호화로 이동합니다. [자세히 알아보기](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="012bd-p158">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="012bd-691">**Outlook의 링크 삽입 메뉴는 테넌트 관리자가 정의한 사용 권한을 포함하는 링크를 삽입합니다:** Outlook의 가장 최근 삽입한 링크에 있는 링크는 이미 사용 권한이 있었던 사용자들에게만 작동했었던 링크를 삽입합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-691">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="012bd-692">이는 종종 사용자들 간에 문서에 대한 액세스 권한을 요청하는 전자 메일을 주고 받게 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-692">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="012bd-693">이 환경을 업데이트하여 이제 테넌트 관리자가 설정한 기본 권한으로 링크가 삽입되었습니다. MSIT의 경우 "조직은 편집할 수 있음"이므로 이 방법을 통해 공유된 링크를 받는 모든 내부 사용자가 액세스할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-693">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="012bd-694">**철자 또는 오타로 검색:** Outlook은 철자가 틀린 경우에도 검색 내용을 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-694">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="012bd-695">**피싱 메일을 쉽게 탐지:** 스팸과 피싱 메시지는 형태와 느낌이 다르기 때문에 받은 편지함에서 쉽게 식별하고 제거할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-695">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="012bd-696">**공격에 대비한 고급 보호:** Office 365 Advanced Threat Protection을 사용하면 전자 메일 제목, 첨부된 메시지, 서명된 메시지, 네트워크 경로 등의 하이퍼 링크를 통해 공격으로부터 보호할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-696">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="012bd-697">**그리기 기능:** 그림 위쪽에서 낙서를 하거나 그리기 캔버스를 추가하여 잉크로 내 생각을 전달할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-697">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="012bd-698">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-698">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="012bd-699">**검색 결과에서 관련 메시지 확인:** Outlook은 검색 용어를 분석하고 검색 결과 상단에 가장 관련성이 높은 전자 메일 메시지를 보여줍니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-699">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="012bd-700">또한 상위 결과 섹션에 날짜별로 정렬된 모든 결과도 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-700">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="012bd-701">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-701">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="012bd-702">**위치 제안 받기:** 약속 및 모임을 예약할 때 위치 필드에 입력을 시작하면 Outlook에 회의실, 주소 및 기타 최근 장소가 제안됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-702">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="012bd-703">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-703">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="012bd-704">**화면에 더 많은 메시지 맞춤:** 메시지 사이의 간격을 조정하려면 보기 > 더 좁은 간격 사용을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-704">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="012bd-705">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-705">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="012bd-706">**다른 조명에서 메시지 보기:** 태양/달 단추를 사용하여 읽기 창에서 밝은 배경과 어두운 배경 간에 전환을 합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-706">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="012bd-707">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-707">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="012bd-708">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-708">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="012bd-709">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-709">Find them at Insert > Icons.</span></span> [<span data-ttu-id="012bd-710">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-710">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="012bd-711">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-711">PowerPoint</span></span>

- <span data-ttu-id="012bd-712">**PowerPoint에서 빠르게 실시간 공동 작업 수행:** PowerPoint에서 빠르게 실시간 공동 작업 수행</span><span class="sxs-lookup"><span data-stu-id="012bd-712">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="012bd-713">**새로운 교정 도구:** 단어를 틀릴까봐 스트레스 받지 마세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-713">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="012bd-714">이제 PowerPoint는 문법 및 맞춤법 제안 사항을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-714">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="012bd-715">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-715">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="012bd-716">**라이브 캡션 및 자막:** 발표자의 단어가 화면에 캡션으로 자동으로 표시되고 원하는 언어로 자막으로 번역됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-716">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="012bd-717">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-717">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="012bd-p168">**수식만 쓰세요, 서식은 PowerPoint가 알아서 지정해 드립니다:** 손글씨로 쓴 수학 식을 표준 문자로 변경해 드리겠습니다. 잉크 수식 변환을 선택하고 필기를 선택하기만 하면 됩니다. [자세히 알아보기](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="012bd-p168">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="012bd-721">**원하는 내용 찾기:** 검색 창을 사용하여 텍스트, 명령, 도움말 등을 찾으세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-721">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="012bd-722">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-722">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="012bd-723">**누락된 슬라이드 제목 찾기 및 수정:** 슬라이드 제목은 발표에 호소력을 더해 다양한 수준의 사용자가 슬라이드를 이해하기 쉽도록 합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-723">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="012bd-724">접근성 검사를 통해 제목이 누락되는 위치를 표시하여 신속하게 제목을 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-724">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="012bd-725">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-725">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="012bd-726">**그림 스케치:** 프레젠테이션에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-726">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="012bd-727">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-727">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="012bd-728">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-728">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="012bd-729">**더 이상 브라우저에 바운싱하지 않음:** 브라우저나 앱에서 Office 문서에 대한 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-729">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="012bd-730">**그림을 SVG로 저장:** 이미지 품질이 손실되지 않도록 크기를 조정할 수 있는 스케일 가능한 벡터 그래픽으로 차트, 도형 또는 기타 그림을 저장합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-730">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="012bd-731">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-731">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="012bd-732">**슬라이드 번호를 유인물에 인쇄:** 슬라이드 번호가 유인물에 자동으로 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-732">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="012bd-733">계속 사용 및 해제 여부를 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-733">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="012bd-734">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-734">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="012bd-735">**잉크 스턴트 재생:** 슬라이드에 잉크를 쓸 때 슬라이드 쇼 중에 잉크의 실제 그리기를 재생하기 위한 재생 애니메이션을 적용합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-735">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="012bd-736">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-736">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="012bd-737">**더 많은 접근 가능한 PDF 만들기:** PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-737">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="012bd-738">**모든 사용자를 위한 프레젠테이션 최적화:** 접근성 검사기는 기능은 스크린 리더를 염두에 두고 슬라이드에서 개체를 정렬하는데 도움을 줍니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-738">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="012bd-739">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-739">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="012bd-740">**더욱 안전한 비디오 환경:** 보안 강화는 더욱 안전한 온라인 비디오 환경을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-740">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="012bd-741">**재개발 대신 재사용:** 사용자가 작성했거나 다른 사용자가 공유하도록 한 슬라이드를 다시 사용하여 시간을 절약하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-741">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="012bd-742">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-742">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="012bd-743">**Office 365용 PowerPoint에서 필기 잉크를 도형, 텍스트 또는 수학으로 변경:** 몇 번의 스트로크만으로 자유형 잉크를 Office 도형, 텍스트 또는 수식으로 변경합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-743">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="012bd-744">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-744">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="012bd-745">**멋진 슬라이드 만들기:** 잉크를 표준 도형 및 텍스트로 변환한 후, PowerPoint Designer에서 스마트한 슬라이드 디자인 아이디어를 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-745">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="012bd-746">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-746">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="012bd-747">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-747">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="012bd-748">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-748">Find them at Insert > Icons.</span></span> [<span data-ttu-id="012bd-749">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-749">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="012bd-750">Visio</span><span class="sxs-lookup"><span data-stu-id="012bd-750">Visio</span></span>

- <span data-ttu-id="012bd-751">**범죄 현장 재방문:** 범죄 현장 조사 서식 파일에서 새 증빙, 실내 및 실외 스텐실을 사용하여 범죄 현장에 대한 세부 정보를 다시 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-751">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="012bd-752">**Excel에서 세련된 Visio 다이어그램 만들기:** 워크시트에 데이터를 입력하여 순서도 또는 조직도를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-752">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="012bd-753">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-753">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="012bd-754">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-754">Word</span></span>

- <span data-ttu-id="012bd-755">**이력서 편집기와 LinkedIn Resume 도우미의 만남:** 이력서 편집기는 이력서에 특별히 맞춤화된 문법 및 스타일 검사를 제공하여 글을 보다 정확하고 전문적으로 만들어 줍니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-755">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="012bd-756">**3D 개체의 병합으로 발생하는 문서 손상 문제 해결:** 3D 개체의 병합으로 발생하는 문서 손상 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-756">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="012bd-757">**원하는 내용 찾기:** 검색 창을 사용하여 텍스트, 명령, 도움말 등을 찾으세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-757">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="012bd-758">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-758">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="012bd-759">**생생한 색으로 공동 작업:** 메모와 변경 사항은 기여자에 의해 색상으로 구분되므로 공동 작업자 중 개개인을 쉽게 구분할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-759">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="012bd-760">**공동으로 매크로 사용 문서 편집 공동:** 비즈니스용 OneDrive에서 .docm 파일을 저장하고 공동 작업자와 실시간으로 편집합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-760">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="012bd-761">**공동 작성 기능 개선**: 문서를 공동 작성 시 변경 내용 추적 기능을 사용하여 Word의 성능을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-761">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="012bd-762">**분위기에 맞는 더 다양한 아이콘:** 300개가 넘는 새로운 아이콘이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-762">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="012bd-763">삽입 > 아이콘에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-763">Find them at Insert > Icons.</span></span> [<span data-ttu-id="012bd-764">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-764">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="012bd-765">**다른 사용자가 변경 내용을 신속하게 확인할 수 있습니다.** 공동 작성 기능 향상을 통해 공동 작업자는 이전보다 훨씬 빠르게 변경 내용을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-765">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="012bd-766">**그림 스케치:** 문서에서 Office 도형에 손으로 그린 캐주얼한 모양을 넣을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-766">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="012bd-767">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-767">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="012bd-768">**정확하게 지우기:** 두 개의 지우개 크기 중에 선택하고 작은 잉킹 결함을 수정하세요.</span><span class="sxs-lookup"><span data-stu-id="012bd-768">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="012bd-769">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-769">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="012bd-770">**더 빠른 파일 공유**: 파일을 열지 않고 최근에 사용한 목록에서 문서를 바로 공유할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-770">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="012bd-771">**더 이상 브라우저로 바운스하지 않음:** 사용자가 브라우저나 앱에서 Office 문서로의 링크를 여는 방법을 결정합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-771">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="012bd-772">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-772">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="012bd-773">**공동 작성 향상** : 공동 작성 시 신뢰도가 향상될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-773">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="012bd-774">**더 많은 접근 가능한 PDF 만들기:** PDF를 만들면 액세스 가능성 검사기가 저장하기 전에 수정해야 할 접근성 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-774">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="012bd-775">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-775">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="012bd-776">**파일을 변환하여 접근성 향상:** 모든 사용자가 보다 쉽게 액세스할 수 있도록 파일을 최신 형식으로 업그레이드합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-776">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="012bd-777">**더욱 안전한 비디오 환경:** 보안 강화는 더욱 안전한 온라인 비디오 환경을 의미합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-777">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="012bd-778">자세한 정보</span><span class="sxs-lookup"><span data-stu-id="012bd-778">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (기능 세부 정보 콘텐츠를 제거하지 마세요. 끝)

<br/>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-781">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-781">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="012bd-782">액세스</span><span class="sxs-lookup"><span data-stu-id="012bd-782">Access</span></span>

- <span data-ttu-id="012bd-783">이 업데이트는 업데이트 쿼리가 실행되거나 UPDATE 문이 SQL에 사용될 때 “쿼리가 손상되었습니다” 오류를 일으킬 수 있는 Microsoft Access의 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-783">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="012bd-784">이 업데이트는 Microsoft Access에서 연결된 SQL Server 테이블의 ID 열이 식별되지 않아서 행이 올바르지 않게 삭제된 것으로 보고되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-784">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="012bd-785">이 업데이트는 ADODB 사용시 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-785">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="012bd-786">VB 코드의 레코더 개체에서 오류가 잘못 보고될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-786">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="012bd-787">데이터베이스 내에서 더 이상 액세스 템플릿으로 인해 첨부 열이 실패하지 않아야 합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-787">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="012bd-788">템플릿을 인스턴스화 한 후에는 데이터베이스에 첨부 파일 필드를 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-788">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="012bd-789">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-789">Excel</span></span>

- <span data-ttu-id="012bd-790">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-790">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="012bd-791">이 변경 사항은 소프트웨어 렌더링을 활용하여 특정 인텔 그래픽 드라이버에 발생하는 문제를 우회합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-791">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="012bd-792">spilling 배열이 있는 셀이 있는 열로 텍스트를 변환할 때 일부 사용자에게 충돌이 발생하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-792">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="012bd-793">이 업데이트는 수식 입력줄에서 예상한 것과 다른 글꼴로 텍스트를 표시하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-793">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="012bd-794">일부 현지의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-794">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="012bd-795">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-795">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="012bd-796">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-796">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="012bd-797">스크롤 후 셀을 선택하면 잘못된 셀이 선택되었던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-797">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="012bd-798">신뢰할 수 없는 네트워크 공유에서 보호되는 파일을 편집할 때 Excel이 오류를 발생시킬 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-798">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="012bd-799">일부 현지화의 경우 텍스트를 열로 기능이 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-799">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="012bd-800">사용자가 숨겨진 명명된 범위에 액세스하는 경우 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-800">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="012bd-801">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-801">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="012bd-802">일부 사용자가 경험할 수 있는 OLE (포함 및 연결된 개체) 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-802">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="012bd-803">피벗 차트의 오른쪽 클릭 메뉴를 수정하여 세부 정보를 표시하는 옵션을 사용할 수 있도록 하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-803">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="012bd-804">통합 문서가 열려있지 않은 상태에서 최근 파일을 검색할 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-804">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="012bd-805">통합 문서에 외부 링크가 있는 경우 일부 사용자가 여러 개의 팝업 창을 경험하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-805">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="012bd-806">상황에 맞는 메뉴에서 주석 명령이 표시되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-806">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="012bd-807">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-807">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="012bd-808">CUBEVALUE 함수가 때때로 잘못된 결과를 반환하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-808">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="012bd-809">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-809">Outlook</span></span>

- <span data-ttu-id="012bd-810">피드백 검색 환경을 중단시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-810">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="012bd-811">사용자가 클라우드 설정을 검색할 때 Outlook에서 사용자가 중단되는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-811">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="012bd-812">검색 상자가 높은 dpi 모드로 잘못 정렬되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-812">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="012bd-813">Outlook 프로세스에서 메모리 누수가 사용자에게 관찰되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-813">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="012bd-814">사용자가 일부 상황에서 표시된 SMTP 주소와 일치하지 않는 주소로 보낸 전자 메일을 보게 되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-814">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="012bd-815">이 변경으로 메시지 헤더에서 여러 줄 제목을 볼 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-815">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="012bd-816">파일을 WebDAV 위치에 저장하지 못하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-816">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="012bd-817">SMIME 알고리즘 선택 관련 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-817">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="012bd-818">타사 응용 프로그램에서 전자 메일을 보낼 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-818">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="012bd-819">사용자가 계정 만들기 컨텍스트에서 지원 센터에 문의하려고 할 때 사용자에게 "확인" 버튼이 있는 빈 메시지 상자가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-819">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="012bd-820">사용자가 프로필을 만드는 동안 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-820">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="012bd-821">동기화 슬라이더가 더 작은 설정으로 설정되어 있어도 Outlook이 예기치 않게 모든 메일을 동기화시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-821">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="012bd-822">검은색 테마를 가진 사용자가 흰색 배경에 흰색 텍스트를 표시하는 "시작" 드롭다운을 보게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-822">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="012bd-823">계정 설정을 취소할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-823">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="012bd-824">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-824">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="012bd-825">일부 시나리오에서 플래그가 지정된 항목 강조 표시를 사용하지 않도록 설정하는 옵션이 무시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-825">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="012bd-826">규칙 대화 상자를 열 때 "이 컴퓨터의 규칙이 Microsoft Exchange의 규칙과 일치하지 않습니다." 프롬프트가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-826">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="012bd-827">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-827">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="012bd-828">매우 긴 Outlook 세션에서 메모리 누수를 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-828">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="012bd-829">여러 창에서 동일한 항목을 볼 때 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-829">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="012bd-830">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 현저하게 지연이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-830">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="012bd-831">사용자가 되풀이되는 일정 항목의 일부 인스턴스를 열 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-831">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="012bd-832">Exchange 2010 서버에 사서함이있는 사용자가 일정 항목에 첨부 파일을 추가할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-832">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="012bd-833">디지털 서명된 메시지에 회신 할 때 사용자에게 문제가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-833">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="012bd-834">모임의 위치 필드가 예상치 않게 업데이트되는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-834">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="012bd-835">모임 위치 필드의 쉼표가 세미콜론으로 바뀌는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-835">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="012bd-836">모임을 지운 후 예기치 않게 모임의 위치를 모임을 다시 추가하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-836">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="012bd-837">브라질 시간대로 설정된 회의 및 약속과 관련된 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-837">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="012bd-838">검은색 테마를 가진 사용자가 흰색 배경에 흰색 텍스트를 표시하는 "시작" 드롭다운을 보게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-838">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="012bd-839">이를 통해 첨부 파일 차단 논리를 업데이트하여 Outlook에서 Python 첨부 파일도 차단합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-839">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="012bd-840">웹 추가 기능이 디지털 권한 관리 메시지에 액세스하게 만드는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-840">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="012bd-841">사용자가 프로필을 만드는 동안 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-841">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="012bd-842">사용자가 서명의 이름을 바꿀 때 충돌을 경험하게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-842">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="012bd-843">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-843">PowerPoint</span></span>

- <span data-ttu-id="012bd-844">Shape 관련 문제를 해결했습니다. 붙여넣기 방법: 사용자가 Shape를 사용하여 셰이프를 복사하고 붙여 넣는 경우. 붙여넣기 방법. 선택 대상이 붙여넣기한 셰이프로 변경됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-844">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="012bd-845">레거시 PPT 주석에서 상황에 맞는 메뉴를 사용할 때 충돌을 일으킬 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-845">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="012bd-846">Project</span><span class="sxs-lookup"><span data-stu-id="012bd-846">Project</span></span>

- <span data-ttu-id="012bd-847">읽기 전용 프로젝트를 열 때 사용자가 여러 메시지를 받을 수 있는 문제를 확인했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-847">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="012bd-848">고정된 기간 유형의 100% 작업이 100% 완료 미만으로 잘못 계산할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-848">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="012bd-849">요약 작업 날짜가 항상 제대로 계산되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-849">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="012bd-850">OpenUndoTransaction 메소드를 먼저 실행하지 않으면 OnUndoOrRedo 이벤트가 시작되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-850">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="012bd-851">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-851">Word</span></span>

- <span data-ttu-id="012bd-852">일부 경우에 기존 파일을 저장하면 항상 다른 이름으로 저장 대화 상자가 나타나고 파일이 실제로는 저장되지 않는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-852">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="012bd-853">문서 블록 이끌이가 “사용자가 스타일, 문서 블록을 수정했습니다.”라는 잘못된 알림을 표시할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-853">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="012bd-854">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-854">Office Suite</span></span>

- <span data-ttu-id="012bd-855">이 변경 사항은 마커가 포함된 일부 분산형 차트의 느린 렌더링 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-855">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="012bd-856">이 변경 사항은 인텔 통합 GPU를 활용하는 그래픽 어댑터에 보고된 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-856">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="012bd-857">상대적인 마감일이 처음 설정된 경우에만 작동하는 ODT 및 GPO 업데이트 마감일 설정 버그를 수정했습니다. 이 픽스는 후속 업데이트에 대한 상대적인 마감일도 사용할 수 있도록 해줍니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-857">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="012bd-858">Office 업데이트에서 로컬 또는 네트워크 공유 또는 Configuration Manager에서 제공하는 위치와 같은 의도된 원본 대신 Office CDN에서 파일을 예기치 않게 다운로드했을 수 있는 문제를 해결하였습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-858">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="012bd-859">동일한 SharePoint 라이브러리의 Word/Excel/PowerPoint에서 여러 문서를 열 때 첫 번째로 열린 문서만 정책 준수에 대한 검사가 이뤄지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-859">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-february-11"></a><span data-ttu-id="012bd-861">버전 1908: 2월 11일</span><span class="sxs-lookup"><span data-stu-id="012bd-861">Version 1908: February 11</span></span>
<span data-ttu-id="012bd-862">*버전 1908 (빌드 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="012bd-862">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="012bd-863">[여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) 나열된 보안 업데이트</span><span class="sxs-lookup"><span data-stu-id="012bd-863">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-865">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-865">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="012bd-866">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-866">Excel</span></span>

- <span data-ttu-id="012bd-867">이 업데이트는 VBA를 사용하여 차트의 머리글/바닥글에 이미지를 추가할 때마다 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-867">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="012bd-868">인쇄 미리보기 또는 인쇄 시 그룹 상자 컨트롤의 테두리가 보이지 않던 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-868">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="012bd-869">사용자가 영문이 아닌 일부 문자의 집합을 사용 시 변경 내용을 저장할 때 오류가 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-869">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="012bd-870">차트가 포함된 통합 문서를 저장할 때 차트 머리글의 이미지 파일 크기가 커지는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-870">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="012bd-871">선택 범위를 상호 참조 도서와 동기화하여 상호 참조 도서에서 DBCS 문자가 손상되는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-871">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="012bd-872">자동 맞춤을 사용하여 행 높이를 조정할 때 확인란 컨트롤이 축소될 수있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-872">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="012bd-873">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-873">Outlook</span></span>

- <span data-ttu-id="012bd-874">잘못된 보낸 사람 주소를 지정할 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-874">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="012bd-875">충돌 메시지를 처리할 때 사용자에게 동기화 오류가 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-875">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="012bd-876">Outlook을 시작할 때 사용자가 프로필을 로딩할 때 화면이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-876">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="012bd-877">보기를 변경할 때 사용자에게 간헐적인 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-877">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="012bd-878">Citrix 환경에서 30개 이상의 캘린더를 볼 때 사용자에게 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-878">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="012bd-879">[여기](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)에는 이전 버전에 대해 문서화된 개별 KB가 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-879">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="012bd-880">사용자가 공유 일정 폴더를 OST와 동기화하는 데 문제가있어 이러한 폴더와 상호 작용할 때 권한 오류가 발생하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-880">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="012bd-881">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-881">PowerPoint</span></span>

- <span data-ttu-id="012bd-882">복사-붙여넣기 시나리오 개선 파워포인트 슬라이드에서 도형을 복사하고 루프의 다른 슬라이드에 붙여넣을 때 예외적으로 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-882">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="012bd-883">공동 작업 사용자 간에 성능이 저하되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-883">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="012bd-884">증분 방식으로 열린 파일에 둘 이상의 포함된 미디어 스트림이 있는 슬라이드가 포함되어 있을 때 발생할 수있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-884">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="012bd-885">PowerPoint를 처음 시작할 때 신뢰할 수 없는 추가 기능에 대해 보안 경고 메시지 표시줄이 나타나지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-885">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="012bd-886">Project</span><span class="sxs-lookup"><span data-stu-id="012bd-886">Project</span></span>

- <span data-ttu-id="012bd-887">기본 일정이 변경될 때 리소스 일정이 업데이트되지 않아 작업표와 프로젝트 계획 간에 실제 작업이 다를 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-887">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="012bd-888">Word</span><span class="sxs-lookup"><span data-stu-id="012bd-888">Word</span></span>

- <span data-ttu-id="012bd-889">더 이상 사용되지 않는 API에서 이동하여 Word의 충돌 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-889">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="012bd-890">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-890">Office Suite</span></span>

- <span data-ttu-id="012bd-891">이 변경은 손상된 파일을 연 후 이미지를 올바르게 렌더링하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-891">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

## <a name="version-1908-january-14"></a><span data-ttu-id="012bd-893">버전 1908: 1월 14일</span><span class="sxs-lookup"><span data-stu-id="012bd-893">Version 1908: January 14</span></span>
<span data-ttu-id="012bd-894">*버전 1908(빌드 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="012bd-894">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="012bd-895">나열된 보안 업데이트는 [여기](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="012bd-895">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 시작)

### <a name="resolved-issues"></a><span data-ttu-id="012bd-897">해결된 문제</span><span class="sxs-lookup"><span data-stu-id="012bd-897">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="012bd-898">Excel</span><span class="sxs-lookup"><span data-stu-id="012bd-898">Excel</span></span>

- <span data-ttu-id="012bd-899">문서 타이틀에 대한 네덜란드어 단축키가 Alt-G로 변경되었습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-899">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="012bd-900">포함된 통합 문서를 열 때 리본 사용자 지정이 로드되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-900">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="012bd-901">추가 기능을 통해 연 WPF(Windows Presentation Foundation) 양식의 콤보 상자에서 항목을 선택할 수 없는 문제가 발생했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-901">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="012bd-902">Outlook</span><span class="sxs-lookup"><span data-stu-id="012bd-902">Outlook</span></span>

- <span data-ttu-id="012bd-903">사용자가 바로 가기 키를 통해 사서함 폴더와 상호 작용할 때 현저하게 지연이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-903">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="012bd-904">대체 보낸 사람을 사용할 때 정책 팁이 표시되지 않게 하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-904">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="012bd-905">사용자가 현재 상태 정보를 업데이트할 때 일시적으로 작동이 중지되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-905">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="012bd-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="012bd-906">PowerPoint</span></span>

- <span data-ttu-id="012bd-907">한 프레젠테이션에서 다른 프레젠테이션으로 슬라이드를 복사하여 중복하는 경우 마스터가 복제되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-907">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="012bd-908">최신 메모가 포함된 파일에는 지원되지 않는 버전에서 열었을 경우 노란색 경고가 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-908">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="012bd-909">Office 제품군</span><span class="sxs-lookup"><span data-stu-id="012bd-909">Office Suite</span></span>

- <span data-ttu-id="012bd-910">Office 업데이트 메시지가 다른 언어로 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-910">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="012bd-911">앞으로 Office 업데이트 메시지 언어가 Windows 표시 언어와 정확하게 일치할 것입니다.  </span><span class="sxs-lookup"><span data-stu-id="012bd-911">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="012bd-912">사용자가 관리자가 아니거나 시스템 계정에 네트워크 연결이 없는 경우에 업데이트가 적용되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-912">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (버그 세부 정보 콘텐츠를 제거하지 마세요. 끝)

> [!NOTE]
> <span data-ttu-id="012bd-914">Office를 사용하는 데 발생한 문제에 대해 도움이 필요하면 [Microsoft의 Answers 포럼](https://answers.microsoft.com/) 또는 [기술 커뮤니티](https://techcommunity.microsoft.com/)에 질문을 게시하거나 [지원 서비스](https://support.microsoft.com/contactus)에 문의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="012bd-914">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (관리 센터 메타데이터 콘텐츠를 수정하지 마세요. 시작)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|버전 2002년 7월 14일|)
[//]: # (관리 센터 메타데이터 콘텐츠를 수정하지 마세요. 끝)
