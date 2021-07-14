---
title: ODT(Office 배포 도구)에 대한 릴리스 기록
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: IT 전문가에게 ODT(Office 배포 도구)의 릴리스 기록을 제공합니다.
ms.openlocfilehash: f6df62267f7f2035f610867721b3dc1b9f65a1bd
ms.sourcegitcommit: 4f5536e809f58462d81c708c153390ebfd1abc4e
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 07/13/2021
ms.locfileid: "53409584"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="f7f98-103">Office 배포 도구에 대한 릴리스 기록</span><span class="sxs-lookup"><span data-stu-id="f7f98-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="f7f98-104">ODT(Office 배포 도구)는 Microsoft 365 앱과 같이 간편 실행 버전의 Office를 클라이언트 컴퓨터에 다운로드하여 배포하는 데 사용할 수 있는 명령줄 도구입니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="f7f98-p101">ODT를 사용하면 Office 설치를 보다 잘 제어할 수 있습니다. 즉, 설치되는 제품 및 언어, 해당 제품의 업데이트 방법 및 사용자에게 설치 환경을 표시할지 여부 등을 정의할 수 있습니다. ODT 사용 방법에 대한 자세한 내용은 [Office 배포 도구 및 개요](/deployoffice/overview-of-the-office-2016-deployment-tool)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="f7f98-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="f7f98-108">**지원되는 운영체제**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="f7f98-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="f7f98-109">**설치 방법**: 다운로드한 다음 Office 배포 도구 실행 파일(setup.exe) 및 샘플 구성 파일(configuration.xml)이 포함된 자동 압축 풀기 실행 파일을 실행합니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="f7f98-110">Office 배포 도구 다운로드</span><span class="sxs-lookup"><span data-stu-id="f7f98-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="july-12-2021"></a><span data-ttu-id="f7f98-111">2021년 7월 12일</span><span class="sxs-lookup"><span data-stu-id="f7f98-111">July 12, 2021</span></span>
<span data-ttu-id="f7f98-112">버전 16.0.14131.20278(setup.exe 버전 16.0.14131.20278)</span><span class="sxs-lookup"><span data-stu-id="f7f98-112">Version 16.0.14131.20278 (setup.exe version 16.0.14131.20278)</span></span>
- <span data-ttu-id="f7f98-113">특정 경우에 RemoveMSI가 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-113">Fixed an issue where RemoveMSI would fail in certain cases</span></span>
- <span data-ttu-id="f7f98-114">setup.exe의 동시 실행을 검색하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-114">Fixed an issue detecting concurrent executions of setup.exe</span></span>
- <span data-ttu-id="f7f98-115">ARM 플랫폼에 대한 안정성 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-115">Reliability fixes for ARM platforms</span></span>


## <a name="june-17-2021"></a><span data-ttu-id="f7f98-116">2021년 6월 17일</span><span class="sxs-lookup"><span data-stu-id="f7f98-116">June 17, 2021</span></span>
<span data-ttu-id="f7f98-117">버전 16.0.14026.20306 (setup.exe 버전 16.0.14026.20306)</span><span class="sxs-lookup"><span data-stu-id="f7f98-117">Version 16.0.14026.20306 (setup.exe version 16.0.14026.20306)</span></span>
- <span data-ttu-id="f7f98-118">일부 OS 구성에 대해 MatchOS 언어 옵션을 사용하는 작업이 실패하는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-118">Fixes an issue where operations using the MatchOS language option were failing for some OS configurations</span></span>


## <a name="june-7-2021"></a><span data-ttu-id="f7f98-119">2021년 6월 7일</span><span class="sxs-lookup"><span data-stu-id="f7f98-119">June 7, 2021</span></span>
<span data-ttu-id="f7f98-120">버전 16.0.14026.20254(setup.exe 버전 16.0.14026.20252)</span><span class="sxs-lookup"><span data-stu-id="f7f98-120">Version 16.0.14026.20254 (setup.exe version 16.0.14026.20252)</span></span>
- <span data-ttu-id="f7f98-121">ARM 플랫폼에 대한 안정성 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-121">Reliability fixes for ARM platforms</span></span>


## <a name="may-10-2021"></a><span data-ttu-id="f7f98-122">2021년 5월 10일</span><span class="sxs-lookup"><span data-stu-id="f7f98-122">May 10, 2021</span></span>
<span data-ttu-id="f7f98-123">버전 16.0.13929.20296 (setup.exe 버전 16.0.13929.20238)</span><span class="sxs-lookup"><span data-stu-id="f7f98-123">Version 16.0.13929.20296 (setup.exe version 16.0.13929.20238)</span></span>
- <span data-ttu-id="f7f98-124">구성 파일에 MigrateArch 및 RemoveMSI가 모두 포함되어 있는 경우 /configure 모드가 실패할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-124">Fixed an issue where /configure mode may fail if a configuration file includes both MigrateArch and RemoveMSI</span></span>
- <span data-ttu-id="f7f98-125">추가적인 안정성 향상</span><span class="sxs-lookup"><span data-stu-id="f7f98-125">Additional reliability improvements</span></span>

