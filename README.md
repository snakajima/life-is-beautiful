# Life is beautiful: アイデアソン、~~ハッカソン~~コントリビューション・フェス

このイベントは、メルマガ「[週刊 Life is beautiful](https://www.mag2.com/m/0001323030)」が2025年で足かけ15年を迎えることを記念して行う、読者向けのアイデアソン・ハッカソンです。

## アイデアソン（締め切り：2024年12月31日）

アイデアソンは、エンジニアでない方も参加出来るイベントで、「AIを活用した、AI-nativeな製品やサービス」の企画を考えていただき、
（ChatGPTなどを活用して）プレスリリースの形にした上で、このリポジトリのIssueとして投稿していただくものです。

以下が手順です。

1. 「AIを活用した、AI-nativeな製品やサービス」の企画を考える
2. そのアイデアをChatGPTなどのLLMに説明した上で、プレスリリースの形に仕上げてもらう。
3. github.com にアカウントを作る（まだ持っていない人）
4. 作ったプレスリリースを、[このリポジトリ](https://github.com/snakajima/life-is-beautiful)のissueとして投稿する

Issueの投稿は、[このリポジトリ](https://github.com/snakajima/life-is-beautiful)をブラウザーで開いた上で、画面上位に表示されている"Issues"タブをクリックした上で、
右手にある、"New Issue"ボタンを押して、投稿して下さい。

- 締め切りは2024年12月31日ですが、早めに投稿していただいて、後から変更することも可能です。
- 投稿すべきプレスリリースのサンプルは、[こちら](https://github.com/snakajima/life-is-beautiful/issues/1)に用意したので、参考にして下さい。アイデアを与えて、ChatGPTに書かせたものです。
- 投稿したプレスリリースは、誰にでもアクセス可能なオープンなものになるので、機密情報などは含めないでください。
- 一人で複数のエントリーを投稿することが可能ですが、それぞれを独立したIssueとして投稿して下さい。
- 対象は原則として私のメルマガの読者ですが、それ以外の人も投稿可能です。
- Issueにはコメントが投稿出来るようになっているので、そこで他のユーザーとコミュニケーションしていただいても結構です。
- 入賞作品は、私（中島聡）がシンギュラリティ・ソサエティのメンバーからのアドバイスをもらいながら決めます。
- 入賞作品の発表は、このリポジトリ、および、メルマガで行います。
- 入賞者には、賞品としてApple Mac mini(2024年モデル、M4 Pro、メモリ64GB、本体のみ：キーボード・ディスプレイは別途必要)をお渡しします。
- 入賞作品は応募総数次第ですが、１〜２個、選ぶ予定です。
- 商品を受け取る際には、その時点で、メルマガの会員である必要があります。

## ~~ハッカソン~~コントリビューション・フェス（締め切り：2025年3月中旬）

コントリビューション・フェスは主にエンジニア（もしくは勉強中の人）向けのイベントです。詳細は徐々に詰めていきますが、現時点では、以下のことが決まっています。

1. [GraphAI](https://github.com/receptron/graphai)を活用した製品・サービス（プロトタイプも可）をオープンソースな形で作っていただきます。
2. ハッカソンのように1日で作るのではなく、11月末から3月半ばまでの４ヶ月間の期間で行います。
3. お題としては、以下の５つがあります（詳しくは下記）。
   1. GraphAIそのもの（オープンソース・プロジェクト）
   2. AI-native 音声版 Instagram（プロダクト開発）
   3. GraphAIのWebインターフェイス（オープンソース・プロジェクト）
   4. GraphAIアプリを自動生成するGraphAIアプリ（研究）
   5. AI-native辞書（プロダクト開発）
5. MITライセンスのオープンソースで作っていただきます。
6. 賞品は、Apple Mac mini（2024年モデル、M4 Pro、メモリ64GB、本体のみ：キーボード・ディスプレイは別途必要）です。４台、用意してあります。
7. 応募の締め切りは３月上旬を予定しており、3月下旬（22日か23日）にイベントを行う予定です。
8. 個人・グループ・法人のいずれでも応募が可能です。

なので、今のうちに、GraphAIの勉強をしておいて下さい。

GraphAIの勉強した内容や、開発中のGraphAIのtipsをzennやqiitaに投稿していただけると、ハッカソンでの審査でその過程を考慮します。投稿時にはtagでGraphAIとつけてください。

### GraphAIそのもの

to be filled

### AI-native 音声版 Instagram

最新のAI技術を活用することにより、誰でも簡単にpodcastを配信することが出来るサービスと、Tiktokのように自分に適したpodcastを簡単に楽しむことが出来る専用アプリの組み合わせで、「音で情報を得る・学ぶ・楽しむ」時代を加速するサービス＋アプリです。ベースになるアプリは既にオープンソースで作ってあるので([AI Podcaster](https://github.com/snakajima/ai-podcaster))、これを活用して開発していただければ良いと思います。

### GraphAIのWebインターフェイス

GraphAIは、OpenAI、Claudeなどのサービス型のLLMだけでなく、Ollamaで走るローカルなLLMを使うことも可能ですが、Ollama向けのオープンソースなWebUIをGraphAIを使って作り、簡単に実験・テストできるだけでなく、様々なアプリも作れる環境を作りたいと考えています。

GraphAIをWebUI上で動かす仕組みは、以下のものがあるので、これをベースにしてもらっても良いし、新たなものを作っていただいても結構です。
- [VueベースのWebUI](https://github.com/receptron/graphai-demo-web)
- [litegraphを使ったもの](https://github.com/receptron/graphai-litegraph)
- [サーバのagent list api を叩いて動的に利用可能なagentのリストを取得する仕組み](https://github.com/receptron/graphai-playground)、サーバー側は[こちら](https://github.com/receptron/graphai-agent-server)
- ReactでCytoscapeを使いたい場合は、[こちら](https://github.com/receptron/graphai-utils/tree/main/packages/react-cytoscape)を参照してください。 
### GraphAIアプリを自動生成するGraphAIアプリ

To be filled.

### AI-native辞書

To be filled.



