# ダウンロードの仕方
このWebページの右側にReleasesという項目があるので、そこから行ける先で最新のZipをダウンロードしてください。

# 対応aviutlバージョン
aviutl1.10 + 拡張編集0.92 でのみデバッグしております。  
他の環境での動作は保証しません。  
が、どうやら aviutl1.10 + 拡張編集0.93rc1 でも動くようです。

※拡張編集0.93rc1でのバグも直すつもりがあるので、バグを見つけたら教えてください

# 規約
このツール、またはこのツールに含まれるファイルを使用して作った動画を公開する場合
* ニコニコ動画で公開するなら  
コンテンツツリーの親作品に、下記動画を登録してください。  
* 他のサイトで公開するなら  
動画説明欄などに、下記動画へのリンクを掲載してください。

動画URL：https://www.nicovideo.jp/watch/sm39708120

手間なのは承知しておりますが、このツールを多くの動画製作者に周知し、楽をしていただくためとなります。よろしくお願いいたします。

# このツールが解決すること
オブジェクトの設定ダイアログにフィルタを沢山追加すると、画面下から飛び出ちゃうじゃないですか。

ダイアログを幅広にすることで、画面外に飛び出ないようにしました。

# どう解消するのか
WideDialog.aufを、aviutl.exeと同じフォルダに入れる。  
または、他のプラグインと同じフォルダ（aviutl/pluginsフォルダ）に入れる。  
特に設定などはありません。

# 参考動画
ツール解説動画  
https://www.nicovideo.jp/watch/sm39708120

# バグ報告
https://twitter.com/suzune25254649

こちらまで、DMやリプで報告をくださると凄く喜びます。（バグはなるべく直したい）

ワイドダイアログプラグインは、設定ダイアログを幅広にするだけで、他の動作に影響を与えないことを目指しています。  
そのため、導入前には起きず、導入後には起きる不都合は全て、バグと考え報告していただけると助かります。

# 断り書き
このツールは規約を守る範囲で自由にお使いください。  
ただし、このツールを利用した際に発生した いかなる損失や損害が発生についても、作者は一切の責任を負いかねます。

# 更新履歴

## v1.01
- フィルタのチェックボックスなど、一部のUIが正しく表示されないバグを修正
- フィルタのボタンのうち、新たにダイアログが開くボタンを押した際に操作不能になるバグを修正

# ライセンス
* AviUtlPluginSDK License

The MIT License

Copyright (c) 1999-2012 Kenkun

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

* Lua License
-----------

Lua is licensed under the terms of the MIT license reproduced below.
This means that Lua is free software and can be used for both academic
and commercial purposes at absolutely no cost.

For details and rationale, see http://www.lua.org/license.html .

===============================================================================

Copyright (C) 1994-2012 Lua.org, PUC-Rio.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

===============================================================================
