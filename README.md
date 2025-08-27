# CALL

## 개요

본 저장소는 **"CALL(Community Alignment through Large Language models)"** 논문의 공식 저장소입니다. CALL은 대규모 언어 모델(LLM)을 활용하여 온라인 커뮤니티의 정치적 특성을 자동으로 파악하고, 이를 기반으로 커뮤니티별 맞춤형 에이전트를 생성 및 평가하는 프레임워크입니다.

![Image](https://github.com/user-attachments/assets/1ba849eb-d639-45dd-8ee0-6a4188175578)

## 데이터셋

### 대상 커뮤니티
- **보수 성향** (2개): 에펨코리아, MLBPARK
- **진보 성향** (1개): 뽐뿌

### 설문 데이터
- **파일명**: `call_experiment_survey.csv`
- **주제**: 2022년 제 20대 한국 대통령 선거 7대 핵심 쟁점
- **형식**: 87개 4지선다형 객관식 문항
- **생성 모델**: Gemini-1.5-pro