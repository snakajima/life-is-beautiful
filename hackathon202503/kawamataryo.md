# 🛠️ [Kawamataryo](https://github.com/kawamataryo)'s Contribution

## 公式ドキュメントの整備
GraphAIの公式ドキュメントの基盤をVitepressで作成しました。既存のDocsを組み込むだけでなく、i18nへの対応やGraphAI関連のZenn記事を自動で取り込む仕組みも整備しました。

- [#977 Setup official document](https://github.com/receptron/graphai/pull/977)
- [#981 Add tutorial template for ja and fix edit link](https://github.com/receptron/graphai/pull/981)
- [#984 Change vitepress root](https://github.com/receptron/graphai/pull/984)

<img src="https://github.com/user-attachments/assets/053b4438-2812-44d8-84d5-f4f3e1bcf4d3" width="700">

## GraphAI Visualizerの開発

JSON、YAMLで書かれたGraphAIの定義理解を容易にするため、GraphAIのグラフ構造をVS Code上で可視化する拡張機能を開発しました。

- [GraphAI Visualizer](https://marketplace.visualstudio.com/items?itemName=kawamataryo.graphai-visualizer)
- [VSCode Extension](https://marketplace.visualstudio.com/items?itemName=kawamataryo.graphai-visualizer)

<img src="https://github.com/user-attachments/assets/d83aae3f-786e-4f3d-bd29-f3687d23b7a8" width="700">

## GraphAIチュートリアルの整備
GraphAIのチュートリアル上の動作しないAgent（slashGPTAgent, bypassAgent）の問題を修正しました。

- [#939 Replace non-working agent](https://github.com/receptron/graphai/pull/939)

## Brave Search Agentの開発
GraphAIで使えるWEB検索のAgentが欲しいと考え、Brave Search Agentを開発しました。

- [#18 Add brave search agent](https://github.com/receptron/graphai-agents/pull/18)

## Browserless Agentの開発
SPAなどJS依存のWEBページの情報もGraphAIで扱えるように、[Broserless.io](https://docs.browserless.io/)を手軽に使えるAgentを開発しました。

- [#10 Add browserless agent](https://github.com/receptron/graphai-agents/pull/10)
- [#12 Fix apikey handling](https://github.com/receptron/graphai-agents/pull/12)]
- [#13 Add browserless agent](https://github.com/receptron/graphai-agents/pull/13)
- [#16 Update browserless_agent to return text in object](https://github.com/receptron/graphai-agents/pull/16)
- [#17 Fix type and params in browserless agent](https://github.com/receptron/graphai-agents/pull/17)

## READMEの整備
リポジトリの印象を良くするために、READMEにロゴやshields.ioのバッジを追加し見栄えを整えました。

- [#999 Enhance README appearance](https://github.com/receptron/graphai/pull/999)
