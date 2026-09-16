# test-repo

Google Colab에서 바로 실행할 수 있는 샘플 주피터 노트북 저장소입니다.

## 노트북 열기

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RIP-LAB-JEJUNU/test-repo/blob/main/hello.ipynb)

위 배지를 누르면 `hello.ipynb`가 Colab에서 열립니다. 설치할 것은 없고, 구글 계정으로 로그인만 되어 있으면 됩니다.

> 배지는 `main` 브랜치를 가리킵니다. 아직 병합 전인 브랜치의 노트북을 열려면 URL의 `blob/main` 부분을 해당 브랜치 이름으로 바꾸세요.

## 노트북 구성 (`hello.ipynb`)

| 단계 | 내용 |
| --- | --- |
| 1 | `print`로 첫 셀 실행해 보기 |
| 2 | 파이썬 버전 · OS · Colab 여부 등 실행 환경 확인 |
| 3 | `pandas`로 간단한 표 만들고 등급 계산 |
| 4 | `matplotlib`으로 sin / cos 그래프 그리기 |
| 5 | `!` 를 이용한 셸 명령 실행과 GPU 확인 |

사용하는 `pandas`, `numpy`, `matplotlib`은 Colab에 기본 설치되어 있어 따로 설치할 필요가 없습니다.

## 사용법

1. 위의 **Open In Colab** 배지를 클릭합니다.
2. 셀을 위에서부터 차례대로 실행합니다 (`Shift + Enter`, 또는 **런타임 > 모두 실행**).
3. 자유롭게 코드를 고쳐 보세요. Colab에서의 수정은 이 저장소에 영향을 주지 않습니다.
   저장하려면 **파일 > Drive에 사본 저장**을 사용하세요.

### GPU 사용하기

**런타임 > 런타임 유형 변경 > 하드웨어 가속기**에서 GPU를 선택하면 5번 셀의 `nvidia-smi` 출력에서 할당된 GPU를 확인할 수 있습니다.

## 로컬에서 실행하기

Colab 없이 내 컴퓨터에서 실행하려면:

```bash
git clone https://github.com/RIP-LAB-JEJUNU/test-repo.git
cd test-repo
pip install jupyter pandas numpy matplotlib
jupyter notebook hello.ipynb
```
