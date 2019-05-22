---
title: Office 참가자에 대한 릴리스 정보
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 5/17/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 초기 참가자 대상 그룹에게 주요 새 기능, 수정 사항 또는 알려진 문제의 최신 목록을 제공합니다.
ms.openlocfilehash: a747d7cf04b1429ea81f0740f571708a1ff539d9
ms.sourcegitcommit: 92ef2d0ee2d901d59288ffbbd0cf6d1da2d45bf7
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 05/17/2019
ms.locfileid: "34161567"
---
# <a name="release-notes-for-office-insiders"></a>Office 참가자에 대한 릴리스 정보

이 문서에는 Windows 데스크톱용 Word, Excel, PowerPoint, Outlook, Access 및 Project 의 참가자 빌드에 대한 릴리스 정보가 포함되어 있습니다. 매주 Microsoft는 흥미로운 새 기능, 중요한 수정 사항, 알리고자 하는 중요한 문제를 강조합니다. Microsoft는 일정 기간 동안 자주 참가자들에게 기능을 배포하며 때로는 수정 사항도 배포합니다. 이로서 더욱 광범위한 사용자들에게 기능을 릴리스하기 전에 원활하게 작동하는지 확인할 수 있습니다. 따라서 아래에 설명된 기능이 보이지 않더라도 곧 제공되게 되므로 걱정할 필요가 없습니다.  

> [!NOTE]
> - 릴리스 정보는 매주 게시되며 여러 빌드의 컴파일일 수 있습니다.
> - 릴리스 정보 게시 날짜는 실제 빌드 릴리스 날짜와 일치하지 않을 수 있습니다.

## <a name="may-17-2019"></a>2019년 5월 17일
버전 1906(빌드 11708.20006)

## <a name="whats-new"></a>새로운 기능:

### <a name="outlook"></a>Outlook

#### <a name="user-experience-updates"></a>사용자 환경 업데이트

출시 예정이었던 업데이트가 이제 시행되었으며, 이는 간소화된 리본과 폴더 창, 메시지 목록 및 읽기 창의 시각적 새로 고침 기능을 특징으로 합니다.

##### <a name="getting-started"></a>시작:

이러한 변경 사항은 새로운 기본 UI의 일부가됩니다. 12월 중순 이래로 출시 예정 스위치 뒤에 숨겨진 상태였지만 100% prod가 되었습니다.

#### <a name="customizable-simplified-ribbon"></a>사용자 지정이 가능한 간소화된 리본

클래식 및 요약 보기 간의 간편한 전환 및 명령 고정/고정 해제가 쉽도록 사용자 지정 가능

##### <a name="getting-started"></a>시작:

사용자는 출시 예정(초기 설정)을 켜고 리본의 갈매기 모양을 클릭해 클래식 멀티 라인 리본과 새로운 단순 싱글 라인 리본 사이를 전환하여 간소화된 리본을 사용할 수 있습니다.

##### <a name="scenarios-to-try"></a>시도해 볼 시나리오:

클래식 리본에서 간단한 리본으로 전환

#### <a name="pick-your-favorite-action"></a>즐겨찾기 선택 작업

플래그를 사용하지 않고 삭제? [보관] 또는 [읽은 상태로 표시]는 어떤가요? 가장 많이 사용하는 명령으로 빠른 작업 메뉴를 사용자 지정합니다.

##### <a name="getting-started"></a>시작:

빠른 작업을 선택하려면 메시지 목록의 이메일을 마우스 오른쪽 버튼으로 클릭하여 상황에 맞는 메뉴를 불러 오십시오. 그런 다음 "빠른 작업 설정..."을 클릭합니다.

##### <a name="scenarios-to-try"></a>시도해 볼 시나리오:

기본값을 플래그에서 변경하고 보관으로 삭제, 이동, 읽은 상태로 표시하거나 메시지 목록을 더 깔끔하게 하기 위해 모두 없앱니다.

#### <a name="relaxed-or-tighter-layout-you-choose"></a>넓은 레이아웃 아니면 더 좁은 레이아웃? 선택

더 좁은 간격을 사용하면 항목 간에 더 넓은 공백을 할지 또는 더 좁은 레이아웃을 사용하여 더 많은 항목을 표시할지를 결정할 수 있습니다.

