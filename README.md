# Week 1: 자기소개 웹페이지 만들기 🌟

## 🎯 이번 주 목표
여러분의 첫 웹페이지를 만들고 인터넷에 공개해봅시다!

## 📚 배울 내용
- **HTML**: 웹페이지의 뼈대 만들기
- **CSS**: 예쁘게 꾸미기
- **GitHub Pages**: 인터넷에 공개하기

## 🚀 시작하기

### Step 1: 난이도 선택하기

#### 🟢 처음이세요? (대부분의 학생)
```
📁 사용할 파일:
- index-simple.html (이름 바꾸기 → index.html)
- style-simple.css (이름 바꾸기 → style.css)
```

#### 🟡 조금 해보셨나요?
```
📁 사용할 파일:
- example-with-js.html (이름 바꾸기 → index.html)
- style-simple.css (이름 바꾸기 → style.css)
```

#### 🔴 경험이 있으신가요?
```
📁 사용할 파일:
- index.html (그대로 사용)
- style.css (그대로 사용)
- script.js (그대로 사용)
```

### Step 2: 파일 열기
1. VS Code 실행
2. `week01-personal-website` 폴더 열기
3. 선택한 HTML 파일 열기

### Step 3: 내용 수정하기

#### 필수 수정 사항 ✏️
```html
<!-- 이름 바꾸기 -->
<h1>홍길동의 홈페이지</h1>  → <h1>김철수의 홈페이지</h1>

<!-- 자기소개 수정 -->
<p>안녕하세요! 저는 홍길동입니다.</p> → <p>안녕하세요! 저는 김철수입니다.</p>

<!-- 학과 정보 -->
<p>경영학과 3학년</p> → <p>컴퓨터공학과 2학년</p>
```

#### 색상 바꾸기 🎨
```css
/* style.css 또는 style-simple.css 파일에서 */

/* 초록색 → 파란색으로 바꾸기 */
background-color: #4CAF50;  → background-color: #2196F3;

/* 또는 색상 이름 사용 */
background-color: green;  → background-color: blue;
```

### Step 4: 브라우저에서 확인
1. 파일 탐색기에서 HTML 파일 더블클릭
2. 또는 VS Code에서 우클릭 → "Open with Live Server"

## 🌐 GitHub Pages로 배포하기

### 1. GitHub 계정 만들기
- [github.com](https://github.com) 접속
- Sign up 클릭
- 이메일 인증

### 2. 새 저장소(Repository) 만들기
- 우측 상단 `+` 버튼 → "New repository"
- Repository name: `my-portfolio` (원하는 이름)
- Public 선택
- "Create repository" 클릭

### 3. 파일 업로드
- "uploading an existing file" 클릭
- 만든 HTML, CSS 파일 드래그 앤 드롭
- "Commit changes" 클릭

### 4. GitHub Pages 설정
- Settings 탭 클릭
- 왼쪽 메뉴에서 "Pages" 클릭
- Source: "Deploy from a branch" 선택
- Branch: "main" 선택
- Save 클릭

### 5. 완성! 🎉
- 5분 정도 기다리기
- `https://[여러분ID].github.io/[저장소이름]` 접속
- 예: `https://kimcheolsu.github.io/my-portfolio`

## 📝 제출 방법

다음 내용을 복사해서 제출하세요:
```
이름: 김철수
주차: Week 1
GitHub 링크: https://github.com/kimcheolsu/my-portfolio
배포 링크: https://kimcheolsu.github.io/my-portfolio
```

## ❓ 자주 묻는 질문

### "한글이 깨져요!"
HTML 파일 상단에 이것이 있는지 확인:
```html
<meta charset="UTF-8">
```

### "CSS가 적용이 안돼요!"
HTML 파일에 이것이 있는지 확인:
```html
<link rel="stylesheet" href="style.css">
```
⚠️ 파일 이름이 정확한지 확인! (style.css vs style-simple.css)

### "이미지가 안 보여요!"
임시 이미지 사용하기:
```html
<img src="https://via.placeholder.com/200" alt="프로필">
```

## 💡 도전 과제 (선택)

시간이 남는다면 도전해보세요:

### 쉬움
- [ ] 배경색 바꾸기
- [ ] 글자 크기 바꾸기
- [ ] 새로운 섹션 추가하기

### 보통
- [ ] 구글 폰트 적용하기
- [ ] 마우스 호버 효과 추가
- [ ] 이미지 둥글게 만들기

### 어려움
- [ ] 버튼 클릭 이벤트 추가
- [ ] 애니메이션 효과
- [ ] 반응형 디자인

## 🆘 도움이 필요하면

1. **옆 친구에게 물어보기**
2. **구글에 검색하기**: "HTML 이미지 넣기"
3. **AI 도구 활용**: 
   - ChatGPT: "HTML에서 링크 만드는 방법"
   - Claude: "CSS로 가운데 정렬하는 방법"

---

**💪 할 수 있습니다!** 완벽하지 않아도 괜찮아요. 일단 만들어보는 것이 중요합니다!