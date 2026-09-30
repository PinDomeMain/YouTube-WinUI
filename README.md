# YouTube WinUI

<p align="center"> <img src="/Screenshots.png" alt="Scr" width="900"> </p>

If there is sufficient interest or demand, I will also create an English version. 
YouTubeをWindows向けのWinUI 3アプリとして利用できる初回リリースです。

## 主な機能

* YouTubeのWebView2ベースでの動画再生
* YouTubeへのログイン・ログイン状態の確認
* WinUI 3ネイティブのタイトルバー
* ネイティブナビゲーションペイン
* YouTube検索
* 通知・ユーザーメニューへのアクセス
* ホーム、ショート、登録チャンネル、マイページなどのナビゲーション
* 履歴、再生リスト、後で見る、高く評価した動画などへのアクセス
* アプリ設定ページ
* システム / ライト / ダークテーマの切り替え
* 設定の保存
* YouTubeの動画フルスクリーン表示に対応
* フルスクリーン解除時に通常のウィンドウレイアウトへ自動復帰

## UI

YouTubeのWebページ上のヘッダーや左ナビゲーションを非表示にし、WinUI 3側のネイティブUIに置き換えています。

MicaによるWindows 11向けの外観にも対応しています。

## インストール方法

1. msixファイルをダウンロード
2. ファイルを右クリックしてプロパティ
3. 「デジタル署名」→「埋め込み署名」→「詳細(D)」
4. 「証明書の表示(V)」
5. 「証明書のインストール(I)...」
6. 保存場所「ローカル コンピューター(L)」
7. 証明書ストア「証明書をすべて次のストアに配置する(P)」→「参照(R)...」
8. 証明書ストアの選択「信頼されたルート証明機関」
9. 「完了」
10. msixファイルを開く
11. インストール


## 初回リリース

**Version:** 1.0.0
**Platform:** Windows
**Framework:** WinUI 3 / Windows App SDK
**Web engine:** WebView2
