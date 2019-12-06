# LEDGuidedPiano(피아노 학습 지원 시스템)
> 초보자들도 쉽고 효과적으로 학습할 수 있도록 피아노 학습을 지원하는 시스템

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

본 연구에서 개발한 피아노 학습 지원 시스템은 스마트폰 기반의 학습 애플리케이션과 제어부로 구성된다.
제어부는 스마트폰 애플리케이션과 블루투스 통신을 통하여 악기 연주 정보를 수신한 후,
LED를 점등시켜 사용자에게 타건위치를 표시해줌으로써 건반과 음계의 상관관계를 숙지할 수 있도록 구현하였다.

## 개발 환경 

* Arduino ide
* Android Studio

## 재료

* Arduino Uno
* Bluetooh Shield v2
* AdafruitLedStrip
* Midi Piano 

## 과정
* 시스템 구성도
![시스템 구성도](https://user-images.githubusercontent.com/39858400/70323900-70bc9680-1871-11ea-81d1-b63a648de185.png)
* 시스템 흐름도
![시스템 흐름](https://user-images.githubusercontent.com/39858400/70323904-72865a00-1871-11ea-9a88-133ddac3502a.png)
* 회로도
![회로도](https://user-images.githubusercontent.com/39858400/70323908-7619e100-1871-11ea-8d24-8ea68942e7c8.png)
## 업데이트 내역

* 0.0.1
    * 문서 업데이트

## 정보

송기석 – https://www.rocketpunch.com/@ghgsb6200 – 이메일주소: ghgsb6200@gmail.com

[https://github.com/Song014/github-link](https://github.com/Song014/)

## 기여 방법

1. (<https://github.com/Song014/WiFi-redirection/fork>)을 포크합니다.
2. (`git checkout -b feature/fooBar`) 명령어로 새 브랜치를 만드세요.
3. (`git commit -am 'Add some fooBar'`) 명령어로 커밋하세요.
4. (`git push origin feature/fooBar`) 명령어로 브랜치에 푸시하세요. 

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
