# ScopeVeil

**Privacy-first cost and latency observability for LLM apps.**

We ship two products that share one principle: collect what you need, never the prompt itself.

## Products

- **[Gateway](https://scopeveil.com)**: OpenAI-compatible LLM gateway with prepaid passthrough billing. Pay upstream cost plus a small markup (5 to 15 percent based on tier). Double-entry ledger, reconciled against the real upstream charge.

- **[SDK](https://github.com/scopeveil/sdk)**: wraps your existing OpenAI, Anthropic, Google, Mistral, Cohere, Ollama, or Bedrock client. Ships only metadata: model, token counts, latency, status, tool calls. Prompt content and completion text never leave your process.

## Why open source the SDK?

Anyone running an LLM in production has to trust that the observability vendor is not reading the prompts. The most credible answer is to make the collection layer auditable. The SDK is MIT-licensed and its privacy guarantees are enforced by automated tests.

If you find a way to leak prompt content through the SDK, please open an issue.

## Links

- Website: [scopeveil.com](https://scopeveil.com)
- Pricing: [scopeveil.com/pricing](https://scopeveil.com/pricing)
- Privacy: [scopeveil.com/privacy](https://scopeveil.com/privacy)
- Security: [scopeveil.com/security](https://scopeveil.com/security)
- API docs: [scopeveil.com/docs/api](https://scopeveil.com/docs/api)
- Blog: [scopeveil.com/blog](https://scopeveil.com/blog)
