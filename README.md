# ABC 친구상담소

ABC 사고 모델을 활용한 교육용 친구 상담 역할놀이 도구입니다.

## 🎯 프로젝트 소개

이 프로젝트는 학생들의 공감 능력과 문제 해결 능력을 기르기 위한 교육 도구입니다.
ABC 사고 모델(상황-생각-감정)을 활용하여 친구 관계의 어려움을 해결하는 방법을 학습합니다.

## 📚 구성 요소

### 🆕 simple-abc-helper.html - 간단한 학생 주도형 친구 도움
- **새로 추가!** 3단계 간편 프로세스
- A(상황), B(부정적 생각)을 미리 제시
- 1단계: 친구의 감정(C) 읽어주기
- 2단계: 새로운 생각과 구체적 도움 제안
- 3단계: 따뜻한 격려 메시지
- 학생들이 쉽게 따라할 수 있는 직관적 UI

### 1. index.html - ABC 통합 컨설팅 도구
- 2인 역할극 (컨설턴트 & 내담자)
- 4단계 컨설팅 프로세스
- 자동 저장 기능
- 결과 저장 및 인쇄 기능

### 2. roleplay.html - 3인 역할놀이 가이드
- 3명이 한 조 (내담자, 상담가, 기록자)
- 5단계 ABC 상담 프로세스
- 역할별 상세 가이드

### 3. roleplay-guide.html - 인쇄용 역할놀이 가이드
- A4 인쇄 최적화
- 역할별 상세 설명
- 진행 순서 안내

## 🚀 사용 방법

### 🌟 추천: 간단한 친구 도움 (새로 추가!)
1. 웹사이트 접속: https://plusiam.github.io/abc-friend-consultant/simple-abc-helper.html
2. 도움 주는 친구와 받는 친구 정보 입력
3. 8가지 고민 상황 중 선택
4. 3단계로 친구 도움 완료!

### 기존 버전들
1. 웹사이트 접속: https://plusiam.github.io/abc-friend-consultant/
2. 원하는 활동 선택:
   - 2인 역할극: index.html (메인 페이지)
   - 3인 역할놀이: roleplay.html로 이동

## 💡 활용 팁

### 간단한 친구 도움 (simple-abc-helper.html)
- **대상**: 초등 고학년 ~ 중학생
- **소요 시간**: 약 15분
- **특징**: 학생 주도적, 간편한 3단계
- **활용**: 또래 상담, 학급 활동, 자유학기제

### 기존 통합 버전 (index.html)
- **대상**: 초등 고학년 ~ 중학생  
- **소요 시간**: 약 25분
- **특징**: 체계적인 4단계 컨설팅
- **활용**: 학급 상담 활동, 또래 상담 프로그램

## 🔗 페이지 연결하기

index.html에서 simple-abc-helper.html로 가는 링크를 추가하려면:

```html
<!-- 자동 저장 상태 표시 위에 추가 -->
<div class="flex justify-center gap-4 mb-4">
    <a href="simple-abc-helper.html" class="bg-green-500 hover:bg-green-600 text-white font-bold px-6 py-2 rounded-lg transition-colors inline-flex items-center gap-2">
        🤝 간단한 친구 도움
    </a>
    <a href="roleplay.html" class="bg-purple-500 hover:bg-purple-600 text-white font-bold px-6 py-2 rounded-lg transition-colors inline-flex items-center gap-2">
        🤝 3인 역할놀이 가이드
    </a>
</div>
```

## 🆚 버전 비교

| 구분 | 간단한 친구 도움 | 기존 통합 버전 |
|------|------------------|----------------|
| 단계 수 | **3단계** | 4단계 |
| 소요 시간 | **15분** | 25분 |
| 복잡도 | **간단함** | 체계적 |
| A,B 제시 | **미리 제시** | 학생이 분석 |
| 대상 | **또래 상담 초급** | 또래 상담 심화 |
| 학습 목표 | 공감·격려 중심 | ABC 이론 학습 |

## 📝 라이선스

교육 목적으로 자유롭게 사용 가능합니다.