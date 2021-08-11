# myWiki
備忘録

<br>

### UIView
- [角を丸くするextension](https://github.com/miyakooti/myWiki/wiki/%E8%A7%92%E3%82%92%E4%B8%B8%E3%81%8F%E3%81%99%E3%82%8B)
- 
### UIButton
- [かどまる](https://github.com/miyakooti/myWiki/wiki/%E8%A7%92%E4%B8%B8)

### UIColor
- [6桁の16進数でUIColorを初期化するextension](https://github.com/miyakooti/myWiki/wiki/6%E6%A1%81%E3%81%AE16%E9%80%B2%E6%95%B0%E3%81%A7UIColor%E3%82%92%E5%88%9D%E6%9C%9F%E5%8C%96%E3%81%99%E3%82%8B)


### UIImage
- [UIImageをURLで初期化するextension](https://github.com/miyakooti/myWiki/wiki/UIImage%E3%82%92URL%E3%81%8B%E3%82%89%E7%94%9F%E6%88%90)
- Nukeはまじで楽



### UILabel
- [正方形のラベルを円にするextension](https://github.com/miyakooti/myWiki/wiki/%E6%AD%A3%E6%96%B9%E5%BD%A2%E3%81%AE%E3%83%A9%E3%83%99%E3%83%AB%E3%82%92%E5%86%86%E3%81%AB%E3%81%99%E3%82%8B)
- [ラベルの文字に取り消し線をひく](https://github.com/miyakooti/myWiki/wiki/%E6%96%87%E5%AD%97%E3%81%AB%E5%8F%96%E3%82%8A%E6%B6%88%E3%81%97%E7%B7%9A%E3%82%92%E3%81%A4%E3%81%91%E3%82%8B)
- セクションとセルの関係は、２次元配列に対応している。


### UITableView
- モデルの情報を全てセル側の変数に読み込んであげると、後々楽
- [カスタムセルのidentifierを管理しやすくする](https://qiita.com/miyakooti/items/c06d18e3685a8faa68ce)

### UIPickerView
- 

### UITabbarController
- 

### UISwitch
- [ラベルの付いたスイッチ](https://github.com/Cookiezby/LabelSwitch)
- （↑の補足） LabelSwitchの大きさは、文字の大きさに比例している。
- UISwitchにラベルを入れることは容認されていないらしい→[apple公式](https://developer.apple.com/design/human-interface-guidelines/ios/controls/switches/)


### UINavigationController

### UIGestureRecognizer
- [コードで設置できる](https://i-app-tec.com/ios/uigesturerecognizer.html)

### tips
- constantsはenumで定義すると良い(enum VCTypeみたいな感じにして、VCTypeに応じるプロパティを出力できるようにする。タイトルとか。)
- [JSONEncoder（マジでクソ便利なものを作ってしまった、、）](https://github.com/miyakooti/myWiki/wiki/JSONEncoder.swift)
- [現在日時（時刻）の取得](https://github.com/miyakooti/myWiki/wiki/%E7%8F%BE%E5%9C%A8%E6%99%82%E5%88%BB%E3%81%AE%E5%8F%96%E5%BE%97%EF%BC%88NSDate%EF%BC%89)
- CGRect = CGSize + CGPoint
- →[それぞれをViewに対して使用した例](https://program-life.com/198)
- [tableViewのヘッダは、HeaderFooterViewでカスタムできる話](https://qiita.com/KikurageChan/items/e1847b54535df393d893)
- 小さな機能の実装を積み重ねていくと、修正箇所が明確になりサクサク作れる
- リストのうち値が0のものを抽出する、みたいなことはfilterでできる
- 下から出てくるのは総称してアクションシートと呼ぶ。SNS共有とかUIAlertViewControllerのやつとか
- ctr + 6 でモジュール内のプロパティ一覧が見れる
- 当たり前かもだけど、viewDidLoad()はtableViewのデリゲートメソッドよりも早く呼ばれる。
<img width="476" alt="スクリーンショット 2021-08-11 23 27 40" src="https://user-images.githubusercontent.com/60727025/129047499-7008ad31-c5c2-41cf-8adf-fed485bb4dfe.png">


### Figma（デザイン）
- [便利UIパーツ](https://www.figma.com/community/file/858143367356468985)
- [UI改修のためのヒント](https://developer.apple.com/design/human-interface-guidelines/ios/controls/switches/)
- コンポーネントで共通化できる。

### UI設計
- アイデアは書き起こした上で取捨選択をすることで、改善させていく。
- クライアントの知識に合わせて、直感性を調整する
- ふわっとしているように思えるけど、実は結構論理的。「なぜこのデザインにしたか」は説明できるようにしないといけない。
- ５とか１０とかインプットして、５０とか１００とかアウトプットして、そこから取捨選択していく。
- UISwitchは「動作」ではなく「状態」のイメージ。（apple公式ドキュメントより）

### 学習したいこと
- MVVM
- [x]ios設計パターンを読む
- MySQLとアプリの接続
- 自作API（rest）
- デザイン全般
- gitを体系的に学習
- リーダブルコードを読む
