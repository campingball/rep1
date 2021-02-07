# rep1
リポジトリ①
「●GitHubの全体像
GreenMameのGitHubアカウントを開く

githubの機能説明：その①「Repositories」

「Repositories」はプロジェクトフォルダの様なものでプロジェクトにつきアプリ一つ。
例えばバックエンドアプリを入れたりフロントエンドアプリを入れたりできる。

例としてテキスト追加してみると例えば現在は「rep1」とだけ表示されているが、
鉛筆マーク押下し編集画面でテキストを追加「commit change」押下。
元の画面に戻るので右上「Blame」をクリックすると左欄にファイル名と変更日時が、
右欄に変更された内容が日時ごとに表示されているのが見れる。
中央欄の四角マークをクリックするとそれぞれの
コミット時履歴ごとの内容（ココではテキスト全文）を見ることができる。

これはメモ帳などのアプリも変更を保存できることに変わりはないが、
Githubの場合は変更日時ごとに内容を記憶していて簡単に閲覧したり
ロールバックすることも可能である。
「変更保存＝commit」

githubの機能説明：その②「master(main)とbranch」

コミット日時1、2、3...と「master(main)=本流」がある時に、
3で枝分かれすることを「branch=支流を作る」という。
必ず「master(main)=本流」に戻るという前提がある。

						 branch
						 |~~~~~|
					 .-------| 4.1 |-------.
					 |       |_____|       |
					 |                     |
					 |                     v
		|~~~~~|    |~~~~~|    |~~~~~|    |~~~~~|    |~~~~~|
	master  |  1  |--> |  2  |--> |  3  |--> |  4  |--> |  5  |
		|_____|    |_____|    |_____|    |_____|    |_____|

githubの機能説明：その②「issues」

プロジェクトTOP画面(https://github.com/campingball/rep1)にはいろいろタブ
があるが。「issues」タブ内では「課題を作る」事ができる。
掲示板のスレッドの様な感じ？
例えば、接触確認アプリのココアのRepositoriesに入るとして「NewIssues」
ボタンを押下し、タイトルに「androidでは接触確認ができません」などと問題を
指摘したりする事ができる。
