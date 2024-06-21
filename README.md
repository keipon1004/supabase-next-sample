supabase db diff --use-migra -f public_schema
↑ローカルのダッシュボードのDBとマイグレーションファイルの差分を出力してくれる


supabase gen types typescript --local > schema.ts
ローカル環境のDBの型を作ってくれる
--localをつけなければ、リモートのプロジェクトのDBのかたを作る

supabase db push
migrationファイルを本番環境に反映させる


supabase db reset 
環境変数で繋がっている