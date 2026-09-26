## OSS Assignment04 22200635 장영진

## Key Learning: 이번 주 배운 핵심 내용 3가지
HTML Form으로 입력 요소들을 사용하는 방법을 배움.
여러가지 Form Elemets들을 이용하면서 그들의 종류에 대해 많이 알게됨.
Validation과 JavaScript로 사용자의 submit을 검사하는 방법을 배움.

## Form Elements: 사용한 Form 요소와 용도
text(이름, 유저이름, 카드정보), email(이메일), date(생일), checkbox(개인정보 수집 동의), radio(결제 방법), select(국가 선택), textarea(가입 이유), button(form 제출)
## HTML vs CSS: form1.html과 form1_css.html의 차이
form1.html은 웹에 필요한 구조와 입력 요소를 만들었다.(구조와 내용)
form1_css.html은 Form의 크기와 위치, 배경, 폰트 크기나 여백 등을 꾸몄다.(디자인)

## Validation & JS: 적용한 Validation 조건과 JavaScript 처리 과정
required, email형식 검사, minlength로 유저 이름의 최소 길이 설정
submit 이벤트를 addEventListener()로 처리.
checkValidity()로 조건에 맞는지 확인, 아닌경우 event.preventDefault()로 제출을 막음. alert로 안내 메시지를 주고 focus()로 해당 입력창으로 이동. 조건이 만족되면 완료 메시지 출력

## Problem & Solution: 문제와 해결 과정
이메일 형식을 확인하는 과정에서 input type이 text로 되어 있어서 이메일 형식을 확인할 수 없었다. 
text =>> email로 바꿔서 해결했다.

## Reflection: 새롭게 알게 된 점 또는 궁금한 점
이번 과제를 통해 HTML Form의 다양한 입력 요소와 JavaScript를 활용하여 이벤트를 처리하는 법에 대해 알게 되었습니다.