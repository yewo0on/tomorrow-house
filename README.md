# 반응형 클래스 정의

| Mobile | Tablet | Desktop | class        |
| ------ | ------ | ------- | ------------ |
| O      | X      | X       | `.sm-only`   |
| O      | O      | X       | `.lg-hidden` |
| X      | O      | X       | `.md-only`   |
| X      | O      | O       | `.sm-hidden` |
| X      | X      | O       | `.lg-only`   |
| O      | X      | O       | `.md-hidden` |

## 의미 정리

- `.sm-only`
  - 모바일에서만 보임

- `.md-only`
  - 태블릿에서만 보임

- `.lg-only`
  - 데스크탑에서만 보임

- `.sm-hidden`
  - 모바일에서 숨김

- `.md-hidden`
  - 태블릿에서 숨김

- `.lg-hidden`
  - 데스크탑에서 숨김
