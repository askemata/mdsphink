# Configuração

O Kite lê configurações de um arquivo `kite.config.json` na raiz do projeto.

```json
{
  "output": "dist",
  "watch": true,
  "plugins": []
}
```

## Opções disponíveis

- **output** — pasta de saída dos arquivos gerados
- **watch** — reconstrói automaticamente ao detectar mudanças
- **plugins** — lista de plugins habilitados

:::note
Variáveis de ambiente prefixadas com `KITE_` sobrescrevem o arquivo de configuração.
:::