##### <a name="getting-started"></a>시작:

보기 탭, 촘촘한 간격 사용 확인란 - 기본 리본의 메시지 그룹, 단순 리본의 현재보기 설정

##### <a name="scenarios-to-try"></a>시도해 볼 시나리오:

Outlook을 사용하여 설정을 사용하거나 사용하지 않고 전자 메일을 분류하고 작성합니다. 간격을 좁게 사용하면 페이지당 메시지가 더 많이 표시되고 작성 양식의 컨트롤이 보다 간소화됩니다.

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a>Onedrive 동기화 클라이언트를 사용할 때 MRU 항목 중복 제거

mru 항목을 제거하고 동기화된 데이터에 대한 복사 동작으로 보다 신속하게 연결할 수 있도록 하여 클라우드 첨부가 포함된 onedrive 동기화 클라이언트와보다 잘 통합됩니다.

##### <a name="getting-started"></a>시작:

OneDrive 동기화 클라이언트를 사용하면 첨부 파일 MRU에서 중복 된 파일이 더 이상 표시되지 않습니다.

##### <a name="scenarios-to-try"></a>시도해 볼 시나리오:

OneDrive 동기화 클라이언트 사용 및 Outlook 데스크톱의 파일 첨부 메뉴 사용

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a>여러 폴더가 있는 사서함에 대한 공유 폴더 동기화 기능 향상

수년 동안 Outlook은 공유 사서함을 동기화할 때 폴더 수를 최대 500개로 제한해 왔습니다. 이 변경을 통해 Outlook은 이 500개 폴더 제한이 더 이상 적용되지 않도록 동기화 방식을 개선했습니다.

##### <a name="getting-started"></a>시작:

사서함에 1000 폴더를 만들고, 다른 사용자에 게 사서함에 대 한 액세스 권한을 부여 하 고, "다른 사용자"를 위한 Outlook 프로필을 만들고, 동기화가 작동 하는지 확인 합니다.

### <a name="word"></a>Word

#### <a name="erase-just-a-little-bit"></a>조금만 지우기

##### <a name="getting-started"></a>시작:

그리기 탭으로 이동하십시오. 지우개 드롭 다운을 선택하십시오. 작은 지우개 또는 중간 지우개를 선택합니다.

##### <a name="scenarios-to-try"></a>시도해 볼 시나리오:

그리기 탭으로 이동하 고 펜을 선택합니다. 잉크 스트로크를 그립니다. 지우개 드롭다운을 선택합니다. 작은 지우개 또는 중간 지우개를 선택합니다. 잉크 스트로크를 조금만 지웁니다.

## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="all"></a>모두 
- 일부 사용자가 PDF를 저장하지 못하는 문제를 해결했습니다.
- 사용자가 32 비트 시스템에서 대용량 파일을 저장하는 데 영향을 줄 수 있는 문제가 수정되었습니다.

### <a name="word"></a>Word 
- 받아쓰기 기능의 응답성을 크게 향상 시켰습니다

### <a name="excel"></a>Excel
- 터치 스크린 장치에서 두 번 클릭 이벤트가 실패 할 수 있는 문제가 수정되었습니다
- 일부 사용자가 VBA 매크로를 편집하지 못할 수 있는 문제가 수정되었습니다.
- 슬라이스를 사용할 때 성능에 영향을 줄 수 있는 문제가 수정되었습니다.

### <a name="powerpoint"></a>PowerPoint
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="outlook"></a>Outlook
- 선택한 항목에서 잘못된 서식 파일을 표시할 수 있는 문제가 수정되었습니다

### <a name="access"></a>액세스
- 확대/축소 빌더를 사용하여 긴 서식 있는 텍스트를 표시하면 읽기가 어려워지는 문제를 해결했습니다

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항입니다.

</BR></BR>

## <a name="may-10-2019"></a>2019년 5월 10일
버전 1906(빌드 11702.20000)

## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="all"></a>모두
- 다른 이름으로 저장 대화 상자에서 잘못된 경로를 표시할 수 있는 문제를 수정했습니다.

### <a name="word"></a>Word 
- 텍스트를 입력하세요의 일부 선택 항목이 삽입되지 않는 문제를 수정했습니다.

