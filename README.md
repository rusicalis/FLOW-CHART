# COTEC 개발 FLOW

COTEC의 MES, ACPT, JIG 설계 프로그램, 도금 두께 시뮬레이터를 순서대로 완성·연동하기 위한 iPhone용 PWA 진행관리 앱입니다.

## 특징
- STEP 1~6 개발 FLOW
- 단계 클릭 시 세부 체크리스트
- 단계별 / 전체 진행률 자동 계산
- 이전 단계 완료 전 다음 단계 잠금
- 체크 상태 iPhone 브라우저 내부 저장(localStorage)
- GitHub Pages 배포 가능
- Safari 홈 화면 추가 지원
- 오프라인 캐시 지원

## GitHub Pages 배포
1. 새 GitHub 저장소를 만듭니다.
2. 이 폴더의 파일을 저장소 루트에 업로드합니다.
3. GitHub 저장소 `Settings > Pages`로 이동합니다.
4. `Deploy from a branch`를 선택하고 `main / (root)`를 지정합니다.
5. 생성된 Pages 주소를 iPhone Safari로 엽니다.
6. Safari 공유 버튼 > `홈 화면에 추가`를 선택합니다.

## 데이터 저장
체크 상태는 서버나 GitHub가 아니라 해당 iPhone의 Safari/PWA 저장소에만 저장됩니다. Safari 웹사이트 데이터를 삭제하면 체크 상태도 삭제될 수 있습니다.
