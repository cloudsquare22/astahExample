<a href="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_01.png"><img src="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_01-1024x786.png" alt="" width="1024" height="786" class="alignnone size-large wp-image-2185" /></a>

<a href="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_04.png"><img src="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_04.png" alt="" width="826" height="346" class="alignnone size-full wp-image-2186" /></a>

<h3>画面</h3>
<a href="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_02.png"><img src="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_02.png" alt="" width="243" height="199" class="alignnone size-full wp-image-2181" /></a>

- 状態を使用
- 名前は画面名

<h3>遷移</h3>
<a href="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_03.png"><img src="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_03.png" alt="" width="618" height="164" class="alignnone size-full wp-image-2184" /></a>

- 遷移を使用</li>
- トリガーに遷移契機を記述
〇〇釦押下
△△メニュー選択
- 遷移に条件がある場合、ガード条件に記述

<h3>アクション</h3>
<a href="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_02.png"><img src="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_02.png" alt="" width="243" height="199" class="alignnone size-full wp-image-2181" /></a>

- 画面処理概要をアクションに記述
- entry：遷移時の実行処理
- do：画面表示中の実行処理
- exit：終了時の実行処理

<h3>画面遷移図分割</h3>
<blockquote>画面が多くなった場合の分割</blockquote>
<a href="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_05.png"><img src="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_05.png" alt="" width="298" height="196" class="alignnone size-full wp-image-2188" /></a>

<a href="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_04.png"><img src="http://www.cloudsquare.jp/kumonosu/wordpress/wp-content/uploads/2019/11/ScreenTransition_04.png" alt="" width="826" height="346" class="alignnone size-full wp-image-2186" /></a>

- サブマシン状態を使用
- サブマシン名に別ステートマシン図を記述(include)
- 別ステートマシン図は開始疑似状態と終了状態で入出を記述
