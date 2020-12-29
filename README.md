# nodejs-rabbitMq
- tutorial ( https://www.rabbitmq.com/tutorials/tutorial-one-javascript.html )

#### [ 설치 ( window, ubuntu, docker ) ]
 - window 에서 rabbit mq 설치 (참고 - https://heodolf.tistory.com/50)
 
#### [ rabbitMq Server 실행 ]
 - rabbitmq-server  (rabbitmq 서버는 default로 5672 port 사용, gui 페이지는 15672 port 사용)

#### [ gui 페이지 접속 방법 ]
 - rabbitmq 서버 띄운 뒤, localhost:15672 접속
 - 초기 계정 guest/guest

#### [RabbitMq tutorial ]
 - 위 공식 문서를 보면 다음 6가지 카테고리로 RabbitMq의 기능을 설명하고 있다.
 1. Hello World : 메시지 큐의 기본 구조인 Producer -> Message Queue -> Comsumer 구조를 설명하고 있다.
 2. Work queues : Consumer가 여러개 일 경우 RabbitMq는 default로 Round-Robin 방식의 로드벨런싱을 지원한다. ( comsumer 여러개 띄워놓고 producer에서 메시지를 보내보면 알 수 있다.) 또한, 특정 consumer로 트래픽이 몰리는 것을 방지하기 위한 기능도 제공한다.(channel.prefetch(1); 이렇게 설정하면 된다고 하는데 좀 더 봐야 할듯..)
 3. Publish/Subscribe :  RabbitMq에서 pub/sub 모델을 지원한다. 
 4. Routing 
 5. Topics
 6. RPC