## <a name="april-13-2021"></a><span data-ttu-id="f7f98-126">2021년 4월 13일</span><span class="sxs-lookup"><span data-stu-id="f7f98-126">April 13, 2021</span></span>
<span data-ttu-id="f7f98-127">버전 16.0.13901.20336(setup.exe 버전 16.0.13901.20328)</span><span class="sxs-lookup"><span data-stu-id="f7f98-127">Version 16.0.13901.20336 (setup.exe version 16.0.13901.20328)</span></span>
- <span data-ttu-id="f7f98-128">Office가 이미 설치된 장치에서 실행되는 구성 작업을 위한 안정성 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-128">Reliability fixes for configure operations that are run on devices with Office already installed</span></span>
- <span data-ttu-id="f7f98-129">일부 시나리오에서 중복 진행률 UI가 표시되지 않도록 수정</span><span class="sxs-lookup"><span data-stu-id="f7f98-129">Fixes to avoid showing duplicate progress UI in some scenarios</span></span>
- <span data-ttu-id="f7f98-130">UI에 표시된 오류 코드 정확도 향상</span><span class="sxs-lookup"><span data-stu-id="f7f98-130">Improvements to error code accuracy shown in UI</span></span>
- <span data-ttu-id="f7f98-131">ARM 플랫폼에 대한 안정성 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-131">Reliability fixes for ARM platforms</span></span>

