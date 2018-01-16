# Travis CI Trial with PHP

このリポジトリは、Travis CIでPHPUnitを使ったユニットテストを実行するサンプルです。

## 使い方

1. このリポジトリをフォークします
1. Travis CIで自動テストの対象リポジトリに設定します
1. テストを実行してみると、1箇所失敗することがわかります
    - テストは `tests/CalcTest.php` です
1. `src/Calc.php` のソースコードを直し、プッシュします
1. 今度はテストがすべて通るはずです
