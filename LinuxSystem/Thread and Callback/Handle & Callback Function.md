
# Handle & Callback Function
-----------------------------------------------


- ## Handle
	- 특정 서비스를 위한 루틴의 주소에 부여된 번호가 핸들
	- 리소스 주소와 핸들의 쌍으로 이루어진것이 핸들테이블임
		+ ex) ISR 테이블 , 이벤트 서비스 루틴테이블
	- 리소스 주소로 직접 접근하는것이 아니고 핸들번호로 간접접근되어 서비스 되는 방식
	- 핸들러(handler) : 핸들에 의해서 실행되는 서비스 루틴

	
- ## Callback Function
	- 이벤트가 발생될 때 실행되도록 매개변수와 함께 시스템에 등록시키는 함수를 콜백함수라고함
	- 함수를 파라미터 변수로 전달하여 실행되는 경우의 함수도 콜백함수라고도 함
	- 특정 이벤트가 발생하면 시스템은 등록된 매개변수를 이용하여 콜백함수를 실행
	- 비동기식으로 실행되고
	- 콜백함수를 전달할때는 콜백함수의 포인터(핸들)를 넘겨줌

	<br/>


	<br/><br/><br/>