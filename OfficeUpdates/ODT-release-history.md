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
ms.openlocfilehash: fb59993362c4c186518f8472cb0330fa1b1e8d58
ms.sourcegitcommit: f042b25b15960fc4911a7e7d8500dcfd992ee95c
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/17/2020
ms.locfileid: "41230066"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 배포 도구에 대한 릴리스 기록

ODT(Office 배포 도구)는 Office 365 ProPlus와 같이 간편 실행 버전의 Office를 클라이언트 컴퓨터에 다운로드하여 배포하는 데 사용할 수 있는 명령줄 도구입니다. 


ODT를 사용하여 Office 설치를 더 강력하게 제어할 수 있습니다. 설치할 제품과 언어, 제품 업데이트 방법 및 사용자에게 설치 환경 표시 여부를 정의할 수 있습니다. ODT를 사용하는 방법에 대한 자세한 내용은 [Office 배포 도구 개요](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)를 참조하세요.

 **지원되는 운영 체제**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2 
 
 **설치 방법**: 다운로드한 다음 Office 배포 도구 실행 파일(setup.exe) 및 샘플 구성 파일(configuration.xml)이 포함된 자동 압축 풀기 실행 파일을 실행합니다. 

[Office 배포 도구 다운로드](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="january-16-2020"></a>2020년 1월 16일

버전 16.0.12325.20288
- 여러 언어를 설치하는 경우 Office 설치 UI가 잘못 된 언어로 표시될 수 있는 문제를 해결합니다.
- 특정 언어 교정 도구 패키지를 설치할 때 Office 설치가 예기치 않게 실패할 수 있는 문제를 해결합니다.
- [Bing에서 Microsoft 검색](https://go.microsoft.com/fwlink/p/?linkid=2109345)의 초기 배포를 선택적으로 제어하는 작업에 대한 지원을 추가합니다.


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