### <a name="excel"></a>Excel
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="powerpoint"></a>PowerPoint
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="outlook"></a>Outlook
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="access"></a>Access
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="project"></a>Project
- 작업 ID에서 강조 표시가 필요할 수 있는 문제를 해결했습니다.

</BR></BR>

## <a name="may-3-2019"></a>2019년 5월 3일
버전 1906(빌드 11629.20008)

## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="all"></a>모두
- 일부 사용자를 대상으로 비즈니스용 OneDrive 동기화 중에 발생하는 문제를 해결했습니다.

### <a name="word"></a>Word 
- 특정한 경우 Word를 시작하는 데 오랜 시간이 걸리는 문제를 수정했습니다.

### <a name="excel"></a>Excel
- 최신 버전 Excel로 업그레이드한 후 통합 문서에서 가끔 외부 링크가 제거되는 문제를 해결했습니다.
- 일부 사용자를 대상으로 새 통합 문서에서 셀을 선택할 때 발생할 수 있는 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint
- 드로잉을 텍스트로 변환할 때 글꼴 크기가 일정하지 않은 문제를 해결했습니다.

### <a name="outlook"></a>Outlook
- .VCF 파일에서 연락처를 저장하면 빈 필드가 생길 수 있는 문제를 해결했습니다.
- 전송되었음에도 불구하고 메시지가 보낼 편지함 폴더에 쌓일 수 있는 문제를 해결했습니다.
- DRM 메시지를 볼 때 Outlook이 충돌할 수 있는 문제를 해결했습니다.

### <a name="access"></a>Access
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="project"></a>Project
- 편집기가 중국어에서 영어로 전환되는 문제를 해결했습니다.
- 게시되지 않은 작업이 게시된 마스터 프로젝트 사본에 표시될 수 있는 문제를 해결했습니다.

</BR></BR>

## <a name="april-26-2019"></a>2019년 4월 26일
버전 1905(빌드 11617.20002)

## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="word"></a>Word 
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="excel"></a>Excel
- 해 찾기 매크로가 실행에 실패하는 문제를 수정했습니다.
- Excel 파일를 SharePoint로 가져오지 못하게 하는 문제를 수정했습니다.

### <a name="powerpoint"></a>PowerPoint
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="outlook"></a>Outlook
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="access"></a>Access
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항

</BR></BR>

## <a name="april-19-2019"></a>2019년 4월 19일
버전 1905 (빌드 11609.20002)

## <a name="whats-new"></a>새로운 기능:

### <a name="excel"></a>Excel

#### <a name="improved-filled-maps-experience-using-data-types"></a>데이터 형식을 사용하여 등치 지역도 개선

이 기능은 Excel의 지리 데이터 형식을 사용하여 등치 지역도 차트를 그리는 사용자에게 유용한 개선 사항입니다. 기능과 최종 사용자가 매핑하고자 하는 지역의 정확성의 통합성을 향상하는 이점을 최종 사용자에게 제공합니다. 추가적인 이점은 도시 폴리곤을 매핑할 수 있다는 점입니다.

##### <a name="getting-started"></a>시작:

- 이 기능은 Excel의 기존 기능을 개선한 것입니다. 개선 사항을 사용하려면 위치를 서식이 있는 엔티티로 변환하고 등치 지역도를 사용해 그립니다. 

##### <a name="scenarios-to-try"></a>시도해 볼 시나리오:

- 사용자는 국가, 시/도, 시/군/구 및 우편 번호를 매핑할 수 있습니다. 


## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="all-applications"></a>모든 응용 프로그램
- 응용 프로그램을 시작할 때마다 첫 번째 실행 대화 상자가 표시되는 문제를 해결했습니다.
- "다른 이름으로 저장" 대화 상자에서 SharePoint 링크가 누락되는 문제를 해결했습니다.
- 사용자에게 "지금 복구" 대화 상자가 올바르게 표시되지 않는 문제를 해결했습니다.

### <a name="word"></a>Word 
- 일부 사용자가 글꼴을 요청할 때 메모리 또는 디스크 공간 부족에 대한 오류가 표시되는 문제를 해결했습니다.
- 메모 창에서 전환할 때 창 포커스를 잃는 문제를 해결했습니다.

