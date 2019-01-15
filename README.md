# 満行研究室 筋力トレーニング

## はじめに

「**筋肉は裏切らない**」

これは世界の真実である。個人的にはNHKの[みんなで筋肉体操](https://www.youtube.com/watch?v=IHYOhDe4FB8)に出ている武田真治を圧倒的リスペクトしている。筋肉を鍛えれば、あらゆる局面でパワープレイが選択可能になる、代謝が上がり結果としてダイエットにも効果がある、なんとなく自信がつく、などその効果は計り知れない。武田真治もまた、みんなで筋肉体操だけでなく、本業の俳優はもちろんのこと、趣味のサックスも[プロレベル](https://www.youtube.com/watch?v=Ma5xXTEMBJs)であるなど、まさに圧倒的リスペクトに値する人物であることには疑いようがない。これも、鍛えられた筋肉をベースとした不断の努力・鍛錬の賜物であることは容易に想像できる。

さて、皆さんには打ち込める趣味はあるだろうか？ある分野・種目で他の人よりも優れた成果を出すためには、ベースとなる「筋肉」が不可欠である。例えば、野球のバッティングであれば一糸乱れぬ完璧なバッティングフォームが理想であるが、それを実現するためのベースとして、ボールの勢いに負けないパワーと狙ったところでスイングをする正確性が必要となる。これらは日頃の鍛錬を積んでいないと決して手に入るものではなく、またこのベースとなる「筋肉」なくして、一糸乱れぬバッティングフォームを身につけるのは不可能である。

仕事や研究についてはどうだろうか？分野にもよるだろうが、これからの時代ではコンピュータをいかに使いこなすかが一つの重要な「筋肉」であることに疑いの余地はないであろう。大量の情報を以下に素早く・簡単にかつ正確に処理するかによって、個々のパフォーマンスは大きく変わってくる。

ここでは、主に満行研究室に新しく参加する人向けへ、満行研究室における「筋力」トレーニングを提供する。

## 方針

- 研究プロジェクトによって必要な技術(プログラミング言語など)は異なってくるが、今回はベースとなる「筋力」を鍛えることを目的とする
    - 今回はプログラミング言語はPythonに限定する
    - プログラミング言語の習得だけでなく、Webサービスの有効活用やコンピュータの基礎的な理解が必要なトレーニングにしたいという意図で作成

- 相談OK。カンニングはOKだが、中身を理解し技術を身につけるのが目的なのでコピペはNG。
    - 困ったら、用語やエラーメッセージを解読して、調べる
    - 10分調べてわからなかったら周りに聞く
        - 理論や数式の理解なら別だが、細かな技術なら迷う必要なし！！
        - それでもわからなかったら満行に聞く。悶々とする時間は無駄！！
        - ただし、解決したら何らかの形で困ったことと解決方法を記録し、可能な限り研究室内でシェアすること！！

- 初めての取り組みなので、課題実施にあたっていろいろとトラブルが出るかもしれないので、そのたびに満行に連絡してくれると嬉しいです
    - 授業ではないので、完璧ではない（むしろ穴だらけ疑惑が高いです）

## 筋力トレーニングメニュー

### 基礎トレーニング

1. Gitのお勉強
    - GitはITにおける重要なツール/技術である
    - GitのWebサービスであるGitHubを含めて使いこなせるようになるべき
    - 具体的には、[ドットインストール](https://dotinstall.com/lessons/basic_git)で勉強する
        - この講座は無料なのでおすすめ
1. Pythonのお勉強
    - 研究室共通の言語として設定する
    - [Progate](https://prog-8.com/)や[ドットインストール](https://dotinstall.com/lessons/basic_python_v3)で勉強する
        - これらは有料だが、どちらか一方だけ1ヶ月だけお金を払って勉強する価値はあると個人的には考えている（ただし自己判断で良いかと）
1. [研究室のネットワーク環境](https://github.com/mitsuyukiLab/lab-operation/wiki/%E7%A0%94%E7%A9%B6%E5%AE%A4%E3%82%A4%E3%83%B3%E3%83%95%E3%83%A9%E3%81%AE%E8%A8%AD%E5%AE%9A)について理解する
    - 設備を含めてぜひ利用しまくってください。改善要望はバシバシ募集中です！！！
1. (補足)UNIXコマンドについても知らなければ理解しておくといいかも
    - tigers操作のときに役に立つ
    - [ドットインストール](https://dotinstall.com/lessons/basic_unix_v2)で無料で授業を受けられます

### 応用トレーニング

- [tigers](https://github.com/mitsuyukiLab/lab-operation/wiki/tigers-(133.34.37.147))上でトレーニングメニューをこなす
    
    - muscle00からmuscle05は必須トレーニング, muscle06以降は割と難しいかもしれませんが、ぜひトライしてください

    - やり方
        1. tigersにおける自分のアカウントの設定を行う
            - tigersにssh接続をしホームディレクトリ直下にnotebooksというディレクトリを作成する
                - 自分自身の環境にこだわりたい人は、[クライアント側の設定](https://github.com/mitsuyukiLab/lab-operation/wiki/tigers-(133.34.37.147)#%E3%82%AF%E3%83%A9%E3%82%A4%E3%82%A2%E3%83%B3%E3%83%88%E5%81%B4%E3%81%AE%E8%A8%AD%E5%AE%9A)を参考に自分自身の仮想環境を設定すると良い
            - 加えて、ssh接続した環境下でGitの設定を行っておくこと
                - `git config --global user.name "First-name Family-name"`
                - `git config --global user.email "username@ynu.jp"`
        1. このrepositoryを自分のアカウントにForkし、それをtigers上の自分のホームディレクトリ直下に作成したnotebooks(`~/notebooks`)上でcloneする
            - mitsuyukiLab上のrepositoryではなく、Forkした自分のアカウント上のrepositoryをcloneすること!!!
                - 参考 : [Forkとは？](http://cuaoar.jp/2013/03/github-fork-pull-request.html)
            - その後、Forkした自分のアカウント上のrepositoryにて、Collaboratorに満行を追加する
                - Setting -> Collaborators & teams から、taiga4112をこのレポジトリのCollaboratorとして追加する
            - tigers上でssh公開鍵を作成し、GitHubの自分のアカウントに登録する([参考](https://github.com/mitsuyukiLab/muscle_training))
                - Ubuntu OSにssh接続しているので、公開鍵のコピー方法のみについては[リンク先](https://stackoverflow.com/questions/16638092/copying-a-rsa-public-key-to-clipboard)を参照のこと
        1. キリがいいところでcommitして作業記録を残す、pushでGitHubレポジトリを更新するなどを行いましょう
            - 満行は進捗をGitHubレポジトリで確認します
