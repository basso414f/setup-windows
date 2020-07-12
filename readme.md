# setup

- [ ] タスクバーを小さくする
- [ ] タスクバーをすべてのディスプレイに表示する：オフ
- [ ] タスクバーに表示するアイコンを選択します
  - [ ] 常にすべてのアイコンを表示する：チェックを外す
  - [ ] 電源、ネットワーク、音量、OneDriveくらい
- [ ] 電源オプション
  - [ ] コンピュータをスリープ状態にする：適用しない
  - [ ] カバーを閉じたときの動作：何もしない

# install

- [ ] スマホ同期アプリ？


- [ ] install chocolatey
  - https://chocolatey.org/install
  - `choco install .\package.config -y`
  - `choco install .\package.private.config -y`

- [ ] google japanese input
- [ ] python3はすでにWindowsにInstallされている
- [ ] ttclock

## ttclock

- デザイン-1
  - 描画エフェクト
    - 影をつける：オフ
    - グラデーション：オフ
- デザイン-2
  - フォント
    - フォント名：Arial
    - サイズ：9pt
- 書式設定
  - 書式： `\M/\D(\A)\n\h:\m:\s`
  - ユーザー定義文字：日～土曜日を漢字に変更
- 一般
  - マウスの左ボタンで時計をクリックしたときに以下の動作を行う
    - シングルクリック：カレンダーを表示

## Everything

- [検索データ]-[除外]
  - 隠しファイルとフォルダを除外する：オン
  - システムファイルとフォルダを除外する：オン
  - C:\users\%username%\appdata
  - C:\Windows
  - C:\Program Files
  - C:\Program Files (x86)

## Google IME

- MS-IMEをカスタマイズする

|     mode     | key |   command   |
| ------------ | --- | ----------- |
| 入力文字なし | F13 | IMEを有効化 |
| 変換前入力中 | F13 | IMEを有効化 |
| 直接入力     | F13 | IMEを無効化 |

# Folder
- [ ] 表示
  - [ ] ファイル名拡張子：オン
  - [ ] 隠しファイル：オン

# pip

```posh
setx PATH "$env:Path;%USERPROFILE%\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.7_qbz5n2kfra8p0\LocalCache\local-packages\Python37\Scripts"
pip install --upgrade  pip
```

# dotfiles

```posh
New-Item -Path ~ -Name .gitconfig -Value ~\Dropbox\dotfiles\.gitconfig -ItemType HardLink
New-Item -Path ~ -Name .ssh -Value ~\Dropbox\dotfiles\.ssh -ItemType Junction
New-Item -Path ~ -Name .aws -Value ~\Dropbox\dotfiles\.aws -ItemType Junction
New-Item -Path ~ -Name .azure -Value ~\Dropbox\dotfiles\.azure -ItemType Junction
New-Item -Path ~ -Name .config -Value ~\Dropbox\dotfiles\.config -ItemType Junction
New-Item -Path ~ -Name .vscode -Value ~\Dropbox\dotfiles\.vscode -ItemType Junction
New-Item -Path ~ -Name .mume -Value ~\Dropbox\dotfiles\.mume -ItemType Junction
```

# AverMedia

## GG553をセットアップする

- 色々刺す
- [AverMedia公式サイト](https://www.avermedia.co.jp/download/index.html)にアクセスし、GC553対応のキャプチャーソフトウェア、ユーザーズマニュアルなどをダウンロードする

## PowerDirector 15 (4K対応)

- [『Cyberlink PowerDirector 15 for AVerMedia』 取得、及び、ライセンスキーの登録方法について](http://q.avermedia.com/cyberlink-jp)にアクセス
- PowerDirector（4K対応）をインストール
- ライセンスは[CyberLink メンバーサイト](https://membership.cyberlink.com/prog/member/sign-in.do)を参照

# OBS

- Chocolateyでインストール


# Splatoon系のツール

- [SplashGo!](https://twitter.com/SplashGo0812)
- [StreamingWidget](https://twitter.com/sisno_boomx/status/1281970294421245952?s=21)

### 権利用の文言

> ▽オーバーレイスクリプト配布: SplashGo!(スプゴー)様
> https://twitter.com/SplashGo0812

> ▽Splatoon2のストリーマー用ツール配布: sisno_boomx様
> https://twitter.com/sisno_boomx
