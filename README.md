# iOSDC2020-Talk-Sample

## 概要

iOSDC 2020「GitHub ActionsでiOSアプリをCIする個人的ベストプラクティス」レギュラートーク（以下、単に「トーク」と呼ぶ）のサンプルリポジトリです。

## 本リポジトリの使い方

本リポジトリの `main` ブランチには、ビルドが通るiOSアプリのソースのみ含まれています。

トークはハンズオン形式です。  
タスクランナーとGitHub Actionsのワークフローを作成し、iOSアプリのCI環境を構築して実行まで行います。

トークに沿って実際に手を動かし、CIのメリットを実感しましょう！

1. 本リポジトリをフォークします。  
![](./Docs/Images/Fork.png)

2. フォークしたリポジトリをクローンします。

```
$ git clone https://github.com/{GitHubのアカウント名}/iOSDC2020-Talk-Sample.git
$ cd iOSDC2020-Talk-Sample
```

3. トークに沿って `Makefile` を作成し、コミットしてプッシュします。  
自分で実装するのが手間な人は `answer` ブランチからコピペしてください。  
https://github.com/uhooi/iOSDC2020-Talk-Sample/blob/answer/Makefile

4. トークに沿って `.github/workflows/main.yml` を作成し、コミットしてプッシュします。  
`Makefile` と同様、 `answer` ブランチに答えがあります。  
https://github.com/uhooi/iOSDC2020-Talk-Sample/blob/answer/.github/workflows/main.yml

5. プッシュをトリガー（きっかけ）にCIが実行されるので、「Actions」タブから結果を確認します。  
![](./Docs/Images/Actions.png)

6. CIが成功していればOKです！

## お問い合わせ

ハンズオンに行き詰まった、CIが失敗するなどの理由で問い合わせたい場合、Twitterの [@the_uhooi](https://twitter.com/the_uhooi) までご連絡ください。

## おわりに

かなり頑張ってサンプルリポジトリを作ったので、スターください！
