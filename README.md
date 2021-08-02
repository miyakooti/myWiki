# myWiki
備忘録です

<br>

### UIView
- [角を丸くするextension](https://github.com/miyakooti/myWiki/wiki/%E8%A7%92%E3%82%92%E4%B8%B8%E3%81%8F%E3%81%99%E3%82%8B)
- 
### UIButton

### UIColor
- [6桁の16進数でUIColorを初期化するextension](https://github.com/miyakooti/myWiki/wiki/6%E6%A1%81%E3%81%AE16%E9%80%B2%E6%95%B0%E3%81%A7UIColor%E3%82%92%E5%88%9D%E6%9C%9F%E5%8C%96%E3%81%99%E3%82%8B)
- 


### UILabel
- [正方形のラベルを円にするextension](https://github.com/miyakooti/myWiki/wiki/%E6%AD%A3%E6%96%B9%E5%BD%A2%E3%81%AE%E3%83%A9%E3%83%99%E3%83%AB%E3%82%92%E5%86%86%E3%81%AB%E3%81%99%E3%82%8B)
- [ラベルの文字に取り消し線をひく](https://github.com/miyakooti/myWiki/wiki/%E6%96%87%E5%AD%97%E3%81%AB%E5%8F%96%E3%82%8A%E6%B6%88%E3%81%97%E7%B7%9A%E3%82%92%E3%81%A4%E3%81%91%E3%82%8B)
- 


### UITableView
- 

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
- 
