# VSCodeノウハウ

- gtags導入
  - GNU Globalインストール
     ```
     $ sudo apt install global
     ```
     下記にインストールされているはず<br>
     状況によっては自分でビルドしてインストールしてくださいね<br>
     /usr/bin/gtags<br>
     /usr/bin/gtags<br>
     
  - extensionインストール
     - apanese Language Pack for Visual Studio Code
     - C/C++
     - CMake
     - CMake Tools
     - C++ Intellisense
     - C/C++ GNU Global<br>

  - 使い方
     1. タグ生成<br>
     コマンドパレットで「Global: Rebuild Gtags Database」<br>
     もしくは、コマンドで「gtags」
     2. 定義元へジャンプ<br>
     (F12)
     3. 定義先へジャンプ<br>
     (Shift + F12)
     4. カーソル移動<br>
     (F12)で下<br>
     (Shift)+(F12) で上
     5. ユーザーガイド<br>
     https://marketplace.visualstudio.com/items?itemName=jaycetyle.vscode-gnu-global

- ショートカット集
     - 戻る 			      Ctrl + Alt + - <br>
     - 進む 			      Ctrl + Shift + \ <br>
     - ファイルの移動 		 Ctrl + Tab <br>
     - ファイル内検索 		 Ctrl + F <br>
     - ワークスペース検索 	Ctrl + Shift + F <br>

- settings.json
  - settings.jsonの置き場所(Linux)
    ```
    $HOME/.config/Code/User/settings.json
    ```
    設定ファイルは[こちら](https://github.com/lef2/treefrog_practice/blob/master/doc/00_vscode/settings/)
