# Claude 사용 이력 요약

> 이 문서는 **기록용 요약본**입니다. 작업 지시나 프로젝트 규칙이 아닙니다.

- **작성일:** 2026-08-21
- **집계 범위:** 2026-06-08 ~ 2026-08-21 (약 2개월 반)
- **총 세션 수:** 66개 (진행 중인 현재 세션 포함)
- **집계 대상:** Claude Code 데스크톱 세션 (아래 "집계 범위에 대한 참고" 항목 확인)

---

## 1. 한눈에 보기

| 주제 | 세션 수 | 대표 작업 |
|---|---|---|
| 영어 단어장·학습 영상 자동 제작 | 14 | 해커스 보카 영상화, Remotion 단어 영상 생성기 |
| SAP · ABAP 업무 | 11 | S/4HANA 리포트 개발, ABAP 지식베이스, 개발 자동화 |
| 게임 제작 (Godot · Blender) | 8 | 탕탕특공대 2D 서바이버, EXIT 67 |
| 자녀 교육·학습 자료 | 8 | 학습 진단 분석, 교과과정 정리, Python 교재, 한자 영상 |
| TTS · 음성 생성 | 5 | Qwen TTS 음성 클론, Fish Speech 샘플 |
| Eclipse 플러그인 개발 | 5 | ABAP 코딩 보조 LLM 플러그인 |
| 영어 원서 읽기 (39 Clues) | 4 | 읽기 학습 웹페이지, 원서 자료 정리 |
| 영문법 학습 프로그램 | 4 | 문법 문제 데이터셋 생성, 로직 검토 |
| 기타 도구·기획 | 4 | 홈페이지 기획, ComfyUI, Mermaid 뷰어 |
| 사내 발표 자료 | 1 | AI 활용 10분 PT 시나리오 (현재 세션) |

**흐름을 보면** 6월에는 SAP/ABAP 업무 자동화와 Eclipse 플러그인 개발이 중심이었고, 6월 말부터 게임·3D 모델링으로 넓어졌습니다. 7월에는 영어 학습 콘텐츠 자동화(단어장·원서·한자)와 TTS가 주축이 되었고, 8월에는 이것들이 **영상 자동 생성 파이프라인**으로 수렴하면서 자녀 교육 자료와 사내 발표 준비가 더해졌습니다.

---

## 2. 주제별 세션 목록

### 영어 단어장 · 학습 영상 자동 제작 (14)

| 날짜 | 제목 |
|---|---|
| 08-18 | 콘텐츠 이미지프롬프트 생성 |
| 08-18 | 영어단어장 동영상 생성 프로젝트 검토 |
| 08-18 | 비디오 자동 생성 가능성 |
| 08-10 | 단어장 비디오 생성 TTS 업데이트 |
| 08-10 | 어휘 비디오 생성 프롬프트 |
| 08-09 | video_gen_google_flow_kr 프롬프트 개선 |
| 07-28 | 해커스 보카 자동화 프로젝트 |
| 07-27 | 18일차 4세트 이미지 생성 프롬프트 |
| 07-18 | 해커스 단어 암기 동영상 제작 |
| 07-02 | Remotion 단어장 영상 생성기 (Remotion vocabulary video generator) |
| 07-02 | 해커스 단어 파일 정리 (Hackers vocabulary file organization) |
| 07-02 | req.txt 작업 지시 실행 |
| 07-02 | req.txt 폴더 지시 확인 |
| 06-29 | req.txt 실행 |

### SAP · ABAP 업무 (11)

| 날짜 | 제목 |
|---|---|
| 08-10 | 폴더 파일 검토 (ZMMR3081) |
| 08-10 | 두 문서 검토 (ZMMR3081) |
| 08-10 | SAP S/4 HANA PO 입고 리포트 프로그램 |
| 07-13 | 작업 지시서 슬라이드 검토 (Work instructions slide review) |
| 07-06 | ADT MCP 서버 문서화 (ADT MCP Server standalone documentation) |
| 07-05 | ABAP 지식베이스 그래프 구조 설계 (Stores layer 1 graph structure) |
| 07-05 | ABAP 자동화 코드 리뷰 |
| 07-03 | SAP S/4 HANA AI 개발 자동화 |
| 06-10 | 로컬 LLM SAP RFC 연동 |
| 06-10 | ABAP 프로그램 비교 (제목 없는 세션) |
| 06-09 | ABAP 프로그램 버전 비교 |

### 게임 제작 · 3D (8)

| 날짜 | 제목 |
|---|---|
| 08-16 | 탕탕특공대 2D 서바이버 게임 |
| 08-13 | Godot 탕탕특공대 게임 개발 |
| 07-05 | 코드 분석 및 개선 리포트 (EXIT 67) |
| 06-28 | 캐릭터 모델 렌더링 문제 |
| 06-28 | 이미지 기반 3D 모델링 |
| 06-10 | EXIT 67 게임 기획 및 구현 |
| 06-09 | 참조 이미지 기반 Blender 모델링 |
| 06-08 | Blender MCP 서버 설정 |

