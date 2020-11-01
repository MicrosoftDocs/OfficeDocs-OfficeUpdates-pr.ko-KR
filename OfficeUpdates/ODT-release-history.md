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
ms.openlocfilehash: f578849552bb4fda0198bad3651170923d0ceb35
ms.sourcegitcommit: b19297da26ce6f740f3e2c94ea8a6c5d4e2aaa75
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/30/2020
ms.locfileid: "48806796"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="ff268-103">Office 배포 도구에 대한 릴리스 기록</span><span class="sxs-lookup"><span data-stu-id="ff268-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="ff268-104">ODT(Office 배포 도구)는 Microsoft 365 앱과 같이 간편 실행 버전의 Office를 클라이언트 컴퓨터에 다운로드하여 배포하는 데 사용할 수 있는 명령줄 도구입니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="ff268-105">ODT를 사용하여 Office 설치를 더 강력하게 제어할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="ff268-106">설치할 제품과 언어, 제품 업데이트 방법 및 사용자에게 설치 환경 표시 여부를 정의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="ff268-107">ODT를 사용하는 방법에 대한 자세한 내용은 [Office 배포 도구 개요](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="ff268-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="ff268-108">**지원되는 운영체제** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="ff268-108">**Supported Operating System** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="ff268-109">**설치 방법** : 다운로드한 다음 Office 배포 도구 실행 파일(setup.exe) 및 샘플 구성 파일(configuration.xml)이 포함된 자동 압축 풀기 실행 파일을 실행합니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-109">**Install Instructions** : Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="ff268-110">Office 배포 도구 다운로드</span><span class="sxs-lookup"><span data-stu-id="ff268-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="october-29-2020"></a><span data-ttu-id="ff268-111">2020년 10월 29일</span><span class="sxs-lookup"><span data-stu-id="ff268-111">October 29, 2020</span></span>
<span data-ttu-id="ff268-112">버전 16.0.13328.20292 (setup.exe 버전 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="ff268-112">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="ff268-113">RemoveMSI를 사용하는 경우 특정 Office 2007 제품이 예기치 않게 설치를 차단하는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="ff268-113">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="ff268-114">2020년 10월 14일</span><span class="sxs-lookup"><span data-stu-id="ff268-114">October 14, 2020</span></span>
<span data-ttu-id="ff268-115">버전 16.0.13231.20368 (setup.exe 버전 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="ff268-115">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="ff268-116">지정된 채널이 없는 경우 모든 제품은 이제 기본적으로 월간 채널 사용</span><span class="sxs-lookup"><span data-stu-id="ff268-116">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="ff268-117">다른 DLL을 포함하는 디렉터리에서 ODT를 실행하는 경우 보안을 향상</span><span class="sxs-lookup"><span data-stu-id="ff268-117">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="ff268-118">안정성 및 복원 기능 개선</span><span class="sxs-lookup"><span data-stu-id="ff268-118">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="ff268-119">2020년 6월 9일</span><span class="sxs-lookup"><span data-stu-id="ff268-119">June 9, 2020</span></span>

<span data-ttu-id="ff268-120">버전 16.0.12827.20268(setup.exe 버전 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="ff268-120">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="ff268-121">채널을 지정하지 않은 경우 현재 채널이 기본 채널이 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-121">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="ff268-122">월 단위 기업 채널에 대한 지원 추가됨</span><span class="sxs-lookup"><span data-stu-id="ff268-122">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="ff268-123">새 채널 이름에 대한 지원 추가됨</span><span class="sxs-lookup"><span data-stu-id="ff268-123">Added support for new channel names</span></span>
- <span data-ttu-id="ff268-124">일부 언어 리소스를 사용할 수 없는 경우에도 계속 설치할 수 있는 추가 복원 기능</span><span class="sxs-lookup"><span data-stu-id="ff268-124">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="ff268-125">MSIRemove 2007 제품 제거를 위해 확장된 제거 기능</span><span class="sxs-lookup"><span data-stu-id="ff268-125">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="ff268-126">MSIRemove 데이터베이스 엔진을 제거하기 위해 확장된 제거 기능</span><span class="sxs-lookup"><span data-stu-id="ff268-126">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="ff268-127">2020년 4월 15일</span><span class="sxs-lookup"><span data-stu-id="ff268-127">April 15, 2020</span></span>

<span data-ttu-id="ff268-128">버전 16.0.12624.20320 (setup.exe 버전 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="ff268-128">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="ff268-129">Windows 7 관련 종료 Office 버전에 대한 지원을 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-129">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="ff268-130">사용자 지정 설정이 예상대로 적용되지 않을 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-130">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="ff268-131">불필요한 .cat 파일이 예기치 않게 다운로드될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-131">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="ff268-132">2020년 1월 16일</span><span class="sxs-lookup"><span data-stu-id="ff268-132">January 16, 2020</span></span>

<span data-ttu-id="ff268-133">버전 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="ff268-133">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="ff268-134">여러 언어를 설치하는 경우 Office 설치 UI가 잘못 된 언어로 표시될 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-134">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="ff268-135">특정 언어 교정 도구 패키지를 설치할 때 Office 설치가 예기치 않게 실패할 수 있는 문제를 해결합니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-135">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="ff268-136">[Bing에서 Microsoft 검색](https://go.microsoft.com/fwlink/p/?linkid=2109345)의 초기 배포를 선택적으로 제어하는 작업에 대한 지원을 추가합니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-136">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="ff268-137">2019년 10월 31일</span><span class="sxs-lookup"><span data-stu-id="ff268-137">October 31, 2019</span></span>

<span data-ttu-id="ff268-138">버전 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="ff268-138">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="ff268-139">비즈니스용 Skype Basic 2019가 2019 영구 엔터프라이즈 볼륨 라이선스 제품과 함께 설치되는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="ff268-139">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="ff268-140">프록시를 사용할 경우에 특정 조건에서 예기치 않게 ODT 다운로드 모드가 실패하는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="ff268-140">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="ff268-141">ODT 다운로드 모드에서 포트 80 이외의 다른 포트를 사용하여 HTTP를 통한 다운로드를 할 수 있도록 하는 새로운 기능</span><span class="sxs-lookup"><span data-stu-id="ff268-141">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="ff268-142">2019년 7월 10일</span><span class="sxs-lookup"><span data-stu-id="ff268-142">July 10, 2019</span></span>

<span data-ttu-id="ff268-143">버전 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="ff268-143">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="ff268-144">Office 2019: Access Runtime, 비즈니스용 Skype Basic과 함께 설치할 때 추가 제품에 대한 지원이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-144">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="ff268-145">MSI에서 업그레이드할 때 독립 실행형 제품의 조건부 설치 지원이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-145">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="ff268-146">2019년 4월 23일</span><span class="sxs-lookup"><span data-stu-id="ff268-146">April 23, 2019</span></span>

<span data-ttu-id="ff268-147">버전 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="ff268-147">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="ff268-148">RemoveMSI=True 관련 레지스트리 설정을 정리하는 버그가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-148">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="ff268-149">예기치 않은 오류(E_UNEXPECTED)에 대한 추가 세부 정보를 제공하는 오류 코드를 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-149">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="ff268-150">2019년 4월 16일</span><span class="sxs-lookup"><span data-stu-id="ff268-150">April 16 2019</span></span>

<span data-ttu-id="ff268-151">버전 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="ff268-151">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="ff268-152">새로운 MigrateArch 특성을 사용하여 32비트 C2R을 64비트 C2R로 업그레이드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-152">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="ff268-153">웹 위치(http 및 https)에 저장된 구성 XML 파일에 액세스할 수 있도록/configure에 대한 논리가 업데이트되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-153">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="ff268-154">MatchInstalled는 제품 또는 언어를 추가할 때 ODT가 기존 버전과 일치할 수 있게 해주는 새로운 특성으로 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="ff268-154">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="ff268-155">2019년 3월 13일</span><span class="sxs-lookup"><span data-stu-id="ff268-155">March 13, 2019</span></span>

<span data-ttu-id="ff268-156">버전 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="ff268-156">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="ff268-157">업그레이드 및 마이그레이션 시나리오 개선</span><span class="sxs-lookup"><span data-stu-id="ff268-157">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="ff268-158">2019년 1월 14일</span><span class="sxs-lookup"><span data-stu-id="ff268-158">January 14, 2019</span></span>

<span data-ttu-id="ff268-159">버전 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="ff268-159">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="ff268-160">배포 구성에 대한 로깅과 원격 분석 향상</span><span class="sxs-lookup"><span data-stu-id="ff268-160">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="ff268-161">관련 링크</span><span class="sxs-lookup"><span data-stu-id="ff268-161">Related links</span></span>

[<span data-ttu-id="ff268-162">ODT 다운로드 센터</span><span class="sxs-lookup"><span data-stu-id="ff268-162">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)