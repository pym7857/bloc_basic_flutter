# flutter_bloc_test

기본앱에 bloc 패턴을 적용해보기

## Bloc 패턴
* ui와 data를 분리시키자.
* 로직, 데이터 등을 bloc으로 옮기고, Stream을 통해 변화를 관찰하면서 값을 변경 (=reactive)
* 1) bloc클래스에서 stream get 메서드, 값 증가 메서드 만들어줌
* 2) main.dart에서 StreamBuilder를 사용 (snapshot)
* 데이터는 snapshot에 들어있음

![img](https://github.com/pym7857/bloc_basic_flutter/blob/main/img/1111.PNG?raw=true)
