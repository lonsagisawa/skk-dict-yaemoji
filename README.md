# skk-dict-yaemoji

SKK Dictionary of (Yet Another) Emoji

[既存のSKK絵文字辞書](https://github.com/uasi/skk-emoji-jisyo)がなんだかコレジャナイ人のためのSKK辞書

## おことわり

* この辞書はUnicodeの仕様であるスキントーンには対応しません(スキントーンに対応する絵文字はすべてスキントーンなしの状態で変換され、その表示結果は各デバイスにより異なります)。**スキントーンつきの絵文字を変換できないことに問題がある場合、この辞書の使用をただちに中止してください。またそれによる各種損害、あるいは精神的苦痛等につきまして作者は一切の責任を負いかねますので、あらかじめご了承ください。**
* この辞書はUTF-8で作成されています。UTF-8に対応しないSKK実装では使用できません。
* この辞書はUnicodeのあらゆる絵文字をカバーすることを目的とはしておりません。現在Unicodeの仕様上実装されているすべての絵文字を確認するには、[Unicodeの公式Webサイト](http://unicode.org/emoji/charts/full-emoji-list.html)をご確認ください。  
動物系など種類が無数にあるものの収録基準は、「docomo/au/SBMのいずれかのガラケーに収録されていたか」「コミュニケーションを円滑に行ううえで有用か」「macOS 10.12.1+Google Chrome 54の環境において、仕様書上で正常に表示されたか」です。また「○○をする人」系の絵文字は種類が膨大にあるうえ、前述のスキントーン非対応の方針上問題が出る可能性を排除するという観点から収録を控えています。

## ダウンロード

[master.zip](https://github.com/mlny/skk-dict-imascgss/archive/master.zip)

もしくはgitがインストールされている環境で

```
$ git clone https://github.com/mlny/skk-dict-imascgss.git
```

## つかいかた

### [SKK日本語入力FEP](http://coexe.web.fc2.com/programs.html)

```
C:\Windows\IME\SKK0\DICTS
```
の下に辞書をコピーします。「かお」「ねこ」などで絵文字が出てきたらOKです。

### [AquaSKK](https://github.com/codefirst/aquaskk)

1. 設定画面を開き、辞書タブを開きます。
2. 追加 を押します。
3. 辞書の種類をSKK 辞書(UTF-8)にします。
4. 場所の選択... を押し、ダウンロードした辞書を選択します。
5. codefirst版AquaSKKを使用していない、もしくはAquaSKK 4.4.0以前のバージョンをお使いの場合、「場所」の先頭にある*file:/*を削除します(この挙動は[AquaSKK 4.4.1で修正されました](https://github.com/codefirst/aquaskk/issues/55))。
6. 「かお」「ねこ」などで絵文字が出てきたらOKです。

## ライセンス

[MIT License](https://github.com/mlny/skk-dict-imascgss/blob/master/LICENSE)