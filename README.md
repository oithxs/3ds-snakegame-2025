# 3ds-game-2025
3DS Game in Kitayama Festival

# Getting Started
開発環境を構築するために以下の手順に従ってください。
1. 開発キットである[DevKitPro](https://devkitpro.org/wiki/Getting_Started#Windows)をインストールしてください。
1. 3DSエミュレータである[citra](https://citra-emulator.com/)をインストールしてください。
1. MSys2がインストールされているので立ち上げて、`C:\devkitPro\examples\3ds\templates\application`まで移動してください。
1. `application`ディレクトリ配下で`make`コマンドを実行し、`3dsx`ファイルを作成してください。
1. `citra-qt.exe`を実行し、`ファイル->ファイルを開く`から先ほど作成した`3dsx`ファイルを開いてください。
1. `Hello, world!`が表示されたら導入完了です！
1. (Option) 3dsxファイルを開くソフトウェアに`citra-qt.exe`を指定してあげると幸せになります。