### <a name="excel"></a>Excel
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="powerpoint"></a>PowerPoint
- 브랜드 셰이프 크기를 조정할 수 없는 문제를 해결했습니다.
- 제한된 보기 모드에서 파일을 열 때 PowerPoint에서 충돌이 발생할 수 있는 문제를 해결했습니다.

### <a name="outlook"></a>Outlook
- 일부 사용자가 중국어 단어를 선택하지 못하는 문제를 해결했습니다.
- 만료 날짜가 올바르게 계산되지 않은 문제를 해결했습니다.

### <a name="access"></a>Access
- 일부 사용자가 매크로 작성기를 사용하지 못하는 문제를 해결했습니다.
- 보고서를 인쇄할 때 첫 페이지만 인쇄하는 문제를 해결했습니다.
- 하이퍼 링크를 마우스로 가리킬 때 응용 프로그램이 중단되는 문제를 해결했습니다.
- 관계 보기를 사용하는 경우 일부 항목이 화면에 표시되지 않는 문제를 해결했습니다.

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항입니다.

</BR></BR>

## <a name="april-12-2019"></a>2019년 4월 12일
버전 1905 (빌드 11601.20042)

## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="all-applications"></a>모든 응용 프로그램
 - 일부 사용자가 클라우드 위치에 파일을 저장하지 못하는 문제를 해결했습니다.
 - 잘못된 창이 리본에서 열릴 수 있는 문제를 해결했습니다.

### <a name="word"></a>Word 
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="excel"></a>Excel
- 통합 문서에 연결된 데이터 유형이 없을 때 연결된 데이터 유형에 대한 오류 메시지가 표시되는 문제를 해결했습니다.
- 로컬에서 또는 온라인에서 볼 때 Word 문서 내 URL 링크가 변경될 수 있는 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint
- 애니메이션 탭에서 변경 사항을 취소한 후 응용 프로그램이 중단될 수 있는 문제를 해결했습니다.

### <a name="outlook"></a>Outlook
- 일부 사용자가 공용 폴더에서 연락처에 대한 메모 필드를 수정할 수 없는 문제를 해결했습니다.
- 만료 날짜와 삭제 날짜 간에 충돌이 발생할 수 있는 문제를 해결했습니다.

### <a name="access"></a>Access
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항입니다.

</BR></BR>

## <a name="april-5-2019"></a>2019년 4월 5일
버전 1904(빌드 11527.20014)

## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="all-applications"></a>모든 응용 프로그램
- 상황에 맞는 메뉴에서 Excel에 대해 잘못된 앱 아이콘이 나타나는 문제를 해결했습니다.
- 업데이트를 설치한 후 파일 메뉴 단추가 사라지는 문제를 해결했습니다.
- 사용자 라이선스를 변경할 수 있는 문제를 해결했습니다.

### <a name="word"></a>Word 
- 특정 줌 레벨에서 텍스트가 올바르게 렌더링되지 않은 문제를 해결했습니다.

### <a name="excel"></a>Excel
- 편집한 후 통합 문서 저장 메시지가 표시되지 않는 문제를 해결했습니다.
- 사용자가 통합 문서를 공유한 경우 BeforeSave 이벤트가 트리거되지 않는 문제를 해결했습니다.
- 열 크기를 6픽셀 미만으로 조정하면 잘못된 오류 메시지가 나타나는 문제를 해결했습니다.
- Excel에서 Application.Visible 플래그를 무시하는 문제를 해결했습니다.
- 비활성 상태의 고정된 창에 추적 화살표가 남아 있는 문제를 해결했습니다.
- 통합 문서를 열 때 날짜 및 통화에 대한 셀 서식이 변경되는 문제를 해결했습니다.
- 도구 설명이 예기치 않게 이동되는 문제를 해결했습니다.
- 파워 쿼리 편집기의 지역화 문제를 해결했습니다.
- 통합 문서를 전자 메일을 통해 첨부 파일로 보낼 때 통합 문서가 제거되는 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint
- 도형 복사에 예상보다 시간이 오래 걸리는 문제를 해결했습니다.

### <a name="outlook"></a>Outlook
- 그리기 도구를 사용하는 동안 Outlook이 충돌하는 문제를 해결했습니다.
- html 전자 메일을 작성할 때 지역화 문제를 해결했습니다.
- 사용자가 아래쪽 창을 선택하기 힘든 문제를 해결했습니다.

### <a name="access"></a>Access
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항입니다.

