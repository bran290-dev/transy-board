---
layout: default
title: 홈
nav_order: 0
permalink: /
---

# Transy 사용자 매뉴얼

AI 기반 웹소설 번역 앱 Transy의 공식 사용자 가이드입니다.

---

> **처음 사용하시나요?**
> 스크린샷과 함께 따라하는 [튜토리얼](tutorial/)을 확인해보세요! 10분이면 첫 번역을 시작할 수 있어요.

---

## 목차

### 시작하기
- [스크린샷 튜토리얼](tutorial/) - 처음이라면 여기부터!
- [앱 설치](getting-started/installation.md)
- [API 키 설정](getting-started/api-key-setup.md)
- [첫 소설 추가하기](getting-started/first-novel.md)

### 소설 관리
- [URL로 소설 추가](novel-management/add-novel-url.md)
- [파일로 소설 추가](novel-management/add-novel-file.md)
- [텍스트 직접 입력](novel-management/add-novel-text.md)
- [라이브러리 관리](novel-management/library.md)
- [소설 업데이트](novel-management/novel-refresh.md)

### 소설 읽기
- [뷰어 기본 사용법](reading/reader-basic.md)
- [번역 기능](reading/translation.md)
- [미리 받기](reading/prefetch.md)
- [회차 분할](reading/chapter-split.md)
- [찾아바꾸기](reading/find-replace.md)
- [디스플레이 설정](reading/display-settings.md)

### TTS (음성 읽기)
- [Android TTS](tts/android-tts.md)
- [Gemini TTS](tts/gemini-tts.md)

### 컨텍스트 시스템
- [시스템 개요](context/overview.md)
- [캐릭터 관리](context/character.md)
- [용어 관리](context/terminology.md)
- [관계 관리](context/relationship.md)
- [사건/대사 관리](context/events.md)
- [회차 요약](context/episode-summary.md)

### 고급 기능
- [소설별 설정](advanced/novel-settings.md)
- [API 설정 체인](advanced/fallback-chain.md)
- [API 사용량 모니터링](advanced/api-usage.md)
- [파싱 룰 생성](advanced/parsing-rules.md)
- [번역 프롬프트 커스터마이징](advanced/translation-prompt.md)
- [프롬프트 로그 뷰어](advanced/prompt-log.md)

### 내보내기
- [번역 내보내기 (EPUB/TXT/HTML)](export/export-novel.md)

### 도움말
- [자주 묻는 질문 (FAQ)](faq.md)
- [문제 해결](troubleshooting/common-issues.md)

---

## 앱 다운로드

[Google Play Store에서 다운로드](https://play.google.com/store/apps/details?id=com.dhmo.transyv2)

---

## 앱 미리보기

---

## 주요 기능

| 기능 | 설명 |
|------|------|
| AI 번역 | Gemini AI를 활용한 고품질 번역 |
| 컨텍스트 시스템 | 캐릭터/용어 관리로 일관된 번역 품질 유지 |
| 미리 받기(프리패치) | 다음 회차를 미리 번역하여 끊김 없는 독서 경험 제공 |
| TTS | Android 기본 TTS 및 Gemini 고품질 TTS 지원 |
| 다양한 소스 | URL, 파일(TXT/EPUB), 텍스트 직접 입력 지원 |
| 내보내기 | EPUB, TXT, HTML 형식으로 번역 결과 내보내기 |

---

## 빠른 시작

1. **앱 설치** - [Play Store에서 Transy 설치](getting-started/installation.md)
2. **API 키 등록** - [설정에서 Gemini API 키 등록](getting-started/api-key-setup.md) (추천: Gemini 2.5 Flash)
3. **소설 추가** - 아래 3가지 방법 중 선택:
   - [URL로 소설 추가](novel-management/add-novel-url.md) — 웹소설 사이트에서 직접 가져오기 (파싱 룰 필요)
   - [파일로 소설 추가](novel-management/add-novel-file.md) — EPUB/TXT 파일 임포트 (파싱 룰 불필요)
   - [텍스트 직접 입력](novel-management/add-novel-text.md) — 텍스트 복사/붙여넣기 (파싱 룰 불필요)
4. **읽기 시작** - [자동 번역과 함께 소설 읽기](reading/reader-basic.md)

> **파일/텍스트 사용자는** Step 2(파싱 룰 만들기)를 건너뛰세요!

자세한 내용은 [스크린샷 튜토리얼](tutorial/)을 참조하세요.

---

## 법적 정보

- [면책조항 (Disclaimer)](disclaimer.md)
- [개인정보처리방침 (Privacy Policy)](privacy-policy.md)

---

## 기업용 번역

기업 환경에서 대량 번역, API 연동 등이 필요하신가요?

➡️ [기업용 번역 문의](enterprise.md)

---

## 문의 및 피드백

문의사항이나 피드백은 이메일로 보내주세요:

- **이메일**: bran290.dev@gmail.com
