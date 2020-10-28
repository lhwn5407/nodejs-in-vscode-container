# nodejs 의 vscode devcontainer 상 개발을 쉽게 시작하는 템플릿

내가 쓰려고 만듬

### 목차

<!-- 아래는 npm run update-readme-toc 를 활용한 자동 목차 삽입 구간임. pre-commit hook에 의해 자동 갱신 -->

<!-- prettier-ignore-start -->
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->
<!-- prettier-ignore-end -->

### 시작 하기

##### 코드 받기

```bash
# 클론
git clone '이 레파지토리'
cd '이 레파지토리'

# nodejs 의존성, git hook을 포함한 전체 환경 설치
npm run install-all
```

##### 기술 스택

- 코드 품질:
  - eslint
  - prettier
- 개발 편의:
  - vscode devcontainer
  - 기타 vscode 확장 설정
  - doctoc README 자동갱신
  - git hook - doctoc