</BR></BR>

## <a name="march-22-2019"></a>2019년 3월 22일
버전 1904(빌드 11514.20004)

## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="word"></a>Word 
- UI에 지속적으로 “변경 내용을 확인하는 중”이 표시되는 문제를 해결했습니다.

### <a name="excel"></a>Excel
- 워크시트 이동 후 응용 프로그램이 중단되는 문제를 해결했습니다.
- PDF로 저장한 후 응용 프로그램이 중단되는 문제를 해결했습니다.
- 저장 대화 상자에서 일부 한국어 문자를 허용하지 않는 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="outlook"></a>Outlook
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="access"></a>Access
- Access에서 Access로 추가 바로 가기가 만들어졌다는 오류 메시지가 표시되는 문제를 해결했습니다.
- 연결된 SharePoint의 데이터가 올바르게 표시되지 않는 문제를 해결했습니다.

### <a name="project"></a>Project
- 언어 설정이 중국어에서 영어로 변경되는 문제를 해결했습니다.
- SharePoint와 동기화할 때 응용 프로그램이 중단되는 문제를 해결했습니다.

</BR></BR>

## <a name="march-15-2019"></a>2019년 3월 15일
버전 1904(빌드 11504.20000)

## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="word"></a>Word 
- PDF로 저장된 문서의 이미지에 잘못된 DPI가 있는 문제를 해결했습니다.

### <a name="excel"></a>Excel
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="powerpoint"></a>PowerPoint
- 메모 창이 적절하게 열리거나 닫히지 않는 문제를 해결했습니다.
- 비디오를 삭제할 때 응용 프로그램이 중단되는 문제를 해결했습니다.
- 경우에 따라 응용 프로그램을 시작할 수 없는 문제를 해결했습니다.

### <a name="outlook"></a>Outlook
- 일본어로 표시할 때 읽음 확인이 올바르지 않은 문제를 해결했습니다.

### <a name="access"></a>Access
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항입니다.

</BR></BR>

## <a name="march-8-2019"></a>2019년 3월 8일 
버전 1903(빌드 11425.20036)

## <a name="whats-new"></a>새로운 기능:

### <a name="word"></a>Word

### <a name="find-what-youre-looking-for-with-microsoft-search"></a>Microsoft Search를 통해 원하는 것을 찾으십시오.

Microsoft Search를 사용하면 모든 파일, 작업, 사람을 찾고 작업을 수행하는 데 필요한 도움을 받을 수 있습니다.

#### <a name="getting-started"></a>시작:

- 이 기능은 머리글의 UI 위에 눈에 띄도록 표시됩니다.

#### <a name="scenarios-to-try"></a>시도해 볼 시나리오:

- 대학이나 최근 문서를 검색하거나 가장 자주 사용하는 리본 명령을 검색해 보세요.
- 화제나 주제를 검색하여 더 많은 정보를 얻으세요.


## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="word"></a>Word 
- Options에서 ‘ESC’를 누를 때 발생하는 충돌 문제를 해결했습니다.
- 메모에 회신할 때 발생하는 충돌 문제를 해결했습니다.
- Word에서 PowerPoint Online으로 복사 및 붙여넣기를 할 때 발생하는 문제를 해결했습니다.

### <a name="excel"></a>Excel
- 보호되고 편집 가능한 문서를 열었을 때 Excel에서 셀을 복사하는 경우 높은 CPU 사용량을 발생시키는 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="outlook"></a>Outlook
- Outlook Search가 선택한 연대순 정렬을 반영하지 않는 문제를 해결했습니다.
- "이 작업 열기" 워크플로우 리본 버튼이 특정 이메일에 응답하지 않는 문제를 해결했습니다.
- 사용자가 회의실 찾기를 통해 사용 가능한 회의실을 선택한 후 Outlook이 사내 회의실을 지우지 않는 문제를 해결했습니다.

### <a name="access"></a>Access
- 어두운 테마에서 흰색 배경에 흰색 텍스트가 있던 저장된 가져오기/내보내기 대화 상자의 문제를 해결했습니다.
- 테이블 디자인에서 사용자가 표시 컨트롤 속성의 Yes/No 필드를 Textbox로 설정하지 못했던 문제를 해결했습니다.

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항입니다.


