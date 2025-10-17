Team: 10 | Members: Sridhar Surapaneni, Narendra Iyer, Balaji Rao

Project Overview
We implement an Investment Research Agent that:

Plans research steps for a given stock symbol.
Uses tools dynamically (Yahoo Finance, News ingestion, FRED).
Self-reflects on outputs (Evaluator–Optimizer loop).
Retains lightweight memory across runs to improve future analyses.
Workflow Patterns Demonstrated
Prompt Chaining: Ingest News → Preprocess → Classify → Extract → Summarize
Routing: Direct items to specialist analyzers (news, earnings, macro).
Evaluator–Optimizer: Generate → Evaluate quality → Refine using feedback.
