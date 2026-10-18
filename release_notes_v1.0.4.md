# YouTube for Android TV v1.0.4 (공식 릴리즈)

안드로이드 TV 및 스마트 TV를 위한 고성능 무광고 무중단 스트리밍 클라이언트 v1.0.4 최신 정식 버전입니다.

---

### 🚀 주요 업데이트 및 개선 내역

1. **v7.29.300 네이티브 엔진 벤치마킹 반영**
   - `h5vcc.storage`에 `verifyTest()`, `writeTest()` 자가진단 메서드 추가 (웹앱 스토리지 질의 에러 방지)
   - `SourceBuffer.prototype.changeType` 동적 코덱 전환 가드 추가 (해상도 및 광고 전환 시 화면 깜빡임/버퍼링 방지)
   - `TVWebView` 렌더러 우선순위 정책(`RENDERER_PRIORITY_BOUND`) 고정으로 60fps 프레임 레이트 안정화

2. **200px UI 상단 쏠림 현상 원천 해결**
   - 다른 앱 전환 후 복귀 시 몰입형 전체화면(`hideSystemUI()`) 즉시 재적용 (`onWindowFocusChanged`)
   - Android 9.0+ 디스플레이 컷아웃 모드(`LAYOUT_IN_DISPLAY_CUTOUT_MODE_SHORT_EDGES`) 적용
   - 시스템 바 인셋 강제 소비로 뷰포트 Y좌표 변위 영구 차단

3. **100% 무광고 살균 및 4K/8K 언락**
   - 프리롤/미드롤/포스트롤 강제 광고 및 스폰서 배너 완전 차단
   - 4K UHD 60fps 및 8K 화질 옵션 해금
   - OLED Pure Black & 완전 투명 제로 스크림 UI

---

### 📦 첨부 설치 파일 (Assets)
- **`YT_TV_AC.apk`**: Android TV / Google TV 설치용 패키지 (5.2 MB)
- **`YT_TV_AC_Tizen.wgt`**: 삼성 스마트 TV(Tizen OS) 설치용 패키지 (988 KB)
- **`YT_TV_AC_webOS.ipk`**: LG 스마트 TV(webOS) 설치용 패키지 (28 KB)
