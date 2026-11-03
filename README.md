# Sagnik Chakraborty

Agentic AI Engineer based in Bengaluru, India. I build production LLM agent systems: orchestration harnesses, tool calling, failure recovery, agent memory, evals and multilingual voice for Indic languages. Previously at Reliance Jio (BharatIQ), Walmart Global Tech, Dremio and Amazon.

## Focus areas

- Agent orchestration and custom harness design, tool/function calling, MCP
- Multimodal and multilingual voice agents (Hindi, English, Hinglish)
- RAG, embeddings and vector databases (Qdrant, Pinecone)
- Agent evaluation: golden datasets, LLM-as-a-judge, model benchmarking
- LLMOps: LLM gateways, cost attribution, latency, observability

**Stack:** Python, FastAPI, LangGraph, LangChain, Google ADK, Java, Go, GCP, AWS, Kubernetes

## Projects

- **[WordHunt](https://github.com/sagnik31/word-hunt)**: a word-guessing game scored by semantic similarity between words.
- **[Med-Sum](https://github.com/sagnik31/med-sum)**: a retrieval-augmented app that summarises medical records.

## Open-source contributions

**Apache Arrow, Gandiva (C++)**: 14 commits merged upstream, 2020–2021 ([view all](https://github.com/apache/arrow/commits?author=sgnkc))

Gandiva is Arrow's LLVM-based expression compiler. While at Dremio, I implemented and fixed SQL functions in it:

- **String functions:** `trim`, `ltrim`, `rtrim`, `btrim`, and `concat()` for up to 10 arguments ([ARROW-9099](https://github.com/apache/arrow/commit/4b8cbee11735d7a97a6150938fbee8fba95d8d9e), [ARROW-9328](https://github.com/apache/arrow/commit/baf20948d0057b1390366e6e08f4c05fe8aaafc2), [ARROW-10050](https://github.com/apache/arrow/commit/3fae71b10c420f7a12b73d71fe29968c4b9ce8e5))
- **Math:** `round()` for integers, longs, floats, doubles and decimals, including a single-argument form ([ARROW-9640](https://github.com/apache/arrow/commit/c5fa23ea0e15abe47b35524fa6a79c7b8c160fa0), [ARROW-9641](https://github.com/apache/arrow/commit/3f3b60412fc53598c84280b3fd16317546b9f22f), [ARROW-10234](https://github.com/apache/arrow/commit/8bbfdc42f529bcef80b31cbe2373f0132249f610), [ARROW-10310](https://github.com/apache/arrow/commit/6ad24c2ae89a9b57ffca74d5f8ccfb1ee6c3d20c), [ARROW-11614](https://github.com/apache/arrow/commit/3a0eafa979f3cba9daa1bc477ee923b75766da3a))
- **Bitwise operations:** `bitwise_and()`, `bitwise_or()` and `bitwise_not()` ([ARROW-9607](https://github.com/apache/arrow/commit/52cb9cb19da4f0b52801f84757d37c8281165e85))
- **Dates, times and casts:** `castTIMESTAMP(int64)`, a bool-to-varchar cast, and a month-end fix for `timestampdiff()` ([ARROW-9795](https://github.com/apache/arrow/commit/52e2c75329470ad0c77dea5e39f486927b0d1ba4), [ARROW-10895](https://github.com/apache/arrow/commit/9d86440946b8b07e03abb94fad2da278affae08f), [ARROW-9501](https://github.com/apache/arrow/commit/423d5e71cfbe3159349b2852650ffa51a507a78c))
- **Build:** fixed a `signbit` compilation failure in the Ubuntu nightly build ([ARROW-11639](https://github.com/apache/arrow/commit/aeb6c04ebf12e441b31e860d70e083ed61adea49))

These were contributed from my former work account, [@sgnkc](https://github.com/sgnkc), which I no longer have access to.

## Contact

sagnik31@gmail.com · [LinkedIn](https://www.linkedin.com/in/chakrabortysagnik)
