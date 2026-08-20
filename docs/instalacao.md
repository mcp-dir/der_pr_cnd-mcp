# Instalação detalhada

DER PR: Certidão Negativa de Débitos é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_der_pr_cnd`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_der_pr_cnd` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_der_pr_cnd` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_der_pr_cnd` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.der_pr_cnd` (ou `servers.der_pr_cnd` no VS Code) do config do cliente e reinicie.
