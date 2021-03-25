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
ms.openlocfilehash: 046054dfb781c3cd19ca6505e5ae5f2f362f6a86
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169966"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 배포 도구에 대한 릴리스 기록

ODT(Office 배포 도구)는 Microsoft 365 앱과 같이 간편 실행 버전의 Office를 클라이언트 컴퓨터에 다운로드하여 배포하는 데 사용할 수 있는 명령줄 도구입니다. 


ODT를 사용하여 Office 설치를 더 강력하게 제어할 수 있습니다. 설치할 제품과 언어, 제품 업데이트 방법 및 사용자에게 설치 환경 표시 여부를 정의할 수 있습니다. ODT를 사용하는 방법에 대한 자세한 내용은 [Office 배포 도구 개요](/deployoffice/overview-of-the-office-2016-deployment-tool)를 참조하세요.

 **지원되는 운영체제**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016 
 
 **설치 방법**: 다운로드한 다음 Office 배포 도구 실행 파일(setup.exe) 및 샘플 구성 파일(configuration.xml)이 포함된 자동 압축 풀기 실행 파일을 실행합니다. 

[Office 배포 도구 다운로드](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="march-23-2021"></a>2021년 3월 23일
버전 16.0.13801.20360(setup.exe 버전 16.0.13801.20340)
- 예정된 Office 제품 릴리스 지원 변경 사항
- ARM 플랫폼에 대한 안정성 해결


## <a name="february-25-2021"></a>2021년 2월 25일
버전 16.0.13628.20476(setup.exe 버전 16.0.13628.20462)
- 수십 개의 언어를 지정하는 configuration.xml 파일이 유효성을 검사하지 못하는 문제를 해결했습니다.
- 마이그레이션 시나리오에서 FORCEAPPSHUTDOWN 속성이 존중되지 않는 문제를 해결했습니다.
- configuration.xml에서 2개 이상의 PIDKEY 특성을 지정하여 PIDKeys를 설치하지 못하는 문제를 해결했습니다.



## <a name="february-9-2021"></a>2021년 2월 9일
버전 16.0.13628.20274(setup.exe 버전 16.0.13628.20246)
- Windows 8.0에서 지원되지 않는 설치 작업에 대해 경고하고 이를 방지하는 유효성 검사가 추가되었습니다.
- ARM64 장치에 대한 안정성 해결 방법


## <a name="january-12-2021"></a>2021년 1월 12일
버전 16.0.13530.20376 (setup.exe 버전 16.0.13530.20334)
- 손상된 제품 등록 또는 비표준 제품 등록으로 인해 RemoveMSI 작업이 실패할 수 있는 문제 해결

## <a name="december-21-2020"></a>2020년 12월 21일
버전 16.0.13426.20370(setup.exe 버전 16.0.13426.20352)
- PerpetualVL2019 채널에서 ProofingTools의 로컬 소스 설치가 실패하는 문제를 해결했습니다.
- 기존 설치에 전체 Office 언어가 아닌 추가 제품을 추가할 때 간편 실행 클라이언트가 자체 업데이트를 시도하는 문제를 해결했습니다.


## <a name="december-8-2020"></a>2020년 12월 8일
버전 16.0.13426.20308 (setup.exe 버전 16.0.13426.20308)
- 디바이스에 Office 제품이 비영구 2019 채널에서 설치된 경우 다운로드 모드가 영구 2019 채널 다운로드를 차단하는 문제를 해결했습니다.
- 구성 XML에 명시적 버전을 지정한 다운로드 모드를 통해 생성된 로컬 소스에 대해 아키텍처 마이그레이션이 실패하는 문제를 해결했습니다.


## <a name="november-23-2020"></a>2020년 11월 23일
버전 16.0.13328.20420(setup.exe 버전 16.0.13328.20420)
- 언어 교정 도구가/다운로드 모드로 다운로드되지 않는 문제 해결
- 관리자 권한 없는 사용자에게 실행 될 경우 다운로드 모드가 실패 하는 문제 해결
- 구성 XML에서 버전 속성을 지정하면 /download 모드에서 불완전한 다운로드가 발생하는 문제 해결
- 추출 시 Office 배포 도구 이름이 "setup.exe"로 지정되지 않은 문제 해결
- 구성 XML에서 채널 특성이 제공되는 경우 설치 원본 우선 순위 지정에 대한 문제 해결

## <a name="november-10-2020"></a>2020년 11월 10일
버전 16.0.13328.20356 (setupODT.exe 버전 16.0.13328.20336)
- 안정성 및 복원 기능 개선
- 혼동을 방지하고 보다 쉽게 설치 오류를 진단하기 위해 이제 ODT는 기본적으로 setupODT.exe로 명명됩니다. 

## <a name="october-29-2020"></a>2020년 10월 29일
버전 16.0.13328.20292 (setup.exe 버전 16.0.13328.20290)
- RemoveMSI를 사용하는 경우 특정 Office 2007 제품이 예기치 않게 설치를 차단하는 문제 해결

## <a name="october-14-2020"></a>2020년 10월 14일
버전 16.0.13231.20368 (setup.exe 버전 16.0.13231.20350)
- 지정된 채널이 없는 경우 모든 제품은 이제 기본적으로 월간 채널 사용
- 다른 DLL을 포함하는 디렉터리에서 ODT를 실행하는 경우 보안을 향상
- 안정성 및 복원 기능 개선

## <a name="june-9-2020"></a>2020년 6월 9일

버전 16.0.12827.20268(setup.exe 버전 16.0.12827.20258)
- 채널을 지정하지 않은 경우 현재 채널이 기본 채널이 되었습니다.
- 월 단위 기업 채널에 대한 지원 추가됨
- 새 채널 이름에 대한 지원 추가됨
- 일부 언어 리소스를 사용할 수 없는 경우에도 계속 설치할 수 있는 추가 복원 기능
- MSIRemove 2007 제품 제거를 위해 확장된 제거 기능
- MSIRemove 데이터베이스 엔진을 제거하기 위해 확장된 제거 기능 

## <a name="april-15-2020"></a>2020년 4월 15일

버전 16.0.12624.20320 (setup.exe 버전 16.0.12624.20290)
- Windows 7 관련 종료 Office 버전에 대한 지원을 추가합니다.
- 사용자 지정 설정이 예상대로 적용되지 않을 수 있는 문제를 해결합니다.
- 불필요한 .cat 파일이 예기치 않게 다운로드될 수 있는 문제를 해결합니다.

## <a name="january-16-2020"></a>2020년 1월 16일

버전 16.0.12325.20288
- 여러 언어를 설치하는 경우 Office 설치 UI가 잘못 된 언어로 표시될 수 있는 문제를 해결합니다.
- 특정 언어 교정 도구 패키지를 설치할 때 Office 설치가 예기치 않게 실패할 수 있는 문제를 해결합니다.
- [Bing에서 Microsoft 검색](/deployoffice/microsoft-search-bing)의 초기 배포를 선택적으로 제어하는 작업에 대한 지원을 추가합니다.


## <a name="october-31-2019"></a>2019년 10월 31일

버전 16.0.12130.20272
- 비즈니스용 Skype Basic 2019가 2019 영구 엔터프라이즈 볼륨 라이선스 제품과 함께 설치되는 문제 해결
- 프록시를 사용할 경우에 특정 조건에서 예기치 않게 ODT 다운로드 모드가 실패하는 문제 해결
- ODT 다운로드 모드에서 포트 80 이외의 다른 포트를 사용하여 HTTP를 통한 다운로드를 할 수 있도록 하는 새로운 기능


## <a name="july-10-2019"></a>2019년 7월 10일

버전 16.0.11901.20022
- Office 2019: Access Runtime, 비즈니스용 Skype Basic과 함께 설치할 때 추가 제품에 대한 지원이 추가되었습니다.
- MSI에서 업그레이드할 때 독립 실행형 제품의 조건부 설치 지원이 추가되었습니다.

## <a name="april-23-2019"></a>2019년 4월 23일

버전 16.0.11617.33601
- RemoveMSI=True 관련 레지스트리 설정을 정리하는 버그가 수정되었습니다.
- 예기치 않은 오류(E_UNEXPECTED)에 대한 추가 세부 정보를 제공하는 오류 코드를 업데이트했습니다.

## <a name="april-16-2019"></a>2019년 4월 16일

버전 16.0.11615.33602
- 새로운 MigrateArch 특성을 사용하여 32비트 C2R을 64비트 C2R로 업그레이드할 수 있습니다.
- 웹 위치(http 및 https)에 저장된 구성 XML 파일에 액세스할 수 있도록/configure에 대한 논리가 업데이트되었습니다.
- MatchInstalled는 제품 또는 언어를 추가할 때 ODT가 기존 버전과 일치할 수 있게 해주는 새로운 특성으로 추가되었습니다.

## <a name="march-13-2019"></a>2019년 3월 13일

버전 16.0.11509.33604
- 업그레이드 및 마이그레이션 시나리오 개선

## <a name="january-14-2019"></a>2019년 1월 14일

버전 16.0.11306.33602
- 배포 구성에 대한 로깅과 원격 분석 향상


## <a name="related-links"></a>관련 링크

[ODT 다운로드 센터](https://www.microsoft.com/en-us/download/details.aspx?id=49117)