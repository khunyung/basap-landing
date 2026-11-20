# BÁSAP 글라이신 리볼륨 샴푸 랜딩페이지

와디즈 상세페이지(v2)를 바탕으로 만든 반응형 정적 랜딩페이지입니다. 빌드 과정이 없습니다.

## 구조

```
index.html        페이지 본문 (CSS·JS 포함)
assets/img/       제품·모델 사진, GIF, 로고
assets/fonts/     Pretendard 400/500/700/800, BASAP Serif
```

## 로컬 미리보기

```
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000` 열기

## 배포 (GitHub + Vercel)

1. 이 폴더를 GitHub 저장소 루트에 push
2. Vercel > Add New Project > 저장소 Import
3. Framework Preset: `Other`, Build Command·Output Directory는 비워 두고 Deploy

## 참고

- 인체적용시험, 체험단 후기, 원료사 자료, FAQ 일부 수치는 시안용 예시 데이터입니다.
- "지금 펀딩하기" 등 버튼은 페이지 안의 리워드 섹션(`#reward`)으로 이동합니다. 실제 와디즈 링크가 생기면 `href`를 교체하세요.
