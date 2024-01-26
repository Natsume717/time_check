# time_check
predicatesのtime_checkに関するデータパックサンプルになります。

詳しくはブログ記事『[【マイクラ】time_checkで経過した時間を検知【predicate】](https://natsumake.com/time_check/)』を参考にしてください。

<h3>使い方</h3>

導入後<br>
```/execute if predicate sample:time_check run give @a diamond 1```

```/execute if predicate sample:period run give @a diamond 1```<br>
というコマンドを実行することで、time_checkが条件となっているコマンドを実行できます。

```sample:time_check```は0～12000を指定しており、```sample:period```はperiodに12000を指示したうえで、0～6000を指示しています。
