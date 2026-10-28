# Chrome DevTools MCP (Monetized)

> Chrome DevTools Protocol MCP server for browser automation, debugging, and performance profiling with autonomous x402 pay-per-call rails.

[![Smithery](https://img.shields.io/badge/Smithery-Verified-blue)](https://smithery.ai)
[![Glama](https://img.shields.io/badge/Glama-Compatible-green)](https://glama.ai)
[![PulseMCP](https://img.shields.io/badge/PulseMCP-Listed-orange)](https://pulsemcp.com)
[![LangChain](https://img.shields.io/badge/LangChain-Compatible-purple)](https://langchain.com)
[![AgentOps](https://img.shields.io/badge/AgentOps-Integrated-red)](https://agentops.ai)
[![mcp.so](https://img.shields.io/badge/mcp.so-Registered-teal)](https://mcp.so)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## @monetize
This MCP server is x402-enabled and monetized via [NanoEmpire Trust Manifests](https://www.nanoempireai.com).
It supports **autonomous pay-per-call micropayments** via Solana USDC ($0.01/call) and **instant trial onboarding**.

### Claim 50 Free Trial Credits
Test this MCP server immediately without adding a payment method:
```bash
curl -X POST https://www.nanoempireai.com/v1/trial \
  -H "Content-Type: application/json" \
  -d '{"target": "chrome-devtools-mcp"}'
```

### Installation

#### Via Smithery
```bash
npx -y @smithery/cli install chrome-devtools-mcp --client claude
```

#### Via uv / Python
```bash
uv run server.py
```

### Tool Inventory
- **`chrome_navigate`**: Navigate to any URL in Chrome via CDP.
- **`chrome_screenshot`**: Capture high-resolution viewport screenshots.
- **`chrome_evaluate`**: Execute JavaScript in page context.
- **`chrome_network_log`**: Extract network requests and responses.

### Machine-to-Machine Specifications
- **Manifest:** [https://www.nanoempireai.com/llms.txt](https://www.nanoempireai.com/llms.txt)
- **x402 Spec:** [https://www.nanoempireai.com/.well-known/x402](https://www.nanoempireai.com/.well-known/x402)
- **Developer:** Rob Lambert ([@roblambert9](https://github.com/roblambert9))
