# unity_book_code_chapter2
> "가장 쉬운 유니티 게임 제작 2판"의 Chapter2 내용을 실습한 코드입니다.\
> 

## 목표 : 공 굴리기

- Project view에서 2D sprite를 생성함.
  - Square
  - Circle
 
- Hierarchy view에서 Game Object를 생성함.
  - Square sprite를 Floor라는 이름으로 생성함.
    - 바닥 역할을 할 수 있도록 Inspector view에서 Box Collider 2D를 추가함.
  - Circle sprite를 Ball이라는 이름으로 생성함.
    - 바닥과 충돌을 하도록 Inspector view에서 Circle Collider 2D를 추가함.
    - 아래로 떨어지게 하기 위해 Inspector view에서 Rigidbody 2D를 추가함.
   
- Floor을 여러개 만들어 적절하게 배치해 떨어지는 공과 부딪히게 만듦.
- Ball의 크기와 위치를 적절하게 설정해 Floor와 부딪히다 제일 아래 박스에 들어갈 수 있도록 만듦.
   
- Play 버튼을 통해 실제 공이 움직어 아래 박스에 들어가는 것을 확인함.
