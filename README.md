thrift-example
==============

Twisted Server/Client, 일반 Python Server/Client, PHP Client 를 이용한 Thrift 구현 예제입니다.

실행하기 전에 Thrift python 라이브러리를 설치해야 합니다.

    pip install thrift
    
아래 명령 중 하나로 Server를 실행합니다.

    twistd -y py.twisted/PythonServer.tac 

또는 
    
    python py/PythonServer.py
    
아래 명령 중 하나로 Client를 실행합니다.

    python py.twisted/PythonClient.py
    python py/PythonClient.py
    php php/PhpClient.php
    
끝
