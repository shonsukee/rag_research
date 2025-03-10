# ■ Resource
## ▶︎ RAG
1つのDBを利用したRAG手法です

- main.py
    - RAGの一連処理を管理

### ▼ data
RAGで利用するデータに関連するディレクトリ
- prompt_template.txt
    - LLMへ入力するプロンプトテンプレートを保持

### ▼ embeddings
埋め込み処理に関連するディレクトリ
- store_knowledge.py
    - 埋め込み処理を行った外部情報をDBへ保存

### ▼ models
LLMに関連するディレクトリ
- config.py
    - LLMの設定
- generate_response.py
    - 回答の生成
    - プロンプトテンプレートを使用

### ▼ scraping
外部情報のスクレイピングに関連するディレクトリ
- fetch_data.py
    - 仕様書のスクレイピング
- preprocess_data.py
    - 取得した仕様情報の前処理
- fetch_buggy_code.py
    - API誤用を含むデータセットのスクレイピング
