==================
キーバインディング
==================

現在 Cursive のアクションはショートカットをアサインされていません。全てのプラットフォームで既存のアクションとコンフリクトさせないようにするのがとても難しいためです。しかしながら、あなたは ``Settings`` -> ``Other Settings`` -> ``Clojure`` -> ``Keybindings`` の設定ページを使うことでワンステップでキーバインディングを設定することができます。

``Keybindings`` パネルは一般的なアクションのキーマッピングを変更することが出来ません。それらは IntelliJ の ``Settings`` -> ``Keymap`` パネルから見つけることができます。

.. image:: /image/cursive_keybindings/keybindings.png

もしあなたがまだ何もキーバインディングを設定しないのなら、おそらくデフォルトのキーマップを選択しているはずです。それは修正することができないので、 Cursive はあなたに警告をしキーマップの設定ページへのリンクを提供します。あなたは任意のデフォルトキーマップをコピーすることができ、それからあなたはコピーしたキーマップを自分好みに編集して更新することができます。 Mac を使っている方には Mac OS X 10.5+ のキーマップを使うことを、古い Mac OS X のキーマップよりも推奨しています。

Cursive は今ふたつのデフォルトキーバインディングを持っています。ひとつは私たちが Cursive で使っているもので、ひとつは Emacs 由来のものです。あなたは好きな方を選ぶことができ、 Apply ボタンを押すことでそれを全て適用することができます。 Cursive 自動的に設定されていないキーバインドを選択します。つまり、それはあなたが手動でチェックボックスのチェックを入れない限り、あなたが設定したかもしれないものを上書きしないようにするということです。既にカスタマイズされていて違うキーバインドを設定しようとすると青色でマークされます。

多くのアクションが既存の IntelliJ アクションとコンフリクトするでしょう。あなたは ``Show`` リンクからコンフリクトの状況を確認できます。また同様に ``Remove?`` チェックボックを選択していればキーバインドを削除することができます。しかし、これが必要になることはないはずです。 Cursive アクションは優先度を持っているので Clojure のコンテキストの場合には動作し、それ以外のコンテキストでは実行されません。
