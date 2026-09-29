English

yakusho-rag is a production-grade, asynchronous Retrieval-Augmented Generation (RAG) microservice designed specifically for parsing, indexing, and querying Japanese municipal handbooks, administrative guidelines, and civic publications.
Built with an event-driven architecture (S3 $\rightarrow$ SQS $\rightarrow$ Background Worker) and powered by FastAPI, pgvector, and AWS Bedrock, it addresses the unique challenges of Japanese civic documentation—including complex multi-column layouts, tabular data, and non-whitespace boundary splitting.

日本語

yakusho-rag は、自治体（市区町村・都道府県）が発行する各種行政手引きや生活ガイドブック、お知らせPDFを正確に解析・検索・回答するための非同期RAGマイクロサービスです。イベント駆動型パイプライン（S3 $\rightarrow$ SQS $\rightarrow$ ワーカー処理）と FastAPI、PostgreSQL (pgvector)、AWS Bedrock を採用。
段組みや表組み、日本語特有の文境界・約物処理といった、従来のRAGパイプラインが直面する課題を解決するために設計されています。
