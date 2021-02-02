Gitは開発者の究極のレポートツール


$ git init
localのレポートの準備

$ git add ファイル名 or path
保存範囲の選択
よく使うのが git add .

$ git commit -m"メッセージ"
メッセージつきでコードの情報を保存(レポート)


githubと連携するには
1. githubでrepositoryを作成
$ git remote add origin https://github.com/tsujisakahideki/discount.git
で連携

$ git push origin ブランチ名
remote addで登録したoriginにファイルをupload

(push/pull)
