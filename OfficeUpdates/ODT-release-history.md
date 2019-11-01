---
title: ODT(Office 배포 도구)에 대한 릴리스 기록
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: IT 전문가에게 ODT(Office 배포 도구)의 릴리스 기록을 제공합니다.
ms.openlocfilehash: 65dbad6110d38fd98fb7b6df94c2a54df2f89459
ms.sourcegitcommit: 6570d42ebb04c11b9aa40dac7825ae8da9694e10
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 10/31/2019
ms.locfileid: "37902404"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="f8252-103">Office 배포 도구에 대한 릴리스 기록</span><span class="sxs-lookup"><span data-stu-id="f8252-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="f8252-104">ODT(Office 배포 도구)는 Office 365 ProPlus와 같이 간편 실행 버전의 Office를 클라이언트 컴퓨터에 다운로드하여 배포하는 데 사용할 수 있는 명령줄 도구입니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Office 365 ProPlus, to your client computers.</span></span> 


<span data-ttu-id="f8252-105">ODT를 사용하여 Office 설치를 더 강력하게 제어할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="f8252-106">설치할 제품과 언어, 제품 업데이트 방법 및 사용자에게 설치 환경 표시 여부를 정의할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="f8252-107">ODT를 사용하는 방법에 대한 자세한 내용은 [Office 배포 도구 개요](https://docs.microsoft.com/ko-KR/deployoffice/overview-of-the-office-2016-deployment-tool)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="f8252-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/ko-KR/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="f8252-108">**지원되는 운영 체제**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="f8252-108">**Supported Operating System**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span></span> 
 
 <span data-ttu-id="f8252-109">**설치 방법**: 다운로드한 다음 Office 배포 도구 실행 파일(setup.exe) 및 샘플 구성 파일(configuration.xml)이 포함된 자동 압축 풀기 실행 파일을 실행합니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="f8252-110">Office 배포 도구 다운로드</span><span class="sxs-lookup"><span data-stu-id="f8252-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="october-31-2019"></a><span data-ttu-id="f8252-111">2019년 10월 31일</span><span class="sxs-lookup"><span data-stu-id="f8252-111">October 31, 2019</span></span>

<span data-ttu-id="f8252-112">버전 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="f8252-112">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="f8252-113">비즈니스용 Skype Basic 2019가 2019 영구 엔터프라이즈 볼륨 라이선스 제품과 함께 설치되는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f8252-113">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="f8252-114">프록시를 사용할 경우에 특정 조건에서 예기치 않게 ODT 다운로드 모드가 실패하는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="f8252-114">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="f8252-115">ODT 다운로드 모드에서 포트 80 이외의 다른 포트를 사용하여 HTTP를 통한 다운로드를 할 수 있도록 하는 새로운 기능</span><span class="sxs-lookup"><span data-stu-id="f8252-115">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="f8252-116">2019년 7월 10일</span><span class="sxs-lookup"><span data-stu-id="f8252-116">July 10, 2019</span></span>

<span data-ttu-id="f8252-117">버전 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="f8252-117">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="f8252-118">Office 2019: Access Runtime, 비즈니스용 Skype Basic과 함께 설치할 때 추가 제품에 대한 지원이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-118">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="f8252-119">MSI에서 업그레이드할 때 독립 실행형 제품의 조건부 설치 지원이 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-119">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="f8252-120">2019년 4월 23일</span><span class="sxs-lookup"><span data-stu-id="f8252-120">April 23, 2019</span></span>

<span data-ttu-id="f8252-121">버전 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="f8252-121">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="f8252-122">RemoveMSI=True 관련 레지스트리 설정을 정리하는 버그가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-122">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="f8252-123">예기치 않은 오류(E_UNEXPECTED)에 대한 추가 세부 정보를 제공하는 오류 코드를 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-123">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="f8252-124">2019년 4월 16일</span><span class="sxs-lookup"><span data-stu-id="f8252-124">April 16 2019</span></span>

<span data-ttu-id="f8252-125">버전 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="f8252-125">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="f8252-126">새로운 MigrateArch 특성을 사용하여 32비트 C2R을 64비트 C2R로 업그레이드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-126">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="f8252-127">웹 위치(http 및 https)에 저장된 구성 XML 파일에 액세스할 수 있도록/configure에 대한 논리가 업데이트되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-127">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="f8252-128">MatchInstalled는 제품 또는 언어를 추가할 때 ODT가 기존 버전과 일치할 수 있게 해주는 새로운 특성으로 추가되었습니다.</span><span class="sxs-lookup"><span data-stu-id="f8252-128">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="f8252-129">2019년 3월 13일</span><span class="sxs-lookup"><span data-stu-id="f8252-129">March 13, 2019</span></span>

<span data-ttu-id="f8252-130">버전 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="f8252-130">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="f8252-131">업그레이드 및 마이그레이션 시나리오 개선</span><span class="sxs-lookup"><span data-stu-id="f8252-131">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="f8252-132">2019년 1월 14일</span><span class="sxs-lookup"><span data-stu-id="f8252-132">January 14, 2019</span></span>

<span data-ttu-id="f8252-133">버전 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="f8252-133">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="f8252-134">배포 구성에 대한 로깅과 원격 분석 향상</span><span class="sxs-lookup"><span data-stu-id="f8252-134">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="f8252-135">관련 링크</span><span class="sxs-lookup"><span data-stu-id="f8252-135">Related links</span></span>

[<span data-ttu-id="f8252-136">ODT 다운로드 센터</span><span class="sxs-lookup"><span data-stu-id="f8252-136">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)