# toutiao
Gradle Project <br>
$ ./gradlew bootRun

### Install Gradle
$ mkdir /opt/gradle <br>
$ unzip -d /opt/gradle gradle-4.1-bin.zip <br>
$ ls /opt/gradle/gradle-4.1 <br>
LICENSE  NOTICE  bin  getting-started.html  init.d  lib  media <br>
$ export PATH=$PATH:/opt/gradle/gradle-4.1/bin <br>
$ gradle -v

### Upgrade with the Gradle Wrapper
$ ./gradlew wrapper --gradle-version=4.1 --distribution-type=bin

### Building Java Applications
$ mkdir java-demo
$ cd java-demo
$ gradle init --type java-application
$ ./gradlew build
$ ./gradlew run
$ ./gradlew tasks
