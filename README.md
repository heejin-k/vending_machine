# vending_machine

## 구현 환경

- 개발언어 :
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/></a> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=black"/></a>
- OS :
  <img src="https://img.shields.io/badge/Window-0078D6?style=flat-square&logo=Windows&logoColor=white"/></a>

## UI 구현

- pc 버전

![image](https://user-images.githubusercontent.com/54096506/163187729-eaaf3cc8-265e-42f1-b75e-2062bbdacb14.png)

- 모바일 버전

![image](https://user-images.githubusercontent.com/54096506/163193055-ed931d62-b49f-4af7-872e-cfe44fd78813.png)

## 기능 구현

- html & css

1. 마우스 hover시 효과 ( 테두리 변화 )
2. 반응형 웹 - 모바일버전 <br> 360px기준으로 모바일 버전으로 전환

- js (구현예정)

1. 잔액이 부족하면 음료를 클릭해도 반응하지 않는다.
2. 음료버튼 클릭하면 획득 옆의 리스트로 이동하며, 획득하게되면 획득한 음료 리스트에 추가된다.
3. 거스름돈 반환을 클릭하면 잔액이 소지금으로 이동한다.
4. 입금은 소지금 이상으로 입금할 수 없다.
5. 음료가 다 소진 될 경우 '매진'라벨이 표시되며 해당 음료는 뽑을 수 없다.

- 구현 시 주의 점

1. 판매할 음료에 대한 데이터는 따로 분리되어 있어야 한다. (혹은 API로 받는다)
2. 돈의 입금과 음료의 선택 시점은 자유롭지만 돈이 모자라면 음료가 나와서는 안된다.
3. 거스름돈이 나와야 한다.
4. 버튼을 누르면 상품이 1개씩 추가 (일반적인 자판기와 동일)

🔗 https://heejin-k.github.io/vending_machine/
