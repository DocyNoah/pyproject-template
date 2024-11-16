# commit message prefix

## Minimal prefix list

| 코드 수정 | 기능 변경 | 설명 | prefix |
| --- | --- | --- | --- |
| O | O | 기능 추가 | feat |
| O | O | 버그 수정 | fix |
| O | X | 구조 개선 | refactor |
| O | X | 가독성 개선 | style |
| X | X | 테스트 코드 | test |
| X | X | 문서 관련 | docs |

## Usage

- prefix가 다르면 커밋이 분리 되어야 함.
- prefix가 서로 다른데 하나의 커밋으로 한다면 상위 prefix로 작성.
