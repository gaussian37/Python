[가상환경 설정하기](https://tutorial.djangogirls.org/ko/installation/)

- 가상 환경 설정 목적 : 독립된 개발 환경을 구축하여 신/구 버전의 각각의 환경 설정 가능함.

1. virtualenv를 설치합니다. <br>
	**pip install virtualenv** <br>

2. 가상 환경을 만들 디렉토리를 설정 합니다.<br>
(ex. D:\Code\myvenv)

3. command에 다음과 같이 입력합니다. myvenv에 사용할 가상환경 이름을 입력하면 됩니다.<br>
    **python -m venv myvenv** <br>
   앞의 명령을 사용하면 myvenv라는 디렉토리가 만들어집니다. 그리고 그 디렉토리에 우리가 사용할 가상환경이 들어있습니다. 

4. command에 다음과 같이 입력하면 가상 환경이 실행 됩니다. myvenv에 실제 가상환경 이름을 입력하면 됩니다. <br>
    **myvenv\Scripts\activate**<br>

이 때, 각 command 창의 각 line에 접두어로 (myvenv)가 붙으면 됩니다.

5. pip 버전을 최신으로 업데이트 합니다. <br>
	**python -m pip install --upgrade pip**

6. 새로 만들어진 가상 환경에서 필요한 library를 최신 pip를 이용하여 설치 후 사용합니다.
