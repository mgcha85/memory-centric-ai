# memory-centric-ai

메모리 관점 AI 세미나 발표 자료 저장소입니다.

## 배포 방식

이 저장소는 GitHub Pages를 GitHub Actions가 아니라 Branch 기반으로 배포합니다.

- Branch: main
- Folder: /(root)
- 엔트리 파일: index.html

## GitHub Pages 설정 방법

1. 저장소 Settings로 이동
2. Pages 메뉴 선택
3. Build and deployment > Source를 Deploy from a branch로 선택
4. Branch를 main, Folder를 /(root)로 선택 후 Save

설정이 완료되면 main에 push할 때마다 최신 index.html이 자동 반영됩니다.

## 사내 GitHub Enterprise로 이전 시

같은 구조를 그대로 사용하면 됩니다.

1. 사내 원격 저장소로 코드 push
2. 해당 저장소의 Pages 기능에서 Deploy from a branch 선택
3. main / (root) 지정

사내 정책상 Actions가 제한되어도 Branch 배포는 보통 허용되는 경우가 많아 운영이 단순합니다.