### 자녀 교육 · 학습 자료 (8)

| 날짜 | 제목 |
|---|---|
| 08-20 | 초등학교 6학년 자기주도 학습 진단 분석 |
| 08-19 | 2022 개정 중학교 1학년 교과과정 |
| 07-11 | 한자 프로젝트 인수인계 검토 (Hanja_67 handoff review) |
| 07-10 | Remotion 한자 암기 영상 |
| 06-28 | Python 과제 디버깅 |
| 06-21 | Junior KAIST Python 교재 변환 |
| 06-14 | Python 과제 검토 |
| 06-13 | Python 학습 과제 노트북 |

### TTS · 음성 생성 (5)

| 날짜 | 제목 |
|---|---|
| 08-11 | Antigravity CLI TTS 기능 |
| 08-06 | Colab MCP 연결 |
| 08-02 | Qwen TTS 음성 클론 자동화 시스템 |
| 07-27 | TTS 모델 샘플 생성 (Fish Speech) |
| 07-27 | Qwen3 TTS 음성 생성 |

### Eclipse 플러그인 개발 (5)

| 날짜 | 제목 |
|---|---|
| 06-14 | Eclipse Continue 플러그인 서버 응답 오류 |
| 06-12 | Eclipse 플러그인 개발 |
| 06-12 | Eclipse OpenAI LLM 플러그인 설계 |
| 06-12 | Eclipse OpenAI LLM 플러그인 설계 (이어서) |
| 06-11 | ABAP 코딩 지원 Eclipse 플러그인 설계 |

### 영어 원서 읽기 — 39 Clues (4)

| 날짜 | 제목 |
|---|---|
| 07-30 | Cloudflare 액세스 정책 설정 |
| 07-29 | One False Note 인물 사진 수집 |
| 07-29 | 영어 읽기 학습 웹페이지 PRD |
| 07-29 | One False Note 마크다운 정리 |

### 영문법 학습 프로그램 (4)

| 날짜 | 제목 |
|---|---|
| 06-28 | 문법 프로그램 로직 검토 |
| 06-28 | 학생 정보 검증 함수 |
| 06-28 | 문법 연습 데이터셋 생성 |
| 06-27 | LLM HTTP 429 요청 한도 오류 |

### 기타 도구 · 기획 (4)

| 날짜 | 제목 |
|---|---|
| 07-07 | 한국오일켐 홈페이지 기획 |
| 07-04 | 영상 생성용 ComfyUI 세팅 |
| 06-30 | Mermaid 다이어그램 뷰어 제작 |
| 06-09 | Claude Code 작업 폴더 변경 방법 |

### 사내 발표 자료 (1)

| 날짜 | 제목 |
|---|---|
| 08-20 ~ 08-21 | AI 활용 10분 PT 시나리오 작성 (현재 세션) |

---

## 3. 전체 시간순 목록

