# YouTube for Android TV v1.0.6 (공식 릴리즈)

안드로이드 TV 및 스마트 TV를 위한 고성능 무광고 무중단 스트리밍 클라이언트 v1.0.6 최신 정식 버전입니다.

---

### 🚀 주요 업데이트 및 개선 내역 (v1.0.6)

1. **YouTube Shopping 제휴 타임리 액션 QR코드 광고 영구 차단**
   - 영상 시청 도중 특정 시점(예: 2분 42초 등)에 화면 좌측 하단에 불필요하게 팝업되던 제휴 상품 QR코드(`ytlr-shopping-timely-action-renderer`, `ytlr-qr-code-renderer`) 및 닫기 버튼 원천 차단
   - 마스터 CSS 0ms 은폐, 50ms 런타임 DOM 킬스위치, JSON 페이로드 사전 필터링의 3중 방어막을 구축하여 시청 몰입감 극대화

2. **웹뷰 패치 버전 갱신 (캐시 즉시 무효화)**
   - `PATCH_VERSION = 12` 갱신을 통해 기존 기기 캐시를 즉시 갱신하고 최신 광고 차단 규칙 적용

3. **기존 핵심 기능 계승 및 안정화**
   - 100% 무광고 (프리롤/미드롤/배너/스폰서 차단)
   - 4K UHD (2160p 60fps) & 8K (4320p) 화질 언락
   - OLED 순정 완전 투명 HUD & 리얼 블랙 최적화
   - 사이드바 초고속 내비게이션 락 & 계정 선택 화면 정상 종료

---

### 📦 첨부 설치 파일 (Assets)
- **`YT_TV_AC.apk`**: Android TV / Google TV 최신 패키지 (v1.0.6, 5.2 MB)
- **`YT_TV_AC_Tizen.wgt`**: 삼성 스마트 TV(Tizen OS) 설치용 패키지
- **`YT_TV_AC_webOS.ipk`**: LG 스마트 TV(webOS) 설치용 패키지
