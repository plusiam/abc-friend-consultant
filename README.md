# ABC 친구상담소

ABC 사고 모델을 활용한 교육용 친구 상담 역할놀이 도구입니다.

## 🎯 프로젝트 소개

이 프로젝트는 학생들의 공감 능력과 문제 해결 능력을 기르기 위한 교육 도구입니다.
ABC 사고 모델(상황-생각-감정)을 활용하여 친구 관계의 어려움을 해결하는 방법을 학습합니다.

## 📚 구성 요소

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

1. 웹사이트 접속: https://plusiam.github.io/abc-friend-consultant/
2. 원하는 활동 선택:
   - 2인 역할극: index.html (메인 페이지)
   - 3인 역할놀이: roleplay.html로 이동

## 💡 활용 팁

- 초등 고학년 ~ 중학생 대상
- 소요 시간: 약 25분
- 학급 상담 활동, 또래 상담 프로그램에 활용

## 🔗 페이지 연결하기

index.html에서 roleplay.html로 가는 링크를 추가하려면:

```html
<!-- 자동 저장 상태 표시 위에 추가 -->
<div class="flex justify-center gap-4 mb-4">
    <a href="roleplay.html" class="bg-purple-500 hover:bg-purple-600 text-white font-bold px-6 py-2 rounded-lg transition-colors inline-flex items-center gap-2">
        🤝 3인 역할놀이 가이드
    </a>
</div>
```

## 📝 라이선스

교육 목적으로 자유롭게 사용 가능합니다.