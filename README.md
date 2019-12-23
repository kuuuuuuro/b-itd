# test2
テスト用のリポジトリです
やったね！

    <nav class="navbar navbar-inverse navbar-fixed-top col-xs-12 col-sm-12 col-md-8 col-md-offset-2 col-lg-6 col-lg-offset-3">
    <div class="container-fluid">
      <!--ヘッダー部-->
      <div class="navbar-header">
      <button class="navbar-toggle collapsed" data-toggle="collapse" data-target="#target">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a href="#" class="navbar-brand" style="pointer-events:none;">顧客管理</a>
      </div>
      <!--ナビゲーション部-->
      <div class="collapse navbar-collapse" id="target">
      <ul class="nav navbar-nav">
         <li class=""><a href="#" onclick="gotoURL('../CGI/MEDIA_LIST.EVENT_SHUZAI.CGI','_self');return false">
           <span class="glyphicon glyphicon-volume-up" aria-hidden="true" style="margin-right:5px;"></span>イベント取材</a></li>
         <li class="active"><a href="#" onclick="gotoURL('../CGI/MEDIA_LIST.INI.CGI','_self');return false">
           <span class="glyphicon glyphicon-user" aria-hidden="true" style="margin-right:5px;"></span>顧客情報</a></li>
         <li class=""><a href="#" onclick="gotoURL('../CGI/MEDIA_LIST.EVENT_SET.CGI','_self');return false">
           <span class="glyphicon glyphicon-cog" aria-hidden="true" style="margin-right:5px;"></span>イベント管理</a></li>
      </ul>
      <!--ユーザ情報-->
      <ul class="nav navbar-nav navbar-right">
          <li><a href="#" style="pointer-events:none;"><span class="glyphicon glyphicon-user" aria-hidden="true"></span> ###DISPUSER###</a></li>
      </ul>
      </div>
    </div>
    </nav>
