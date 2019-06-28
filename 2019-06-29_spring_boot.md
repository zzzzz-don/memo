## 概要
Spring bootをIntelliJで使えるようにする。

## セットアップ
- JDKをダウンロード
```
$ java --version
java 12.0.1 2019-04-16
Java(TM) SE Runtime Environment (build 12.0.1+12)
Java HotSpot(TM) 64-Bit Server VM (build 12.0.1+12, mixed mode, sharing)
```
```
$ /usr/libexec/java_home -V
Matching Java Virtual Machines (2):
    12.0.1, x86_64:	"Java SE 12.0.1"	/Library/Java/JavaVirtualMachines/jdk-12.0.1.jdk/Contents/Home
    1.8.0_211, x86_64:	"Java SE 8"	/Library/Java/JavaVirtualMachines/jdk1.8.0_211.jdk/Contents/Home
/Library/Java/JavaVirtualMachines/jdk-12.0.1.jdk/Contents/Home
```
* Project Structure for New ProjectsでJDKを設定

## サンプル実行
* clone
```
$ git clone https://github.com/spring-guides/gs-rest-service.git
```
* Welcome画面でImport Project->complete配下のbuild.gradleを選択

## 参考リンク
- https://qiita.com/MasanoriMT/items/492a0fab07793a645ba5
- https://spring.io/guides/gs/rest-service/
