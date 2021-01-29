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
     6. grep<br>
     (Ctrl+Shift+F)
  - メモ<br> 
     タグジャンプの使い勝手はvimでgtags使うのとあまり変わらないように感じますのでVSCodeでも導入推奨です.
