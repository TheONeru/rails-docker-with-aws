# rails-docker-with-aws

<p>参考にしたページ(ほぼパクリ) https://qiita.com/saitoeku3/items/b1aa2ae143624e551aea</p>

<p>1.docker-compose run web bundle exec rails new . --force --database=mysql --skip-bundle<p>
 
<p>2.config/database.ymlの&defaultの項のhostをlocalhostからdbに書き換え</p>

<p>3.docker-compose build</p>

<p>4.docker-compose up<p>
  
<p>5. CromeなどのWebクライアントのアドレスバーに"localhost:3000"を入力し，Railsアプリのテンプレートが表示されることを確認する</p>

<img border="0" src="https://cdn-ak.f.st-hatena.com/images/fotolife/k/kisokoji/20180131/20180131090648.png" alt="rails_temp">
