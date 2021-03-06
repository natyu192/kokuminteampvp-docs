Destroy the Monument
======================

**Destroy the Monument** モードでは、チームが特定の範囲のブロック(モニュメント)を全て壊すことで勝利となります。

モニュメントの範囲はこのように定義します。

::

	monuments:
	  redfront:
	    team: red
	    name: 'Front'
	    pos1:
	      x: 33
	      y: 42
	      z: 0
	    pos2:
	      x: 33
	      y: 44
	      z: 0
	  redback:
	    team: red
	    name: 'Back'
	    pos1:
	      x: 33
	      y: 42
	      z: -33
	    pos2:
	      x: 33
	      y: 44
	      z: -33

``redfront`` や ``redback`` は内部で処理するための ID なので、 **半角英数字** であれば何でも設定できます。

================= ====================================== ===================================== =============
項目(\*は必須)    説明                                   値                                    デフォルト値
================= ====================================== ===================================== =============
\*team            モニュメントを壊すチームの ID 。       チーム ID
\*name            Scoreboardに表示される名前。重複可能。 文字列
\*pos1            モニュメントの範囲の地点1。            X, Y, Z
\*pos2            モニュメントの範囲の地点2。            X, Y, Z
================= ====================================== ===================================== =============

