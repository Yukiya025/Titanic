# Reference sites
[【Git】間違ってpushした場合の取り消し方](https://qiita.com/kazu56/items/ce6eafa67a09463e6064)
**注意**
かならずデスクトップにファイルをすべてバックアップ取ってから実行!!! でないとすべて容赦なく消える。

`$ git log`でcommitID取得
`$ git revert <commit id>`する。
`$ git push -f origin master`する。