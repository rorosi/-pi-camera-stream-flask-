# 라즈베리파이 - 실시간 웹 스트리밍(pi-camera-stream-flask)

스트리밍을 하기위해 다음과 같은 패키지를 설치합니다.

    sudo apt-get update 
    sudo apt-get upgrade

    sudo apt-get install libatlas-base-dev
    sudo apt-get install libjasper-dev
    sudo apt-get install libqtgui4 
    sudo apt-get install libqt4-test
    sudo apt-get install libhdf5-dev

    sudo pip3 install flask
    sudo pip3 install numpy
    sudo pip3 install opencv-contrib-python
    sudo pip3 install imutils
    sudo pip3 install opencv-python

## 1. git clone을 통해 파일을 가져옵니다.

    cd /home/pi
    git clone https://github.com/rorosi/-pi-camera-stream-flask-.git

## 2. 웹 스트리밍을 시작합니다.

    cd pi-camera-stream-flask
    python3 main.py

![13](https://user-images.githubusercontent.com/56014938/126754316-64beed6f-6caf-45b4-b8c5-791f7ff365cf.png)

## 3. 라즈베리파이ip:5000으로 접속합니다.

![14](https://user-images.githubusercontent.com/56014938/126754366-3fb3fed5-8f58-409a-8ea0-f55778ee876c.png)

    


