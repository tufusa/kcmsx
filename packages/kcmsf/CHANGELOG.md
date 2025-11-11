# Changelog

## 1.0.0 (2025-11-11)


### Features

* `useQueryParamsState` のセッタでクエリパラメータに保存する機能を追加 ([#1519](https://github.com/tufusa/kcmsx/issues/1519)) ([b315e32](https://github.com/tufusa/kcmsx/commit/b315e32be21c37041a3ebf9a1dd58cdeb397a8ae))
* WebSocket で 試合イベントを送受信する機能、および観戦用の画面を追加 ([#1487](https://github.com/tufusa/kcmsx/issues/1487)) ([93c9aa4](https://github.com/tufusa/kcmsx/commit/93c9aa4900f826c2c799624183546c0fa324e509))
* クエリパラメータの更新が replace になるように変更 ([#1523](https://github.com/tufusa/kcmsx/issues/1523)) ([378f049](https://github.com/tufusa/kcmsx/commit/378f049ac2f026e0184caaacdffe53a619eac659))
* ゼッケン番号を自然数順にソートできるように変更 ([#1181](https://github.com/tufusa/kcmsx/issues/1181)) ([b48d6c1](https://github.com/tufusa/kcmsx/commit/b48d6c1872c24a367c4b61d87946c57709db2f8d))
* チーム一覧ページに読み込み中、読み込み失敗時の表示を追加 ([#1353](https://github.com/tufusa/kcmsx/issues/1353)) ([55186e9](https://github.com/tufusa/kcmsx/commit/55186e9309023f97382c053137689a4484155726))
* バックエンドを `/api` にプロキシするように変更 ([#1614](https://github.com/tufusa/kcmsx/issues/1614)) ([dd9c966](https://github.com/tufusa/kcmsx/commit/dd9c966ed2614eb8f38a60fc55f4db5a2e287dd8))
* ヘッダーにスクロールと連動して非表示になる機能を追加 ([#1578](https://github.com/tufusa/kcmsx/issues/1578)) ([3a22ba2](https://github.com/tufusa/kcmsx/commit/3a22ba25c6b3a76bf7c057ee9c375ca786b799d3))
* ヘッダーにトーナメント表へのリンクを追加 ([#1585](https://github.com/tufusa/kcmsx/issues/1585)) ([7d598e2](https://github.com/tufusa/kcmsx/commit/7d598e2aef06cd8d7a637b3f5c9beafbb40b1c5e))
* 公開用試合表ページに自動更新機能を追加 ([#1580](https://github.com/tufusa/kcmsx/issues/1580)) ([6273558](https://github.com/tufusa/kcmsx/commit/6273558c53f1032aeb1a815e4481f392a3660cc9))
* 公開用試合表ページを作成 ([#1517](https://github.com/tufusa/kcmsx/issues/1517)) ([61ca7fe](https://github.com/tufusa/kcmsx/commit/61ca7fe20f2f17cd1ab1678b453ed18f963dfe7b))
* 参加者という文言をチームに変更 ([#1345](https://github.com/tufusa/kcmsx/issues/1345)) ([8df0642](https://github.com/tufusa/kcmsx/commit/8df0642fcfe606001996bc9756749e4e6097a4f2))
* 表示をチームからコースに変えた ([#1382](https://github.com/tufusa/kcmsx/issues/1382)) ([e057aab](https://github.com/tufusa/kcmsx/commit/e057aabeffaec9aa14d08370a5991af6559f0331))
* 試合ページ・観戦ページにおける WebSocket 切断時の自動再接続を実装 ([#1572](https://github.com/tufusa/kcmsx/issues/1572)) ([93d417c](https://github.com/tufusa/kcmsx/commit/93d417c6093824938d76b8cedee214f62e50402d))
* 試合ページでチームの表示を左右反転する機能を追加 ([#1215](https://github.com/tufusa/kcmsx/issues/1215)) ([5df18fa](https://github.com/tufusa/kcmsx/commit/5df18fa3fd97a00d3e9a801ec7bcf4e76a8119b9))
* 試合ページと観戦ページで左右入れ替え時に色も入れ替わるように変更 ([#1510](https://github.com/tufusa/kcmsx/issues/1510)) ([1bc7eca](https://github.com/tufusa/kcmsx/commit/1bc7eca3bb395c33a7d65d1a0eb8ffd1ab6f645d))
* 試合ページのcountableな状態の増減ボタンをsquareアイコンに変更した ([#1182](https://github.com/tufusa/kcmsx/issues/1182)) ([c2cc32e](https://github.com/tufusa/kcmsx/commit/c2cc32e7f5ff3846a65280d71b31f66cd2dd39c9))
* 試合ページ以外を試合表ページと同じレイアウトに統一 ([#1330](https://github.com/tufusa/kcmsx/issues/1330)) ([20cf65a](https://github.com/tufusa/kcmsx/commit/20cf65af0fb2d596555bc8d5a3f8220b860c0978))
* 試合表で走るサイドを明示した ([#1287](https://github.com/tufusa/kcmsx/issues/1287)) ([df2d47e](https://github.com/tufusa/kcmsx/commit/df2d47ef7b4fbd22813844b0b78f607fc7456fcc))
* 試合表ページにフィルター・ソート機能を追加 ([#1581](https://github.com/tufusa/kcmsx/issues/1581)) ([4140647](https://github.com/tufusa/kcmsx/commit/4140647a1d57217851bfd33304dd0fd7ed4173bc))
* 試合表ページに自動更新機能を追加 ([#1501](https://github.com/tufusa/kcmsx/issues/1501)) ([6f19616](https://github.com/tufusa/kcmsx/commit/6f196162c29551d1c55525c32e65722cba6ad549))
* 試合観戦ページにWebSocketエラー発生時の表示を追加 ([#1503](https://github.com/tufusa/kcmsx/issues/1503)) ([2530455](https://github.com/tufusa/kcmsx/commit/2530455f9f9cf1cfe51b1154c97de356bf1b0b6c))


### Bug Fixes

* valueを変数で持つようにした ([#1135](https://github.com/tufusa/kcmsx/issues/1135)) ([43bad9e](https://github.com/tufusa/kcmsx/commit/43bad9ef057adefeec129eba624a00a9b8a23aca))
* WebSocket の再接続処理中にページ遷移してもリトライし続ける問題を修正 ([#1596](https://github.com/tufusa/kcmsx/issues/1596)) ([e929a18](https://github.com/tufusa/kcmsx/commit/e929a18963726b126f39a46713109fbf8677b1a5))
* エキシビションモードでは WebSocket を接続しないように修正 ([#1590](https://github.com/tufusa/kcmsx/issues/1590)) ([c61d111](https://github.com/tufusa/kcmsx/commit/c61d111710fc2548303cf9d5ddc642942b4d529e))
* 一括登録ページでCSVに空行が含まれているとページがクラッシュする問題の修正 ([#1597](https://github.com/tufusa/kcmsx/issues/1597)) ([08217e4](https://github.com/tufusa/kcmsx/commit/08217e43b29bf013fc82a8080614eee698f52923))
* 公開用試合表から観戦カラムを削除 ([#1595](https://github.com/tufusa/kcmsx/issues/1595)) ([0770f99](https://github.com/tufusa/kcmsx/commit/0770f99262652ec6ce5469d7fb0d1d3d2446c7ea))
* 試合ページの得点リセットボタンの判定が本来の大きさになるよう修正 ([#1502](https://github.com/tufusa/kcmsx/issues/1502)) ([72ce452](https://github.com/tufusa/kcmsx/commit/72ce45252e1c97014e49f563849242dfab4ca4a0))
* 試合番号がコースごとに部門をまたいでも重複せず、連番になるように修正 ([#1520](https://github.com/tufusa/kcmsx/issues/1520)) ([d95476d](https://github.com/tufusa/kcmsx/commit/d95476d3c8f63cbaef14cd6ec824cef8816cff45))
* 試合結果ページのプルダウンのデザインの統一 ([#1192](https://github.com/tufusa/kcmsx/issues/1192)) ([1ad494c](https://github.com/tufusa/kcmsx/commit/1ad494cbf6dcb8de1705fdaa6d6b3b8423a24c58))
