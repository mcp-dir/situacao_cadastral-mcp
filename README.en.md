# Situação Cadastral

### Situação Cadastral for Claude, ChatGPT and AI agents

Check the registration status of a Brazilian CPF against official sources (name, status, birthdate, enrollment, deceased flag). Platform-hosted, no credentials, pay per query with prepaid credit.

- 📊 **1 tool**
- 🔒 **Read-only**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Magic-link login (no password)**

[Portuguese version](README.md) · [Full docs (PT-BR)](docs/)

---

## One-click install

### Claude (Web and Desktop)

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

Manual: [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → name `Situação Cadastral`, URL `https://api.mcp.ai/p_situacao_cadastral`.

### Cursor

[➕ Install in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=situacao_cadastral&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9zaXR1YWNhb19jYWRhc3RyYWwifQ==)

### VS Code (Copilot Chat)

[➕ Install in VS Code](vscode:mcp/install?name=situacao_cadastral&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_situacao_cadastral%22%7D)

### Any other MCP-over-HTTP client

```
https://api.mcp.ai/p_situacao_cadastral
```

---

## 1 tool

| Tool | Description |
|---|---|
| `situacao_cadastral_cpf` | Consulta a situação cadastral de um CPF (nome, situação, data de nascimento, data de inscrição e indicação de óbito). |

---

## Pricing

See [docs/precos.md](docs/precos.md) (PT-BR).

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_situacao_cadastral` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
