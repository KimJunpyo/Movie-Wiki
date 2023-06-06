<div align="center" >
  
# Namu-Movie
</div>

### 개요
TMDB API 기반 영화 추천/검색 웹 서비스로 사용자에게 쉽고 빠르게 원하는 영화에 대한 상세정보를 제공함으로써 편의성을 극대화 시킬 수 있는 서비스입니다.
- 인기 영화/검색/장르별 영화 검색 기능 등의 다양한 검색 방법을 통해 사용자에게 편의성을 제공합니다.

### 서비스 링크 : 

### 기술 스택
<table>
  <tr>
    <td><strong>스택</strong></td>
    <td>JS</td>
    <td>REACT</td>
    <td>tailwindCSS</td>
    <td>styled-components</td>
  </tr>
  <tr>
    <td></td>
    <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/JavaScript-logo.png/800px-JavaScript-logo.png" width="180" height="180"/></td>
    <td><img src="https://blog.kakaocdn.net/dn/doBY5S/btrlEmJSNSs/qmgj8lzzHRkt2b0WX5nSN1/img.png" width="180" height="180"/></td>
    <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Tailwind_CSS_Logo.svg/2048px-Tailwind_CSS_Logo.svg.png" width="180" height="180"/></td>
    <td><img src="https://i.ibb.co/ydkG6cv/img.png" width="180" height="180"/></td>
  </tr>
  <tr>
    <td><strong>라이브러리</strong></td>
    <td>RTK</td>
    <td>react-star-ratings</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td><img src="https://img.uxwing.com/wp-content/themes/uxwing/download/brands-social-media/redux-icon.svg" width="180" height="180"/></td>
    <td><img src="https://raw.githubusercontent.com/ami1906/react-star-rating-lite/develop/public/filled.png" width="180"/></td>
    <td></td>
    <td></td>
  </tr>
</table>


### 개발 환경 세팅
```bash
npm install
npm start
```


## 팀원
- 공동 기획 후 1팀과 2팀으로 나뉘어 개발 진행
- 1팀 깃허브 링크 : https://github.com/FE-Sprint-Study/Namu-Movie

| 1팀 |  |  | 2팀 |  |  |
| --- | --- | --- | --- | --- | --- |
| [김민재](https://github.com/crowcrow07) | [김영웅](https://github.com/novice-hero) | [황찬우](https://github.com/HChanWoo) | [김준표](https://github.com/KimJunpyo) | [김태우](https://github.com/TaeWooKim-SCH/) | [류지수](https://github.com/R-jisu) | 


## 기능 목록

### 무비 카드
- 무비카드에 Hover 시 줄거리를 보여줍니다.

### 영화 상세보기
![무비모달](https://github.com/FE-Sprint-Study/Movie-Wiki/assets/100808381/6dfb08ab-7a98-464c-a06b-eb301d1475f3)
- 무비 카드를 눌렀을 때, 영화에 대한 상세 정보 모달을 보여줍니다.
- 모달 외부를 누르거나 닫기 버튼을 눌렀을 때, 종료됩니다.

### 무한스크롤
![무한스크롤1](https://github.com/FE-Sprint-Study/Movie-Wiki/assets/100808381/b41aee1f-a613-47bd-abff-53e930541975)
- 00개씩 가져오기/스크롤이 끝에 다다를 경우 00개를 더 가져와서 화면에 보여줍니다.
- 더 이상 불러올 데이터가 없을때 데이터가 없음을 보여줍니다.

### 캐러셀(메인 페이지)
![캐러셀](https://github.com/FE-Sprint-Study/Movie-Wiki/assets/100808381/ffd460e8-0232-4944-8c18-4c28b9bc23ed)
- 자동으로 특정 주기마다 다음 콘텐츠를 보여줍니다.

### 마우스 드래그 (메인 페이지)
![마우스 드래그](https://github.com/FE-Sprint-Study/Movie-Wiki/assets/100808381/5789f95c-402d-4025-843f-488571693233)
- 주제별 무비카드를 10개까지 보여줍니다.
- 특정 영역에서 마우스 드래그 시 구간을 이동할 수 있습니다.

### 영화 검색
![검색](https://github.com/FE-Sprint-Study/Movie-Wiki/assets/100808381/35bf8941-e675-4b44-98a3-917322b1d10b)
- 검색한 키워드가 포함된 영화를 보여줍니다.
- 검색한 키워드와 비슷한 추천 영화들을 무한스크롤로 보여줍니다.

### 카테고리 검색
![카테고리](https://github.com/FE-Sprint-Study/Movie-Wiki/assets/100808381/ab79b391-7862-4290-9093-a30ededf25d4)
- 카테고리(장르)별 영화를 보여줍니다.
- 장르에 포함되는 영화가 없다면 영화를 찾을수 없다는 메세지를 보여줍니다.

## 회고
- 김준표 :
- 김태우 : https://github.com/TaeWooKim-SCH/Movie-Wiki
- 류지수 : 
