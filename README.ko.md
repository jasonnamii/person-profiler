# 인물 프로파일링 엔진

> 🇺🇸 [English README](./README.md)

**7축 웹 리서치 엔진: 핵심 DNA 특성, 강점, 약점, 30초 엘베피치 추출**

## 사전 요구사항

- **Claude Cowork 또는 Claude Code** 환경
- **웹 검색 접근** — 실시간 인물 리서치 필수

## 목적

person-profiler는 흩어진 공개 정보를 실행 가능한 인사이트로 변환합니다. 웹 신호를 7가지 전략축(경력DNA, 의사결정 패턴, 비전, 평판, 개성, 관계망, 현재상황)으로 구조화하고, 5-7개 핵심 DNA 특성을 추출하며, 강점/약점을 평가하고, 30초 엘베피치를 생성합니다.

## 사용 시점 및 방법

미팅, 파트너십, 채용, 투자 의사결정을 위해 인물을 리서치할 때 배치하세요. 목표 웹 리서치를 수행하고 7축 프레임워크로 통합합니다. 더 깊은 분석을 위해 research-frame과 조합합니다.

## 사용 예시

| 상황 | 프롬프트 | 결과 |
|---|---|---|
| 미팅 전 리서치 | `"Profile Jessica Chen, Partner at Sequoia"` | 경력DNA→의사결정패턴→관계망→대화 준비용 30초 피치 |
| CEO 리더십 분석 | `"Build profile of new CEO of partner company"` | 비전→평판→개성→강점 + 약점 |
| 채용 평가 | `"Profile finalist for Head of Product"` | 경력DNA→의사결정패턴→비전→전체적 강점/약점 프로필 |

## 핵심 기능

- 7축 리서치 프레임워크: 경력DNA, 의사결정패턴, 비전, 평판, 개성, 관계망, 현재상황
- 5-7대 핵심 DNA 특성 통합
- 강점 및 약점 평가
- 30초 엘베피치 자동 생성
- 웹 리서치 통합: LinkedIn, 언론, 인터뷰, 공개 서류


## 연관 스킬

- **[research-frame](https://github.com/jasonnamii/research-frame)** — 더 깊은 가설 기반 분석으로 확장
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — 파트너, 투자, 채용에 대한 전략적 의사결정 정보 제공

## 설치

```bash
git clone https://github.com/jasonnamii/person-profiler.git ~/.claude/skills/person-profiler
```

## 업데이트

```bash
cd ~/.claude/skills/person-profiler && git pull
```

`~/.claude/skills/`에 배치된 스킬은 Claude Code 및 Cowork 세션에서 자동으로 사용할 수 있습니다.

## Cowork 스킬 생태계

25개 이상의 커스텀 스킬 중 하나입니다. 전체 카탈로그: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## 라이선스

MIT 라이선스 — 자유롭게 사용, 수정, 공유하세요.
