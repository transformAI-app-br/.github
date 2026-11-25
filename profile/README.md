# transformAI.app.br

dados → inteligência → valor

Servidores MCP abertos sobre dados públicos brasileiros. Cada resposta traz a procedência, para que qualquer número possa ser refeito na fonte oficial.

| Servidor | Dados | Endereço |
|---|---|---|
| [**comexstat**](https://github.com/transformAI-app-br/mcp-comexstat) | Comex Stat (MDIC): exportações e importações do Brasil desde 1997 | `https://transformai.app.br/mcp/comexstat` |
| [**cnpj**](https://github.com/transformAI-app-br/mcp-cnpj) | CNPJ (Receita Federal): 74,4 milhões de estabelecimentos, atualizado todo mês | `https://transformai.app.br/mcp/cnpj` |

```sh
claude mcp add --transport http comexstat https://transformai.app.br/mcp/comexstat
claude mcp add --transport http cnpj https://transformai.app.br/mcp/cnpj
```

[API](https://transformai.app.br/api/) · [Blueprints](https://transformai.app.br/blueprints/) · [Base aberta do CNPJ](https://huggingface.co/datasets/transformai/cnpj) · [transformai.app.br](https://transformai.app.br/)
