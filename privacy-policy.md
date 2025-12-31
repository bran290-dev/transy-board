---
layout: default
title: 개인정보처리방침
nav_order: 99
---

# 개인정보처리방침 (Privacy Policy)

**시행일**: 2025년 1월 1일
**최종 수정일**: 2025년 12월 30일

Transy(이하 "앱")는 사용자의 개인정보를 중요하게 생각하며, 관련 법령을 준수합니다. 본 개인정보처리방침은 앱이 수집하는 정보와 그 사용 방법에 대해 설명합니다.

---

## 1. 수집하는 정보

### 1.1 사용자가 직접 제공하는 정보

| 정보 유형 | 설명 | 저장 위치 |
|-----------|------|-----------|
| Gemini API 키 | 번역 기능 사용을 위해 사용자가 직접 입력 | 기기 로컬 저장소 (암호화) |
| 소설 URL | 사용자가 추가한 웹소설 주소 | 기기 로컬 저장소 |
| 앱 설정 | 폰트 크기, TTS 설정 등 사용자 환경설정 | 기기 로컬 저장소 |

**중요**: 위 정보는 모두 **사용자의 기기에만 저장**되며, 개발자 서버로 전송되지 않습니다.

### 1.2 자동으로 수집되는 정보

| 정보 유형 | 목적 | 수집 주체 |
|-----------|------|-----------|
| 크래시 로그 | 앱 오류 분석 및 품질 개선 | Firebase Crashlytics |
| 광고 ID | 맞춤형 광고 제공 | Google AdMob |
| 앱 사용 통계 | 익명화된 앱 성능 지표 | Firebase Analytics (선택적) |

---

## 2. 수집하지 않는 정보

앱은 다음 정보를 **수집하지 않습니다**:

- 이름, 이메일, 전화번호 등 개인 식별 정보
- 금융 정보 (인앱 결제는 Google Play Billing을 통해 처리)
- 위치 정보
- 연락처 또는 사진
- 기기의 다른 앱 정보

---

## 3. 정보의 사용 목적

수집된 정보는 다음 목적으로만 사용됩니다:

1. **앱 기능 제공**: 번역 서비스 실행 및 사용자 설정 유지
2. **품질 개선**: 크래시 분석을 통한 버그 수정
3. **광고 표시**: Google AdMob을 통한 광고 제공

---

## 4. 제3자 서비스

앱은 다음 제3자 서비스를 사용합니다:

### 4.1 Google Gemini API
- **목적**: AI 기반 번역 서비스 제공
- **전송 데이터**: 번역할 소설 원문 텍스트
- **개인정보처리방침**: [Google Privacy Policy](https://policies.google.com/privacy)

### 4.2 Firebase Crashlytics
- **목적**: 앱 크래시 분석 및 안정성 개선
- **전송 데이터**: 크래시 로그, 기기 정보 (모델, OS 버전)
- **개인정보처리방침**: [Firebase Privacy](https://firebase.google.com/support/privacy)

### 4.3 Google AdMob
- **목적**: 광고 표시
- **전송 데이터**: 광고 ID, 광고 상호작용 정보
- **개인정보처리방침**: [Google Ads Privacy](https://policies.google.com/technologies/ads)

### 4.4 Google Play Billing
- **목적**: 프리미엄 기능 결제 처리
- **전송 데이터**: 결제 정보는 Google이 직접 처리 (앱에서 접근 불가)
- **개인정보처리방침**: [Google Payments Privacy](https://payments.google.com/payments/apis-secure/get_legal_document?ldo=0&ldt=privacynotice)

---

## 5. 데이터 보관 및 삭제

### 5.1 로컬 데이터
- 모든 사용자 데이터는 기기에 저장됩니다
- 앱 삭제 시 모든 로컬 데이터가 자동으로 삭제됩니다
- 설정 메뉴에서 언제든지 데이터를 수동으로 삭제할 수 있습니다

### 5.2 제3자 서비스 데이터
- Firebase 및 AdMob 데이터는 각 서비스의 보관 정책을 따릅니다
- 데이터 삭제를 원하시면 아래 연락처로 요청해 주세요

---

## 6. 데이터 보안

앱은 다음과 같은 보안 조치를 적용합니다:

- API 키는 Android Keystore를 통해 암호화 저장
- 네트워크 통신은 HTTPS/TLS 암호화 사용
- 민감한 데이터는 외부 서버로 전송하지 않음

---

## 7. 아동 개인정보 보호

앱은 **13세 미만 아동을 대상으로 하지 않습니다**. 13세 미만 아동의 개인정보를 의도적으로 수집하지 않으며, 해당 정보가 수집된 것을 인지하는 경우 즉시 삭제합니다.

---

## 8. 사용자의 권리

사용자는 다음 권리를 가집니다:

1. **데이터 접근권**: 저장된 데이터 확인 (앱 설정 메뉴에서 확인 가능)
2. **데이터 삭제권**: 언제든지 앱 데이터 삭제 가능
3. **광고 개인화 거부권**: 기기 설정에서 광고 ID 재설정 또는 개인화 광고 비활성화 가능

---

## 9. 개인정보처리방침 변경

본 방침이 변경되는 경우, 앱 내 공지 또는 이 페이지를 통해 안내드립니다. 중요한 변경사항은 시행 최소 7일 전에 고지합니다.

---

## 10. 연락처

개인정보 관련 문의사항이 있으시면 아래로 연락해 주세요:

- **이메일**: bran290.dev@gmail.com
- **GitHub Issues**: [https://github.com/bran290/Transy/issues](https://github.com/bran290/Transy/issues)

---

## Privacy Policy (English Summary)

**Transy** is a web novel translation app that uses AI (Google Gemini) to translate foreign novels into Korean.

### Data We Collect
- **User-provided**: Gemini API key, novel URLs, app settings (stored locally on device only)
- **Automatically collected**: Crash logs (Firebase), advertising ID (AdMob)

### Data We Do NOT Collect
- Personal identification information (name, email, phone)
- Financial information
- Location data
- Contacts or photos

### Third-Party Services
- Google Gemini API (translation)
- Firebase Crashlytics (crash reporting)
- Google AdMob (advertising)
- Google Play Billing (in-app purchases)

### Your Rights
- Access your data through app settings
- Delete all data by uninstalling the app
- Opt out of personalized ads in device settings

### Contact
- Email: bran290.dev@gmail.com

---

*This privacy policy is effective as of January 1, 2025.*
