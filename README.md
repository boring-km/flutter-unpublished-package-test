## Test Package

- 용도: pub.dev에 올리지 않고 사용할만한 방법 모색
- 관련 문서: https://docs.flutter.dev/development/packages-and-plugins/using-packages#dependencies-on-unpublished-packages
- pubspec.yml 작성

```yml
dependencies:
  testpackage:
    git:
      url: git://github.com/boring-km/flutter-unpublished-package-test.git
```
