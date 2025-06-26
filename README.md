# Alan의 블로그

Apple 디자인에서 영감을 받은 깔끔하고 현대적인 개인 블로그입니다.

## 🌟 특징

- **Apple 스타일 디자인**: 깔끔하고 미니멀한 Apple 홈페이지 스타일
- **반응형 웹사이트**: 모든 디바이스에서 완벽하게 작동
- **부드러운 애니메이션**: 스크롤 애니메이션과 호버 효과
- **다크 모드**: 라이트/다크 테마 전환 기능
- **모바일 친화적**: 완전한 모바일 네비게이션
- **빠른 로딩**: 최적화된 성능과 이미지 지연 로딩
- **SEO 최적화**: 검색 엔진 최적화 적용

## 🚀 시작하기

### 1. 저장소 클론
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. 로컬에서 실행
브라우저에서 `index.html` 파일을 열거나 로컬 서버를 실행하세요:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (http-server 설치 필요)
npx http-server

# PHP
php -S localhost:8000
```

### 3. GitHub Pages 배포
1. GitHub 저장소 설정에서 Pages 섹션으로 이동
2. Source를 "Deploy from a branch"로 설정
3. Branch를 "main"으로 선택하고 "/ (root)" 폴더 선택
4. Save 버튼 클릭

## 📁 파일 구조

```
├── index.html          # 메인 HTML 파일
├── styles.css          # 스타일시트
├── script.js           # JavaScript 파일
├── _config.yml         # Jekyll 설정
└── README.md           # 프로젝트 설명
```

## 🎨 커스터마이징

### 색상 변경
`styles.css` 파일의 `:root` 섹션에서 CSS 변수를 수정하세요:

```css
:root {
    --primary-color: #1d1d1f;
    --secondary-color: #86868b;
    --accent-color: #0071e3;
    /* 기타 색상 변수들... */
}
```

### 콘텐츠 수정
- `index.html` 파일에서 개인 정보와 블로그 포스트를 수정하세요
- 이미지를 추가하려면 `images/` 폴더를 만들고 이미지를 업로드하세요
- 연락처 정보와 소셜 미디어 링크를 업데이트하세요

### 새 블로그 포스트 추가
블로그 카드 섹션에 새로운 `article` 요소를 추가하세요:

```html
<article class="blog-card">
    <div class="blog-image">
        <!-- 이미지 또는 플레이스홀더 -->
    </div>
    <div class="blog-content">
        <span class="blog-date">2024.12.20</span>
        <h3 class="blog-title">새 포스트 제목</h3>
        <p class="blog-excerpt">포스트 요약...</p>
        <a href="#" class="blog-link">더 읽기</a>
    </div>
</article>
```

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 현대적인 스타일링과 애니메이션
- **JavaScript (ES6+)**: 인터랙티브 기능
- **GitHub Pages**: 호스팅
- **Jekyll**: 정적 사이트 생성 (선택사항)

## 📱 반응형 브레이크포인트

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: 480px 이하

## 🎯 주요 기능

### 네비게이션
- 고정 헤더 with 블러 효과
- 모바일 햄버거 메뉴
- 부드러운 스크롤 앵커 링크

### 애니메이션
- 스크롤시 페이드인 효과
- 호버 애니메이션
- 로딩 스피너
- 패럴랙스 스크롤 효과

### 폼 기능
- 연락처 폼 검증
- 성공/오류 알림
- 이메일 유효성 검사

### 추가 기능
- 스크롤 진행도 표시
- 다크/라이트 테마 토글
- 키보드 단축키 (Konami Code)
- 이미지 지연 로딩

## 🌐 브라우저 지원

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 있습니다.

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 연락처

Alan - alan@example.com

프로젝트 링크: [https://github.com/your-username/your-repo-name](https://github.com/your-username/your-repo-name)

---

⭐ 이 프로젝트가 유용했다면 Star를 눌러주세요!
