# tutorial2_surface

このガイドに沿って作成：
https://sotrh.github.io/learn-wgpu/beginner/tutorial2-surface/

以下でビルドする
```bash
cd ../ # tutorial_windowディレクトリの一つ上の階層に移動する
wasm-pack build tutorial2_surface --target web
```

index.htmlを開くと、黒いウィンドウが表示される

Chromeで開くときは `--allow-file-access-from-files` オプションを使ってローカルのファイルを読み込めるようにする。

e.g.（コマンドプロンプト）
```
"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --allow-file-access-from-files
```

※Chromeのウィンドウをすべて閉じてからじゃないとオプションが適用されないかも

参考：
- [Windows版chromeでローカルファイルに直接アクセスする方法[オレ得JavaScriptメモ] | 56DOC BLOG](https://blog.56doc.net/Entry/809/)