<template>
<!DOCTYPE html>
<html lang="ja">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>ポートフォリオサイト</title>
    <!-- BootstrapのCSS読み込み -->
    <!-- jQuery読み込み -->
    <script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
    <!-- BootstrapのJS読み込み -->
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">

    <!-- Optional theme -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
    
    <!-- Latest compiled and minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
    
    <!-- chart.js -->
    <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.2.2/Chart.js"></script>
    
    <script src="https://use.fontawesome.com/4a5c519a7b.js"></script>
    
    <link rel="stylesheet" href="style.css" type="text/css" />
    
    <meta name="description" content="tbkoo53のポートフォリオです。過去に制作したプロジェクトや現在進行中のプロジェクトを紹介しています。将来的には、エンジニアに転職もしくはフリーランスとして活動をしていきたいと考えています。 最近は英語の勉強もやっています。">
  
  </head>
  <body>
  <nav class="navbar navbar-inverse navbar-fixed-top">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">ポートフォリオサイト</a>
        </div>
        <div id="navbar" class="navbar-collapse collapse">
          <div class="icons pull-right" style="margin-top: 10px;">
            <ul>
              <a href="https://github.com/tbkoo53"><i class="fa fa-github fa-2x" aria-hidden="true"></i></a>
              <a href="#"><i class="fa fa-twitter fa-2x" aria-hidden="true"></i></a>
              <a href="#"><i class="fa fa-facebook fa-2x" aria-hidden="true"></i></a>
            </ul>
        </div>
        </div><!--/.navbar-collapse -->
      </div>
    </nav>

    <!-- Main jumbotron for a primary marketing message or call to action -->
    <div class="jumbotron">
      <div class="container">
        <h1>アイデアをカタチに</h1>
        <p>あなたのアイデアをカタチにするお手伝い</p>
        <p><a class="btn btn-success btn-lg" href="#" role="button">お問い合わせ</a></p>
      </div>
    </div>

    <div class="container">
      <!-- Example row of columns -->
      <div class="row">
        <div class="col-md-12">
          <h3>制作物</h3>
          過去に制作したプロジェクトや現在進行中のプロジェクトです。
          詳細からご覧ください。
        </div>
      </div>
      <div class="row">
        <div class="col-xs-4">
          <h4>メッセージボード</h4>
          <p><img src="http://placehold.jp/280x130.png" alt="プロジェクト"></p>
          <p><a class="btn btn-default" href="#" role="button">詳細 &raquo;</a></p>
        </div>
        <div class="col-xs-4">
          <h4>Twitterクローン</h4>
          <p><img src="http://placehold.jp/280x130.png" alt="プロジェクト"></p>
          <p><a class="btn btn-default disable" href="#" role="button">詳細 &raquo;</a></p>
        </div>
        <div class="col-xs-4">
          <h4>モノリスト</h4>
          <p><img src="http://placehold.jp/280x130.png" alt="プロジェクト"></p>
          <p><a class="btn btn-default" href="#" role="button">詳細 &raquo;</a></p>
        </div>
        <div class="col-xs-4">
          <h4>オリジナルサービス</h4>
          <p><img src="http://placehold.jp/280x130.png" alt="プロジェクト"></p>
          <p><a class="btn btn-default" href="#" role="button">詳細 &raquo;</a></p>
        </div>
        <div class="col-xs-4">
          <h4>Comming Soon...</h4>
          <p><img src="http://placehold.jp/280x130.png" alt="プロジェクト"></p>
          <p><a class="btn btn-default" href="#" role="button">詳細 &raquo;</a></p>
        </div>
        <div class="col-xs-4">
          <h4>Comming Soon...</h4>
          <p><img src="http://placehold.jp/280x130.png" alt="プロジェクト"></p>
          <p><a class="btn btn-default" href="#" role="button">詳細 &raquo;</a></p>
        </div>
      </div><!--row -->
      
      
       <h3>My History</h3>
       <div class="container">
         <div class="row">
          <div class="col-md-8">
            <div class="table-responsive">
	<table class="table">
		<thead>
			<tr>
				<th>年</th>
				<th>ひとこと</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<th>2009</th>
				<td>高校卒業</td>
			</tr>
			<tr>
				<th>2010</th>
				<td>福岡で１年間過ごす</td>
			</tr>
			<tr>
				<th>2011</th>
				<td>WEBデザインを勉強しはじめる</td>
			</tr>
			<tr>
				<th>2016</th>
				<td>TechAcademyで学習を開始！</td>
			</tr>
		</tbody>
	</table>
</div>

          </div>
          <div class="col-md-4 col-xs-4">
          <img src="http://placehold.jp/250x200.png" class="img-thumbnail" alt="profile">
          将来的には、エンジニアに転職もしくはフリーランスとして活動をしていきたい。
          趣味は、楽器を弾く、バイクでツーリング、寝ること。
          最近は英語の勉強もやっています。
        　</div>

        </div>
       </div> 
    
      <hr>
      
      <!-- Form -->
      <h3>お問い合わせ</h3>
      <div class="container">
  <div class="row">
    <div class="col-sm-2">お名前</div>
    <div class="col-sm-10 form-inline" style="padding: 3px;">
      <input type="text" class="form-control input-sm" id="name" placeholder="お名前" size="20">
    </div>
  </div>
  <div class="row">
    <div class="col-sm-2">フリガナ</div>
    <div class="col-sm-10 form-inline" style="padding: 3px;">
      <input type="text" class="form-control input-sm" id="kana" placeholder="フリガナ" size="20">
    </div>
  </div>
  <div class="row">
    <div class="col-sm-2">都道府県</div>
    <div class="col-sm-10 form-inline" style="padding: 3px;">
      <select class="form-control input-sm" id="pref">
        <option>お選び下さい</option>
      </select>
    </div>
  </div>
  <div class="row">
    <div class="col-sm-2">Email</div>
    <div class="col-sm-10 form-inline" style="padding: 3px;">
      <input type="text" class="form-control input-sm" id="email" placeholder="Email" size="30">
    </div>
  </div>
  <div class="row">
    <div class="col-sm-2">ご意見をどうぞ</div>
    <div class="col-sm-10" style="padding: 3px;">
      <textarea class="form-control  input-sm" rows="3" id="comment" placeholder="ご意見をどうぞ"></textarea>
    </div>
  </div>
   
  <div class="text-center" style="padding: 30px;">
    <button type="button" class="btn btn-success">送信内容の確認 <span class="glyphicon glyphicon-chevron-right"></span></button>
  </div>
</div>

      <footer>
        <p>&copy; 2016 ポートフォリオ</p>
        
        
      </footer>
    </div> <!-- /container -->
  </body>
</html>
</template>
