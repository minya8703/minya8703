# 경력 기술서 웹 페이지

이 프로젝트는 PDF 경력서를 웹 페이지로 변환한 것입니다.

## 파일 구조

- `index.html` - 메인 HTML 파일 (수정 가능)
- `style.css` - 스타일시트
- `profile.jpg` - 프로필 이미지 (직접 추가 필요)

## 사용 방법

### 1. 프로필 이미지 추가
- 프로필 이미지를 `profile.jpg`로 저장하거나
- HTML 파일의 `<img src="profile.jpg">` 부분에서 이미지 경로를 수정하세요.

### 2. 내용 수정하기
`index.html` 파일을 열어서 각 섹션의 주석을 참고하여 수정하세요.

#### 주요 수정 가능 항목:
- **헤더 섹션**: 이름, 직책, 연락처, 온라인 프로필
- **Professional Summary**: 전문 요약 내용
- **Work Experience**: 경력 사항 (회사명, 기간, 직책, 업무 내용, 기술 스택)
- **Core Competencies**: 핵심 역량
- **Tech Stack**: 기술 스택
- **Education**: 학력
- **Languages**: 언어 능력
- **Development Philosophy**: 개발 철학

### 3. 새로운 항목 추가하기

#### 경력 추가:
```html
<div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
        <h3 class="company-name">회사명</h3>
        <p class="date-range">2024.01 ~ 재직중</p>
        <p class="position">직책</p>
        <ul>
            <li>업무 내용 1</li>
            <li>업무 내용 2</li>
        </ul>
        <p class="tech-used">기술 스택</p>
    </div>
</div>
```

#### 기술 스택 카테고리 추가:
```html
<div class="tech-category">
    <h3>카테고리명</h3>
    <ul>
        <li>기술1</li>
        <li>기술2</li>
    </ul>
</div>
```

#### 역량 항목 추가:
```html
<div class="competency-item">
    <h3>역량 카테고리명</h3>
    <ul>
        <li>역량 내용 1</li>
        <li>역량 내용 2</li>
    </ul>
</div>
```

### 4. 확인하기
- `index.html` 파일을 브라우저에서 열어 확인하세요.
- 수정 사항은 저장 후 브라우저를 새로고침하면 반영됩니다.

## 스타일 특징

- 오렌지 색상 (#FF6B35)의 섹션 제목
- 타임라인 스타일의 경력 및 학력 섹션
- 회색 박스로 강조된 Contact/Online 정보
- 반응형 디자인 지원

## 수정 팁

1. **HTML 파일의 주석 확인**: 각 섹션에 "수정", "추가" 주석이 있어 쉽게 찾을 수 있습니다.
2. **구조 유지**: HTML 태그 구조를 유지하면서 내용만 수정하세요.
3. **스타일 변경**: `style.css` 파일을 수정하여 색상, 폰트, 레이아웃을 변경할 수 있습니다.

## GitHub Pages 배포

GitHub에 업로드한 후 Settings > Pages에서 main 브랜치를 선택하면 웹 페이지로 접근할 수 있습니다.

