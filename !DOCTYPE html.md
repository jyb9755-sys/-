<!DOCTYPE html>

<html lang="ko">

<head>

&nbsp;   <meta charset="UTF-8">

&nbsp;   <meta name="viewport" content="width=device-width, initial-scale=1.0">

&nbsp;   <title>의정부 성모병원 응급실 챗봇</title>



&nbsp;   <style>

&nbsp;     df-messenger {

&nbsp;       /\* 헤더: 의정부 성모병원 느낌의 신뢰감 있는 청록색 \*/

&nbsp;       --df-messenger-header-background-color: #009688; 

&nbsp;       --df-messenger-header-font-color: #FFFFFF;



&nbsp;       /\* 말풍선 \*/

&nbsp;       --df-messenger-bot-message: #E0F2F1;     /\* 챗봇: 아주 연한 청록색 \*/

&nbsp;       --df-messenger-user-message: #FFFFFF;    /\* 보호자: 흰색 \*/

&nbsp;       

&nbsp;       /\* 전체 배경 \*/

&nbsp;       --df-messenger-chat-background-color: #FAFAFA;



&nbsp;       /\* 버튼 색상 \*/

&nbsp;       --df-messenger-button-title-color: #FFFFFF;

&nbsp;       --df-messenger-button-background-color: #009688;



&nbsp;       /\* 둥근 모서리와 그림자 효과 \*/

&nbsp;       border-radius: 10px;

&nbsp;       box-shadow: 0 5px 15px rgba(0,0,0,0.1);

&nbsp;     }

&nbsp;   </style>



</head>

<body>



&nbsp;   <script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>

&nbsp;   <df-messenger

&nbsp;     intent="WELCOME"

&nbsp;     chat-title="의정부 성모병원 응급실 FAQ"

&nbsp;     agent-id="73318352-be62-45c4-9fd3-124ab1b3c83b"

&nbsp;     language-code="ko"

&nbsp;   ></df-messenger>



</body>

</html>

