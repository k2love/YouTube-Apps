# YouTube-Apps (스마트 TV 통합 공식 배포)

[![Android](https://img.shields.io/badge/Platform-Android%20TV%20%7C%20Google%20TV-3DDC84?logo=android&logoColor=white)](https://www.android.com/tv/)
[![Tizen](https://img.shields.io/badge/Platform-Samsung%20Tizen-1B60A5?logo=samsung&logoColor=white)](https://github.com/k2love/YouTube-for-SamsungTV)
[![webOS](https://img.shields.io/badge/Platform-LG%20webOS-CF0A2C?logo=lg&logoColor=white)]()
[![Latest Release](https://img.shields.io/github/v/release/k2love/YouTube-Apps?color=FF0000&label=Latest%20Release)](https://github.com/k2love/YouTube-Apps/releases/latest)
[![Ad-Free](https://img.shields.io/badge/Ad--Free-100%25%20Zero--Ad-brightgreen)]()
[![Resolution](https://img.shields.io/badge/Resolution-4K%20%2F%208K%20Unlocked-blue)]()
[![License](https://img.shields.io/badge/License-MIT-orange)]()

안드로이드 TV(Android TV), 구글 TV(Google TV), 삼성 스마트 TV(Tizen), LG 스마트 TV(webOS)를 위한 고성능 무광고 무중단 스트리밍 클라이언트 통합 공식 배포 저장소입니다.

순정 YouTube TV의 직관적인 리모컨 D-Pad 조작성과 모든 UI를 100% 그대로 유지하면서, 광고를 원천 차단하고 4K/8K 고화질 및 완전 투명 HUD를 제공합니다.

---

## 📦 최신 릴리즈 다운로드 (Download)

사용자의 TV 사양과 환경에 맞춰 최적의 버전을 선택할 수 있도록 **[안드로이드 TV 이원화 라인업]**을 제공합니다:

| 플랫폼 / 에디션 | 설치 패키지 | 파일 크기 | 권장 대상 및 주요 특징 | 다운로드 링크 |
| :--- | :--- | :--- | :--- | :--- |
| **Android TV (Chrobalt)** | `YT_TV_Chrobalt.apk` | 약 75 MB | 🏆 **[추천] 최신 스마트 TV 최적화 (Cobalt C++ 네이티브)**<br>• 순정 YouTube C++ 네이티브 미디어 엔진(`libchrobalt.so`) 탑재<br>• 4K 60fps 무중단 하드웨어 가속 (Direct Tunnel Mode)<br>• JNI 직접 주입 0ms 무광고 & 스마트 쇼핑 QR 차단<br>• 리모컨 채널+/- 키로 0.25x~4.0x 배속 조절 (OSD 뱃지) & 1.0x 리셋 | [📥 **다운로드**](https://github.com/k2love/YouTube-Apps/releases/latest) |
| **Android TV (Lightweight)** | `YT_TV_AC.apk` | 약 5.2 MB | 🪶 **초경량 / 구형 및 보급형 기기용 (Lightweight WebView)**<br>• 5.2 MB 초경량 시스템 웹뷰 기반 아키텍처<br>• 저장 공간이 부족하거나 스펙이 제한된 구형 TV에 최적<br>• 100% 무광고 & OLED 완전 투명 HUD<br>• 리모컨 채널+/- 키로 0.25x~4.0x 배속 조절 & 1.0x 리셋 | [📥 **다운로드**](https://github.com/k2love/YouTube-Apps/releases/latest) |
| **Samsung Smart TV (Tizen)** | `YT_TV_AC_Tizen.wgt` | 약 1.0 MB | 📺 **삼성 스마트 TV 전용** (2018년 이후 타이젠 모델)<br>• 100% 제로-애드 & OLED 투명 HUD | [📺 **Tizen 저장소**](https://github.com/k2love/YouTube-for-SamsungTV) \| [📥 **WGT 받기**](https://github.com/k2love/YouTube-Apps/releases/latest) |
| **LG Smart TV (webOS)** | `YT_TV_AC_webOS.ipk` | 약 0.03 MB | 📺 **LG 스마트 TV 전용** (webOS 3.0 이상)<br>• 100% 제로-애드 & OLED 투명 HUD | [📥 **IPK 받기**](https://github.com/k2love/YouTube-Apps/releases/latest) |

---

## ✨ 핵심 기능 (Features)

- 🛡️ **100% 제로-애드 (Zero-Ad Architecture)**
  - 프리롤(시작 전), 미드롤(시청 중), 포스트롤, 홈 화면 배너 및 스폰서 광고를 네트워크 및 런타임 레벨에서 원천 차단합니다.
  - 영상 전환 시 잔류 광고 오디오가 흘러나오는 현상을 네이티브 킬스위치로 완벽 방지합니다.
- 🚫 **스마트 쇼핑 QR 코드 차단 (로그인 QR 코드 보존)**
  - 시청 중 화면 우측 하단을 가리는 거치적거리는 협찬/쇼핑 QR 코드를 100% 차단하며, 모바일 계정 연동(`yt.be/activate`) 로그인 QR 코드는 정상 노출됩니다.
- 🎬 **4K UHD (2160p 60fps) 고화질 하드웨어 가속**
  - 저사양 기기로 오인식되어 강제 다운그레이드되던 화질 제한을 해제하고, 최대 4K 60fps 및 8K 화질 옵션을 자유롭게 선택할 수 있습니다.
- ⚡ **리모컨 채널 키 배속 제어 (0.25x ~ 4.0x) & 원클릭 리셋**
  - 리모컨 채널+(`CHANNEL_UP`), 채널-(`CHANNEL_DOWN`) 키로 재생 속도를 0.25배속부터 4.0배속까지 실시간 조절(OSD 뱃지 표시)할 수 있으며, 노랑 버튼을 누르면 `1.0x (일반)`으로 즉시 리셋됩니다.
- 🕶️ **순정 완전 투명 UI (Pure Transparent OLED HUD)**
  - 시청 중 화면을 가리는 어두운 그라데이션 박스(Scrim)를 제거하여, OLED TV의 완벽한 리얼 블랙 명암비와 깔끔한 자막/컨트롤을 제공합니다.
- 🎮 **스마트 TV 리모컨 완벽 지원**
  - 방향키, 선택, 뒤로가기는 물론 재생/일시정지, 탐색, 배속 조절 단축키를 완벽 지원합니다.

---

## 🚀 안드로이드 TV 설치 방법 (Installation)

### 방법 1: TV의 'Downloader' 앱 사용 (가장 간편한 방법)
1. Android TV / Google TV의 구글 플레이 스토어에서 **Downloader by AFTVnews** 앱을 설치합니다.
2. Downloader 앱을 실행하고 URL 입력창에 최신 릴리즈 링크를 입력하거나 브라우저 기능을 통해 원하는 에디션(`YT_TV_Chrobalt.apk` 또는 `YT_TV_AC.apk`)을 다운로드합니다.
3. 다운로드 완료 후 화면의 안내에 따라 **[설치]**를 누르면 완료됩니다.
   > *최초 설치 시 "출처를 알 수 없는 앱 설치" 권한 허용이 필요합니다.*

### 방법 2: USB 드라이브를 통한 설치
1. PC에서 최신 APK 파일을 다운로드하여 USB 메모리에 복사합니다.
   - 최신 고성능 TV: `YT_TV_Chrobalt.apk` 권장
   - 구형/보급형 TV: `YT_TV_AC.apk` 권장
2. USB를 스마트 TV에 연결한 후 파일 관리자(File Commander 등)로 APK를 선택하여 설치합니다.

### 방법 3: ADB 네트워크 무선 설치 (개발자/고급 사용자)
1. TV의 `설정` → `기기 환경설정` → `개발자 옵션`에서 **네트워크 디버깅**을 켭니다.
2. PC 터미널에서 아래 명령어로 설치합니다:
   ```bash
   adb connect <TV_IP_주소>:5555
   # 최신 스마트 TV 권장
   adb install -r YT_TV_Chrobalt.apk
   # 또는 구형 기기용
   adb install -r YT_TV_AC.apk
   ```

---

## 💬 문제 제보 및 건의사항 (Bug Report & Feedback)

앱 사용 중 발생하는 버그나 기능 건의사항은 [GitHub Issues](https://github.com/k2love/YouTube-Apps/issues)에 자유롭게 남겨주세요.

---

## 📜 면책 조항 (Disclaimer)

본 프로젝트는 순수 연구 및 학습 목적의 비상업적 오픈소스 릴리즈 프로젝트입니다. YouTube 및 Google TV는 Google LLC의 등록 상표입니다.
