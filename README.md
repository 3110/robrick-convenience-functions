# [ロブリック](https://robohon.com/apps/robrick.php)用のちょっと気の利いた関数ブロック群

シャープ社製のコミュニケーションロボット「[ロボホン](https://robohon.com/)」用のプログラミング環境である「[ロブリック](https://robohon.com/apps/robrick.php)」で使える，ちょっと気の利いた関数ブロックを作って集めてみました。

## 使用方法

1. 追加したい関数ブロックのXMLファイルをダウンロードして，適当な場所に保存してください。
1. ロブリックで「設定」ボタンを押して，保存先が「デバイス」になっていることを確認してください。
1. ロブリックでご自身が作っているプログラムを開いた状態で，「読み込み」ボタンを押してダウンロードしたXMLファイルを読み込んでください。その際に「作成中のプログラムを削除しますか？」というダイアログが表示されるので，**「キャンセル」** ボタンを押してください。

## 気の利いた関数ブロック群

### 「指定したダンスを踊る」ブロック

[指定したダンスを踊る.xml](https://github.com/3110/robrick-convenience-functions/raw/main/%E6%8C%87%E5%AE%9A%E3%81%97%E3%81%9F%E3%83%80%E3%83%B3%E3%82%B9%E3%82%92%E8%B8%8A%E3%82%8B.xml)（リンクを右クリックして「名前を付けてリンク先を保存」）

「踊る」ブロックはプルダウンメニューからダンスを指定して踊らせますが，ダンスの名前を文字列で指定して踊らせることができるブロックです。

「踊る」ブロックでもプルダウンメニューから「ランダム」を選ぶことで，踊れるすべてのダンスからひとつをランダムに選んで踊らせることができますが，例えば「ロボホン体操」「ラジオ体操」「ロボホンズブートキャンプ」「ヲタ芸」の中からひとつをランダムに選んで踊らせたいといった使い方を想定しています。

現在，2023年12月21日までに追加されたダンスを指定することができます。

※2023年12月31日現在，ロブリック v2.12.0（2023年12月21日リリース）では「シャープ戦隊ロボレンジャー」は踊れません。

### 「連想配列からJSON文字列を作成」ブロック

[連想配列からJSON文字列を作成.xml](https://github.com/3110/robrick-convenience-functions/raw/main/%E9%80%A3%E6%83%B3%E9%85%8D%E5%88%97%E3%81%8B%E3%82%89JSON%E6%96%87%E5%AD%97%E5%88%97%E3%82%92%E4%BD%9C%E6%88%90.xml)（リンクを右クリックして「名前を付けてリンク先を保存」）

あらかじめ「JSON文字列から連想配列を作成」ブロックは用意されていますが，その逆の機能である「連想配列からJSON文字列を作成」するブロックが用意されていなかったので作成しました。

「ずっと覚えておく」ブロックで連想配列を覚えておく用途を想定しています。

引数に連想配列を渡すと，「JSON文字列から連想配列を作成」ブロックに渡せる文字列を生成します。ただし，キーの値はすべて文字列に変換されます。

### 「連想配列の値のリスト」ブロック

[連想配列の値のリスト.xml](https://github.com/3110/robrick-convenience-functions/raw/main/%E9%80%A3%E6%83%B3%E9%85%8D%E5%88%97%E3%81%AE%E5%80%A4%E3%81%AE%E3%83%AA%E3%82%B9%E3%83%88.xml)（リンクを右クリックして「名前を付けてリンク先を保存」）

「連想配列のキーのリスト」ブロックはありますが，連想配列の値のリストを返すブロクがなかったので作成しました。

## 参考

* [ロボホン用プログラミングツール ロブリック SR-SA04 利用マニュアル Version 1.4.0](https://robohon.com/apps/robrick/robrick-manual_v1-4-0.pdf)（シャープ株式会社）