## <a name="march-1-2019"></a>2019년 3월 1일 
버전 1903(빌드 11414.20014)


## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="word"></a>Word 
- Options에서 ‘ESC’를 누를 때 발생하는 충돌 문제를 해결했습니다.
- Word에서 PowerPoint Online으로 복사 및 붙여넣기를 할 때 발생하는 문제를 해결했습니다.

### <a name="excel"></a>Excel
- 보호되고 편집 가능한 문서를 열었을 때 Excel에서 셀을 복사하는 경우 높은 CPU 사용량을 발생시키는 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint
- PowerPoint에서 @Mentions를 사용 시의 슬라이드 이미지 크기 관련 문제를 해결했습니다.

### <a name="outlook"></a>Outlook
- Outlook Search가 선택한 연대순 정렬을 반영하지 않는 문제를 해결했습니다.
- "이 작업 열기" 워크플로우 리본 버튼이 특정 이메일에 응답하지 않는 문제를 해결했습니다.
- 사용자가 회의실 찾기를 통해 사용 가능한 회의실을 선택한 후 Outlook이 사내 회의실을 지우지 않는 문제를 해결했습니다.

### <a name="access"></a>Access
- 데이터 전송 발신기와 테이블의 재연결을 확인 시 표시되는 프롬프트 텍스트를 업데이트했습니다.
- 어두운 테마에서 흰색 배경에 흰색 텍스트가 있던 저장된 가져오기/내보내기 대화 상자의 문제를 해결했습니다.
- 테이블 디자인에서 사용자가 표시 컨트롤 속성의 Yes/No 필드를 Textbox로 설정하지 못했던 문제를 해결했습니다.

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항입니다.

</BR></BR>



## <a name="february-15-2019"></a>2019년 2월 15일 
버전 1903(빌드 11310.20016)

## <a name="whats-new"></a>새로운 기능:

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>모핑 전환 개선 사항 - 이름으로 모핑

모핑하려는 도형 지정

#### <a name="getting-started"></a>시작:

- 두 개체를 같은 개체로 처리하도록 모핑을 사용하기 위해 사용자는 선택 창을 사용하여 도형 이름을 바꿀 수 있습니다.
- 이름은 "!!"로 시작해야 합니다. 모핑에서 이름을 사용하여 기본 일치 동작을 무시하도록 하려면, 예를 들어 “!!이름”
- 사용자는 계속 “!!”로 시작하지 않는 셰이프 이름을 바꿀 수 있습니다. 모핑 작동 방식의 변경에 대해 우려할 필요가 없습니다.

#### <a name="scenarios-to-try"></a>시도해 볼 시나리오:

- 슬라이드에 도형을 삽입합니다. 직사각형을 가정해 보겠습니다.
- 새 슬라이드를 만듭니다 

- 두 번째 슬라이드에 다른 도형을 삽입합니다. 삼각형을 가정해 보겠습니다
- SelectionPane을 열고, 슬라이드 1에서 직사각형을 "!!도형"으로 이름을 바꾸고, 슬라이드 2에서 삼각형을 “!!도형”으로 이름을 바꿉니다
- 두 번째 슬라이드에 모핑 적용

</BR>

### <a name="morph-transition-enhancements---smartart"></a>모핑 전환 개선 사항 - SmartArt

더 원활한 전환으로 SmartArt 모핑

#### <a name="getting-started"></a>시작:

SmartArt를 사용하는 것과 같은 방법으로 모핑 사용

#### <a name="scenarios-to-try"></a>시도해 볼 시나리오:

- 슬라이드에 SmartArt 삽입
- 슬라이드를 복제합니다
- 복제된 슬라이드에서 SmartArt를 크기 조정/변경/이동합니다
- 복제된 슬라이드에서 모핑 적용

</BR>

### <a name="morph-transition-enhancements---tables"></a>모핑 전환 개선 사항 - 표

더 원활한 전환으로 표 모핑

#### <a name="getting-started"></a>시작:
표를 사용하는 것과 같은 방법으로 모핑 사용

#### <a name="scenarios-to-try"></a>시도해 볼 시나리오:

- 슬라이드에서 표 추가
- 슬라이드를 복제합니다
- 복제된 슬라이드에서 Table을 크기 조정/변경/이동합니다
- 복제된 슬라이드에서 모핑 적용

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word, Excel, PowerPoint, OneNote, Access, Project, Publisher 및 Visio