## <a name="march-23-2021"></a><span data-ttu-id="f7f98-132">2021년 3월 23일</span><span class="sxs-lookup"><span data-stu-id="f7f98-132">March 23, 2021</span></span>
<span data-ttu-id="f7f98-133">버전 16.0.13801.20360(setup.exe 버전 16.0.13801.20340)</span><span class="sxs-lookup"><span data-stu-id="f7f98-133">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="f7f98-134">예정된 Office 제품 릴리스 지원 변경 사항</span><span class="sxs-lookup"><span data-stu-id="f7f98-134">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="f7f98-135">ARM 플랫폼에 대한 안정성 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-135">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="f7f98-136">2021년 2월 25일</span><span class="sxs-lookup"><span data-stu-id="f7f98-136">February 25, 2021</span></span>
<span data-ttu-id="f7f98-137">버전 16.0.13628.20476(setup.exe 버전 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="f7f98-137">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="f7f98-138">수십 개의 언어를 지정하는 configuration.xml 파일이 유효성을 검사하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-138">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="f7f98-139">마이그레이션 시나리오에서 FORCEAPPSHUTDOWN 속성이 존중되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-139">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="f7f98-140">configuration.xml에서 2개 이상의 PIDKEY 특성을 지정하여 PIDKeys를 설치하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-140">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="f7f98-141">2021년 2월 9일</span><span class="sxs-lookup"><span data-stu-id="f7f98-141">February 9, 2021</span></span>
<span data-ttu-id="f7f98-142">버전 16.0.13628.20274(setup.exe 버전 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="f7f98-142">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="f7f98-143">Windows 8.0에서 지원되지 않는 설치 작업에 대해 경고하고 이를 방지하는 유효성 검사가 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-143">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="f7f98-144">ARM64 장치에 대한 안정성 해결 방법</span><span class="sxs-lookup"><span data-stu-id="f7f98-144">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="f7f98-145">2021년 1월 12일</span><span class="sxs-lookup"><span data-stu-id="f7f98-145">January 12, 2021</span></span>
<span data-ttu-id="f7f98-146">버전 16.0.13530.20376 (setup.exe 버전 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="f7f98-146">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="f7f98-147">손상된 제품 등록 또는 비표준 제품 등록으로 인해 RemoveMSI 작업이 실패할 수 있는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-147">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="f7f98-148">2020년 12월 21일</span><span class="sxs-lookup"><span data-stu-id="f7f98-148">December 21, 2020</span></span>
<span data-ttu-id="f7f98-149">버전 16.0.13426.20370(setup.exe 버전 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="f7f98-149">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="f7f98-150">PerpetualVL2019 채널에서 ProofingTools의 로컬 소스 설치가 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-150">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="f7f98-151">기존 설치에 전체 Office 언어가 아닌 추가 제품을 추가할 때 간편 실행 클라이언트가 자체 업데이트를 시도하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-151">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="f7f98-152">2020년 12월 8일</span><span class="sxs-lookup"><span data-stu-id="f7f98-152">December 8, 2020</span></span>
<span data-ttu-id="f7f98-153">버전 16.0.13426.20308 (setup.exe 버전 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="f7f98-153">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="f7f98-154">디바이스에 Office 제품이 비영구 2019 채널에서 설치된 경우 다운로드 모드가 영구 2019 채널 다운로드를 차단하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-154">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="f7f98-155">구성 XML에 명시적 버전을 지정한 다운로드 모드를 통해 생성된 로컬 소스에 대해 아키텍처 마이그레이션이 실패하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-155">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="f7f98-156">2020년 11월 23일</span><span class="sxs-lookup"><span data-stu-id="f7f98-156">November 23, 2020</span></span>
<span data-ttu-id="f7f98-157">버전 16.0.13328.20420(setup.exe 버전 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="f7f98-157">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="f7f98-158">언어 교정 도구가/다운로드 모드로 다운로드되지 않는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-158">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="f7f98-159">관리자 권한 없는 사용자에게 실행 될 경우 다운로드 모드가 실패 하는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-159">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="f7f98-160">구성 XML에서 버전 속성을 지정하면 /download 모드에서 불완전한 다운로드가 발생하는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-160">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="f7f98-161">추출 시 Office 배포 도구 이름이 "setup.exe"로 지정되지 않은 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-161">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="f7f98-162">구성 XML에서 채널 특성이 제공되는 경우 설치 원본 우선 순위 지정에 대한 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-162">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="f7f98-163">2020년 11월 10일</span><span class="sxs-lookup"><span data-stu-id="f7f98-163">November 10, 2020</span></span>
<span data-ttu-id="f7f98-164">버전 16.0.13328.20356 (setupODT.exe 버전 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="f7f98-164">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="f7f98-165">안정성 및 복원 기능 개선</span><span class="sxs-lookup"><span data-stu-id="f7f98-165">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="f7f98-166">혼동을 방지하고 보다 쉽게 설치 오류를 진단하기 위해 이제 ODT는 기본적으로 setupODT.exe로 명명됩니다. </span><span class="sxs-lookup"><span data-stu-id="f7f98-166">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="f7f98-167">2020년 10월 29일</span><span class="sxs-lookup"><span data-stu-id="f7f98-167">October 29, 2020</span></span>
<span data-ttu-id="f7f98-168">버전 16.0.13328.20292 (setup.exe 버전 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="f7f98-168">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="f7f98-169">RemoveMSI를 사용하는 경우 특정 Office 2007 제품이 예기치 않게 설치를 차단하는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-169">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="f7f98-170">2020년 10월 14일</span><span class="sxs-lookup"><span data-stu-id="f7f98-170">October 14, 2020</span></span>
<span data-ttu-id="f7f98-171">버전 16.0.13231.20368 (setup.exe 버전 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="f7f98-171">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="f7f98-172">지정된 채널이 없는 경우 모든 제품은 이제 기본적으로 월간 채널 사용</span><span class="sxs-lookup"><span data-stu-id="f7f98-172">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="f7f98-173">다른 DLL을 포함하는 디렉터리에서 ODT를 실행하는 경우 보안을 향상</span><span class="sxs-lookup"><span data-stu-id="f7f98-173">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="f7f98-174">안정성 및 복원 기능 개선</span><span class="sxs-lookup"><span data-stu-id="f7f98-174">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="f7f98-175">2020년 6월 9일</span><span class="sxs-lookup"><span data-stu-id="f7f98-175">June 9, 2020</span></span>

<span data-ttu-id="f7f98-176">버전 16.0.12827.20268(setup.exe 버전 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="f7f98-176">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="f7f98-177">채널을 지정하지 않은 경우 현재 채널이 기본 채널이 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-177">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="f7f98-178">월 단위 기업 채널에 대한 지원 추가됨</span><span class="sxs-lookup"><span data-stu-id="f7f98-178">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="f7f98-179">새 채널 이름에 대한 지원 추가됨</span><span class="sxs-lookup"><span data-stu-id="f7f98-179">Added support for new channel names</span></span>
- <span data-ttu-id="f7f98-180">일부 언어 리소스를 사용할 수 없는 경우에도 계속 설치할 수 있는 추가 복원 기능</span><span class="sxs-lookup"><span data-stu-id="f7f98-180">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="f7f98-181">MSIRemove 2007 제품 제거를 위해 확장된 제거 기능</span><span class="sxs-lookup"><span data-stu-id="f7f98-181">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="f7f98-182">MSIRemove 데이터베이스 엔진을 제거하기 위해 확장된 제거 기능</span><span class="sxs-lookup"><span data-stu-id="f7f98-182">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="f7f98-183">2020년 4월 15일</span><span class="sxs-lookup"><span data-stu-id="f7f98-183">April 15, 2020</span></span>

<span data-ttu-id="f7f98-184">버전 16.0.12624.20320 (setup.exe 버전 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="f7f98-184">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="f7f98-185">Windows 7 관련 종료 Office 버전에 대한 지원을 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-185">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="f7f98-186">사용자 지정 설정이 예상대로 적용되지 않을 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-186">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="f7f98-187">불필요한 .cat 파일이 예기치 않게 다운로드될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-187">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="f7f98-188">2020년 1월 16일</span><span class="sxs-lookup"><span data-stu-id="f7f98-188">January 16, 2020</span></span>

<span data-ttu-id="f7f98-189">버전 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="f7f98-189">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="f7f98-190">여러 언어를 설치하는 경우 Office 설치 UI가 잘못 된 언어로 표시될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-190">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="f7f98-191">특정 언어 교정 도구 패키지를 설치할 때 Office 설치가 예기치 않게 실패할 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-191">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="f7f98-192">[Bing에서 Microsoft 검색](/deployoffice/microsoft-search-bing)의 초기 배포를 선택적으로 제어하는 작업에 대한 지원을 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-192">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="f7f98-193">2019년 10월 31일</span><span class="sxs-lookup"><span data-stu-id="f7f98-193">October 31, 2019</span></span>

<span data-ttu-id="f7f98-194">버전 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="f7f98-194">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="f7f98-195">비즈니스용 Skype Basic 2019가 2019 영구 엔터프라이즈 볼륨 라이선스 제품과 함께 설치되는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-195">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="f7f98-196">프록시를 사용할 경우에 특정 조건에서 예기치 않게 ODT 다운로드 모드가 실패하는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f7f98-196">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="f7f98-197">ODT 다운로드 모드에서 포트 80 이외의 다른 포트를 사용하여 HTTP를 통한 다운로드를 할 수 있도록 하는 새로운 기능</span><span class="sxs-lookup"><span data-stu-id="f7f98-197">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="f7f98-198">2019년 7월 10일</span><span class="sxs-lookup"><span data-stu-id="f7f98-198">July 10, 2019</span></span>

<span data-ttu-id="f7f98-199">버전 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="f7f98-199">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="f7f98-200">Office 2019: Access Runtime, 비즈니스용 Skype Basic과 함께 설치할 때 추가 제품에 대한 지원이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-200">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="f7f98-201">MSI에서 업그레이드할 때 독립 실행형 제품의 조건부 설치 지원이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-201">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="f7f98-202">2019년 4월 23일</span><span class="sxs-lookup"><span data-stu-id="f7f98-202">April 23, 2019</span></span>

<span data-ttu-id="f7f98-203">버전 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="f7f98-203">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="f7f98-204">RemoveMSI=True 관련 레지스트리 설정을 정리하는 버그가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-204">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="f7f98-205">예기치 않은 오류(E_UNEXPECTED)에 대한 추가 세부 정보를 제공하는 오류 코드를 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-205">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="f7f98-206">2019년 4월 16일</span><span class="sxs-lookup"><span data-stu-id="f7f98-206">April 16 2019</span></span>

<span data-ttu-id="f7f98-207">버전 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="f7f98-207">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="f7f98-208">새로운 MigrateArch 특성을 사용하여 32비트 C2R을 64비트 C2R로 업그레이드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-208">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="f7f98-209">웹 위치(http 및 https)에 저장된 구성 XML 파일에 액세스할 수 있도록/configure에 대한 논리가 업데이트되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-209">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="f7f98-210">MatchInstalled는 제품 또는 언어를 추가할 때 ODT가 기존 버전과 일치할 수 있게 해주는 새로운 특성으로 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f7f98-210">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="f7f98-211">2019년 3월 13일</span><span class="sxs-lookup"><span data-stu-id="f7f98-211">March 13, 2019</span></span>

<span data-ttu-id="f7f98-212">버전 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="f7f98-212">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="f7f98-213">업그레이드 및 마이그레이션 시나리오 개선</span><span class="sxs-lookup"><span data-stu-id="f7f98-213">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="f7f98-214">2019년 1월 14일</span><span class="sxs-lookup"><span data-stu-id="f7f98-214">January 14, 2019</span></span>

<span data-ttu-id="f7f98-215">버전 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="f7f98-215">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="f7f98-216">배포 구성에 대한 로깅과 원격 분석 향상</span><span class="sxs-lookup"><span data-stu-id="f7f98-216">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="f7f98-217">관련 링크</span><span class="sxs-lookup"><span data-stu-id="f7f98-217">Related links</span></span>

[<span data-ttu-id="f7f98-218">ODT 다운로드 센터</span><span class="sxs-lookup"><span data-stu-id="f7f98-218">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)