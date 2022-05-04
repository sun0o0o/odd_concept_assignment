# odd_concept_assignment

배포 링크


### 과제 1
- **PXL로고 클릭시 첫 페이지**로 돌아옵니다<br>

- **url에 검색 쿼리에 사용한 데이터가 직관적**으로 보입니다<br>

- **반응형** 구현 <br>
media query를 이용해 500px을 기준으로 모바일버전, pc버전 사이즈 제작
- 데이터가 로딩 중인경우, **로딩중**임을 알립니다
- **페이지네이션** 도입
- 검색 방법 <br>
1. keyword 검색 <br>
2. 이미지 url 검색 / product_code 검색 <br>
- **데이터 캐싱**
- **오류가 발생**할 경우 **사용자에게 인지**시키기

### 과제 2
- **이미지 특정 영역을 드래그해 선택한 영역의 이름 붙이기**
- 지정한 **영역 수정** (삭제, 이름 변경, 위치 이동, 크기 변경)
- **페이지 reload시에도 지정한 영역 유지**<br>
 localStorage에 저장

### 어려웠던 점 (과제 1)
- 페이지네이션 구현 시 1 페이지에 10개의 상품이 보이도록 제작했는데, 모니터 화면에 따라서 10개가 보이는게 안정적인 경우도 있고 아닌 경우가 있다. flex로 페이지를 만들어서 그런 것같다.<br>
- 상품 이미지의 크기가 다 달라서 같은 사이즈로 고정을하면 사진이 늘어나는 경우가 있어서 원본크기로 맞췄는데,그럼 이미지를 감싸는 wrapper와 크기가 딱 맞아 떨어지지 않아서 빈 공간이 생기는 경우가 있다<br>
### 어려웠던 점 (과제 2)
- canvas의 사용
