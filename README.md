# Serverless scraping
完全サーバレス
GitHub ActionsのCronで定期的に市営住宅募集ページをスクレイピングしている
スクレイピングで取得したデータをdata_txtファイルへ書き出し
２回め以降はtxtファイルとの差分があれば夫婦共通のLINEアカウントへ通知するようにしている

## Current function
住んでいる地域の市営住宅の募集状況をスクレイピング
