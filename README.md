box-dart
========

[![wercker status](https://app.wercker.com/status/f96d712f8efe2c6e9ee586ff4661a06d/m "wercker status")](https://app.wercker.com/project/bykey/f96d712f8efe2c6e9ee586ff4661a06d)

A box designed to run build, test and deployment for Dart projects. It runs Dart version 0.8.1.2_r28355 which installed in `$HOME/DART_SDK`. This path is available via `DART_SDK` and included in the `PATH`:

```
export DART_SDK="$HOME/dart-sdk"
export PATH="$PATH:$DART_SDK/bin"
```

Dart provides the following tools:

* [`dart`](https://www.dartlang.org/docs/dart-up-and-running/contents/ch04-tools-dart-vm.html): The standalone VM
* [`dart2js`](https://www.dartlang.org/docs/dart-up-and-running/contents/ch04-tools-dart2js.html): The Dart-to-JavaScript compiler
* [`dartanalyzer`](https://www.dartlang.org/docs/dart-up-and-running/contents/ch04-tools-dart_analyzer.html): The static analyzer
* [`dartdoc`](https://www.dartlang.org/docs/dart-up-and-running/contents/ch04-tools-dartdoc.html): The API documentation generator
* [`pub`](http://pub.dartlang.org/): The Dart package manager

## History

* `0.0.1`: Initial release
