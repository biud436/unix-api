# Introduction
리눅스 및 맥 (유닉스) 기반 OS에서 CPP로 어떻게 프로그램을 작성해야 하는가? 유닉스 기반 OS와 윈도우즈와는 무슨 차이가 있는가? 대한 궁극적인 호기심을 해결하기 위해 작성한 프로그램이다. 

나아가 Windows API를 어떻게 리눅스나 맥 전용으로 변경해야 하는가? 크로스플랫폼 시대에서 QT나 SDL2 등의 라이브러리를 사용하지 않고 어떻게 파일, 메모리, 프로세스, 시그널, 타이머, 서비스, 쓰레드, IPC, 파일 시스템, 유닉스 소켓을 이용한 IPC 등을 작성해야 하는 가를 연구하기 위함이다. 

이러한 리눅스나 맥 API들은 루비 등을 하면서 함수명들은 익히 들어봤지만 실제로는 써본 적이 없다. 그러나 직장 생활 등을 하면서 리눅스를 많이 다루고 있기 때문에, 이러한 유닉스 기반 OS에 대해 더 깊게 알아보고자 하는 순수한 호기심이 생긴 것이다.

리눅스 API의 학습과 활용은 내 삶이 다하는 순간까지 해야 하는 장기적인 플랜이다. 이 프로젝트는 그것의 첫 시작을 알리는 종소리에 불과하다.

하지만 단순 API 학습을 누군가 보기를 바라며 깃허브 프로젝트로 공개적으로 올리는 것은 나의 취향이 아니다. 이 프로젝트는 언젠가 비공개로 전환될 것이다.

언젠가 유닉스 기반 API로 무언가 거대한 프로젝트를 만들게 된다면, 공개할 수 있으리라 생각한다.

# Usage

## Linux
To compile this program using `g++` in your system, try to do as below command on your linux terminal.

```sh
git clone https://github.com/biud436/unix-api.git
cd ./unix_api
chmod +x ./build.sh
./build.sh
```

if you need to clean unused files after compiling, you can do as following steps.

```sh
cd ./file_copy
make clean
```

## Mac
To compile this program, you must use the IDE called `XCode` and you can use specific unix API only.
these certain API didn't support on the Mac.


