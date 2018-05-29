# "머신러닝 실무 프로젝트" 예제 코드 노트북

이 저장소는 "머신러닝 실무 프로젝트" 책의 예제 코드 노트북을 담고 있습니다.

## 저장소의 구성

각 장마다 예제로 실린 코드를 주피터 노트북 형태로 제공합니다.

7장의 예제 코드는 fastFM 라이브러리를 필요로 합니다. 이 라이브러리는 윈도우에서는 사용할 수 없기 때문에 [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10)를 사용하거나 macOS 혹은 리눅스에서 실행하셔야 합니다.


이 예제 코드는 Python 3.5.1, 3.6.3에서 동작을 확인하였습니다. 아래와 같이 환경을 구축하시면 됩니다.


```sh
$ virtualenv -p python3 venv
$ source venv/bin/activate
(venv)$ pip install -r requirements.txt -c constraints.txt
```

## fastFM의 설치와 관련된 사항

fastFM을 미리 컴파일된 바이너리 패키지로 설치하면 Python에서 임포트가 안될 수 있습니다. 이런 경우에는 [fastFM 깃허브 페이지](https://github.com/ibayer/fastFM#installation)의 'source install' 항목을 참조하여 소스를 컴파일하시기 바랍니다.


Linux 및 macOS 용 wheel 파일이 PyPi에서 배포되었기 때문에 Python 3.6 부터는 fastFM을 사용할 수 있습니다.

## 저자들이 출간과 관련하여 작성한 컬럼
### 아리가
- [오라일리에서 "머신러닝 실무 프로젝트"가 출판됩니다](https://medium.com/@chezou/cf835ff4c128)

### 니시바야시
- [오라일리에서 "머신러닝 실무 프로젝트"라는 책이 나옵니다](https://hagino3000.blogspot.jp/2017/11/oreillymlbook.html)
### 나카야마
- ["인공지능을 이용해서 쌈박한 성과를 내보라"는 상사는 도대체 무슨 생각일까](https://medium.com/@tokoroten/96f4da85b924)
- [악용금지: 100% 성공하는 A/B 테스트 만드는 법](https://medium.com/@tokoroten/c871f61233e6)
