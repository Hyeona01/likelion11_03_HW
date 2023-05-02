###### likelion11_03_HW
# 3주차 인스타그램 레이아웃 과제 - CSS

 ### display : flex

> * container 요소
> 1. justify-content : 주축을 기준으로 item 배치
> 2. align-items : 주축의 수직축을 기준으로 item 배치
> 3. align-content : wrap 상태에서 행이 2줄 이상이 되었을 때, 수직축을 기준으로 item 배치
> 4. flex-wrap
> : no-wrap - 아이템이 한 줄을 초과했을 때, 무시하고 이어붙임
> : wrap - 아이템이 한 줄을 초과했을 때, 다음 줄로 줄바꿈

> * item 요소
>1. flex-basis : 기본 크기 설정(row-너비 / column-높이)
>2. flex-grow : 기본 크기보다 크게 크기 조정
>3. flex-shrink : 기본 크기보다 작게 크기 조정

### flex 에서 여러 아이템 중 일부만 좌,우,가운데 정렬을 하려할 때?
> 일부만 지정한 셀렉터로 정렬하고자 하는 방향으로 아래 값을 준다.
>   margin: auto;
>   margin-left: auto;
>   margin-right: auto;
> 여백을 활용하여 정렬하는 방법이다.