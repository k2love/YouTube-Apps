### 🚀 변경 사항 (v1.0.6)

1. **YouTube Shopping 제휴 QR코드 광고 영구 차단**:
   - 영상 특정 타임코드에 노출되는 제휴 상품 타임리 액션 QR코드(`ytlr-shopping-timely-action-renderer`, `ytlr-qr-code-renderer`) 원천 차단.
   - 마스터 CSS 0ms 은폐, 50ms 런타임 DOM 킬스위치, JSON 페이로드 사전 필터링의 3중 방어막 적용.
2. **웹뷰 패치 버전 갱신**:
   - `PATCH_VERSION = 12` 갱신을 통한 인메모리/디스크 캐시 즉시 무효화.
3. **버전 업데이트**:
   - `versionCode: 7`, `versionName: 1.0.6`
