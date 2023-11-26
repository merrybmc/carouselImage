# 제주코딩베이스캠프 파이널 코딩테스트 2번 문제 구현

## 💡 프로젝트 실행 방법
```
git clone https://github.com/merrybmc/carouselImage
npm install
npm start
```

## ⛏ 기술 스택
<div>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=black">
</div>
<p>
<img src="https://img.shields.io/badge/React-29FFE3?style=flat-square&logo=React&logoColor=white"/>
<img src="https://img.shields.io/badge/styled-component-DB7093?style=flat-square&logo=styled-components&logoColor=white"/>
<img src="https://img.shields.io/badge/Recoil-990099?style=flat-square&logo=recoil&logoColor=white"/>
</p>


## 📌 배포 링크
https://carousel-image-9ubronlz3-merrybmc.vercel.app/
<br />

## 📜 폴더 구조
```
📄 src
├── App.js
├── index.js
├── components
│   ├── CreateImg
│   │   ├── CreateImg.tsx
│   │   └── CreateImg.styled.js
│   ├── ImgList
│   │   ├── ImgList.tsx
│   │   └── ImgList.styled.js
│   ├── reverseImgList
│   │   ├── ReverseImgList.tsx
│   │   └── ReverseImgList.styeld.js
├── Global
│   └── global.css
├── hooks
│   ├── useCreateImage.ts
│   └── useMoveImage.ts
├── model
│   └── ImgList.ts
├── pages
│   └── Mainpage.tsx
├── store
│   └── store.ts
```

## 🚀 레이아웃 외 추가 기능 구현
- [x] 이미지 추가 기능
- [x] 이미지 좌우 슬라이드 이동
- [x] max-width: 1800px, 1120px 반응형 구현
<br />
