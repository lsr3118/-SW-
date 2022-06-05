# 오픈소스SW개론 과제
###### 컴퓨터공학과 20223118 이사랑
---

### 리눅스 명령어에서
> 리눅스에서 활용 가능한 명령어 top, ps, hobs, kill에 대하여 알아보자.


- top

> ` top: 시스템 프로세스/메모리 사용 현황을 실시간으로 출력하는 명령어 `
> > top의 출력 정보

|항목|의미|항목|의미|
|---|---|---|---|
|PID|프로세스 ID|SHR|프로세스가 사용하는 공유 메모리 크기|
|USER|사용자 계정|%CPU|CPU 사용량|
|PR|우선순위|%MEM|메모리 사용량(%)|
|NI|NICE 값|TIME+|CPU 누적 이용 시간|
|VIRT|프로세스가 사용하는 가상 메모리 크기|COMMAND|명령이름|
|RES|프로세스가 사용하는 메모리 크기|  |  |

![top 명령어](https://user-images.githubusercontent.com/106869854/172036782-1a9efe32-b21f-4fe8-9821-a776ac62ac86.png)

- ps
 
> ` ps: 현재 실행중인 프로세스의 목록을 출력하는 리눅스 명령어 `

![ps 명령어](https://user-images.githubusercontent.com/106869854/172036823-dc6dd2ff-0eb6-48f1-b7ba-386324c68b02.png)

- jobs

> ` jobs: 작업이 중지된 상태나 백그라운드로 진행 중인 상태를 표시하는 명령어 `

![job 명령어](https://user-images.githubusercontent.com/106869854/172036576-617617c3-ddbe-42a8-8c25-3989e8e2831d.png)


- kill

> ` kill : 프로세스에 종료 시그널을 보내는 명령어 `
>> **기능**
>> 
>> 지정한 시그널을 프로세스에 보낸다
>> 
>> **형식**
>> 
>> ` kill [시그널] PID... `
>> 
>> **시그널**
>>
>>              -2: 인터립트 시그널을 보낸다(Ctrl+C)
>>              -9: 프로세스를 강제로 종료시킨다.
>>              -15: 프로세스가 관련된 파일을 정리하고 프로세스를 종료한다. 종료되지 않는 프로세스가 있을 수 있다.

![kill 명령어](https://user-images.githubusercontent.com/106869854/172036828-343b5aec-6cec-4c6e-94df-1daeee59b6ee.png)

---

### vim 에디터에서
-매크로 사용방법 (q)
