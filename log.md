# 100 Days Of Code - 学習ログ

## X日目: 2020年XX月XX日

XXH/ total:XXH

### 今日の進捗
テンプレ

### 思ったこと
テンプレ

### 参考URL
テンプレ


## 13日目: 2020年4月27日

1.0H/ total:13.0H

### 今日の進捗

### 思ったこと

### 参考URL
https://qiita.com/rubytomato@github/items/78087a2c69389f642760

### 今日の進捗

## 12日目: 2020年4月26日

3.0H / total:12.0H

**今日の進捗**:１年が残り何分かを計算するだけのアプリを作った
https://sol525600min.web.app/

**思ったこと**:
create-nuxt-app に失敗していた。
```
$ npx create-nuxt-app 525600min

create-nuxt-app v2.15.0
✨  Generating Nuxt.js project in 525600min
Trace: { Error: EACCES: permission denied, open '/Users/edapiyo/Library/Preferences/sao-nodejs/config.json.3385132208'
    at Object.openSync (fs.js:443:3)
    at Function.writeFileSync [as sync] (/Users/edapiyo/.config/yarn/global/node_modules/write-file-atomic/index.js:212:13)
    at Conf.set store [as store] (/Users/edapiyo/.config/yarn/global/node_modules/conf/index.js:168:19)
    at Conf.set (/Users/edapiyo/.config/yarn/global/node_modules/conf/index.js:82:14)
    at SAO.run (/Users/edapiyo/.config/yarn/global/node_modules/sao/lib/index.js:81:13)
  errno: -13,
  syscall: 'open',
  code: 'EACCES',
  path:
   '/Users/edapiyo/Library/Preferences/sao-nodejs/config.json.3385132208' }
    at sao.run.catch (/Users/edapiyo/.config/yarn/global/node_modules/create-nuxt-app/cli.js:46:17)
```

以下で解消できた。
```
sudo rm -rf /Users/edapiyo/Library/Preferences/sao-nodejs/
```

**リンク**
https://github.com/nuxt/create-nuxt-app/issues/371
[Vue.js 現在時刻の表示 ~時計~](https://qiita.com/ron-Qiita/items/17af311a506d08b7bf14)

## 11日目: 2020年4月25日

0.5H / total:9.0H

**今日の進捗**: 100DaysOfCodeのProjectをfork

**思ったこと**: ハッシュタグになんとなく便乗していたがちゃんとルールに乗っとった方が良いと思い、記録をここに書いていこうとおもう。
今鍵垢のtwitterに記録を投稿しているが正直Webエンジニアの初歩的なことをやっているので恥ずかしい。
もっと言うとSIerエンジニアなのでdisられるんじゃないかと言う恐怖みがある。
収入がどうとかそう言う話でなく、組織に依存せず自分で自走できるようになりたいと言うのが今考えている生き方。キャリアとかぼんやりしている。

**リンク** 

[I've joined the #100DaysOfCode Challenge](https://github.com/kallaway/100-days-of-code)

[#100DaysOfCode の始め方とルールについて](https://qiita.com/akihanari/items/fc24d2faf88c8f768cdf)

## Day10: はじめてのFirebase Hosting
1.5H/ total 8.5H

**Done**
- Twitterアカウントを作る
- Twitter API申請（まだやってなかった）
- Firebase HostingでNode.jsのアプリを動かす
**ToDo**
- Day7までに作っていたアプリにメールアドレス認証機能をつける


## Day9: 早速サボる
2.0H/ total 7.0H

二日サボりましたが再開
**Done**
- Firebaseでプロジェクトを１個作る
- Firebaseでメールアドレス認証できるようにする
**ToDo**
- FirebaseでTwitter認証できるようにする


## Day8: 投稿後の記事にアーティスト名を表示させる
0.2H / total 5.0H

今日は休みの日にしたので明日から頑張る・・・（やらなくなりそうな予感

**Done**  アーティスト名を追加
**ToDo**
-  今作ってるプロジェクトの階層を整理
-  FirebaseでOAuthのチュートリアルを探してやる


## Day7: 投稿後の記事の日本語化
0.3H/ total 4.8H

仕事一区切りついたので今日は若干おやすみで簡単なとこだけやりました。

**Done**
- Boardを整理
- 投稿後の記事の日本語化
**ToDo**
- いろいろ調べているとFirebaseでOAuthやるのが個人開発では最短でいけそう
- チュートリアル選定し消化


## Day6: 記事投稿部分の日本語化
0.5H/total 4.5H

今日は元気がないのでほんの数行だけ

**Done**
- 記事投稿部分の日本語化
**ToDo**
- backendとfrontendを１個のプロジェクトにする
- コード進行をMarkdown的に書く方法を調べる
- 投稿後の見栄えの調整
- 利用者の名前に日本語を登録する

## Day5: バックエンドとの結合
0.5H/total 4.0H

**Done**
- backend(Express+mongoDB)とfrontend(Vuetify)の結合
- 新規登録画面の日本語化

**ToDo**
- 記事投稿部分の日本語化
- 利用者の名前に日本語を登録できるようにする
- backendとfrontendを１個のプロジェクトにする

## Day4: Express+mongoDB環境を構築
0.5H/total: 3.5H

**Done**
- RealWorldのバックエンドをmongoDBとExpressに暫定で決める
- mongoDBインストールbackendサンプルを構築
- API仕様に基づいてユーザ追加ができることを確認（写真
- GitHubにレポジトリ登録

**ToDo**
- フロントエンドと結合

## Day3: ロゴを作ってのせる 
1.0H/total: 3.0H

**Done**
- ロゴをここで作る
https://designevo.com/jp/logo-maker/
- ロゴをトップ画面に配置
プロジェクト直下のpublicに画像を置くとimgタグからアクセスできた

**ToDo**
- バックエンド選定
-いずれかのサーバにデプロイ


## 2020年4月11日　Day 2: 続けたいけど３日坊主で終わるかも

**Done**
- RealWorldをfork タイトルを編集
- MITライセンスの著作権表示場所について調査
- タイトルロゴを置きたい場所を特定

**ToDo**
- タイトルロゴを作る
- タイトルロゴを置く









