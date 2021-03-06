# シーケンスオブジェクト

PostgreSQLには、シーケンスオブジェクトというものがある。
テーブルのidに採番のための値を一意の値として保持する目的などに利用する。

[PostgreSQL 12.3文書/第9章 関数と演算子/9.16. シーケンス操作関数](https://www.postgresql.jp/document/12/html/functions-sequence.html)

# シーケンスオブジェクト操作関数の注意点

トランザクション内で、シーケンスオブジェクトの値を変更した後、トランザクション自体をロールバックしても
シーケンスオブジェクトに加えた変更は戻されることはない。

[PostgreSQL 12.3文書/第9章 関数と演算子/9.16. シーケンス操作関数](https://www.postgresql.jp/document/12/html/functions-sequence.html)より引用

```
重要
シーケンスはトランザクションとは異なる扱いを受けるため、setvalによる変更は、そのトランザクションがロールバックされたとしても元に戻りません。
```
