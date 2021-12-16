# Java

rt.jar APIクラス群の実体

"C:\Program Files\Java\jdk1.8.0_73\jre\lib\rt.jar"

これを解凍した中身がAPIクラス群の実体。数学系。

# Java実行

コンパイルが完了しているJavaファイルを実行する
```
java Javaファイル名
```

コンパイルから実行までの手順

Sample.java 
```Java
public slass Sample{
    public static void main(String[] args){
        System.out.println("Hello Java!");
    }
}
```

実行結果
```
C:\User\ユーザー名> cd C:\Sample
C:\User\ユーザー名> javac Sample.java
C:\User\ユーザー名> java Sample
Hello Java!
```