| 날짜 | 제목 | 작업 폴더 |
|---|---|---|
| 08-21 | AI 활용 10분 PT 시나리오 작성 | `skax\20260910_10min_pt` |
| 08-20 | 초등학교 6학년 자기주도 학습 진단 분석 | `서준형_진단검사` |
| 08-19 | 2022 개정 중학교 1학년 교과과정 | `junbe_study\middle_1st` |
| 08-18 | 콘텐츠 이미지프롬프트 생성 | `english\hackers_video_project_v2` |
| 08-18 | 영어단어장 동영상 생성 프로젝트 검토 | `english\hackers_video_project_v2` |
| 08-18 | 비디오 자동 생성 가능성 | `english\hackers_video_project` |
| 08-16 | 탕탕특공대 2D 서바이버 게임 | `game_make\test_godot_2` |
| 08-13 | Godot 탕탕특공대 게임 개발 | `game_make\test_godot_2` |
| 08-11 | Antigravity CLI TTS 기능 | `english\hackers_video_project` |
| 08-10 | 폴더 파일 검토 | `hynix\ZMMR3081` |
| 08-10 | 단어장 비디오 생성 TTS 업데이트 | `english\hackers_video_project` |
| 08-10 | 두 문서 검토 | `hynix\ZMMR3081` |
| 08-10 | 어휘 비디오 생성 프롬프트 | `english\laha_english` |
| 08-10 | SAP S/4 HANA PO 입고 리포트 프로그램 | `hynix\ZMMR3081` |
| 08-09 | video_gen_google_flow_kr 프롬프트 개선 | `english\laha_english` |
| 08-06 | Colab MCP 연결 | `tts` |
| 08-02 | Qwen TTS 음성 클론 자동화 시스템 | `tts` |
| 07-30 | Cloudflare 액세스 정책 설정 | `english\laha_books\39clues_book2` |
| 07-29 | One False Note 인물 사진 수집 | `english\laha_books\39clues_book2` |
| 07-29 | 영어 읽기 학습 웹페이지 PRD | `english\laha_books\39clues_book2` |
| 07-29 | One False Note 마크다운 정리 | `english\laha_books\39clues_book2` |
| 07-28 | 해커스 보카 자동화 프로젝트 | `english\hackers_video_project` |
| 07-27 | TTS 모델 샘플 생성 | `tts\fish_speech` |
| 07-27 | Qwen3 TTS 음성 생성 | `tts\qwen3_tts_1.7b` |
| 07-27 | 18일차 4세트 이미지 생성 프롬프트 | `junbe_study\voca_video_plan` |
| 07-18 | 해커스 단어 암기 동영상 제작 | `junbe_study\voca_video_plan` |
| 07-13 | 작업 지시서 슬라이드 검토 | `abap_beginner_2026` |
| 07-11 | 한자 프로젝트 인수인계 검토 | `Codex\hanja_67` |
| 07-10 | Remotion 한자 암기 영상 | `Codex\hanja` |
| 07-07 | 한국오일켐 홈페이지 기획 | `KOREA_OC` |
| 07-06 | ADT MCP 서버 문서화 | `Codex\sap_adt_mcp_server` |
| 07-05 | ABAP 지식베이스 그래프 구조 설계 | `Claude\abap_knowledge_base` |
| 07-05 | 코드 분석 및 개선 리포트 | `exit8_67` |
| 07-05 | ABAP 자동화 코드 리뷰 | `Claude\abap_dev_automation` |
| 07-04 | 영상 생성용 ComfyUI 세팅 | `Claude\comfy` |
| 07-03 | SAP S/4 HANA AI 개발 자동화 | `Claude\abap_dev_automation` |
| 07-02 | Remotion 단어장 영상 생성기 | `Claude\remotion\test` |
| 07-02 | req.txt 작업 지시 실행 | `english\hackers` |
| 07-02 | 해커스 단어 파일 정리 | `english\hackers` |
| 07-02 | req.txt 폴더 지시 확인 | `english\hackers` |
| 06-30 | Mermaid 다이어그램 뷰어 제작 | `for_work\mermaid_viewer` |
| 06-29 | req.txt 실행 | `laha_english` |
| 06-28 | 문법 프로그램 로직 검토 | `grammer_basic` |
| 06-28 | 캐릭터 모델 렌더링 문제 | `exit8_67` |
| 06-28 | 이미지 기반 3D 모델링 | `PyCharmMiscProject` |
| 06-28 | Python 과제 디버깅 | `PyCharmMiscProject` |
| 06-28 | 학생 정보 검증 함수 | `grammer_basic` |
| 06-28 | 문법 연습 데이터셋 생성 | `grammer_basic` |
| 06-27 | LLM HTTP 429 요청 한도 오류 | `grammer_basic` |
| 06-21 | Junior KAIST Python 교재 변환 | `junior_kaist\textbook` |
| 06-14 | Eclipse Continue 플러그인 서버 응답 오류 | `Claude\eclipse_continue` |
| 06-14 | Python 과제 검토 | `junior_kaist\NEVERTOUCH` |
| 06-13 | Python 학습 과제 노트북 | `junior_kaist` |
| 06-12 | Eclipse 플러그인 개발 | `Claude\eclipse_continue` |
| 06-12 | Eclipse OpenAI LLM 플러그인 설계 | `Claude\eclipse_continue` |
| 06-12 | Eclipse OpenAI LLM 플러그인 설계 | `Claude\eclipse_llmhelp` |
| 06-11 | ABAP 코딩 지원 Eclipse 플러그인 설계 | `Claude\eclipse_llmhelp` |
| 06-10 | 로컬 LLM SAP RFC 연동 | `Claude\erp_caller` |
| 06-10 | EXIT 67 게임 기획 및 구현 | `Claude\exit8` |
| 06-10 | ABAP 프로그램 비교 (제목 없음) | `Claude\abapcompare` |
| 06-09 | ABAP 프로그램 버전 비교 | `Claude\abapcompare` |
| 06-09 | Claude Code 작업 폴더 변경 방법 | `Claude\exit8` |
| 06-09 | 참조 이미지 기반 Blender 모델링 | `Claude\exit8` |
| 06-08 | Blender MCP 서버 설정 | `Claude\exit8` |

---

## 4. 집계 범위에 대한 참고

- 이 목록은 **Claude Code 데스크톱 앱의 로컬 세션 기록**을 기준으로 합니다.
- **claude.ai 웹·모바일 앱의 대화 기록은 포함되어 있지 않습니다.** 그쪽 기록에는 접근 권한이 없어 조회할 수 없었습니다. 필요하시면 claude.ai에서 직접 내보내신 뒤 알려주시면 이 문서에 합쳐 드릴 수 있습니다.
- 세션 제목은 앱이 대화 내용을 바탕으로 자동 생성한 것이라, 실제 작업 범위와 조금 다를 수 있습니다. 영문 제목은 뜻이 통하도록 한글로 옮기고 필요한 곳에는 원문을 함께 적었습니다.
- 날짜는 각 세션의 **마지막 활동 시각** 기준입니다. 여러 날에 걸쳐 이어 간 세션은 마지막 날짜 한 곳에만 나타납니다.
