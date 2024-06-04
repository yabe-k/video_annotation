# About this
動画ファイルからイベントの発生時刻や回数を記録する作業を支援するツールです。動画を再生しながら、動画内のタイムスタンプとともにメモを残すことができます。

# 使い方
## 動画ファイルの読み込み
動画ファイルを中央にドラッグ&ドロップして読み込みます。ファイルはローカルのみで処理され、サーバーなどに送信されることは一切ありません。
対応する動画のフォーマットはブラウザに依存します。mp4はすべてのブラウザで使用できるはずです。
## 動画の再生とアノテーション作業
### 動画再生のコントロール
* [Space]キーを押すと(または左下の⏯をクリックすると)、動画の再生/停止を行えます。
* 左下の"speed"入力欄では動画の再生速度を指定できます。1で等倍再生、0.5等ではスロー再生、2や4では高速再生となります。
* 左右の矢印キーを押すと(または左下の⏪⏩をクリックすると)、指定した時間だけスキップできます。スキップする時間の長さは⏪⏩の下の入力欄から秒単位で指定できます。
### アノテーションの追加
動画を再生した状態でキー入力を行うことで、その時点での動画の再生時間とともにイベントが記録されます。
* [Enter]キーを押すと、動画が停止し入力ダイアログが表示されます。ここにイベント情報(任意の文字列)を記入してEnterを押すとイベントが記録されます。ダイアログに何も記入せずに[Enter]を押すとアノテーションはキャンセルされます。
* [0] ~ [9] の数字キー(テンキー含む)を押すと、0 ~ 9と名前のついたイベントが記録されます。
* 記録されているイベントは、右下の👁‍🗨アイコンを押すことで表示できます。

記録されたイベントの削除も可能です。
* Undoボタンを押すと、各カテゴリの最新のイベント1つが削除されます。
* イベントの削除は、[Ctrl + <数字キー>] や [Ctrl + Enter]でも行えます。
### アノテーションの保存
[Ctrl + S]または右下の保存のアイコンのクリックで、デフォルトのダウンロード先のフォルダにCSVファイルが保存されます。
### 次の動画の読み込み
別の動画の操作を始める場合は、このツールを再読み込みして再度同様の作業を行ってください。
