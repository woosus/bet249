# 겜블 100% 즐기기 — GitHub Pages 자동배포 스타터

## 빠른 사용법
1) 새 GitHub 리포지토리 생성 (공개/Public 권장).  
2) 이 폴더의 모든 파일을 업로드 후 `main` 브랜치에 커밋.  
3) 리포 **Settings → Pages → Source: GitHub Actions**로 설정.  
4) 푸시하면 액션이 돌아가며 자동 배포됩니다.  
   - 배포 URL 예시: `https://<아이디>.github.io/<리포이름>`

## 구성
- `index.html` — Tailwind CDN 기반 랜딩 템플릿 (히어로/글래스 카드/CTA)
- `assets/images/` — 로고/슬라이더/레이아웃 이미지
- `assets/js/main.js` — 확장용 JS
- `.github/workflows/pages.yml` — GitHub Pages 자동배포 워크플로우

## 커스텀
- 섹션/카드/색상/폰트 등 알티가 추후 요구사항에 맞게 업데이트합니다.
- CP10/City156 쿠폰 폼, 파트너 로고 스테이지, 좌측 사이드바 필터 등 순차 반영 예정.
