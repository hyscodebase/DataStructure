# C언어로 쉽게 풀어쓴 자료구조 — 학습용 포크

C 자료구조 예제를 장별 Visual Studio 프로젝트로 보관한 학습용 포크입니다. 원본 저장소는 [yunkyung318/DataStructure](https://github.com/yunkyung318/DataStructure)이며, 예제 코드의 출처와 기여 이력은 원본 및 Git 기록을 따릅니다.

## 주제

| 폴더 | 내용 |
|---|---|
| `DataStructure1` ~ `DataStructure3` | 시간 복잡도, 재귀, 배열·구조체·동적 메모리 |
| `DataStructure4` ~ `DataStructure5` | 스택·수식 변환·큐·시뮬레이션 |
| `DataStructure6` ~ `DataStructure7` | 리스트·연결 리스트·연결 스택·큐 |
| `DataStructure8` ~ `DataStructure9` | 이진 트리·탐색 트리·힙·허프만 코드 |
| `DataStructure10` ~ `DataStructure11` | 그래프 탐색, 최소 신장 트리, 최단 경로, 위상 정렬 |

## 실행

Windows에서는 원하는 장의 `.sln`을 Visual Studio로 엽니다. 장 안의 모든 C 파일을 동시에 실행하는 구조가 아니므로, 실행할 예제를 기준으로 빌드 대상을 확인하세요.

GCC 또는 Clang에서는 표준 C로 작성된 예제 하나를 직접 컴파일할 수 있습니다.

```bash
mkdir -p build
gcc -std=c17 -Wall -Wextra DataStructure1/DataStructure1/cal_time.c -o build/cal_time
./build/cal_time
```

일부 파일은 `main` 없는 함수 예제입니다. Windows 전용 API나 이전 인코딩을 사용한 파일은 환경에 맞게 조정해야 합니다.

## 저장소 참고

`.vs/`, `Debug/` 등에는 과거 IDE·빌드 산출물이 포함되어 있습니다. 학습할 때는 각 장의 `.c` 소스와 프로젝트 구성을 중심으로 살펴보세요. 이 README는 포크의 탐색·실행 안내를 보완하며 원본 코드의 저작권이나 배포 조건을 변경하지 않습니다.
