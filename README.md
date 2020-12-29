# nodejs-rabbitMq
- tutorial ( https://www.rabbitmq.com/tutorials/tutorial-one-javascript.html )

#### [ 설치 ( window, ubuntu, docker ) ]
 - window 에서 rabbit mq 설치 (참고 - https://heodolf.tistory.com/50)
 
#### [ rabbitMq Server 실행 ]
 - rabbitmq-server  (rabbitmq 서버는 default로 5672 port 사용, gui 페이지는 15672 port 사용)

#### [ gui 페이지 접속 방법 ]
 - rabbitmq 서버 띄운 뒤, localhost:15672 접속
 - 초기 계정 guest/guest

#### [ 코드 설명 ]
 - rabbitMq_sender.js : "hello"라는 queue에 "hello world"라는 메시지 send ( gui 페이지에서 확인 가능 )
 - rabbitMq_receiver.js : "hello"라는 queue에서 msg를 뺀다. -> "hello world" 출력
