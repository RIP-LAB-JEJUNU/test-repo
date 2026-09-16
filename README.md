# 프로젝트 이름

> **이 README는 템플릿입니다.** 아래 항목을 프로젝트에 맞게 채우고,
> 이 인용문과 안내 문구는 지우세요. 필요 없는 항목은 삭제해도 됩니다.

한 줄 설명 — 이 저장소가 무엇을 하는 코드인지.

## 개요

무엇을 위한 프로젝트인지, 어떤 문제를 푸는지 두세 문장으로.
관련 논문이나 실험이 있다면 여기에 링크.

## 환경

돌리는 데 필요한 것. 예:

- Geant4 11.x / ROOT 6.x
- Python 3.11 (`requirements.txt` 참조)
- 클러스터 모듈: `module load ...`

## 실행 방법

처음 받은 사람이 그대로 따라 할 수 있게 명령어 단위로.

```bash
# 예시
cmake -S . -B build && cmake --build build
./build/sim macros/run1.mac
python scripts/analyze.py
```

## 디렉터리 구조

구조는 프로젝트마다 다릅니다. 이 저장소가 실제로 쓰는 것만 적으세요.

```
src/        소스
include/    헤더
macros/     Geant4 매크로 (.mac)
scripts/    분석 · 그림 생성 코드
```

## 데이터

**데이터와 그림은 저장소에 넣지 않습니다** (`.gitignore` 참조).
실제 파일이 어디 있는지 여기에 적어두세요.

```
입력 데이터: /path/on/cluster/...
출력 위치:   /path/on/cluster/...
```

## 그림

논문·발표용 그림은 커밋하지 않고 코드로 재생성합니다.
어떤 스크립트가 어떤 그림을 만드는지 적어두면 나중에 본인이 편합니다.

| 그림 | 생성 스크립트 |
| --- | --- |
| Fig. 1 | `scripts/plot_spectrum.py` |
