# 챕터 1

## 컴퓨터 구조를 알아야 하는 이유

- **성능 용량 비용** 문제
	- 코드가 처리해야 할 데이터가 방대해질수록 컴퓨터의 성능은 높아져야 하지만 컴퓨터의 사양을 늘리는 데에는 **한계**가 있음.
	- '개적화' 문제와도 연관

=> 무작정 하드웨어를 업그레이드 하기보단 코드의 최적화를 도모하는 프로그래머가 될 수 있다.

## 컴퓨터 구조의 큰 그림

- 정보
	- Data: 정적인 정보 (ex. 이미지, 동영상, 소리 등)
	- Command: 데이터를 움직이고 컴퓨터를 작동시키는 정보

- 하드웨어
	- CPU: 메모리에 로드된 명령어를 처리하는 장치. 내부에 ALU, Register 등이 있음.
		- ALU: Arithmetic Logic Unit, **산술 논리 연산 장치**... 결론은 "계산기"임
		- Register: CPU 내부의 작은 임시 저장 장치.
		- CU: Control Unit, **제어 장치**... 장치들을 관리하고 작동시키기 위한 전기 신호를 관리하는 장치.
	- M/B: 모든 부품을 연결하는 장치. **Bus**가 존재함.
		- Bus란? (Thanks to this [Blog](https://richong.tistory.com/92))
			- 각 장치들간의 통신이 가능하게 해 주는 데이터 전송용 통로같은 공간
			- System bus:
				- Address, Data, Control
![System bus diagram](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.net%2Fcfile%2Ftistory%2F2430644657A86C3001)
	- Memory: 현재 실행되는 프로그램의 명령어와 데이터를 저장하는 장치. 메인보드의 System bus와 연결되어 있음.
		- 프로그램이 실행되기 위해서는 **반드시** 메모리에 올라가 있어야 함
		- 메모리는 현재 실행되는 프로그램의 명령어와 데이터를 저장한다.
		- 메모리의 저장된 값의 위치는 **주소**로 알 수 있다.
	- Storage: 보조기억장치. 전원이 꺼지더라도 휘발되지 않고(비휘발성, [NVM](https://ko.wikipedia.org/wiki/%EB%B9%84%ED%9C%98%EB%B0%9C%EC%84%B1_%EB%A9%94%EB%AA%A8%EB%A6%AC)이라고 불림) RAM 대비 낮은 가격이라는 특성 때문에 전원이 꺼져도 보관될 데이터/프로그램을 저장하는 부품임.
	- I/O Device: 입출력장치 일체. **KVM**(Keyboard, Video Moniter, Mouse)가 대표적임.

