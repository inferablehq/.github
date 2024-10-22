<p align="center">
  <img src="https://a.inferable.ai/logo-2.png" width="200" style="border-radius: 10px" />
</p>

# Inferable

[![Documentation](https://img.shields.io/badge/docs-inferable.ai-brightgreen)](https://docs.inferable.ai/)
[![Slack](https://img.shields.io/badge/slack-join_chat-brightgreen)](https://join.slack.com/t/inferablecommunity/shared_invite/zt-2n61s5fp0-ieB9e~iLQqUKmHWBxPgheA)

Inferable is a developer platform that allows you to build secure, agentic workflows from your existing code via Functions or Rest/GraphQL APIs.

## Getting Started

The fastest way to get started with Inferable is using our CLI:

```bash
# Install the Inferable CLI
npm install -g @inferable/cli

# Bootstrap a new project
inf bootstrap --cluster node

# Start your service
cd inferable-app && npm run dev
```

## SDKs

Inferable provides SDKs for multiple languages:

| Language | Status | Repository |
|----------|---------|------------|
| Node.js | General Availability | [inferable-node](https://github.com/inferablehq/inferable-node) |
| Go | Beta | [inferable-go](https://github.com/inferablehq/inferable-go) |
| .NET | Beta | [inferable-dotnet](https://github.com/inferablehq/inferable-dotnet) |
| Bash | Demo Only* | [inferable-bash](https://github.com/inferablehq/inferable-bash) |

\* *The Bash SDK is a demonstration project to show HTTP-based integration possibilities. Not recommended for production use.*

## Enterprise Features

### Sentinel

[Sentinel](https://github.com/inferablehq/sentinel) is our open-source, low-latency tokenization proxy designed to achieve complete data localization when interacting with external servers. It allows enterprise customers to:

- Mask all data sent to Inferable control-plane
- Guarantee zero-retention of private data
- Audit all traffic between services and the Inferable API

## Documentation & Resources

- [Official Documentation](https://docs.inferable.ai)
- [API Reference](https://docs.inferable.ai/pages/api)
- [Quick Start Guide](https://docs.inferable.ai/pages/quick-start)
- [Architecture Overview](https://docs.inferable.ai/pages/architecture)
- [Security](https://docs.inferable.ai/pages/security)

## Key Features

- 🔒 **On-premise execution**: Functions run entirely within your infrastructure
- 🔐 **Private networking**: Outbound-only connections, no inbound traffic required
- 🚀 **Multi-language support**: Node.js, Go, and .NET SDKs available
- 📊 **End-to-end observability**: Complete visibility into your workflows
- 🔍 **Distributed orchestration**: Reliable message queue for function execution
- 🛡️ **Enterprise-ready**: Built with security and compliance in mind

## Community & Support

- [Join our Slack Community](https://join.slack.com/t/inferablecommunity/shared_invite/zt-2n61s5fp0-ieB9e~iLQqUKmHWBxPgheA)
- [Blog](https://inferable.ai/blog)
- Email: hi@inferable.ai
