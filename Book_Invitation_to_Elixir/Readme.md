# 「PhoenixLiveViewとNervesをさわるElixirへのいざない」正誤表

## 技術書典7 製本版

| No. | 章 | ページ | 誤 | 正 |
| - | - | - |-|-|
|1|4.5.2、4.6.6|50、60、61|router.exs|router.ex|
|2|5.6.1|89|git clone https://github.com/nerves-project/nerves_examples|git clone https://github.com/nerves-project/nerves_examples.git|
|3|4.4|47|{:phoenix_live_view, github: "phoenixframework/phoenix_live_view"},|{:phoenix_live_view, "0.1.1"},|
|4|1.4|13|RERP|REPL|


### 補足:

* No.2については、そのままでもcloneすることは可能です。
* No.3については、2019年9月1日時点のコードで動くようにするため、バージョン指定に修正しています。本件については、この内容が関係しています。https://github.com/phoenixframework/phoenix_live_view/commit/b01ca6e816f1133188b9a8714f3cc5fe3dfc8472
