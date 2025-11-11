# Changelog

## 1.0.0 (2025-11-11)


### Features

* WebSocket で 試合イベントを送受信する機能、および観戦用の画面を追加 ([#1487](https://github.com/tufusa/kcmsx/issues/1487)) ([93c9aa4](https://github.com/tufusa/kcmsx/commit/93c9aa4900f826c2c799624183546c0fa324e509))
* バックエンドを `/api` にプロキシするように変更 ([#1614](https://github.com/tufusa/kcmsx/issues/1614)) ([dd9c966](https://github.com/tufusa/kcmsx/commit/dd9c966ed2614eb8f38a60fc55f4db5a2e287dd8))
* 公開用試合表ページを作成 ([#1517](https://github.com/tufusa/kcmsx/issues/1517)) ([61ca7fe](https://github.com/tufusa/kcmsx/commit/61ca7fe20f2f17cd1ab1678b453ed18f963dfe7b))
* 認証に使用するシークレット値を環境変数で渡せるようにした ([#1587](https://github.com/tufusa/kcmsx/issues/1587)) ([f00a3b6](https://github.com/tufusa/kcmsx/commit/f00a3b6b3124c73742204283787a996bda20bef0))


### Bug Fixes

* 予選を同時に生成 ([#826](https://github.com/tufusa/kcmsx/issues/826)) ([93edb46](https://github.com/tufusa/kcmsx/commit/93edb462bd03646f30a572bce27dd1761c558a34))
* 勝者が決定できない場合にもMainMatchRepositoryをupdateする ([#1218](https://github.com/tufusa/kcmsx/issues/1218)) ([2770dd2](https://github.com/tufusa/kcmsx/commit/2770dd2ab9028b370660f1f642e5cbcb4bd98efa))
* 勝者の決定にSetMainMatchWinnerServiceを使用 ([#1126](https://github.com/tufusa/kcmsx/issues/1126)) ([3bfe2a6](https://github.com/tufusa/kcmsx/commit/3bfe2a63d78e1698d1083fbf907d473bd5345808))
* 試合番号がコースごとに部門をまたいでも重複せず、連番になるように修正 ([#1520](https://github.com/tufusa/kcmsx/issues/1520)) ([d95476d](https://github.com/tufusa/kcmsx/commit/d95476d3c8f63cbaef14cd6ec824cef8816cff45))
