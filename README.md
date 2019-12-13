# learning-docker: Dockerの練習

## ミニレポート

### Q1-1: 同じ `docker container run` コマンドを2回実行すると、1回目と2回目で違いはありますか？どう違いますか？

【回答欄】1回目はダウンロードのようなものが始まりそれが完了すると'Hello world'とでたが2回目はダウンロードのようなものがなくすぐに'Hello world'とでた

### Q1-2: なぜ違いますか？

【回答欄】1回目にダウンロードのようなものを済ませたから

### Q1-3: `docker container ls` と `docker container ls -a` はどう違いますか？

【回答欄】docker container lsは起動しているコンテナだけを見ることができるがdocker container ls -aは全てのコンテナを見ることができる。

### Q1-4: `docker image ls` と `docker container ls -a` はどう違いますか？（間違ってもいいので、自分の考えを述べてください）

【回答欄】docker image lsはイメージの一覧を見ることができdocker container ls -aは使われていないイメージの一覧を見ることができる。

### Q1-5: `ubuntu` イメージでの `cat /etc/issue` の結果をペーストしてください

【回答欄】Ubuntu 18.04.3 LTS \n \l

### Q1-6: `docker image ls` と `docker container ls -a` はどう変化しましたか？

【回答欄】docker image lsあまり変わっていること路が見られなかった docker container ls -aは1行だけ増えていた。

### Q2-1: `-d` (デタッチド・モード) でコンテナを起動すると、どのような状態になりましたか？

【回答欄】デタッチド・モードで起動したコンテナも終了する。デタッチド・モードのコンテナは停止しても自動的に削除できない。

### Q2-2: http://localhost/ をブラウザで開くと、何が表示されましたか？

回答欄】Welcome to nginx!と表示されその下に五行程度の英文が表示されていた。

### Q2-3: コンテナの起動時と終了時で、docker container ls -a はどのように変化しましたか？

【回答欄】8行だったのが12行になっていて4行追加されたことがわかった。

### Q3-1: `docker build -t sample-image .` 実行時に表示されている `building...` は、Dockerfileのどの行から実行されましたか？

【回答欄】8行目に実行された

### Q3-2: `docker run sample-image` を実行すると、どうなりましたか？

【回答欄】Hello, from Docker container!と表示された。