### <a name="seamlessly-switch-between-accounts"></a>원활한 계정 전환

새 계정 관리자를 통해 사용자의 모든 회사 및 개인 계정을 한곳에서 볼 수 있으며, 사용자가 직접 여러 계정 간에 전환할 수 있습니다. 업데이트된 환경에서는 사용자의 로그인 방법이 명확해지며, 이제 먼저 로그아웃하거나 복잡한 대화 상자를 거치지 않고 회사 및 개인 계정 사이를 전환할 수 있습니다.


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>시도해 볼 시나리오:
- 계정 간 전환
- 새 계정 추가 [참고: 먼저 파일 | 계정 | 연결된 서비스에 가서 회사 계정에 연결된 개인 서비스를 제거 또는 그 반대로 하고자 할 수 있습니다]
- 계정에서 로그아웃
</BR>

## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="word"></a>Word 
- 표 및 이미지에 대한 상황에 맞는 미리 보기 관련 문제를 해결했습니다.

### <a name="excel"></a>Excel
- 자동 필터 검색 필드의 텍스트는 검은색 테마에서 흰색인 문제를 해결했습니다.
- 새 Office 추가 기능에 있는 동의 UI 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint
- 노트북 또는 태블릿에 슬라이드 쇼를 표시할 때 자동으로 확장하는 디스플레이 문제를 해결했습니다.

### <a name="outlook"></a>Outlook
- OneNote로 보내기 버튼 디스플레이 문제를 해결했습니다.

### <a name="access"></a>Access
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항입니다.


</BR></BR>
## <a name="february-11-2019"></a>2019년 2월 11일
버전 1903(빌드 11330.20014)


## <a name="notable-fixes"></a>중요 수정 사항:

### <a name="word"></a>Word 
- 일부 사용자 지정된 스타일을 Word Online에 적용할 수 없는 문제를 해결했습니다.
- Word에서 서식 있는 개체의 컨텍스트 미리 보기 문제를 해결했습니다.
- Word에서 목록을 붙여넣으면 작동이 중단되는 문제를 해결했습니다.

### <a name="excel"></a>Excel
- 통화 기호가 없을 때 숫자 서식 뒤에 추가된 공백이 더 이상 표시되지 않는 문제를 해결했습니다.
- 주식 자동 검색 관련 문제를 해결했습니다.

### <a name="powerpoint"></a>PowerPoint
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="outlook"></a>Outlook
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="access"></a>Access
- 다양한 성능 및 안정성 수정 사항입니다.

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항입니다.

</BR></BR>


## <a name="february-1-2019"></a>2019년 2월 1일 
버전 1902(빌드 11326.20000)


## <a name="notable-fixes"></a>중요 수정 사항

### <a name="word"></a>Word 
- 임베디드 Excel 테이블에서 셀 크기를 조정하는 문제가 수정되었습니다.
- 그리기 캔버스에서 도형 복사 / 붙여 넣기 문제가 수정되었습니다.

### <a name="excel"></a>Excel
- Excel 웹 응용 프로그램에서 파일을 열 때 발생하는 문제가 수정되었습니다.
- 파일 이름 크기로 인해 .XLSX가 실패하여 CSV 파일을 저장하는 문제가 수정되었습니다.
- 컨텍스트 메뉴를 수정하여 컨텍스트 메뉴 옵션을 표시했습니다.

### <a name="powerpoint"></a>PowerPoint
- 사용자가 키보드 단축키 ctrl + alt + 7 / ctrl + alt + 8을 사용하여 대괄호를 입력할 수 없는 부분을 수정했습니다.
- PPT에 로컬 비디오를 삽입하면 'C'드라이브의 디스크 공간이 줄어드는 문제가 수정되었습니다.
- 일부 사용자에게 표시되지 않는 Microsoft Stream에 게시 버튼이 수정되었습니다.

### <a name="outlook"></a>Outlook
- 일정의 작업 보기에 작업 제목이 올바르게 표시되지 않는 문제를 해결했습니다.

### <a name="access"></a>Access
- 차트 관련 배율 문제를 해결했습니다.

### <a name="project"></a>Project
- 다양한 성능 및 안정성 수정 사항입니다.
