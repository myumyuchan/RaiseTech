## 第3回講座
### サンプルアプリケーション起動時  
![起動時ブラウザ画面①](/image/lecture3_deploy1.png)  
![起動時ブラウザ画面②](/image/lecture3_deploy2.png)  

### 1. AP サーバーについて調べる
- AP サーバーの名前とバージョン  
名前：Puma  
バージョン：6.4.2  
![APサーバの名前とバージョン](/image/lecture3_APinfo.PNG)  

- AP サーバーを終了させた場合、引き続きアクセスできますか？  
⇒できない   
![APサーバ終了時①](/image/lecture3_PumaShutdown.PNG)  
![APサーバ終了時②](/image/lecture3_APstop.png)   
  
### 2. DB サーバーについて調べる
-  DB サーバー（DB エンジン）の名前と Cloud9 で動作しているバージョン  
名前：MySQL  
バージョン：8.4.4  
![DBサーバの名前とバージョン](/image/lectire3_DBinfo.PNG)
  
- DB サーバーを終了させた場合、引き続きアクセスできますか？  
⇒できない   
![DBサーバ終了時](/image/lecture3_DBstop.png)  
  
- Rails の構成管理ツールの名前  
Bundler  
### 第3回課題で学んだこと
普段何気なく利用しているWebサイトやアプリケーションを作成する側が  
実際にどのような作業をしているか流れを把握することができました。  
またGitHubを使用して課題を提出することで前回の課題の復習をすると共に  
新たにMarkdownでの画像埋め込み方法を学ぶことができました。